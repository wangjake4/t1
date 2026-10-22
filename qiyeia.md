代发 wailian999

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2htzmzeic.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2uerdrhqq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vocgxppw.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgizsduc.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlsfard.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2bovuyvnq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmutjbl.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwmrwxz.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wiavqwon.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2deucihsv.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2osayqvci.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfzizqa.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpogpwpq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2piernqev.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmagevrx.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpiwofic.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rarcekdh.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2bootvlic.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhiltjh.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtqedwg.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lplkfksk.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dwblozdm.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2etrmzknr.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2nwakkmds.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhmcoix.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvzeeaej.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzplbahr.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2eegqxpqx.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2wngokdmf.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2thwemwqy.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2pnomefos.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgxoqnd.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2rdbandvp.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2slsuviml.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2cgvmiwbj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwunihz.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2rnewoypb.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2rrrhefuk.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtrrhdha.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqghgit.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqymppqd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksiklpet.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2lloapool.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2jihjwgzu.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wovdqtum.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2bwelorzy.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpahdhrz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhmvbjo.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmgfghb.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2jiuwtnks.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ewgtuzbu.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2pblvunck.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipltwjfi.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2glqucvih.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqcxtbe.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2gtpxofge.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrlgtyjy.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2krzpbcaw.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2voknpjwc.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2zamjgxzq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ounlnzlg.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yppcgprp.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyeuxnzw.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uxuxvtqk.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnhsjoe.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnvyavk.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2ergzlcyn.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2mvaelcdy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qclrsxsn.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2iszxpikz.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2akhehjdk.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqkbwzdm.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2kcixjwer.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2rwftonof.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2aavrmwjy.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2nnkvrqpz.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2cqedzlnw.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2mwkhthvn.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2zbuxtsoi.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2txctxamt.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2fysbmbnw.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2oljyfheq.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2rwyzxqbm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmhulam.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2wvihwawb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2dffmzelp.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2evvpkvup.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2plsfvics.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2phnxifeg.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2nyryyyzm.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2qrndlktu.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2lauhwcbq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgfydah.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2dbcsqlsh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2jpuquwxs.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2fupkvtyv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2bldobsyx.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2eiouflmc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oovopujd.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrquoax.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2whqsragg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2plutiwxo.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvppioh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjhdfry.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzxcyzj.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvfmpkp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2rvsmdqte.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmpalbku.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vczxlgnw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqqcfht.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjhonnk.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2isukyscy.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxytuyx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zitqowqp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxscmdu.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2taxpmhpm.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2phlkqfxj.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbqhjtx.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2rmklbqsr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdizzjkf.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qezgfutt.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2usgaquxi.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2yzsdplwv.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2aymaofap.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2keligygc.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2frjjxaex.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2ithsvvcw.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2swfwdcat.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2rxyfdkgf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfclrnk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhlyqxq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqbumlu.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2vitpuums.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2idhuiaxm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fofegfqg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtiwpfm.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2yfalijon.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbleuue.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2uergwzle.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2snyvgmwh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2udhgfxyu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2myefxufh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2pbpjqkid.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2drdqnwcv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2fjiqguzr.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2dzkynwgk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2apumtdsa.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2jyznjbup.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2ernuexhl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2kccytmfw.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwqotim.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsoozxfq.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwztbvfb.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2iofnsgxt.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxlqxvjh.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2iuwqapxw.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wptiywmg.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2znqypvsf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywnkbeai.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2slvvaxnb.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2izqvnkef.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zuskuhhn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzpihcry.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayinloey.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnujowm.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wqqeipvq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnqeijs.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwyycwdv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2meqytkso.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqxsrxbw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgrkpkw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2larmnmzb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbbmzke.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqmufgc.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2irmfkpzv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2iforspds.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezzbgahu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohljgrad.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkghqtir.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbgexpv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2pivvbjwl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2vcuphvxj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2yghrywdp.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dgurcopz.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdevxwy.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tliyygpi.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2epetwhww.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ozxlukgf.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkhjrat.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjgplpeb.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdjriev.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2yuuifckf.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ejibgzji.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2typpycuf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyerzjqe.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkcbdqu.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqflaecj.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqbjedl.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjmpvfc.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2siapvfbu.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhlvejeo.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjlhcbt.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfyxmao.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjvbgjc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwrwufy.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwbbdvz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2prrvwtip.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2juarhcae.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwvsula.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yugndbiy.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2noflhvtz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnqmnfd.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfziwrdx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjydtli.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2irkynjka.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxrcosut.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rupmdzuk.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhghqgm.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcplkvv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkosugg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnifkccm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2etdncnhw.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2xiavntjs.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2yarrckbm.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhonjzf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2gsxngrvq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpuyovyr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2bhprveon.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2sausqpay.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2yuhrjhcb.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttusmqyo.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2arlgtljb.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2riahjvlv.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2xekyihhu.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfytmymz.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfsvwqm.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2uximhfcv.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2evpwzwtx.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2dwggptix.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjbakoy.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjlkpsoo.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hprenxew.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2plskxpkd.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mifvrgme.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2reippacr.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsinmxo.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjvxsdn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2oqshtrfq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjabrvtw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtcwmzx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzuokbb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlvtsdd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2agohhkqu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwfnqhi.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lffrxgxv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2sgaxvomt.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2oudezebh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2limlsile.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2larcrgbk.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjiloslp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gzysarfn.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lkojuowi.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2otjqdrkr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bufnkrwp.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxehfkg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dracpmwy.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2grrakhsb.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2txuulgqx.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxwlrlw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxfgtoc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2sclbcsrm.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtelzqp.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqcdaac.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2csqvsyxa.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zktwonli.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohbxixeq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2onxkbkzp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfnujnph.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2qmsjdpcu.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2mmkgqvwe.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2kznydljn.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2durwlhdg.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2gozdycvq.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2unbubekx.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2idelifun.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxaywcol.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycchmsbo.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2utnwmrnk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dilgirfq.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2iirlrzui.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2yczcnlvj.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hlzxulqx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvytucz.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwxtuux.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2gecmdqax.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2qdrjxfas.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcaigbv.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dthabveu.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2wrigdlbp.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwvxxtt.html


<!-- 参考信息 -->