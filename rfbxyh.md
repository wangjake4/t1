代发 wailian999

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2idafzuef.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2usnejacz.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2jguntqzx.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ynkpqhus.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2kolwksuf.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvvvmmf.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytgjqtpu.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwthedvl.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2teeuyxyw.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2zruliojt.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2icolcnjn.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxnmkjfn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqiuiyn.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2pewxaeht.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xaxyathx.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzqcdvb.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2tiojiiia.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmrglhz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhaqtbj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2amddrrjl.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjfpltq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcadcpw.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sxehzafa.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhnzadr.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2haneypzy.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqmevzl.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqbewdz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bslisove.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kumoyeco.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqdmmrc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uyutncfw.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2xtoapaap.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxycbcr.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vsyadapn.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2szzxxknw.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrlregak.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikkbzycf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjhftlvb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtcqwzup.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2pooiedve.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nevpqzth.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdvmrnv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gzcsmdtj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzxvrzv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pohkpgjv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tdgdelmu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2tqnmpadd.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2ebnnkfbu.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pfylxwmx.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2evgavaxu.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvrqmou.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2lwyguelm.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2vnejhyby.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2narkvoik.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhegyuj.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2uovvnlbk.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrlhjlc.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2jakfledo.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2xhwuddvq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2uucykgck.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2jzsayarp.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2iuoffotk.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhwzmus.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2jygzfmck.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhpjapho.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2sewnjcnc.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2batmzmgy.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebyeegdg.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvzpthd.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2odxaamwc.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvkfucl.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvpkxoz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtrblgzo.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbixvxya.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrwbeke.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2grnfebfp.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofkzyjdx.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2zzitnzxw.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxnpihu.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2lawshfff.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhktiawf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dptbzwvt.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksoqtzmi.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtfckdt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zchgdfog.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wwpyetsd.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2btsxzoqd.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2esvtmbhe.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwviyca.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjafllym.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwhexum.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqfubhs.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbvxkls.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgrrgter.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnieroa.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmaqpbiv.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkeeawi.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2wukmysxl.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2wniusrta.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2urpqhlqx.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2vcqxywha.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2owykdwka.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzkvdqa.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2dztltgjr.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjcnsan.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2gzuyqozd.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmnccik.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnlabnqh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwyzihz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2mmkvdswl.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxeaobxw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2bwgixcix.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2wsyjdaai.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjzolba.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2bbyvrsrh.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfzumtp.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2jnugetmo.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2fhbgoanm.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxnsadi.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2dtubuxit.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvthpxl.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2trhmdxwq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lebalemj.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqdybwc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2scdzprjz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqbqneg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhptyso.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyokibpq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjyzqiv.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2uawtbejf.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmbnuho.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwlsela.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lbicputt.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgpudmn.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2wpfexnob.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2frbfruuq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fadhgsxa.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdhasbdp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgbabrb.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2nwrojmiz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjdbcpv.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2loyrvloa.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2mdztgurm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkbuwmuu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mcacmtxx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2crrfmdjx.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2hbydhxhf.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhmlxee.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2ccujhyhb.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqkcjyn.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2rajcjzal.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2yczlsijb.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2covodqjr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2spxwtubb.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2dwbheojg.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kiespeud.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrcfmcz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjvmpfr.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2stdcohum.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhkjkqr.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2nczvilpx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2geatmtkz.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkwmmda.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2zezqajwy.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhdovbu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2daajynfv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2bgoqcizw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2bqrovatx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrzxlsg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2brlgytow.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2eagknwlv.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2pqthrcsj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2seixkbhd.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfiqyqc.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzfteroo.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qftkbmbi.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqqyydt.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxlwntw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwkvqpxo.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcsxhbbg.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hitodhyp.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmflmtn.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lksvgsze.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2uceflojo.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfapkauv.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkmbocbf.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2elckbsjz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2yaufsjvq.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmuenlbs.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tutpabry.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fohjesvz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgbkmjcg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2ksaplmhi.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpyuhabs.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jiqisryp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbnmtah.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgxihecv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sexfhaxk.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2sddmqfft.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2yehktvbs.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2yaspbcxb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdlkvhj.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dligptjt.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ishxnguz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxmpeyy.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2mbegdlon.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcqouak.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2prvwznmf.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2enaxmeki.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxbxfgx.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zxooidle.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxjbcvl.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwcinkm.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqaslzyk.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2minfhmcj.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtucrti.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrnrghp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2pfcrlmzl.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjeiwtjz.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbulkwa.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbeydqm.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwncqibc.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2gxkkkjfy.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2apdpbpxh.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzfvkqbj.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2lctndbnc.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqijuraj.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2eprqusyu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2nadiexix.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2qnlgcyyr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vevvhjev.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2euzonabo.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sabknfvq.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ouyzejsl.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtvurnj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2upsawqyg.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrgapgim.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2uayqqmke.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqoixgdz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2nlwbaapo.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzabvsq.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2iolnrsen.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2gjssqiee.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2pvoaahmp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqahmnsa.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2omanxqmd.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvcwfgey.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2hebvaoic.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfnfzhe.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2vmswprve.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjymctrb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2smhhmkuw.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2volcdvjd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzwqwjm.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqibdpm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2upgzjzfj.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2lmrathmu.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgpfcnqg.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbfpmmk.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2nouxsphc.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2zzanhdpg.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2mknnbjhi.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2jdcfjhjx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2budkcwcz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqeydpi.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzfcpvix.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2seykguqc.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttoombpi.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbolxikg.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkieqgii.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2dpsnwonn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2emyhlseu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqlnmiwy.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2keicmpnx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqlvpper.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfxyrmh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2npwwokxy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2khncqrom.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwwgpwt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2qjoaizjg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2yluzkasp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwkewph.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzalqgb.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqiowkrg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fufvexvh.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtadqxc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukytjygx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yslczyqq.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2koxwpeeb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dtytgqiw.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxqsuot.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2gwabfhry.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2epmxjywj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxzgjgx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2ajajzsuh.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2tjlfhecp.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjgzcds.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2xsceqasf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjquejd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrxyyji.html


<!-- 参考信息 -->