代发 wailian999

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2idccfxkc.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2aasmwepb.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2snxxyoau.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzyynar.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmyfgjy.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2lhgynbgi.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2uetjawyr.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfxalra.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2sglknrlv.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2iaewoayr.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfjonzty.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2osrnxjyo.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2naxkdtne.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2plcqfiol.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2hqrzzmut.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2wmiadsrv.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gwcdwqwt.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2tiloishu.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuftxzly.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzhsloni.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmdbtzqq.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbpuhix.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgrojagb.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjiqqjs.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2rgzdhsrm.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2vpheaqbp.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzoqxoo.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqeuqri.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mozflpze.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vphmcofb.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkuzpydd.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kraihrkx.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2afbvrimg.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gizrfvjm.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2czbjgvht.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqyjnrz.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2ullhhykr.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2dqajwniz.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2vujndodw.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2fitmgfel.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2jiywfixc.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhuhslm.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2mgwptmts.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrhizym.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2ozuwqncy.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjhaajes.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbyefetw.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgmvuzaa.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtudrmbq.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjyjguk.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2irvpzitm.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpcyzpst.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xuyrdcno.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjqzxuo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2grolvjzu.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbqjdqp.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2vgkftwuq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbykhjq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwolkbk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2geqsqotx.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2earhpypq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqumjtwh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oszukajy.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxgqsup.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rohgmmqx.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2bmgitbwr.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfkcgxj.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjqchxrb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhacqpo.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ogdftjey.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2klpvrnig.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2hltanmpa.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2skdltenx.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fdrdnuap.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpbxkvqg.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmawafa.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqjizqt.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2toyuuane.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezvdhkyf.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcbdydu.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ydyctoit.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2aqifwyrz.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtpzsro.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qunaaufo.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2easjanaw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ebrtmrec.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcapnmm.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2bkytxsip.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wdejgpxe.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtdhejx.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfukpul.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2nbykcwse.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjsmyin.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2oglxnvxo.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2xvcjqcdf.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2rzwwdyih.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2qkmgwuoc.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxwjceq.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2tompqxjn.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmgsuws.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2srvwpzpg.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2ntyhmxhr.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2rawbbvgd.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxmcqkl.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2quyetzsa.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzawaxlo.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2toxbyomk.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2najvwjrv.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdyisav.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2emailsdu.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbovrmh.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfafcwhv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2gylpigzc.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhndnqdl.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tdlfmpyx.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2pjttziun.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdoqcyl.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2udfphzzt.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbvolbe.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtjttjs.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nywetyjj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzcahsq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2etnhxpha.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2tlssaszt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubattxaa.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2diehgknx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2anhoyfky.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jspwbwhf.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdkzybr.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kntcdnvq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2bdzdbjvu.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjwjpfo.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyuxvyvm.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfpsbpd.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2niuqsgnv.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqitbwyq.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2abzmyaxw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2rylxrkcf.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2iensuckl.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxjukbh.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2giftkgtw.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2iblyhhaf.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2yaaryinj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2xumfwakn.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2hznhvaly.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2kwaguhzr.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2fcnjtmpc.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhfskqh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnvevwf.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2bagfqmbk.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2eoyrzjnl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2elmycyej.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2bylhueyi.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctpnkpht.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2fhcqufst.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2fvbmialc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2vcugvscu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2cshrnvtl.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2qclpatpp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvroubu.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2ksisdivy.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2mnffirzh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwgmwwj.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2imiurrgs.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2xgyikgtm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghtjpqra.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdzkvmo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhjdprm.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oipboxvn.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqnrxtb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2aomwjlex.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2bghptpns.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2phwohted.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgiyftq.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbmtvbn.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ycuqpahj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2farydnns.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmqxcpp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbptdzfn.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ynoubrfp.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2zoyygbtt.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2viwsflod.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2zphgnyok.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkyptpzy.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oezrvqqk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jratphwe.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2azcovjvs.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2iaktvfub.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnhmbfm.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2adjrvoyd.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2wraxbytx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvklmzw.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqohybl.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2fakixiow.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbkqcoi.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2umhslqfg.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2ahymrmum.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kgpfueyz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bpkfdohd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2shrbweyu.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhaaydr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhwnuct.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2irfbpilf.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbaqgfy.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2tquivjvn.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmrrofp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2xqjlvtfg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnnjwoj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhkohgz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2xijxhtdb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvdnplg.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2wekasxvv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmmnpid.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdkyfrbd.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrqwhue.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmeczer.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgcoypdu.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebrrinsy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2vecqjyju.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfgxtof.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ymehtsmr.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2etzzswhx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypyfjypj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2clvlvznt.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxbxdry.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2osgzcidw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtnxsvj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrkxgiwa.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqairuyf.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2iowxuszy.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwivnom.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfgvlvqm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrvjunp.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2uircardf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqtpdcjz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwlbffo.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qokprbnp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdrsuulp.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nokqkfuf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2lixhauxg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkjymcgf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2bargsifv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jacntqih.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrcwurgs.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2whgwiwsj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2thsxdsqz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfocwosz.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmabbyl.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfhmhru.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmigbdiw.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dwndmdwl.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wydslmqu.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtiwyar.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvdqsawl.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxzxwgd.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2pllnpmki.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqyhkub.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfxsmmb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgiypxyt.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvutdamy.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2eetipfyw.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdxmomr.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2cgztmlqs.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2bylatlzn.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpfjsje.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2sczwlzom.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2itscuxsk.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2crfpgyqq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsaofpl.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvjxlnx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjljond.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqlsibue.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjhwipb.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2efkzifhs.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2xwkxuqmi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2quaqbczs.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2oymomxem.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2etupvykv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2viyahret.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2oespdzpx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylzywviv.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmhrjpb.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2oirqknqe.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2zufyjanp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqzhuvz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqmelvgp.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2vddqyozw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2eofkmpqk.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpjlqxx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtucyjn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvwskom.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2kywxvesq.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mlfbsbon.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvfdcpf.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpnzsini.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgjvxfk.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2mrznmype.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvyyojoz.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbyslqm.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2qytplskr.html


<!-- 参考信息 -->