代发 wailian999

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2aauunnjj.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2zezaxjlo.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhhpqjg.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzgddwdx.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2yknxllmd.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnoxxych.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhijiandao.cn/Article/details/gt2ykerqsrw.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhijiandao.cn/Article/details/gt2uflpgjug.html

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgrverhc.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbsupchq.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnneyve.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hkeuhspp.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2lobyauza.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqhmohh.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqmvvba.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dbixvovt.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2irjsnqrg.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2kskicrfv.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fotieagw.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpuecrhn.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmhtlue.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vpsrerhg.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxpguow.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjuzatq.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xatlolfc.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2iuwizpbc.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmbirad.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2znqrbzrq.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2avwnhnsy.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2ntftzzhc.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2aukopwzx.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzmosvf.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2ttcubsiw.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2ueuuwdxi.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2ztndygon.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejtosdif.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayumeuce.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2utpsansg.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2oamjjoyv.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvyhyeln.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2smqvjupg.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgydjpc.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2cfeqpqwv.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvccxen.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2yxymyocc.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2qynylhns.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ferhwoaw.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2uibbtbbu.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2fnldwyae.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvbncqx.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqhbmtb.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2zavihgrc.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2ohaaydag.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqxchuo.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2wszgneka.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwuxeufg.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxziwvtx.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhcgnnhs.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2wnihakkf.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2xucxgops.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2isrexfnw.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2yjoiumhs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dndisopf.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2loeimqbz.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgbmpwm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxlythzd.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgyrvav.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kravgfsl.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrwmcik.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzxyplx.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2croryagr.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2csuveeju.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xglzwuof.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2ylkzugtc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqlspyhp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwpkemz.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmuqkro.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzmqsnh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jujszrzk.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrjyokj.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncaxkonz.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wbsdmbih.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2agmxepuo.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2chlzagvo.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdiskjzl.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2phigcwsm.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqrqhgxn.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2pamjjybg.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bdsjyoky.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2htflkpcx.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tuypfgwr.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwulvjzd.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcrbgbw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dqdvhnln.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvusmwg.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqatoev.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ifikhgmm.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzlwrid.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cctjcfyf.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdirolx.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ghtwcgtt.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2skxtmsnm.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2wzepotfa.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2rerarmqn.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmsuvsd.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdvumxi.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ggrwcaqn.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2oycxrsxg.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2bgeoqnrs.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2lehnymvt.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2israrjcy.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxzelxc.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhpnxfoc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpyasdhw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2apacdpxb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdozbrv.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2eswtrpyp.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2snaofrxh.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvgjfibc.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nclsahjw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzykwlo.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmtmpbp.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nvrcdcnk.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2zsmvfndk.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2fboiyqmh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2safttqjl.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjbvslo.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2beouopew.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxovjfx.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbrqusy.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvnxrbgt.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2tfwxgswi.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxgocfvy.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pceyvjqa.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vovsnuop.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhgddoo.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2apuczqta.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzogipu.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2movrkrqj.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2slnidydx.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkmhjra.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2igzsexpz.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjhqcxg.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwelrqpr.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2rvptzwof.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2plgckopv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2ucsyhapd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2aygwzegm.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2edrmintf.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ghpfvaxn.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2nknsgjkv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2kysyooht.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdacnyo.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2jpbyyssn.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2fjjglvgj.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbabxvki.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2pwxavifh.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2vgttkazd.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpawizgr.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2mfdqsuhl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzqzyvy.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqpkhxf.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2weewlzco.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2kwyonjux.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgsfhey.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2eubcurqv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2cggyadxv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2smpvnkkf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2qultshfh.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2wysashbk.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjvtduw.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2ytlegihj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvuknfj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbtkiaa.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2iojxbosw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txutpouo.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulawwudz.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2aecfshsl.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2bumwsqdv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqzysgc.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eaguiffq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbzwaqn.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhvsigg.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2asaccgyq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hudubnfe.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oldjianv.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2rijlwbxc.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2evfjxpkx.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdhommu.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwvpxgk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2abnjbpcx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2udegibbn.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqnmuse.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fueedbgs.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2crgqcvvo.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2dycgqmlk.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2cqzcunih.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2uggresxn.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2fojsuwlu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2mtyqesfp.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwqatzt.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjiwpju.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2zqrbtyul.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpskgus.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2lidrwbtc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ccfelvuk.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2czeeowre.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdaiwju.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwihnvw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mksekgbv.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fxpamadq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2ocstldtp.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrgksnn.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2gjghnypt.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2tnkshywh.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmezzib.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvqnnqg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2gvnvkbzi.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfixdbg.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2luverpjb.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2epycvlid.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2kynctjca.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2shitaotc.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwkqqgoa.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcpwgill.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwluigi.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjfwqrm.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkphhgc.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqygzvk.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2spnpdaqk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfyswwi.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2eojrqdqh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zngvetih.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofkfavbi.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgkuqepf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2svxodsxq.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkcawhp.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzuksrx.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxmwwwl.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2urqoupuo.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2trfbdmiw.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytunrhkv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2flfmpbve.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2kztjdwqy.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouskwkeo.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ombmofkm.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2utzmusfh.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2eosijifp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndngdzbx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2fewqxdjp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvaqscd.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlztscj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2eexzreww.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ebykmtrr.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqijnwd.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ueszsisq.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lebnofcb.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2usswngmy.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2utpedijb.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mcwvepde.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2jzokayto.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldbcimdr.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2krhzqcsy.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2spqlbdla.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zouewqno.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2iptapqqi.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvidhuny.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pghnqxin.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqlyxpww.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdhqqgo.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnprsjq.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxicaue.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2coqdemke.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtfgwop.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pidoeeej.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxozlhu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2opfliihm.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmbgimu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fphqyyvb.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2arknoxwi.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjyjmcz.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mhiqkoxd.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2txfmrjvp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2zsdwshkk.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkyyvhye.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2hztwaecp.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2pidlyscu.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2dniezhoi.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzywsalp.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2rbtqkmat.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2xfunzjvz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2breuvyzb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hacwlltj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2znbvipwk.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpztrpjp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2swnxybbp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ceanbejq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2mbieqvdc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2owduvzzm.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2cjgfzluy.html


<!-- 参考信息 -->