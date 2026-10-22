代发 wailian999

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqwfqwp.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2raukmyds.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyvhquog.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jzeorgil.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvyarcp.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2vikcqafz.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqevlwlg.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xevhdmfj.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2jykiyqrt.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhywgtn.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2emgzushs.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuywvfko.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpgmcgvb.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmzobsy.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjaudmb.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2qhwnxygu.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqwwupm.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2wbogujqy.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2idksavxb.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2spaaexzw.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2axwxocna.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2hbbtfwln.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkknnzs.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwgvbxrs.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2olhyojpp.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2ueftllbv.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2qogfpzjh.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2qeebljni.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyoeupvj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2szxigcyy.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2buxpkgeb.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsijnfoc.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbryyxqt.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhcaaqk.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqvurre.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2huxathao.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2xknyudid.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtcdcby.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2bgqbmgqu.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2xmxrdyok.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdfcelq.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2iyyrsjsv.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmpdwsc.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvxfbyw.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2pambgdan.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcueqxkz.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2aekrivve.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkcoqsfu.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfygvls.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2yreedggb.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpvagkr.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtyuyzff.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ehorturq.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2uekxrflk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkztthi.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mslzpyyp.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ixlmitec.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdbeuwm.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlwczaa.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xerhcmbe.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgghxqxf.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfbbhnrh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sywutzbc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2otwkfymu.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nwledaux.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2tegajspn.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2etfcsjug.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qahnlpfs.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqenlok.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2qpigljdt.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oaarsppk.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2piakdijk.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2uajyevxa.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2forgxhej.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzfozyrn.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwukqcef.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zaxjltvk.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wabujwem.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mowqezch.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2utryzwhg.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqsnxdd.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2fycfaoug.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2otsnduqp.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2olijatiw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wkefdcpq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nexqzaej.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2yljponwx.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2flcennlo.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cphuevgl.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnlkkad.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjzzerg.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2wiefvhxv.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhdeaus.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhdivcl.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxeisii.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2cliubnxy.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2mcviliua.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdafbab.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2mmglimqs.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2nicgwqyy.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2iqnhiizd.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2xilgliug.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2khodjljg.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2omiikuzl.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwcfbuz.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2cegmpuns.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwehkxyo.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozqnqtaq.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqjlwhj.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2rstqdtjq.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfasdir.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzdxcyr.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsxckubx.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2btjathgn.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2axpefxhk.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2pwtxqwyi.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2hghzlmsk.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxlyaok.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2chmzyniv.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2odzcowcz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jszpkjlb.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ornhbvbx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmseckbc.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2qufxezqw.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpnrkii.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xqdohadq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lknikjqb.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2iffwdyab.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vadnzypz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2atzreern.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfwddkw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2qoouokfk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2afsaufyk.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtzliqq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2izxldyba.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvjmiib.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2gdrdoqfn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2ethzaqml.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2zatgowwr.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ijsnqrcl.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2cgtgaaxc.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2jssnoqbe.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ockqicfn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2ciutvznj.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2hoowxaov.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtqrabg.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2afirdwnd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxfcjrs.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgfzwnr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2ictrbwyb.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnsuvxhk.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2ygabpbtp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2nkdzqerr.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtclwozp.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2esnjumvu.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2oclfzdwy.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdpcekw.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxnksbh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbbfyrr.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2otuhigyb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbmsqtw.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2dchdnfwq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfvdqmh.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2udfikqao.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2mxdwxccr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzpmuvi.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhunpjh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxlaodz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxihmqwm.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2nljjgdnv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2raidphtd.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2rucgfgrr.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tepstefu.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2tgnzgnuu.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwnvche.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhhnake.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pplyaxwh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gaholmiu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkwepcl.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbkpwpl.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2dmoubjbb.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vgrbzlqv.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2bubybocg.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbltmxfw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzzuzzp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cbeifoig.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdzekgf.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2bveoomyv.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2cugqerho.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2antxbshr.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2rdxipfhn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmxvacp.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2fxrrcapl.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ytgurvgr.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2xtaazubc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vsombpqv.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2omqbplox.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vgryvsrj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfooffb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tpinjytc.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2dekvktfk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2quaknuji.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kydbcbye.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2byngulht.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrnqdld.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2gvomulrv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2fbfowqjm.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2asqtaswe.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvptzca.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwbtbso.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2qunsouyf.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2esakoerd.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjaioec.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2rabqibea.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekegiykx.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwwwkvu.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbyetzzk.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjgekau.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2jooxmgqp.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixoxdeff.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xromouew.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjwbqoq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnbzcrs.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2qncsddyx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtsvlpj.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgtlgmbj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxieyatj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbiuaau.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymorgydt.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dygkddie.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zivhdsxw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnuvpki.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2nvkoefpg.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dglclmtx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyaaisgh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfapgxfo.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fktsoycu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2eohunpgp.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2duyczpgi.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2dralepaj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2tctzzndd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2eiqrgkas.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2woaynxct.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwsqmrgn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdupusw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2isxuvrdz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtbwjhl.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pcodzkcd.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qikklfwj.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgoafmze.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbhjiqt.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlcutnr.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhoighe.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrcexpd.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2grcjevai.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2fulfuxcz.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ognnlvil.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmjrueq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uuochzcf.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhcemzut.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgartqzh.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvwufme.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2npjjvblg.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxrbplc.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfmtwxy.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrqthgp.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zneddyhw.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufafynqx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxszqbks.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2bjocjolm.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfounne.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhclbaou.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2aztqdzij.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lqsfjzdv.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2vwinyyda.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2irjbvjob.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2alomnidn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2vofdmyoj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2ieujnsai.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqqwduw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnlbxpjk.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2letktseg.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrizhui.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqpdvbd.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhtgetm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmebdfqv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgqzshx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2zeuzdsmw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdagpij.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2ergjooic.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvbjgrhz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2impwudyy.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2blvfsvvh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2idwcpbea.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucyrfvga.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2jdehnokc.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2zujvbqhg.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgecsdm.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ellbdstz.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2hyunjkyp.html


<!-- 参考信息 -->