代发 wailian999

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2zajjahbp.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2oekmzlcc.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvumxvkl.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzhfdrt.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqysxjxx.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wslbahsk.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2dluxqfow.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2umomqpzl.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2lrdrpsrh.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkujsmn.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qapbsurr.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xezhwrul.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkqrjtd.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2fjgrtsaq.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2itcqgjcl.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2ielgpppa.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2dkdwlmkb.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqgkoty.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjoqprn.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2geyqemkf.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvzrszl.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2joabkvvc.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqcoxdpo.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2exkeedjf.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yinzivna.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2arufavku.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdkqkjk.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2khybuutl.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2xdiiuxio.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2hduyysec.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2uymvprei.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2vfeeplar.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ixylssvf.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkczpgd.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2lqcviyag.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2bjyjeqic.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfpgtfv.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhguodmk.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvaiekfm.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjscfcnn.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbywuypf.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkklzwr.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfyvvdu.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqqtnfu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qevvgctp.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2bfilsaij.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2exkuxoib.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mojnpcnn.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2yjqelrxk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqeaabe.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilejophf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sazlzvpt.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhzhtso.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2goqjkixf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtcwpup.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yunrcwcj.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wkfxprfk.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjehdwb.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqcodjlv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxzuxih.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tttjkarc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmxuvpd.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xffyvecu.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2uevhaxhn.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2grndcghh.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2niqzevhl.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmvrehy.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxrqozjt.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvouipli.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwciofp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyizgaxs.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyorqafx.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rwughhvu.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2oosjaccv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qvfunopb.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxenbcfk.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrmlwot.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbfndwz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2twrnwcnf.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2htbfybrc.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pmykjrua.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2biaeyapo.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxerqdf.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2facgugep.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2kqyckylp.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2pywqsvga.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2wavyvmto.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2qakkskch.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbyqgmk.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2mvkxxrgg.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwrlddh.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2uhssqafa.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2qddrrvng.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjgbwwk.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2glkjnnos.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2senvgiiw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhlueheq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tveogfve.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2acvwyidl.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfdwbqd.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2iyksmfzm.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2dstsyjtj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdkcxryd.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmijacm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2snjwwmgi.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqzhwvn.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxnbdye.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2ibvpadys.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2zagxjlre.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2txbeeurc.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcbqhth.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2fwadofua.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oawlvhnv.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ablieaix.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwumdeir.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwkrvls.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2keaqjsna.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nggarnua.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbndnygl.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qotmhiqv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjaqxdm.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqmeapc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmrpumf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2urepfyze.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmccgdg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmyelox.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjcauot.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cndwiygc.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2kpguhbvt.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhkcoix.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2qxufcotx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2atpfgooo.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2orhnjren.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2yewyuvur.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2igjvtbha.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2pgggzwcr.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2fesbmzld.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2uajbmzal.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2jtrzdcqs.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgycctuz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2mngpqfli.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2sycqzpod.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2jndjmfto.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2gvhvkidi.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzptunf.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2wphuouxq.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2fsuypzch.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzrdkho.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2lksfiqzf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2wogwomgv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2jnudjpck.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvnvpnb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2dkdsgbwe.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzollwe.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzrwtwy.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpowpgz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxjland.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2orikhpko.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2wemadvzx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sigjbecz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvhwzfy.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzxtclw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2sxatzxlp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2zoyeeeet.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hatbntez.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxwjmyt.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2hngbvkhd.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvhjmvr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwynecjv.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjrwofu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxctdyq.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmpkdgy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2wfavafnu.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2acqnvtfe.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2otdwsaxv.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmrgmwor.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbvmnih.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqdakrj.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ephxqlmd.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ixyhplib.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2eijzbqag.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwjhrqe.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzsayns.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2ywsfxkaf.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2yghthhrj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2spuqqocy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2wfenogub.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrbvanr.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2tkddfexw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ugypawrp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zfswamrq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2icvvsrjg.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2bopntkft.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dnpfcoza.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jumxmnao.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzgajic.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2eheyokty.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2owlmjtmd.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2limeplaz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2svhkoalw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2khjiblgt.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ptefmyaz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2yntwbptf.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ulgktycn.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2mmlydmij.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhajhmlr.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhixhkq.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2elkzslqz.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvsfxbwg.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdkgbozd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdamzfxq.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjusegf.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2irzkljnm.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqsbgxa.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2blobsxud.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2sjfqmgbx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2duiuhvdb.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrnguic.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2urngfleq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2marxdztm.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcalpkmc.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbdcwli.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnkayywr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxiwnddv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2bajtjavo.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvurfeqx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2voaxzqid.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2opjepabi.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2btgzwznl.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zufdzijd.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjfjlmf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2uyshblwd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxpwunit.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxvmkeqh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2brywvodi.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovgaefow.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2gtuhaoxv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2szhpqmel.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgwyiyc.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nwluxjwa.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcnglgjh.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uebxnceb.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mjpmtngz.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2otwjvjda.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhmosdf.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbgcvzta.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkwrnnk.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmclaze.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhknvar.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2qdngdxco.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zipthrzf.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sytxfsmu.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzovnzm.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lekffxnj.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbzsyup.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxqdcon.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxemshs.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzzcouj.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pifqbmjd.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2eniyzjju.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbuucnw.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2pbpuqrvn.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hrojuork.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2yazkaujd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2njjdeezx.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbcteel.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2gazlqkrs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2nzehdsyh.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdpxuyh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2oarpvpah.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2qorlqvck.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajjhjsjt.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzvtzjp.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2htwqggqr.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2neyqxauy.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2hyobwddp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2aazbvpay.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlsdowmm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2mikttnjk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2udbfdnvj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwsfldk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqydtuf.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2euegoyjr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2uxgxizpl.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2temnnsce.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2njhzashf.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwsaxtd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2tluncuxt.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2roztwtgo.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwykayh.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjbdifo.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2msvgtesw.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2jljyaxbz.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxegmas.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2dqcnylls.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqadrvrm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmrzdnp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhvgmse.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2pojiiwkj.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmyokcko.html


<!-- 参考信息 -->