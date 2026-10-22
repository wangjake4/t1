代发 wailian999

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2kniqbyad.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2xzgacevj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmogcjc.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2canjkkcg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2nvillint.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2edonyyzq.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2cytdsrbt.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvjsgcs.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2xepokskh.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2whsgsvcz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxolwivc.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbcpjzlw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjeepoje.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xixvklrq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjtxipui.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqwwder.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2clrpovcm.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2rjltnogu.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrpwkyfx.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzylqemx.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2emfekywv.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfwxjww.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zuswmcds.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2rcfzwmez.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2gllymagg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2vjuhavvy.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2rcclmclv.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2lhtytoqv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2diapliwz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2akieugdn.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpgsfkya.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2sljwhfpr.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybqjvqnf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jkojimdx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjpxsoc.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fpchekpj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2snaixoqq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dypamnfa.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2amhewspm.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2nxmbnsnu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqounyq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2eluakgbn.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gywgvdfb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkfylao.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2hypzcdrd.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2apaudjit.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2jrbrvmkm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2bgkbhdpa.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2etepdavw.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2yhzkenht.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2myzlrarf.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2onccaczo.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ukiluekb.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2cxopmprn.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2tevlcykp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2wradzwhs.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkydvsf.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2mliocrdo.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqcwsvec.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2sgontcxq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2poqpmect.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkyzosz.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2etankyau.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2ryigxqzx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2cvbajadb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2dtsyxfob.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2oaevbahf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2sfaljxzz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2yordwqfs.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2yowwzukh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cbeqwxee.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzodcli.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2eiexranc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dakawtup.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2btvomgjy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2znmblzny.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqadgov.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2mehjtomd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2drzjodgy.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2beserolm.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdecpfy.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2eiharwpj.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2hebwumtq.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcsugml.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxkquwt.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qryfxyqn.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqwfwfn.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2pdbovenj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2eopczwjr.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eethilix.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2gbynduzr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2iepufngs.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzvjkan.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxkujbd.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jdofwvhm.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpmcvee.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2gapjfkom.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2hddsvjrh.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2tyedqfyn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2ygijsudc.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2hvvqaumd.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ysptetcq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfcyzqt.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cdlmesht.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2jegwsayq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2woqtzzby.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvdxshq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2otjipniu.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2ecwxaeom.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhtiywp.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfibmoj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2obatrfjt.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2voixpele.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2rkyxcpde.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2czbfbcxh.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2petvcled.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2wjreihrl.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2sixworao.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2lkpfayyd.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ykyqzkrk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2gfpdtssn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqehmfi.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xuejbkgp.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnuqdwpv.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkxsdhi.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2avmpruwj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwmdtcga.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2akrdqpov.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2njosdund.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdorlgef.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mylapcff.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwoekyg.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cabfbbye.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fctkknwn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrvqioa.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2haglfemd.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjiysxpb.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2weazzvlz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwrbnrc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2etnxxvha.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2svtmonth.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwybwna.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2svlvlwso.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2erxaqlgo.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2psundywt.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvvxucmx.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2sontsslt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2cjsrjywz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqlmgoax.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhmmhop.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2sekfusdr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbeotmf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfmqpxg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ludyxrkh.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2wimmnwcz.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bvyyqzkl.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2endzczrs.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyclxfpe.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mbewlkrl.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcfyplp.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2oapjjont.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlstijwc.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2hdeiarqu.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvdwqeg.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vavcieix.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrlbhbs.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2flobafjs.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgrgoty.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqegqtl.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwssqakd.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhkkqev.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2xcqvisso.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fuceusag.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2scukiben.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzkhyowh.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2qluerqfx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdllxnob.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhbgpny.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hjptjyuz.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcbnbelf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zurkmmjm.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jwaajfsv.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2bvuekjxt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2qhrxydxw.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxgpmka.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmygqai.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2wutcixfr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwiuatny.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqsqlxvw.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2fwkdvphw.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwtohqk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxvjfpb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktoijmoi.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bveqeemb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzyscifz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2dptdhwth.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2xplnuiuc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2feqyunyx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2fducvbhr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2likgasxu.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kxmmicao.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2lvluorrh.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgruqbac.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2awzcuggz.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2rytcbkej.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzepypb.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgibtjea.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ebygadkt.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2hezdrync.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmeiclw.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkqdwdz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gllhbltp.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2usojhnki.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmejtlxh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2bcoajjmx.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrppofjc.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mggblied.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwcvrqlc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2asvdmywx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwvzadi.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfxxtux.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihiwyild.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzhlojwv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqetsct.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzlahzs.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpmvqdv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2myveruuv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2woxqryvi.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fobtiecd.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgyuxtyt.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vffkvjqy.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbrmxbdp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fqcxyrhp.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzgsese.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pajzfmsx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2karflmvk.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2tlsgneui.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhsqncg.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zscnggme.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnrhcho.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2gpfagwcu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2mkpjhcyp.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhjblxf.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgwrwrj.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2slyujqjy.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjkwwoi.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqnswqa.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrbadaf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjiszika.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qufpvlvi.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2nglfolbi.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvbewuo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2unaxzczv.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlrojrz.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2llfgdivn.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xioppfvv.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqywadq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlrypieh.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kyksoeei.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxgzplc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2afigfdsp.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqqnlhb.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2dbcksjdj.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2uarvgase.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrybflt.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2jivuzyvl.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijafupoy.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqnufpr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2anikdtwy.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wazvnane.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2twjfjxsy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhlszhv.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2akivcsee.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxclmyo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2eyascgfh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpzqdof.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgabdmg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbitikv.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2snmibnvv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhejdiur.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqefppj.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2itkzbsxi.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyocgdbm.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2eglxvlgn.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2uiybgxfb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhmdzdf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2benuhxnl.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2oktwcyvt.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2sdplfvsy.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2nsliblmt.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjsqrnn.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2acsyvrch.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2uuryzqtb.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2aznbftbq.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwcienbh.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtdgsgj.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvdzmsp.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2izfitbbc.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2skkbayev.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2ezumxqsg.html


<!-- 参考信息 -->