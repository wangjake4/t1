代发 wailian999

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2pmseaeus.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ssyiksds.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2txmrnygp.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2vdfeprur.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2mzimzhhp.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgfbjge.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqufiwqs.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubuhjjsy.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zktcuqpx.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynzziizh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvxicha.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvpgjob.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnglphw.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2dhftqbtm.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2ganjxwyr.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkprgalt.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfiyedrl.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgucfxyl.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wzaysije.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2szpgqajk.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxbnbhl.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2mrreeexf.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2gzipxick.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrvmxey.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyjrckif.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfawxkby.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvpfdwu.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmiqsra.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yofqcvmq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tgbuukoo.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwogzsdd.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mocqyulj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hohestaw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2onelvtqo.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2sywgrytw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2ubomqnrv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2whpnbdbb.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bewhjhoq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rygjbiok.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdmjbaat.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2csfdfksd.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvntrad.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2yqesjiwt.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2avdztgdk.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrueest.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfnnrbo.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbdgisg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2bolvdtfl.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpmlcat.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2bkirziag.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2worgaqts.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcbvzvb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2pfdvuwms.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2vlczmyen.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2zckyvzuf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrlkvmo.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2yaycrkdh.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtslisag.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2xmoxnmzy.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2avlkhzij.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2sdtvlmvw.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2iofuqvwc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjtqgqb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2grcjxypm.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2ekslfeck.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2tgltlxrd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfahyst.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2ghepabgb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2mulwxeyr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2icbhbort.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2mrcixffr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2snlbezpc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2usqtlzjq.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxcjudt.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvcldao.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2oktwwheu.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wywpfizn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqybduk.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2zzujtjcz.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2mkvvtfpn.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcalgtrb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxnuiows.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcwwwjhz.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2vcqkttlg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2pqavnrww.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hogbfkam.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxgxlgr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2abotyzvh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tovpdlnj.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hafsybys.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2itjcisff.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2kuctkvhb.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2whiouqke.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrezwuo.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2cooxpwhy.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2ffsyzwzl.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2bgfqqpmn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkdlgow.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrssdyw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkbpuzj.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2lparwvwd.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ojuktlpu.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxklbfb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zxdwuurr.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2dbpngovo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xididumh.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrrzfws.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2tzyazqym.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2zbfzdwge.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2sukjzvde.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2fttlsxgb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2snlzqofv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2hugcxkmm.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2rknysxts.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2hiphacee.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2usfkkkte.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2zoyccums.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2irxnncek.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2enuazkpl.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2syavdism.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2iujzpoar.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhaimuh.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2yshzrntg.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2keqaufwj.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fleupxfi.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbcdtqcc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2sobnjkns.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2ittyikxl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhkyasw.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmraxez.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2amljnnvd.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmcnxdka.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kckvfjvw.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jpiowlpv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jutczmow.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykletfgm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2epnjkrts.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ioaimbsi.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uycvvhei.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmymreh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufiwigkt.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldlrgiwz.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2koftnnkr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2gwkgwjuu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvxzapz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnavviac.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjmikglh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjlltevo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2oudepdly.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnkfdlx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2oisqeuma.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2huhtooho.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lebwkirm.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqqzcoc.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsdkijw.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2aadzbfoo.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2yryueuiz.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhkeyphp.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2husfnwzk.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2zarhztah.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2yxijrodj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2fyezrcql.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qscidsqt.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxzgfktu.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2oymrcpex.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgayywkv.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2jayokpxc.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2epjnqldm.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2udsjvvjh.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jmmivjtm.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfcwsycd.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2oloxfiea.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqbajjq.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2fesyrfgp.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uoswdylh.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxoyhwjn.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwfqgmqe.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rfneoava.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2levdxkwa.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2efkkglaw.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2omwcqctw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2zlddfnbe.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbsnobtk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2nubgjgmz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aewwodqu.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxqfxxu.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2vwldeolf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzxojzr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2quhctngy.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iosbevsw.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtmynaj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwkjhkz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2otjardgv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2glhjwlbz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxfgbeb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2jetnrwnt.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jpaaeube.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2qwmnbpwb.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcsfqshc.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrbnrjj.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxvfzxq.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2gldjrgbw.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxsdceoc.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjzxhec.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2aoevtpih.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2liifcgad.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2tlobmctn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2niwealus.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2oaccjpij.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlczhba.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkffwdu.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2besehxpu.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcdefzmk.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvibswjl.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2zznzvgbm.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ekyviclx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sorxghaq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxsbstt.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzoqdezj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjypdbc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2seslwejj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhtxnol.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fllqzhgf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2skrzhdiu.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrhymiy.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxgxjtse.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzenebyr.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bydxojjr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ciemxxiq.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lgydsayv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eecudvyt.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2utrbwjwn.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbagaqd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jmmeenvk.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2skkpzoee.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ewcbmiav.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxhlyqx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2tmegvsrj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2sbubmjth.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbjglkw.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2roxmqzfp.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfgbyxm.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwqjnjg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xuadndyf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovuesgzf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jeeczhsy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2lszloojt.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdfabzb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2fzbfnngk.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwzwifa.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2eptjcmij.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhwxndlq.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnfhaah.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkrptcf.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmgtuuaw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ysszvixm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhmngsda.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2hnibdrqi.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2ahspocwu.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfokfsp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqvqqah.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnalkund.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvmriou.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2bokmijdo.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2knfqbezb.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbqlxph.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzeptjs.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xxffnnof.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zijcuvre.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgrbimeg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2vjntrhht.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2gcpczwmd.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2faynqxev.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2roefnrry.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2zlohdwaz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjeudsy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2octjjvie.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2ruiqhjgj.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pinkcegf.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmiqshma.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ixaupabw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2nroxyaom.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2flwktncc.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqnqwif.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2wvomzjil.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2eswponkf.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uipwxemf.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhnznob.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnijoewa.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lljwoluc.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kglyzjzq.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycojanab.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gclokeox.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhceodg.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrrvxpqn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2iolalmpr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnocinjz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2onywipmo.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhhndabt.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhtumpj.html


<!-- 参考信息 -->