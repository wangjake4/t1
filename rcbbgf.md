代发 wailian999

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fabqhxvw.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2aehnouyy.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2igelkhnb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vixhhyzg.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtrjocc.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2pqkrsxxd.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2qmymbjim.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2wnyejzku.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2mvawkxds.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmsucjx.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2iovppkmh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpjmnnr.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnezuou.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2nibfluqs.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrjwboc.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnihchr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2puqbcyty.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2khrallrl.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkuuaufq.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvsdtqu.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlwpuna.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2xaiqeujj.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2egqrraps.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2zjetioco.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjptode.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2euzbvhou.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2laegptsh.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxemufq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2kjxohfhk.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjnnozg.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fgskuvab.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdqtagd.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2zsolezvy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqoiueuo.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2daxnrxsi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eeomorzj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzmpitl.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpyynxm.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjktfyx.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxywewmy.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rsasrrdl.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2rnupynni.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2olhuwugq.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2izzpgtdv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvkrdpc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwsfvnp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbioblwk.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhvupyk.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2nfincyxa.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sfyygvku.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzwmvgf.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2czsswgqy.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ynepylqy.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vtyrcicq.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvddmrc.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2drxyumrr.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2ijbojphb.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfinevcu.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2yvnevshz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2jmoqhrxd.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbiczbp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2trlenbet.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2hbrgfzif.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2utgtxhgs.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2yztoipfy.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qkzsaflc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hmnlwgal.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uldwdujh.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2njhcqbvu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qttmjeum.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qpengubm.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdszsnm.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2glozkzip.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2dcqhctsw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2efgmuhew.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2ssptyatz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2qzscwosb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2tvuostbc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2kibdbmgu.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2anpsnwbe.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2pybwkhfo.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtufyspx.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2oofhczgz.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjulmjfc.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmkwhvq.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjhbvlt.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymeoaclo.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2urwxcpnn.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rikbiqpt.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2agcxbkhr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2safadacl.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2vzelgpdc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhdscid.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kuveeswf.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwyoeqzg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkottxp.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpqbxfk.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2iohdvfbc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2orpkhbiy.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtzdxyk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2jcyrwbog.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jlethccx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tuticure.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsgzlpqj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nelbryaw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xczzcipb.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qaznmfhs.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwrowrn.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2hndzyjoa.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmkqlqse.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2texitifx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2mznxqkli.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwkkprz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhbsscg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2negfcswo.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvrghjj.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxpytif.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2eivptzfj.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2eintngif.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrpxxpv.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2llcznpwk.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sztxhdbb.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2orjxvdvy.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnalbezv.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qmeneqbq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbzpyzm.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrefflx.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2esgwuhtw.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2trnwxkev.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvkbpjgc.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2orwsfbqi.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2dzijgqvw.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gixyauvt.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwrlvqq.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhurpqjo.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrctflz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2reidxuth.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ajejpkcv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbvybzn.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfwslpr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbsrfluy.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yakhtffx.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2adobkjgy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxtrswq.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqbbdlf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkpcmmg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydyjksma.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgnrzgk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2htbwjaew.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2baekfbgl.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2umdwbsxp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2yuqwwzdl.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhzgapf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bohdvnuc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2iphkfvhl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2pknfzbjy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2gepkxdhm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2ghlphiaf.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmiqmpf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmcypuy.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pncgehwg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2dvoenkad.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbyjmlta.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2rubeplhu.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2uynepiyo.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2shpzigzl.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggyvguqx.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2nastedrz.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2skhxjvsd.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2gidzhneq.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2ctkmvyqy.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvdfvtk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmxbkokx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncztukub.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2onwkebqj.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfahfeok.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbzxwwh.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzkrtdzt.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2bedrhipd.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fhlpqkmx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqljguy.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2povpuyux.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgyzsiey.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdnfttp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqelhln.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdkmlvkz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uygyyexu.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmjwqdr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ckryfdkk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2carrcxvn.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gemfpwpd.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2drerjtcf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2npxiqatx.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rftgangf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvddlxh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jzgbejds.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkxoapo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqlymvq.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxzwxcq.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2hsyzessg.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnwznql.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2osdltbrn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2vniiucpk.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2kbkwnuoa.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kzehhmqm.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2kcvpzyaq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjuzukg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2awwianiy.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2orfxrgmw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcdoxwgh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqmnvpz.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2qxpsxaih.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2emsstimo.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2keibxjhg.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ntncvboe.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmphgshs.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yiqykzad.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdaihhsr.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rclzyokr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcfwwkp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tllthtbn.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2vphxecwp.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2xlutmvbk.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvqhbvj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtittmv.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2rovdcndg.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2plehamai.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjsqaeq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bvivicru.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwyvunz.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2huwqcrxr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zznsaytt.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2elsdvmuk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zudzyito.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2uobbqsyh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2vydpuand.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkfquqz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdyehnb.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2vmggtjnb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2txmjsmvm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2miesmwyi.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2zfnscjeb.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxpsfyh.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqhobhk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzenhmj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rlialoib.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2zauepavk.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqhztpl.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2cpfueiyl.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2nugiicxt.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2acltbsdh.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2tnypqsuy.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhillihw.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2adpaipoq.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwvkegr.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2brphjogq.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfwctvk.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhvwayd.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vukhhrxt.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2tooakaju.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbtldfrf.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2paiumlfy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzgepwxf.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2ioizvtrv.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2klvsjbro.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2fovsyocr.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2reykzrwp.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvamejcl.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2rnejhkoe.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwookiso.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvrnxywd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2forokvnm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbblktc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvwoycp.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zxuiupwz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2vmiumtdd.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jufjmozo.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mttjxejh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzuptgzt.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnecads.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzssmtzj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2twmadbzw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjtvrjb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqoblrmf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2snlexvzu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjlrouc.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2hnfvompf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdekywh.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2wblobzjw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wirinmed.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvdquaik.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzqpemea.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2xiozsncy.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqumkihz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfudpcv.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qiiprbcf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vruzhrro.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhdhfaaz.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxhdbcer.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2wffopvsm.html


<!-- 参考信息 -->