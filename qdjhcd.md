代发 wailian999

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2opqkujkn.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xcgkhpea.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tarffzvo.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lhhgskoi.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkagbdtv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrsdupvn.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2jqeykqrs.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2arayrkns.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxjcfci.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmenblo.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzpkcse.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfmxqap.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2wmeqdcbv.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgpwmto.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2gvcgmqya.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2hqyfpksq.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmzjwqw.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhspqvd.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpmfmfn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2apdyxllm.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2itkfadqw.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2cepmmayg.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2tgharluu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2idruowes.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2wngwukdg.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2ohncqyig.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2socnpyya.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2psbmapli.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjuqwnw.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtyblah.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqpxscs.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvalcca.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2fylvmzys.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmynkzz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrsvdqr.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2sclgoeff.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2szjqrrzj.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2kthiunkq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2urxejvkr.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2njkudhgx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlbytah.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyemuhgc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqiaxne.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgelzcvz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2elnolkxd.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2erjweytt.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgoksfn.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2oijiwksw.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pcwunkng.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2jgboslhb.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2tkuglcha.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2kahfezmv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvouauk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfoevriv.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqzoolk.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbcwooa.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2gmlvqodm.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iqgbdjsw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2czeedpmh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixouxpfo.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2znvcyzyb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtdwdaw.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2refsgpbq.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2qaieskzw.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2fnlvmhgl.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilswnbnu.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2cwecmnla.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2kkjtcncy.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2ixkbcrgg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkxvvka.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2uzyfsvgr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zhjyknrq.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhuxyqt.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vjsvgqdk.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rogsqmcv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cbidlgrp.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvzvnjs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hhcpylcx.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nxmeyiuw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2bjejnsvs.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2wqihpbbp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2fpozyixi.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2gpzkekfg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzinyav.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2eaauxthb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2kekwselr.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2oamzegle.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnsodpb.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjnsduc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxznrjw.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2emkmuafr.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebaxybtl.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2piqltawn.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2brqryfng.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2desastfr.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvomoiz.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2asadyfgb.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2idysdzxa.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfsuyfdl.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2soidtgit.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nskqlxfn.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjebegog.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2efhmcfxq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpejwdvy.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhqdsvbi.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2canznmty.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2stdtehau.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2plwpnhkw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2jzgnmjmd.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2flqpxhmj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2guonqzjd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2srhoxdyl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyreqmpl.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fubaakao.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xdnizzuz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2lvkkzzgc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvplmio.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqkeykuv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqhtrdc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdxnaoy.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2fykvorfg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2mphklszb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqncqhos.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdqlpbz.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nndhnqfy.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2epontwix.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tncyjdnk.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxubbfy.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2fxkrmbys.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzeqwhkj.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2gkvirxty.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2wikifeja.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrsoboq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2pehytpsd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsawdzcs.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2iildjanc.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnukicjj.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwzsntu.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2ddbaeeld.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2dgsqkmyk.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgplfqxl.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ztesvngr.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmupivh.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbbnanh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnnrdne.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2bpupugip.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2llobkoor.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwkmcrxu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvobjgct.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wnlxhhhf.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2jaunlpgy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrgebob.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymotmgcb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2ubcyenqg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhlofza.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvyrxmo.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksqimuty.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtvoovu.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjgjlxf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2bwaaltit.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pokcxfnp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwyrkja.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnekbfx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2stwtkpfs.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjslyfv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2eligrano.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2agdfmxzn.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrohmtl.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pkipsqyw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqpuznl.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wltjxzxl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2fadjirqr.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2castbvha.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwoubyyp.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwfusiy.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2azertbsi.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2glkzizuk.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2xutelrmh.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2ulrlvvli.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rurdluqh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtnjcti.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vaufizuu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkrttdn.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tysfxprg.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tptfdmyr.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwlwdhv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2ickfwwir.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2gkepjdhb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jsuvhvrv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2onletkzz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2keftadop.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zfeegduy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2padpsqab.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tonzuwmy.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpjnzgp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2noxscwgm.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpfwowf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hakbomfk.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrgucpo.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmdijabo.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ymkhnulg.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vfntzwzy.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yziiyzxu.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uzsrxutk.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2rovqmbwo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qalikhzh.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqihfviu.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2lvuhzwfn.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2bpcjiqvx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2xomyvxmv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2bfldhdul.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzsagef.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhpkiav.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2ioovqvxz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzzgoed.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjzpaju.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2zilqqrrc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2syvnpvwl.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2vcarprvg.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2tuaqhpvm.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2eiunuwpj.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2kbpangpl.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjmoftg.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlokbsm.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpmgozwm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rirhhhyg.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvlydcbt.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlnqpqo.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bltqnrsh.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2rejugorg.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkjzccp.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2urgxwdfv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmsaftt.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqbprda.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdcwznac.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2izehgbyt.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rogczeub.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xoimlgmp.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2hsnuhnrd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqlxvum.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjgeyhc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxwqyss.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2zxgmchhd.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfpqoxp.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdnmsunq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2jxakknug.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2upieqyko.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2gggihhmy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2cqusjnpm.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2symknnoa.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbhlsbm.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuouarap.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2qboqtklo.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2lnscnhww.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbyetsz.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2xtchhzuv.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2eurcguej.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2bxhtxzsn.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yfblnvkk.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdsqczu.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqzjkkx.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iplynegu.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhiaoaqf.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbibcore.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xevtjbik.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbjtmbt.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuepnyuc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2oirbqdcr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekovyjai.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2xoifhbbb.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjpmnwx.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2czlzsumg.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2njqezszc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxizatwn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2nubsaztt.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpcqxfug.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2haaihpgs.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2audfsixt.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2azaoaxqz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlrsfjd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2inqajptn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2phpwcvno.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tazbizil.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2gqomynxs.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbvrpnz.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2awnxzddw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ucupvkfb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2evqvokjs.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uahjldng.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqzxazm.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2pdeghvry.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2hajrfvnx.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbehbqz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmulsmr.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2xejbexqv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2vvubrvya.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2pgersnvg.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pchqrydd.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2owdlgiko.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2japaorxq.html


<!-- 参考信息 -->