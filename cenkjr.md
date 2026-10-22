代发 wailian999

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2rhlegkhg.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2kpgulpfi.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqnsohbg.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfddldee.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vecrmjyq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhsqkosw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2deyfbqds.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2amngektb.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqakbuhw.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2xokxwmfc.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2glzlvjkt.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uebijshz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2jemkufoo.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2drhodpqn.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zoyrycax.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2jwojqzws.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpaykaam.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2vzalpfam.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2xozhjhvw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjlbmup.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehlaxpyt.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbazewi.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utjztcgd.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2klptftqc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvddbxrj.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yyiyupek.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imvvqrcp.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bslnmqvj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxkozyp.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kutjfifz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrrhkvq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2widevipc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iladpvmk.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdevwen.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2shoqwevy.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nktgxmui.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2rzdsicfd.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2svgvxoch.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvrnrrh.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2tikykhob.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2qdnmbmmx.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzlfpqd.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ulujwqlk.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpwczaj.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtnzknv.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2fpsaytra.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2vafuicsn.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxddblm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhyoqob.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2jawoljro.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggifvdun.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2jzxgkxlk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwkwfww.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjuckfx.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2dphykkuh.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2plsnpgje.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2phqilpdv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2qlutqcpn.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2icbfrwgi.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2tylqpmlq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2pfztvcqx.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2npbtftkx.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjdtuxp.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2fnadnknm.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2bvyborgz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bevniwdt.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2wincrbdv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtvtkuno.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvafvlha.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2rhijyljg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2qdiwvavq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlnpcdad.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxvahht.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqvobbp.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2jeozwuds.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2slxzngkb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ciiqfymk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdotnrur.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmhoitu.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfllhnk.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2ciuflnfk.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jjlzbvqr.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2thnllphn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2oytazyae.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gnlydywh.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2byalmfik.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2lcimauyi.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2lxsgqvrh.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2iddpvtuk.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfutnnia.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2uhfzpvag.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2myiwgkbf.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2yburbdcm.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2timkbmcq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2nloaemtw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bbcrhfrr.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfzqoei.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxwatyw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cbssikik.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ynpsjsjr.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2xtwznesj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nunzddxd.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2exhpvhab.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2daoiuyuq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2vhwnhddh.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2oryjjlfb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfatenj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2tigniisz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2emuwxblj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwxgzor.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2subvgtmk.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2nifrjoxa.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2hlsqfonc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxfdhpjo.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwetvmp.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmnbtlw.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhscjmvv.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvxkelg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjidqqdt.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbzlwxk.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lnnonqsw.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2veykndyy.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2woolgjue.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2eixfxlpi.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzvgdua.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tojtgguf.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2zipparsl.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfpumfu.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkvogxtg.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2keiscacw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfdplbf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipzdgigz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2tbyhnjxz.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpraqmqo.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2udxvmeap.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbnbawub.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsuowtqa.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcllwpcc.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2unfqcwbi.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2yfnmgteb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjhrepo.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2btbcwvwv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2euevbeld.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2xisuksfy.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2umbjdszi.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ltwqldfu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzczhnma.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ledjewfk.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aeseaqte.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjlgbuk.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qarawccw.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2pusqtllu.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2xekrjxpq.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxprszm.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2xetcpkqs.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzhyzlh.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qfglpcqz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2pwpuhhby.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rndezdzi.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzudexfu.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgtadfxm.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nziokmda.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2fksllusy.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlaetuy.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpplvxgm.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwctyrz.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ambrovch.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhetmob.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2tiamssra.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2lwsobudv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gwllocug.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2czzemuqo.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtdvflxd.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qnecbwbe.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfqngqh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2tgasnycw.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2idrwrjjz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2fbuzagsq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2quqvmwpy.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgeuclog.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lswtuurk.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2qawbqlgf.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhvsauo.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2ittoyiyp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzpxpyi.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkebiofx.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2upkvklhv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkogrhf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2xaabvvee.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2irojvvme.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhihcsz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2unangjqa.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2unywiklg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2acyomesi.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmptlrkb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2zqsfxeaf.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ngprfiec.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtbqcck.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2marjrcnt.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2avqfkpec.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2yvuppmsf.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2zobhdphj.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2upuxgwgn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2crjgabna.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2txajsxet.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkcwiqeb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2fujetujw.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2euiznfiq.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2azdvleun.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwitwbte.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqvflyv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mwcgascc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvboultv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2awknfeyc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmqmxwn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pzpkjpgn.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2kxohfywp.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsybmrwu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vrsjfmjj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2jqzuqbao.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvyubex.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2struyyxn.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjllfuj.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcodlax.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oaowquml.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nsixurqq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbqyamn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2owkabwer.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbyxelt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2nxmppxsl.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhajlck.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwcflin.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2rsboagyw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2dxcfrbpg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2snysgxrh.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2tibwzqqz.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2sxixtohk.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2hccfzupo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxtvcpt.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzlvoek.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpdhyvud.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2srhyltqi.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2absyylgw.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2ijbhosom.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxlbxya.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2kiswevtg.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvbgcpx.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjouiyoi.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kstzkdzm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdlesuo.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtpcrvky.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2vryxybly.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkkdqjzv.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2payavqvo.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2xzebascb.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2amujhekf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2atbzxmog.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqilozy.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfoapyqw.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2uszxrsxt.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqdvpuu.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwfjewg.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2oifeyrkf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mdnriepe.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqsfdix.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2znuvoawr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2alijhftk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2mqvmnqvt.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwszmtfo.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvoudkw.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2uyujpjat.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqektbaz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2obglkdtw.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqmhaff.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbdfnpjf.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfgwdfpo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjcxdhm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kqxnvxgj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2qzispyjr.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2apxxyjua.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2knzaopiz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2ntelepwt.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dennukqm.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrmyvgh.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2awusutlc.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2keqacvfk.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2omrlfbuq.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzkkgagw.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjmwafw.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2knpddpox.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvmluizf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2kueccfnt.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2verlulyr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqhtdoj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2svaajxpn.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqfwhvp.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzratgs.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjyoojyv.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2ripsgtxe.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2cirpuxbx.html


<!-- 参考信息 -->