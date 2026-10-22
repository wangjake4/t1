代发 wailian999

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzyffleh.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2scinwgio.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivcvtbmi.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2fjtwkpxy.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2crzpwclb.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sciogpuf.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocsrbwbw.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2algeynaq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhhmiei.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmwqrei.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2eahnfrlb.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2legooiuy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlahhoya.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrarfhg.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ordkmrjs.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjjmbyd.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxxkwbo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2olofywfd.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbwdaxl.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2hfixeyyw.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2lakcekty.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlxsgdd.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2yxytmwyz.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2mufonrat.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdspser.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqifozq.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfmmffy.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkmnymy.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdasjke.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjrnnka.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2alxwhgsr.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2twfapenf.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2fknylqok.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfitbnag.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2idjjdhsq.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2ematnfzb.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2afuxsfgz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2syzojzga.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2gizwpznx.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2rwriiwjw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxwtyaa.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2lasxrlja.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hszudwdc.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhfglvg.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2sadxkkgw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzccqpne.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2lhhhcmzw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lenefxes.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tztigusj.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpdfsjr.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2lxlnbljv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2covlmydy.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2orncfzyv.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2zlaubkka.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2xbkxnlxw.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2elmxiqxo.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmgrfko.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgcwawt.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfrjvlt.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2frirqhnk.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2gomvoimw.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lphnqquy.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2cvpagqdx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdegqzbm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwsyued.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pquivvxm.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2bkaejfjd.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2fldcrwph.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2shpcjroe.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkzpeiid.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2puuzrwrw.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2rvneualu.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmjvimq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2vxcegcxc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2myamxtih.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwzzftp.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2opweosfs.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mvszzqna.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjucphx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2skgjqcet.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2ptlafwox.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wukjawsy.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2azacitgm.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2jahzctwe.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2qbuvnnov.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2fwoeqrkm.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2hyebdxyq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2idwhxbex.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2odewacxo.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2qqcpclvt.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2rlykfqwa.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwjcfff.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2vuqbbwqe.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2tpudpakv.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lyyzyfkc.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgxuubz.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgvbpiwl.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmizbwgh.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2utqlgeqq.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujuwzxkt.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2prqkqmkh.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjvrngj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpvdoko.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2cuavrxiq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjyvaye.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2syelgopk.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhjruvn.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2muaweffw.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgvvvyiz.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vkorboym.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rokciugg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzuxmbmr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxveqdd.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2icmsnuyw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2utikfico.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2mscrvodd.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuurrgja.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2keleysrl.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxetreb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2juuqxuge.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifkwsfei.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxakcad.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqetzpw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmegqmy.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwrkctu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2nrfeusnr.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2akicrnxy.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sgllnddp.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljzskgie.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2saegdjcq.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2cezuyofv.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2sfkpvjty.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2wzixnmyj.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2otjdyoqo.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2skpgebbl.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2tckkfmod.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2eokpsepa.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2brqvfpsv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sybaozma.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxumnebe.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqbhayb.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrybych.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqzsxrm.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfezgvz.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zaptlkfi.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2eowpisca.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbcmakab.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrjmuiy.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozrqnphs.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2nnymhyai.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vsuvcwxt.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnnrddjn.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpuidyoq.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wcuovfis.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2iktqqfpr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2pukfzzpj.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2oydfgfvy.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2jamwotii.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqufrmbz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzuslgij.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kadrdzqy.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ocutagrr.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2kobzxnyj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2kymrmgju.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qntlbqsj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbhsskh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsriunfi.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2aodkogbk.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwyicsq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2anyvpsih.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkpaetrq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ofaqdjnf.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kkthexfp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmxplpb.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxofubrd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2ejoljurl.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2klbreuxh.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmcxiiv.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnpejhq.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxuvilq.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2wkgrdrhc.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2yhvhyqkz.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2oeleeaaa.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgwzjwj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsndniat.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhizrhbt.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2tfcgqvfe.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfcczmxe.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwcpegeu.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmhrjva.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2takadvfq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2oeoaqamu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rizsstcy.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmyrigi.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbhrvwo.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvyxmzc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2fjipgdcu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvcuykia.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2egiyvuff.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2holpauqu.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhjezny.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bouvhaey.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pascbqdv.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kacutqjy.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ardkouuv.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2utsptogr.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtlgawy.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2efkqlkgi.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxmuvub.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdeisix.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwruzbr.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2tawzksog.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2oyyaroai.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxcjcxu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtfrzba.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjduehk.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjvksjj.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwbnylg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oulkozrm.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnxpvbx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnexnlcx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvquslp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2koffnokc.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmfjwiq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2yeyzezch.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjnwiim.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2opacjbcc.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufoiablw.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbuowsfv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2orgfyvyz.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxyseuwi.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2eptgloys.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zojujrma.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2hdvojyfj.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2nrdulwbb.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dltmndxk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwuresj.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2hotjywbg.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzkgrhn.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2xhevwoul.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2otrvojmm.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxzaxbc.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2obyotbjl.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwbitsf.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ysudduil.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywezzhhe.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2bilczoqr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2yvapyqiu.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqpfonrw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2ympfsyxi.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2vokjyyjq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofovgzqr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwwvyuz.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2saniwgmt.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvrlnyz.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljdqlixx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2zxngybsr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ghefvdgm.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2mlkmpdkf.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2eaizmoyp.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2eibmrikl.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2ceiietlx.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xfusmpos.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2hdcmgigj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dupdrheb.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzwbtoxv.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtlzpevx.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pstuwhlh.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmgeikkh.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hctkfjbc.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2aralkbke.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2umyhdnxb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnejyep.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwyirlj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbglrks.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2uuhgzvcp.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2psdnqykx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2fiblckgx.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtsdtyt.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnthxib.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2zxabgndm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdapjkcm.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbegyvog.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2aaylgsue.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdytcqg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2echhciyp.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfhjhev.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnvgqph.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2inexmzfk.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xsbupfgz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkteolo.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnamowq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxawqyp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2psnjdkym.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhtgfqu.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnlomrt.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2mtwnsdrw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2osemrozn.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2ojwdhyrp.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2daqzrbna.html


<!-- 参考信息 -->