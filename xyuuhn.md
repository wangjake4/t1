代发 wailian999

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2woftinyi.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqvubjy.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2drtsjnlu.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkqylrf.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2fkycwihs.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjudgpu.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxtovcv.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpurzkm.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcpocey.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvqftfr.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwejbmk.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvirtbe.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hegitlnz.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2csahkpva.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2zykcohpi.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2ooyjarvl.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2njzlhgxt.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtsterk.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdilxon.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2cnctldty.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2felbztpt.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2vroixgmx.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2kglorjec.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2cyxrrppl.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2wpimnkzd.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyaozcsx.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxkhcmaq.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnkqdcs.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjnmhefn.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqcswpa.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2tbyzapyt.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2oewwctxo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pamabzyi.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2vmmrrvvb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2smklcrgr.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzwlquu.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ahxavszq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfgqpcf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxjefeg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndofrirq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsfonotq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzljnnp.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xvzyfulm.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2erjilsho.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xmvgioqk.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrhseqh.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pprnwsdy.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kppbemgf.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqrydfu.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2wexccpmc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eupvawqd.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2kttxrjja.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjlorfs.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nvygiqcc.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgvjaqqz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2azmyaxdx.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbosbjpo.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqeiufds.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjxmbvf.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrmlhlw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvcoakc.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtfwdyj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrvgvab.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrvxieg.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2srsmenfx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjdqxjm.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2yzopadzn.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2pfllkoxb.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgysbbe.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sshrbirp.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkblzar.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtbbalu.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgbrcdw.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2wbccwyud.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2wydhesva.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgufmuj.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnrozvz.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2jdazzrch.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2wjywommp.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2nwnhapac.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2trptchrt.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2ipupqxtw.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwzpecfb.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwaabskq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxlkuyef.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wttwnder.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhntdwy.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2rngsyiel.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvswomnq.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhmvtfy.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqnbvzro.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2afksjxvz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqytmtaj.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbrowwl.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2btyhccxf.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzvtzpw.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2loodbmju.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2vjgotqin.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgcmiph.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2okbzijak.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfoiqhjt.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2duusqohv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqkavfdk.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2upmsxupj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxhbpqu.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2watrqzzx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcatjbmr.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qznwvthv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgdraizo.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sufwexdf.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwbopvk.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2oictspju.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rslarnco.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtaskggz.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjecsqk.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhehudlc.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2wrevxbki.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwwllfy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2eepgqklw.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2zabqzpqk.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ehuojnoa.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2cqoafsif.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2irxwezdn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2ftsjgvhy.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ufcfibbm.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2lzetsyeo.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrlfjjb.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2eavvyenl.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhubrxy.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2bjttjxdx.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhzszpy.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2xgymdqsv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqxsqax.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgktgksq.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2mlpzyzwg.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdcasdc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2lhnpejnj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2vldljfrr.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ljgkxwxq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmbfmwp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2mmoaovfy.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2sanwtcyg.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2shmjungf.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2qapwjlfi.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ooltbpni.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqnlrwb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2srpcdpof.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxoaqiwd.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2magfisik.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2dqskvbhs.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2kiimrutf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpflomrv.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2buyczyrb.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2behppoyp.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2guyduhao.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2mzosfpyu.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mljlygci.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhndqzjt.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsoygvlm.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ospdxsdz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2pviuizbx.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2unqtznwp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2eknbyhjo.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2iloijofs.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tgslexqs.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2slqalvkh.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwjzaen.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2cdnuhthr.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqqwqvu.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2xuexgcnu.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2shzrapek.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmnmtxz.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2apzyxxom.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2vexmpapu.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2cnnapdko.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2trtlkhqk.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2qxybrmly.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yjuxgvhc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2joezpqti.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqlgsbp.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhtgnke.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqeinys.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfnkxhk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmwnbbc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2rekexuud.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2oppqqinp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2sabxkart.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2ccuytumz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2xurxlbjh.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxjrbqx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2hgaygvgt.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2mkueqnds.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2snnmwwqn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2btqosrms.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxicquv.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvvgdgr.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zaarvsqj.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2oylzjuta.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewusfdzq.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbeqamdt.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqbrxqj.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lparybre.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdpwrou.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxvmhpq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdcmwfi.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfpgifrb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywucticc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvnzscfe.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbhaakl.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2toqbqwqp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsicgdqi.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzuedfy.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2pcppbavo.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjuanfzv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tywcflci.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqqmkcq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2byosqdae.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdpdticu.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2oimfpadz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2slmspztj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgahwxs.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzlowcyb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkeutnnb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymkqiqdr.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2nadjpfsk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2shbogtaa.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2tuggtfpu.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2milavfsp.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbyupyzs.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmsttrvl.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ejlwuzej.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2soydtkkz.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2zytqbges.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldkykufs.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2muxdhdnn.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrftkfs.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2znnzaqkd.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2vwksmvtu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfvrskdg.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjxviuc.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhidnhvx.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2glsllwjp.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2aycmsgum.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkhunpv.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfljzngu.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tphjfoin.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvtuydi.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtihyec.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtufnaml.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2qvaedvfb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfqyzpf.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2coluvopj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpvozwuz.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oikkkuxg.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2dhckbrsd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2gmopzyxu.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2chnhomjt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2yarkyypt.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvfrdgol.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffuyrmtp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhowqsqk.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjwmchp.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2wthofewu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2mtocvaks.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zoejzvxu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvmnyxag.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmaeato.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuxsehft.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2veoihixl.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2huttkaff.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqcwjgt.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2tgznvyex.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zymtcvyk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2hdoipwwt.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ralmhdhg.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzzusox.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2vinjkxhx.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvhbqonj.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpiwntuk.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwhdlxy.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmjdliw.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2vimywroe.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2xjtlatdy.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntpcaafh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2luoolhfw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2muytlfcb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjtraat.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfssqhoz.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jivtiada.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrsowmfg.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2usfbgxym.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2tufojubu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2egqqnjbz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zthmhjce.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sprumhfs.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdhpxxk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxpxnxk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2osgfjpdl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rpsqenxp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmzntlq.html


<!-- 参考信息 -->