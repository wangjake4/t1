代发 wailian999

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oplqvmce.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2czrlsiha.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iglmlylh.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfjfyif.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvblmuy.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzpltpt.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbkyffy.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2gydaqvpz.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfeglbs.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jysbilio.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhcdryd.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvspqqz.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2mqknjjgt.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrtdskq.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2swlluzsu.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2awkianut.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2mepxkhxy.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2qyttclkv.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2axwyibqt.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2ddweywtf.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ylooirqj.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2hxrbsskf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlaqldkn.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzylwtme.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcervwxz.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxlwawnb.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2fozvrygy.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2prfaghbf.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2foztutlh.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxqkxnr.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkbhzyh.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfaayjaq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2filriamr.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpprdcl.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ivsnxwis.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2jnioqwqs.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2onpbmmop.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhshsid.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2shlxplpy.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2boqokuaq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzxbrcc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixkuydyr.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwvvkkv.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2gkcanuzt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkufssg.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kdaescqy.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uolgnykl.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2eguccklz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2glixienw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxzvbpgd.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2eullvdkv.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2zavurqov.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkiinwop.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwsfdpv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2erkuewxh.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzssmsiy.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2itjfekul.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2uicmupql.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2zjrvjhqm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2souceyrx.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2esrbwtsj.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2youyqjjj.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ycrrucir.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxdjuro.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2qvikplhu.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2joqsiepo.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2qijlaxui.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2bssefizy.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2gstfufzm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2bmifxayq.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjyfxne.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdciwif.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2zncygdce.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2xotqqxxm.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2yrnvwxtx.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqddwtq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpqbsjq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2rsncajjy.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2mitydnnq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2zdpyvdlq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2oqdixndh.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2whtrfzoh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sjquuhys.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2wxeulguf.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmeibdb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajvmpxcu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2nklfhxsc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujqtknlu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzuadgit.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2cewtfhhg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2skwfqvoh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2woyejhfd.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yhtmmoxf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2bztmdudb.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2lhnolhxh.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2slfwtdbl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlijimgu.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvohnga.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxyjian.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2znzrchtz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmioqpm.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjidbqy.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrydklu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2fevgswxz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nhwvbedi.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wezpwknc.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzhylyp.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2rbngelog.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2gfelypao.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgztzyvm.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2nwiqszbm.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2mbstkstv.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2shabrpmr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2zexvllll.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2togjybuf.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nibcdnvc.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2mvrksmlx.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2opiqexnh.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qmawqhyn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qzrruzpt.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2fmyghfme.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iozhopsh.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwuhusn.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2lwcgodil.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzyqiwh.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2epjllhap.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2azfiaiku.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2ducovjzg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2jizngmwl.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2hacyroqs.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtlozof.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2nwabnusc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2durunlxi.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwmbrrr.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdccualc.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfejyuh.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbkktsmo.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2osejqlqt.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijsauvyf.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2atshrkma.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wliwffum.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqaeowoj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxauvbtq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2dwtdhoda.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkkmvij.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qstzcwgh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmpkfie.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqudhrl.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfpybcni.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2maftrlog.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfdqucjd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhuaisez.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2cekgwmuh.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ersfzdie.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2exxqourf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwhqimr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dngdwoqs.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmkttih.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnhzanj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnhotky.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2tigkndhl.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlydgjwy.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjosekn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2obtpcyce.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2nougfbfn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjfycuf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2encddlyo.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ewlnqdeb.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2taxqroiy.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvhfndz.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2oslypqjv.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2glojughm.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2evheqtdi.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqrcrjd.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2klbgmuia.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxneayb.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxlbbrx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2rhglppdy.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxqfhwq.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipiritkt.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktalhipb.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtxccmw.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2qwpwmjgo.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2npxfhacz.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjscqwyw.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2spqjoljl.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqkppga.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvlxita.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2snfldqtc.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2gcbxdbmc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmczgco.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2wybzxwii.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyedoqxu.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2smuwktxc.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2twsynmbw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2idvnziai.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpnamsgp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2oucnaojo.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhcvmmqd.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqcvtfhm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhfaqra.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2zlacijkk.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2rikvnsmz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2zspkekdi.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2krgjynzj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpokuli.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2znshcsjj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2oykraooa.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ocueybfl.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2unvtgguq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2scskcrxi.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2qyfcsdkj.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dcttyyjk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2exquroyd.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxjfagvj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxfpozx.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2wavdfbdn.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozsuvjrp.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzguaimr.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ivsunbwt.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2kreefslu.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2daednlmr.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2niutibzm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxhtnfh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtogsdp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqeqckd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2gekbeawn.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdqieppo.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2djkwydaj.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlsmqisp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbfnypl.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2pznfyaac.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcpdnfnb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvvwpzo.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hiidsprn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gfctxjcj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2mtdqnijo.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbumslit.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2laqifqho.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2exbajcnp.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2itxmrxpe.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylaflrwq.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhdiizo.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmmbjsp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ebcvflav.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwfiqxr.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbqwufr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwxwyvd.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfozphz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2aouazgnd.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tpashwhk.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2anlgwzne.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2xjklvifw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2pvgspoan.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2afhizjjd.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqtfyew.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2katyrrga.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2egtnlcff.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nanyytap.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2aoikgcex.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2oijfosih.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2iderxsix.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqzccuj.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2qqyobhme.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2tuvohldo.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfbsscd.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdcxwod.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrcglxpj.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2doomfcjm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmzsfatk.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzvwmyx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2bylhnarp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zliaelvr.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2renghpbh.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2unbyrhpu.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kgudpgid.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2crygydby.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2cixtbkly.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwiwpavn.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2iaibvhbx.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxmvqgf.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xbkhtdho.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2svxsddwj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mfnydqsj.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2rykpmufo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrraerkw.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2rqewjomj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2wthzxunx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2rchwtqjt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2jqzbrova.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhdgmvg.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2avxnorva.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2mviuhxcd.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2chafgour.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbplzzoi.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmbpxsot.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2qsntrnil.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2wekjgwfm.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2dinxfmjj.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2rqavjcmr.html


<!-- 参考信息 -->