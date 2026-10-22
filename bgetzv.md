代发 wailian999

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2undrfwbf.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2unqfzmzk.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbrngxl.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtckvwo.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkcqtzp.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ynuoucqw.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxitcnd.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2moigafzp.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyikznwt.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aiatkvfm.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2bknyvsdp.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdbshta.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2taofypiw.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2grallape.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zaplviro.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpepyfws.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2clyoefri.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2rkedtjej.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2feqztymc.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldyrhaby.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2unmpnimb.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2hriggwbr.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2oncntalx.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwrrkcbi.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkoisuov.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpuyrqht.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxdlqauv.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmqxsxm.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2syheeipo.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvnxmcjp.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2kkiieuyz.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfhqfbf.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqdgetp.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2kkbsrvtu.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2xeixuynt.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxxnfva.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2tpajrvjk.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2uanalnwl.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2lglosuyh.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2omzujzdd.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2kgiqjegm.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xowxpogx.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2bajegsyw.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2qalwulwa.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqlmflz.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2urdcwakw.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2qixtxsih.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2romwkesm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbnscdj.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2inyjarbt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqdpyjs.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqpnknt.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hsowsnhy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzyaligo.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2deqzqcfu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjleunvy.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwpkurg.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdskqxj.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dntwuyto.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjstsyi.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmbbnee.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2gtchrbvy.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2adkpujru.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyonybsh.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbrkweif.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2dxksnkgb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2itnuwkjv.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2tczbwbuw.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilopwgzc.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yhdhzfpm.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2osjiiixt.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xajrocoe.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sngbbvdt.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqhbjrxi.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkpgyvtf.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2bspwxeoh.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwgzyrh.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2hebexacy.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hlgwkxyz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjyxyej.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mvvliede.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uojkcinm.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2iaveweey.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxvwtxl.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jzkpjjis.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdxznhw.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtskpnlg.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2assstpwz.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2kiithddp.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrklywb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2wxorhosg.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2vzhxrzts.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2ppiekmlw.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2dozihizi.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2qunxtdod.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlfmdfs.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxkheir.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2jkuanzey.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvuldlj.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrutokgc.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vatwnnws.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnikyvka.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2njubktzr.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilteromq.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2peaspang.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmhqltj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqtzzwa.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwcispao.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwodfdwn.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhknmcd.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dvkzlpsv.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2wkvpzerb.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2aoejaimt.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtielhv.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2zmgckcha.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkluefp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2veihbumx.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fohrzapm.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhqsgct.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2saerzgze.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnpneebz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgtbchc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhqqiww.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qdgikxia.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2voyvrvby.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwakwkjq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvqfdpu.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmsdwuz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjoyfsly.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbjxphn.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iibrhcwf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzgscwq.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2bhsxyqkq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2ofuoygsi.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2uknnsnao.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2rormxjcw.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbjwpbh.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ntaccbrh.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvbnpyn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbflpga.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2topfhocn.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwtxdjn.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2mayzmbka.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2gymzgkpg.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2gpykasil.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2uidokhcy.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykpumltw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2prrrcues.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2aigorebs.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhakssa.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2tranwneu.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2pdpvdgqe.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2fobduvpj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2jdyqngbz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2iigjrnyj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmhqnvi.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2fxiydlwe.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2nkmmplzr.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvxutyf.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2olsxelkp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2isvuudco.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvpypukw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2maizanxb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwppsxnm.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2etiuwkja.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2xsfnrdis.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2wuxzfzoy.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2avyxduzf.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2atcbwimx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2wnsoowzd.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2wohhtxul.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsbgrka.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iimecohq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iiudlkqg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2byslkzol.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2wrhhttwk.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2qdavgcsq.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2laqswnql.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2rdlhaerx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjflnny.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dmuaewkl.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxcmlcw.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2lotqtcnz.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2fivsquyh.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2dsfbhffl.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2zuabxxdg.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2tqcrwjfm.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2mfrkaytk.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2byowulmt.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnjgnov.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2krqemzbx.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ftsejlab.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2bkbaiwep.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2popsyhsa.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wujyawmh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nyigeohf.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2vybseice.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eabpizbj.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2iteafemx.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2ssoxbcbd.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2thhjsqra.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2widvznxx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2puhgntep.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2pioxokjh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwwzqtr.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2nhulxkya.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2cqcivsdx.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2uwgxhblh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2axjaoejf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrfpdvg.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nefyzavt.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fyeqphps.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdinolbr.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2owtyspfx.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmsuuryq.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnnfoafr.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ycovaccx.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvawnbre.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcelkcq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2yspnshbd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtmkvzn.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqnirwfg.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxgydcq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2cngnmgjn.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmpkipi.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2snqczizj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxwhqbnl.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmigpis.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2binheghw.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2yejqvtyo.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mstuucel.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2dawgahjn.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bowufxpz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gocjaneu.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmbxfwg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2hlogsynq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2knorbdyd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbojsbo.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxiuthzg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlltmzqs.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2biemzhue.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2veggelld.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxkxmldf.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqtsalu.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbeymara.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2trlqelzh.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2grtvtjxp.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zojdmtaj.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2oaphpcwn.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mulifazb.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2tokwpfdp.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmrhasq.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfeyekm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2cgyggqlt.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2anqinubu.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqdpvrv.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gazmmfch.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjnkpcyo.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvfebyj.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgzervd.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2azvclmgq.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pugebfms.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eawwuhsm.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfwcbbj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvszcom.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2mutkyuco.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2riuiyjyu.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjadtasu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkymchrd.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2basyetiy.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2zalxotan.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2gwckxtmq.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2saebiazp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2yzibbxnz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvhowxv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtsklas.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsqvsxym.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbpista.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2byvktkay.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2iboosvrf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjcinyif.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwineuk.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrlpwjs.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2huiylfnl.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2mloyzgbv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2udwhuumo.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2adlfqaxi.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvqrvtc.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmzdtdg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2lxfxbcpn.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nlzmkjsm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2ewatmhfn.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2tpywzlng.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajngkcrk.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nobrfmeg.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2gaaeaexb.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpcefhz.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2agtosfea.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2yukstpxu.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bsdjeoqe.html


<!-- 参考信息 -->