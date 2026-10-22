代发 wailian999

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvcsnct.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2laxjsloe.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2olwlpbll.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2ubnfxvep.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2igurczyj.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2gpzqcaao.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2utrfqakw.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhnfsnp.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2kzuwxmyw.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2diloyfbn.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvlajeu.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkwevthw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgcjxprv.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ioilqgzb.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2stleyghp.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2moynoahb.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrunrkwt.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2npgngigx.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2coorsvtg.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zspahcva.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqpxaik.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfcmaul.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkyxsoc.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2yxyjdbam.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzlbelms.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2rkfooeis.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjdnbhm.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2aupbnqpz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwnuwnoo.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2snvybizk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2shzmlloi.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2dedfucvb.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzihwjub.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2htjokved.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sphnozgf.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbwvymd.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqguhjb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pekhorru.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2pvajdzmd.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2kfarwcvi.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzdcduz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqjhkrw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvaqodrf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpvzmjto.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2wnozkqve.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2toatgvks.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2iwuhwkcr.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ptwfraiw.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2eknojecg.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2gtoedyrg.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbhxgdf.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2wyquzwrn.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2qducqudm.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2zkaqutbl.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2zmfmxlvz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2oaswsfzf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2hcafqnce.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwuvxly.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2eatlmrio.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2vzyoaexo.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtoesyu.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdaeifu.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2nmstmsxp.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2hvrpkvca.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2lsigedtr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2odjuvqzh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2xjohmevg.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2upskajom.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbhmbbr.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2rjfpwbfi.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bztumrws.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2yerhedwf.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2spgfoupx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuaokgqt.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqjhfuk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjckmhva.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjncykee.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxgmgtq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2zttnoaga.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhgvlkau.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jxweuqvn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2ugsbbvui.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbmqmec.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2jkaeywwj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdevtrst.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mewaxqku.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2etosduas.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2jioqldrl.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2yereanlo.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ceozhoud.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2gunlstbd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqkzyuc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rquetdja.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uoxnkwpj.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2evrqqpoq.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2dynqisnn.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqafmih.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkspwkld.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2efkdhlgu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2otkwahde.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxcvqmt.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2vgvirjmf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2jysxwcav.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2znfindct.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2xylnwkew.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dhclgaxf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqlsewd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ucjpetmy.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2bzhucdqz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rweyjjlr.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjtnqzv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqubifx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2caeukihe.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2jwgfapwt.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2fymprtsz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2ytcyqdoo.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2tuljriak.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2yndqwvsy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2dcqljyux.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2phrnxqbg.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjcffxb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkjistp.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrrvdai.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcsmbsao.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhldjzjk.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjtbmte.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdsphvry.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdobvzt.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbegmby.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kowoxwko.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uttpcehx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2krcxcnkn.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kphsiilj.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bziusjyd.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2lakdojjz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbsuwpc.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rptescem.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2spocfhrt.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtjfnew.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2llwkssak.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2vldtipcs.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2czeqlqqp.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2metjsblh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgtnruu.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2haxomhcw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgejajxm.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lxahsyng.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2dfbadgwj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdurecgu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfmayast.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqiusbkg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2gncetnqe.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2sjsiwglx.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlzmwrt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2feszrxta.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mwacyclz.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtnrsuu.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocehpkla.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfpdevy.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mrpftotv.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2kijcdfye.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2htauyaqe.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2vscdncsm.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbkzlmhc.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2olgzrbfl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2pqsbtbrx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtdpvaxk.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwyyjfm.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcynuvme.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vonupfxt.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfomzcn.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmlffux.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjvrbsx.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2juocxrkw.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yubzqtus.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2biplvvja.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2abbvwfnv.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnmafey.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xlckunic.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbeumsh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2repwwtny.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkadoay.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2bnfjznal.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtczilk.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hddrrvsk.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2gcsjjxrb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2nefigsks.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2behsyqlp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dajfhmpa.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2elkepzqu.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2mjgfkytg.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhgbcja.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qskydgoa.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdbdzqn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfrewmtr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvexfts.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2seanieyd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzthfbt.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfymhlfb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxrxhuk.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmhugoj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzcsncj.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwpakcr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2hxrgvxoi.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2zwcoowyi.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2sznovovb.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzexgiho.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2envegmpl.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2czedtqfd.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmaeddt.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmgosdq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uavfwopq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbaroits.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjmttzm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbucgyl.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgoedqyq.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkzwedon.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkpfexvz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2gxcenfpc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zxlyqslk.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuyzzsht.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmparcts.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fiofadon.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2egdkugax.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvgtrmc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsivgfkg.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfxbrdk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjthcoe.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qoswtjwh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpslnhcb.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnuomenj.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrovliat.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ysexqqgj.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hmnpdlas.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdhnxzct.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdgabje.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2wchxtzwx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2nymdlgmb.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2utpgwfdx.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2epdxszur.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2gualiuqn.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2wwpujhpz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2erkiufln.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2nyiodqca.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ijzetrbd.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2qnwzrqcj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxgtfwgh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kuixcduq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqianvvs.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdukwxcx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2gxybfxnm.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2kmgmnerc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgyfiyd.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvrhxkt.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2kiamnvzp.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcchvdnr.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwnpsza.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iilvyhht.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jesnxvvy.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvldixu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyeimpar.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2dledwwkj.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2hphtutpe.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgmvasb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2dynpskko.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhckaige.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2clqrbtls.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2wyivzcgt.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rkhuhnvh.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxfwitt.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2iuvkvrao.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wzunmiya.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwlsxwi.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgapkcas.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2wzlesiqt.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2mibmpnsp.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhquryv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2cojkwmol.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2yifqbkmh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2oepclgeu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtktcnk.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2drgxyyyd.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbjazwjz.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2empqbvqc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnwnifw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ulrnremk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2jgctpvul.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkvtnmw.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2syvvgedu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2xjtkhwjv.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2umqbpcdx.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2bhncdbrp.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwuimevc.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvvcxgk.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpewche.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nviqloot.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdtntsod.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxmtdif.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nukkhbjy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2rckdtzmx.html


<!-- 参考信息 -->