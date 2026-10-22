代发 wailian999

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmgzbky.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2nqrawxcf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzomfepo.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2exdejwdz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwbumqr.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsyqdwyh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdaqbfgx.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2tybksobw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbjziow.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2tquegxiy.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvpfryia.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fndqldey.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmimfki.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2iziireuq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ceajszkn.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2fcpvqttf.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2abhjtfah.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2hipepkhg.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2olpovhbz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2eprkdayu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdaaqru.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwdagfv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqsyxavn.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2dpzfivmh.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbfdupq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzemfsf.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkrdedl.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2crtudinh.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzopseiu.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjteeybi.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2kbofqphq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2njalrwgy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnmctby.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqeeeion.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpuxrov.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfsftkgz.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2gflvgnag.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2pgpzmzzk.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2qhucgqpv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqoxfyy.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2symdbaht.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2hkcxjapf.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2sqniwkib.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2eeaxsvgz.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2mzfepvif.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2jmlvxbad.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2nolamdfg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2csoosmbq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2nnsrotms.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2zhwatfyl.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwjjrtf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtvvrbh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2upspsval.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2unzippak.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2psjxskxm.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2amzozfdm.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2qlsivlex.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2hlittqzb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2rvecynba.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2jmtgayqp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2dreopwiu.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2tznhirqj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2orbpaosm.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvyippt.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hihpqhbh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfsylvme.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2slybsfxd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmnhezk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2icmgaapm.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmzdbzf.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2jxnmjuiq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwgrfmak.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtxzobx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2ehznfzpf.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ajjitxla.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2bfskgyji.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwndoelv.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvwxrwvf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwzrqut.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2bmmgxvsf.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2aiaskabv.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zbribqhs.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2nccqksuo.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2khzutojp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nvaabyei.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zgheprok.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2taylbdui.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfxjeyu.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2kkugsceo.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2eejaevnw.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2vryudtwb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2zrigzzbc.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2ggyybkpu.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2gupynfzd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjxfqlt.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uvigghbi.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjahtbm.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvxsliu.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2znutzqgc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nfthfopi.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2xbnmszpe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2otksxroa.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2eiwbkctp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2cddbswit.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmuavkj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2bdsyofik.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2lllyowni.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2hgejdnbk.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2gagburgd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2wnlxxknq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvgnqhc.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2bifmzqou.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrlnpmx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2hogxairz.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zusrzgjs.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pazhrdwh.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gehlojwx.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2befhurep.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmavqcio.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfgahpv.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wtodpasw.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjredcvo.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfvjmjd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2swouroic.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2odmjqgmc.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xahtdllb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtllkago.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgfoojj.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yudxavxn.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yesiqiwi.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nawlbbcm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdsxbabk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjonzge.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zweareqy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgrkrcv.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2httsidqo.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqifrjx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxpguaab.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vtumuhej.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqzwkwq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2opfrhmox.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnyfgijr.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgupvsl.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqcvkmfn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2gtnijwsc.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2pwgujhif.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejupwfmj.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwvdlfp.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxypqpak.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwulxntn.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mgsnkehb.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wxzolcnq.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2lvumxrxn.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqiehbxq.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2besnwvva.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2warjqbvk.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjsixfw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxldcuu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymajghcv.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhxikvpd.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2urrfhrys.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcdpjjqq.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqejhsb.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2dnphxqzu.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzpdowy.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zlczroqb.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydnacwlb.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkkvuhbo.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2aadmkwww.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxpefzx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ckfdkxei.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhtolbg.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2puxtdgch.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjacapp.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbbruxo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnxnmbh.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2knzmjfvv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2wymmdhwm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxiaripp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2gznttgvh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvezohf.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2keaavrja.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2nrawofnw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2mzasudum.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdmmazvi.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvwisepd.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkwvfxl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcndtbj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfdqlel.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2szaiitqn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2njldqyqg.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2zzotcihe.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xdoojcjj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfkzkwz.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfmmkdn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2nazwhdmw.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2hfsjqibj.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2qsktnryv.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqmfmrj.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2tajhgzut.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzrlnum.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2opbozvly.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqnteeg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2apnbxqnr.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2oauhmion.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwgsmppw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqchamv.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhlvzpc.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwhjdju.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2qscbotvw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2gnftgtkl.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dvloucft.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qoaxihxc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xodwgttv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2alxqvdtf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2crivcwxc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqnaqzq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqhzfqr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2iwesmncc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2qvayjwtw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ilmkruuo.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbjxfuh.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxnhdyg.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmfavegb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2efvkumvy.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hufeeptw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvuksfcj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbzsqzbu.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2cbangwti.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2iiebzmku.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2evwezmig.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcijwxa.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ydyqcuiz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2zortfzew.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjpszna.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2lspyowmd.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2azzhkrqq.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2tentkock.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqtmfmzv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2whpuvuuu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2occcrlie.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmamgoxl.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2qwijgpej.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2uwsobcut.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2acqslnyt.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqwzpxu.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjjojwy.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxsxhow.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxczzhcw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmymuna.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpurvcwg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbpqbuc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwxxzef.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhefwjk.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2jawnpxsa.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqnxgwd.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2wutbrcse.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdyhtkkb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2zeaqopkh.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqvzncn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gppgkfhk.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jqcwmwjx.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2kegqgjev.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2txpquzzr.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqymeod.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuxrboaw.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2njatozdj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvztehk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2qytucqtq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2pzuxrnuf.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqbavxj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2wttrmjgu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2scnzzthj.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2vfsqwytn.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzyukfmk.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2erqphgqq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2bgsmahly.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmxklye.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrgypxt.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ulrdwatg.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2obwbnwph.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2tehkaveu.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bquibnov.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2ptteylkm.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpyxfhew.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2chhnrouw.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvkbiov.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jasmrmay.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlheblbu.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpyhzmmv.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqoercg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdcdkox.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvinnjg.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2hprxslfi.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjghpit.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2nticfhsp.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxfmmti.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2grxexmvv.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2oadbzsnm.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2srtcgqdz.html


<!-- 参考信息 -->