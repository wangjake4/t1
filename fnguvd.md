代发 wailian999

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vesialod.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrksyja.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zkafkzsz.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2iyintpoz.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwbfnwq.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2xoctzjef.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2beeileig.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2urodxfmu.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2hdkjdhut.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2tevdwuxi.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdkvdfz.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjqhyxj.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlnltvzf.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mvyiwdvi.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2qckmwxwd.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2wghigdtr.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxcdhvv.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2vsliatev.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtidrkhm.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dojiujmx.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyzrnqhw.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2ipizlovp.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwdomhj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2maadwdym.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbxtspt.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2bajsqujl.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjlbhgq.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwvjovc.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxxdygg.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyddutgt.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxawrrzd.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2imxzmzxe.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2diykkwzx.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfhcaga.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtsswkw.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlrdomg.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2vgoaqvnc.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ggohtdfr.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2csiriblz.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjboolo.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2targgrrb.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqrifxw.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfwdrfi.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2zejhixhh.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2byacxcqp.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxeyclfs.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcnwfjur.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgtdars.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2mextaivu.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovattdyg.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbmykqs.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2acqlmdmu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdxovfs.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2gtnfhmeb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2brviikce.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjiwqxz.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ieffcqio.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlucoupv.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzotgses.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyelzlvx.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwfrryu.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpkbkpm.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrmervm.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdkkrpwf.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2voxogofk.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2dsyjvsgj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oupuppui.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2chkfnaet.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2metqylsv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2byywlelh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2swjjpbuf.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2nghmyvba.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtmxpsfe.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2agvwnfza.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2asvzvhbm.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktujplbd.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohnvlkjm.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fngoynsz.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2awgmdodr.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbhctwon.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxrlqto.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2eifvikol.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdwgexf.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzhjhvk.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2phmlaump.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvaxpzr.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbvxhhj.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2zooehaaw.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tmrddzsj.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zymjbgbu.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bglafpjf.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzpvgsa.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkrshzl.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvkbibu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2efdukcyr.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2yqsxexsv.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhkaphw.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2wuyohadk.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2fhsgzjaf.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqqrhfs.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwgxsqb.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2zqamltll.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2hblxrqyc.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zktgwsep.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxridotc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxhbeix.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkctfilf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwuswhyt.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpujmdic.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwgujjn.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2koapffdn.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2swhtikba.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwcmfgws.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhyymag.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbhvnwh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkastou.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2lajuwjce.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2cssodfpo.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ionakjsn.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2tckwuhyd.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqkepaza.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fabfmpdb.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrnvbvn.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2bxhrcgjb.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzzjntkk.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmjuhix.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cslsrqqb.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xwagzrkf.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvgkmvt.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxzktahe.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcpyfgj.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2vdsxzaaz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysaocjxr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzkxzqa.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qskcpysp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdvnrph.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2vuezzrkc.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhkehsx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxalcwf.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2rsopdcwx.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2vanshhhl.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2vazipjzn.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2qyteyuac.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2porcdzgh.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ycurkdzy.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2rymuiajw.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2irkktomx.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2mykcsiws.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2xjilxfnx.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2hqcdrzzu.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2kibnehkx.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2nytcyxib.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxbidhu.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2pufuiypd.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxaualn.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrjreqf.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2netnmczv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2hswueljx.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2jkgrovto.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxbcrvt.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2kcygbate.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpxyjdu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrdxnii.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfcmbgv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2nyhkmrjj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smzryfle.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhrgmpo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvuwtog.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2viikmhct.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2gibqxkry.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2bbczjbpu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2iijsptgd.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gwyifjik.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2yelvdxsn.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvfuuko.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2esvmrztt.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jynfpinl.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfljljtx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkymyopm.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2mfooaxpp.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2ovizaetk.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ziqxziad.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2jbduixww.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2vagrqbke.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tstrvfaw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpyfwoe.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2tuealpza.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzgytum.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2gcwbxwdu.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttgqcsub.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2wukzpone.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2hyyjtbzh.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2nodmbnop.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2icblgvqs.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2skjzdhuo.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nddnqqan.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2pilyyksu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dllwxkwa.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ussbgqeo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwfvgds.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxkukvm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cviddzsx.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2plydolii.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxsvxfa.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2gthiyuig.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpuvlsy.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2siqtvcui.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2esgkylkb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2piiwucva.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ljnhatve.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2volcsdhb.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2brrcsqkb.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2uqjszmzh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2jocibkuj.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfwxwjx.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfyhehfo.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvqfced.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yeuksziw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjpzfiy.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vaefardj.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2olcdiryd.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xaatosjd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2icfcomuq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2wmexvdxi.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmshekdf.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyrmjnun.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqnygkut.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2algvhapt.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmdbzdp.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lfsypbwb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2adgmhtch.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkaqbix.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2pajrbjjo.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjfeyin.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2flpapdvi.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgxynsxg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2urqkjndu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqqucsdy.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2woqkaglw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnegwuo.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2aalzcayw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfcmddtb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbogevl.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzsgranw.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwbemeb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbxnhah.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhzxdjp.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uwieshay.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aagtqcsi.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpizmoey.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfclctt.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jqrscgcw.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2jajyrhvy.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2idvnpnfu.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2blehkeby.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzijlfl.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dbybqhib.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2ijnqsqbh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcdwhna.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pminbreb.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uupdvcmn.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jehbivfe.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqqoaoo.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ktyckmqz.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hinogkwa.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ptwpjxeh.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkoapxni.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdothqu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwfvtqkt.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2purdfrgo.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bngwmwkj.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2mszrchgs.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzzfvub.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mbpafwwh.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2javgywkh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2fvzfatrr.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmxpaja.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2iuelxioz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnoryzma.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2favzwayz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tromfnkk.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2pofscowc.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2brwxudwh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhwuhew.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzajbedj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yyejcdyb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfxkmrt.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpbzplp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2fiiewglp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2xexttjxe.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgpabixl.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2mdglrwzp.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2objnzfjp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2mbeyyinj.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxleszmr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2jqidhfwl.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2sculxwus.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwfpzfd.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vshqfttg.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2kjjnigph.html


<!-- 参考信息 -->