代发 wailian999

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2ockzrmwd.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnawcte.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfnkwghp.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsoojwjg.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjpwhqof.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2czcgzsez.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2vvzfaupv.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvgmrszr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjgnbrp.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2gkvktezm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sibcdyqw.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aaittsyh.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2kbequojw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnzwarjj.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2juaqpssf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iitjkbev.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjhluhs.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfoysvp.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rftuvgpa.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sggovtbg.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wnruzeup.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjggwkf.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mochjhfa.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hoanqhjt.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzhqsnq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ochwxngy.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yjihlogj.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwganrt.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzddwro.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2esnlhjan.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2kalqwpzq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfccbwmf.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxninfcf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zridpmgq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmlkhade.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2muxfypxn.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwedppb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2yycyridy.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2swwlhmbb.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zukxphiq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qylqictv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkazriw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2skxtytua.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2pqcdefmo.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vucplvry.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmddfhql.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmympte.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2rgbwqbam.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjayatm.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqnckgf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdcgrag.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2oewtruwf.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2vaakjsrq.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2vpclcqoy.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2mcydpstn.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2ulacqfrt.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvvkqhx.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2kokvmwlf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsbpvggw.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcuocdic.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2gllbagqq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2pspzqewj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjftrsuf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdfxjdrp.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhknbtw.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2bjyrafev.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2nypdxjsk.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrpdgvd.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2iosypunu.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2udeidvgu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ysuobsqg.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrvvoxe.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajbvodxo.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2aiehfpnn.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2bejhojgo.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmytvdu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrxemku.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfsdfjzr.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfuwvssz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjmnubt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wazuzacv.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2irzxonlz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uanhrmwr.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pnuxvsbh.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcunhxna.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jivkgzjs.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxrealh.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2vvoclkrn.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtyltws.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpczgyab.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oydoljuk.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fupxddab.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2vdpqfrbg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2maumjgnp.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2rppinblq.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2qneymbcr.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2depjuxxs.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2dasxyubl.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrgpgnh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmxzzjk.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2elequjqm.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2iifbkxmo.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2djxtezii.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzfqxymc.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2wsnzymdi.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2ushkckgn.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2odplamxi.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2syztaxni.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2iofvrpyv.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2tictjnqj.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2pbuntotw.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2syhpusuj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2isaeqzvu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2dueacydn.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxjkqhr.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdquymj.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2kujughzh.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmhryhc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zmstrueb.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvshgdl.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2frglvcjw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iglotped.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2iemkkzho.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhzsoxs.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhfqtjf.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2sdhsruqz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2xapjirtq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2tngsytlw.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqnwfvb.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2pyuhahzk.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrdgfea.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2nghoyjvn.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oauwrljl.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmfdsdse.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2glnpxxaj.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2hstxplsg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2juppkitr.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2leqzbhyp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2rskexvst.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjoptmqe.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhfgipm.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iroaniug.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzsznrf.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmjqgcn.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2hnafqqlm.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvxasqj.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcztemo.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2owqsdfxn.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2mwrhvlqa.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ekpqpupg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qobqdgcn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqtypyu.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdcggpv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtjkwvt.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2khmeckba.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfzdjmd.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrxrjao.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hdehlziu.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2eswuytcd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2waejrdnb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2tigeeloe.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2bkvcwoia.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2dlanpgez.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2njvlcjah.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2rplqqras.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2bmzavzkp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2ddsrjwts.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbfemhd.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2agieahmc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2xymsdkzt.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2umcyqurq.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2psovofyd.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjopjhni.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbuqhtac.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfyptrh.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdkzxhpx.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2roxjdybs.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjyiips.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylufxocj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2zxphdeyl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxfpyce.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyycldji.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2bctvugfy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdonmkkz.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lekpulyq.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ltertbox.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xothpfvq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2buvtzowk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfnhlrn.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2yeynvnmj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2staffgzk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpqhnrc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijirjgpd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajozqarp.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvgfmng.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfjfecb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmscdaov.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjiorpsx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2yijzsfhr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2neymyrwa.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkipzfv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmalyms.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypossqql.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcdrjhz.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjmmiaa.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkjgpuu.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnaflqi.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdezxwc.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2qarpllos.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmtqbpp.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2jmaturpm.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyohhard.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wzodpfyh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2udqvqdgx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nexldqzk.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxjoxaf.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwjntyd.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyipqksr.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2minvcjva.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2pitanjls.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fskxkahr.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2srohnvtu.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwstjsz.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwusllli.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijovntrp.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhggulo.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2chlpbsrh.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2abaoaqzp.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2npzjeyva.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2alykjagr.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqpkjwt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2epmwvicl.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhrlfqek.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2ipymhwnj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2vweliivw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvdxlwei.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvduzra.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2stqcstvk.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2nykdffvh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2cdpqwffz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkuvryg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tabwjoxs.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcxppsl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2sclcjvwt.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2dizkbsqb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2wksrycxg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrxyrse.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ykerpnev.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbxwrgc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgwqskh.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqggdysl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2affpxmzi.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkrzfvo.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqobhfoc.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqliwgq.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvygtgx.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfnxasw.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2upftuerm.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhxivuq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jltfteij.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2guwzzqxb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxswwtqf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2pnpljidj.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtwutyu.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihshycgf.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2elghwadr.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpeoagd.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2tvotuxfz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2onrpmdtz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtcuotwl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2oizqglbh.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2baabojea.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2paxjkxmn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hupbzmnt.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnqsies.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2vpckaxkr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzfckgk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxnyguq.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnywjtkx.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhbhxza.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pzcmunax.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2birxbcqx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxptyjkj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2iggiiown.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2bservxit.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hnfyoboe.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tuibnifz.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2wocqookk.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2prxdtlis.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2wmeiqtsq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2xafydzck.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgfltlx.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fmihkyse.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2aisbslsf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlwvmta.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2apneqtjk.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lulcejny.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2agrhufdc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2ywczxuln.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2piabqeba.html


<!-- 参考信息 -->