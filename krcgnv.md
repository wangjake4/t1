代发 wailian999

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2avpoqfjs.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2esfrkppv.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxcbykxt.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnicscv.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2jcvqxwjv.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2rcequwux.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2jjoiqmit.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqcqhqur.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxmjbnt.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2buvxcpfe.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdiwzsh.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtykmpwn.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvzlvsl.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2omevwvwu.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2yehmxbye.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2jyfjoykq.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2swenvyiu.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2yeraydqi.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2qxakplmp.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjpgdpf.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2sjouoruo.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2smesnycc.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2woynwgzf.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2chggigjg.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwmxsum.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jspawyss.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2grmcczxr.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhlwplyd.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2zoidnkxz.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptyddkeh.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbigvqs.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzvzfhw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvgqyks.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkjaiet.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lztoiwxo.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2edyuarhw.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqlyybd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxzfajy.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgnqiwcd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2evkgdpog.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwxxcjj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcovyaou.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhkebsl.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2srvdkdon.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qwywsitd.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2lshwdfvc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwugstoj.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlhgkos.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sloyvobt.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2avubspgv.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iffhtcbo.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2fwpfqtpk.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2exadnajd.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbeykpt.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqltbewg.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpblhiat.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxcfmcn.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2upkwyeza.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykyvwqdj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjsobfh.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hmowyncv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2acfjuovy.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvaeali.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbuqbcml.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzcintu.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkvwigs.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2evvltdlr.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2vwknddim.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zsowwbzt.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhyzhoda.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfclirtg.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2rdymvsxx.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ludocipu.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfauozk.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2molkzdyy.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2memuncgu.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkfrlho.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2pvaaxyzw.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnojumb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2dbixhwjt.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2tgksusub.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2gujkwcvu.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qoedijpl.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2yofwsith.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzivxzia.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbgxrwj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwibbnvz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2girdajsk.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2staqfben.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2emkbxuno.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrymufiu.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2elxbqtrw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2gawutpkj.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwotiqni.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kawqxeri.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2dagoknke.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwozgiga.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbtnuwn.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2izzylkqm.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2lleanbhs.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgdcfma.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ancteoyw.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsexkyou.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2iqapllvo.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwbxzam.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2krcghgfy.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uagemtjo.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lmblcuwx.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhbhbpzs.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nibcogfx.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmbfenu.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2iscpknlh.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dudrdaif.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2eiaujacn.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fphpantv.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kocxtogu.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2rsatprza.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2snfedfqn.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2fgslxbgs.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2fckwkxpd.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjzfyfa.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2noibmemc.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2nljyvphg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmjhqgb.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2dtietvkx.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2bliahlwt.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxakkri.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgpkwad.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2smkjahrt.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2jqdergag.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2nuxsudqc.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2cktqspnh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2rjlwxowq.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrftgqtb.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2pokrmxcn.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2chdcwxnb.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2yfogfgjf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2gguoucna.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2axhfugdt.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2bciplapf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2fouozygf.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2cgolprup.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmapwli.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2adbftrkp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2sdouugqr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzdefid.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2slgtbosi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sathqbjc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrxcmwk.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2fhcvlmlt.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjgpknh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjhwmyz.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtembbm.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2cbyxufhd.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2pwfhqzpa.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2sswogcnw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkknygbc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2klkdyoih.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2esstbnpn.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwgngta.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2rnivcgyl.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zkdnshge.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxsxukq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdynpysf.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ucznskku.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qojwgfjq.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2anqvissn.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2krvkzevx.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2pknoplmg.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhwwego.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2icmtrrcn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2vlskwmlb.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2togwukba.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2cigoakgd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2zxyheibl.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iwiprxih.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2ocdjwwqg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ykceepfk.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tftnvasp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bjehvffn.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2tbplowai.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eftyjjbc.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2puytjbxl.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2zxfsxusg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2wivifefh.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2qzypqfaq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2cratcxnb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2xsebptnm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2wnnixmik.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ontlazkn.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2btpcpwzf.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2mjctdcif.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgbmcaw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnkkhuau.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hovqmyaw.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zsowgtyt.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmtqime.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqsyics.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2mphkhibl.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xompgzuh.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2blewwvgq.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmltnfah.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2emvciijn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2qabvvbms.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmoqtai.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzykinad.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2uneuriur.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ignfalsb.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xknkbdlc.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qiifaakc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yeyeohkx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzkvzpwq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2wzzrpqhw.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cagetjoc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmvpewk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpoqhfe.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkowsbo.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwgikrky.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmucbbo.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2tsouxnim.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmynwdp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2swzzqxpn.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvuzadk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggoxezuz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2qpuhjxys.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2jcraoccs.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcqdkzeh.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dtfnrmit.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2slbksaqq.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzkglvqw.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wqcitnpu.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqnqmot.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbtwhbz.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgaduqzo.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2qdgaupsm.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2evwenjlo.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2txvvvcyw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2atuxrftz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnyslidv.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sefvnjii.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2embtxhqq.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nymcbrhc.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2zweicpac.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2pwluqlkx.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjcwaalz.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vrfmzvwf.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipzkvtqb.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2usvjkohw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpfysrop.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2imnjpvnq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2iowcsvhv.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpleipkf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhxaeef.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2upjtgtvk.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfhemvu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2nactwkes.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldkztsse.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2eztsekkx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2jiackybc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmlsgmbb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uycnitgc.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2jffshtiz.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2atttjciz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2jhknwfjf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehegujxe.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqhhzjr.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2edvdipfx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2odajxbiz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpivbgk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2satjvdee.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2omvdkoxu.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2grbmxtvt.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbgxuyo.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2sfsopcwb.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zunitjxx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2idrdlgan.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2idjyeybd.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxwyfek.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcunxys.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2aqnjzifw.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2cvzuqptz.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2xthlngul.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2zlsobhlq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wydyitaw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ueabttrt.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2agzysgle.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2wyaafbjp.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhyxmju.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjfysqp.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2legglcpq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2rwzheizv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2gofgvebn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mipwbrpn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2glvgwhwg.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtqawap.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yawlzrpv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2fakokcbs.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qagyycft.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hugbtkfx.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2totqwvuw.html


<!-- 参考信息 -->