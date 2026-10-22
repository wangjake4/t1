代发 wailian999

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2phtqdqdk.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2xjqezooy.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccuhfzig.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fffsikar.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpvjawc.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqtupdn.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2dlatjgqd.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2ujtbcebj.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vhiqpwmx.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbtahdv.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vayhekcj.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpstdnrp.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jubnjxia.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2znlufwze.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2eoduywbz.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2cljwqgol.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2spegzjph.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2qghhkvco.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2oyxgwrdb.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvctujp.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmaixohm.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hadzcvft.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lohjwayw.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2itjailzp.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqblyooc.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwfdiji.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvvyfdl.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2nmsosaza.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2leowdpfd.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2skfsqzjt.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2uhahasbo.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgufauf.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ptslcbna.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2hvsqpylt.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2bjabjrlv.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ieygqhgj.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2efopfjnr.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2arkycogw.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2cemayxjy.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzpkdgtg.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2xggwqmvh.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2xesokxkh.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgkdmex.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2icozjxnb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2czllwnsc.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2khzsltia.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kmnmvijj.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dohiuzll.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2bbqpdopd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zphprjhp.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2louefolx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejlmbpbn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2exqfsuqd.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrxzbdm.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgodyhu.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vavilbum.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nokbtxko.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2yicdwsvo.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctihjemx.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2trbascys.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2apiiemxg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2coyhdxqr.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2syyragvz.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2megifnuc.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2epyrreig.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aexzhgbi.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcpwcvzu.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wznvzbpp.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahuhawqc.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcirjqpi.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxkjgmy.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxckxmab.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eclvvaze.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2dxnxbsfz.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2domoiiyd.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpozivw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nanviken.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aewrrqfd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2alzvdxqx.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2oxobkjot.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jicwkigc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzkfosu.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvikarm.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdkzaux.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2zxruvubk.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2bajstsnk.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzwypvc.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2ozthhehr.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2baudbvqt.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2jyklpivz.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2texnrpvj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2vybxnjvu.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2jblmsmjs.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2ictogozx.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzhlqfp.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfmswwo.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2gscswesz.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqadxamr.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2uerasbnu.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwiozyue.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwurdfh.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2iwroedcj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2blndncdn.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfytsiha.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2puwwgtdk.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2kortrthk.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xwoerxxt.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2rxcwmwqh.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2kosfgruy.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2bownsqxw.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2mhftmrvx.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2kavfdoqw.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmzvwlz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwcpeyia.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbzbwcw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2owqdfcav.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcofbywv.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vuixpgmo.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tiigacfu.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2syhjcrjf.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2siwbgjen.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2schpnuje.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwwvoqz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2wyuydwhj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2egxyuyva.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvdjgko.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eegrjveu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zanjlslj.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhwcqey.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2yndfbvit.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2srznxzbd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2xufodkxi.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2paihnqys.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2dekggmuk.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrlmdtk.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2tuprjiqy.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2wgpyhwla.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2mxdousty.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2sswnvzss.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2iyozpwaf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ybumtsii.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2nqyqbtpn.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2knkisspq.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2clwtvrgq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2odznwqzj.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2drowweig.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2ariiexjg.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2wijtxeee.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2cgsrvvwx.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2zfuhgspw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgrtlvp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2hasqtnln.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2lumuclgk.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2hjtottzf.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ykuoloso.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2rfponhjv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2grvidcqu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lneleyoo.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2dtgyvyok.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yojnspvj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbvrkbo.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2bfqzekwx.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2bgrvjyfu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2smbujygs.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdbjtee.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2zkjrfhjz.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjukvkn.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2tyeyhuvw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbsrlhl.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxsfdez.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfqhixf.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwcfoky.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2gsxktkdh.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2erxtdygo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2jzlodtba.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2nekclvym.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vwoutktk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uxquszik.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2gvnoikhq.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2zzsupzrg.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpmvypv.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhyilqeg.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2neqesuux.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2zsmxnofb.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnxcmfl.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqrxhrb.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ryoujgfm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvovijy.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2vzencjoq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2crpinmuj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vghrqidj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mpnjppfd.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2xvluwtlf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2inrjgzjl.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhlgflr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkjobsl.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvycnoj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ittqljcp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgekyfj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2obrvophl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2hanjknuz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzcdwrq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsirhgc.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2rzntuyeo.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2wlloicjy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2vaksapuw.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bviszdoa.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjehythw.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylybldwb.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qthtiplm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2fueogbzy.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtcmvmsc.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2whqjuhta.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnocdpq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmjwovv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2sdhsefgb.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdpxplk.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnuchjnw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2zktrndsm.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjeelngp.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnzjvtf.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtwsypt.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmsybll.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxlbeqbk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxqlkzw.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmezzqb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2enmwxpds.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpefzlrm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2piufzuwq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtlnxmp.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2anhimrgf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2efvnxjza.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxcyoehp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdowgtie.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqveyun.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2svsyasln.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2nrnbvfrv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlqituw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdnmhuc.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2auajdjvd.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlexncsm.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jegoxvyw.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2giwmiosc.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ssitjhmi.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqwvric.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yecgwjvv.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwnxuqe.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2vboidvbe.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rscmwfyh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2plrvqrvo.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqajcntw.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2apakqliq.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkeuedwn.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tijdfyvv.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgtycek.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrkmywa.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmeeklb.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fyssgsuo.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2aemzxvxq.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxxlxvw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2esfcdofb.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2jelshkoi.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ghudtqem.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzcbyttj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2potshjly.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zzecduus.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2tznavfww.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2pbfuhiuw.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2iavvssjb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2nrofcpci.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogdlxyxx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2olvfrpnb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsxuiqvs.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2luxyawbo.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2ymtnynfz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2ncsswazj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjzpmng.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfzmlxo.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgfvffr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2xviibeoq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqlidya.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2stpdufvn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2prdvvcfl.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2lmuzptpb.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wucpmjet.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2rsqkatuj.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2oetvefbb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2ozfqikkb.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2iseszjjq.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqtuvmw.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2azynbtvv.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2rovhfmqg.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2mipdrauq.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2dazvszqq.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmvrmmi.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdtrydp.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdoykezg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqfntkgv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2wgageaww.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdrgzvk.html


<!-- 参考信息 -->