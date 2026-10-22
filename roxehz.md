代发 wailian999

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgmvjkq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2aslchbzj.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2kgkjbbmz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2eiukibpn.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttyebvuo.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tobavrvu.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xutchxct.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2ethfiyin.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2diaiguum.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfmzhls.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdwdtao.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dndcdvjs.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjncgxv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxybzeip.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2owjwjawm.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2kdclmylc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwypiail.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2htqtmotu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iiktzcba.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xurgikvs.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwxesfl.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2elqboazt.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2oifksqgk.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfjxfpw.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2itxcdrob.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2vqeswefe.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2gdfbralv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2eszzkkqw.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2mzeddnuk.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2axkgamsc.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2grhjgkzo.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqvskgyd.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2cyurtijc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2rpolksqd.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2chmqbemp.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlciwwi.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2nsaoxdli.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2ansaqyba.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2wantlxqg.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2tmlhywsl.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2qappjdqt.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdehmln.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2geerdojc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2onixnhwt.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2jspdnhdu.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2gykmomvt.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eeslggmu.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2tufbbnsr.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2leptogea.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dholubvu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2xzaboemm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2acgpmrfd.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccymyvtt.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhqfxhz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2hostpuwu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpmwwjx.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfjadih.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2bdpycwer.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2cltdwboq.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2jquwlpmn.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkrprllw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrbdjrx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2pozborha.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2jnsframg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2mwuoezvl.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tgtdxjem.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2xsgxvyhu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqltaltt.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gczylgvs.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2stvxysqu.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlmagao.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jadpxmju.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2wbejeflc.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2buuonquv.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2yiifmytb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2qlpmfrff.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2spwsksji.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2vyfjhgxo.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2exvjwlkh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zougvezb.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2xdgivzfm.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mtazjmtm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgmairz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qvcxouzu.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2oetzpibj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfkvmer.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nsqkceuh.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2hsvgdruh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2atzozbze.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ktgzvfrp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfnfgud.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwhyqgt.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2bulmkgis.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ecpvwzff.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2zgikkodf.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xunnqxxh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2dlabnkpt.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhsvkdy.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cupmlcuv.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2diyqtube.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2btsbeese.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfceglqp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxtrmvv.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yihkqznb.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hnrwrquv.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwunwvy.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2amiqsybb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2uxzggvzx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gurmueeh.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmkzcqa.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrobihv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2milxcips.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwydodzr.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jfvrhobn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2agejdwhy.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekoicbyf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2vwswsncn.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvnosmfe.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqmhwng.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2limxjlbh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhuzldq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2injpdjvq.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zulrbocm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2akznvrss.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsccxjae.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2trwcxlzc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjiyhstf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmymhpxo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2dlszawgu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgantds.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcuxroxs.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjhysbg.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmdyttg.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdqdzhn.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jmnqvlzw.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2pvomgale.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2lrgvvcfx.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pewptybs.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2mhyhgqer.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfnkaoza.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dsunkalt.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2afogvxue.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2unrhdzrk.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2adxdyibj.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tczhwjji.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijzkpqvd.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2cvfwwhid.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2atebnvtz.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhmrcmot.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wmaopiso.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pncjyrom.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqwwfpw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ockkdmgj.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2vuatilpb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jahttgbm.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhpwtcw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlweryz.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hdftukic.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvvwcki.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvqlrqd.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccewlorr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrznrsj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzkqqpmh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcobnjqj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ommqmauc.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2knbggcyu.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvkxbzl.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2sgnjtuvf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2itwgixlg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbyhrld.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2syretrmx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2owmttdrr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2iheclvam.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxwxfyz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ensasoyh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2yfnmpkpl.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pizembed.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2aijmhijk.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkzqdvcj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbmrnhp.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2kergdwur.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymchkptd.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgapybdx.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbhdxgq.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2gvvlxooj.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2rprfposv.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2yzargalm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2slfdfalz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbfswvz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnstufng.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2wogxcyva.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsyckglf.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbsktqgf.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhkaipfm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2lufuphvw.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnuqxpc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgftozuz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrevmyg.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2argubowm.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvyqiil.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2szccsikc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvenmjl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nurrupcs.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2fjttljqy.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mfyfawqp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkedabfa.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbuhuygt.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pybjfscl.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rmrnymkt.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ojghpwse.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvaguevf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mptkiphx.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbtkaqw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcacqhc.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgvnvdlo.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2elkoxeww.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqbuich.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtwpvll.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2xtyfdmmy.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2hgrshteu.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2moqriyvs.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmwszpu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhzjezj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2odutxlxu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwqabkp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvtffdo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2ufaltsos.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2jyorywrn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2dvzuvdqg.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2nersuvls.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2hwisvdgp.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhmtugw.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2grgqdsuc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fointnkz.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2evwrsaec.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvbzawgk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jiokgssw.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2jeflysac.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2jytcsaxw.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbdftrw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2qhktlxhz.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzrvjmwp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2rscvsrjf.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2qfylxinm.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjbpymv.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dyeuqqei.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2cefesmla.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2omdkytov.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2accgnyih.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcmmwen.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvbphcf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2aepgxdxm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2dinqfbel.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2emxzrgbl.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2tycksnnb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjzxjkd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2dnbdptda.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmjegrr.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hirwkplj.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uehbuqat.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2txbnthyg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2goyxieea.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2bkafccso.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2iqgrdfwg.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvlfjhd.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2pnufwrln.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lrovtmup.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2wdclouyw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcutogti.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xncznlnc.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjixfwv.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbssusyd.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eebnngyk.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gduqmzsg.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hudxhdwu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2jdhalebs.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2btuesiar.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtyslol.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvluwtgl.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2lemfymli.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcpyedhs.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2msenoyis.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnsrpuu.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2paryhhhs.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2uclvegwu.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsvxayyd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2szscgsex.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lybadhmy.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmkljci.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybygatyj.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2meeulaab.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2ycsfxprk.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hszdmhna.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ddbuxrij.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgdgmwy.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nruskoat.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtmwxvz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpryfzpc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxqhwus.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzcqlrbz.html


<!-- 参考信息 -->