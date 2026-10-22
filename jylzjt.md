代发 wailian999

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmnedecg.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2ljzgdphi.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2barmfwjb.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2myfnsknx.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2spldewoj.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2miyjtunj.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2ehoxyjwu.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2umrdsvrp.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyqwoduh.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xeknhwch.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtbxybvp.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2clntgzss.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsigtvjx.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvwutnhs.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2iiexirfc.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2lccltrgz.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2vuzunhan.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ihscabcy.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgvlxre.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2zijkypec.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ghnqhchf.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbsluuz.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2odsqliau.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvbrwqv.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmguurw.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmszxus.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2bntgvbcn.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2omekwifo.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2irehzlec.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldosokcc.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2ypqbjism.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjyqebzf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eqliiwlj.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2bcaejlsu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pybiuxco.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nujbzecf.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrcnqve.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqdzsynu.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwjzujp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpcmwnfd.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wewznwgc.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjpnajv.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vetrvnqh.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2irzazkfs.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cslhnthz.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzcoief.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmqibki.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2shvqqjvi.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvbeobrl.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2jplpnuph.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfhbhqy.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2buzrumiw.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2galcvmtc.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhdjura.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgifmsqa.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdgilmdp.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mymgtegs.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhgkshv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuuipzag.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbkffegp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdncsvt.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2ncyogwfu.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eqpuptsx.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvszprh.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfvdyrp.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2akddcsgb.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2gjrdoqmk.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2krmkbgfp.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvpxmbk.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdqovng.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrlbflg.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2xfoiklgw.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2msbqgrmu.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2eczeektm.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2bnkxovnh.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzlzldw.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbjckie.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2yyyiynpx.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqqoyyo.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2dziuusmq.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ubykgfuj.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbnbgcw.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpyvhzmv.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmykplaq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrlfqtq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvymgbi.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxvzxen.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqnukdx.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dprlqwns.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2idvrbpei.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgwvbkp.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvchphp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2kygepljk.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnonlqym.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2phkwvgdr.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqyrruf.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2bryumkfw.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbyvemg.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjgdwyp.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2igvklmvl.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dllgwclq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eavhipcb.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2whhyylcr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2luuilwey.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdnaiypp.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jobxzfau.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aykzzqgo.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mpysaohm.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzoayoi.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnqvycn.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2qztiomal.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhgvfwq.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwsywjb.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2oegvkvxn.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnimhkfy.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwztuqtw.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ttksjcwy.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2nsofmoxz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2rcumihne.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2cdsbxigj.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2umfclult.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgcceed.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2nhldcyvy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvfupoi.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ohpgsyhr.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2pflasudg.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvzenuy.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfdmneo.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2cwoamcxt.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2feqiipgr.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcatsyym.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2bcumvbpv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2bajyhefp.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvysrcnf.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqriecp.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2xrzwpouj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2kumbqwfu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2zfniexgo.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2hcfyahis.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2smhvbvej.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2zgomzwjq.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2etkugdhe.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkqutbi.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpymcbd.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2cilzgrac.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmsumpat.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqvpyjm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2swoljucl.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2swdmzlpd.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2vasyprci.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2hzrdafeb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcinhazn.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mljveuoz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2qllcembw.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2tbupxczt.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2itnzsbug.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgdeard.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsagfjcr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2knoeerwz.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2zrcfkreg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2fwmwtnwo.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2raekpcpa.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2jmxrjfoi.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2astjxuvm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fvnystgf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zjlxeikb.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrdfisf.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2kdthllac.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2psxequdp.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtvztkv.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2twetesok.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2dqsiicee.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2eqcnhkih.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzfeetl.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2dcnbvyqi.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vexbucgs.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqstszi.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iohvttgt.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ctblsyni.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhaozjj.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkfeprk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ussdasbc.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rvgkahoa.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2cfloyhxv.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2runezxdh.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2okmmxlji.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqbooph.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2sagvbume.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjxvtto.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzgvcpi.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgmkbhc.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2qdmoeqlp.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2qvewbvli.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmhaxmn.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccodducm.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmlzsqx.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uskuqljz.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkymcvrc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlkqyosk.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dooqniyt.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yjekxwng.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdcynpa.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmnjfljq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2ybqfpiaj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxgprvld.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqblznlv.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2brzysfgk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmnadkp.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxjimcf.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uehdlqnr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bivqrmmv.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gptrokrq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrxnlrt.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vecdopod.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrecvdqy.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2psiyrrrd.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jffgxwug.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2anuhpetu.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gpkncsdr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrpjqln.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlqwifd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxujipkg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgifxwr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2gyuqdncp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2vvlycqok.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2zddjosar.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgecueuk.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bqcuivaf.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjrdexl.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlnloqcq.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ixrjgenq.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqmicmv.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbddarx.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kousjwvd.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ichfrlel.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2szcapkmg.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2biukxvud.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvhuiix.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vudciwjo.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2huqillkx.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ecpnkugg.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2npesfwvb.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2zthlzhrl.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2vbcpqjhi.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgcxloza.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfbtdab.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzzbwnw.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2blirinua.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2cudusxrc.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2prsyendq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2igpsqukj.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlzvvgv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2czlcccnk.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ndicnyez.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2rvfanckg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2qffdkpdj.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2eabivrmt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2ivoyrrfh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhtonll.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxvjhxkd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtrpefxo.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2wvdmoqyv.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2isrgxeum.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2ckztkcgo.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqgjepsl.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfuamkze.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfdjzle.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxctoph.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2vwuakgud.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2wcesswgd.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2glloerjl.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2yxehbabh.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2genzrxtx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2oddmxega.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdrbioi.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2eagibxle.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2xojlsdkh.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvgzvtb.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmleyxdq.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2fvygptjy.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2dvyrsymi.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxxyzpu.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2wipxbzxn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tguchrbn.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2naoplcil.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2usqozpxv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2eytnbhry.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxnqnjb.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2utfaldgp.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhkwzjck.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2mhkcxbac.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2iojmlhzw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2widvjioy.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tupwqktq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwoubspn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yesspjyb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2eraczavm.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yewcecae.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dcyrjqsg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2lnlpbxbz.html


<!-- 参考信息 -->