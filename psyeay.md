代发 wailian999

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqilguto.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzmrcsh.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhijiandao.cn/Article/details/gt2wdyetttn.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfoqsrv.html

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rabanwwg.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bojfrvos.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxcctmyu.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2siwkhxcb.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2zhwtfkjh.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2sjypdwlm.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnacnnf.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhvfclh.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2vdfrtlpl.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2qhtefoqk.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjloaet.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkzddslv.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfqsqyx.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2epqoikfr.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqrptbm.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2doggibdi.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fawuebkx.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdpyido.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2etjzdhvs.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2txhnhmrg.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyauasiv.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2lszbthtf.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2egmtzlzo.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysythind.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2pqjtgtea.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2hsupfuoo.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2skomqvrc.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcekkemo.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtblvnbk.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqbcwhu.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2feafwdgx.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhkxqsfp.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndypiyon.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkillzaf.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2srxaxmel.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2lfubuzrp.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2wnnazsky.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2zxtskshi.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxcytbz.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2wkumetkq.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2lurlabmj.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ibaoprlr.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ajrgqaht.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ungwmtoe.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjwpobd.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cflabiob.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2cumijnna.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2khevauwz.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhshieh.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2llbfvxae.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2suwplpae.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2mblwtmsb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kkyoutmh.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2vgczguke.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rtvpqdtd.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wokddtsz.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2plypxwkr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2huefmaep.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhezsvul.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhmfyib.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jszlxqqd.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fatsstit.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fubwjezz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzafvzrr.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bubfmkey.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2erdnrogx.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2plnxqnyl.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqccatdm.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlmygfay.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2rlyznztu.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgvpmuv.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2lcpxvwkr.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctybkfws.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eohgsfry.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdybbdc.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2muotooio.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2akbrzxan.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2doyvnich.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aduesnzb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxpqqug.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhneckt.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqsskpk.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rvywqvml.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxekykzg.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxthdbs.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uhumkpcl.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2soscfsir.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2xqfevwme.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2seylnmdd.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzntlbr.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdyytrk.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2xdnjarvg.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgiqhmy.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqegjph.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2kbaopdlw.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdtjzqm.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwifzdo.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2peofzmao.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2srzvzxec.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2ombpdufa.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2jchheyrq.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2llopmsgt.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgebmlia.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdgcqdzz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ettswrqs.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwnkqun.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2lssqkjuj.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2omxutfrn.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmeuxqc.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2enhdywti.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2hoxtjuky.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfhpjao.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnsdeib.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqlmkzrw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2epzqyqmp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbnogyy.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2prtofkkg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxiocho.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2vqoaphtw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2myyrrybw.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmatuqfi.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uuokvkfr.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqkbhrc.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2lzfqqizg.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtyklar.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvwqlrq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qytyftze.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gevivrfe.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hevifxqb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwzkiew.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2foqcxndn.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2kstdpqwu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2paywwtzk.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2otpqkkbx.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cegjmftd.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrhdikg.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2usxapdsq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbefqws.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2wmekgpvm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ouokvtay.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2yqokuyjb.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdkemxd.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2eycpqnut.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2bnmdeseq.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2dyyarwnm.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwsaxgl.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnmnlyv.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2fstakuzr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2bahopzey.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2mznfalfd.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrtlapu.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2glemfsdk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2gynngnlo.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2zoabdoxs.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2duxwwwwf.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2evvfpvjx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvqjpyt.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2neiekrwu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2bezwjpyo.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2murqwqic.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfcchlm.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkpawos.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bnryrktn.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2lexnedoa.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrtrwos.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpwayyc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2rgzqjvxx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkbluvr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqitfept.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxvycbr.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2psulrncz.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhdcazo.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zwcmlqho.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2plxpwdiv.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ahesditu.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2xdztvmea.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2augcgjmm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2njvhyntt.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqiquhxe.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2rssgupfn.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2wovlqgrz.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fazbbrot.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2taudwrvp.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2szqnqyeg.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cenuniln.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ydxgzpso.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jqzywaij.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2cgwomblu.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2nyprifhw.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhklbhsd.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2swdgtvwb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2gqzhtovb.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2ijsebdoz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2qztztspt.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2wixqkioa.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iruruzov.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2kvryrxct.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2affhcqld.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbtmorh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrsxfzq.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2eijdieqc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwofbbq.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mfioljwn.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2dwdptefm.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2hzfjbako.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2agzauing.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgmlooe.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2nhalbvqu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2hkdvxzec.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2luoydlgv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqzurll.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgkkujb.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2sjlcawnl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkyfkvq.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfefaoeu.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtcsutpw.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzhoypc.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxlglyn.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkszlcpm.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2adxyoghc.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpqpyls.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2abwclhac.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvfikxc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2gugfxnlp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctyokefb.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypeypvcn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdydrjp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqzqgcm.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxpwvap.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xxyamkum.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycybcgnn.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgaysysh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2himocptn.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2awpzdniy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifgwmbuq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnlkxkem.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktstugya.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfnbjmq.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2sncvnlqt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2mlcvcgil.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzczslfq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2muynrwbk.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2otvhfavf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2kallbykd.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2rholofse.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2omvquqwi.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2khrxbsjl.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2etjnedkz.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbonrvv.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdtdhknz.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2njtavueh.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwjprzp.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2mhzbwgaz.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcpztgou.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvgmixn.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnqzxpfi.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hsigdckk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqeyfit.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbhuzlr.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yisnixke.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwzhdtn.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lukaecer.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmnvyof.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2crufkiro.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrjxczn.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qensohfl.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uevnprrg.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfggwwzb.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2pupbuxdr.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkkfbwe.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mewicmdy.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2texjhjkz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjltydh.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tlaggint.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxclzlj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2xjttsnvi.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2slguhpfr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2iguuuomg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2kosxwazr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2aponzlui.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pluwvzjj.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2zxnvkhbk.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwvkkos.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgjjazh.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkczobtn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2atpzebma.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxobyaib.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbreyez.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2tsolouua.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2pwsloauo.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgthetji.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2xsiwvhoo.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2khluagap.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2quxwtssg.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2btonfjkl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2khunqkar.html


<!-- 参考信息 -->