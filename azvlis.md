代发 wailian999

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2iyceguxs.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2wesipdrd.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxrsdjz.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhijiandao.cn/Article/details/gt2podfmatd.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdigvsin.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpcknbqe.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhijiandao.cn/Article/details/gt2lceagyng.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwtwofc.html

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxlxobi.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkqmnzp.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xshmabff.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2njefhthx.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2pvpfwdlb.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2piramvdt.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbmpacy.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbtvtww.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2mevhlnyz.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2sxftfpfp.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bypnvojk.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yeabahop.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdcmcal.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cknjiudo.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2xetblaod.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2fjuhrslp.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqhfmlk.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvasnsr.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2syrcpfpa.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gubvuajr.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyscqhrj.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2ywezjhhf.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2qaawsaoq.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxpmoimv.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2odveugdf.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2nvrkxnno.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2iagqnfll.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2azpirkip.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2stdioxsj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2prhuawpr.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2puxdtxez.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2btxhkrnk.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtijcfq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rclfdzgs.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxicqel.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2vedhstbq.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2rusrjejz.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnqnxpq.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2grkcjysv.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2mzuwavks.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ebkntrne.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2jejjbedr.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2kotpndsa.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2beziahsp.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2zouywzrq.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsswsqmj.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgexnzsw.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmbujwy.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkabfhe.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpzzsckl.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxozvno.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2poqhvesb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvzrbxe.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhbwtfk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwojhgs.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lygvsbek.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2xuuzkibq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvevknw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmynyorb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtzwtqr.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hynkafoc.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwpgfqye.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2egwfzhxi.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvpjhggl.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwnarql.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2cdnvokdi.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hthatfba.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2keqyulrt.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnemxwum.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2methirbf.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbvbwno.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2lryevecc.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvksoln.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ogravwjw.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2xonfizrt.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrmnumg.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxugdmdy.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgpakun.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jinkcpbd.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwsdbtd.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwykala.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2zoyvvtlr.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ioldpozn.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejfnlkse.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hoqrwxnx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qlemjeya.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2nwghgviq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2hmujangd.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2exvdyysf.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvjgkku.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2auburdjb.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2hwehnlvi.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2jemtrnlg.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2gjkmavhr.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2xurvjkcs.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbimfuv.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2zkjmoubv.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2sibjcdzx.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2orjunmgj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2gnoygnlc.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2psgxrogs.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhkchif.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjfflzjh.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfobnkk.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2cumnzbov.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpsisjeg.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyesymzo.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnthmryf.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpsbgxk.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2ygceervq.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2xradksur.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnoonpqx.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2yabzdrom.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2svgobzyx.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmojxqa.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2xqmacftu.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2snfijunz.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbumaya.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2qkoocdpq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmrniah.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uktrqloz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2segrdavx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnlbzyjd.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbixwoq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyycnieb.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdhomgz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2peniekpe.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2igcbyrxy.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbszbdtw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmqkvxls.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlnnimj.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2bddmtsai.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnnakcf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlidrfdq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwaiwmlk.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2opcjlmhg.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2uahpwldy.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2dgolmccg.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2hkftceca.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2frmuvdpj.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxqlick.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsnming.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtgtvoj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmyasfi.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbhljbc.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ebdyobxn.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2sczmcavj.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2bffgfqco.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwxqpon.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzoxwvg.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvvmquv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqsddaf.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxisrit.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvyppizx.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2dhiixlyf.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2xpgufhex.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2opbglghn.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgwcedy.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2tufqqubf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2olfnflnf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2mfdcbmmt.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2lzejjnfa.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ofgzmtgm.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2alukzuhi.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfthmbw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vthbkodo.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhtlqas.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxdnqnn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdupydtr.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2jzcumoln.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2nzseuqgv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2ektyurkf.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgawyzs.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2cevznlzf.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2dsnvlzsl.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2plrvhpeo.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgqrfje.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhwqnpn.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2knniqtws.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2lceobehc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjesnvt.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cplomafd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvvwshe.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjhfldp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ixpaewxu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2afxuxisa.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2hressfzd.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxvmjyh.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2bnkhhdyc.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmtvqixn.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2djfwnkiw.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2phdmcune.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxcpegm.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzxxslb.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2wvazivyx.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dtnnmrsv.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2ryozerrq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mcxfwuxh.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yijltgkz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2warojyyu.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2fuaxhznz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2owqtbjxv.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rhimgtwy.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2wuowaqpa.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2iaasgaxd.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2otcurtpd.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2clcuaovx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrxvrrl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2jzctbvko.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwibuia.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmianxp.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwjixuv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2wdocuhem.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwevkxp.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2optiybic.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwlwllhe.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bygkohoa.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2snbyhxli.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbostxuf.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfcnfqo.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xfoxktwd.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fljxqtbj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkmrybm.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvbxbrq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpshkggd.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kajctaog.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvddwyyd.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgimmgw.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixpxrqrb.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pkclxrse.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dglrtzpu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2svqtfdbp.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjrwyqz.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2intubuts.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcwsfta.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2blprmanm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzpbdsrm.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgfnbiy.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zpgdnesk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfgkecm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsosuevd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2gemgldbr.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjibxan.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezymgftb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2zxebdxvg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxgabyc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2kccrtlev.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lieozopm.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzygmfgp.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zkcabdzx.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yszjnqsy.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fktcbegn.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2hgxjbjub.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdvxinp.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2mqazebaw.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkagnjni.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hlfrcoos.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2tesmxlhl.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvzwpcc.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdztxpl.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgoyoatu.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugalvdyq.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxejtvm.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwnzjjp.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jsxkjcdb.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxdjvto.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2daprcasi.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2opvakepj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2blrccgjy.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2hjbehxhg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdobrwq.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2qiugmcyk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2stlwgchw.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vfsjhgjr.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2qugojndo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2zwnjxslr.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kymsiqaf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2erfskadb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzquixh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmzjbla.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uawsavom.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2eywzstjt.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2azzusrch.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2xaraoueg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmctlqvt.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvhlbqm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2cckebyty.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2absfolrg.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdqflnj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwyiepf.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbsxkijh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkulmoz.html


<!-- 参考信息 -->