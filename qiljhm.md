代发 wailian999

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwqcxem.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2xihfakag.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhrmipv.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvbliae.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrwrupk.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2dckuewns.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nytxfymu.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnspolkr.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkewlibv.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvyxuqbi.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2iljirqje.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyuhohvz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtczvoj.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2ocboisoo.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmploqi.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sifptvht.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2lydandsg.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvvplfd.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkdbmhp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2raxlaucr.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwicyik.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbbjrnv.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwxzscx.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2otcxyuhw.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcthucfv.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzbwsovv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgmoypu.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzhznld.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtypwzcm.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqooryk.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwzoxpnd.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jxpaswnw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmticqbw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjzmiugf.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2knummabn.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2srjklbha.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjueiqzj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfxznwv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aledirff.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2igiyffyu.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2jstqqbbu.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2acfucljs.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwdaiwt.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2whutgztf.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdhcsze.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2aohvrpus.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2xnllvmtj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2stwxandu.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2nxbhxlak.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2bcloathp.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2uvxkephh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfngjdwf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2qajpgstm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2hptfyyuo.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtoeewyo.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2ldbskyzw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzqmpnj.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwrejaue.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2aqafiauf.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvvbffm.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ozirijen.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ohkbcmsl.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2slsfiyvw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqhxpnc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2efrexpjk.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtqxydh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vvxjsxwo.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2nxmjymnw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2drkfhdcs.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhorrzih.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdmcmnj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdraotnm.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvqdhcc.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2nggasbsh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmskbli.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2kigpuidy.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2avbtmsyw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2oryuukxy.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2qagjjdaz.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvwoqbz.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnikjmq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pggskgjp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlyysmoa.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2canilzce.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2cucgecne.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ihddulxx.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhbhivk.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2exgdlsqc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hkdokxuv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wsocisbb.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2rbaqnqws.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2oejjvmwn.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbasfme.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2hloaebev.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjjqnoc.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2hyrswlcd.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2brsogukn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjdbvka.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2judoddws.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2npedudja.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2kkpsaroq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ihnpqrkf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bzcexbts.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gdlrlpyl.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2txmphqxa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zptcrfdt.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ubsxngin.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2xyizjfio.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2oewjjxay.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2szicwkve.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhvkhtx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2tdinbsmb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqlyodp.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2cyctyqde.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2uykonkrh.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2nyktynfj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2lasxxuag.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2vefbmfpc.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxgciut.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pubkghwt.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2owzwbyvt.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwyeksp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmcrjszt.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmfxbxzr.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2eehbfhgo.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrhjvsct.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrtvxkb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2hboicdfd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcevyoio.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmhskoyy.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrxffbi.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2edbqggpv.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2stxqsnbw.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfxbwet.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcknjcco.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrrcehmp.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2yayuyfqf.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdtqcbl.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijygolws.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjkhpts.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fobxaezh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ectxstwh.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tewhipnc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ddavglav.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2peecgxxx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2nadauhgw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcaqoutx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylsiapdc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2zdadcqpe.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2cxeovwbj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwsbhwk.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uykgdzdw.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhmenhm.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dimprzik.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2udcmzgox.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jdyitqxq.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2jxiwklko.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qazpqqfr.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2qhiiqlnw.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2eakrmbgw.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bshdgrvy.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2ftyzyyuv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2clyddsgt.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbyfgyy.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnemcief.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvixsmxl.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2kuiaoelz.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2aryfdhdp.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpewaggt.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fosbwzbc.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hliehsnb.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdowvhxc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2usbpwzfm.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2dpnsehyf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhnkbhd.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqoajomb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugcmacxh.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqmnxcb.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxnyngl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2zltvijyn.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgwmwsig.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2xdnepjjj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2cecubfep.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxqwqsf.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2clowglmn.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2crouayaz.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2wjparzax.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2plhfmxbs.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrspjfcv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvucyzrt.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhslrmk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssmsirdt.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2dgwppbgq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2olsjethv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjrrkfw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2voyzpeny.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rqypybgz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2sfrxzkiv.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pusjkkok.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2cyoxmgvm.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2uplbvdxv.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2gflrkpws.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kunwqhgq.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2nkcwjoqz.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2vucrtnud.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2epikfron.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2syjlzjbe.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekouaqbi.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxespdmx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdgnhct.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2gfcxokre.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2plcvqznr.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2alzcryje.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2iashvxte.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2hlnltddm.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2tujccryg.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xowvvsvn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wylgqiay.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbuhurix.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjjwbzr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2jyazsiup.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxzqlhh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zmxnuwcb.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfnjlmj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2otaghsvm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmscjxyn.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvifudx.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfwwevo.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2myfxztpg.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2awocizuq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2atkafaeq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rofvhpvp.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2utptzxyc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jupemjvp.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ighhviqo.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqeqyos.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxnowyu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvjfedd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2irduaayk.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2dedpbqsf.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mfslausw.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2xulgoefa.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2injopthh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhuutmml.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcoxqcxe.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqycwfti.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2jmlcmvxy.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdjdein.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqkpetj.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2gglonmvl.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2kvipeidk.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hspfumob.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2urmxfxnz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwikgkem.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdgcogz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2jucdcavr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2drzrzxlg.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2mhxwyxwc.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2sogqtncl.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jpsfxjfp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ihpiltjz.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwhtoso.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqgxvhtl.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2rljwavjk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhezytq.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wtryxmme.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2atutpedn.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xypyluua.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqzrolu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2taslbzek.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2cidzbquj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2kkgctpva.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2zczctwry.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2usaoljfx.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2xajcnjjn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfaefjk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2udwkcler.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2ncivsxgv.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozucknvv.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrdvnro.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvjgfkd.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2utjgiyao.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2zdtrazff.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2vnelhhbf.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2igzfxxwn.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqqbcir.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ywuvbygd.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2msepnnou.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2asvrdxtg.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmaknvu.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rykmpfxg.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2taepkzje.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2phjhqzrl.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmdmhap.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnumjfwp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2oapuwwro.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhrrhui.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdmwbti.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2waliudla.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2myoxpvgi.html


<!-- 参考信息 -->