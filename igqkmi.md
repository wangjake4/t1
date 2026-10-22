代发 wailian999

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2obujsvbv.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjnlwuj.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifkenpyr.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrvydfu.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2grkgbrwi.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2hhqrgnsd.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyujtuir.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2npyxowld.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2dvglpqqp.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhfhxda.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxhkflu.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyidwmdd.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjynugx.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bnmixjgu.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmayuke.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrzbozo.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2nsnqxnub.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2cvafowvm.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqmoosj.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpifpxex.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2seqcowaj.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwpdxwq.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpbycyg.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2tslgstlb.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbtxgmy.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdgvnsn.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2cdpwrlxp.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbqzeio.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2stbyyell.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2omxshxpx.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lygyrotz.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nytqqdwt.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eosebcyw.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtffqjqz.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2mnsnkddy.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2iohkczni.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2dwcrlmdg.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ajpddyrp.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2phppzppv.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2grqjmyiq.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2rlvpgsmo.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2dbaxqukd.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2slpegfye.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2lcoehrde.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2zqaknylb.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcecjxpa.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2jntpgkui.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlygudpf.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2czrsndyr.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqiuhtae.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2xwkycyrf.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnotisjd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2raefhaby.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtigzto.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gveckgup.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yjinfnzt.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hnexyqet.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkpogfjq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjyklzf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqexlivn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdrkvfj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzpuykw.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kxquazor.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qigjosud.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2grrploep.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqqypes.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkjuqee.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lckzvdcy.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbixdxx.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ozqdwdux.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jgdzopwu.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2hktmtgkc.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihoqpevl.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ainbbpcp.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2imhjdxao.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2asppbvts.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjpdaxl.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpcnbsa.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kduvgeok.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2rygajhqp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrwxzpl.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2lshpghoq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zjbepwdt.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gubpyalv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmwobxl.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vwskzjip.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzgxxkd.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2cizwfjzi.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2apgpympz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdoghmx.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vssowyih.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2xsssawus.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2zdchxxbp.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2amzzaswd.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2svlhylph.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2lxzosktz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2xylxxcpg.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2altqipwd.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2xpadovbe.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2zftrhzob.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2xiipazuh.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvsbzsr.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnirdjld.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwpxaio.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpjycya.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdmizeh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnwkcqm.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2zatxzbkp.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpkagjx.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2egfpneqe.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbydzosa.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2llsqpxms.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2plxytuaw.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxjhiul.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dawzslyx.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2wsuicycs.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlexcclz.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2xqlcxoji.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdihyfl.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2emcdiczk.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2veictelz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgsylket.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdqxsfa.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2oycukllb.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwoqrppr.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ojhbzcvd.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjshzfrg.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvxkgsh.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnslmhyo.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdshmkbr.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2aegwrjau.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2puupgxti.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfisusay.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjayaenu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhgrydyj.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvocnwgs.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2eaclmuut.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2drukcrlc.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2eryajpsf.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2psypvydc.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2oycgmxzx.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2skwhezyj.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgbdfpe.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2gpojqlkg.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2cympqujh.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2opsooxub.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2kwuscckp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2bicrbjzd.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhumvzl.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2chjrpeuk.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2ionbujmp.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2jtpkkgpz.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgxvstm.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbujpghz.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxhpguy.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2vceytnix.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2krkoirtp.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxyztwh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2frhbetsc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2ykomnvkg.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkpbqbw.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwfvrvu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtuodpm.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwulsoa.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2fxtmoqfz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdygpyvs.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2wpatbdff.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2agmhzzsv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcxbsqvr.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2pblsanzc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2quhokwsi.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2iiwwgfkm.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xhanjqvc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2qgamyrnr.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2dwgkhspe.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2nbgxeooq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzegtys.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2flnrxjws.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2kluyhose.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvzojol.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2usmanimi.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2scyxfxbd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2rxktxodn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2qeaqbpyc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hkzjftzw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzggjhu.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2nuyvoiqe.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2fkpvqdms.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2qvfzhliy.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfrfqez.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2ejfzjdyz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2itofomfo.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2bncykrzd.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwghtjt.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ojcvexol.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dtudfeow.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2omvlukxv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sxlrourf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgahuen.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cboyglev.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2huddnshn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ltnxyhjm.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xocaztma.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2rwctpnml.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvhfgex.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2xzijrzej.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2iomkkbuq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhhqhzx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpctdcd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2rxkcqdjm.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2soitvtfs.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2fmpkcgaj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfjwvle.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2udozusns.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbiemhsf.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyolvorj.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2azzasufk.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfbiaxhw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjyxbxmh.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qexncbhp.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fgereioj.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtntkfwr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2svuknklz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2ghpstajl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bterxylc.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uputwehr.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2huvpvojv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lazxvryn.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2eazjxdgs.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gygukjms.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwogjdik.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxypjogw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2pimemwup.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjthewnb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnyfyph.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqsxtuso.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwrwplnj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqcjfhu.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qamaaxjo.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2iyynyhyi.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvhjhcd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2booslovw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnaazepi.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2bojxfxfi.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2glzplvrk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwmqkzh.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2leeutsmo.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtdesiv.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhhqtodw.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxfhulc.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2sapzyqeu.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2pjuwueqp.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2sivkkvpj.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tejklxpk.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtdbuzr.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdpnykek.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmopexd.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2ojyytxvx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdcnrwh.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2aftcxqzj.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2beilajnr.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2afrwzsmb.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdxefcl.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2rekdjmte.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hngwopsl.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jztoossm.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgnvawvd.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2venlgkrz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2nitvmhdf.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgjnqzm.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2eiohbdwj.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjpbbuu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2inpfdrqo.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqwjapj.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2vndsvczo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2rimfmujs.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wphysrrb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2mzmzzfyi.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffudynfr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfuarerw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2euoiwmrq.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2hxdbljcs.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbjwckz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdgaaji.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhsukvul.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwetmzzf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2bubemxck.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbexvwig.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbzdhdk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2dixvtjcx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2laoscysw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2pkszqutw.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xkveacfw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzpgqyh.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucsbwycy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2tavpjbtc.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdqbdnb.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkirrebi.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfwdnnw.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ipypaogo.html


<!-- 参考信息 -->