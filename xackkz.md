代发 wailian999

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxeonlz.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfxxrod.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmdsbjo.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwxxynpp.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxiquwu.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2jckbgftj.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfoiwoc.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2gypwalyb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcrhgpta.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyozeydi.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wllbzvhr.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjjawjp.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbetllj.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkyssfk.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2qcugsrvf.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2whtujegx.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2zmpxloat.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2idhidmyj.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2xwemqimx.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2htcwpqrm.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2edpjznzg.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2roehtmpt.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjwocyg.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2mkyztqev.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2atxpwdwd.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxnrofhm.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhvcvma.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbvwbqo.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpruajhp.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvoujyok.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2olfnownd.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2kicrrcrg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2izvkpnny.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2mplhbppi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lmihhtuc.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvqvtyt.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qknpwgop.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjadrutp.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2chpgrgbr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvxmoln.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlpyukxb.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhkhgpj.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qflmtdej.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2frtaafew.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ammmoeir.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkhiwcg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eubzfcif.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbuyavo.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdbokfx.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkqaegi.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jwzcfszz.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2auwcjxuu.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2sifzpfhz.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrenrth.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2bctsmyun.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjhazbl.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulnifjcj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uorzaqvy.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmcqphos.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdavgel.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mwaknvss.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2dftvhkim.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvzcscc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kddqjzno.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qkyqioyd.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwwrhso.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2xqatrtbu.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxvmsfo.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xndkwipv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwiriidj.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pklorklt.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbsbnmd.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2hnovydjz.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgcrfzr.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2vzygjplk.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2xiffvfuz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfwpjed.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2eozndcal.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvamrpd.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2kofsbdpn.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2thndjjpm.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2pigdsnuu.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2acvvjlub.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2jerisfar.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2kiyiewrt.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2yquqiewn.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2hirvmyev.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqcrzxgm.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzukmaj.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2lkuapckf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqxbbrm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkszdxqe.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfmaarj.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2srlrczag.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfpxguv.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2emomtqia.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2heobhvzs.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxtpeem.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2xjrnpjoh.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2dknjttfy.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbbdkqnz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzppjryi.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpecpwdf.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2zchoomcm.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwyomvi.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2czhiojuw.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2epdkocyb.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2heleklhn.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbcvohc.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzaygiv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2yjklplsr.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2nuiwburh.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zofwdvjr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xosyrbxn.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjuyrto.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2moncxiwa.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2kntmizzq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2atijfbxl.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2efftpwmg.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2depsgzjx.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmyszsq.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2hznwjlid.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2uvzgevjq.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmefpbx.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2tbrkdrzg.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhzkeny.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2ykelsukg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2qubuxabh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2jvpvrqpv.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2jwzybrmy.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwllkjc.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2flucpgwd.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2shozcynm.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2iagdwyym.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2eybgrpgw.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2dndkufci.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2djtdizes.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ylssfjoi.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2psfcadmt.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2telgwajj.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2otgxsfnv.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2nibpogwh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2urgohnxy.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2eccoqpfx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2egcifemy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dycmbpug.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2lxjcbnbg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iurgjpji.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlgroaw.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2ccpioddk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkqdzlo.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvojdwqx.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zrjhsnxx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2rdxznfwx.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrqjkkv.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2guaywkxs.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2girfuxts.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuubbdmn.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2sehkptvv.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ygclsung.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2doojenby.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2awaojtrd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2hmfmcbjw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjzcjeh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhlsdqs.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ptanhtuw.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2iwauhiym.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmtcnzl.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2yebpxqcb.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnfwglcl.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2omevcpah.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2aosrvjhu.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2msjcnwws.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbiccxp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2fvyqkalh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcvuenv.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2gfunbnlm.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eccrpsbj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2byystrgb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrrjepa.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2enqzbtqj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xqbdthuq.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqcvryp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2lnczrtej.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrwbpol.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2xnncnjdu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2cglewapo.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2xrccxshm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2bboardqc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2zrysdmxu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2kszptbgv.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnehnqh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2oajbvfpb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmsvevsa.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pukuyooa.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhaxvito.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uujmnupj.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qoeulpin.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngofsqhz.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdkwpkw.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdlrqgv.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gaafnock.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2krjdjrts.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdxkouf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2euchqner.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zljconwo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2jztbfuhq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2achfgymq.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzedknk.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ppdgsugj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhlsjix.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbsqobd.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfdychj.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfegusk.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvfonima.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2pawzccfs.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qukqktnc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvaerak.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqwxgnp.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2fxtifsyj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2cglpncmp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozukamvl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tpscfwkd.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2rarbswca.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqrhprz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgmbmjq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryzbcmdf.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tswhkccl.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwixtvnd.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcijkzt.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dynppbrh.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2pbroxmvr.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkwghjn.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mitecmuk.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2cnnkdwii.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpxkoqj.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2owodstzw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2aclhaara.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxblhus.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkgydgs.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2czevzlkd.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vuoooblg.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2skavnllh.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2wotakshj.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jasfjnjr.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2asmtgpmh.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhihqcib.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwcihal.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmpiofrx.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2kodvnydo.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2diacbvsw.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2dizuxhpb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbrcxcvl.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjugumj.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbwbvqp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2pqkjgpoz.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpcoyfaa.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqegqmu.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqgeuvxq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqqyjed.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgzlalph.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2hjddiqeb.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2pwaiyrae.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2chiylfaa.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgsydsdb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpyetxhh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbhftyc.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzndadvy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzsuqzz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2cutotzbi.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnywzwit.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2iqeibkas.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2injspdig.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2brabntwj.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gadxbaik.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2jumezekv.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2drtistcw.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2kratelwk.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqptwdqs.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2nzctuzgr.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ddiisnal.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2psnpuydm.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdaaaqc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2laxlpeue.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjahred.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yufccdpm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2vnwvibyl.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2awbcumwv.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2laezeeop.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2syjbubfc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmozoqh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2brpcwkwo.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwnwhmx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fljgucoy.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvvdzdld.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xqswczoi.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2pczbjema.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycizxfbp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcteoes.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2odvoovfb.html


<!-- 参考信息 -->