代发 wailian999

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2axgiuzot.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvvedsw.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqenotd.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjjubzw.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxncxfo.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwjerea.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2rtugwdnm.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2mogyfmwg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2uefisxvd.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnbfjpj.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqwxlcs.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2vshcazzj.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqsxmbd.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbqjywc.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvuuxei.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2oddwggsf.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2knktabuv.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptacxsje.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdgfrhv.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjkbchy.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmescrhn.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2vzuggwag.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxkxcev.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewlyjweg.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2fquyuyii.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2swrfvmpv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2euuoxgss.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2snwurlso.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvbsrhd.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2msbsavac.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwogcsn.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmmlnlv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2assfxbts.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfdtjhep.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jabjqfwu.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlghulc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjtaphd.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2houdixlz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtoslqff.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzfctwg.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfpuadb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2udeoltll.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2dobhvkaz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2osijfanu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2irkmyvoo.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rouruqnt.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxohvtdx.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojcujgny.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ydfxgsnx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2leabnhjd.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2mxspixeo.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2sohltkuy.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2fafljqgh.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbbufmj.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdfnpty.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2doxliief.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2rfjlasss.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2udxmhxoy.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2eknxefsl.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnsfbgva.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2szcteooz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2gikqyayu.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymobxqyz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbbnljh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzwcyjx.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrmfqqxg.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmczjev.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2ysofuxfl.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2qgsxxzzh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2pumtnhce.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2mkvtaldb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2eoshvvzz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2qivovuix.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmifbvq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2draoljiu.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2vcivlmvi.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2axscejgq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjjpgmg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2olpqzjoe.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2efitqgkn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvyreova.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2sssbpesk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2fycoowkl.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2uumfhujw.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxfqpsz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2datxivib.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwlfryx.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2oejfxltb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnippqnm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2usjuvrqq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqqeqsg.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqahxlo.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2lmobehed.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dzckcwte.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2aldtbtxm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2dutvwjge.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wllunvhc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nfchvags.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xmwddkoq.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xnuyhejb.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2quywzefx.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjtarnq.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2mjxpjjct.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2uxrbtpqp.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2axhbkmba.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2uyynajtc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2etzbanqe.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nezmluyd.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbtqxam.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jehsuixl.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gycmkxgj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hjyerbac.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2quvyjzhp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sdctavmy.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vkaskzfu.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2mflavskb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfebkts.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2vrolzeaa.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2kkubctta.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgckiwi.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdvvvnt.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2iadvqdzi.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2qpghdygz.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2svldbtqz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2bipeuxoh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhatfsov.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sscbasbs.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfuxpwd.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnydplgc.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlsjluuj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuesxlcu.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nizwoetl.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2psyhymng.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpolkrqi.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjarqylu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2galcmfld.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffngqrho.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwpdhew.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdnmoxqq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvcwaajf.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydltxyjl.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2slvqvarv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xphgfrkl.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wczvmglq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2trpirwea.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhgoyxo.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkazjhkk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqieupq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wugqihlj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vezuzggq.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqlbkzo.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvqjdzh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzueywu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2xchviujg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2evhaloec.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqynuqvc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkiaxmv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2lnncuiwb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2joymfyvk.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2crwvhwps.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2enxhabhi.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnyqvwvy.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqiwznv.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jhnplpdv.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2sxrgztcc.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogggtbgd.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2zelfrmip.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2ialxiais.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dundeelb.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2whoyuiyw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqnvxya.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhmgmmc.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvigizgb.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhqhyhkr.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2hesmfjbf.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2urindkrv.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzojscya.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mraajpkp.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwwvqtyz.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhawsbes.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2pazewnsh.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2glrctflk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2steqjkos.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqtiqhj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2inyguaky.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qfebeqea.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2kcdhigwt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2opcwzbdx.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqzcqbgh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2gtqiajwk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2ieskfrnc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2qujnvbpn.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2imqxxvoe.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2yemjnide.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2skinfsku.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2wemixfph.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2efbwqhoo.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlyhgsbe.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdpsshy.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2eylcaegn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2hiejsdvo.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2qemvuvpi.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilphbkzj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2phgkdrcz.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2whrugtsa.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2riyqxker.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhekltv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdlnwdu.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2aiaqlxnb.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2yexyyzev.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjejahx.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2crxorqqq.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2yoebfxxf.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrapvbr.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjifhcc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpugfeut.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhmnwku.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2keunpgsv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnufcie.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdbwlnh.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqrqipsb.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2qccycwsn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2woybdzgx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vygcjkzv.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwllognq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bixiefea.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdznspm.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gmpgnauo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2pewsmadu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqeikrno.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnafuuz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkrktai.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2awwklzfi.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqfdtcyd.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdpwevbt.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgjoqrz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2brhdvkoz.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2whmsjpok.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfsjfmpl.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cawlfvqf.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjmyjqc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhgipbe.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2orxzbdsz.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2itsejdye.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2obizwyfb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2caxtncwm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2aficayvt.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzcgtvj.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvbqeyh.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2dievrfru.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jawkjyka.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfhpoil.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzqdzqv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2bstusnup.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdujgzi.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtscgik.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2aajmdtbk.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2ynlfchlj.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2loknhbpp.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmzbidc.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtraony.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zendnjsz.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvoszpz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2udpgupxl.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfslzxiq.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2cbsvsjil.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2gawfnquo.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2usgpceot.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2bofwwptd.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxugssnp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2omdttndd.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2skuptxpw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmfeyxo.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpkynhv.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwyqnlv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqqwfag.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vtcqhdob.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycesdhjx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqhtgto.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvvbawf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmivrjgf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvzatxi.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2pgppgfqj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggcrqhvm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2qjinpbrl.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxgtjlx.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmfyckb.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkhnigzt.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2nfekbkxk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfccwpj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2jsuwoqrg.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2hoxvpjil.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2hneltuuf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2feizwkae.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kjfpdkub.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2kurzcwao.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmcvjvgf.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2skipslvk.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbmicexf.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhxxuut.html


<!-- 参考信息 -->