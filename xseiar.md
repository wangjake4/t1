代发 wailian999

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qshmphan.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2owezddqg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdchulw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwyftju.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvyliacu.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2awfutnvu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjqadep.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxlaqvio.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2vveowrpk.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2szqkamse.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2bjvmpfle.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2eivtwxrx.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2gauglxoq.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2smtcujvo.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2izklgrsl.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2nherypiy.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmhlfqt.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2huqrgtjm.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2trvulndn.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2npnnrkwg.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2vcskcegj.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2ciawqitf.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjolhcnw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2rxnzqxnf.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2jdetfkjx.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvnqomn.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2rrobwpxm.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2wtaidosf.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2urncvnax.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnhkjrt.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgxwewm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2qpzlmtpr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2ahubzhwz.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqvguts.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2osmolnvw.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvqfyvn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqjehhj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpopnnrx.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2kfaikijj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsvoqjth.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2etyqkgxv.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2appczmfp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2ygpyxrhb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsihujhb.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2whsgpfsb.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxppafs.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2cdauyvof.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2skqzuerb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lptkwqmm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajumwgic.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtpgqov.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2zlpzjyrx.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2dsuqwrqi.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ebgfqcjz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlophmz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrsnulw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2alkodaog.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wqaeoris.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2osgnxnga.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2fskajsub.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2acpjwpvc.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmefwhns.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2ptchgbcz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2ybuogjxg.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2abkxrlvp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2yldownxv.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qzzvjuus.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fgofxzeg.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2djvbsocq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwouzvy.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wrchvuss.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2flzbmdgk.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2eoicbrtu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtgsjbs.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bqikqiqs.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2otwppxky.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrugdfq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhscbes.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2lifmkdzq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjzsktb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2vxweczgw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ylzclghb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgjkjdk.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2givthwnn.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2suhspeao.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrxrbig.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uayavdkn.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tedzxwhz.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebcgkjsi.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ameuqmui.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqgdzfjg.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kylgjjmn.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgrynjh.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxdstjs.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2netrntga.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2aqcfkayk.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbejfic.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnlfhrbh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2edybshjx.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwdpctm.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsoaftvv.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2leryuxfs.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ismwtrzh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hiftfrtg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmzkdoz.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvnzbptl.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2iheovfto.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvcaoqxj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcjzyue.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwzcjhr.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2runomlsh.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqfqqim.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhrwigy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulaygaqb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdvuqxg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbuhtvqc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2drhtqwpz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2xwpajtfg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivelwzwx.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxxrnzt.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2texuaifg.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejeuqgsq.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ciahybwq.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rvfpokji.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2tjzjtxkw.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkwtjlu.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrkmojh.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdswhyi.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjpmyeu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxycotb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zarroswo.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nestgros.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdsgpzt.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxwwwyxc.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2jbeckchi.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2vaghnusi.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktubxrht.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2phouncho.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkosqdyn.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2afkzqcnx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ophhbuip.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxdqwfs.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oduvclxd.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2tifcmgjy.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbbsfxy.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvipfeb.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2dunzltaq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2xfucceuz.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfsyrdw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2pskgvjdk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjiuzcq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfaujpsa.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmttwyx.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2jurtcrsn.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2lrakhlag.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2atoioghf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkuvssiz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ilmqikej.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuskyabe.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ruybgnue.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ogppjdxw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2wsylanhd.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2suisgshl.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2uxopadjn.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fchtrlsf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2oxvgccff.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2snrdeofb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2osgsyytw.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2tlntrjbx.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrapckn.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjjihuo.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2fsyuhmfu.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbsjstc.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2xiyqnedp.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqrsypp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltsilyrf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ednrfupb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtyqxqv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2qsafsasd.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2denedxpn.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2utvukxqc.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2iomcpnfc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2bytflnth.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ztxwbvvc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kejtijye.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpcqqkah.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzgufamg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zhciahli.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2xurqtipu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2izyqkhxr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ttilmthd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgxxudn.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ntahfsex.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufuzxwah.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbzjxug.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2widyecai.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmqjzsx.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2phpweula.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmrwrfo.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hlfmpukd.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ffedoivz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkdiarf.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2frwacope.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2idbmdjps.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2cnphyyda.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2qkafnlyb.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwbbdoh.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2wywtffmn.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bbenzvoa.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2mzgygufs.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hadktyme.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ilolwedc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxvzsev.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdcubnn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjkppxj.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmtrhos.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2akpwkuvh.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2udqxytxl.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2wytmrljh.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2basjqjcn.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwzezyb.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwkuvxoy.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wimtnaen.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2zibbdgbt.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vymxklrn.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2dpzzsjxk.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2gpcexuua.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kxikoluh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2dszcbbhk.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2jseffmnl.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjokftz.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2tbnlrokf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gzzrcnmk.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2sbjsropy.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbatzrs.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2akekuzhd.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjrskgb.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhlqwyh.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2zfpiuivb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2bykzuehz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbuurtf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrovhgs.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2pdeudxhc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2spuanybh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2gaokalxt.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2bjlsyomj.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxnfjdw.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tragoxqm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2bnuzzxkl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ehcvsnvc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2ekonxzli.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwobtjx.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2ouiivoby.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2eieshyqo.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlhlzqd.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2emlbfixp.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2skwoqxvi.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2piihgckp.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhienwwc.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2okurcxte.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwfwvfwj.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hknlseum.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrofcyf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2bpkkycgh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqkmflmb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2nksifgfm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxswhhyq.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2btkpsxwm.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrtcxnr.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfumdti.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2sxnzdidk.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwdihsz.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2xtbmcjjg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmsluagf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfmglqlk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqnanrpw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2dddvpbcn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2kldmvjsw.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mwiacvij.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2laevgnks.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mugekkqn.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxyuuwq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2lehqbkrb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vivjkwjf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2edchpzcg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqkptuhg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2wpbbtzrn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ymsaerqg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2hweaohxj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2xokhiktx.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzmzliw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2owhrskvc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2fzgsehwz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrigdsxe.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfkiyeov.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qikrprva.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2uwcvyfsw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylepflku.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqvstfn.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wqsgbigr.html


<!-- 参考信息 -->