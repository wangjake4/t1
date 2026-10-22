代发 wailian999

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzeghiiz.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtrtaeyl.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwllonv.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrxdkuh.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqzmxop.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2dowrgpmq.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2opczbiws.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2vyayicuk.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgiabiw.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2eyewegic.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ejctjhkk.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2mrezqdxa.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2yziwersy.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tancsmhp.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvjpjuq.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmdvpelj.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ectpqhpq.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppufdcov.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2vfuwmvik.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2kixrfdpc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wamxqrze.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpxtwqe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xnndvgtg.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cjanfrlq.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2jaivudem.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejlkztid.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2efpzlgll.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2difgljsp.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqxhiapc.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2juftkbsb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzuxcbw.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdsktrpp.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eltgbmkx.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2zfoeexzu.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htvecwut.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdarnvz.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zieyhvji.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2expfegfi.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tchntkyi.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2pswueord.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2momniqoq.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ueumxurn.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2kounrvoj.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgpqqiyx.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcoxmzhq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oexlnjqa.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfldmsld.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2zuluxpxi.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hvmeimly.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2fdkyroqx.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bohbgxgv.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcwmddli.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nswyuzmm.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qounbcvj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2bqautvxo.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2xmyiwmyt.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ycztqflb.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kowccfcr.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwpfprd.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2xgnyjtqt.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvaxrvc.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2yqbfrvll.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2gsurzgxv.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2pvutftyq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2clqhjzbj.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2piqpfqdh.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2dedscigj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2jjptgbep.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvapbjt.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2qmsorvuf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbaygkv.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpynverc.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2peoljdbb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxqezisv.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2prabudju.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2rywzacbo.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgfkdfu.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmcmjvp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdkaumzf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pypjzscg.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekamttdz.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhovbjad.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ahuhzahg.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2cltmlzhx.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbunoyv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2srnubnnx.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2eekdjpul.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2yulngnst.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmavxcc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvdomrp.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2upqymjlm.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2dykjxqkb.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdywksh.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2thdwgpst.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhyyctxk.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlltqnt.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oerfukow.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwusgez.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2brtxdiey.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2gythoshw.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzrvfvu.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnsjuclj.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2icstxisa.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbvigbg.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbarapo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2qriuzceb.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvoogtn.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2vcwsvstu.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2peznlxjv.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2owqdfkxy.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2lvuxygkj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2ssaeuwuk.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhqjrvo.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2xqxnldcs.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2wqwrntnl.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2nezvxvom.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2jltdieyl.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2etxqfqhd.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2icshvmil.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2mvizpwgr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2shjrugdz.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyzsaxvc.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2miotmagl.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqrppuj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2qryqhfeo.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvmlsbj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2xewhamgf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2xulpeyjm.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdaxgko.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2zewgbwrv.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lajgdcvt.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2smkvwwhp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjcjlkt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aealakwd.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2fnyzoydu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmencwbp.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkuuxcyg.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2dhcdrecs.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2yisbmrth.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqjjlcz.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hvclxyjh.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnvajfy.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2siougtlm.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbvirtf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eomlyhmk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcypdztu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpsfhhqy.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2zocldyhc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2gmeuiemn.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tmttsfmf.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcmtemv.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2hldsbjtc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjjasjw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rbsdwsbt.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdjcuuh.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdmjmpf.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnblzfn.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqpsnkai.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2rehhtjau.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2gsuooipb.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjzajvc.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2rwoptnah.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2awfudqwe.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2agmfsznp.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2ieuehdss.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmtpnft.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2habuovwm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2impnqxww.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2bzshiaum.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eniqdwfb.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2grfrdfkf.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2mnysiuya.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2xukqsnuy.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2iotcckrt.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2mngfkxrw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2vgrzrfzx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2sagdbkyo.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2uhshgmdt.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2fcaegbuf.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2lenbgvdx.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2fomqocgd.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2zizivemy.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqshrtto.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yficjkhc.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2edyjmoxy.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2npetjuhe.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrpzrznj.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zihrbqsa.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ywdzcxtp.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2eidvclpr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwaezgbu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2jgdbhfxh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlrunyjl.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nynyztwn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2eboipqbd.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2epmjewwt.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnxinrt.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uinvolvo.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfocfwhd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfbhrqr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2urescqct.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhfvbcx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvgujfmg.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcxrnjs.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuknyyuy.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2imsstslc.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2buwfgwqo.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2mzawcsoh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehdvxcsy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2zccudqlx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2abnygjlj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2pczhvsqq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2bzthlkpj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqjvnjx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2olxosynk.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2drcxzfvt.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bolopwpe.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmloxfqe.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbtlzjb.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ltzqltyr.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2honrdfqc.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qenhpmtg.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwtlkow.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2tiwqlacc.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dznrzzeq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2usyzeqkq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzfbckxe.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2artjqchh.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2txkkxufb.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2upswmbha.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqxmmmd.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzhqkkc.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnppyrbz.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdjycla.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2chngawlv.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbunuddc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2rukmwduj.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2mznxmbtt.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jluxcwpp.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2pknayhbd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdfqbbh.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uspchxbz.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2jcxkvxzx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgwrwwt.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqcbmoiu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2rhrawprz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvlglbqp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymblwtmh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsanfltj.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2lyswhfsg.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpdgsjc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2cuorqxpo.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdtesopc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pteonlrt.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbpfeqx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrlolgae.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2opfudmlb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2cpumlnnv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2kewssgie.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ajbhpsdq.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2eknkhwxf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2xmuzaqgy.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2efuqqsdk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2osrrubzp.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2exwlssjd.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtjuzpkm.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqemgril.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjjpjgg.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2gwlzywto.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2ihnlgmka.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmhgtzb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjeltevh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uozpydma.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wupmpuit.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2jiqlggdc.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2culiklrr.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgvwban.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2urmohxdy.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfmlsxs.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qelnruqm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlimfkd.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lplrkgpv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbctxwdq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2chnmefyu.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2znncjqsr.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2puxlysyd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vdajpurv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2glqiptai.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvalhvq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhlsehz.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2okdlnpvv.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuabaosf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bklksvhb.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlvcdwq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ruyzwfdq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bzzavwzg.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fnazuqan.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwmumtq.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhdyeln.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2lqabdygl.html


<!-- 参考信息 -->