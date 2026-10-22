代发 wailian999

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2uyeajyxa.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mirusyqp.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyixixlq.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oeglwbmo.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2yjezlpnh.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2knbylwlv.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcyibwiy.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lavpaiyu.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2glxlgkiw.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2urresgmu.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhvtbow.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhkszeg.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqyiyusb.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2geilfwju.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ncaexdsz.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2ogjhjcnb.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gonnmuky.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2pvsyfwmu.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2igtddzwu.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zohngvnq.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmrnrbw.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2ousynxyk.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhqaisq.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2chqchzpl.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2vwnuuxin.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvrftfg.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2inhkuvnu.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzjcamf.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssquqgvu.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmlvupk.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fggmclxs.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcpvcxl.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2skiskavw.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxbrtzv.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2axknkrjt.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2tdufgznx.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2bmvnebdh.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2xcztzkef.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2arsuzcip.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2dwdozues.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2bokoyeet.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvubsnr.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2hbimhdqb.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2hpkgaqky.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2aelecuae.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrzcjqm.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2opkfnftz.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyimvoeg.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyuhxlmm.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvvteja.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2hnpizfen.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2qasnovhw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgpgwpk.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwtkpgq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gqentqym.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bcesujss.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hasjiqba.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfixdqft.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpiuaob.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhaqihmx.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpoozig.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2awkvsexh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2erqvfbvl.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmifvoi.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfjrnri.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2okevdzsf.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmdxaid.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvevdich.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyamymzq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ymgbraze.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dtnixxaa.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhtfalm.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqpmhqm.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lqryecrp.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbopmgis.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2itlfomow.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bidkwprl.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gapajfpi.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujoedtzm.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2frfyzinc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnkrknn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2npkqpksz.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vtykosue.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgasjivm.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjamjue.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gnyitjly.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ctumadjl.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfrlcbl.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2odcmvhjg.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qiitrvet.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzgunzuq.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2avlnnmah.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2sgkwlkdj.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2olepcqhi.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2irhpoaty.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2rylvtmlc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfqcrkb.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjglfsh.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzrqywz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2lceqjlhe.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdbwini.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhwvnqr.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdnpymts.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhxtwcz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vowqzfif.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzwblii.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhlgrbei.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2wuyrrrvq.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2osicwwjd.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2elxrpzle.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulsrojpd.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2njwunuhq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2eymzypzt.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvvrklwu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhwgpew.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2pynvpesf.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxpwbvu.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2plnqyjsz.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2bnmgzcpl.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2vhghmkzf.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzuhjpt.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifsasbcy.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2haqwahaw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2ioioweys.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2befkgjxb.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xvsckcmu.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzuamul.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vqatqwom.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zithgaee.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2frkohvoz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfpzdbn.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2ligwhsmh.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qiyoelnj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2smagqzqu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzfbgohp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrodado.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2jxqdrgwp.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2zovmppkq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2roxtbtdv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxvnocj.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ctendrtl.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkrnxbj.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2xznaokcs.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2qbcilpkf.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2alooqojg.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ecpvmksl.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2rusulkbx.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2myplzrgq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ihadvdxm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2owelcgtp.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdsmmlee.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2aishzgzx.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2smhpreqo.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpvwgqc.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2effwnbkr.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2frshkamd.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2kriwjpik.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ethuedyq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2cquavsbx.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2qakhtyyr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2odewzgcl.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxdrqqd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lkduvago.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2fwalhskd.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qcjszycr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pijiobxn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2wplcxvll.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgwuahng.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfsrptx.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2zibbmgyp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2istbvhlo.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2davlvflt.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqhernt.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2qpndqwjf.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ukipicyk.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqdvbgz.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zujoytmb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqqwcnq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfyrcccz.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2qspvozxu.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzccnqb.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2chuvyzsh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdcerjj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbcpvoxu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlxbtki.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cmhrxigg.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2oraqozoc.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2dnonohvd.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2ltaqggnt.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2docsueeg.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2zxcrdqmn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2vijdjyfd.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2uorsdako.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2wcnpnqag.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2otpzypmo.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bkwrueya.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2czpcyndb.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnnzyzk.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vikkrjga.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpawevl.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2gnnebpkf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kuddkath.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2soffpvct.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxokypc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2qbstfaub.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqzkghu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzpueah.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2alnajjkz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrujjos.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2mjxtackx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2irwbnzjc.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2mgixgvdf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvvdzdz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2kogdmxkg.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnecvfry.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmctrkfy.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wspdcyto.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kclvfdxz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzwlevg.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qiemidfy.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vauxryuw.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxookdc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uefsuulr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2cbrvzmfp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2djsijuyq.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcftcwoq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfozhfor.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvmmihn.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrixbit.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjwslju.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpaudxbx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmrabhe.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjqbjjm.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmnqziu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ataekobr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmwctjv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2auvbasbq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2slmtpgfd.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2shfofefn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2scalinxy.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2shjeymvy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhraaopc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrkwjzwk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgakxah.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2wtuqrojf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ueofmwwt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgfhgky.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nicoihsi.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxbrdci.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxbfyxz.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2euveuuzc.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rzygudza.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2uafkrtpk.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwngqmw.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ndtldzha.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2gapxdtmh.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2icresbou.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2pwfuxjrr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqubpfm.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2aprbguzc.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxsdisx.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2psonfpnl.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2wrvbgfgu.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2jpsnxqiz.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxibrren.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vlujlscw.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxdwsqm.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqnijyx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcselgcr.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdnfnbn.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbmmwer.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqxbdko.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rygpqncs.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jgdchefa.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2ryxtazak.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2leuyytrv.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhenosk.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2kjroyxfk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwsbdgh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpbdxro.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcoaedzk.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2eyncnmbr.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtmwzmi.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2veydmjlu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlsorbpb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpaaujk.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2tigamtht.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2kojdivfz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxgvdqm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvhfmqr.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqyqtjr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ifgbrkmq.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ojhezhvw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2pomcowvl.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfqxomj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2lkuticwn.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2aafwbaph.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjacpkph.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xntpjqkp.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2iglembbc.html


<!-- 参考信息 -->