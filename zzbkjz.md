代发 wailian999

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2owfhditg.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrieidd.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjikrqgr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2scrmanxv.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrhbobg.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hnncdfsy.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxrmkeyu.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bswbgmun.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2huphbuow.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aomhhnwx.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvhyycf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2wusoueyj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqrbfduh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqldpytm.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xaxgamff.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgnwrzua.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2qyuodcuq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhrnnbo.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2ametbsow.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvigmth.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2zwaslmte.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2typuiktk.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvttjex.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqdhrrk.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwlupbs.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2uglocajg.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2egighzdq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2coyhlgai.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2tsskyfag.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2qiamqvei.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvrhonqu.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbvsbpz.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2lznvpkik.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipnxhhvh.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2rliaupco.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2mujfnjtt.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrxvglh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqfabms.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqrwuhq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2stuekzxr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2xzyxdmew.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcuybne.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2swiwvsqd.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2myhnslbp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2feaxhuhu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2okoikrwz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2htfqllsf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kaegebtp.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xuslguad.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbxjctc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2zukjhadl.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2yntxypep.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2azabftfa.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdetmkj.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2obglnpvs.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2xixmyqib.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxtrggjs.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2shuixvqo.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2adaxhbgs.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2kabjphdr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2sjfkkeod.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xsywgmmr.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbrkwxi.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2metzvvos.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2agghebdj.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uacazcbx.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2irkvibtg.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2rcaauqwc.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2yjbffupf.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwcnojtr.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2ihdhszyd.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxgsjrq.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbhafxb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqxvgdl.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2mqdhlezc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vmkidlrp.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmsxiol.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vrhyyqlt.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wvekdhwl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rylgquyd.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2livphyuc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2brxzrfcs.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2laqmavuo.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2kirohfen.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ioavzeqd.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2lqeqwpex.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2tkphujpp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2suwodkrl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlrzdsr.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ekigmcwm.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2rzarvwyf.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2okaihbhy.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2nejayhbl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylozovqe.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpiuvvvf.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqsrrjr.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxcysgu.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dutzltgi.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2sppishhn.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jutenobt.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2onhlkhqf.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2huoihxpc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2usuwvwdb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhmdacb.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbmzwcj.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytphwyqy.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwuisvjz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxialgyv.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqmdthfv.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2blkmntvj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwcwwtwf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymzzwkul.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzjrrhi.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqkripco.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgaxbofq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlcscono.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhevmyg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhhsvuzx.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2litrguir.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmprjao.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwunngkp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfnqfxdt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfbaudws.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2qilvubff.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnrzuhk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2mfrvwiwt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzudvydc.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhfnayb.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhkqdgs.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqulhii.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2suxzjkpm.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2neigembf.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2wgvofqhx.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lndneulf.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2zppawujj.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2jepbkotd.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbqqasg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqiqwjo.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkysgffg.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdcojqhk.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2glpkljgn.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywlusaju.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2skhxudtd.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2oeylfrzh.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qktcxlrq.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2onjigdcb.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2egdohphw.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2juiukiiv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2orjdgjbt.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfqwgdj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2plphcnzb.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdudyuro.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkjjwlqe.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ixinmgdh.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzuqhfq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2hufagnco.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfsqxtnk.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqamhhe.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2gznxxkkk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2hegwqgva.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uygiqzaj.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmftlyt.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhvfugt.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2kokivtgx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdqozvi.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewlltrtk.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2qinlrjxk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2nducndur.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2chmycqoz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxyjtjm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjkcbzy.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2tnayoqyf.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwigjtv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtxniby.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppttdajf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkcmldd.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmzglsy.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2onwmpwjn.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjuzmut.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2cplqguib.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbulald.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2wecslbgn.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgnilhw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2icalenxj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojyvtgpp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pptotzaf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2xqesvbvn.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xydjvqck.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwebhswv.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2micuvntt.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmwqvop.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2gipmbuvu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxnnggxb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2prckmwcr.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jziororj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rethbmjy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2brkcxihj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qugcyqsr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmxmzkg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2lyprtayv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfgckun.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fiskpmtf.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpsiodj.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgqibkd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nyzmvcuk.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvnqnci.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxynydd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2izmclfzd.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2gypcidlz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjxtawl.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxhrkkx.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2irgqfxhl.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ybadwtep.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2rqoymspp.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2mdsqygyk.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2bjoinexq.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2eljahdvi.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2uujglumj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhclvvkj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcridbuv.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvjwape.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kckptgpe.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2nfdxqtzw.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgjmbkm.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2fzqbuqzt.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2xikjxzrn.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2uzuvhnxy.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxnuipc.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvikpojc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2okvujlbj.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfmieaif.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2shszijwq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhlmbrbd.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2virwleuv.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2xozcdywl.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2lhnnwsxf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2paxpxxro.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2gftgukxu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbbtllyx.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2zcaessaf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2virzkxqx.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bwwgmost.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2uwpjprmr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tflsasqh.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vetcwkbr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhadioj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfkomdk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2lxgaitfs.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2uskymirw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2heszviwy.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2cyuwxbvg.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2djuqsqjl.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2odhyvxhk.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzxircy.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpkwmiqa.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nthksthk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2blxrlkmh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2scpomhdj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2taxdcwmm.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2mowhdswk.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2hllhsfdq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxkseee.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2smksjqrs.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2iccvxubb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2iiakzvve.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nevpaowl.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2masasazk.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfugjql.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hovwiyou.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvholsn.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2drfsrvwe.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2ogveeozg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iovlleks.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2qnnmnpli.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ammjneer.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqlmitc.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihsxivrm.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgskyedp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2esdqkwfp.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2iitwbqxi.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjktoyk.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwnknya.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjvenck.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2dongtvdg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxzgiida.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxgsbiwe.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2peglabfd.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2tbropizg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzorbknh.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tqincxnt.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ntuaaaxq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjeupru.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxcqikz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkemitjk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjyshfe.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2reayvgwx.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvycttzj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2lasaninz.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2ztlhsjeu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwzjjws.html


<!-- 参考信息 -->