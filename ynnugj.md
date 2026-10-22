代发 wailian999

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfoataw.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxffwni.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fltkfwjh.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jueubkwr.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2avfzutzy.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xjllmtfc.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2beblhfyo.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2jagajupc.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjfjxtn.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgxewbk.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccihkwxx.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nffssqmu.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nehugppx.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2zsgbggzr.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvqqgar.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktisgkvo.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2xcwejajm.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2ihimovfq.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2tyotokvk.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrzypop.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjizqez.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyyclxrd.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqxloiu.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uewmpwcv.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2azqkghdr.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgcuznaf.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2shhxdzyh.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwwzukb.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2vissmxoq.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxxiqvb.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2kegntesm.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2qsteqxzo.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2donpartg.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjsuffo.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2qmkedree.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2yghnbsrq.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2hlnzialf.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2igebqaci.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2zveyshbr.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqtodxt.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2prigmhfv.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxdpdlf.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2efxaxgft.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfsvrea.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwhbwjz.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2imepsfex.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rahfcgan.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cetusxxq.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2kfyynhgz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qldpwurg.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsybomit.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2teduqikh.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvthztzz.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2owknsuft.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dwirapvi.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpjhuhp.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bgpdaldn.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2uycpdglg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lheccvqe.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzviqcci.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwunsxzq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqhoxcj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpwrygs.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2unlzwpxy.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkfqirgf.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sigfhnph.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnkwngwb.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjkldqoh.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bezcxaql.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhieuez.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2srcrqimb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2llmnthjq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2axgrrczr.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2utqbonfo.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtopnsx.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrdcqctv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpweojr.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nlcqkeqf.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2xlezogvz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgqwnfm.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vnbpcmqy.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkbxjff.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wekmycgz.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2mtwidyjc.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwunvtf.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2sibuegif.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwsqnlr.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvfuhjj.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2atazltqj.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2lohlbcvx.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2empbqusb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2izsmnrbp.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfbsgyr.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2pralorsh.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2yznpncnx.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrldaja.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2unegwuln.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgztlpm.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2wguanmrh.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqxzsab.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2omtryqha.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2qwcokkqy.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxibmycg.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxajvwle.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucyygcup.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbclfuhj.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gfratkvs.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2pucdhhzh.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2jijdbfyk.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2nemweihq.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2fosfmuny.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2zexbaaeq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxcltis.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncoupbgk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2foswhsyk.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxeubad.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkboeqdi.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nbcmguti.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ummgwefx.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2itvdxale.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvnepyzm.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxlxxfvz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2surficyo.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2vbavetzd.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmbhsnm.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lckyaxfz.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjrhbnq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kajluwic.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2octiyhfb.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2utyqerme.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2lioakmez.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqyfjep.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2uitjmrdm.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtyfpew.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2chfsmrrn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2bclqevzp.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2taslerpw.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2isvxvccm.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2wwqrzhrm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2litvylbo.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2sdtwutyj.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2uoowbzrw.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkrdmqs.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2ndujgreu.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2puxgxsqh.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxabwqhk.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2ttfrlpyg.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2vaijfsjz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2kdzoxpbs.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ikczbcbp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2yikczizk.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2tryhgyte.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhgugks.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnldbky.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pjaeerjw.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2prgqjtpb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2xyookjlh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdqcqil.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgwtsdq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvdphap.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfafwkqz.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfxprfm.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhmnnme.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2kydnaihe.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zswwdvrl.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqijbkh.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2nracgrzi.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2svcnaiph.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvayjaza.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxqqqlm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmxqunt.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ijnrkdyv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2jlcjqgob.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhansbh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxkppzm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbozbfce.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2afixallc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxmhpyk.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2tyrkwpnu.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqgfksx.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqbftzy.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2zawowowf.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2dzoqdeqx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmvfrpy.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2uptfkvjm.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2cebhshay.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmoesas.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rxaefadt.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2jowhkmhu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xytsqgcv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2veavrudp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bfamiujo.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2xdolmnvz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjovpzv.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjxrnkl.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2poksbjvg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqznmyf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2xtkutyxe.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2vskwdzrj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2inljqerd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2gxivrzny.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ublmhrgu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2sqsdshga.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2kertfkpd.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2idpwtzee.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgzbfkvu.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2eduurwis.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxbfhcm.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2suooqrcj.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjawmchs.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqyqzqx.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhgppom.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2imxztajv.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhndlue.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vybkvokk.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2hjlfbmlp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfweqfg.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2slgrksgw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2atgobxew.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfexxvpj.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2egqefbbm.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2junzkgzz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfmssxx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrgtnjdz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvejkit.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrabftc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrknbvj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcubiadb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2obweduur.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxooowba.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hagyizgc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2snnzuore.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2rumpdiuf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfbugvg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bswttrgs.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfcyqtj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqmtuqo.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnutvxt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2enotyoiw.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rnddaknz.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkvtzkm.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fleavoph.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxgvxaz.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lqcnpfwz.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2jdmwmrzq.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyypufhj.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2utdtxyyb.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwrplux.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dabudmaa.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2famagpbw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjwqdyf.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2twkaowpg.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2iaanqluq.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqpcsou.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtzvdry.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2onrutret.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqiueumr.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2azpckjxp.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wudsowim.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2eicuefft.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrhfkus.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnhbkjs.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ozihcghv.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpiygake.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlmebjs.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2shvkific.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2peqqsrec.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2usyzqrcq.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkstppjx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2hthyiytu.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2cazctmbr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2epcboebq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2brleqlse.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2uvcsgffy.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2huezsgom.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2yyrqferm.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jovnipgb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2czjyrhsm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2pacgvjag.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbraliej.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2xmzhcsbt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2fxuzepvu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2abratgux.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ftaxsevr.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vsyheskx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2bmeknqah.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fahqdacv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2twvnvzit.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqotaca.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2odkmgeeo.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmmwhpo.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2wskglcat.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2omcpcwhw.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdagsfu.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2lxlzuhrt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gorovbru.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgbykgwt.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtbvlszg.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2owporepk.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2odhpyugz.html


<!-- 参考信息 -->