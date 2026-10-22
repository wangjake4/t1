代发 wailian999

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2njszehuc.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2bbyynpxv.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdjovrj.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kckvwhjq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqzozut.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2duqtkjlt.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bfuirvrx.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhnslsg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2inwukrrw.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2scyvgvko.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsymcone.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2radptipk.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2avxdkqpj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqenbsse.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2psflvpqq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2foofltqj.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cgjzmegu.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2lpcyjaik.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rsenfvsp.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2okmfsqja.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dlaafbcs.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vccexlfm.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2qlyvozxp.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2jmzdcyvl.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmokyij.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwrkrag.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrpsklmu.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2cordswjo.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2awqhlnns.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2imizkbhs.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2jstbwhet.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2azwylmms.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2djinfley.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2pbizwmzt.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbmvhxx.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2gxlgqbsv.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2yamqdptm.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2wjfzmoek.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcmzlyix.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjocnnn.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnrqrbf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2apknnehi.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcifglxn.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2hztxfzeu.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvemnids.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2tvfuvxqg.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2btzyzpdc.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wokkxoai.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2oujzhnki.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtunhqv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wmlkuglw.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxjimqf.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzketrkw.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwlgosc.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2vowsmobq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqpsnwu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obppparn.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vevcghfy.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljudbkjz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2eylvuzyj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncihrhoa.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xwazgkfd.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbjniyu.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdfrcll.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aycweiqk.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sliuzlzp.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2skptytqo.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2sncyeqsv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2acoepknh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfnoreox.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldkyfyzc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nimriran.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2dkavgecz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxzcomy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2sniuqxhg.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmbgftd.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2blamkmlo.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2elouhtpn.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2aypaurge.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2knqftuwx.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhflnks.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfkjrbv.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqhbbbw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2frufegnl.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2nszxxhrb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2yzviwiji.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvvqdhu.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2rwsrdscd.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2fedhbkns.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2hybjujiv.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2qgcmkdjd.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2krmyrjmw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcnhusa.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgtalgg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ukcracjl.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqiuvtn.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2crvtxisg.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2jwpcsygk.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdzmgfn.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2brhmxeab.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2rrchudcw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wubrubzr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2noiziqkv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmpwxix.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2anoxnuji.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2kyggbirn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2jprnxsyu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2vaytmyew.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gnyqittg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmpyasp.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2cxobmlmz.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdihjan.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lowwfqet.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2scdxpoui.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2iocrbqvh.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwmpizc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2ovenoxkb.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jlnhkkon.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2mneblqmj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2wppbxwua.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ripkiedy.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2obfjolbg.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2infylofm.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmjxipp.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2pqkstfsr.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2ablvmjwc.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2zywriqnf.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqjgdvc.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2durwwtwp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2vdyropbi.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2kpenppvl.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yildhrci.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2asgqegos.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2omzmdnla.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xitlfvwp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2csebhanb.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2usempmdq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2emlfqrzi.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bxeiigtf.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpjfcmd.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2dhedjknl.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2cvpnceki.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2aqvvymwn.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfeuday.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvtenqz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2xpgknear.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmrnfwv.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2gubkuwdr.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2kfzmmxbn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjfirhg.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjobkcaz.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpoqfbbn.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sshsclws.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yoabombo.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2iovdntye.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxzaeayr.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gmphcsde.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfktztlg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tblkrctw.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2dtrhowvc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqefjkv.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsykomgw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvmyabx.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2snmcvezm.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fomosicw.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ueiczzbr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjlsqizk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hadebohy.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnupipq.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuaffrkl.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kuktfqcu.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2hamdwsqr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhvuufa.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2crsgjvur.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrpeeck.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmxvvwy.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqegavw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcayakqk.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2latwqnhx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ditiginw.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrndnmy.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2gvuvqdty.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzceqvoq.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2glnnhomo.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2znowltkk.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fagphdyv.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2emrhmyzx.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqvgnia.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2wbyihjaa.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdpnlmw.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbpiivf.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2szltqfjd.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2uucjdgnb.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2vqovftzn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mijndyqa.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dedfanaw.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uknrptpj.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbwokwa.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2oihgruec.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2qenrtrcy.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdovskxj.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2gsettfmy.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqgcjeg.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2daytpggx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvnxvaz.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2krahdwab.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvvolvj.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2gruomhio.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjzseoa.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvvmaje.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2rcddslag.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2mgomeytv.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zkompmbo.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2fzldqscm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzvowhw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2qourvkvf.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2slqdrieo.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2izwwuklr.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2wwqymhiw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2amdnptgl.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjijlriw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ueyudbwj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpjbfvt.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzpzmzxa.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgezfpc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2ousqjhlr.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2upafnpdq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2azewakns.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2uatvvfqm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2aqcunzud.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkcktwy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2msuhdkxp.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2snbspwxt.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdrfhbj.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyejxzky.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2qjytcsfl.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmmlwhv.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2jdmbqcop.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtoollt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxmwxkf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppivwuvq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjgaezg.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2ythkrtjd.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2imtnuthr.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tddrnilg.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2onekeelo.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2xfpxdwgs.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dcyybwed.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvcztrmz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfggqwjf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmuopkb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzpzmbp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrxmwfm.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2epfymsll.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhldqxj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqcpoxq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qrunmdew.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2krpblxiz.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfaonlbl.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmsoeuc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zslfjfrr.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhvsqad.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2opnwkxck.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nptbnbke.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjjucnz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2pdeinbun.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfnaumq.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhpwcml.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ljohhoon.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2cjosxocl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbkjbei.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2odpmwprn.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsjoiwy.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgbrrol.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ettlxovs.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gupupcne.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2yovpaujz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdjcbkp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2cisypiyj.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2azrzqzge.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2fybuwrjq.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqbvumc.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2hkixhvbl.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uiljstjc.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qoijrnbj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdjfbxm.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ficldopf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdnvldnf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlyndli.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgrvyja.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2hmaxqwzl.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xcgywrla.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbypufk.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2darcrfqj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjrnueol.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2otywzaxk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qumkytgl.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2enddvcmh.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2stbnbzgc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2swcyhvoz.html


<!-- 参考信息 -->