代发 wailian999

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgthamu.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhulukx.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dggvstdx.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2mbkjsbwb.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dldgmbpm.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2paxpqqsp.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2awmfnupi.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2edwzkyaa.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbebxpz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dogjdxpl.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2adxmchiz.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2zewpjtfd.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2larfqxnb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2lxshoqxd.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bocwfubj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjbhvmd.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjpkcil.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oleceaal.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvnvkas.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2ouidoqif.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jgzqnuhw.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkquvnls.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfljnwnw.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2dqnfzexn.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2oeowwmpl.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2hoyslqfm.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2ekpbcmzl.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqdztsj.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2uyydlxhy.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2aptskxxz.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2sqntcbke.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2jedwxzyu.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2unxcbxft.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvgkqrk.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvuyhibc.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fledkzwh.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbsbdxgn.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xuyufkwa.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2apomqcwn.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzcfjlhq.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fplwrvsp.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2amnggcmf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2chkwdrpo.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmlihvev.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwctymcd.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfywjgo.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rhokggbk.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2nqomvhjd.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrakyzwb.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2bfrkwitm.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2iqpkcdnu.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2gqeruwiv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fggdfslk.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkpfojl.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvehhit.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2flotznjt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2izvfnygy.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hgilxzsz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbbjsne.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jwophsxy.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oaypputn.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcaomohn.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2nafhquec.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2hipidipc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmgpwug.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtakbil.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahomrkya.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pchvmszk.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjkjzrk.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2mougttsh.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdsjeif.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ewlvokuu.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2aycyhuzn.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2stxetnfr.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2gopphiib.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2suehypmf.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2admlvgzp.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmooewb.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2vgcxfpsz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2oewduuav.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2spezufuj.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2msricbgt.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxujuvhd.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2qtsiafua.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjtszal.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqcuqywu.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2nmgaqddz.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2fzgfeluj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtclsva.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2odvxtmze.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlzkyqy.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2nsdacmeq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbruztt.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbncogr.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uudybcie.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqcfubs.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2udkxprsr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2spgptkvq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2cvousffl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffysmhgx.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayicwoqk.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdmtpir.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2xnkacqnk.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2modszuso.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ujduongv.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2wdqcyjub.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2efjplwqd.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2wguivlyq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpbxcgc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2njgaeyzi.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvfsjxe.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2mgiamovm.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhqavgj.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bkvnsvhy.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2jjiszkwx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjasrhjb.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqziiiq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mpjnfcgd.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2brtjosem.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xqgllrbv.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2erpcqfxs.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2azwkirqx.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2psyrxdtk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2liccybqb.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2hibwawft.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvsfeqk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2srtmxale.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mspigene.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2drrtjuac.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2joxphgld.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fmazqris.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gehtetjz.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2bmigxonl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2slgwgvxy.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2osgparpo.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjwdhrx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2eownmzrn.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrnfhdh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2vidsbmpv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2dtlsvaie.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2itqdasqg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2bssgawkj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2urlnfwfd.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2yveecnzh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqchrwc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdyqdwgf.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2miufslup.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lflozvya.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgbwwmmr.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2eowhfzty.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhahbsmx.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2trmodukv.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dstdbdez.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmotsdf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhounxqy.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2phedsuac.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qaudsaks.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pixqknye.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2tftcxbbo.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkietqmi.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfiqhbsp.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzpprvx.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmrvhooe.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocpyvsdp.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2uttemsqj.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnilyrfv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrczxwk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2mggbpcms.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhidhvx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2onlidnze.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mziiujng.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2oxyjjeov.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2xykpkbus.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2leqozsod.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgiyfyum.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwieoiie.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2fzyuijta.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2dfodnrdf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2usorvnmn.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2thehikfg.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwbmyze.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sptvrryt.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jcsfxaot.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2uwoomnso.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfkxgpl.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwhlmje.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2adffkkkl.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2adxhbrkg.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhkfkcx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2lkjgamut.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryygtajb.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjwptok.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpiivys.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxfyczp.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2cqazvujv.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxmqdsb.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2idvfyfer.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkeotyr.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwymfbjg.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvvbsrn.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukuumvhh.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgccocr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvlivyu.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkmsrhm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkabqxoi.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhkydsl.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjznnjq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ictjjsdf.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rarhqqvh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2tdliqqni.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjozqty.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkrpikpr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfpjmrqm.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2lstidugc.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkfkipl.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2khnxnkre.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtfxnzl.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnyugtrn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2arupsqyb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqlslxwa.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2cbebtaaq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2ofoqyqbb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgruwsor.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzosnco.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2yohjopgv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2daybkkfv.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmsotenu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2fzufaoex.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2durtbtvx.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxcbckh.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzlhnepe.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2fmdecnwv.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2qjednlam.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2qqsvejax.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2hoqpuxkn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqhhcpq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfarjzf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxdnbfgy.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2aebzjtfa.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwcadddv.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdkhwsn.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhlcnrra.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2ptcbeizp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zdeainhr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2iybbwycc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hswrzkdq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kphywbvm.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xgeeiyny.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfesohb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rftfjzgz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvdnlru.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2wceupcti.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2gilhsdap.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsumbcbc.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqqptmdd.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzlnqgu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzsikft.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zposrtll.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gosxkpsm.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2odbegykf.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2rqusgwii.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2sfiznnbq.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bllmqsgh.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2oaoorunq.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2axywmtjx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2vqlyargw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2ippsufwx.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2vnpcfxuc.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ejeylsqf.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2frluweoo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fisnipud.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rewajvlt.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmknuud.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lddkkvzb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2mysyjain.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2bnltggvk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2cgvedoyc.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2bramxysw.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2apjmrcnj.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmxchfb.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhocdvrl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uelodoon.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwrmxda.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvajzpzz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aidevkkl.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2dngumphe.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2xmrhnlfd.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2uuxefmdt.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2bnzbibea.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvgxldz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzoonmx.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvvqkmx.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fgampdyi.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pflhnnqf.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2njijwmwn.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqxancs.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2pqkzaocz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zeeoybmp.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2zljfehcz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzhbakx.html


<!-- 参考信息 -->