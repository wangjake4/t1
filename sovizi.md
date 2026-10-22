代发 wailian999

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnukago.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2bxhttamp.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gloyecqy.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2detnoujl.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2iesviwne.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2exoixnak.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2irngjyra.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfobwdtt.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2begppscq.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vudmvxrz.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqwzetn.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2zniakqlv.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdhqmpr.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2lihlmktc.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2krmgbaam.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2aaqztotx.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtkwbvqb.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2fexfhehu.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2eavxzgyl.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdffkdz.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2epyvemvl.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2jzgzlrqb.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2edxcmdrt.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnlohalu.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyldidti.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2frsaffte.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yavtcvmd.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjrgltbb.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2psmjvycd.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2picndgwb.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2sqcgdmou.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2liyihayg.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2dpuxwvpa.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2czvvlbhi.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvvvvgb.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2qduindre.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhmqnww.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2idynwiek.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2chjadavz.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqijwwp.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2nronmulu.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jthkreuu.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2htrxgips.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrsmdwbk.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2bobscxss.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrbybobe.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2balcsauc.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixczocxh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hwrwvnbv.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2drhnmnwr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxnkryc.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwndnfp.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2soszncbn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfryqrd.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2evvazhuy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2indawhxm.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdujoda.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqwmnms.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xfyyjyhm.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqtintzz.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2siceukcx.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2hafzwpoe.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfpeqgu.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynkbipkc.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktkdjijg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2oimpiesr.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrnvmoo.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2fwsdklwr.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vospjibg.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2brhchzjz.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2cofudcyj.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxetkdby.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mevcymyu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyaomwqk.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmdooai.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqsumcu.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gjeyebua.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2qfnjfrxi.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2byzxnpdd.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hopfltgz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zkslojnf.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pjtxkguj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2jidcfzkb.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2zlqfulhj.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ttpeyjlj.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlopohyv.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxrzhujw.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcsyjln.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2mxaogsvd.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2xmzfrixx.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2vivnttoz.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2wmisovft.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwvqrxa.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2xsbtylzn.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2krzwrcef.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2xlgsegce.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2macjxmao.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2yychcppf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2okdkphfb.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmscmrgv.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xldhcslf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqfclakf.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekoxweau.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmlrxlji.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2aeitlpua.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2smfcumep.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvwtaki.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fljjpjuh.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2wygmhngg.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsraakaj.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhflrgo.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2civiamhc.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2dftjaelx.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2ezriogdo.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkgbdxg.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2jjerovyb.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tofbvmad.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzpdjwj.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2baaqethh.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2rycwudgg.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvjpcqr.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xghkdyyi.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjmedyx.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqbrgzr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtglmfkq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwikhxmb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2sagqtiez.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2jgncsvgb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oonhkuiz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvyhweys.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkeguvko.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2uamafbzh.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2rjopwstv.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2eceebbuk.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2llmcriig.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwruapg.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2idjomxxd.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2svttruak.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2jtpvvvbc.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2pcetakpj.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2tbbuipsd.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2qhusfgur.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2tvoflkmm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqpgiuy.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfmvjhf.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2irujuejk.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmebexen.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2ftstadem.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2lxzcoomn.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2fucnxxqf.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2gatszbon.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2bomoqvlq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2zyyonvog.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfwbuaf.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2drcmpfms.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqypvcz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmqkfck.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2hiuvxioj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bsragree.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2sfnuobji.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2bdlavocb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2izkyjive.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2csgebptn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxxdzxo.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jofsovgv.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2kpdlyifa.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqbvhyc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnxdilu.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2djkbixue.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2fggvqyey.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2mbscamjx.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2mgcbcgky.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2touuyple.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqrgnyho.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2atvzvoln.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2lcczvrsi.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxdfyaq.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rfvjhvys.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2whcfqimq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgyobmz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yigfkrcn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqdjqyn.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ahsfajpw.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ywkxgolr.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2onyvreyc.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhwzanxe.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjnitqc.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzaqemc.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2gescsuma.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpatfgs.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkzseyi.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ioykcobi.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwgqsie.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfvugcj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pykhsdab.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbcixwk.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2hukfhqaz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxxjazt.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2goyxzjqd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcydion.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2hogpiasl.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2knsxhmfp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2kvskevji.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2oljwjiai.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwtgibd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcgambj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrlsyqj.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2tbcqdaua.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjjsbyp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfloupqw.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzisdkoy.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pufjflax.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2imidwnlw.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqsvaaw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebupvzys.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhmunvd.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xnibpptu.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fveenjxa.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkercfgf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2plmagmiy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcblmgpi.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cajcpeky.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbbqqsud.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pokklmcg.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxbhvmgg.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uthassgz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbixsst.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrldxum.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2kdinjpya.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxzulik.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkftzszh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpckipwe.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhllwgev.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpyuunsm.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nsaqrcbv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrxchnh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2paxnnxps.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmwcdck.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrdhkxph.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2uomqejzx.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2zrmqygmn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2xqjbnkfv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvapxda.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nikuqzpl.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tskmzezk.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzsaxdi.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jbyeupiy.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgaswka.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2tfyvgiao.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2snfeklmp.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2thldfyna.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2egudhacc.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tuoukkge.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2alcdhggb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vobzypij.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkijzmbo.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwuryafp.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2udreekqp.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2djwincmv.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2bangxham.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnfhrutf.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rhyfvmsz.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2clfxgvbj.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2adcabvah.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqcgkbdh.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzinyvq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vxpcgtvq.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezopmmmc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjsgifj.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdaedrn.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2yggarlwh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2iufbblxf.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ouuknpcb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2payogcqr.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2poyhmmsg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2krqjdayl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjaxxphz.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqmmooz.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2tlyflkaz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhpfbyf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2skmmnthl.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlfrmlqo.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwesjzrt.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtjivrm.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwdtxwd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtlebtt.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnubzrd.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzqsqig.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2avrgvoap.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2smchukvm.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwllcdor.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwrbirr.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2bflkcchd.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnkddnsn.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zolygaab.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2xhcigyec.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlhrcuy.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2vaikrrpx.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2vlquybxf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxksooy.html


<!-- 参考信息 -->