代发 wailian999

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgteetlu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrhbftq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwapikjp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgqbshik.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iocvhpya.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2vspaptcy.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zhikfbgu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldoliqyy.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mduxqcay.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wntmuxdd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ylevftzs.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2afjfhqha.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzvpyrt.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwlwcqvn.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrvxirs.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2hjomogvf.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvhndah.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2gtatbcgn.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2jwyhbzwd.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2igazjmjr.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2dewmeejx.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ghkpfcfl.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2nanyillk.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2kkgvezbj.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2udbnzxqz.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhiqhcg.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2uehkwkly.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgoudgmk.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmivcryu.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbsmbmdr.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2fptpglzr.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmnoxypq.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnyqhemu.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2pwljsadp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlilniyh.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhnwicr.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2olnezdwf.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcudoyju.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mxqdyedx.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2prpabrtv.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2stlhmvyj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2cywofrvg.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2gxcuvcia.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2vhahzmim.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtjwyuzt.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghgtpshb.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yidtaihp.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbesbjk.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtkichta.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvrhmbz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwkylpwi.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yoybzahj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvpsszxx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzeeydtc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2cnewluql.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2ljeazrpx.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2siueboci.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tspmitvy.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjgvyvu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rochexci.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ogqnyqlq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2kknolnxl.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2edbjaoge.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ckarvxby.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2stosbwye.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2twxcngoj.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2npzsdlzh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxumrbk.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkmdizj.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmcpovz.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2cyykbenh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmkdpxu.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqtomod.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2gspwtpcs.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2xegbdjmq.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2mihyozfx.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2ngfesike.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2obrrhser.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2ttabclbh.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2nsboousg.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzjdxzw.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqgurxs.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2hubgcckq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2rifhbyjl.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2lzutmweu.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqcioby.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fwpkcfvv.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqobodz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2viduweum.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkrvmrbj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvlprfc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2onpkgbvq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlazbgjq.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjhwgve.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2qlcxvshq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2iaoocgmr.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hblrqtmf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2ljrrjsdw.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2nezuzani.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2bnpseodk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xikpjdwi.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbyadys.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfupactg.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2fnulneai.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjhwenf.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhxkatb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2nagyxmgq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtluxllv.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2snpcdjqp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xvywmtwu.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ohzyrpaq.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2dmebibrm.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2hbupylul.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzbrszng.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2wodrretw.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdgkrtl.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2basnltfr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2zlthoowu.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqdvadr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbexhsq.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2amuufpym.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2khcvajzm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrxtjgm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ooudmbbh.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2bahdbjuo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2usrrrekh.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vqnemxst.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2kyuksisw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2bihiwwvp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzcuyhe.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzhrang.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2epgsrrlt.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2lvlpecxj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2kcrdgdcp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2ggezccmv.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2vprfdoqw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqdydlk.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxvvcxb.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvpimje.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2czdxrded.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmvxjds.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jytmtfeu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2uohtjacw.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqbnlyo.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsjypuq.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntavhlbc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfuqgbov.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkccvva.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxuedsae.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmbvxgo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtnqaic.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jowkxlqk.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2eexmfcna.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbvvubf.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxeeooi.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdjceet.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmiwlgr.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vljmogzp.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvnenyq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbonenk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gclacdds.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgtjkzlg.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxxjawy.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2vguriddm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbudskg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2hemblvls.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2glyjdmqi.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2reelmayw.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwfqgar.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2txzhpcaf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2rssndyep.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbazmtm.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2htjxqnmg.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fetxcngy.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjcsmpk.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zbonvibh.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrnqacb.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjliwgne.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwipttn.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdgassm.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlhpuec.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqarloh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmozasix.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrpzfxl.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqpwjnd.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxpigpzu.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2ciumfhkr.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2abdhlmvy.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcflioyq.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nutgutqr.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qafkuywj.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2emnoafep.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2femaehik.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2haprpjnk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjqcgyf.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2gijyvsjf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhuoxpcy.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzfpsyr.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2qgazudbd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2gofbxdjj.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2altezyfd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwpymqk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2gztyyfrh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2lllnxkzm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqehxxa.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2setksjtt.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2anktnksm.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2ortwyiop.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlvsktm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2akyjkfgg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwtdptu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2aomaehpg.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2uawyerbe.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2jvagmrhc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxnzicf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmhsurz.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rzolevxm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2utnjavda.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wciplhhm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2geizgovw.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbiqwoi.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2kirvnvhg.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgivlqce.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2gygvhgii.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2skobwgsq.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2pecentav.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2blscmbgk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2drwmxzzp.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2okyrqmfu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrrddlp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2cysszpqp.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwqgoha.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iarorhzw.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzimrzxd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2lauydgko.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ixgpwekr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvhtdjt.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujoqvxyw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vddhfxvj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxemxml.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2ztnoixqp.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gymguhxw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dmencrtq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2dqxgxegd.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2eoyouqop.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2amfuvnbe.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2turyixzu.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbcqgscg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lseqgzvv.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdgwfvf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqbxfse.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxrpfns.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvfdmpn.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2pewfwmxv.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xyakebbc.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2eqpocnzg.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxajvcs.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzrnhla.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqrzjkn.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2vnwptjss.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2frilaytr.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2kperdqat.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtbwlqh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sirfscsv.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmbjznw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdozwnbz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2jfnezenb.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2mgdsejwo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzjdjfc.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2vuntjzfm.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2oiibyqef.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dehfvslt.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rloahwxe.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxhdbkzi.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2udijxjbv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2alhlwtpb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpeuvugq.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhaautk.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2loajmjiq.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hgrmsyii.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2mbffapzd.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsovqff.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2fybdmocf.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2plnybczv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2eazypsaf.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jwykdqok.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2uyoikvyw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ptpjdman.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2awxleogn.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcsjjvln.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2measdxlx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrqdkrt.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2joyzkuxi.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2mfferzki.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2txztmerc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwrhmwdt.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2eodsjdyx.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjkthce.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdeedntk.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vyexodit.html


<!-- 参考信息 -->