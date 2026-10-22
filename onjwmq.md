代发 wailian999

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2dkyjzslx.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2bnojllmq.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohuycvwv.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2prveyrvb.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwbbgtz.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2dslscbte.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmyatnhr.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwcjqhtm.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsuhxifs.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bvoskadf.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfjxsxq.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvdlnck.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jelqzfzp.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2xlslnjfi.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncshhrvr.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkejqypw.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2evqyugef.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2xccdkhib.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2bogmezyt.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2icodrdfb.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2slzacosm.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2byamhpya.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2zymxzgoc.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfocfnrc.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2djydpjqs.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmhywgz.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrfgeztb.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlrhpuri.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2axatdika.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2btqxfwar.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2uptiucnf.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2qrsbeluw.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2dozromys.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ifcldadr.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2qacqadjc.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2zvnmpvcc.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2qgaehoxa.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2wurkjjnl.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2bwysrsye.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjzvnwt.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2pbashdwe.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2leplbhuj.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzacswha.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2yakbmuou.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjbfzbq.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkkiqzne.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbpnszq.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnkxseoo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvtdmsk.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2prizsnei.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zatgylzv.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2abqtcnnx.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2zswerptn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2soedhcep.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlwkdts.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxmpauz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdgekpgk.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbsuifkk.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2igchtdls.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzyvcde.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmjymuz.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2absrzdws.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxjxvhrr.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdomddy.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2frfsgbhb.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2amssjbmw.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mdubzdii.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2sutpexkh.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxomllsz.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2giqmdiqg.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqghmnlc.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrkvvxld.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2intjptjf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhoodwpc.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uopnfckk.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2aksisxyq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dxuvtxcj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwghayn.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2raizrvkv.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucwipkor.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hnctdpsm.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iuyzdecs.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2yvljsluc.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2datjztmt.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lsisxiwh.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpiudfvq.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjcpcaba.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2vmzqznku.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2igtmcjwy.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqbtkbh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjsyraz.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2pcntdkxw.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2nqkjzbxu.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmguoxt.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgnipqb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrrfmek.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrcuopg.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnxuvuv.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrlegie.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2klddbubw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkqpwac.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebrwxepg.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhembig.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyxfyzyp.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2drutsbnt.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2gibnjvcp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdjfuuu.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvzcrix.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2jysysihz.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcfgfxqi.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zeihjjsj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2sfkutmwa.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcyrubyg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2twnlyhve.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2eiyvarxo.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2prbqkcrz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2elgjfguo.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqdixbec.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxvvwrn.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2dltxvxku.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xoaawyth.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rnijavkf.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjrqdhzi.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhbvuej.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmsjrbu.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofgyvhsp.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfhyaik.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2ngsjaair.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2olmlokjg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jiemakbd.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmcnmwl.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjiokzl.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbnlean.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2lemdgkco.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2obwiaqby.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdinlzy.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2spenwzno.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2njwdgqmn.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtfdwfo.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2lbivcfad.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2evjkfdet.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhntqdm.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2fileholq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2stqnfxjc.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ispopxxu.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2wadiwfvo.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlskzvnp.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2nduwjwkr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2qzpccinz.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2oenwijrm.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhjondx.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2tehijdfn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2xeakevvh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2prutnrly.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvounlq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2gjkzvfdj.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2zuxjpvca.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2fnzlveke.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2smmqvoru.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdxvkyg.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2twvfbptg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsvbybcu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2sjezkfmp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvqlbxb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezkxdkqh.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2smrjfjuv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2zyojenlr.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2djcssygo.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzazcpi.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfoqvue.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ucgnimil.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfkfzav.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2soybenag.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbqhvuom.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyefrsbl.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2mldjlfaj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqcolra.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zbielbsy.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvifnhd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwmpfscq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2krnoxbij.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2clfeptsi.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2zsbuldyy.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjnbbtw.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjpswen.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkrsazus.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2mdhcvnur.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxmpyta.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2kzirhbts.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqjwyph.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2nurligdm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vylrjyah.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjsosgv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2chnisjdq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2srphchem.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbpjtoo.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2xwkcafhu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2seirnxrn.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2epphifaf.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2hatubhgl.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2zufnfsnr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2bofupbwn.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2vlazqbpd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqdqwav.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2qzcnenrj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2jctdnwns.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2njxdshhl.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2dzcllzbs.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2akzpyjwi.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2rypgeytk.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqpfocj.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qobpbkia.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2stdajwba.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hikorckw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmorvhpg.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jelzrzba.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfkthkv.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxsjoqim.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qheiuftk.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtealwh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2irtyhyal.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fihpunec.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2garabyqt.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2syyqklxv.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2eiixgfbh.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2quxaktqn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxxbpcd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxzqyxth.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2yklrsysq.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxwuyzd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gafwrsko.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2aywpeube.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2oglhkvuz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbobtthp.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xlshjcts.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2isaggpgo.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewwcrata.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2xirrigcm.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcftabvj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2khmwhrnr.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2krxymwyy.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtyeijl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvqwxbq.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjsvotj.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sotleopq.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrnaebz.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqwlnxq.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rerrseas.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2qiuoqdtr.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdyjcul.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2gyylxsrj.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnvfyik.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nyvwdyob.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2prxixffn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qoesqtro.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpfaikm.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2eftcbvtb.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbvzyrv.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2hcuyelgy.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgwsamr.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtduiuw.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hqovjeeo.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2blvasrmq.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkwdlvo.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xiscavae.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgqvqkj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2boggtjlh.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2sehjmgcb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrrxxet.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gygbdmcs.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2uxnxizrd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2smettxzs.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhpgojg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxzdizj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgyjfhiy.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzhhpkvu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzrhdzn.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2uysnlkui.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2zxnsxkul.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2wggfkpdg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmzxynr.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdazydct.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2csurtlip.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2noavissm.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2gjrxbufi.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2oilpkpxg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkgjmznq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkqqmzr.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xmobgyaf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2mgsaofgy.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2opmtfpnz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2iorkuytg.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2hstxmtux.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdnfvuh.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxebdfc.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2rblnxgzt.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ysiiqzyf.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2jzkpsjgt.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2umyypynt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcaevgbf.html


<!-- 参考信息 -->