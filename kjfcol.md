代发 wailian999

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2imwwkrfi.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwlgxbb.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfvlfwg.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2swryjzzn.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvwweul.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtgrilz.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2stdrwmgf.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvactsl.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkyxcmyk.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqukgdno.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xufjqsxh.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhjmlnl.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbjiyna.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hiiluxmu.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2rwobxthp.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2unaekllh.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2avtdmocj.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxmkqei.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2glzyonat.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2kouxhgny.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqatfqo.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2dwamaajq.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzsugqb.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2nbuaetsp.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2rpggwycd.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlxczxr.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcsmiody.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlfeuwup.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2aleveilk.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxptosl.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2pghpejzw.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwyymxhn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sksoaarv.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqbfqyr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2musjkqut.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvhempe.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2uqkxxdnt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmcyadtd.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnxcuqo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwwbytvw.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2thxtuhei.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvsfcecp.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrirrek.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfggnyid.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xowvjwvo.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2obimxwfo.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pluexqki.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvqbnry.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozqdgniz.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwkiaqy.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gslsiebb.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2eywyvrbu.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2isdvwawd.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kawohkbj.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2feziesgq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvfifka.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jymutwkc.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2okajmzjb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozfbyawu.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqgspjqk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrddsjh.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrsssfw.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zbaiaxtf.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkkwobus.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbjbatp.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2niumdpjq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzfybri.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2smkubezu.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dbgxtdou.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2flenurrd.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2scfwrept.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwammhn.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2mablicvn.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2twojikcp.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2mlweldpv.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvwwuej.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2ytneddvy.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2odjdnlgm.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2hpcqbnbk.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2slcgezrr.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2jlimkxnm.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2lqokvddq.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqdkbjq.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2boeviibp.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqtjxcrl.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwduetn.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytttdzwk.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkysmkql.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxiwrypo.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2cmcyrtmf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2urczdile.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ssoxlinw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqpandbk.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpwwllg.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mkiajupu.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2fikhlhzn.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyibjnvo.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2clcpmjpf.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2zuctxdry.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2bykrpkmw.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxyajka.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2exbtifhu.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2odguzgvr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2xboxjltf.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgkagzz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpeaccp.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfiqrhb.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxnzabz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqybfbaw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzxamkuj.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2ifisxqkl.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2tricrcwh.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vstdprdh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghksdheg.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqifbgi.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cklghjzd.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2aaqphqiy.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2eywhkzur.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2lgdtbnpa.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2sijnqonu.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxnjosl.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmxsans.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmdsgff.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhlqheb.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2qnrcqybm.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2rejkyfga.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2liaeewkg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwajagmc.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfhvqwn.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2zilsxhrm.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2udysgxzv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmjbngw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2qlwszwnj.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2nuucttqv.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbpbknl.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2phaadozw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2nlymkjuj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgbhncv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2flwpjopn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsixubl.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2simigqzd.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2axsunbek.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vgafkmtw.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmtgpek.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2abcwvnim.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aoefruap.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2oxnqyjez.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgwafkxe.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eypueojw.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2wvvvlarl.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjocfsd.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2otwnnlau.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cnnpnvsp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2qcemiwih.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbeityg.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhjkenk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqsvpum.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqiywhws.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvapfaw.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2sprmyfsa.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2okvjjpnc.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rjkqjupo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhwqfvy.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2huamzcpq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cmouutuz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wenrnvky.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xcyzswwp.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2fabtrcwz.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjzgjow.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjgferfl.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhvxooh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2ujssbddk.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2svcotrsx.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2yolqnsdw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2wquefgln.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mocgcnrz.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2pyezaybn.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rruljrdm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jvrbfvlx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oreughyn.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2pxsipdtf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2suzlfwdm.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gazwicxi.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2sqkygrnt.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2grmeojzw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ckskzysi.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2fmgkjkzx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2rkquxivf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2cnyqxqwq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwhhkip.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdpelue.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2sipyyzlg.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwbtxjo.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwevmidk.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2worrrjsx.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2eutgserr.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfagqtn.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqvvgzs.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2myokyvlf.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgddmlh.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xdupnxpg.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2joceibhq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lztqrdxq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdbfnyh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2eheewsiy.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2sofugfmm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojrypfdl.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2aviseiaj.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfakjuzr.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2byryjdci.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocemjsbx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2swkxhubi.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2njygcxev.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahckcvir.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2znpdgcoo.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkcvqrpv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uolbahiw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wapwevkd.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxoynwb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2qswfvmep.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2eweecsch.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnytucbo.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mftafqhm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2evwowsmu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2uoafdxxj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrxxjqt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2welbqkuu.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2todmkpxq.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwggqni.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpobiajr.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2pfynnhjb.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2pnkalbsd.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2xixywqag.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mstwjrxx.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ldbmwmkh.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpcazssr.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2axgoohow.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmwwflp.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2quhxjclr.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kggcgisd.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnljdoai.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2eorkyugb.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2ljyohmzb.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ttehnteg.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwqptxb.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqircrp.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkaoorb.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2khowzwef.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdendldg.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2gxceeeyc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hdareolg.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnakszim.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrtcfak.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmxfnjj.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2omdhbphb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2quxdwovl.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lphcmkna.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtknouy.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkhieauj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwykftaq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsemwpsp.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2kslvqplw.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2ougcquec.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmsaigr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrweeloi.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nayjdwwl.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2wafalxxl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqssljf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvoqtif.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2blqclvjf.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2omifnjaa.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2loqvehcd.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrrrllz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2yirijlxz.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdohfuy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2wepnorvl.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2jjskfnok.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjrqdlhz.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfyglwrp.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2igovsctb.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2syoylgrl.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgslkuf.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2wbceoelw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwcnkth.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2unwkpuli.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjgaeyj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2pvakmylu.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dboykzbj.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2alwaglzf.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2nglxkzck.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcuubvr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qehhplpw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2runfhmqa.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkrhqtuk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2usgtugdz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dxizgtwk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2pjazumsq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbudkyus.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2sxuofrww.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2iaehecun.html


<!-- 参考信息 -->