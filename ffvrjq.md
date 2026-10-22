代发 wailian999

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqjprsw.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjytqxk.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2pftyikdf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxwepik.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvcrpmq.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2scywmzke.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2mahntjdx.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnruyobt.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqueijzi.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfaehwvx.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xjgsuguf.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2xjyrfbyn.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2matlvyux.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpspbrt.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2kivmvyxe.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxlaojo.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2laukbrjv.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmjpyvf.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzqjuwdf.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2yszohqpk.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwncwri.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2elvqwmra.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmkokxgi.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xnkerflh.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2amhlllnf.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iibbinyp.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjvrchr.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2riwfafts.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjxguagd.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2oexxytbx.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztybynbd.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mftiyegz.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2utasqoci.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2saehrjhq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2lczlqbyb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2swjrksur.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2szvvofxz.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2otjnjtgt.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2qomhqgxm.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2qwryfbyk.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2yloarzdg.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2udtxfifi.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2rsljslmm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfxxvoc.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2axideauk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2srmvcdqa.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjlkkiec.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2axmayytq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2ktcqqxfx.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2giyewzix.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2jflpdqww.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvajblu.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2crdrsqij.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2slueeosu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2tphttwre.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2yhzbovza.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnlwkmp.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2msawcxqt.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ilccirch.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2anspccxj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2axfhnysw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xauigffk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmhdsos.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2twqpieut.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2paoqjesn.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2gdpjvwpi.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2rvnqdgna.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjtsthe.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjlqral.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzchmnn.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzvlbkr.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2bwuamrjr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkcqbek.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2demyqomz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjfadih.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmlwpka.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2zzefqbuy.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzwizue.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2pjoxktob.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxorwvv.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hgpzzpfk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2axyvumdx.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2tejfvmav.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2tfbodkep.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2oaibuupd.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrjeyhm.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2oiyujncx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2isvddqwx.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2pxyzbmbz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvzihfh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2djwbrhgz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2taibnjob.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrbaamz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tmcdxhiz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cpaxhcdj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzgtfts.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2tuchcgcg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nneuwirf.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lmcmimzv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2dojyoczo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtttkje.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2lxagizvg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2feljaiee.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqllado.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2cxrdmwyf.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvitwtl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2bavarlfv.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2hzrfmpmc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2gboiqaot.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2savrwzgm.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngekaafr.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2klpiwtzu.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjizqkvh.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rftfirty.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqtcymuz.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvxtlokz.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdjtngw.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xneaomzx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijucumvu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlaslwg.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mctepspj.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2esxpxjvu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxeopclz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcggmcep.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzrjhec.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vjnnyscf.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxetiqsl.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mskkzhtb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgwnkfx.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixajhpzm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfjwezt.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhklnkuo.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxyxzre.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2svhclwxw.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rqgevcks.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhzfbak.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ancikwxb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfscqusz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxzwkgau.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnsdymug.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2eccvkauf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2usvvaugu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2jopqgsdp.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rcclbwoz.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvofvnh.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2grcsilvt.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2erpozbid.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tljuqcpm.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2ejaroqwk.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgdorsjm.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmebfrd.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsemrrhw.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nbpfdzov.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2erfpknsv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uuleavwh.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2exivrvnn.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgthzpot.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2limfqyha.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2saoywcui.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2unokykzg.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2iymuirsz.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhjnkmo.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oeoyymsb.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2miarainu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbsedssm.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2gbshulra.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qcozcrqy.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtpwzbf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjzmqxh.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2shquiibz.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2cyylfbgu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2uhryfsgt.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfefbat.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2qjhfqkxj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpacgmme.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpncvkpi.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tooeraxu.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzyekmw.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2ekotqdyk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmjbtjt.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fengaocv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyzpqkwh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewkoacfa.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukklzfhd.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2iuzxdpqm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwgdxdk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfoqlipo.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ueslzlfo.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2djfmndkc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2okwinwdt.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqsmegm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2muvhacnp.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhibrky.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2tyztvvvp.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmeakcyg.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2xznowmno.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2dqirhnze.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2madlkqzf.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2casujagh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2occisuhx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdbpiown.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjavlfky.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2uttuqcqw.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjutbhwx.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pogjpver.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsbuncbs.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfofqvo.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqtliaq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wsplorlg.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2umtcqhkx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxdffqxn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2foqwmqlg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2hdpsdrxg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2taxtevpj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2upqfljyx.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2jfoirlbk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hiadbmfy.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2isssseib.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvdkvea.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnyagcfh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2suvufxwh.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqshlvm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eggoxyqr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rjswnmyp.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qirvxxdc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2rprzbmtt.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxmpaaai.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2oiynbhlp.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2obgohhzx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2cmldkfvo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2uljmrgjj.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2awkjubte.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cbomnnnq.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2gakjgkca.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnfyjboc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ardsppwb.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2orfcvjsj.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejraepnq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2fttvilqo.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2seahqjcj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2fuywzekj.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrcfpif.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2deshhghy.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qerdbsge.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwigflin.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqitdel.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cusbcgno.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqsuxyn.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwkqmyg.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2msodyata.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2oexyqeoq.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2iunksxdx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2kwyidtba.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2qckvgrzz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylzdtzxp.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2uessugsx.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqgdujs.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmqznyd.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2qjdcbzju.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rqyalici.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2fpwlqplv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hruryzuo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnxdhku.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2hepxgiey.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywrkchjv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvpcvve.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2wdizkibj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrbqmmr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2unaxhomj.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2ghgiffbl.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjfsgxh.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdxvjep.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xkoaqtzp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2iunbbflm.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2bjluptuf.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2qqzoufji.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2igccpily.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2vkmimhtn.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2epluuunm.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2zqeykiim.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfekqxh.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbrbvaw.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwurfst.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2musqwpwq.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbftnhrw.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzxyytmv.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbxuukj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2blidmspp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iuotusnb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2rkaahaga.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzcqtpzn.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2rbojxaej.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbctnvvr.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmzlbao.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnkdvwb.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2larnibji.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2ipalyfad.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwdtufq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2esczlztt.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wugyrtsu.html


<!-- 参考信息 -->