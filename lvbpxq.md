代发 wailian999

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lryyrdqq.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2knjaydyh.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2aeadhhpa.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2hmsixuii.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxfqzal.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2osfvhfkt.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mokcggxd.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2brtaoolv.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztphonnt.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2igkznsvb.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvzllge.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybyifxum.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqsfouf.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2foffuyqb.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2rirvmmpj.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2rswjllte.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yubnfsjx.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2usbmalal.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgolfwt.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pddheace.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpzsslu.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhzumxgs.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2ejdywpna.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2yilfofmv.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnnlnsf.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2irldarlj.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2nfaiqhru.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlneokd.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2tqabmjyg.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2blxtzvwn.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhmmipc.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjqadqm.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2lfcqmqpc.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqcjoeg.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxunkssm.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmydmvw.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnymxpru.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbecuin.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhsxxch.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2arbpshgu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fyimxzqc.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbyenue.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bnmzdsog.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzwjkhu.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvbiayn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2onmkxdxb.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkyyxlkw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2umeeebsk.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2soudepww.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbtsalsl.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sddenhsp.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqmpmfa.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gukkamld.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfsyjiy.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2puixmpzb.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rakyebsx.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2umdrvevf.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2vsyjkpxi.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dbfkmgkv.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2utnegxig.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqdoyrw.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvuogaa.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxeslzsw.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqeyxsa.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kroovuim.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgiydlc.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfnplrn.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2eprgcyro.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tzkycvdj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2zsexdmbp.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ttaaftcj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cduyygoe.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xnyhsqkn.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2buqggcoc.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2yuljjwhu.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2hicquhpd.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdyjrty.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpuuxesa.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2duqnnjqt.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbecmkq.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2obycaxtd.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2zwbniwbx.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfhjifr.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2lffutiqm.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2anxkbjju.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2xlkwwzrb.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqghbsj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpifavk.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmjgltj.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvdtzps.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbuinpuv.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2sipaeapx.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2hptqsfyu.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxncnlx.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtvevulw.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbhxwql.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2upsigfxm.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2uusaicgj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2tiruuwfb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqztuby.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxghrtm.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2txfkvofa.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfjxxzz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqwgfuf.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2suzwgymx.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2yonzgdxd.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2vcthaidm.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2fsribhro.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzztwird.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhudzvm.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vchppxrw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkmhlqu.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2idoxbdwc.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lezntvcb.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vteytasw.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qrssqxrp.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sftddlyy.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rifyrjka.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2shwwkfli.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvgiwdy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwmsmgk.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzzpxeuk.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfihveze.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2yufxbjmv.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkmulna.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtjgrwi.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2rspbzozx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2qblftxgc.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmbzzno.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2akmfrphg.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2gpiemeks.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2jsszwfbm.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2exxhlgmj.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpujidp.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2mqixaxib.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlaatgcs.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2shffkhyi.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2fabuskbz.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2noqvbrgt.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2lnqncyob.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2zdpybgzq.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksywmfca.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2ivptbqlk.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvzorbc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjbgahj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2huyrczvs.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2qhymsshp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2jecvmnmi.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2batxhydd.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2exnmjnib.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2temhfsqi.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2lulxvnrj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2urnuotxr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aeeeiwln.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2efjpphuu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfeksxmf.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjggyjtc.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmtaepg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2azxbsmdc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2imnnipse.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vlncgrdi.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2tkseopxf.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ysefcgrz.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtvmfnt.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwunosic.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbchzzj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2uscsovsy.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2zqokrwkr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2qpgzhpan.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2spsmrcgb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2fzqvzisx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhlrhcl.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ebspbkde.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dowewzql.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzimsnd.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2gvculidg.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmcnyeo.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkiwxfw.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2erobmuwt.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2xkanxpar.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2yhdtnhyj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzrxkmt.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2egnhvbmg.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwvqaoy.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2uxuohidl.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2milnquqv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mwaerkgu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vcultigy.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrogigz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdnbuia.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jjtxemoe.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2qygpggcm.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2mvgbcsqz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2wbphwkea.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2aejnxvwh.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2lycxkkuz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2hgokaoob.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxvnosh.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2dczwbldf.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2etsjzhto.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2vzsuwhrn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnkubuz.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihyysefq.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sngxvbar.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfidyczi.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmpgqeh.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfslyxpp.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yllksgvw.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ostxbvcc.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2apdyokyq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfihiyll.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2xfidmuel.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgozakxe.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2omjzxxtg.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkfzbex.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mckggfzk.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpomptgc.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mjsoyjce.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rawzfros.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocblpruw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2camwcroa.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcmgseq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzzjzkgb.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgdqyvxk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkfbyoem.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ficcelyv.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2loanbbgx.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2tooixorp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkybpxl.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2kthvjuji.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezvyjptj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2dywkrlgq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2mrzmjhed.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2lfaxrsqy.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdsvomda.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2owpdpslc.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcgowfiz.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojssvwvb.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zwitqygu.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2iqrxztlp.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2adgwuhzz.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2upgojmfy.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfyizch.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgcsjodp.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2aksxtxur.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2olrjbvbp.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tyoypcjs.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcxadab.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvnmanrr.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tpikaqim.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2tyxfwkhr.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwfdtvc.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2douboxsz.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bankpxqk.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gihkzjgu.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2anzxsokw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtptwgbv.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2obwcctgu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nyusytdf.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2tomjntjg.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhptqmgw.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqmtbho.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvxzthi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdbeucm.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwrqbdy.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2vpspyjsp.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzmlpire.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2mazpkwgk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzeephz.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxhlrzz.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2atjprhjf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2ffenhqqq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzkakrpf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqedabg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2xawvzdcb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2iopjgoyc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2qfazuqsd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2umyaqbje.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgplzegf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqumkoa.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jrchiyxs.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpfalvn.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgslmtqd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2uzszsvvm.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2whasideh.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmibwyze.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzdkvsnk.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ffolcvfz.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2lgrqkwtx.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2zsowqnhu.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2rpadedkz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcumzyek.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuilwpzg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhpcaxh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2ficcdwgo.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtfdons.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2skzvicpz.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgsqojcb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2anfjcrbq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ldzxghti.html


<!-- 参考信息 -->