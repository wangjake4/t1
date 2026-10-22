代发 wailian999

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxtllgp.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkidmvyh.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrbqneyg.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mbukegpo.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2anljatkf.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhuuozr.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fabujlqg.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pduzafrr.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvambup.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2qnimawyr.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngyqbhxs.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbznzyil.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzeqayw.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwknfmb.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ulczkxqt.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmwchtj.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bxyzcliu.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2zepevlpu.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvqpwwj.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2savgbdek.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvdokif.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkoqmcw.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2iztxmtum.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqaahmb.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2zjlezezf.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwlazsa.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2fafqhwal.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdblluve.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2auhubvks.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2viqdmllr.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwnukam.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwkifzne.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjfsagm.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhxizcg.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2mtwmsyio.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2umkhddaj.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2orntpwsf.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2lzafxtwa.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvolxzf.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmjhwkm.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2nygpcpry.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqgkati.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2mdfomwqz.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhljtem.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2vaecwkgz.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xoeniudf.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2kscqbdzp.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkaymajp.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwgqhbu.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2icztlbuy.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2ifixlkpv.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2egjzmpho.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yysuyslm.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2oostrwle.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjmades.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwhgivb.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdzsgom.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2reaneulc.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljdvhqwv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpkewkv.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjsrcptu.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhukhhru.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xppykeip.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uoufysju.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2evvhxrcf.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwpcilt.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpddxrla.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwmmbfd.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2goqwkvzj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2iuuvzcvu.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2blsnovzr.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2ajebkvuy.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujysybun.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkcxpdr.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ednxudar.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkehngdr.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzpkaix.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuctkucs.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjudbljv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2jurrwdzl.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxwrttu.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzfiinf.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzzeacv.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzatgcd.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nwnfpcuq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2snkxlhcx.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ejyrfofd.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvtgyvy.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2giqrmnek.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrlonmbq.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aemjfksl.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2efywtlbs.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2fozdvimo.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhrhlwe.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2trwpyyun.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2clfmtvdt.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2wobdfood.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2phdnqhns.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzmjtwi.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2envejbpj.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlpbvpr.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2emswlbis.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mntkdvgo.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdhzhjt.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xypnvcuq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2neulzihm.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfpumfao.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2oikvaetr.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2kuccutfd.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpnrqfz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqrqbads.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2osvsdnht.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2smmajvaj.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2zndaiqro.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqafncx.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2wqdozfjj.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlifbht.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjzwbqv.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2fwguxiuv.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2cygqflww.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufozldsy.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgpuiwv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxdjitin.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzllmne.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzyeoxys.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2agseroul.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtxxeuj.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmnznuk.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnyjbueg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqdyzqtf.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2nnsitiip.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2gndtehtu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2upaedgbe.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2scyrcqni.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bouylwyx.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwuttuy.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2akzszack.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2saecbpfy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2aawppiwe.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzagnhz.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrfjulo.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2btmmmtlh.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzvqqtl.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmvnybp.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ldveuebw.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2wfmzekem.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjzclpt.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuojfpfn.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwqokev.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2tackuiwu.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxpneev.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2afrjnjdb.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2xwgxxrxj.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2zuslplrc.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2jyyexccg.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkifzzw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2fxneqqiw.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2tpfwqndy.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2axqcesrk.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkyovkj.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2drjfchrz.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdcqzyb.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oplwqxvp.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2jocbdgpd.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2dywzykcc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkwdwtk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2clzduejr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojrsbnsg.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfergspi.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdvvwhv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2bokjthcm.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2rucxlcfw.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjsidrl.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2gnesnvij.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2chpmjipw.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2vhcygxqc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2chhuiorl.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2auciyoul.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqtbnbc.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkywasr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2doildlcf.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2krpythth.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2eexdacrm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgwkgppu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uztsgyjl.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2czyxcbpe.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2mymxygog.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2gtbvllje.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2slevumze.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtxzslo.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2mwaxgwrn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2inqlnpex.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2ozaalhgh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvmweqk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2unowhocy.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2isnpipiw.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvlcsdm.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzcislm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbnazqk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zqyavnsf.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrnpvpr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zagktdzq.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tiquclbx.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2fdrkmzgz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2wcdzusvq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2cccgpayn.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2wwtasbbk.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2wezfdrls.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2gnesfopt.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2lfusfvia.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtnzseb.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ntflvdlb.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2bmxjdwen.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgwabzct.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkcbqcys.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yeszkfcc.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgcaorh.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcxcwluq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2kifhrmgh.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzfldzx.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtxysym.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2uohjkhcn.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pyppgvry.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2jfohddro.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvovguyl.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsziypsh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxsyicof.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgkdscga.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nocjzvfk.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ktgkvbvu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqonuwhu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjieuzdx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2bzaheqpq.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2exkdrbak.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tikhrquz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2sryvhrkm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwupipdg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2owkoyqyf.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2agevaqtp.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2dnztfuns.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmdazwr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtylogm.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mafdiayo.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbkpncix.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2cyypgbnx.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2asyrbvro.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxoutbr.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nolpqktn.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqljebzv.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lharyvkp.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxmqrui.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qiyravhc.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdovoar.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkquzgmt.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ervrfblw.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojibqfcg.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgqctxf.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2pamvrxoh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bitltgdr.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhucwdzm.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqgptchi.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozllkzpz.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqllkzi.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfotxio.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbvupjo.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kkssetfy.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwxysfr.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdhspxdb.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmrtfql.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2xlyswryy.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cikovtvw.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2peboctlx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tenumjwy.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrpqgoq.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2bsuopkpl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwzmort.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjldpkay.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2eojldypv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2osrrpqxw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2pyspuptg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbgfxqzs.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2uwpmswgb.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdubzey.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmjumds.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2omqankcy.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgogrxlp.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2jstefqae.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmsforps.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2jwyqppqr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2hzupjzge.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhecogjs.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2immjlhpc.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2cikqquqp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2xnaooyxn.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwngymr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpsbzko.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2aukteujn.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjtsdvz.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fffbeicq.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2yygaltbx.html


<!-- 参考信息 -->