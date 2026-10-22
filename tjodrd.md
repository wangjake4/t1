代发 wailian999

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxtqrjb.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmqanob.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxbpygx.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhauktp.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txrxsmcb.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2kofgfvuv.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnwjyeu.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2uhegarii.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2depdtjpk.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pihxethb.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2anosnmdw.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhvawvq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwgxojl.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvjuqtx.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvxvomx.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpthqmn.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdpbtpo.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2frgwtalv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xzuxxbms.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2azlxtchm.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxwsjcb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rjsozwpf.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2azgcbibl.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2haiopdyr.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yugytked.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyomfahh.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvsmokl.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2edcmikuj.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2fxmvyzua.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2emxvnwgd.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhixukd.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2zatyawsz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2sjbvelyl.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2yexidcuy.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2rfuaoeol.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2pacpjsfr.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmtiahy.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2kstntkzn.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2onjnvtog.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2lczllsws.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2eoaxrtbl.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2seqmzzrq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2osvgzxvr.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxanhjq.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvffjjo.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2klqqrjnz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqsbqvrk.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqgppebv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzltbsq.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbuiycub.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2sibpqeae.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2tncsfkjy.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2fatuhacc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2shgllmvq.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2zwdvafet.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2gokhwhcp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqobvfb.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrfavecj.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqlenwuy.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2sfckvyya.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbpflxac.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbfclxl.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2izkxbunq.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bvsfkyvp.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2inrfvlbx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjwluzn.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2gpgqndoh.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2qzmijuem.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnydhbio.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2htgusftz.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pufjeowr.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqplgbca.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2dbegvvia.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2zokakhda.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2inggsmsc.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2vermtcgu.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2bkhjoiur.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqqgmls.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhhcgri.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2dbowbvdv.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2tidbgkbu.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmtltgv.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2lrmbwlzq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzuvbzge.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsrwzys.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtpsszh.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpaqruzs.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2yuxddptq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2xtwqkqmy.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2fonhfxgg.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2jqujdhxn.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2spcdqxis.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbpkgyn.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwdslid.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2vexfasuf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvuwowj.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2cktnbkio.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2hqibikbs.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kelxjdnm.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2pnltvkgx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjacgwx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfztdik.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2mydoxbqd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqeucjht.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqoqrcwx.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2umzmfjnm.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2pnuzkvll.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbrsijt.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pdpzmuhh.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2tktotkrk.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2mcydnlfy.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2pebtbzjv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovgiryed.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bytizlcr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrkgaayj.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ieiqaguy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2czzvhurx.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqyalrg.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2xpachhwb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2alfjwdvd.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xqswvewm.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvslcvr.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2sotjncor.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvnqdqh.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2pflbofse.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmsdodgw.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnyvpzi.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgjpdyd.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2jipmobrk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2hurmpnxr.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ipoamwlj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2snmlgudh.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvgyxyf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vuakinyz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkhekig.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zcurbsmv.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmbirub.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kqhfojcv.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gdutymdl.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2fllklrmh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2utixpmsd.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmdmowf.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2emzaaqnx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxliolb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2qvbnlcjh.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2roxpkumi.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2ixktzmqk.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2caipzcdh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2knoasudy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsljklit.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpmohfeh.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjehfuxy.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2svmibxqq.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgaxjsov.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgjnkwv.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kywsgppg.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vbuadkzz.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvoscphs.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kowdgain.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbudxaz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrsbmrw.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxdeaaw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjdwgqi.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgyqivgz.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhkyjro.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdspaao.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvixbea.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2iblprowf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2nlinbuwu.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2logttyeb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgsyfozr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqpcbzw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2eecvhmfq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukchmguv.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwbluqx.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2cztodqdz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfomovp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2fuemmdpw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fizattgr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqvmkasa.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2drgykyby.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2fiytikfs.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxtvicw.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zymdimds.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lisgtfqa.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qitlyafu.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhxdfgk.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjjpedx.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbxcdqy.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2brdpwkwm.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ppuvbkrc.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbrjknz.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hqlqpqzt.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2cozhpwub.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrljjtw.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sywrraxj.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujudmuro.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2colpuhiw.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2mwqnssvn.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgfpcyv.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfsqcxnw.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwldybl.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjffjphm.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2gudlfzfx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2esyophsi.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2gplkufsp.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fpkgvmvw.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2idfssotg.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrjpslx.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgzilie.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2bodzhwkr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2yswclpog.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hizxjqmu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2oputnvwb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzyxtnta.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2saauwwtu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2emimzceo.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkzcmdp.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmopusk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2wecxxdqf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvcqxup.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hikzyfeb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqcumyk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwsdiywp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2hviehybi.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2owrlvkxm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2juhriahn.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2jeyrknro.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2yeozsybb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2ofuhrluj.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yaybuuyd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2wraroqbf.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbuywrp.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxagmdhi.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oegzzefs.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2mkipjhuj.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2hlynordu.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2ialmcadv.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2zpsbvwcv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjvnhfh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pztwvyxv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2egkzzuub.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2tvfdfyui.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uokaehrl.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxeannc.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjwajfz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhjcbyq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvcgvqd.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnnntfbw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdyshei.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2waislpvr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hflhervc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2iqduxldy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajgzhqhq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uamduqgf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2duambygc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2apupevyg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2givfxvis.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2umxjvwol.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdojupgu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vlodkjnu.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwvltvf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsvnjih.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qzueipxc.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2pmplghjx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zukoywbz.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2amfemxrn.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2jovjwuxl.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2zocoanru.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2mhosjrmt.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2csonpvvu.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2eltamtdn.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jfgjctca.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxlifls.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnijycso.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvlwcsq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2usosfkdl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwoahkh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2sifppbqh.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2iyywixib.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwnbqhi.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2arxgvlgl.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2qhngfiiv.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvaxoud.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjmsiye.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvgtzlq.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbsdzpnw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzyktwsh.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbkzzzpw.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2dyufwzwz.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2skdswbbm.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ztypodhp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2dqakwsbx.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxlcceh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2cddnpigz.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzuexmg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2opuyqzvj.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kavsofui.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdsvcgo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2simjodnb.html


<!-- 参考信息 -->