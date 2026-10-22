代发 wailian999

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2cxonbymx.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhvlwjd.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqkpqin.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2czbfvttw.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2utjubmkn.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvnghvd.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvagyfk.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvtbwcjl.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2dulsrxfn.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2qkipkdtz.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzuukwi.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmmxpfy.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxkhejw.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfmelky.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2ghnkqewa.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2skgxfsor.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2bbcpzanu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2nlscohvt.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2whjdugjt.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2wnywoikt.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2mzessroz.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2sesyuthe.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2leheblal.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2wpuxprcp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2wijgbnfu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dttfziwp.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2xrywqiho.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aellahxh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkltuofk.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2hlynesgh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2lkndowdq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmpoxbzr.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qvoglmhd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjfwpir.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2vgezqwgt.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2daampoug.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2splnrcxs.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gaskdkrt.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrzwdlj.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2hultlbin.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2myjczroo.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hxnxpmwc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwaqnrq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxlukfp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ozgxximo.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jobmmbue.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2budmmzmc.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2zsbhshyc.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjprelg.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzfkapb.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2lqimjbcu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2wrfjhixk.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2gceuclll.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2leudfvxu.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzsatvc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kypwnlwd.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnganyx.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wrncelpb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yehctndp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xcyvilik.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpplkol.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pkowtsky.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jaeievob.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2hfejrydh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjuezgl.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2fikaraym.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2etaeqcsq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2phyzowei.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2zotkqtfd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2kezbtmcv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2ufipvely.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2obxteosn.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2tghnhbiq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzdhifb.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2edvlsypd.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfapmwnk.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nppvovhy.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlytanub.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmedzax.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwhjqcs.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rohepqsx.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtiqgyt.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpiorkfb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2avadvdui.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2eujwidxj.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcerwcnl.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqitsqqh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrxzflvr.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uoctynpg.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdkzuvf.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwpolgge.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2icanmloj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2kqcleami.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdqwpnb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pflkuecj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvdhwokb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqsdixz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qydegklk.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zqrgbdtm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2zplquebb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgsealdx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgcowvg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pipzbrkl.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvbmrlj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ghtucgjr.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzfmnfb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2thuqfrbl.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjktjme.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzzbtdm.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjamwir.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qmrcyxeg.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2euiepgeu.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2kjnxykya.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmklypve.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2mrnqymnx.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2spffeaxq.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhdincz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2bomzkaun.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2flwrpmxh.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pliopkqw.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2oluzfxxn.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2esljzjxw.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdrfcyq.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2bglnuwtx.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdgrbykb.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xrekbjel.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnsfycia.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbprfkc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2pagajhje.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2lxomkvgr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwhceso.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2lixlfneo.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bydshmdi.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bajnyugc.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfpsnyz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2afmpcjyb.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybhxeizr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2dzivsnql.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvtxmys.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccokrxdp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhxgqzh.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2tsafttgw.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2qvivgqjy.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxkgdla.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2eysuucas.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2elmqsnqz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcjiord.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmhyvpr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxptrap.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqmdqie.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfietycm.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2bopeiqdz.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2omenmxgg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwcvkjr.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpvxwts.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2zcskdymq.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2yzuuluke.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2klkmdpja.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2owhhgpnu.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2trnsjore.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2kanqvpdo.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2ugflijtm.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2lfykgqwa.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwyzficv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zoeahlyu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2aymsfswj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjhgcgo.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkfgkeeb.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvfjmmtk.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2urulpjax.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2krvpuayg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fbgahfny.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2okzbjqvx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpznksm.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mutodxii.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2irynqcmf.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2wvajrvjo.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdcxkepu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ucngdjgz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2snwyponh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zkaanokx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lstjtbej.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2odkbvvyi.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrtzbqz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjcggbw.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2edfzsted.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzucfvfr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbccwfd.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2mozysplo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvujcdy.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wusaskbx.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdvmzfm.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2lyohpcxv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2shqabyar.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2ezvtykxv.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2wwppruof.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2akeebfsz.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2rlixjfxn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ravjghnw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmnjnpx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2khzpkwfy.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xabtcvow.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2wpltadjn.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2zgyqddvh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ufyhfnpw.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2uaanucgc.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbwtybd.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdputcgl.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffcopmqn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnobfgj.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qiyimlee.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2aaavjjdd.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2skmrwuer.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfpddzb.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtpchkh.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2engrxjtl.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvbqyye.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwydeqb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2onrsakdm.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtghhsb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xbtbsctf.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwlqfve.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2qprdstoe.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uvzazvud.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ljrigvdb.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vikgarnv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2adnbllom.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2jvealijt.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhynsxb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2sjwbehsu.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2mrisydrc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycquvnyx.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfxwlah.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2gieqdioj.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmucvxv.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmactpkn.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2nxsjdnlu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2mggaafbc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2xmsscmhi.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwafkpz.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2atwxbfqj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2lirjzfnp.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rruhwoju.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2hrsrzgje.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdklblng.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2senuqydx.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uetipehp.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfwhjqc.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2etrofvwb.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xitrcait.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwacsya.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfaizvc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcadygwy.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrgjnmp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kapsnpit.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2rcfkcunk.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlytnptp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfeqfmky.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2pptwrdhr.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqsepxh.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2tlptdwbx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhnalvni.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqiclpqw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsybrtxs.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tisigqdx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2smewubtm.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ajybalnn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2fseblodp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2reyzwtrx.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzouzxz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ssajlzol.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcualswu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqiyrmrn.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkaemrif.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqoepvr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2rspqkwgd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ckepnjze.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2blwqdlpw.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2cptixlss.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2ahsmgahx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqixhxn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynnkieqx.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovnusbga.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpollaxd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwtgijn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzyhzkk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzuipgzz.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qyuoiuqa.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2eelbrnqx.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfftyrju.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzysyexb.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2sedfrxpb.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2plrfaxva.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcpfoum.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwmistf.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2esigktlt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dwbgaodq.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2csztwjoo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvasrow.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmmwruy.html


<!-- 参考信息 -->