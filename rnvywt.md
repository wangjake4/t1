代发 wailian999

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tiasapil.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tiyfqakl.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2diggikqy.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2eznghwqs.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2znculwgo.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrgjxju.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xugaqpyl.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2okntbwxh.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2kueqjjhl.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwfzrdv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2bazezfpq.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxcabty.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2fjexifhz.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2bpchzkdt.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2rtcnivgv.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2ptywtpal.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2npmgezga.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2syjehsuu.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtryqpm.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgiqrvyt.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfgpdtv.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlaksyk.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2deglywzb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdlgghrs.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dchnjpbw.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2hbuippvt.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipddulcm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpnrtrxj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2geyaydbz.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpsvjedb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhgizsr.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2tcityper.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2exdwybqx.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2qxorella.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ekyqsetb.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwihvrx.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdvlucmr.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjkwhjx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nokocvte.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2oekbmzih.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmhydiyp.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqpqenc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slijnvkl.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zuurrrtw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hermznsu.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkeqjkf.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2zzokqfai.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxiejrl.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdrkzta.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jucxbcft.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmmaziy.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfexmlkh.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2pshczgvk.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2xscdunfy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2hrfznbgv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjfwhmo.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2qjdecihh.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2rvukjony.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtvglng.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2eiytcgkg.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2tfwdykws.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2kefolvol.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxtlbcu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjptwztl.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzxjoty.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2mreppfak.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2tiiofrtc.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2jlfteawg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2lyimjhhb.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlchpqxx.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2mikrulvc.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2ugzfndvw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2litsrutz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2qslerejj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2dfpgblgr.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdqcpml.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2bhuxzhxo.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqymvco.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kaufmeaj.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxkpvyd.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2uefsyaca.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfpasiq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2bicffbje.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2claxfgem.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwyagzqi.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2qntagaoq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnundri.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmzjrfof.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yrwnraqv.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2wgpwoofc.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvcbtdx.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvsvoaq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxaoboit.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtlbcxfb.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkzoejr.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2fxtzvvgq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqeheuk.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hewyizes.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwmpxda.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2whbihyjn.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2olehkzxe.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2grovpbdi.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2azqhdcxx.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2clwbifkv.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2hjehsifx.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxdufwj.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2wgeiqnfl.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdzudlg.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2qygehnoo.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2mwoqxflh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2oendrchl.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rrfryicf.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2zlogwkaj.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uvkppasj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gerjpmsd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qbkdrsff.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2knpwpsnt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hjijtctm.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2aoihrvjn.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2mvfebtuq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgryjmu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2vrekcoll.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2mgohbetg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2ahemhnyx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2dwuporvw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxbqfgm.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2dinvbzmf.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfhqiwz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2jvpaabsg.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2oavtxekm.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfaqizbs.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2aumfurra.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmizgaix.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpavrrhi.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2gerkjaar.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrxipbj.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2aozubpxx.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2boltzsth.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqjsbeu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2ulirobca.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkzckunm.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwsjxph.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxlvbab.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjtkqik.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dilvlddv.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkchcdo.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2iujkmsxf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjdflem.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2klnspypu.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxnhqfgn.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nelwyhbq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhhdpppw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpacitp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xeegadcg.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cfsioibh.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2klbqppfo.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhftove.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzovdnxf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbouypkj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbwuvhmg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2vijsmhsp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwtsvjw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzbtxeln.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqhwewe.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcssrunw.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xuacppyf.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nijqbkev.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2afuclyle.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2wczfysxn.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgjoyrc.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2rjcktgme.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2krjpnmxp.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pyihiviz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2vxshpjqw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrowdnw.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2erkbkfen.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckuerlgd.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojffnxie.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2ikfddjmy.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2efljegdk.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2axftlbyk.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pirbeyup.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2veqogunz.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlazddu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifuvuitr.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2eawwoerz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2abhynuxn.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2cigkndwy.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2movdztlh.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zvzggipz.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2wfkoctqw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2fbutjdia.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzhuuwvn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2apsmeftd.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbejhpmm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvkotfz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrgcmhb.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2vfecffgq.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2olbbtzpy.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2ailratvk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2beaxuqqy.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqaogbbb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpojxgzb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2kaouiyju.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfgvcld.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2umjkmqqp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2igpmncod.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2njrryzfv.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jiutmynj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwpthvg.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrqndmu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2vyzmgddr.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2lymihvxr.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmgigijn.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtjoahzh.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2plkdsjbu.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2gbeedtcu.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2ecyvjutx.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2brxsqcze.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnbzmvb.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxbundk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvkejtz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxhybhg.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebgwdstc.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2aycusriq.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2piyebune.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2bepceodk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2sapgsnhq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmeebaau.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgyqmnl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hofwmibg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qdgyclgg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlbygsc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2juczlqoy.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2adypnqgt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2ybnxbnls.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2gjyaplpa.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkvxfyku.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfpxxjji.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzshifvd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zthgibnx.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hztznsrf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dncsizac.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfxsoqa.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2mbadrtyg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2cmdwnhfm.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uflnnsap.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2njksvnxg.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2kdodjbff.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqbcybc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvozskq.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2gqoksyxj.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjxgesk.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2hwgrmlam.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxsibrqj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpkpohkp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2urpabnaw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwreidbh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjjgdqa.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2pziieepc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2smgqzzqv.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrayzed.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkhnyqg.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmtfzpw.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpizehdl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnbliqu.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbozgovk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2bygbgovb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulgffhcz.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2bzaikymz.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2todvkgqk.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ripgztjt.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2egorrecx.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2jydwbhvo.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqrkaxzw.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2lmaaauee.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlggmha.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkcwkdt.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhrvdtu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ojlcejaq.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2mmabtibr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvwqewo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzhfaih.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2yckmefhy.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2uguvqtwk.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2laerxlrf.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2rfgrlojx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxclsqk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2kjqphjir.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdrvwjp.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fetuomrj.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjjuimg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xbirhdfb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2iltlcgri.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2cyvhljru.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2jblfyksk.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqgvexd.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2sqcqasof.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqibfup.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2mweoxqtm.html


<!-- 参考信息 -->