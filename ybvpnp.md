代发 wailian999

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ljaogsar.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2ljircjlg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpegffrz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2epvvumdh.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hktyrdef.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2zmxicpya.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rcfnqrwh.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2sxutnrzx.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bonzajtn.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwqvgxl.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwffjzv.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhslyarr.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhdevvww.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpheytsg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjzizgc.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzdezuj.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nqiywtzc.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2wiftfncg.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2citaqelf.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmsxorxc.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bihsevcx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jtscsjsg.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2xvaxxwam.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwmahhe.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tlnosqfs.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2anxjzihy.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2awkcqtkw.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwlpxyn.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2zskuakgf.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ixrztwau.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2tojrfute.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2asgygfvm.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2hacdsgpp.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2vuevtkms.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmxjlwu.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2auzostvo.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2kqppbtlr.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2fujdolun.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibdlvjvb.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2msrverer.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2kektmlnb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjljjqp.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybxmrpgp.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2xssporcz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmstlivh.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2kynwwvyj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2gztyklrt.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2klhbzlcp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcaonbrh.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhrjlnh.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkaitup.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvdlaab.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvpzzzn.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2uaedfild.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2vmugpfiw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2tpcpupfn.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aucbdbti.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wplbixzk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yksmmuzg.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2lwnjverq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwvssup.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwdmmlz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqotzftd.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ekuwgajq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2catavuzv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwinodlq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2oquhdxor.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxlpfaz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjitxdap.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsaawomm.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jewkbhzc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwdzsgu.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2cunpcffr.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2jnlhqjhx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2qjnepcxn.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmascjr.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2czlwjrgh.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2bncmrrba.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2jjckxfmb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2ztxralqb.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2kakueifu.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkpzfuu.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvxoshp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2koqfwddx.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmvaewz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxhbkdw.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2viavpujx.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2vvsxatsl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2axdgegvn.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhknlgtk.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2rtvdelsq.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2atkmnkmu.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2npckmxzi.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2cidtvnwk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2etombwih.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2ictrxjdx.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjwvvpo.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxnoynd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pwzjroms.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqcldve.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzrmfos.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxlvrmd.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2ndpglval.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dluwbpjs.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddknczjy.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvjmzvd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2bkvfkaky.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgmedpc.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ndwbfdgz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2mapxzjim.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2psvtiflx.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfsumgy.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbwuqwb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jujpupms.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmsgsizn.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2fyziahua.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxjnhur.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gczxntdv.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2jslohzci.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfyicylk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hehbfxle.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lavladvx.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2fhuaohhm.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2nydthfel.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwfuhfp.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2happnkew.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2patoiysu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwwpzud.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2caxvqayp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2qvplkwzy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjecsmu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbznzlm.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2dhacglge.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fvztsdsr.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbdvwev.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2koybbueg.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2ixozwplq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxhrnjd.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hyktjbvy.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2dmuhefub.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2qkuxbahy.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2qlrfrbcb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2confznxc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2mtciyarg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2bppqhbcu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2egqdxtuz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2flsnnqar.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2wghnaaru.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2gisiesyi.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvgmfyi.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ensoslig.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwkfhrk.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdlqmfop.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqevykps.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2lllguwmm.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhbakhq.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2whrtpokq.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqvnpdz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mktkkczt.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2dtjwfdry.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmntcasq.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2exrcbsyi.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybgobgjh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2bukllqab.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uylgkvcu.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxkrtbx.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqrwhwif.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvbetcv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2aifaizta.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ceefkhde.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bipgjcwa.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2eobjpyga.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbaptek.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zclwtvwy.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqmzpow.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2tsaizjxy.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjnzhtfn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqpaqfi.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gibncrtw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2xoshoyha.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ziddrzlb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhcsgao.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2fiftrcag.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlaepdr.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktnhvpqm.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2atbsykuh.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ghthgawk.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbsgmcq.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2oqiqgkyv.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kodsumlo.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2qllnontm.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2mimrbqvu.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2crraqaop.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2imqhmbgs.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfoffgnc.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmviyaem.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nogfuibi.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2surgkpvx.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmguoqv.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2mzzasigl.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnifsobq.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2uzpcmczn.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwronvp.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlnlrnh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmpufqy.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2gyljtcng.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kjpvsnms.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqysgyon.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkaegde.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lmyckiud.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2parziyzs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2jyyibzci.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ednmkmkq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkpdhhh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxzjdhp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrimtnz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwxtwab.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmtpcdn.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2puvosegf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2cirwuqzd.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzpykwuf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtyblqjr.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydfmssii.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2rubucwhq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2yufltrzd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhhoclt.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwrxljwq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2uecbouvt.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2obpukjjc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2mvddexoq.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2njqokcrk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2bbkrzuhv.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2teepacxq.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2zuyjubxc.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xopvnhxh.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2iegbmune.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2pasasaru.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqtqqth.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2kqzqbwya.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mexzaryu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2scsewxgi.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2unsteezr.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2lwipbusf.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrcpsqsr.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iawtjfyf.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldyjfleq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbeowtn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2drgklmbl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwatvtsa.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qykvojip.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2raalrywz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjslnhh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2eephepnj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbvfzis.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kwsbvljw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2puffzaic.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2yqowlyfd.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2celzckll.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrubcmw.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzzktnz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjxylml.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wvwtasfa.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuevufds.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjrrcnk.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2lscpehbz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2yylhwluh.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwqzzxf.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2wndoroch.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2onhaazok.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2ycuobnux.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2rlvrpnrp.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqwmxxk.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bzcllmhv.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2dbojiwnt.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvczhtku.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2shqnvgou.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vliqkpvx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycplsjxq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhlmgqx.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2fcoxekzo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ayukdrgq.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2iimzvxzv.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbgahbt.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpefkna.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpuxjhcz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbrsfjzn.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2juecujay.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtenmijz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nypcxmsh.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2zanmndis.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhasmmy.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2suwzndjp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2xbyermjp.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2irlbtmve.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmiqlmz.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2obkvnqnu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gknvowda.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkxxiho.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2vnsqewdq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tcyegzvl.html


<!-- 参考信息 -->