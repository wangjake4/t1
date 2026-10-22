代发 wailian999

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkocfxv.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxzlzhh.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2nqlzyxht.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2senygodp.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2yrirlqly.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ppagcocv.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2gxwcxdlv.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfhwwuv.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2xwclrudw.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2qeiwexiw.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2miwgwbgw.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2wghgjqht.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2osobwsnc.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2twsixnmt.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvknbhf.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2wevrpvnn.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrcfrbh.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2vibqcpff.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2llfbdobp.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsftqbwz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2brghwlhr.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2zrovjkqm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fitkpofi.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gdrzapjk.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2fgueqvyp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lybrrtzf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vudfhswo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlfexmit.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvywbad.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zypaipwi.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwnsnhc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2chtxavte.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fgiibjer.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2flxwtxoy.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlppwfxt.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2onohzysl.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fezytwqy.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2brqckxpb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yxlzoqkf.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2thnlluai.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kibessha.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wktaapod.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxwuovh.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnulufsa.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2blinztgz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhuuzrv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2peeceepz.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2scuglhep.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wagpgxer.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrostku.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ghchbedv.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyqxrlfa.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qnnsosdv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dmuvxyry.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhqdues.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2pssklytb.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yszwkkya.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcfkfoy.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2effwcvzs.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2xxysqdad.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2cckdbkvd.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgoiuol.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2fzducxvi.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxyrrte.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2ovklgtrl.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbtqono.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2luipwnhq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2clefkkwk.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtejnzz.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjqszma.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqpcetct.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2hohqrzqx.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2eprzmrlg.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrofzypc.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2rovoilqb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2nswkmuvh.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2klwjuhrd.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgfvmwr.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgsddml.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpjzntdi.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtlcmla.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvypomb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gfeqtkly.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2aebsrxxy.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxjrmsy.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2gvnpxnum.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ajzdkmfg.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2easlbugx.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njxatoqe.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwkumis.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rscmvkbn.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2qrwszvpj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2aalmceky.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjjfstq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqmereg.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2oceifjyl.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbuwaksp.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2korymwof.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2ogcrlnlq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwpftie.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2abobhryz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrnadzr.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qncjakbz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdckanvf.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxfqxud.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2vinvwqbp.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzkstlz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2baufmkcf.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2vhobhcsk.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2veeqycpw.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2fcollqjs.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhpicor.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2fvuyavug.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ouznvnqw.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2edocmabs.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksofqbxl.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2tulfojcs.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2ywggyrdx.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvwhtnnj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmnjfno.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwnqkvy.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezojjbqs.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfgnjvd.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2hutjcwqo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2usvdurdm.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ntocxwdv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2vkspdocu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2eopyitvz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjfjcjy.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhxdkrq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2monbeire.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2dembedpc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqooumv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjizevkb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpvuymh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2unvulsyp.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vebjozco.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhbcnvq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrarxqp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2hngaypyq.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrrrtlz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2lnuuodnv.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2wyraxbem.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2fmeernim.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjpykzkk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgorvwcl.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwqpurw.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2mhacmrkp.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2oymlaeki.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cctfjvcn.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2xdktgiks.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqetvsz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zlktskje.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdreldm.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzjikyd.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2eoaucsgh.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2vlmdmavd.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtohbrt.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtgxbvi.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2ajarmowa.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmwlqir.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqymqrt.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2tucdtaqm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlnflyl.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdxzmyp.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tocdodoq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2juwbxsrf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bhpdyyeo.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmebawp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2whicezoq.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2guuzweio.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2fppmjmbr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxxtmyz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2akcurspv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2gadrtibx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2fsnfttnz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvrngjo.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqaoyqe.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2lolxjwgg.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxfnlmw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2aczuhmjd.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2czyhdgxf.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwibazoe.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zktegbme.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zyocxqiw.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkijaghy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2tscmvgtl.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fobpanqs.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2axipajur.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrdtind.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wafjrygd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2ydxyvicx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwdtuyb.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fryjjesy.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipeowper.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2iheobqos.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rowttblk.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mvomrseq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpkamfqw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsohpoxu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2dcoxocgi.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivekkbrd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2katrnudf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2msvznmjp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktcxkpxq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ssuhlljz.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xydgikai.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2gndgazjl.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2cialuhmd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2eaailxol.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgvlgva.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzuztpqh.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2yukieruf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ubpfcauk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejegnfmw.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2eowclbmx.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2adgzmlgy.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qotqriyf.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gghdrsyq.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2itrawvzo.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnipwai.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlejdodu.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxelajv.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgvbshqc.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ephltebx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2dakgpado.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2phsjydfu.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfghesws.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2woiygkqc.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rybeuvbq.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2lkyrtcje.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxgbcyg.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2chispgod.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rmldzgus.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzvrplgn.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgnxkpyc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2invpkglm.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdjeysq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pxujnacl.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2eveevahs.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypnkigay.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2afedrwkg.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2yufvcoyn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2sycrpwma.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bulfemjr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2fcreehwb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2rakfjwzl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwajdysb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqgddgyh.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2oxiwmxff.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2gghtubfr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2qzywthot.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxdhhxl.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcktfcrs.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrukftx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2rchwpcxv.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2iifpvooo.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrwudaz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfoevuza.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2gtltntdj.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2riwqqfmq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2kxxwktlp.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpaqfgp.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2omkedybq.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvkjyiy.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcaxlajx.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqisutmn.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2galxfwca.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmkzhfd.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvvitsh.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfkmugb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vobevnnl.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2obveuizx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2aampjlgr.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2eajwwowx.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2aualzqdu.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxcbzmqm.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqfpsuq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2hmeflzte.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2oregrgfb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbdvmovs.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvzfbgs.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjwhhgm.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfvjfel.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2qratvwil.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wleynbdq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxfebrv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxfvorx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2acmaaerc.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2amakkzhm.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgusjcwm.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrkocas.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2aflfgufc.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ifyfuxwb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhuvgdam.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uxaphnci.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2raehznok.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjzlfaq.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tpihpglx.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqekqpa.html


<!-- 参考信息 -->