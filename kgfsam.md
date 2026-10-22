代发 wailian999

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqwqjhx.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2imerawka.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2swzrqycx.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzhyfmc.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxomfws.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2byvguiki.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2guykggqm.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2ixiqnfkq.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqdxnpc.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2cwooajca.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdrbwke.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpoeutcw.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sepmkmam.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2vtujoeyx.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjuiadiz.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2tishhysm.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2wolteicn.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjoawbl.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwkqvzv.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2cakbdsvt.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtovlsm.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2behlgbzx.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsbiwdwg.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwrfexp.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqkovgk.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zribvhuk.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmrmalq.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2lbndincv.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjljiyb.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2lnynihhg.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfhexlx.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbjxwiv.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwkldfe.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2jodfbuqp.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2cilgwgdc.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzdqmik.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2vfeubsog.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzhxezvm.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkmxsrh.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2roixttgb.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqjxgrf.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2appoqxnr.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2motshves.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncviokqp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmmfglr.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzdiffj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2crdfgeoi.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhrddcw.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmbnurj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oufadmlc.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcukkanv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2agrdhsna.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdbdptk.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujymeorp.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcrnkcq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xihgzran.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ddpdmxtp.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfaigvc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2spgcfgsw.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmbhyab.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfuirnpd.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2kjlsozir.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gibfazqi.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqwezsj.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vledcggc.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mzyfilyh.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2urikhmtg.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2thsfehta.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhcuvet.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbxemmn.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxnzuvc.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykcsqvra.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kmutawkj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2olzhfpvq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvrxyol.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rykpioga.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kmttgilp.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2prrsnklh.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2moqmahrj.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2dqozhzhp.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ampbhhmi.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdqozhu.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbywhvwt.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2lurkdbqt.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2pypbgvvy.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ftimiysf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqgatqb.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2owntfrbv.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2rydpmsuk.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbqroeu.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2kocozmqg.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2bfczxgmh.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2uwhzmqbb.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2oxehljmu.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2htvbqqcn.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2iowadepk.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2etpbyrdd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fllfkchn.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhdoiop.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2keykscnf.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqppsxrf.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2jzujchzj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfkwhdd.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2amqkssow.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihaurqkf.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxromzmk.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ehrpuqie.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2zwkszcfo.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyldheez.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2ccfbwokf.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2wvlbdqff.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2tbeczmlt.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwicrcts.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhsjnjx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2swpnjzsz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2jysmlfqo.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2atyfqzas.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xynoipgw.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbzegef.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtfnxxr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iafvmttq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkqljna.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2qvpzpmoq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2hcepjqnr.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2awqaemnk.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjcoyun.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxizrxkb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hieczdhv.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbagzut.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2aosvtwar.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2ztknyeih.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjmhqym.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnnyvce.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhgwwep.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxeolzd.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2jpufqpkw.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2cajkdnhs.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqjdvwi.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2jfrcvcuf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2yewmzoqv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2jutlrcbn.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2wqcfuoxl.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2qobxlsju.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2fypleogf.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2mboiyuwe.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfimnnb.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2hyaxzhgz.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2jscphhli.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2eovpbexr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2jznnqwmv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2vupruxgl.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2kciepsyr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2rgydicjz.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2uauqoybm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmlfvru.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2zatlhttn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hdygqjol.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkgfnxff.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2woarvsut.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxcsarss.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgcpger.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2okotyyvr.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2odwkwgcj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2nssjmztp.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2midwajnz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2liypzvda.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2opwwrzpd.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqxfmjy.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnnyijt.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngsnqaqd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnipdvpu.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2zxoamhpb.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbiycts.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nmyxwxqp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfyyrok.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpsphhrp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxiokwf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxmgilw.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2rauparef.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqrarxj.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2uzeopxij.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhljpfix.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2goqtttwy.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqpsxuk.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2ufonhcbu.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2zwpznwja.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2cpdmdufy.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lbunkvyf.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2sybfrebc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkbpcde.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqamble.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ojomgmxs.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvrsssh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kytxovum.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrevvbj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkotjvu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2capvampc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2bagrxkup.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2vxweloam.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhobaqy.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2jyvxdtnj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2vvolsgws.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2huryrpwv.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwotisa.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2agrentxp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppquasuw.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bphtanyh.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvgsyuty.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgmygasw.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tknlyaqd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwakxnb.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmucpnr.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2srapkpwi.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2whjttdqt.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2likdtnne.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2otkqzsze.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvmcaec.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2homhzwil.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2iudmiicm.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjeoeiuo.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtfqamm.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hwoohude.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gejyefiz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlaopuaq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2afbvsftq.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkiiyypi.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmtuxns.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2dznzivqe.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhwqdwxf.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rouofaxu.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ocdvoysf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2tavllazv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfxknwe.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2kobaaihy.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2svjecgrz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2wykgsfam.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ofzralew.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2xleuiizc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2gynxjxgm.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uwztifgn.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqhprjje.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtchmfm.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmgtfoe.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2edoyaaey.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfivdhe.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtubvwdh.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbgdxrx.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2bswpjjpz.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqsbyen.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxaajka.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2swnjhpuu.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvyszpzo.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdznampr.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrouvux.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2zghsyogx.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2thccadmz.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2onrftyse.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xeptfgja.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwijtijp.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2waielwhc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkldwvmu.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2tifutznv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mpksxqzt.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2hohgjwib.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2szoeaigl.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xncvsrbp.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqyoplt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2segfovfg.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlnwusd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2vyzyeufs.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxntjue.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2cimfizle.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iuriplea.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbqyapz.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvykxbp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2mebrxyxt.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxaxlder.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2butjjzph.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkfgvrrk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2eepcfjfs.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2cqdhsnaa.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2yuxjxxyz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvqisdy.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2hudgsnhf.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwupqqy.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2qwevbdbe.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pckmbaup.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2mhtwtkrr.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvanfrm.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqmzzeo.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2elotkdxl.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfqszyc.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2salmwrjw.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2ncekxgtm.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmekqxf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfkazlpw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mixxmjna.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihbylbzn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2yqcuzpah.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vujafzoj.html


<!-- 参考信息 -->