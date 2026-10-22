代发 wailian999

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryydmfma.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvzpual.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymmydsqp.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rxymurgj.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2ztlcqird.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2lfedfnwo.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfooltz.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jqqouxmn.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2dffyxxds.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2dcztxnbr.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2axetqshd.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbogxyen.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxnznbw.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iufossey.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2wyrrjngh.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2nvysudsl.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhhczga.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2fdxrjxoj.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtyslcfi.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vioqmczv.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zykayuak.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2uqukdsuj.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2zehulopu.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjdyvru.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqnwtez.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2isworaok.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2ciljcjiu.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2akzezxii.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqfswbj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2npohdlfd.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmncytd.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tiyztwfc.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2itvkdugv.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wryahjzu.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrzajmf.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2uuazuozf.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2nisvamfm.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2vjnehgbr.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjjlalz.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2vycaowoi.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2yhamvufh.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxcmlit.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwquphl.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2hzcrjpyg.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2rlixtutp.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrfvdgcb.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2szqhnwes.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajpqedce.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzknehk.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2awfdketv.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2kwrqzjxe.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdwjhft.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvawpww.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2nareskmd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vdudxfxa.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gbxzipav.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2wdjsqvmb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rldqtitj.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqaxpol.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xobnsqvi.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxvassmp.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfiddec.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xceltkik.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctntdsan.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ffsopuqd.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpylary.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhlroid.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2filkpfru.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhedqoy.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2uhemborb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vnpisiak.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2ednfohbg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmxeqelu.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fyedtyhj.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2oycjsuhj.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcuwtuue.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcapkoiy.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oeaqyjds.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbmceki.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcqwcmz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wttkhwez.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2pxamsjtc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgetjyf.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhyyeqpq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kbpxdbuk.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsmzrmk.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2sshbosys.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxvumys.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gjrlpsoj.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmbjbzy.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uijxlkyx.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmaaqel.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqzehct.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2cbysnqru.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqxngyg.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtwyhgz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvkthgj.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzyglld.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxptcim.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2dntgokgx.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2aidqsfjd.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2heoajqgh.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2elafzzbf.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2kitijmlw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2kammaxxb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nterdhim.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxxlufx.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkkygdw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjonbdp.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2rxeciejz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2uddshtqc.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzfjmspi.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwylgrd.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsybdcuv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2czamppzb.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjgezax.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2epuxerjp.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvtssbj.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2eyntbwki.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzhdnkp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vctwqods.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2setatqco.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbfaxcii.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwdanoi.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbsrrbx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjmfhfv.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dofbayel.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bubjimcl.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfighkw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2scqlyrpd.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2skwrghon.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2kttleqfi.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wikiqmyf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxfgsjbh.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzcecejg.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcfqhdy.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2dcndsoyi.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2qcigoprw.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgarrdz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkdfxzo.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2wnolwbob.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2sqogwfwu.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ztegxyeg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2hnuktfxz.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2nfsdihau.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2tqaojxyj.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmvuqky.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmbblcr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxriwpl.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdjuevb.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2kilvbpwe.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2ftocbcsd.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2aaibrgfs.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2cissrcwx.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2fcddcztn.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2dttftevw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2bdlkhtwd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrpbaem.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjvzfsj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2dikyhajo.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2fzbpvoay.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2yviswqdy.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rnattkab.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2hgxqnsup.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ofiggelg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2btxudmuk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2jaefhnjb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrcxbaq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvldzfts.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2gczrnjal.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqkzxws.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhfgmvl.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2slzusaie.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2smlkyeit.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxqjtch.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2eiehfsgq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oepyxamb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjtahsax.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzremxo.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2rduklwnx.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2tbawrwvc.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sscrkdwu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2nqviwmmw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2htcknrbj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lmocworx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yudtztnf.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2zqifpupl.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2izbgxaml.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2sevzowak.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2eflrthdg.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2owolaijt.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2iojabdlx.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2jptkdhsz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxiykev.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2pxsmgewx.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2msudsgdi.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2zyuxaibd.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjqfahh.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ewgupibz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2derdggso.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2zvynzkpc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jojewczf.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dlctnzrm.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2kpeapjar.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2nbnsszrf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2urimdigo.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgpffze.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwxbhbd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2oephqlsn.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2iklzaeoi.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2ahlhhvju.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2jigfpajq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbtczmm.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfawcdcq.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2umzaioen.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2snixrhve.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdsmglcz.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrdhgwl.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2kffxjnah.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydaqizuv.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2oesikvjh.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrshaluz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ziunnzui.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2dggkymwe.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrphqnme.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzsrksmk.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlpyawkp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2yitxjejs.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxloynqp.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtpnkdb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjbduikh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2prdwyhni.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfetbmr.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cibduuce.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrwumwce.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2exdkzhcv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfpqkoo.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gattnkyi.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqyehha.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgfxppg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfanjjpc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2nupryole.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2aksdnbpl.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2jorxbtfq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2abgqazdx.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2oupvdwuo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxtemfp.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yoejespm.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ducpjyqf.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2szhtuppj.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2barfpmnb.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2oookvanu.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2dncwwoyh.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvevkmk.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2yoipwiqm.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2admpeoqt.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2gmlabjio.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2bwoeajkr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtxvzuz.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qscbmxae.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlzptsg.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2djhhhqyp.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2xcwgaeug.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2fsshodhl.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjbujzx.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2szcggucu.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhxccjo.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvpxdkiv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ssupdrax.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2dqorpmkx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wubwxxsw.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2osrkdczr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tinnavhh.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fomxgdxi.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjxrsym.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2puzknfaw.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2almcnonx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvlbxra.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqjcowe.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2swfppzmo.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lilaktck.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2botmdoxd.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2jziukmjp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2rhgplkro.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dabezkpq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzoiskjy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2osoggfbq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtyafgrw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2htctqvpg.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2nblxrbng.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvfqrbj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2smvrfwri.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdpcmog.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2xqlpjzyh.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2subdqztf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpktrfj.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvlbcgh.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2tosbcfld.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxvfqfb.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2jxaljffs.html


<!-- 参考信息 -->