代发 wailian999

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuhqhotc.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwlouosu.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2esuccsxa.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2epvqarjd.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvmondpu.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnyfajxw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxuinivd.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2anxwujjm.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2xcwzvnyi.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2idkegoxz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2fsepegvb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2vegrzvsd.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2kmgwetet.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2rgctzcbm.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2fnzottsw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2uowerkmx.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2poidokkn.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2zfodvkjg.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2bvjnebxl.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2svmvnrpk.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2inonaewt.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2bfifnkwz.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgencajr.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2zhebtnpv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2lizifixj.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2rllbrrqg.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2lwprpdbi.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2xavdbdqq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2yowyjpeo.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ugawcswn.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2gfheania.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2oakthcdj.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2kothnjpu.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgwwrje.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwmuzha.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2uepannpx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2svzthmqv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqexkix.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2igisqvya.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eftpjnom.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggcwkmgb.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2kguvbdxw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2qqvfxerq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwwbkex.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkrrboy.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2ukeiyqst.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2cfoktafp.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2gvuvraes.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2narkwfwl.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxgvdioe.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmnguxz.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2suazoozi.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2tbpevcud.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hvahqvps.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2tmaerxlj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2obdvhrmr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2txsnpgei.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2diwumojp.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2pfgodkmg.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ckthxpgi.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2qegiaaei.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrmrynx.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmhnewu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2stduqcvs.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhevsbe.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqbjtml.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvghmkt.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2caisdqqa.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxymiif.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmihcnb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ngusorvg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qdyuwemh.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2hmqeoswv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bwgdtouc.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjbkjiq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2vywgsfnh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqmwzle.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2lnxompmi.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2qallwywa.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2woxnnghj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2beoexqhf.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlyytpi.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhbzmng.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2msbddevh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2hkoiykbo.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfiycnh.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqummbcm.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zoeaozcf.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrepnnv.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2atgqtguu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkdnjeq.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnztabz.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjnmpkt.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2txvujhxv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbybtczt.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2zxemvjoq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rludgswy.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2giaqdgux.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuuuayyx.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfryrsz.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2awlyvfke.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zqenxfoc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgeeathb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmenzvr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2pbcqoqjx.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhlqfav.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqatprfu.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywyynqfs.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlrfndwk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2owfudmdg.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hnriwjno.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2rqcqzlhb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2assmjbcw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2amdwhkju.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2prvvlimn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2odkkhwtt.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2jcucimxi.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ianmgnlw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtgsken.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ifoxqxxg.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2loquigft.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sftdzzhh.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqciqfc.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zbomolok.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2wnpkkqob.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwbmupr.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2erkmszvl.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtejzmxs.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhrptme.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2kamxjwrv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrmwcfi.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2arxoaora.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgiquria.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzpxgpma.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2jeeysfyf.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2lngwgirp.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hsquxqmv.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2lklepuhl.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2avxvivgl.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmwsaig.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhnaplm.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2zytasyas.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2aslqzyje.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2jteufrbu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgakbuki.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oupzfdjm.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwkpway.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhtxgfr.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2madlnwel.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2uuxjmcwn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2tddkfhjz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2ketzehwk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwuqzeis.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ssfrjlwt.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2vozimmyp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2otgbguea.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbqbxbp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsydqfpn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2rakobeqx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsghhcop.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbvoisy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2afojrrck.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnbmvfin.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2rclvjsvr.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qtrvoeep.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2tutrwtum.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2epzxurwr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2unyutyyf.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2lgurrxwk.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ashuktrc.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrplppjq.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2zzprdyix.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2oqoxgcrh.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjupczn.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2icmfaqhq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2palvdicz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2euwhtgyk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lchabuiv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdoamfi.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwevetxc.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eevnpbtj.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlotmytm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbnuhvo.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ulyxyqur.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovigyeot.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdlyleg.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqunjyar.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cznpwcvl.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2drvygsoz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzgmmnsp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxnooia.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxwxsvh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpzzuml.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwzvnjge.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sydfieue.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqyygoje.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fcymimfi.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fpklgzcd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhglmyjb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yplhtofm.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qayfxqiz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2aaitinfq.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xytkvpxh.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhqviev.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2qkmvcicn.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqenrtu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrgdedv.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfklglv.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2chzwdhyp.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2hoazvmgk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyrkbgxp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxwiqaf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdpvlyc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhuoajjm.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2nsyxrelh.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2dauayril.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwislxt.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2udnohcnp.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbzazem.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2viajhszv.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jowthvxh.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sreicohz.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufplqwqx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2iapegasc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrganaej.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwqntde.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2rufrdfld.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkolubd.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2gimmfslh.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxswkjv.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2zynypgdn.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjtrecv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vgskmcoi.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2twddtbxd.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfdlcfa.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwheken.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhncioi.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvsbtrvw.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2aktbbgcu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2lyqplpmq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2jchcyopj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2leytufwj.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2ujljchzp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvkjeybr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfrmugy.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2tnrhykzc.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2abmesxnu.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2svfmrrhd.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2pncycpau.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ruyrmmeq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmgigko.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjhldbu.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2txjqmlsz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2yeqgguuf.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2putzvsqv.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbrcszw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjsbwkpz.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ailwujvg.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2icraczmx.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsnkasso.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzuksbx.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2niwqsgzt.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqydwhcn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2xlakarob.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlzkpzkc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfuwksp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cworskom.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmtbxff.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2obytjqlu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvficgi.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2xuirdguz.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjpasln.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2djpldlpm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzgmmpj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjltmqae.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2glouhvpv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztpyzfjy.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuymaidp.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nsptkvsm.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2errzhrht.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsyhgenb.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fcyulafk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2dbccokow.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nravvkwr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pthywoxk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxbuhkl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2zhwnvipa.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwymdzdz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2sycxqtba.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqpuomj.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzggpxi.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2chptxvga.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2qnlqlvie.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hekqrtni.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmutubvu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfqfwfh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2isavxoiz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcwsvnsq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqxzyeo.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2shfkuwmd.html


<!-- 参考信息 -->