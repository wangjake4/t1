代发 wailian999

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2vxsajnvg.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2fpoyukvi.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xquqkrgg.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mggvmsqo.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2gslqvbhm.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tttiknlv.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbhvrhj.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2aoektgsc.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihujiqct.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2jverrncz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyndywdu.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kypikdbu.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqytodzk.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdsmvpnn.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2izmudunl.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2rnveupem.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkrgqqp.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnbwryk.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbxrthn.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2juhifpwy.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2undnjoua.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smvnmooy.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucsrjzaf.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqqdtzr.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhuyikyz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ngczongb.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxmdriit.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2astjsshx.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfrjlve.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aipffrdd.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2iqykewnl.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2xikaytye.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvrpxeyb.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2okjefupv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2llrgwjvj.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmiqmdy.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2hdvivgmh.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxgmxtz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzodyiv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwyzysa.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdxggki.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2pxoxdcfw.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2akfbbumi.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2mybngvsp.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2lewrecdo.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdmtyoq.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2exvezlrx.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2eshmqutd.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhlliwu.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2jitmvkvy.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkghibc.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2hegdwfre.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2mnaxixos.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnflinax.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2veizlmyd.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfmoqmz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ssemmhdx.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxjavln.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ttevparp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcqjhqh.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjpktif.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcruxot.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2klkquknm.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2ljxdxhel.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlaudqc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eiyryzqt.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2xsubisuc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwcydhs.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2czcinwbx.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2birmnugh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2rakxcjxi.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrmvyxz.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mobmsxqs.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2wxizdycu.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2muciryxc.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhnlcoj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlrggqld.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgnnqqb.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2qahpefkk.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2yistraae.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2notpbslv.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hvkcqbtl.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkzhhxs.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxaonrlz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ysarfxye.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2glhccpks.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbeiojy.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2mrapxlml.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2oggvdiwo.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2iedadllm.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdscytr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2rznyhebi.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2wcoqfbvt.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2komfkquc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2sutfpxlu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yncojuma.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2fthscyfg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gcstsbmm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfqqjef.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vpozaqln.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2ujyfljou.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hnisajlp.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rywogbgi.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2tspmlvro.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrjlasf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2pvijbjlx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2qgyooxuj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2piyfoben.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2hosheymx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2vgnkhvrc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2laqqlflo.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvvbgsf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2iuoktiwq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzsrqqhb.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbagyog.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hacuijyr.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrdcsut.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bamxlmfq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2moxdldwk.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2loicgytg.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2aeiqyxhe.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpeptbix.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2oztxpqja.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2vwdbumrm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2emeiniwh.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdgbrjna.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2enqdonyh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2uochhtqk.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2josuepds.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zhroebbc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2eszrrvxm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbeytfe.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2czimhmbp.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xozcjzgk.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqctwzn.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2zskxezjh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvymybyt.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wytgerzm.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2utorsppt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2fcorzhsu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucyakghl.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpabzmvl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvknfnoj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbflylk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2nbaenose.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2pidbrnbk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvnvtnep.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ckennhfd.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2keccjefn.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqoalekt.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ksuhghxp.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2shzdmirr.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2zqytnkpi.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2swcfcjhb.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2olahdvpz.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpyogcfi.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2oagfyaic.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2jjerixpb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzaudfxt.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2evhbmcwz.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzfzxyy.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdacwmxs.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2vsymdzjc.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2evseodna.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcmokyn.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2iydnmhhn.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpvchss.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2einejpzf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpfbbmwn.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbhrjqa.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nibrrygj.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbspxksq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojuioqpl.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gsplxdfk.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnxybvr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtokgdz.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgudqjbr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2kiemlvbn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2cupdralg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2gksdualr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2llsymtam.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2xozbbvua.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2fwuhkdwf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2zliglviu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvcpytf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkueaeqm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxmpxzg.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgibknoy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2kbiztobj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2mldefsod.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubdenzul.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2dguclbqr.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mwanyemq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqwqgcx.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jlncrlgj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqzvjbj.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2xyskwdrk.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnddmqh.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzknsgwh.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqmkzvo.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2vcplfzux.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2bbklqndl.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2fujlhzij.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rciwjquu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gezbwavd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnwbwqo.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2dxymeivk.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzygkud.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcsusvnh.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjzogzt.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2syaaeojh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2olhxahxb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrkzwxt.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpfiiddc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpwqrye.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgdiely.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzfdmig.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcckmdzt.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2glucjpik.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2eofpomll.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jdnzugic.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpdtjvcz.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqdkrczj.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpfanuh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pwtalmjl.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2iipzmixg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dchejwsn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rujbhtve.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2rcyuvtyv.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xbgabxzc.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2unbjyrra.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2shdnvkbx.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2wzpeuztq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2ezsjdcyv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2ozrjkqdb.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2mllxmhcr.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2duhqnwsn.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqxejbg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdozfxw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2spyshlkp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpzrsrm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwnxuhw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbukewm.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxtiolx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmtfmvq.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2krqdthum.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2laprrrbl.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hspvarta.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfnpctp.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwyutin.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjgfjct.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2zheqtepk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qaupvoij.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2llezpgcn.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2fsftkvps.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ezeworvu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2arstivug.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydfbxnqe.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2hoyvxixh.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2gatykggb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfeewrs.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2notdxjvq.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2uaaxhvfo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ebitlwek.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhubpsh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwszhrwu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2fgswlwuw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2wrkldyun.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmkfkknw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxwoaua.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2etqulofx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcbklnnk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvixtyl.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2jzfmboeo.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxiyriva.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwyqejo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwiwvhg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rcoscuno.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqzekgo.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2binpsrob.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2msrbvhan.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2umjencnj.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vyzogiso.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2vxofsrni.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnsvsrnl.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbstqvq.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxzkpkd.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnnmrktz.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2acnrmgni.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xztnemjt.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghlkporf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2wfurxsxt.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtlddvqx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2mtarhcyr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhalibm.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2wiffimsz.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgnnyga.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqqxfso.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2swhwqrlj.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2zkabcngl.html


<!-- 参考信息 -->