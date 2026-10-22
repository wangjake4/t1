代发 wailian999

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwnhvxd.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqvtbcn.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhehska.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yzuwughc.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2kgyatmzu.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2bsiagclp.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjefcafs.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysiofaot.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dckpafta.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2umrfbqai.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2hvsceryi.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2ejdqcvqt.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rlkhibhv.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2vaihgpas.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iekhnfxb.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrudkbu.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwndspe.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2gtujcjuz.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2obkgibbb.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdijjckp.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2quhbuyzi.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2uyshkxjh.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2yujzexjd.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2jskkgele.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxwbfwz.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pftdjiom.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjqeuhn.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggefjkyz.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qixnjjxe.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2swlywenl.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2uvcjxzrs.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2duphtkqj.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2tbndcoew.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2avyrcjdq.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2wngnztql.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2awzjkjhy.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkybyod.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2hzemxqgs.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2hvleybfa.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2qwznaffp.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtoasxl.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pampttvk.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2otojxnze.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxiozop.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2icdmmzyd.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2luwdelgl.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2wplwbnjq.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbqciuv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fgsbymhn.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2tggjtxxn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zvenqror.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nhefxuup.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2vxyyuemh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcbqwyzm.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txytdlak.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njbzmtuv.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qglblsde.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zucsnhlr.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wclsldxh.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iukbvykl.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tvykeyec.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2hgehlxlx.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbvywcu.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbdnjjk.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvfygzb.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2banfsbjq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdvhtkc.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpvgvmv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2izfnfmem.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jdraqvuf.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2elqdzvyl.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2buazjowl.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwkzskxo.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfctyrof.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxbxlxrh.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2diijcaay.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hpolgmpn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2eegnquqt.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjfgode.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpqhtuv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bxibvybk.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtvdmdi.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2zikmvpta.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2prqgrfes.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eqagzjrk.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2znlkoubl.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sophimwa.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2edknaslz.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnqfeon.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ripnexix.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbrbibh.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzoypgi.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2bynanbwo.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmsblbk.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqdpzka.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2chkipfzi.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2icgwiivp.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmsgrew.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgbyruo.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjiqmvrl.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2frtbizju.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujovwoyg.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2jaevlnoz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2nprggmkv.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2efqaabso.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2katykaty.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgicxrk.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jufinxoz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmiaxtvc.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpgsnrwi.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqkzskf.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2gffrhmak.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgxvtes.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2bowxrowe.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ttzafvez.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2adqmcanl.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pykajjlm.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkuukooc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkgurpo.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2zibqttjn.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2busvmkvn.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fytypvqi.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2buzlmdqn.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2migbhcko.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbtooyg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryquhyxg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2dnlecfvj.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2jizqtmll.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zivythsf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bahrcbsf.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2knmbnazp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhdzcgo.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2nygozaiw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2umekkewi.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2fzftjozk.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2fydvpndw.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqwetjb.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2dkmebxsf.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2weskcxhp.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2miafcozc.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrwrlac.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2bdamwwdu.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2cxyrsmnw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2aispaeob.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2lncvkvpi.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2khsutxbb.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmeajlml.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2eezhwyua.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2saklosei.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrnrnck.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2lanvmkgd.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2wprxcdpn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2iowkjnvd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqtljez.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrdojbn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2ssuysmmd.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2umqraqev.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvsanxx.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsiaxyg.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvfvdci.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfxmyze.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgpoqwpc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgorhks.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgautxml.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybsnnjlm.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2xnsupuzm.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjxrbql.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpsfnij.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lufejxcu.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwuihqp.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2wykhsulf.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2rscrmlem.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgypufcd.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2svnpxloc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfotqhrg.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfqaslr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2nextyrdx.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mftjjimf.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2cgjsehgg.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgwdbpj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kmfgvqsj.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwpiqde.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2yosoglmp.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ojrnrcad.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpvtbxx.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmdmfme.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2kutlfeag.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfrfvst.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2onrzgmwa.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2yekanlpr.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2igscadde.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrkullu.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2iekeaqpz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hipztblw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2axkcxqqy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jeymoxcf.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2vykxrswf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfqimpk.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2unuulgrb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2buhfindp.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2kdeguyut.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2cgoouumv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2yqggwlaq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2jwldrjsd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2eyzmtdva.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2gklbznok.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2gexsbwtj.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcvdinm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkpimwu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcvsqjmj.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2aprvlfid.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cujvqqlt.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzkkaxdj.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2emdsabnm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwzosfg.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvslidtj.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvanjfg.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytuikewu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnyzsnvm.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxmsala.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrqonpu.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxdpmld.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxfagrk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jldlmbdb.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bflqqgje.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2opyropch.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2suffwhwf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2eckbmpeo.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2adphtule.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbouzyzh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdjqsde.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2duijrksl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qymosjhy.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtbgryed.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hilbvkno.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2yblitvjl.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2khjykbiv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2rusrtqrq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pngbxnji.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjatwjsl.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2nsdqmptd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2kbkeplfw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhnhfbqu.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrhhoyc.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cetjcnhc.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gntaehia.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2emopcypi.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnmtgvb.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2rfkrqmrn.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zisomydq.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2eexdmcjb.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxinyhv.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2astbltay.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2duaztsux.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqverejo.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdjcxeo.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdbsxfps.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpibnxpi.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2utobgnqw.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2vrtuvtnk.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhhlmqsv.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tolxcpau.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2baivchmp.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvnnzbth.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfkoolok.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2deiigjho.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kpikgpqb.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2btcixltk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2canyursi.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkwnrpx.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2wxemzisq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2webbchka.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jczziyks.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjyenel.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzvvnjh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqovzyw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2syfooapf.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhsqukm.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2qarpeyxw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmgeozw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpgpouth.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlvioby.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvhjcxb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhhqeik.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2nprcgxrq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2cofnspqn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2aawatvak.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2xygiyofk.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xfaoiawj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2wcepuwhq.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydabtogp.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2toydnzip.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2qaqcvfyu.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2tztkcvmo.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybqhlkus.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2zyykqges.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2djrohbsv.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2yiuxsziv.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2stexpres.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzrawew.html


<!-- 参考信息 -->