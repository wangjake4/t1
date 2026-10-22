代发 wailian999

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbtiexe.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnmuson.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2phgxqgbr.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2pydekpuv.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2yedamvrc.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2uegbxjom.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmsvgjjg.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2erozvvem.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzhqiylp.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmihzljb.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2esbkbxic.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ioevbide.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjaiwgy.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2copmeksa.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwpzziim.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2txzipvxu.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2evfehgni.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxuwqtwr.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvmgqqn.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2tuuraoxw.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhtdhyzg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2somjdrpd.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2szyeqcoi.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2qufvwaeh.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuuzgtpf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aafzlwno.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtjquyx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2knwpjfwt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2culkfddw.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fdzydudo.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbakcygj.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2abtuctis.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqtvfmw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ausftclx.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2efrlxfnq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2mhrpljhx.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtoroygr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmmfgro.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2czwsuoae.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcxmvdl.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2kicziuxm.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2ptktuvsr.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2gakputex.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2hrswnhcm.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ubdkdgnl.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwqkmld.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2jycgslow.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2wasogrij.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2rxistxnh.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2oygejgwr.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2whnmqjjs.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqqivqh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbquwnb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2wsyrgpbh.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntsqgwot.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2mipoulzu.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2piqebwbv.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwslvvc.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2jflqtnpo.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2riwbxety.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjwlctu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ticsftzc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvfmcvx.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2ecazhurr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2ltabxodn.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpziljx.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqwfsuw.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2xomwtzgi.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkwoglt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vymearas.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2juoejiws.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqyhgjdk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2absyjwup.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2hivexmsl.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2yvytiolf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2uewfcrsf.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgmqasr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2uwuhysiz.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwhqcpv.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2faeipkgf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jedfvqll.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bchjjarq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdumnnt.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ykekuknw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2guovzbqh.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2smwaftyj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2efilnmid.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2whpksahi.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtdsrcs.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2msxoakhq.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2zoagjjam.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2zctjnxyn.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2cqnyssix.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2geelcmtq.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2xtpbfheg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpgqfyh.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2glgghscq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2kblixtsa.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ljohvcsj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2luodfjzn.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2fliyzrfq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvittsd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2elkypjzp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fejtkwhu.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2portchwe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqgnago.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mfgvgxsc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2vbiliyei.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2rlddawrk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2hhepmfjg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2flstkbbg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2peiwtour.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2wzmobgke.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2jvsfbgva.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2qblpsbsz.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2huoiifbr.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2wymgqxas.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyszwjvl.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yttoanim.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbxxxsz.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmmwptul.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbzxbds.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2glyreeby.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwpptuk.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2simnirtb.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2akurdkfe.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rixsjyzh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2vfgumxii.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2eiikhjwk.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkjfagl.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqaoecy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnyqmnk.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdeataf.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rgchqegc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkjgqjen.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcassigz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2dtrnlxeh.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2aohlmucj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lenxwlmy.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwybgel.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjvtcfz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2txvfawxo.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2shhoqkac.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2kybfbtkp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxnhbrpj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdvimbtk.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgcetqka.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2eidnotzp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbxqgta.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2wdjygvgu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqymdeq.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2aejlpypd.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdawmlo.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cymyudfm.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbwsbwg.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ciuyikki.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2nowvqunz.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmakhzuc.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2fvchxcvw.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctisydry.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxpwltb.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2dvexproh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgtsnol.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqiykfjx.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsoliyie.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2azmylpve.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzdlmuk.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2wugqxlvs.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgzrogp.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fvkmfuoy.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfiljlf.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmesuljp.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2iscbpsnn.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2kjcbpeot.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2madmzwpe.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2glnoddpe.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2virpwuxg.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2haxlqllz.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2obhluoyn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ewlcyhok.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvydxnz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2goqpjkca.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwjnjwwa.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwfxzqp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhkujtz.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2wltnsoxd.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjrknyl.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2enlytglr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2paeapuwx.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qctuvrob.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymtgjjnw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwnkvgpg.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbsblrj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2rxnwsrcg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2yapcbfst.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2mvfjwgxr.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2sixuzldx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2arxsnepa.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxzxpod.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2dvamxejm.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2xubivorb.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2anqsblax.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2guttsxae.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2cnehbugl.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxznfoy.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2gagimbix.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2flzfxole.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2drxosxio.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pagzciih.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kycllwae.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2iybeqina.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkloqgys.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kymgkerj.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkfjbpcn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2tlwepwkb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2spshitug.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pikcnrze.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssjeyemb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2poifqcyn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ckuslyqk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdumbaq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjrliwk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvcjnnb.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2zcxmrsjp.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2irqfhzzl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kusuyqmp.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdaysjay.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkwvupst.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2legvtoah.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hizhanmu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2aquhseus.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2obownxum.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fjeuwgaj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqpbpbx.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kduomqfm.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2jxmriizp.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkrxvfx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2fiehnkds.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2zepvezzc.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2prriesju.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2akwxafwe.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2lnxabfug.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrzbtrj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2brfmitbu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlruzazx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhahtvge.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjstrik.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2kugmfhpe.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2goolhbvr.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2gaastzxu.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbdcqob.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzirkae.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvhvtkt.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qufwloyu.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggpwiohl.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqeupar.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjeepwsl.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2eshkcjmk.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2elgsbgcn.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfgmygn.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzdniva.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqsmjyia.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2shmdzzct.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2leobyiie.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2idegaoww.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2evhkdwtm.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvbgqki.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2osihoegl.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhwfzkx.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdinagro.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2oxvhuwew.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2yqpskuul.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvkjbzpn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2azzyzlrn.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2jnybqipx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2affatzey.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdkhrcz.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2qhobkogu.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxadqwww.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wymvunyt.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2mpqsxcik.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwpmdyb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2voawbzgz.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2spgbyvig.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2ilsiyage.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2kexlrveo.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tcwwesav.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2sqavtnll.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwslgffn.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqpjfsh.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxybiwke.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xeatdyxp.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2demlfqlx.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkzvvoov.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbyyracb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2rtdkpsid.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtmwwuw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgpllou.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuyyqfns.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdcteyi.html


<!-- 参考信息 -->