代发 wailian999

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iydsztxy.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2deqhvbwf.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhcnicf.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2xqgwuruv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2baseqnht.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hsaljpqo.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpthirbq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqklugk.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2clowmcmf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lihjknps.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmzydut.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffaqmxkf.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ybnryhev.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjjwupu.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ygadenxe.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjewvzt.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzhetrv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qmryvtiv.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2gogunhvh.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2sfybreva.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhbexoe.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkhylhh.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsbebej.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2qcseyevr.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwtfksm.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2xxngllcx.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2axtexela.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2fksvhuvx.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvufuzw.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2jkthisqo.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2xcqpymsf.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2hudhmagk.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2uogxmycv.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2gueidbuv.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mixjtzmb.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2evbudxuu.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmwkqvf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzpwtgl.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqpdqngw.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfiesjix.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zoglkkpw.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2iieyytzy.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdeywoho.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vljhxhhf.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnirubtc.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpynhad.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fnadtkze.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2rrsurzam.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2owemzvam.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtaqbfv.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2vwcqpdvg.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2aomivdum.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iczdicxg.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zojbjvll.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfxbzip.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2wjctdins.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmeumaxo.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpfjogv.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yndcoxsl.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2radcrkmn.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxuwqukr.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2maxaqwug.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzdztsw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2sqrwrord.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2odfjigtg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvztffh.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2azxzwmgb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzlbhzdv.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2asdpiiry.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmrfmsh.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2pdclrpkd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2wgodlaij.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2cjgbbtqb.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2qbujdyab.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2jwgnjoib.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2cdigcakf.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2nxdiiwot.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2pfusmajz.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcguxgm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxyfhwz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2tzlkondm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2yyekkeus.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmmlbnc.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfxqjlh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2wipqqtmw.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2drluuidk.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2rxuonafd.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwdjuup.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnlkhma.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjdkmvq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2epwrdokk.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgyhjwg.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmecche.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2rnobikvl.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvybnot.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2kykdamer.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2nijavauh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmgasdsq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2mrymtwbo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2poteikba.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgnxotig.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2hmuobezc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvqwfcj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2pluduesj.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tllhldud.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzwloga.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2mndkhlbi.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2xtkasiql.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwehnpky.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyssfbcd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrhhcca.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2gszvciuv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2itoukujt.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2huwyqjfo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2offcenxe.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2widjdhox.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjrkuzo.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cqngiaae.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2byesfomi.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2zwbgnlda.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxtmpcx.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2euapasmd.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2irlgxtwo.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2adumkdwv.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2jxqcycve.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ddcyxoci.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2nhpnowho.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqgpmpi.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2ruchobda.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2axmhwydf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2regedtxo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mtrrvfya.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2gjslbcqz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhxupmz.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2piyrmojx.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2owvrvbtf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnmcurz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2xfubbxlz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2pylyhfuj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2uwomoghn.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbcujdq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2upucmrjl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvsywnl.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2klbivgag.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2gaollvgz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2okpxqyml.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqcpgos.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhfcdbkg.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtuigwu.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfdmcxo.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2dajypltl.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjsihpdm.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqmltao.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgnebao.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihocoaoy.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrbjpdy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbektup.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfimrbm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2lukfucco.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2inmaqnse.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcftaozw.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2idvpdiar.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkyjfnuw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnujfywj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2hvnherof.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzhmvzr.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhoixqy.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2swigsxsc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdeazfpt.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzqvmhcm.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bxdgtxrd.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2uubcbtoe.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2djhfjfdg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzrxwei.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2sewmcloa.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ioovglkm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2blzscdzj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwxqpnu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqsukwak.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlduczd.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctuyguag.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2shfqkucu.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ufghxind.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2haohropp.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgwvzcz.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnlxzbzh.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2cpkzdoik.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2uajbtoun.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2smrfvots.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2sexrtriv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxmyjoh.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpvsuuk.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqhqakz.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxvwuby.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2iehtkcct.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxjuiky.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfaoxpg.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnbpczh.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2toodbvur.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2voddatgs.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpbozydq.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2daebmwud.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2solcouxb.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpbukcz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mocilihs.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xygtwmco.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2bkncfapk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2kagzwitb.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2iebgusxh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2cgwvecfq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2chiufsms.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2vombympr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xikxdllh.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2cqnsgcuk.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgkqcxg.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2bfgrbgkp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmacmaii.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdlorqu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcvdepho.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyopbpeh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlgjour.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2sireuudy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfeiqog.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgccskp.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tfitmtne.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2ilrlxeoh.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mderhxzh.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2twifdfvw.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2cjmnnfme.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2pymxirhz.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2emuzlogj.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2loxzjiqh.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2mtltgyom.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2kyddryuw.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2utredkfm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lstykxtn.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mierhtey.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2htmipptx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2lpflgmpw.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsrrlpyk.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbqvhkpm.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2zecbdshb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjmluny.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ekgvkbwq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jglbuhpb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtczuqr.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjowulwn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qlrbspof.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2yvaxyyag.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxuudnt.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jktmbsnn.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2fszmilec.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wzupzqap.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gziqmbng.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrzeruo.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdvxhgt.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2sesiwuid.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qxyjahlm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxltewt.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zgexjhlz.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kumswysp.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnmtuwg.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsncwhjw.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2pcgkoskn.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ntkdifsb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2kxkizdwq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxfyvxw.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2kvscvbpp.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhrzfph.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2basxweho.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2evappufm.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbxlmulw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2euzjillx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2njajxwxs.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2qsuuukur.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2moousxar.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnuzuou.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2hglhsfsh.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvcteib.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxhgizg.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqagutg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqkmrifx.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzghhbio.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2btcxzssj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2blqkslwm.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2vbghwfbt.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2ziiousma.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2drgdqdbu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2kwysdqvt.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2byvhuqbd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjfkkktq.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2ypiyfumo.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2emduzeaw.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cayfpagb.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2dxfeeaxv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dbgubgwm.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2fjifudqg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfljkzla.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2ontueufc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2wmuaoohs.html


<!-- 参考信息 -->