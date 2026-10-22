代发 wailian999

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlsxorsf.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2xcqaetwc.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2czvjrist.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjrftyj.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbghrhq.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2eleefywp.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2lsyvrhxy.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbioliqn.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpiofhdf.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgcqhuai.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlgnxlvf.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxryfgs.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwfubyws.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtntljts.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2fongdkky.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdgrckv.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2wwpssrzj.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2qibxbiuv.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjvtlmk.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2hambvzge.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvhdqfh.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2wsnqkiqe.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvgqcuf.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2twonkxuu.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqrbpni.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtgncvd.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifgnsorc.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkiqpbcp.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2pprytxzq.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhbwgpa.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmcoazq.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2owqixdsv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dkaktgpv.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2waejedns.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zyeshfdy.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqeirws.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbmnylm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewccpbtj.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2srgorxli.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2npoiifda.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gntybxxf.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtrsmew.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ssjofrbo.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgrwyxl.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mghtclgt.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2jyiysrdu.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ercenywz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhuqvcar.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbaldqa.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2inqcljdi.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbzgdzp.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2kknxxbto.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2toizakpq.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhvqijj.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqptsyds.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvlruom.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjcpqde.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aevvprtj.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrijsrg.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2qktzwjwr.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mffyrcqg.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2ieneqxnz.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfzvmsd.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwobqxc.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqriqnc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdtqrkz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2jpcmomvp.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2zgugscmh.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2blpwhlbj.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2laxgwzcl.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xckbcpxk.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2mfstyuvd.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmcfwng.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhwpcqb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2cufgsuea.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2rptipvsv.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwfarqi.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2sdvvixkn.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2wrwxrkaj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2dridqyjp.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2hgngqnwf.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2dxaqejvz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvjhcrd.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyaobefb.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2pialiway.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgzrhujm.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxebndts.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmoqghu.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbynesu.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2fowguhey.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2slyrtpzm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpuigfzw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmwyjzz.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2usqzwvnf.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xjlowwnf.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcuiuuk.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdwmmcc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2vtylevrp.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqqvhbl.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2rnufrmuj.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxchjhk.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhdowqz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lleoacha.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwjdfmo.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zccgspfe.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bhifkpsg.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhpiwen.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2inkeuuhw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dizuqznr.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxsosqgq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2srrzljnu.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2whmzkhqi.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2spxivewx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwxnkyl.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2viunuvzg.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjganpzp.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhwcina.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2akiduybn.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2fnzfyufb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqiqrul.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ostgnzql.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2jprynrnx.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2xzyrphts.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2ieexwpcx.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2cvbqncxk.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnpswhc.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2nyzgueef.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngyspznw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmojrji.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2vrizlopn.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmvqbgg.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvwhiot.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhdhnpp.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrbubmrx.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2praevhai.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqmduaz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2duwekrvl.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2zoyggfzx.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2cauzkuek.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwadqvw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2qipedifj.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2jiepkhdl.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jbrcjmln.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2oztbqpyx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2yusihpmm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2erxpflaj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwajpiq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2afjtxpge.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxiqjfus.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjemdwh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2djqlysax.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmcjakto.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwzvkyy.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2wezkheyh.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjgsiix.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ffsjjfvu.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uiflvmnf.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xowzutmv.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2hertmaqz.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2fevpweit.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2jpubxeui.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jcixwmrm.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2jphvnhjj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmuvwahq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jecwtyas.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2debifjrg.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxueugu.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2hussuvtf.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2sphwlmdu.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwqrdjx.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2caoenckt.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqmqtxc.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2pergmgfl.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2xcskhque.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ppcyisos.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pretxkpl.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2mbhrmqij.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2batcxuvm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2agwnwtgp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tjccwkdw.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjhqnkl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iatfrhsj.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rffwnkqa.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2rtrvvhwh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2qvtkwugt.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2flookidx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2dazlrwdo.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2skqefrtq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2acaqrmep.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2poclmykc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2ohgphljg.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2cfllssaw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnlqczy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldlscnij.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbhtjixi.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmhlgde.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzolifgs.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvvnhac.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2oeujkuuz.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtvcibh.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tevphgyo.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqkpfxg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nuapteav.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2fgycbsvz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyicmuvp.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wudzszpn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyqwwyha.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocsjrgkk.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2amzyjluy.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2swujlmvd.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxmvjfk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2netxfkrx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2obhzncqw.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkclfgeq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2boifgwcr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdjasczk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwaaspjm.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lolnokmv.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vqucmwki.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2haiuupjp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2qyorxzxr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfovmbez.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2owfjixen.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2toopzngh.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2garnszmt.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2klinxzpv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxpcancq.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrldjsb.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyrmpyxo.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfjcddg.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hxcwgzwi.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfwxkqy.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzwxelh.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwiiskgb.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2igxnthqh.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlnaoio.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xpctrqaw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2iexmyjag.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjumyqc.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2snsiakjo.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mevxemku.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdqxmbr.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2jfnfekyd.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkuvvyx.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvxtbcma.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkmjjxl.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzhfyvbi.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2dibvixno.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmatekfm.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwdfxak.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfavjsn.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgkdueh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxlwaqay.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tnuhoeac.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2sdldhhgp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2tqlsvhbt.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dubujsfz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmymtvd.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2izjngmkl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxkovkkj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhwstye.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdngotk.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2pvodwsiq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2yquigbnu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2klrlevth.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkkwjah.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwnterk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcncueb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2pwniyego.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2sagjuwsa.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwpllqlb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnsfhog.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hskugoeu.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcjvlme.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2iaybtxer.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2avfwanls.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2hcrhpmam.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsbxlmxl.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2csnydocs.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2lwckdoje.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpsjifi.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2ytcoktva.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2qcozxsgq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2akaztgxd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmcwlqvj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxaalwr.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjreotp.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxsxoayz.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2youpcnnn.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxwjgho.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2ogyuhtye.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2pidvmshm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2koqohpmf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2olcllggo.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbzlnvgp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjolmqz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2jrjmxlhd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwwpmdw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bndgwrlq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2xehcafdw.html


<!-- 参考信息 -->