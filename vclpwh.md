代发 wailian999

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcoxdug.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwyuzats.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjufpbg.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2xineoveh.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqegutum.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxluxov.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjpdcpo.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydsofjrc.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqdxtro.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrprxgpz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fryhwxxw.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkwxnxf.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldszstqn.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2huuzulbp.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2teyswmec.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrrnttq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2plpwzfkr.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vexyvcoo.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjezybea.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2rmngvdsv.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2flwfqfjq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxlxqsi.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjytrbhu.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvtmkvl.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvjebqax.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdlfgyte.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2unaozbsw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwslevf.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxpmciu.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2obosayzt.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnkjmncu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2utibpmyu.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2apyvxnud.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxcyhzh.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2hrubcxyg.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfrmrfm.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2eibfrtqy.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqcdqqo.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2bswurxft.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfjukaf.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtokpus.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmzexut.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2ahceebij.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijroujyg.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2lloqufiy.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2kwffthkt.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdhrwbq.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2krgbagcv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxrexlb.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2fipgwmld.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnatqzw.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2siqauhuo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2qtftwlvu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhsrlot.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2rirmngvc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2vnyvcpmp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2pijwtbve.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwqsqfy.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2axylrhcq.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2iamhpfao.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvsozsq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gucfpghr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2mhoiymnk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vevvhdqf.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpiomvlo.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2xatmwyjg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2wgegjfca.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvnfygv.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2faxehzgp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2yghmzghv.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2vhxwefwo.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdvppee.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cztkkzix.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjxyyteg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvalsfad.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2jouhceyx.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2poqxeopy.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lydbsoxo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvxqjyf.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqoxhhsi.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjquhkv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wuirvtsj.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwuezvg.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjseuzl.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2whjngqxq.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2pyzibqmt.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzydapl.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2jgcfvzlr.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2eveeapdc.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnbxnpu.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpxwxqw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uoixkshk.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2zddkffds.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lpiqyzvq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2scevwbau.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dsszvozi.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhikmso.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2prlztzdx.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2eskvpzyf.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxcdvtm.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcwijmi.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2vayvahrh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2epceddcz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2zixrhjse.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2aeetubzl.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2duusnxol.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzzvrqj.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvyiuie.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2uipegjai.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlgzpxjm.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bodurdwk.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwumhrlz.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwycxil.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2unsdkgtb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwcjsemu.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxabptl.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ncixofqh.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzggexxu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kavmulmy.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2zrltsfnk.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmkgaom.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsytcoug.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvpsmwj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqizrnik.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2emqnpehm.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjwfase.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfvcjdp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zckbuksz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2kikoecfv.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvsdmky.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2btihpsoe.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxieael.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2osbelfqf.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcrvubgw.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxghmjm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2whoqbcuq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrkxnna.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsasmtlg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnegxnw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgganbhn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2izmyxedj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2tfolwytp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwmhvosy.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tqenakqv.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aooukhwj.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckpatavm.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnbbrkc.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzezkxf.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2baypaobf.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsnetua.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2gpavffus.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2axkljooj.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hltltffn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2abwfxepb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2enjoytau.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvmtcum.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtygjrgo.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrnjmhc.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2srxbrrnk.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2imokdjpw.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojsbcnwa.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qrclotib.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntuqvpiq.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wusbmhlo.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2exxrbsqu.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2snnyctve.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fuujgkug.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2lodipnne.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqoeryrp.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lrspbocn.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2earnvipb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbmlydh.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jllhpazq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2muumimgv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqgknlb.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahxkzfom.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jctjvrum.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2flhxuvrr.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2gosivlyp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2exfdcqfz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwkxgqm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqmavfe.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkboiqbl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2adzyzihu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2prlkjrzi.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2vaitdcil.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2whjmtjzx.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2zmomxivq.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjmlpoq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzwhubo.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxwqfib.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2lpntbcok.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmqnexi.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhiwtohn.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2igzrvwku.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2eiozyfkv.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2jynenhzy.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2smvlkugp.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2rcykapli.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxtpcby.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbscoeps.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjurpxyk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2vgfijsmi.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdmbbxp.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdxbqvh.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqnmubye.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvryjyq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dyheelku.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fsiounxf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjuxpmx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2eidrkvxj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jvkvyuhy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2acbkfwji.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bopzoqau.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2shkeklui.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2bdzadlog.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkkxhsc.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfatcqns.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2frwzljxl.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhssylbw.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbkbafh.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ugjchzwl.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwmlmct.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkcgsyj.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2uorwtxay.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dbyjardk.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkjnnkn.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2rfizjusc.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2auqyydfc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfrsklv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2flgjxunj.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2tckpyxgi.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xlgazypq.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2hyoggrzz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzfjggc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhdlhfn.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdquxto.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdazzcp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2yxachgpa.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2tepiunfk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnmllyk.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjrkhhb.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2simebqlu.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjsjdszf.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpnjnyjz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqrqbuyo.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxapolnm.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2wscxehvf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rflhwnvz.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2yzfvptfo.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2albdkfcu.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nvpkcvxk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqlvkvt.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxduwimu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyuudmrk.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2suhhpicp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uuagitgv.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2habjbcbi.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2ykcpvzbe.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yrprdbdv.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zzejysfg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tppffkvt.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjhnjjp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdqpyoo.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpcsbsyk.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvjrrty.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2dovlittr.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2lecuvdaf.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzchpwc.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2siixcecz.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjktpsf.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmxmeuk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2dqtzqwmx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgctyil.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2ljooflxv.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2qctvrdus.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhvssvz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2qgyamaws.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2edvngxao.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2ziheeiuh.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbygbjob.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuekhwbe.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2doxpyuvj.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzaavjle.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pibfzfqf.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2intducrs.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvunaac.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2xncovkme.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzkzkcjj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2grpdocfj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wskutfea.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2hxybtuja.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2gshkhloj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdmfcoj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2wyuobrvi.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwokhqbo.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfkybdg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2nozkiiyv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2afoyiyfu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hivkmcjw.html


<!-- 参考信息 -->