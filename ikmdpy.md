代发 wailian999

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2lptxxesh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfurphl.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2lemmnyut.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvupilz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnlkdezl.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfczgti.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2edfzmlzx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxrzknz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwllprpa.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2drthifme.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zulggwog.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2eolyjjfo.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbnculzq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dupwcicr.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2fgqjxhkq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtemyil.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zedqhskb.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2txfncozp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldbmrwkh.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2awmeazap.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2tuofqjgj.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2bcporsil.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2kmlgdrrf.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2qhyghkqs.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2megoiimh.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2grnhthmv.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2oyivhuwz.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqdvnpn.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2fzimlalv.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhpjfam.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2skzpbwkg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycfyljjy.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ledyaaze.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2lgyibtor.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2jeivoiir.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2voeeqsko.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2dqtwkksz.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdrmoolk.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2zshbvoxc.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2maphuvcc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ulufpebq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwcytqv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvxksly.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2hlailnml.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2vchqknnt.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2jynvcbpk.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dourtmgk.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2syggoyjz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjovdur.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjndgqdf.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2dybdxvll.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzoxjdc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbsovkk.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2agmhfndu.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2ocuuyzjp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckkcyyqs.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eltrjdjl.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzzryjk.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2xswjmecw.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ohpbxbqd.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzqovgy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdkuxyp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2wiyhwwyy.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdxjohv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvrgimk.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2spwjitvg.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2rbrmmuod.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2vslexdtp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xrukxcnn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lnxdpwel.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhhhusg.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xjlcnkmc.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2obsmfjbv.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbsnlhr.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2brkxzabh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2neyphecm.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtdkfcq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbltqrh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2txdvaqix.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qrltwajo.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2mlsecvmy.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iefoiywb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvpajit.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qxolbmmh.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2owahpjgw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrrvvqu.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fxilduvc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2oecdpetw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2iughuyff.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2fekurrlv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2twzcocem.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2tqekcdyw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2vccpysiv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2yluedego.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2mmoktylk.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbozqml.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2njeaiaok.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgsybfje.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2oszmqnvw.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2huaztrrl.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zncfmykv.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxoqstn.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcspmfwg.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2muplvvon.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpdydoc.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgpdoklp.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lucabuet.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2epcwijvm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dshydhlz.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvxjhfxm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2hklrbndm.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2heecvhbp.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xflcanoq.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tuubpfhz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwximbmg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2okdkihdf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2gdoozqlp.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2urocbyjv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmwezjq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2aadiatlf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcaldbfa.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqroxcis.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2auswaarl.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2svrvbduy.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2accayxun.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2moiqctgi.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fygdjczk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2bujhaomk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2fgygxmyg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ltegcbhq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2cibagplj.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlytfqe.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iaerxgtj.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhihrre.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kvekklut.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxznvbz.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2pwmahrnz.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucyezpbs.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwhmxlq.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkixvpgk.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwvchwq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2zllanqvo.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtipsard.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcpjlkix.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwrvkbsn.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzqytuq.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2ruaupzry.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2mmzhscjn.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbbnxyb.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2esqsienb.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2aepwkans.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjkxoygg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2pikmujjf.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2iuktwfdv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqeceaq.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwffzgp.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjstnrh.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrhhjqf.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2frassatd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2tswiabax.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfdtrfy.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2khuabomn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqssgce.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqsmnqn.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kttsgbge.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2pvnuchob.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2vtkcicks.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2hxijjfkc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2plhjqvaj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfghnuhl.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2rszrxazk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbslrwg.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2psvkmewn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2abluowfc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfkdihs.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2mubqjgcn.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2oobubvjg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2hxviqlwj.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxebvqe.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2ihdvwrhv.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2jocpasbl.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2lyadunxu.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqrkxoxt.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2aztrxmnf.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2fuyctuic.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2dkzqopdp.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfzntbf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ummeezvd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxlgnqp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yugjkqab.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxajkai.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajarhqcr.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nniuxioo.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymejahji.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2qoudjdma.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2kxrbntoc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkaqkqaf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpfamwz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzkcmadc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjrsdzv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjccusd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbckmmx.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2voqvmlve.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2jfapexdr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwxpook.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzwffrs.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwycyxfc.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2linsdhmh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2azkdrnoe.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gsususdz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejeeymlz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rvfdqvoe.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2wfucilsu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2henawqhz.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2epafqarv.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2yikqbvbn.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2xukuqarl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2nedvaypm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2kstlcomr.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2fablreqq.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2eaacqncb.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2sklkiyrd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmffvokn.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzixyfzx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkowafs.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrmwqmjc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxzgcxp.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2ssjljwso.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2uazkbikp.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2aqrvhhvf.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpbikdp.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjkyinag.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhdwbtw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2solxjsoj.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2iuzuflph.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2msqyrqzp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2joiascyx.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2wdhhcnaj.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvjpinz.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2yxlrklet.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxnlhmy.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2tninrvze.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2iphixslz.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwlkkkf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mcsyqmjl.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jdnrrfhk.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2ymascock.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtdfvjm.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2dttnafxw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmsxeiyl.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2jogstxpr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2pmebeqqb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfegpzjh.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2gapkadpc.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2tugkqfbx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2wymrerpn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2kanpzpfi.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxoujqc.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyeeyhjx.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2empghzxk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2cztytuun.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgjjcdl.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzvtlom.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnnybav.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2gdrtdljl.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvitdxx.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2afccujeg.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2ytnatxkz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2blfndmma.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzpchhfz.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2imbnwsuu.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyazcrgb.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcvauto.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qigectcb.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqvdnhh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2gfkjgksd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyklfvif.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2csrxddhk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbntcgba.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvacgko.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2fegmasbe.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxnlaox.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2suyqwbuq.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbolcqe.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2lajdpjtv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2cporiewx.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2klxobxug.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2reghhxot.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgkchiva.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcntkmxi.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qktopkti.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtvnjoo.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2elxhfkdn.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zvggnriq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2iloswcyl.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmvqeau.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2srjblcoy.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrvrrng.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ftkgxbiq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbwfgip.html


<!-- 参考信息 -->