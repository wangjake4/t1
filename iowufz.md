代发 wailian999

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2kfezjkgj.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2jlkkukpn.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2eosspsuo.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2szbrwkyv.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwxbjih.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqttsaon.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2dckoxjpt.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfbvxvd.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqsacpqh.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwsbvbm.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvhkswm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jecrtnku.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftirxzfc.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqpbfppp.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ngprmdni.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2olhtcjto.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2flqpxmwx.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2fgdfwitp.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2toukpexm.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2qwmxqpaf.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsljbvxz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htqukcrc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbgvyoa.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2nooliozj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjihxnez.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xioghstw.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxposuk.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bdisrhxj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnrwpbzk.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpukifh.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2vmsejwxh.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2nssqnyxu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzbajxd.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtarcmmp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzkxdnll.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtuivuj.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2cgncaalu.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2ydxdvpzp.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2bklwhvym.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2fsnbqbmy.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2vceqxkqe.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2xazbqsac.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjligfu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2anzfmzzw.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdobpon.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdjsovl.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2unjyuvev.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2zsxpeuom.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcfqdsy.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxuowvf.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjhivfw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2abxlzluh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2aayarfrc.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2vznldvap.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2shtziqig.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2ljdhjzcs.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqlxbyh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxfrcpk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2mfcclstz.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2azfmgeac.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2kpififqt.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrvbcuu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvqebda.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbqhorx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2uggfbwwf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nprgbauu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2bhamhttx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzjimhar.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2twfvtlia.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2xtvqwbzp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2oyxzzkle.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzikyifl.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oljwaqnk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2szohnbdd.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwuribe.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2xndaadzs.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdfkbchf.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpswaled.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2duanjzbq.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpriizk.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2flijiuks.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gstbgpso.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2tjvivpxj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfkskgi.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bubktdas.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2exlkgsbb.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2qojrpxky.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2tdrboaza.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2istpvlqy.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxlakdp.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2ilcsnnse.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2oivssijx.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2kdmqksif.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2lucoacik.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2zuzalezc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dfivmdhj.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2festfwvt.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bnrevdod.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gbihnwcz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tldukhwc.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2evletcno.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2odespray.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdobcnk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2pycqwaeo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwlgxpr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2sannfrkc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqewryj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqxtvnl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2zesraigc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2wqwjwhcg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2plssneag.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2zkdebzxu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2hdycygwx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkxeaic.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qofrpafc.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpgobrv.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fazzomgz.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fduqzeey.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2gclwumkv.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghtsmxjw.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ysnlgrvk.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2woeezlpv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhlfzjmp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2cuojnyji.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtlplas.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnuejyzg.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcylreut.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2smkjxhnu.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmttzyjw.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kaghgjjf.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfuzprz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xebhwomo.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqhlhni.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebylycwv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dteqacso.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2dezwjmaw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwijduck.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxxtsgo.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qkzgngjr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvdcajd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2vecnhefr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2xygnbbiv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2eukvvcvl.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibtoftmw.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2vqievoev.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2hmodtwlk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtlshsdv.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2feyjvgly.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wajaqjeu.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnpirfzy.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gtkbkdyz.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zxesbupj.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2azzmpvka.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lofujznq.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkasxqd.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnaaywlz.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ftldxafk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2vguyuqbi.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jsofoylx.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmlkvbcc.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2puvcejdu.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztuscvow.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2muokzced.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcaibgb.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2seurkman.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkqashv.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfjtbcy.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpjpyfw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwlvbxin.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2alrrdvnn.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2igiufnzv.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2gftrvboi.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkyilyd.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hcueirsp.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtftypt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxdgzqo.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ruqkbdlr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2slstfseu.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwfaalwa.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2krgnnvjt.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wemshuqq.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2findcxjg.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2jgkhnksb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjjneek.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cktjhlxn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gaapqhaf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjbogsgf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdxfpxbj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2zsugpuhj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2fdlvvnti.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzyojmt.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2grbalkwl.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fodbegxt.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2kycynqtb.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdaeonsp.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2geoyzfib.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2smavkqyy.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2heuegjfh.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkdhncv.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2jseeybwi.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2zjztbdep.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmbohor.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbjmmnl.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jllxvwro.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahxstcda.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zghfasyu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2ecfxnqes.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkyhanhx.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvvmwuz.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2cyykhobo.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2jistasee.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzpjuxn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2arndrolv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ausmmmsu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2aiujlmgg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvvorhu.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2hwrhforc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzdbplq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cozyexmc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2vyzwrhvu.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2gurhboud.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2adffydjq.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufgfyuvt.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdlsvgvg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cynethit.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2obhkhyaw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkbizvp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhqqhjo.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2pnfyxozj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhhbxkv.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2udzrpyof.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2apbqqqpo.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2oubtvmlp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2zlonxxvs.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2rpcqmvdj.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2sebpfhfu.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxxwsul.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2koqlgklu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvuwrdo.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcizkjsm.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltqugijf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfycsscx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2ennzvngl.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2fyimoglv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbkmfsw.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2eidnszsr.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmzdgfd.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdiocdo.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjhanhgx.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqvdxeu.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2azslzccz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtaftly.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgsciezh.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2jkncstss.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2vophdxww.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bqoemnlk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ziufjjrq.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjztzod.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2petwvbkl.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2bnkdgvnq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bsogrkmg.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kzfgrrie.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2eygvzbnt.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bngtsamt.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2aqstnxjb.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkgeqrek.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwrbvlm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2fqodpzcb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvxdtfu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzuqvul.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2tferuqie.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ooyjizql.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2koyknagv.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnfkbqf.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yljkvymm.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2psivvjky.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfrzcrx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtkrnbf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2veemdjaj.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbckxst.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdckmem.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2vuncdajo.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bikzgwna.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2uabhnmgh.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hefbehfp.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjfiqgl.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivungdif.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpcsebyr.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kznhhmnc.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvoeuiz.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbqcqjf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxgwgmr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkcjeim.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2kybeaybh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xifpwxrw.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2jerrwqcn.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfudamg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqavtee.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2jowjotsb.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2csmlejqw.html


<!-- 参考信息 -->