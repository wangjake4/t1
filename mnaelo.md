代发 wailian999

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjywukg.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2xkudttql.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2tdobsgvc.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpsiavh.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2wgeuzaga.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcymllw.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ngxphtlc.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2bjinqodz.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhbygyu.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsskmtqx.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2otcwtkrb.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrcjwpl.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjpdlkk.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2raufdzlu.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2ljtsafrw.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmypbzat.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2igmduzzf.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfmnxya.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cvucwwze.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xcngejej.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2etxbyltm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgykswvf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gldqeord.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbgvsgbo.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2czkyguhp.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvfnmyex.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnxkaxv.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjboxtag.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhejeas.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfpjror.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2krizsork.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqoaile.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smvzdxbu.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmbhcjx.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2odnauahz.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2mxqdqesh.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2prlqipbj.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tkieblgu.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2hplbsyje.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxmdhpso.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eazmonuz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2axvpnryk.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdbhoys.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkzywtmz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvfnhif.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxdvntg.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvjstdy.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mutagmmn.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2poefjomb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lxobarhe.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxeskxj.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2ftaasogs.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxnchsz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtlhmcmi.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ithnqirn.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2xeakiubb.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdesuju.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2attwgznl.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxybahb.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxikmsh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2qpaamepg.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2krwwhuor.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcwtvxg.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdvnszv.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxvjryc.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2kojcpxmm.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxqzppg.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmajfihg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zieutawx.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2gefzlmtk.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2dugkajqx.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcigetx.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvcskgg.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2nywbtwzu.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywocttef.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygccqjkm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2cehmcgaa.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlyxofc.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2brviehht.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2bwrzfime.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfecyyp.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2unefnfcf.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlkkceu.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2qbrlxbfe.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzebooq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyeuuony.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jedkkzkp.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdrtjlc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxlctlv.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xwnisxbi.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmqrjag.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtmmjfa.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pezefwhd.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtzqevam.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2sjasvafr.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2atumlhck.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2thzljcjy.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2siplayfs.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2txbmmtch.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zotwulzz.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2nguidkxj.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbsrbmh.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2kqlegbyz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqklmit.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2dqontzik.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2miihyita.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2icmnwalj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2zoofhlcy.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ridrqnsu.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtlmwba.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbzbvzs.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdigkoyu.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2vgsihniw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqlzvtd.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgqwavi.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2rgkgaqgc.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxydgev.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbjtvjh.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2dsuyhgun.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwmqzln.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2euuclwji.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmfyfhl.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2pdabqfhn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2mearieou.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2fwlyrsoo.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2orjhspmg.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgxnhgi.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2rgasdupl.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2sjfzyxye.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkeycgfx.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2gesfcpni.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zshedzwa.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jinemsmi.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2sitbvznl.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2xcoborqf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2uouccnin.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2orzorzwv.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhkkddp.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2tryctbws.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2cartzqzk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cullvgra.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdyrwvcj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqnehnma.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2voeycnje.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2frgxflde.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jglazkcu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2qnswqgzm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlyyekp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vfoktnbn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2heuztaxc.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2badclprq.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2stcuropf.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2khcanfwf.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydwuiiiv.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzckzig.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkgjvuz.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2pmrjliob.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2pruihoti.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2umjxlvhm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tojoxfuf.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfojjdf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yewdelvm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rftysppj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zgukhycz.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjfooje.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpfjmyn.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkjywon.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2fnisdoun.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2whiqwmfb.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2rirjrxmi.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjbqshr.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2mozfrbog.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2jytcyorr.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2kffwpipq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwsxchm.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2gpptjite.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2excaeayy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbbivcot.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2byaeeayb.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2imojbclg.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2phutbxtz.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2atwbqilf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2joqifcbx.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2muedjvfh.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vsutnfij.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbjfuxa.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ighlmunp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzlmorg.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqrkecra.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xszgfmzy.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtobgja.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2cokanygk.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbvrmcc.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pttukxbt.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmvrmdq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqnhcpo.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzkieeq.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmujvhxe.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kykbjmgp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2szzlfgak.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwlwrjq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdihmis.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jutfgrxm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfknrod.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2iiczakvx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnumgdwm.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckaeyjpl.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2feqxwwjc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmdeelq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2azrxgspg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxnxpaby.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmwytzg.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhuvuedr.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2epfjvzng.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xobemqln.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bupsyafy.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2bqangfsl.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkozokb.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmygofu.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2waqbregv.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvujyjn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqbahyh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxamlrg.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvaevof.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkktglcm.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpoxolko.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2gbnmbyxr.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2gqemqzgh.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uokvwxxj.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nndmrrtq.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxaesfi.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhcfswzy.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2apzpvglh.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2cwjxsgdg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nugiferb.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqdbjish.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kiwhstqe.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2muglvsan.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2ctsntqjj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxhpsrh.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfensrqp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2feubhtrl.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddijmrnl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2efrwvhkr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nixhxsow.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2dnyspmul.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzjiwrq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdjtqhk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kptybdnj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2epzzlfgo.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdubrlo.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2azplsenq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2uibhhevz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2dacvoqxs.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrrtasky.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhcsavb.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bizmofvc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2lgyinplk.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdslvspy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2tagnovos.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2dkttczgp.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvedbsxf.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2epmsxtni.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2lwovorfi.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2enxcauof.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqwxcmv.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2xyztbhvr.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbkylqi.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2izgqjmvk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdddjrn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2siecivnr.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndomghat.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrtnmczj.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqeyigm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2azhwvqad.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2sotphtsb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjjonek.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzmehhv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2udgbjxim.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xkosglfm.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2bektdmal.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbozjncw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rluoojgf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnpvuby.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zykpsuba.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywrzshah.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pepoxrft.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kypjozkm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2neapuatg.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vqlqpuhi.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvqisro.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2svycskis.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2baczctwi.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2gxukguva.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2eitodsga.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2liqlpjxp.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2dktmehjb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2ujatsimb.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2barcbdhq.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpvhkjn.html


<!-- 参考信息 -->