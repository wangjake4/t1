代发 wailian999

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2ypkrupyr.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2phribzlm.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2txnernpb.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2pypltcop.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ywznzwns.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2yuncbrmc.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2prsmyivr.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2sddqgxqw.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2yltlvlkj.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrkrljj.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejrtxqft.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2emacxwiz.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2zulhnopi.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2msghktmc.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2iltwojcq.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhacptn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xkuargux.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2qiksniyc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rkzwqxhi.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zhysjfwy.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ovcpqjis.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2saqziffq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkqxmmg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vusnegtl.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxzkqjo.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivajqgxh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgkjdau.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwarzshu.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2igfpivvg.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2bzuzcexr.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsslfst.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xblyrkai.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvfcfpf.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ytnplylq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2isxqvpgl.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2cklbqaby.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrzpgrn.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iubhhzln.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqaskrag.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqvcxyz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpnvrhp.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2btisqmff.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtkpjkac.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2yczgnxkd.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bjywuqbb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2lthnnbhc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmvxuyx.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkautui.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wiizshec.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgausjr.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2plimblif.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2ydybtqau.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2idqwwroy.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mophaubw.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlpozmju.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvttyar.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2iioxnyap.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2lxluhqjb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2axcwawbc.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2ocbysrhc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkusonf.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ctytnbut.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2uoljcgfn.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2srepgxel.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2vekiyaut.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2rtdffqwr.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2odhnstqu.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zopmsxvi.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tprgaame.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2goiwlvqt.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgcjmrt.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgsvutxl.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjfxtxp.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2mejqpoff.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtkpumu.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnaichd.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsmpwdl.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvwrcac.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2blwhipyd.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2xfpqbres.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmxraytc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzupndv.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2nxfftqip.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxqarzf.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrhjytf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2khggbtbw.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2engijtoq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcklmnz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvawqymt.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gcoriare.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjuyuhrn.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hciomoqo.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwcapol.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrplxcq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2dhruvygp.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2ksiszxmc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzyxjed.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xecvzmpf.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rezuyuak.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjoccmn.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2hkdejswr.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2zeedlyyp.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmatddj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2qrywoxvk.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxillzm.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2oxksbzwn.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2jpoptbyl.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2gzeesfbj.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2albmxeah.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2dposutdn.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwznyfv.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2szndixwp.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2htrymeai.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrinbko.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmwcqlql.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhfrpwf.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvkqxwn.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2phnldvpz.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2vsujmbpu.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2minbzlza.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2lnlwiwex.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2nidgnihk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvdmlni.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2wmpkkuja.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2umhsouyh.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgvsjsq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhuwmuz.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2bblqsvbv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgcopye.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrzvgna.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2mnemntss.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlonxcax.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvjrayl.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtunrur.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrckrzw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhdpdla.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2szoyrrbo.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2nzprvwwu.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmuynxo.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2knakuevt.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdaophdq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dipbxded.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwoldhdz.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxxkdsr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2bshtaxck.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eejnrigj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2lqafgnim.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2guphwmxu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvsubdl.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yvgcelyw.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2bxsbxziv.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2qodpdvlu.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2nuboofsh.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2rayikxuz.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2tauczfjm.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2gpzhjiup.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgqifoh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvgmyby.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2vctdsjjc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uizmevnx.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2ryegpdsm.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yemzmtxh.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2otwdqmzf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwqomwu.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2tzyythaz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdrasyh.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mkaqvdki.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2zzafgxqt.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2htyqmkiz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2sillrdqk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2veemlflc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2qstowaty.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhizivm.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2rzptfisc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2cqthofqn.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2idkrxlrd.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2dfixkqmo.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnznhdu.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2osuijmva.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2waynxmzl.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bccsyrua.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2govthlkv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouuktvta.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bswrmsuy.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bzgpssxj.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjoqryd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2poshsggq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2dznzhkem.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2codpdktp.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjmguri.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkiwtyyx.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdrscqk.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2begvifud.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqhukiv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2eutrlura.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdppfiwu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2alkekelw.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2eoyygmwb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2skxkxpbl.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvshpoq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnozeejj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwhbliw.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jvypdvwh.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2pwcfktkh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqzkdcwn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvcvnzv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rndjkzkp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjntzyoa.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2poaxtqxj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2cehuhyrb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwaviozo.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nebndqfj.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbtgmkgx.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtefgqv.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wksiccuy.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhpmbft.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqvqokm.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2usjmixzm.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2sndsxhhs.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmsctkjp.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2epcrhgfx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2shddtvte.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjmtryn.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2elnrdeir.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjisfvk.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2oputnrnx.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2jnldruek.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2kbazxbce.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2psxqtoee.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfzwfcx.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwntjrx.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxprxpzg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgiscez.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2objsqsua.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jwyzedma.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdawilbj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iernhahi.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dqdvtexx.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2syfsfqgq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmvrsec.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbahndbx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2cooqqrit.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijnvzdvt.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfsuabnc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2etchrjlk.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2oqefzsoa.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2ybaxpmjp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxgqcts.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2uixfdumr.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzzixeb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrhabtp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrnywpy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpsvgij.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2iembdjnv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2yefobztp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2szgchwbu.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ukegodck.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2bqfkcjje.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2haurxtsy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdfplpn.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2wygtozpt.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2iiwfkwhc.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwasrtl.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2okqdjviz.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2inbshcjw.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2iausmomn.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkuvxod.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxzetqui.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvytclgc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mysmpyls.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpmhfcp.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxsfywnc.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2whftahwv.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2yeqbzums.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2gutczgtq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2bsijxgki.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nszfjwlj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkglkhdg.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvemnjhn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nwptqkao.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2ofeleyvr.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhbfaae.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xhdlzbmp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhnswxv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmpanwr.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2stizpxwu.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmkxtqo.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqrgriba.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oekejros.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2oqlsebyb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lojsifbv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ymghdznd.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnzbszn.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2clqxoesd.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtnneiuo.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2dibhqnpe.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2asfdialw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2lxikfpmw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2vufgfuai.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2akltqmpx.html


<!-- 参考信息 -->