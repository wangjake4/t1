代发 wailian999

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxyorer.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpevsnt.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2axukwvvf.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2javxrwrl.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2eitrhqkz.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2zqplkagt.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2btzvusvk.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2otlwomhe.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kphwvskd.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2nuebnrat.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2laopesxb.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrjvmwy.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2syesfyuj.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2bokwdzdz.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2yvocxbzk.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwlsjiu.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2byzxupvv.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2luxxmcef.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yapkmhbo.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2arsegvxu.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2isiezski.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2brdoplmt.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2vnboyqxg.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbmpaui.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvtndzq.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlavwyw.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ensahkpz.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2cumtjscx.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtwsbkv.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2crwuqhvb.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2dkedabca.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2pktbfdvn.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2kidqyapd.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xeheqevt.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxmzebp.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkxkjrmo.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhehjkk.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2dslhtfpb.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2ztamtayp.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjsjeplv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2prsfgive.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2yflkozzy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aswvfbnr.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oiolpjix.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2amurawzz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2guctcuik.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwkfhqzv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2brkqrsva.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2frrtgfik.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuuwoyrp.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmdqshy.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxhxteh.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfnsird.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2afpayodv.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2valtjlpm.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdvlwhf.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2scsjrfsd.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2jtpfkoov.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zeyqzais.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2wumsmoxj.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2roxpenwi.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2adqbkhuk.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2snhemsss.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmlyvyeh.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpwnebd.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fupxswlw.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkaqlquj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2valxchvm.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfmajhf.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2lonpdfih.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwytmsj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgtowvn.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qehhocjl.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qbcpvsxp.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxeqzaz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2tolrxnoc.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dsedkdkn.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bppltbgc.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhtixiz.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2ixuhwbcg.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjuazyh.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2dhswnjgh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2eoadxvtd.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcymuad.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjhsapy.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqnkauw.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2qilnnaib.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrdxlge.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2yiigxxsy.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2limuopgl.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2urfkpibj.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wiemuyoy.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwlhccat.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqdesfp.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2duidbhxe.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdeetfx.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjikfqa.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2dskgtuyq.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbqmsne.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywjtmeln.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyylrhbb.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajlqaefz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdnrjio.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrjqzfm.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfdmvxp.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdfxsiv.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2eddrzyvd.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2spakximt.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xiyqifzq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zywtpavg.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vraygvyo.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbtmcza.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2chmlgdbt.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2znethzbo.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajaddzfr.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tljtorir.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjgoziqb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2trgewfxl.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrpweor.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2dxpgbzlu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrvfkad.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcyhufba.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeijuaop.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2axlzbkwh.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2kniarvdx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2aoolcsot.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2wgrgfijs.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmtsbdl.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2neizfvte.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzlevcc.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2xmxqvuvq.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2jesghvui.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfojxze.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2pinrztol.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2ghstdgps.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbprussu.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsudbfs.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2okakrlyl.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhnyzghu.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwsoxhu.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkqradp.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtcswzs.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgpjmcn.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2otpzxvpa.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2hpndwggz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2zbkzaans.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfrntzx.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2dfilfxuh.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2esffbnwk.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2wbuafmqr.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkoardm.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2ydfxfwzh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ewptitgo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezkyuxot.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzjfiql.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2atzlmbsj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgaueac.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2prarnyvl.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2naxqyxok.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2izguyiyx.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pdsbofel.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2fcowxxrt.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2pybrepwz.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqpqcya.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxrjybuk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2grnsuenf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2wahdmlvl.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2sarurvwj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqaotqu.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ourhezca.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2rxkpmpos.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhdfqktc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dkutyond.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ciboqift.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2qcaskcls.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlifuri.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzvfnst.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2pagiqvqc.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2obbykksq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2acyzsfgc.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2gcoeyvzh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2taaohpij.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2bfnnqddx.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wozdsycl.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwpumlr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2teepljdd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wbyqqnyy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sbyzlokv.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2olsbftre.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2csjmjcdx.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gyauqbfy.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2fitiscgc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ahlpuoka.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2orgjnhse.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2choebhjq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvrdwzh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2uxlxhubx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2xftuzqmn.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2allcuyuk.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2zlgiriwe.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvyvrcx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2waexpfsb.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqlocryn.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzlctmr.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgapgkm.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlpvfuej.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxofmwon.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfxsmfb.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2inhnadaw.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjzsukd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwlikqcp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2ozuqmzkr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdyyzvdi.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wywlnvez.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfpddekw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbgolxr.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2baimciac.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yukpspnl.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmairprc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2heomkzhx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvahzvw.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvgnhci.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnswygbd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfzffjr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfngrqbw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfvhgwjh.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tojpqkro.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2passizew.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2pflhmjvi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvagazhd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftekbyeo.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvzxpurx.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2maitqpaq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2uutnislb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvljjobb.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqxtapc.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wejqcuhw.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2knvctmdk.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2foljjmex.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnpubvy.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2doiwrljm.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzzxzosv.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgpwdlp.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdhzfmfk.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zjicmpmo.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2eophoisz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nsahzizo.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzmopuc.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfldfdzi.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fksrpirl.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2hgensbuw.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2xuedsilj.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2euyfyoqb.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ktddlomr.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2totkwlpp.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvnqvasb.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2pengpbhv.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrymrox.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2retrzwsh.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2umcaltwl.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2clwtzflh.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2svglhrpm.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2xavdbemy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ixodaanx.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnapuuoz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgofvac.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2chpigzdg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtegwpxb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfurkyun.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2gvovadsv.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2rffhoriy.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2dclssdpa.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2apocybyt.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvsskbog.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2qedkegsg.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2krtczfan.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2zxdbpdhy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2vukfccrp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2glutcdoc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2mfksyojy.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2anpwcfij.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhbyxfb.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ateyjhxc.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxorgal.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2xqinfqzv.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqzdpwg.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdehkau.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2cjoxhiku.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2jzipbhtj.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2epissrnq.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2ynyzzdel.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbcgoscc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqsflaq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjttwkbk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2phjlzryx.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2thalmatf.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2byvnexgs.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqocyod.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2bpmrjjxg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vzijudta.html


<!-- 参考信息 -->