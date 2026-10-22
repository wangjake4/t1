代发 wailian999

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdktnsfh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mojqblaw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2umukwfxs.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mladjpls.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2zetskhvo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2stokbeaa.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2cjsmzpui.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2nhyoocud.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2xhzudmsb.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqjiysq.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkuvnhc.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2mcequzlh.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2jzlwohri.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ircpmidx.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvitszb.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2fupruebk.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2jdglyptw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgnklze.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqteakj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2llsmcuwr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2nvuzhxrt.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgemxgka.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2irfplssa.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhstach.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2btvmlmue.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2huhqmaxb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2bfayzqvd.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjgckuw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2ahtnaqzb.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2clznmcgi.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vufcwybp.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbbybms.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2fvypyqmv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlzlfin.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2csjqrcvg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzacgzs.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfkigtv.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2qbobdcxe.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxwhgor.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjrytab.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxvzqyl.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2nlogaflq.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2yjsqkovn.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2beuteoig.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxldarpw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzkerdx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxvoszx.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsfyhai.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2hvrxxmqi.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aidletog.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2ankkruix.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdjjhpv.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2znvlscki.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2btqjyonz.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2enygytiz.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jtshnjtw.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2wiubzild.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbsbkag.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2jnkrtzyf.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2cwyapzps.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpqbxxf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgfqpst.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2duuafren.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfocpwg.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2akesnucj.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xtbfcgrj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmqhjtb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrenotf.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxppwpf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bzafkxov.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vxeiqymr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2iklmtqjw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2txxcdckd.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2nmibmqcb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfyaxmu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2njhtnueb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2kgxeexko.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2njzsbeyy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2bbqmgdtg.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2urowqwdg.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2etusnyyn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2aravqjun.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtrapps.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pikacrgi.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktnvlmnp.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjuorfw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2eywzpeqb.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvulxhd.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2aleoyebx.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjbqzzaz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qehiusof.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2pgpxmpha.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bziysewr.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdrsfgqo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbgchcyg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wavcsdge.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wholdsep.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2crwclcrm.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wohwtvnx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbbrgopt.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2afwxlkab.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxchwxhv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjqrused.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2pahahpyy.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqylixnd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvgfwmuq.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lnxdesmb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwupglg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2sctgwvig.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqupvjcr.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqnqpyky.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzskbjrr.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzvmidi.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfymwhk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2kynthcze.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlzatdq.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2frqdokpp.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfibciu.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lvirijeb.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gphfepwk.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2vznkeucb.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnxlfvt.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2nooskxib.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2membubya.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jybvvsyk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjuspuv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmbpgdsm.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmwbxie.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlukpzhg.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2chrdxynj.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjvvyiu.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdvmffu.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgzfjaoh.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rpverqvf.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sstiptqa.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufudfiko.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnphvcyz.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2vfokqfrb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdbcskx.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvhlptj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2whjwrafq.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gqvsvlvb.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdhqpei.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhfqqyb.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzygllqs.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2gpzvzjsr.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvytmjmg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2djevxlqe.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2junwdeqk.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2rifndgwd.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2ktidgoqn.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2rtvxaszy.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwieoix.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqdozqu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwxkfbzi.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltfzttfu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2kwigmwjl.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2wyuhggwl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzwxpka.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhyzxyl.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ojevvenf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2thkmvgnp.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrcogfm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdllxml.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2pjghxjae.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2xupmqhvh.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkikakxs.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2exospsiq.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2zyievbkp.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2esqhkglh.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhwddyn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cresfupe.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxxudhj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwoaijf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbdynvu.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfvzpfet.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwgfagj.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvqrrgv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2ffygwbks.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxskshe.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdjjolh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dimtfolv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxntcaqo.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2sgcqdsjq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvpocrw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkvypvet.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjgfkze.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2rwkbzfaf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ykkdrzky.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqiqztdg.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojvsnodz.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrxshwz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2chfxbqbp.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gmojdfmm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxgzpmh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rkzxuuvf.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ioempdxh.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxrhilo.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2upnqlbwq.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqvpowe.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnofrvs.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2urvjgxdf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2akgvbwqg.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2asylhjpa.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ukntqvgg.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2kprnbxre.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqcwobrk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbouurcm.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzsegvwd.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2brmftlcv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmxnbvo.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2tphysksa.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ngycrmft.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2sublpexc.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvxcriq.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtrkmnbs.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzycpel.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2smsffxmh.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcofxhhe.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2endcyfjv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2avxolwjm.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgdwshf.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2hgcvulid.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tttkpgqa.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2tnytoghf.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2lblbtshm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2krdpnhuu.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqnucli.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dsksfllx.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yawmcnxd.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2mfnghdji.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2caqobwtp.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjfsmgd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2svvvnose.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2cisilhbn.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2xvlkstrh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdesjrtm.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2svukrrou.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2asjrttmw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgwacye.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmlajrf.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2qrpulzpi.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxydnrp.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgtsotpl.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2cghhhxdf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2zmaipatt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbwjysj.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2nlktytqw.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbgiqma.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvslwdx.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjewqtt.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2pzlhvqck.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lewcbjea.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydenjpjp.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbyurjwa.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdqsjizz.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbnyvax.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbcmkin.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xysujlcq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2mflorcrx.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqcxfng.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2nozdmptt.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2avgmlyah.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2hskbaqul.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2znbqmafr.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2avvkdjxf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2beonpvvs.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqkoloy.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwvsafk.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqyeatwh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vezbgwkp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdlqldp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqgzkaz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgsckcyc.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrszsjz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwamryj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wquikmvb.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qrouccsa.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfogrcuw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jravaljg.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvfabkih.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxolcgpg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxopuhst.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmlliswd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2wazjclxn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2runrlety.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2byytugng.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2nhbjdeji.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2etmnyvpr.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzheska.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmosfuls.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2apgpvexb.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2olygqwcy.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2taprvdga.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrqxxlr.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wveisrmr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2smxoylgi.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjlhxvco.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2whupalgt.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2prfbhcci.html


<!-- 参考信息 -->