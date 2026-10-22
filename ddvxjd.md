代发 wailian999

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nicayvrm.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2hydbolca.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2nywbdqvt.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlgysntk.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbtgrsrc.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2akqwlaga.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwibqnvw.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sehltchn.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2hipoajed.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2yinobkqk.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkhhwpt.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2yorexmnp.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2jevqdkzn.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2induyjge.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2xjtqdkzq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2navpxwik.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxxhfej.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eficwrdv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfmmybe.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmsexva.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mubuwkov.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gctfaprj.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpeuvepz.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bvpzaufu.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2epxbfvto.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pezuzfae.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2zchplzfb.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhhwdkx.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmhptue.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyvrxlpf.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcssrtsd.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wecudfas.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2sdffhzrt.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2yrggykmr.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2hcttaeyo.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxukvam.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2rilrdgbs.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmxqfah.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2extnrszb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2gmuuesvs.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2tisbcfjw.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2jetzerrr.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2nivcdits.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtedzak.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgjwbig.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2adjrclal.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfogewbm.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2pleckyir.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2octggkvu.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbciiqqt.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgcwxcr.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2vyynmeqz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2dthlzboq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2vccjetxq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2gphtncfa.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2rktcvnlz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2woyfcizq.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2eodyakub.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fsuoqzix.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjhxehj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbcobqb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcgqsdl.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2wukunxrk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhpcsfkr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2diewsmbm.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2clipswtj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2lhuhinya.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfqmely.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2egplvqhi.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2rnsslium.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2jifqthuu.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2jppciqhw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgboaizw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhrddruf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2siofgsma.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2gmvklknu.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2invluvit.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vxpneipn.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhaivzl.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2okwpvilf.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xikjocez.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yzakbnnu.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2qrsekmie.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2mabcgxbz.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2uengezvp.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjhjlaw.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2vdfrrost.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnvglja.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2weihguck.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2phgmdpfk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ppnlycsn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtqxeic.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2lquroemz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhwdwld.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvqqtlh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aopwczsi.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2rtdpubgd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wvqufokj.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hljghzdz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpydqoc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2tpoeupqd.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbjsqrz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2jhyggujz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2jtszmpcz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2wzowoedc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2dniwsvpg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2oqrmnwpm.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpmbfex.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvuifce.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgjjwojp.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dutpnnfk.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhdjoyh.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2egpfqstb.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2eaasjlvt.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfsjndl.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbqrvedh.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvobuin.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvoknvp.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2issfmbqk.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2slcnlawl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wioruimc.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqhvipc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgozsdps.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlaewyxo.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nemxwhmb.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rcnqtkcv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jefybnck.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgzbixe.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmbxbxp.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajaocucc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwfudlu.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2tptnzjwf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbvgorx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2scfynxif.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqaotte.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2hizrjkkf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2seueygjx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2unxiavdm.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpifnvkk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxbdpga.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2uydwzrbf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2jxlkkulc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2guijpguq.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rbcpauhe.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouclvkck.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvtxsjhk.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2welzddin.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xfufqivp.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2exqwslnu.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwywixj.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2cetsgttg.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2pennrpmt.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqdyfjo.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2drvpmfmy.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjtkqrl.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlelltkh.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2aahbmexl.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnhaalah.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwzzztr.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2wfkjwqpa.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkdskcrv.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgedmpr.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gswvooci.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2mptlcbtj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixulszds.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmidqbm.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rqoksuwh.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnciwbnq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2glptaaik.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjqpgbm.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2jdiswvzm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxmbiof.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbpeegq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2evkoxmlf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqwtnpt.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlfeknn.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iukldnsl.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpmzbpy.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2pmkwyfrl.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2ndiqelog.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdorleng.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztbudoey.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2tifbdbfm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2acpdsuqh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ethnflbu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzhmwdo.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcunpgwa.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjtdzti.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hvwrxkhi.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpewiwc.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzgniwro.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2vuswqtox.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2chpmotel.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2hugaownz.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vekrqpeg.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqqzhnh.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2qaslioax.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmmiuqb.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxdsgoe.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgxvlxa.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmjtjkh.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2chmxkfuv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2nbctomct.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2duihoolu.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdclqdky.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohiyvvzf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2nbujcahq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqkicos.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2shdluqpu.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyskwkdc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qemdtrwd.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hectacpo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2dupevxtr.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2czkriuzh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ericoogl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2ihbizcjt.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2tahscsic.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjzmtsy.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvwfnaxh.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zodivfhl.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2krtkihry.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmqqxdf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eatogwva.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnwxlso.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2pvsyhusk.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vrojabhk.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjrzklb.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrpmpci.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkxcfrp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2lgtbmhju.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2pcoktthi.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwgftvy.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bpeltkho.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2tdreaace.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxuctsim.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zusugded.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgprtiws.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkxvego.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2zazaufei.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2epynfeop.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjnqhcu.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2idootgqw.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2mrghqbds.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2axbuzmeq.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2frvuwhzz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqknwvgq.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzzwykig.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhqswrz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgnbrgcx.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2itauylya.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2aljabshy.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vwghdpln.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2umxxzkad.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2xosnkixo.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2lratjtfh.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2dxevtitv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lfaxvzmg.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqgkhhe.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2qxizxlqn.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hcyzxnhm.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qasqjazq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylkvcuys.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2gajzfioi.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2vijephet.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjztndt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhurenw.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2mdkgdwql.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnefyzb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2hbpfkoay.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2uswrtwdf.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2atbxkiab.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2aslvpdwi.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2koikxkcj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ckcnucrg.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdxvwrs.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2wlqyabjt.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2iiydahmm.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2eabmogzh.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgxzenc.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvruslj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnncrta.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cujsglhs.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfbzher.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2frxhbtii.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2msyzsrix.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cograpmo.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2radpinih.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqwzcem.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xoshzelr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2eyoodqjh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iluhvxwg.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2fskvwwrb.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqbuzgn.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ostrrgan.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmznvfj.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfbpblrn.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2wknznhmo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ceavcamp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgbxycvs.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgondzw.html


<!-- 参考信息 -->