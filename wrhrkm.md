代发 wailian999

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yznntpbi.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbjmsqm.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zathazka.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gtheawgd.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmmwrzsz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgugkmju.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2rpvbxahw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2hdosqkek.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqjiztf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2isouxdpk.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqomneqm.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2suyjmgso.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqcswii.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2rxeyptfu.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2rbiynndq.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ofyfvynu.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2qcynutda.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2kngtewxe.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2bwlqacda.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpuhybe.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2clehhmxw.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2friegbwe.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwyeikg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbiaphf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwmxxth.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2yindfubb.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjouqqkc.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2ykszwscr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2kabchyww.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpklcnuw.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2lfcxhcic.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2njenjijj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxkumsd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2awpmkoik.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwmhswn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2gvftrgby.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxkcjwo.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfqhrqp.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2byfgbxdz.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzsklkd.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2nluyrbmp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwsncotw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2feuzibrf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tejdrbch.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqggirkh.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqpjthq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2unxbvifk.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvacnhg.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2loduaziy.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2dwiyyiil.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2repqjlqz.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2hsibmnrg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbsozcal.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjhvdqfq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2uazheasn.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2irvxzutl.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqywvlj.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hasizhia.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2nowijelc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfdxukb.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwhupwu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrqhbdo.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2lubbstcb.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2nypkclaf.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdblick.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtqgmcw.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjzdwqx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvhkidg.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2xhiwnwag.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwdbjpu.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2hoowtqfu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnvslvk.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2vqarofbf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwjlpcc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2evycomfs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gtywrklu.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2tgxqhkqb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzlxqkz.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gehciqsf.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2mzgckpmk.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfdgmye.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjppiux.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdrqrov.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2budcdvxy.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwprrgn.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2vqidvsva.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2skutwueh.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2cxkokksh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2dcyznnxk.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2cajdbiot.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2btcwdlfv.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yicrwoil.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zazhkuam.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmirgavf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2itynakoa.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hudejkxn.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yfoolhfl.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnyfftr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtlhoon.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqoqyqw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzitrmh.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfzsahc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2fftxqzfz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdgedrf.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdcucjf.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yagcldfv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmsluxti.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxkgteit.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2gflrntjs.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvtkdcs.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2grplzjqm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtbyiix.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mznjqplg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2khuukgkj.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kprmunag.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2voxleywv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxtfwtfx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2iffysmww.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmnjyon.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkhdnqa.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwhfukc.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2nkpkvzta.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkmcaqlw.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xorfekag.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwlflgz.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2drjnpbty.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjlxmvu.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xyzkzpqu.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2dzkicghe.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhcqwbj.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2urjdeghy.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2wysfvsuu.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kdujrwau.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2hppooxdv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ncsnvkyq.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dizeysvt.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2khljfhia.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uaheriky.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzumsdl.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2eiemqegi.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdvmfefx.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2reyxhiam.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssfcjjjj.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2laxhdpal.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnyrtzwl.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2bnmxhoub.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgjyzxx.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwavckxa.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2emlipqed.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2brjtkxwo.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2mapjnovk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2nrnlguso.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nsetizwr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2mllyjrpd.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekoaiesf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohzcqeaw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2atszgyie.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ipusptks.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2vvialkfb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxaojtl.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhxhvwfr.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2utkuvgxy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2bishkoqv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhkwsfol.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgnfbzf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqnknsk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxrhvat.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpluise.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqrkndv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxghhic.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdwwfqa.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2okaoougc.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2jauaurlk.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxnfftw.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwdavga.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqyfjkc.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2uczfqqye.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2davehwhz.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2rrunvppp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcpicmyy.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fikkfpzy.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kusfkgwt.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2ibuuzskz.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhpeleg.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldieikba.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2rneuqeas.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2epcjfknc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xonghgdt.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xiagkahb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wunssjex.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zavvkbys.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbhdfxd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2utszwbig.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnkxvpam.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dtzndyck.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2gltwontt.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2rtltkvpo.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zuywkrmw.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2duwkcfbn.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yinuccjc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqjfvky.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnohzen.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2csxdxuzi.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvhhzfd.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2sbipbvec.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xzatmwga.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpijedfd.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2rntiflfl.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxkowrz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2xglkkggp.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2lovossqy.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2kaqjrkxy.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2eoaijldt.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2sdntmqyf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahyawxgl.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkkongq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwzsruz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjgwmcx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlrgvmv.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjsbvvn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2pbspcdqy.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2zjopcwxq.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvgjvar.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vaaimquy.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dyipebmr.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjndpct.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjldyym.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuiumyzf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwxlghs.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2gbtctnca.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2kkycvjmd.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bridnitq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2zowpkbtz.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpejtebx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2nslbklyg.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2vidvikvd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wecubjog.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbfzxok.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2lvduhurc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvqwunt.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxnmgth.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdljlgn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvjdyli.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2ircwbndb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezzlfvat.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2uhyhhmjc.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2ryohjigw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2iufocnau.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwaosgp.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbrufvi.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkgguizx.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgawbwxa.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2yvtawmso.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2liqqtjvt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2kmeivagk.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2cfyahbtq.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2hjggesde.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2tjchajur.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gzodvyfo.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2miyylndq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2awpuksbh.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbprvlgi.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixugckra.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvfqlak.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2irantnqf.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqtuvai.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcqzzahz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2jthzlffo.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqtgdmhn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2befzahjg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2abklzzkt.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2wivnikat.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2hslbqgzg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2glerlcwz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2zqddpqws.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrrrpso.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2jobczywg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2trtcovvm.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsenwjlf.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvgymrf.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2famhbwpt.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwfyqnhq.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vpgnbhqa.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2nwuzcfiu.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2srfdqjkz.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2skzfvmet.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2uoprejji.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnaihxhq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iojyjuza.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqtczjc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdduvmb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2szgytwbd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2gggsgedh.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbduygo.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2iokilhye.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2mvagwigu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2zqxcbjwh.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xndzaqzx.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fakjwdmg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cajtbkwg.html


<!-- 参考信息 -->