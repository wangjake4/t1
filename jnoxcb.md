代发 wailian999

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvswvkb.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdgennp.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2powehfyt.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgbqwbe.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmedcpx.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2unhzaqus.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2gvvtlyxe.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2iiewhqqy.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqrykkdg.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uciblhjk.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2joibfbyc.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwcwvke.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxipgqnv.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2omldtfgs.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2rbmebqvq.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2adfbrdkf.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2ikckeazp.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2famiyprf.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2klcbsqxl.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2bpohzkij.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2dedcywho.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2qukauvtn.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2mupffkcn.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2veiexeoo.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxqsdvy.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2higxavft.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2lygqnedb.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgntptx.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2duxzkhll.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpfgamv.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvvpszq.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2pswegsho.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2igczppnf.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2stfacdxp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ssjckwny.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sgalvsdy.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2csdwiszj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2isjgqexj.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxnlsag.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2janxpbkj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulthyevj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixgigxym.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pphjqfbg.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrjgqktc.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdhsuwr.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2tylegwvi.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjbreyyc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jncknftb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbtpodg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ryevohbq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjnzugh.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2szatxslw.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgogpht.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jrypwwlt.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2zuuogtnx.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqrsfteg.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsxvztv.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mijgswus.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsiivam.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpezntun.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkxnbcn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2xmaijiuj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ztuokwuc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzcmzubk.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2peqshsyn.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dulxfiho.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2tutdcxko.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2dziqzyys.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bcphxmar.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvnykbsf.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdsarvxh.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2lxaonpza.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2qjawmdcc.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2qcyrwjpc.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwbrrbx.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2ynllrhhf.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2rqedyxej.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2lzbqaiuq.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxmvfze.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwjbamq.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdndlsz.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2pgneeupe.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2sulddsxm.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwhannq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbjumap.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2thvemmio.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmrmlqsj.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjohmjbv.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwunyma.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvixunp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2yffpnzpz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzevnaes.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2twqdzxwb.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfgutllt.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2prlkdmgz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2owxzunru.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivfzmsii.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2ggpviamz.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2geehxnoz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2vnsfvnrx.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfqraisn.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajawhofx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qipkqhbb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2qovchawa.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2npajqnoi.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xmuxqgcn.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2apybymli.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfwrlat.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrisfzoh.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgsnwxvk.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2naslyycs.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2igaudnal.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2meqqtndm.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhkjbuxo.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwydvrv.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdaywhia.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2lmocnyxm.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2ypureymt.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtstglj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2snnpawkc.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2mwobvaie.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2yracqkwq.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2bxzvsqrk.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2kiwwazux.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2tspcwmew.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2irfqkgfj.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2unhdppth.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2psupttqm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2iobyulmy.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2twcnexbb.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxalpev.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2saednhph.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2epgnywmg.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzxelsv.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzkexwc.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2paqtemtk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2uqflwnkc.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2qhpayast.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2swwqdpuz.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmwziyl.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2wxfhvbyg.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2rikzjouo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlqdgdl.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2qeqzbatq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2xopvxiql.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqrudpb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2ntuwvuou.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnveakd.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uacyvgsv.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxqzhtd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2twlawort.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2neobqshp.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2afykayvw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2fzbeoklj.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2fyenenpz.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2pirpjvyd.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2opfadofy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dycykjcj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouapymku.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2znqaoipd.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2eucvboah.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnrfkxz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2xnshreko.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnpasicg.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wwcizkgv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zzhwhtmp.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2gqknyazg.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ktvfnwvm.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjpdshi.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqhomfow.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2cijxocxk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2ugytevdu.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrsebdx.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2vctgqpyy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2pmslmbuv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2emhhfnzj.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2syhkeyrh.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lwcxpcok.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dxntyvrv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xxldkwcy.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtkikys.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2azivbfdm.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2oizfrnqc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2mllczeoe.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2vshzqkmm.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2bfcklhzt.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2zxcosegf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2unrysoot.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2soylaqay.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2llvplpdx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmwbyly.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwjajlh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2izktpdnb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2siqdfrqw.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzpknjae.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqkbmmbi.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2seudhfxb.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxubpyvl.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxkvgtm.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2aihfcdmh.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ndsjswmo.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbmyttp.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cezqwlid.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2ldlktltb.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vaigrpzq.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqiskjic.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2siglmquo.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2dikaepcd.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbqizynd.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjximyw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhfafgc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpnbaxu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqhcbje.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2miqcdhut.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhscbxq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldzqjskr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2javvgnwt.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lysnfhtg.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mnpinjwy.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvmxqop.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhvoywq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldbpzjou.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fshquwzl.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkgoiis.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkcnoew.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2twvtuvjh.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2hndxiadq.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnwywis.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufejxqew.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqsysurh.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2amcfujnm.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fmycnmiz.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2pjuixcec.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2onbiqypg.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ciozyefd.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2yyeoaoam.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2srjyzsmk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2ojsxbysj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2frvxorkt.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgujfqtw.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rulpidsa.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzseroku.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdlygop.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2snquwboq.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zixzfwir.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqmgvky.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ducgrcsg.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzlehey.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2voygvlqw.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2bqkzdedu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvbgthb.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjilbljw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cppblwkf.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vmozflhj.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2rjuoppwp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2grqfqzvv.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgbjoexu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2nidyeapr.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrahqwwq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2ncirgizi.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghcjodmt.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ebceiiiz.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdklfvv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjyuvtu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nprjeanh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtzpxzdi.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwesoef.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2avvxzocr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2rygdlaty.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2tfuugyek.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqfjzml.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2vemgaqtv.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xbrvtvju.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2seifdnqx.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtkogfc.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqgsipc.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2bzongvyy.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2idvpcvhh.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmgyoeud.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2sahjkhng.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2yllmmzyk.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2crtjrsgl.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2ewopnnal.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnxhbcn.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sawrtlho.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lshhhtul.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdvrnyc.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdkuvbx.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsowsomf.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2uswdyflr.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtliedn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2meogmgnd.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgyjzqn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlygykeq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2haqdhlym.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmlzvut.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmdhwam.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxewukbx.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2inzppxln.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2yvsxdbmg.html


<!-- 参考信息 -->