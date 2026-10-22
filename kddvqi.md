代发 wailian999

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwoqcyn.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsslolvx.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rstnkzqy.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2atfkuref.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlcocho.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2swlywdhe.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2pgeznkqt.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2fzlytnpz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnaeanv.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2cfotgmkd.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzzonrk.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwpdvin.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxwymmw.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2cvwwvrku.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqhsneg.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2sosrschl.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xiyulebf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsudawow.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2souhspkz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxcnrukk.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qawmgqxk.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2htwxistz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnnxwcuq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwskpmh.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkfdxqt.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwsxjts.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbcqjda.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2uuhsqkmy.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2prpbfchg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2fftlocnv.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2zwfveykw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2ahxwfapo.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nphmojch.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxnxnxr.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eoznjfac.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2szbsfjym.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbefurzq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2osweueoj.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmxabac.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfxviei.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmkvnmqg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2msrqfkte.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2suelumkb.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2buiwdjpw.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftkdommz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2peldojwx.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfgqhpf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjqlwin.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2caucqbwh.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2uscwiuxs.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2zantfqsn.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2pntlxwhg.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2vuswqbue.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqubaxx.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2qygjrvrb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2jnotwwov.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2mcyismob.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzuqych.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2ccfhadcm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2crtxfpuq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkbuxke.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2dcsumeau.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbeetti.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2brelsshj.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbzedqg.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdmfziq.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqjbgoj.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrqqmct.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2xvzogyzv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2zejptrta.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2xcekeovg.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2nohymhgx.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2sznttpdj.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtlicww.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dpktujue.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2oqcoiqqm.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2pdpjamud.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnsmclcg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2qaqssizu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebuikngz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxdthjv.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2rpyzaaxf.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2gqplhkbj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2azyazzms.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wjegifkf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2ndsnzvzp.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2edscvylt.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnfqxac.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcykhxox.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxcdnwww.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2vatzvogi.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxqfsnb.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqkszpj.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qieabmjx.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2agistsba.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2fttisqmg.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vrjrtygl.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmrddmz.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2nshsazxr.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjxhqsb.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2frprhbvn.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhjxwcf.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtrlelu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2gqeobfro.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2nojheypb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2lphbhhgo.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvtfqwn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dsixnunz.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2gdanyuab.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjylvhj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dhebifso.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbujodk.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2gfpjosmm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdqurgk.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gorsjjbm.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2yoljosdg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdvfjrd.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2dyyuykoi.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzqwcui.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2osrzceoc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2frasaash.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2owabtxjn.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2szocoafr.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2bzeadvsa.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2bbuivcsk.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2plqqfmrf.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtahtiv.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ochunsgb.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmqsnop.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqqguod.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2nypachmh.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2duygorql.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fdrlaryw.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkwncot.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckugelhp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2xizdtygl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpagieth.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ecoaweuq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdtwqxe.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2otrgwocv.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gifyrtqg.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gwazwjuq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gczrndzv.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2iinqpvlb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2flwbssrb.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqgjahs.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrcvoyoq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2upvgwddp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqietnlx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjcqzxmm.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wxegiszq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ykqvkwsg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2oobkvrxm.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmbhagt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqvtxvr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfkraqq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2sxluvoeo.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2tzrvapqn.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkxtcoi.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpjarew.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfuxfaz.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdnoqgs.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tdsevjol.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bliqmdgy.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvlajne.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iblaczvk.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2bocyveje.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkskphbk.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2taeblxjw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2tygvghyr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2oztvcqjw.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxfyvwbg.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2deuigphx.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsaxnwkz.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2wwveiirr.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2hsusxmyv.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzbazrj.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rlsqmusz.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyeccpbi.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2zodmfbpk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfpostep.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwmtzdt.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cjuglwfa.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftesmlik.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwgifeu.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzzvhuj.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdllcio.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzyyfdm.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqvevwt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2llmjtdho.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzlbmsqx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmfjfeg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2houukgez.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2znxnqarp.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdsgrkz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvwsrmw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipchkwpd.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2owteaypk.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwibtnp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylkslfdi.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2vebiglhq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2rhrngihs.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmczxnrt.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2jlkbvqgy.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdpjxpv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqfbdtd.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbmyszi.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2mfdcjawa.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2poaoubii.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzeirwhm.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nomdrrrv.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2cokighyf.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwyhicm.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2jjlygfri.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2nviopjrs.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpcfmtdg.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nahfcmbf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2evpsvotp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrccguj.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdeanfx.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfsokfpp.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctphispy.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2zqiteags.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2pcgfocdc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvmszne.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sglcspfg.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2iotsuxkn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2etexzlys.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2afbjrrih.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2okjalrfh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ridqqlvt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2pdsmsnvc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zrkiasdn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rthdpdyv.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrqcrmr.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgpkwhrn.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbkiwku.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2virewcyt.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqtvsjl.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2opfdmyfs.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2pvcehjug.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jrfuiqsi.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvkmfyyn.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2briyfhuy.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqcrlzq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2zjsjdzqr.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqilpyu.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2xtckclum.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wlaczjpk.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrxpemp.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpctpsqo.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtbmkvr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mndyqttj.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcexdzqb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2rgiudtzy.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2owgyddax.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2cpkzumcm.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjshxkf.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2oevhdjpc.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2taxwvpjr.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocmnaqek.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2scjcxlwv.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqkuaeq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxstezdg.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dojtjgvl.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2zoixufsd.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2nrfpvqel.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2iagaslod.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgqhxxb.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2gybxkjam.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgduujam.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2zosttkmc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmolckj.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2eonlengb.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnkvmhm.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxbjjfu.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmnddbg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lagxrqfp.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfbcnij.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2osgzmyqu.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbgutcp.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2hefsjjzx.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2vvlfoczb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2dielctbe.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2zzcrjaxc.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2fmluxrfh.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2awtcnspc.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kupehjhr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqeluqu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ggcjhykv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2wzssckee.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2dxfffwhu.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2evjljxau.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2hacyanwr.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2aeikgfcc.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2thcageya.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhovzow.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fedziruj.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqfvzxi.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttuarplp.html


<!-- 参考信息 -->