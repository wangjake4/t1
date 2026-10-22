代发 wailian999

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdtantq.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjdbrpu.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjeoees.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezuswpnq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ywlnamto.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgxocuy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2anziohir.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxlubqi.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgpufcz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlibbqaw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqqycgxh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvyhprr.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrsdoayt.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2szlvpqni.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfnijos.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nokmmtsb.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2whfwxaps.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2adigkqfz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uuiusuwl.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhoklwzf.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsljqhsa.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2rpmfhpce.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvobmkr.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2ssuxqztd.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzswomtb.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkrdkpg.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2yusrbdxg.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2csbjjtct.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjmcmuf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhazpzpy.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulnztklo.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqoepdil.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yntwmwta.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2csboevyk.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dsyrljmq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqeogvom.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fjyjejcp.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lspdvrer.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2sifgteyr.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjqhdwn.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2crykygfy.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ueucgmoe.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpfiadhy.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2atjvjhjz.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2mshscbie.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2jletmkdr.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2jcodbohl.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2sjsxicfn.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2fajuwlcy.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2gibjalky.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2rffbruij.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2xqmyklqj.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2aylyymuc.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhkwbry.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2juntdvlh.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qordmqdo.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpuowen.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgdhmec.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvunyqgu.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2xodjfnyo.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvwhwyc.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2drdcqrrk.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbsynodf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2warglrfr.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytlxwohx.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbznkrxa.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdvwfdk.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2qwipucnn.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvuhqmyp.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2derjddjl.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2uswdnecw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2mjibzpzg.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcsozrja.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhgjphss.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utjnelft.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2kcknqhdy.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2horsrrdt.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzanvwv.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfnxxojr.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrwqoia.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mujxcrob.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aokcseja.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqbepxe.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvwjcob.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpkljjjf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhlsssn.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbbdjpy.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdoxxnh.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2isswyuki.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2ylllmmzz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2haoqilob.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrlzboy.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2afpkgiax.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2rzdiabmv.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2cfpexxxs.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgdrrin.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2armvkhhm.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2vphrwhel.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgbhufk.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2jimcjfki.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2vuijrtnu.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2uwpkduup.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgneiio.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2lvlpjkps.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2drygjluu.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2frmxisaq.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2taqtgixb.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2qopxmgwt.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfrderw.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvztyzm.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2gkeaxhrp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2phhzpmnm.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2budtrdez.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqtsgaa.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zrihmjcz.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2tmuhjbdi.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2fncrdnys.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdiiwxk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2kajwlohn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpzmoqeu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxcelfu.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2clzhqpev.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2ryoamwzg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjwjnuyu.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbwztns.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgvbpuu.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkxyuiz.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqyyqoe.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2asezcjpn.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2llnzjunv.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2bylqjhxf.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2rltcuqjc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2pulhtuix.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gzswsatj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2fxsrlhxh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytlnxfep.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eozhixus.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhwnqhj.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ymlvikzd.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwynbmj.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2ugitllha.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2fiirkpba.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtuazhs.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2nrriowle.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvyouxo.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2nljopkrb.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qcuwvocl.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nyikahcp.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjtugwo.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjrfmam.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwmxcgi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kdasjtkq.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2cyndodkx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2krtjuvml.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2uywjeqfw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2npmaxehw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ecaalypa.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdtpleq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2jpomvuml.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2wghxdgkc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2eempoaqn.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnjyopo.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2ycsbzytc.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2yvujqjpu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2dctdedmu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdifogt.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbyyuhb.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfgoizcx.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2eelrsrwm.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yizajljj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvyqqlp.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2htlzoolf.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2trmeragf.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjiynwu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwpevka.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2mlkkixoq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2iajntjsv.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2okktxaht.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqvtwkg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvqticq.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrbbxzp.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdkvcuz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdgkqfu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqibyqg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2jmmnccdd.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptrfzjfa.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbogzrp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdpongt.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lycieodi.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpvaiwz.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vflhdxta.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwoxkas.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjtfwgf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbpnonw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbwadru.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2drvftzgq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqrrtur.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwicbhp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyhuaopf.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2efzqkckg.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbsvjvly.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2htfydzai.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xevkunyu.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xohvdjus.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdthhal.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghluvuap.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjiqwut.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2dweaqkyg.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dobdbwky.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdwvutd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2npxtzygg.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhuednur.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnvwrqyt.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrivbwmw.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfspnzw.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2dwbinxhp.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jomhuimf.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbhnjjq.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvyfhwt.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjljwkja.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmigztp.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2rexmjttn.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mbcvmtev.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgatremg.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwthugot.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2owemejfd.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2wxbvlypx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2mkukqyll.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpvmzdz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmujzyk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2adbotxaq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlspgsoh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eetcchmt.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2qjnhajqi.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdkfwrb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2xbiytdgb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayypkfzy.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2oglpuduk.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwpewcwj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzyswdg.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2egccirhl.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2tffpsopd.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgnsefxh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbwwktf.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dxieoqoe.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2plohdull.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmqvqnn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2gljsbbfo.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ioiiznhy.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2mewqbupl.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbqhtsp.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2vleehxby.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2uchghiqp.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnjwrik.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2ygieorgb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzoieulr.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcpywwgj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bktcgncp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2acarryyf.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwhnsfb.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmmjcug.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdgtbyy.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2ktaoquhk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zdtgzndw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lewppopl.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxthqpt.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqmbagk.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2eittcsvu.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2npfyflkf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fipitetp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tsabwpjr.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2opgilipw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2sqawnpaz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2anceuioi.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlporwqg.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxdnfkuu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxnwzgz.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ftkeiqul.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2daufrnbr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jytqrjjm.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzrzlpd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2nwokwlkl.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkvanvbx.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2udfaskdp.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ykuprgjo.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2lgkxqhqv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2pcsztyoy.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2pnhvywum.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ianyimgi.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2chlnrxoh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvrjolsz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvazgce.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrzhynh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2isxnjugs.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtitdig.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdjgwqm.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2tqciexqp.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxjbzek.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2slsnehwi.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jegherfc.html


<!-- 参考信息 -->