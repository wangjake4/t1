代发 wailian999

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2lrndzbmy.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2rroniong.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpklhhr.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxhlsxiy.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iehbsgwl.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2hkltkxrs.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2ungodoqi.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2gntwhgjj.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2owzkvlno.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2dycazwid.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2fupdysxn.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqamxls.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxttnoyg.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnkytjsn.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlukpwjg.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ergcgolc.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndlupang.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeketvxs.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2krairxtc.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2lysyknwt.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2vyarkawi.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2wgnpcebz.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2awvxqfwu.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2wpnwpzgh.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdliasb.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2xfihpypk.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2jgcjwnvp.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ehspdwkz.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2swmxomjl.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fekhimbv.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2bovfanrl.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwdffvc.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmrdahz.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2eochohrz.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfyfbbn.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdpadczs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwraiki.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjnyvjq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rldoisgb.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eznawmkc.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2whywnkae.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxgbryfi.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcqjxeve.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2flfcbkuh.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2evapnddh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvgujix.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2duvusaqt.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbiielak.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwbdsyt.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2iksebhuf.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lernumbr.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuazcfwn.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsnhfwbn.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2simoeqbd.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmjoonf.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2mfgtgjkj.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2omdsofjp.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ggblawtw.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2weqtnbhl.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvpepvvd.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fybjnovw.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2puyxdhjx.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcendyqp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2csykngan.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhtpfvc.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2btgenrsr.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sofvafqn.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbqqoaa.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2erfmznqt.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwhvfvm.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2nazjzzdy.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2scigahvc.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hmazsrng.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmelafdj.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbwsnytr.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2yylvnkvn.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2jbtecjve.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmosmmh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2zantzwva.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdbabiq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2lrympqjh.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2qmpfnjgx.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2psyqlwge.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2fdrxwnzu.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2nbaagejr.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2nyjdtntq.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpuqgcpx.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2unrcemdo.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fioifodf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhrhtqdj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgyckbxi.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwrqrdp.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fopjevlw.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2zwrdtawc.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgyrclxt.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uncytmye.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2yntvxyfl.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2fekrowdf.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqqilqp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqtxptx.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2irltndfq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2riwicvmr.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdbchgk.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2jjlbkjci.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyvbufnm.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2envrofly.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgspdto.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2ropzhpya.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfsnuvfn.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpknxdf.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hoyygqyu.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2osoilxlj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fddrcfoq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpvpvjm.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvtxtvq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdfrpae.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2njgesecl.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2knccjkvy.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpcqhypq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2oajmxcok.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjlmdwi.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2zorhtogt.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2wfosfeck.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2plbenaja.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjgseda.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2bsvqrbma.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxmaevz.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2rlaokccb.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2sblmixov.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2hqelskwi.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2fplyhycp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2lynrriqt.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2crzghiou.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwphggb.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtmlglu.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2fheaaypk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2augemshl.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvniztfs.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2nvoegynv.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2mydovakj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2mravkmta.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ylekeksk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2wovuepym.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2asksldxu.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2ksebkoeu.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2oiegkwkj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eijspczp.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2axgaezbz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxsvuof.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbefzzr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2dwyekdwz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjmgjhw.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aszbrrol.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2ocyikync.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrnmotk.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkulmssg.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jomasdlt.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2fiypxwdf.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ewujtout.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxeaewr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrmrcic.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qteumjvd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkxebryi.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2exrmqifo.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2ymodroau.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nkdhkezp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2zbyrukze.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvqmwymt.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eiernmum.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gijywgmk.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2stpxvunv.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2aghodalx.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2vutkwyty.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2mybpnlyg.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2jixmextg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzqdhxv.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdpzeuy.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2qoclonsk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvbrybl.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqswkcl.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2sflwodvt.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iekjvphz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2miykswdf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kpgdkvuv.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2hdyqzqnj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wldlsdsz.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2goqqgvao.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2poaynbis.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2yiszzdor.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjjtzcc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2ftglpzug.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2gnlshzhi.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2buwgjodj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhjqtdf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2wxoauyrk.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcirfuf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2opkteqtn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqmzfaj.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfuingqk.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztcyrfcs.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjfhpylx.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbkqobq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2knnenity.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnyrsjea.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqkbavz.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qshnlhnf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzauprmm.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2penzvuci.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tpsexvfm.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpprpipk.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2reysdfsn.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2uijamffe.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2eglqehmg.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qqglfemb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nythjjrk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymyqtdkm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2icpvdffo.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxtullm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdnjpts.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmowqgv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2avzodtqu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bemlbspd.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvgjkdt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqwrdbz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjqoefo.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzabdvxg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbrmbmu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnqdmji.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2udkafpuu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2uzcufjlb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfpwzfg.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zldlgwfy.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbofrus.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxnbbmma.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2srfobexv.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtbesyp.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2gildqurz.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wescybqp.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2isiikbfh.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxrllnwt.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2maxvrjho.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2ofyqvwoa.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2waakslvy.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cicjhywu.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmevzbad.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmfdlgf.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwuygql.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpbhtcn.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtctqjir.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2glbxietl.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyzdwzit.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqdxiygx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlcntdbm.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2vzprvcip.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zvpantgt.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkpadtyu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbsguza.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hdsrwzhn.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2ustjoueo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmjqmnj.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cklmbmmn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwlgogw.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfaxahjr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxanzxrl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvsnrgb.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ozxdredt.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnxjlnz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2tybbtjzk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2njnpuiei.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxsfczgf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgjdwum.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2avebuqbz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2gnosgams.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2ykeibamt.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2swrudipc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2nwregbvx.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jlerqufe.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2oblebtcc.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygpjbjev.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2oszafaag.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvxhhgx.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqlvsff.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2srxyaivc.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtuzrwz.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2vdaplafu.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2jzurdbre.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2salvhrcr.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yucexcdj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxpounx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqgwibsm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmvlevv.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkinyjav.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dowfwxei.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmuqrpb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2xzzjmuhz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2igaduhdp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnblipfk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpeuploy.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2stwqrzwx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cugqulug.html


<!-- 参考信息 -->