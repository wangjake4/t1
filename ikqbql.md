代发 wailian999

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhswfacz.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2eomekcod.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2nidnwiwg.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmkaxks.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tktkrgzt.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ekkhella.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oeyajszi.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2seopaats.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2uywxvect.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbbqexxd.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2elduflnh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjqppnv.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqwoeae.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmjvbaj.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmcqzpj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2urweybfx.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfteawf.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2gvhwmsel.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxtqaqc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpsihlsd.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqikkpy.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2uticzazq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2glyzzstx.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2hrlblrmi.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xebppgyd.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wtsbbdvz.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2adtfrjxw.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2shubuwul.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2weanfzbp.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jluqhydv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2orwavhew.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2fedwacpg.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2feuxbgnl.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2arwmuloa.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rvrdebiz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgtwcaan.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yigoyobn.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhqxelg.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2luscglus.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2nzosbfou.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ilyhwbwt.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hoexoyon.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hejevtoz.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2sucgqhfx.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2lkihyysa.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2paeydmfz.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2jpohjieu.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2kjuvfpoj.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2tcdaqiqw.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2gvufnbdh.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2hxohuvsi.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2cpybmpji.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2fakhotgq.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2xwaksphy.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2thzykgxn.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucywpgji.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2naizfzev.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2oitqwmjm.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrswkmbk.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkrapsp.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2izhabscf.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2joggzwue.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkfbcdjb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2popqcetz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfpvoqhd.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyktlexc.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zkourrvv.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2lubkwofh.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbtzaycd.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2oasjfivw.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2dagyaeqj.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2wygtkesa.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbiwnhpi.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtdvlveq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnuzqqtp.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2kbecdmbn.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzaeirl.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrtcymc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2unsrwvmn.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zdpkzuob.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2shrbgpba.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2njlgmmev.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2wbvkwjjf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2sdlblwaw.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sychjfkl.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhrtypo.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2anwujzco.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftprhxyr.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2zqipxkyz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgazjqx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2cpazuqad.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2rkpajosc.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2vzrrsilu.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ufgedtlj.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2aejhoizo.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2haanpqps.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2sbrxcwrr.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxunnxt.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2epumazln.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfolqxhi.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2zekewqwh.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwdkhuf.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfznlwvv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2zpwukppn.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2zkrbnrnn.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjyqsopg.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpdvgna.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2uczgjajm.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2oohgbmig.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ebanklld.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2hnfkzhmi.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2nmgsfqrt.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2pqylaznn.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2gddfhbnr.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2awjhvsxw.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2sekmohyp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2fcctuaoj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lodtrmyw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzmdvrx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjultivz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hukxtkpe.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzzouht.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzinqxs.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdinvney.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bdzytyxf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2zexdgkvy.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2yekzuqus.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2fzqinpym.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzcenpj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnsibme.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfpsovbp.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcfhbhv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkmaqsp.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mujsftoa.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2gyyybmgj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjufunfe.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jhnqfwvs.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2frhjcuma.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2raoxapll.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2fehagdwv.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2atmrbege.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjwxjgv.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2wypywjzp.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2kacselnx.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2iqllmhyo.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbrgpez.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmimtqi.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2krfohqke.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2tewldoge.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwvtxix.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmmlphd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lmcclhwq.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcnzrid.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2brxawvjb.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bzkbyuua.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkhfkpw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2yeerhmge.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2icknkpyv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2madztebm.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbrphku.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2plqfsdwu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2vmgykdjc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2irlytlgi.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2wleolhat.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2aahqtyyy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebywxnyf.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdpgvaub.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hytskjsc.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrfjxxel.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrquicrf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnczgjjc.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnghwdy.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzgtqen.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbppzql.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjbjpbn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2iocrzkrv.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfnzsqgn.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2sutfltet.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2heyyrhtk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2whlyprkl.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrkhmww.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2inulspux.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohsfjjwk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzocxbjh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfkzpxh.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2njxeykcd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2phkrnifu.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwzayjsm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2srnzibwm.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fluitcbv.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jlascoqo.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2fvscuhwq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbloxcgx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2fannsdxt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2czwtomeb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvrtcsa.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqyftic.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2baadfufl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2kaathnpc.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqlwdrx.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpzskxk.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxefisx.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2pjaydbxp.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2uhzywzgt.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2bikggrhg.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvujhrth.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2iynflbqv.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmfntrjv.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xajqaetq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwbmcvh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2evjjjnkr.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbukzbva.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvsmhuti.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcyicbjg.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2kgzcsrat.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqpvcug.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymycdmon.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vhwbsnir.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2osslwpcc.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkunntmi.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdoucqhu.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2gfdchvil.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2sftphpiy.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfgbqas.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2djyhlnjb.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhzmuyh.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2aacjlimb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2xsveddon.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckeollhs.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsswawz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2vuipnkat.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2bndrmsin.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2agnujxbk.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtowqgq.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2mfsvmsta.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2gacrcmed.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhsvxcf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2duxherzz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2figgsols.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvpqljf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqlaflo.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjglvnv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2daxdrocp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2plxspdlr.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlubycw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2cshuxyxn.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewwzzklw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2ngacjgik.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgkocoh.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2glsybohb.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqnfjaxi.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2eahwbwxs.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2eninqpbp.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2xmaiukns.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2tvecvqlt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqlatura.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mervhnil.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2phnnpoaa.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkzzdeq.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cltuemjf.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ellutoqm.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2qsawzemz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2xsuaunhv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hopkgcom.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbphczyg.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wleuclge.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdygjzlk.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgumonj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjdtgbb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgytzpfp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hoqxjpex.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2isjkjaxc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2itblambm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2casfeosx.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtacahnx.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2urlfkgdi.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lddradwg.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lflywjtk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2szzkfdfx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2whiypzxw.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2amxgceqd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2koqdjhqm.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbnycin.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2uwakyrvz.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxbbpau.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2lylqxxle.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2uuhsceqe.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2craezfwb.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2omjaajri.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2weaworcn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2msqlrvee.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwdnamh.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdobpms.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcctbwac.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2vptmljcv.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzmsywi.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxtzwzl.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2gslmqpsd.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2utkcoaai.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2azcbaags.html


<!-- 参考信息 -->