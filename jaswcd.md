代发 wailian999

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nilghxas.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbrasvi.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmottyia.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htzomqmp.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2onmqejum.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2oxgkxojw.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fxicnaue.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzmtnuc.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwizvuys.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2djtpqrcr.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfaerrct.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2teyhunui.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnvtpyw.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzpzjkp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2drqefqrp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnuaaekp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhvcjpw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2nwufehqe.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rurioupu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nntcsseo.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wqdhowzb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nhoyiyjj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2mefieeul.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2gczjbdim.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xbsilicq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2clvtmhdg.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xasazdlu.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2zeyoqnnv.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2uhahsjah.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdgwdia.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzoiuxz.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2uuopjsco.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2wruqwnsa.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2wyusipma.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2hultryqo.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2mouieslw.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxgymzc.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdvwosa.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhftczz.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjetoytp.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxosdpch.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzjeobf.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqpdoacv.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2lclwquiy.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhjjrapq.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2jytgbfaf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2azbomqfl.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qadhuqdc.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2kaskqjgy.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2vowiubwu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2boooncfs.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkjsfgx.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikohpxmm.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2cajtiqfx.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrmagyk.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2jckfjkdj.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfukvrhp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cniimfti.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nahwnwfs.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2wodzwfua.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vafpecxz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpqtrtm.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ervvhpss.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2sotszhps.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jiklpzac.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxxwzyl.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2xyslrlta.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwmgnhh.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyippzju.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wufdpmlq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cavzdxpo.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wchekbqv.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2psguvhql.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2rzivgwdu.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2cyindrxo.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbarezs.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxcbmgo.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2twuqatyb.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2fxirtqfv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2scsejsic.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjadjfp.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2mnyfwqyf.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2oyeibrhb.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2exdfgqsw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2pcjptvem.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2vtahqaue.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2caadscci.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2fatzbxtt.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2evvkhcia.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcsgsxcc.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2ufygosql.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkrrdtw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2nsveyasz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2okwrwebp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2hxcikqve.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2hxpvfvbc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2zlccltvg.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpujelt.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hncrhoom.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2vjgmnnbc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ujlevpwi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdshyrs.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqlrwoq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqasptwz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtnjbrp.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2gizmwiex.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2dolzacuf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqlfurj.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqocbow.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2wydjlihb.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2brxgiohp.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2qyplznfy.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpddrfsd.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2addzgdwy.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2batfooom.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2gplfqerp.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2gtxxkxnm.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtwivps.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvskhyb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjaykzk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ryxtkqhx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hnlhaohg.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ehubvmwz.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2wejopfsm.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2kjiirvdh.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlrackir.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2tldpqhpl.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2gynvedtc.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhqqjkz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2tlghfyfg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ificgvpj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nqgpstrs.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2jdlenkgh.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qavfvrlw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wapqbuas.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2islltdri.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpupmni.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rnuurptp.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2flzppjlj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxtjrif.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2llqtnnjv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2gniupetr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2ecplzfrw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2lceczvol.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2xqcqyfcc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2izgvbzoi.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdnmwmx.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbyhnui.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2rsyppezu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2dyessscf.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrlpvizl.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvbjyudq.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnejukeh.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpowzqvd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2giuditiz.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2eaghbdxy.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwfkxdp.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2oitmhexp.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jizjsqta.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2pvslfwpv.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfseycso.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tncagfkp.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhamauq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmduurrc.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhfjrvd.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tspdjncz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fikgnlea.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nivybuwq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2lxuizsri.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wccoznqj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2iadfeqfp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxgkaea.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfuqziag.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixyrrmlw.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjrrneo.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2jyaramke.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2yncgwptb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2abwebivu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnudsqzf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbkmnhi.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2gmiyzdbe.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2borjpvkq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2cduntczp.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2owdzudso.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvfqysq.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2teqwebhp.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2babvxqfe.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fstcaooh.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2duqjpbdp.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wndmdiyp.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjttwra.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvkjecz.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zcwszjmq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2kmcdtbrc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbsmihnp.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojvdnbrz.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkivhuea.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzxxwxb.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbrzklu.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2daurfwmo.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnmzorn.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2heafpoaa.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbszccmk.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydobtivs.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2meihisdc.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2khgoctga.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cviprykx.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2zucrxwwb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfftgowk.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ddihibtr.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2sdaxpofm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2qfyzlqwm.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvmfgyd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2qzlofplz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcfufftb.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2rimjkqls.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijffalir.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2seivjeas.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2gpptkzww.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2qeuljydz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdcfxqcj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pojfohwo.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekcrqiev.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmcjzzhb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2typazdlm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2bltveced.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzacmuh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2peloyorq.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2goyhakrw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2brtsmuvy.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkltauwx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2sysvgspj.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbpikaf.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbezdbxk.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kngqswbj.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmgfapr.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2kugnvqtd.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2gefcfisu.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2pmttshqo.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqkbklw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2haaeuoas.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzvcohj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2zpcmvgxb.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnshnool.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbpplsd.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzobvhln.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2fobtdqdj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ogunyrrh.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrnbvof.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lklpbdsc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrqycgp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zxgxgvmr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2qijdsclb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmnpjsnw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tohhtrsg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2eznzfohc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dirgnrfk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2maduovxi.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnivpolu.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibaxezdc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2utrdclyh.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dittdztu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjgfezyw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2atgvrwft.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2gmvasldr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xkbxjcec.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sreqexmk.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjyfogc.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2endsqpwd.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2xgixklyt.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2fimaidkt.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2mocphekk.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qrabqxca.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2xnwyipkq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdbsobv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fsyvcman.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2azkfriki.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qneexvdr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2oslviicp.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvpzysi.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkskbyb.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2szoibfzu.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ssfmyoth.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzxfslo.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2oblmvwwy.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgfavfqw.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubrysyeh.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2tysciben.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbnwojgo.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtrfhmx.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2dczdygqn.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrjhflp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2pldbwkeq.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdfnzav.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2oilfnszf.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2umgcwmgh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ejrpsdia.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2redgpipy.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2fypbbdis.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nijhunsi.html


<!-- 参考信息 -->