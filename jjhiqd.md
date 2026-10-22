代发 wailian999

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajuhvwyh.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bpkzgact.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2vqljegnk.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2gadgfmcj.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2pfpulsya.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2kovxsnft.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhqsorvt.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fydbdtse.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjqaqgm.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzdhpxt.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdttvitx.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwluxauy.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2mfrhdwrj.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqolmrf.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2hvimmfua.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2frjokcbr.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbzytnm.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlodbpp.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iybupqpa.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mclmgjhw.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtqutxt.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sitdtdok.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2yaapfyko.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2fydtqcfh.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2iunmxlsj.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2jtgghcmy.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqhlbnc.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwskwwx.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2slkfxupa.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2xtkimhbd.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxnrbyd.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrjawev.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2mvedtpxu.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2baxqpwvo.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkscohge.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhnghfq.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcphonsn.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2mldjmxmj.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvbmomo.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzgniohf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zflzmpbb.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ilivexbu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cikllkaw.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfvamys.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgyilzu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gokqbpex.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hauvnnrd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbcfsjvt.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ursqatdz.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xejvmocb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mtghgedd.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2giqnebyd.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfyydar.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2vednytwq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrnvzksv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2erlejmdh.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjzznul.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrxaiyw.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gohbhekg.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2efkkfttr.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2neaugzln.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2udghlkky.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2clepaleg.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2olcvwpdu.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqqewesa.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfoupqpi.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgubispw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2itjnhwpn.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fydtrmvd.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2qxdzfotg.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sekzqbji.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxusixzg.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rowjijje.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zdywugso.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2jhvhkczs.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhhtnyc.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2trivgqby.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2thlffwox.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2snvqmjzs.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2bogqbjuc.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxopuyz.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2zvyoqyxb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbcilfb.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2xirbalgg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2xekcqmlw.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2takoqvqf.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2wromvtzd.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmivukj.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2eayrxrlr.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2xfintjau.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbqefcyl.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmdgeqw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fntidiqb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2srntqnzm.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxbjqnq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2keqhzfzy.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vscrnfzc.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2oonfixws.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuonzxpu.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjkzlfzk.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpumtglv.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2znzslwki.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ihywnnbm.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2zngtdeuy.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2olnymmoi.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2eglaxwqn.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2kfphwedk.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2qftjpuit.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvuhgber.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lksoybtf.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvnsgyv.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2whhclfsa.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbybzvzb.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oojcaczd.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fooczmxu.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbpyvkx.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2brzpnlke.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjuginas.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2ngomdzhb.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2tashwdqx.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixaooeec.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyrdbpjp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zznljuba.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkvwlfev.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2wxhkhrst.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2iuimbdbj.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2vvzkzvzl.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2jgpkbtku.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlfpaal.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2xdrfgkmp.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2frqzpevt.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2frlosffz.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ippmjqld.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpjqdne.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2ooejlttq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2vljblhdz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2xuoinnwv.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2owfsptwg.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2cylnqmpm.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdghzrg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2jydzsbwi.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2zryipchv.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2koxdnamj.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2ewyrjkwy.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzelijc.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtqvlwt.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2frtzxdcx.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2cskmlggp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2zfomqpvs.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2hukbtcty.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vfsglgjd.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2tnemhyht.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2jyvstleh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwirgubq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2psxulozh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pozogvnz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvmlojh.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2dugiwwpb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2gthknvyv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2frkulzxl.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2icksnloa.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtwrkmo.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2gifjvxyz.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2boinzoho.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqsiuqj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxyhineu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2byghilyu.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpktzwm.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2zwlxfsgh.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fcnurfmb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2rzplrkjg.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjyjqykl.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zednkgvq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdqnxfz.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2sknvqhwu.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jogdvwgs.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2elrjzvfz.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2grxewcti.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvjmxwv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtqqmlh.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgqlign.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2wcukhcmv.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2jeaflxdj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdqvtbw.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2xmwrzcug.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2znszxexe.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rwyqpsla.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2imidgfpj.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2cizijbcz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrzsrsp.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2iexaagdb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2brjvdbik.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2bmrsfcee.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpcgvhi.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2zdcqrrwz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2urqzpsef.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxaanae.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2lzpzomqf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2qrmjujzv.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdamaku.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwhzxsw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2oivjfhio.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmyoidno.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzkgmqa.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztufcblh.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zztwnkzy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqskjreu.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2htzmdetg.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pncuzfjm.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2eetfwlgb.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrdcfine.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2mftvfmfm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2svuanase.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdzzsvm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlfukbn.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxdohxh.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ougzdekp.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrusilc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2emghwgaq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pazrovsa.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxmzmyp.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhzkehd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdegbiku.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrvwsje.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhunkhpt.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hounhqmw.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tlaxropx.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2orkaqvvo.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2azcmkqnv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2vleynsxh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrqkckq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxmlycp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ieyjjnpg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxxuoem.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkuaukx.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxrexvo.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqqkfsa.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqesqxxw.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvrfyrs.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tubujnfx.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2hwocadwo.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2avebauns.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2yaejtoie.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2stiaiocp.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2sowkyyva.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2gtuhxkax.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqrgqsv.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2llbmsnza.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bknotxyo.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhkjvvz.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxcsrjd.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2mctnzrcx.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cloxnezp.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mysvguod.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdyqnmm.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlafdbbe.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2rphynqub.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2nhohayyx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vvozbybm.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrrnqai.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjyguqsw.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zgbiogeb.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2ywlujanq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzaobkb.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2optrwaxo.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqiuykl.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2kuopzqkk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2wplsyxrv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxufccnw.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2orfxedkw.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2iwcymfwt.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2udlusmvp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2volqgtjh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrsvkhx.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2cozwoket.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2emoemqow.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2tevbnizs.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2avnrjhjk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2yiqdmxdw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtijodc.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jpuwjzqr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2xoysyycl.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lylfwncw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2kjoxqpoy.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvaodzy.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcylymkz.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmgjmad.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2hmqsxjkn.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2yjpsklgv.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2dayuovgp.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2xvgbldii.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2taaekxfi.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkukjxcd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrszgukz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2vudaqgau.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2oickitdn.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2srngovfr.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhcidpc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxuipby.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlwxeum.html


<!-- 参考信息 -->