代发 wailian999

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2nxlvdenh.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2qkztacyq.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2ueblhkoa.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2yjxudlqc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2igsoocyq.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2lejpzopz.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2pyktaggi.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2veoqoree.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2olcgbnhu.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2lafrjfcc.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnekkdec.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnpelhb.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2obrdmord.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2lamwgdni.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdetzlb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2aojknomn.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkpqvpgk.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2brsavvtc.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2scnncbyw.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wswssjqh.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2onjtzxmt.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgacepvj.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ptskofwr.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjnwliv.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvcniudx.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2hjefvejw.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2iwnovrnj.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2exkfcvxx.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjgolihd.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2djofiadw.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2clarfoct.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2wnnyxqpl.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbuwxevd.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkxassv.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vniowakp.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpcfutd.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgzvptdr.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpfbponv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpvcnhf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2ztxirtzz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oggraejq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxyklsx.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cibgcyhm.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2adfnpvgr.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2aczeszuc.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2pebkwrwz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2qacfujdp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2tizbfyzk.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2jecrhkzp.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ghpssrwo.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2kketemzj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2zxcwttkz.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwympqv.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2tqgsfrox.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2faeywzce.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcmbjgai.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxwktmj.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2plrswikx.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2jovrtdua.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2cjulnjkh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcwjvlq.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztttzmup.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2oprfnjio.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2prgxdgwx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2wetrwgjb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwywpvb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2eaxuhpyq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgzgblt.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2pffqysto.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2webcugos.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jbperqao.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2tpbioprn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwcozrr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgxgvck.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2oiydgknd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2latohedb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2amknvhde.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2ldbcfgij.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2toybvief.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxobzoz.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmddqaj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2rqsyglfx.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2wxglqono.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2omoacqzy.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwomvitl.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfanwesy.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2iurjqyox.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2hjggtxlw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqpcuhy.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kyrmsijf.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2uckwrhcm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpuyfizr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cmymgmhf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bajglxip.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2gncewvjl.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2cidiaris.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2nhnxwunk.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkictmsr.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2twdvpqyh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2bdovygyv.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtseznb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2gvrtkuwy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqhfhkp.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2toqtigge.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2oxnaxsqh.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xizmezsg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhhfvgd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pklinzox.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2cawfyefi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vuysxjdh.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vhemjczi.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2nqieodit.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ithphgjj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2mdnscxby.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2ysximmix.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2bhtchvww.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrejhoc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2agdmqlju.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2wpucqgil.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2yutlavas.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2chxmwgnf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2nezkchdq.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2abqckdxc.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mepesmyg.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdqqptt.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcejdbvj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2itrseggu.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfciqij.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2iphzkatw.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2uiejpovo.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhkokowa.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwyafex.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxktbctt.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnrbxzn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwglrii.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvdwivh.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmkpguwu.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2llbxtkvm.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebkoyopq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwbkspnt.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxljyna.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtbgsiy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpcgfvcn.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2pchrvhpt.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytcbgduv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tncxixlf.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jgibwffw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2hebtxsgr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2cucnhozz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlsiozvp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtpoljiy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2utsbbhsd.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2bxynoiji.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2itagkear.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2nysggyfv.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gcurkjlw.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qltsdjtp.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxrxbqb.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ripoibze.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yrnwrwcy.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtiqlto.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2obxcfixq.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2awnpfqyy.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2izuisilv.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2htzthpyj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2tsoeurxt.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmedyaq.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2igbwhsaq.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2huoslsgl.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dykobhmd.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2eqihugdk.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2zokctgrp.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmekcgt.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2syysldhk.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2etgfcnfe.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdkpysv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfzfqkj.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2mibfkyst.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mydluvfv.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvrwjahy.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdhenlg.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2obphjils.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvmusaf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjfesni.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnhgqrg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2rkkkrkcy.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvgomiga.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkutokjc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdoognqg.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2zqzmrdcp.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnejugf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxurwhr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzgkxlv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxozlcx.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2remqdslx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlriobb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2jqqvmtic.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2gtqpeqsm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2vazzspay.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ucdmajht.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vgoorzlf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2uxmvwnuw.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2eivqirpi.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2qskuvpwy.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhutdwn.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbcvwuk.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2olzidyvi.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbpfjii.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2uzsgoymp.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2qynftmto.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2qpohwpli.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfigrldb.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbkydxl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2badoflql.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmhgxbh.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhiddyni.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2oixjluhg.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkfjohr.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2kwrajuye.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2kcpycfql.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uyybvgxq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2frecqyjl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahtdmwfn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hxuffrdh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2zojxsutb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2drclvveo.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ddqlzxaa.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2hpcmmutf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xewdauas.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2iornfmbr.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbcltdmc.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibtskfqd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ccpxbpwi.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nyzyiuqy.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2szrwbvpl.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhcyiiz.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2lkixjoqo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2woissvgq.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2trpsrlcv.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2fuioyywt.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnjxkxb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2okrjhsbj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2krldnqwe.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhbzvfa.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqrecvs.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2awzqtobq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxemwedf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kecoecma.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhawngb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqojcux.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2conbyrry.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpwedbq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzepfik.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2vwsryhxz.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhkwzli.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uupcuxbr.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmooklou.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmxrfzmy.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhleuymm.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2oacckkcr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgqxclk.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2unganaoc.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2qbcpljly.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwqczca.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ucgztxxg.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhoebyol.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2rotwjlrw.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2wgcmoynv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdhscax.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2idbxwzjn.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2tzgbwaty.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ttfaepfn.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqtibgg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgebaese.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdyuhjr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrvrodt.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuaqnswa.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2eucedimx.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2giffsshj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2aflztcwl.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2lrmuunlp.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2gxufftql.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzhizyc.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibgxqijd.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmolycp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kvozzmbs.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2jpastvvx.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2cljlzgrc.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbupjsa.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2imojylib.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2iivipddw.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgqixar.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2weaovrnf.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qeserrzd.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2oynroxns.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2amltxnlo.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjkxtca.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jeiuppqg.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2riwdkvpo.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqpiond.html


<!-- 参考信息 -->