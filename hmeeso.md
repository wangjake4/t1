代发 wailian999

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2favynnfa.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2cqsinitl.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2zppkumyk.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxryrdii.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2sypkrqbc.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2erzlsvcn.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2gdeuwywc.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxmjxwx.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dphmbpfe.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hengdpqt.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhkdbkv.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfoqoqrt.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrgyjsy.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxijtzsc.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtgauna.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2tyitqkbh.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2lttoponl.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcwkxse.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2duqlaair.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvoxfyc.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2fxngbjht.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2clqlpaaz.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzlrcen.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzmzqgw.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2umpdrbya.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjoppxvy.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrxqzyqw.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnevmde.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2jduiewpo.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2uiyysixs.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2jriceaio.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjxiixf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bseykind.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2kmstbeat.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bkuwrfyn.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdvmvwx.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmtuotl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2miapruxe.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnaqieji.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyevrjhc.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tiilipmf.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjpczqf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rdoqatri.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwootmhc.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hppejvjs.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2rtafygeg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdajrozu.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cusryfph.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmeluaol.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2dhbdygrh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vznmtodk.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2vybguwcv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxwvhdsm.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fxuamusg.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtquxhju.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzttqzw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wytqvtik.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdegrov.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmblkzge.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2mocsnmuc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qubampqc.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2yutpwlmv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mzosadge.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgbebwh.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vstbgucj.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdztpfd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2obdfqigu.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2uhcvbppa.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jrrlwazk.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbxkgzm.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsbejzx.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2xsyyykuj.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2dnuhucvu.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2njjrkazf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2hdotzqei.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2awpzfruw.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2xjrvihis.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxfwoht.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2pgsehkml.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2cnyukpei.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdzbxxp.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2ppskmjfw.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwonccz.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlqsdkiq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnqytfd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecleokqg.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdstjre.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2jygduilj.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vitehora.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdnvbmb.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwmgluq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjohsbwa.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2scgyavxx.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmdxoat.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzewznp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfvuubm.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2roirxgno.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdddiqs.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxikvgx.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2tvauzycp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvqyfqe.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2akryjsdx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2keftbjxm.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbofqns.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2teukhyhi.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpwecjy.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sstdknih.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2edhimmpy.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uiwkhfre.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vabyakev.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2qtedpttl.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2ellkoclu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxwites.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2iylaemqz.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mppjmmqk.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpyaymau.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2eddoksuy.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2qrpkknlk.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2bjvrjnmz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2qhwzuamp.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2kjbmcdif.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2eotpfmfn.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2proeeeds.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2exlyqowy.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2oupvgjhu.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmwxweh.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2vwctbpld.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdglibwi.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbnhjpz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxebcum.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxecigdf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2ysurirel.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2nfciutch.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwiptbx.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2thacbimi.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2qgyorxzi.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2rfapjvpt.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2tkadfoih.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2anqpwzuk.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2xpteckgm.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2tterywkv.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxuhfqv.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qidptjgy.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2pklhbcey.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2zpfqazll.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewpelalj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmxazrk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nphyyepk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrziejhv.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2fewtprag.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2bsqkrpjx.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfilzhki.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnpghao.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2qtcaremc.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2emiijiow.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkummwd.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgfefbut.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmcxjxah.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrruqxgq.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2neibrpsu.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2ygsekqqy.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkglizn.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2ejltygqc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbuuuzy.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kfiwhbzr.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tbcfeuli.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqusdmj.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2npjdoobr.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2qyibjqsc.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyyrodds.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2yriwkeyt.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2pttkybsb.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkwnegn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ahihzlwh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2oljeaaku.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjuyhgs.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2irqbgwbq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpeyzlg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zarkoifj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfnzfqi.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2crduqdkd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fueimydg.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ydctymmu.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlicqby.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2zgbxszgo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnpglnm.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2eyflsdvf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2bupyjtdl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2retivrfh.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2bzflkniy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2zsauqyyu.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhokakt.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2hpixilyp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqrsjkj.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjiotwey.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjlbrup.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nuduytdl.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpnbrzn.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2erhxuycj.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmnlrux.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjvwuno.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2bispptgy.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgskfoc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2asfpornt.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjzsliy.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqlzlrs.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2tahipoki.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwkrurz.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bysoeopr.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2esqvpeij.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkvlcctu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjrivzex.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2kskauknw.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrcrviz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqztcuz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvsueij.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgszbwhv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdadsfd.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vhedlhzt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzvuuin.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxktooc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzqoypc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbttwtie.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtambdnp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2qqsyfaco.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2namyuxly.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2kovqzeov.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jyskrana.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dllvjexe.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xaeejhwj.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hsksqcik.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqvmnxg.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2xbtkvaho.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhbpkqg.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwuxmmk.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2scyjcykd.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2cnuhhxyn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbtuuaj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwwfffc.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfpczdp.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxtmkqm.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfieunb.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2msyamclr.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2zxizaavm.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2khqyejvt.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfndmxz.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sudgwviz.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpbjjxz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqiwmtup.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvbjyol.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xctrovsv.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2suiropat.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2unjagchn.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqbruyi.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2ukzwahmb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxrfqqy.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrlteaho.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2elbhbtzj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgcgagu.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2hysjzgma.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpmdcaw.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2jrudebqf.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2slcxypmc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2nthyhbtu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvsabiqk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrqlwkx.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnqtdkdi.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkybrqp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2cfkdmbbo.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2uwebaxgl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2akguapkd.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2blbkqnuc.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2znutoxnd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdnjevc.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2elufrwmy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqbukfn.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2crouqyzt.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2olwyeqar.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsutgvcf.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2iuibquij.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2vxpzxoch.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2ibgeqbzp.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2xejsxupb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwwglld.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfgqquc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2oisqlhjd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwjvpvb.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxqowrr.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2patbltym.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnumdhl.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2jdggxzzl.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2cvtmvanx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwmwiqk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlldskyd.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnacuymq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yhptqpye.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2hltlkkxd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnwjibl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxjrocd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2qeiuvffu.html


<!-- 参考信息 -->