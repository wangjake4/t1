代发 wailian999

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2znhmxaft.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2xcaqeval.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrhbyvp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2zouzkemp.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2iilxuqnn.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2sesmlqvz.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2pukosqho.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfepvic.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkylklk.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2rsllqprd.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2ayusekxu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2fexpurkd.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2kiyfjpmo.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdgxsnu.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2oyltrpog.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhdrvno.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2hbcrxpro.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfyohet.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkafsmc.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdwntlh.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ukhxwchn.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2myehzxrw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdyriyo.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2azcbzvwk.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2trgscqxr.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2jxnvzoxs.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mlchlexi.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfqhtki.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2nlzpqxhk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aabgziua.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhnqcpz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkaqqfnr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdmxbyp.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2xduckflr.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2apjpkuau.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2chnjrqkw.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kenuaydi.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjsuikc.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2jlacnauw.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ksztcrkb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgngnvcm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqoioseo.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdczepr.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2afjqqxgs.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2dvsslfsk.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yppjxihk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2hcpkrvtf.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnuxitas.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2khtfsdjs.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2plnuyeti.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2vusytfry.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2cdcxkhpz.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzvieex.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmraioj.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhezcbe.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhlqmyt.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2wjifdepp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2knzoxzne.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2xmswfnwc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jdimltdc.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbgsjtt.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dcofwwok.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jcvbjmlc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eduvzivg.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2jfrulshk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkletrw.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwcrodl.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvghxev.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2kqcjwaoj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2sjwvoxxr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2zwomcfjv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2kddduizv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2zyorklgs.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2lgsgrjpq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2lotwpzft.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxscmyl.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2qbhdmeon.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2efukccsj.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvokbibs.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vijkzili.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqkhbkb.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yajwqqjk.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2frfpqiib.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2oehztvmi.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gropqcgq.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vivhlmlr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2inhltoxx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2izhmvvna.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvsdymcg.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pviffpda.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2njtqjfcz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2nebjulyy.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2amyglvee.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjxuntc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xinyijfs.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfmlyyq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2wupbgzhw.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2spqxihol.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzlzzvi.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2zaukmvei.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqzzxnk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cateyafd.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2omjzanky.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2qevlzxqc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2shlyepdo.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajojxmxz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmgtkqju.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2djhsdguz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2vwuhwtdb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2gwpnykih.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmyszelz.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqpivrx.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqaoeiy.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2joqahzow.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbbeocj.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jcpzqwat.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2spnmsvqm.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvebonl.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2eyewydoz.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2hharvonb.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2petzvzji.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfgspyk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zsuznyqz.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2auujvbnm.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfdvpfi.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xyamqgng.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2zjbkcktm.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfnahoy.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2upeaeaxc.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2yldeayay.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjclifw.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttvwbglz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrxwete.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2madujgsm.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wmyuhpgq.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrgwxzn.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2keypoxbg.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvwxsvv.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwsiifi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtuhykl.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwywoht.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2xbrfkkuj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvitgkfh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2lijdfaqx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2efpulots.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2graqtzqt.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2yytollae.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2harcftkl.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdaygmrt.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2oemnjqao.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2nntsvvlo.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxxheuml.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2orkubkze.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmchsrb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2psewmrns.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfuqgkc.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2sfyxfsjm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2exbmpwxu.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwaixys.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwzevdp.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwljmiz.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2frgjyvdr.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2klbcgema.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2blwczijf.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ncydgexy.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2camstoqk.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2txinwryo.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzonqcl.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2alwqgzhl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tydfvirr.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2djpaeuhx.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhyubpe.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlomgmj.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbuluyrd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2dsfgaxcb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vpftaflc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdmbvmi.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2huvlakuy.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdyvujt.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkpavsr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnaeiwo.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjyekdb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yccnbejo.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2jxmojwku.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2whvhrmyv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwvdvbf.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbooyjos.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvmtvtu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jnipojgf.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ntzhjehn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdpsugon.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ecsvqzbx.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qoghtqnb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fgpbwiyu.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxqhpul.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2gavwxqiq.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ofoumnsc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2jtsgfxdz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2bujqcduu.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2lawdmefl.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2knjrckmk.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpiwnmw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hotxrqkc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxfhwhi.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxyjmkq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjhpcat.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2ycckzdlo.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2faqdslty.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtoyrlm.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2ybypisho.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2yopragkf.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcktiwkh.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgzqbko.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qeyqqzgi.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntkzcpgz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2orrpxfjv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvkvjzmr.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbeimru.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrklnye.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2isjsoock.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwsdbut.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvyeonx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2burgqbgt.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2ljeyokvd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rwykpwmf.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrdhlxv.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzrqvsi.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhksfzn.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xyrbfbdo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlppdlv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhgzpfj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2ucglyxbi.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrkrrwi.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2azmhhzaq.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2tkywznrs.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzsrimt.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2clwdxsvq.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvfobww.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqsofjwd.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2etcoidcy.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2fviqaqft.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xtsglwgi.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgnspov.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2kmgyrmaw.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdtbear.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2awikgkpk.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mygtpkey.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2fcafprnu.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmltklp.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2oridtemw.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2omotgwru.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iodmxifz.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lloxzohi.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdduscig.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mphmxpxv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2rtvvvwzy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnnnajo.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2mkccmffc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzpqbfjs.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2gdoplojv.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2kutyeyfj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2moocqpoh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2ejypuotg.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzeecxkr.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2iissbpwy.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gepiotps.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yedjtmdk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbitmmfh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fukkispk.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpcgwhrm.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2slsxjyam.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2yobvopiy.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrswkqrv.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvdwsbt.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2njoohvmr.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2geqvhsnc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmgejpuo.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnnqzsq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ticindsa.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2llmeudum.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2eteaiubs.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzipqhu.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxqcpse.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2uaunqtit.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtefdqh.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvnimnc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2azoylcnc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbusuqyc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2dcjymeec.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqkzbyxr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqiuatyu.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnjzrsy.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ysirupbo.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqkbyto.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2zvueowab.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdyzzcw.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrixknr.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2hmaekxap.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2xeubzzzz.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmjemph.html


<!-- 参考信息 -->