代发 wailian999

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gapldnbj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ismpkwdj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vitejvhz.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2mjigzbul.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2avfmevtd.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2stivuuii.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcrexqb.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjcefcur.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxylfchd.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2silysump.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wokidaae.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdyrgwqh.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eoesznyt.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2fvajlyph.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2stnoqzyp.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjyankf.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2forqxycd.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lqknolsl.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrizgir.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2lxayeqst.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vjiczrel.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwekqda.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2stwvqmgx.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2myynmxrl.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2pdcxccbu.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2pryzurgd.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2mkelxawn.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2ggpvohqm.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2petiksjg.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2kshcgiwf.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2rptuwzld.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2mhxxbcnb.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfrvwbo.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2xetuioow.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkngegv.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwjabse.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwjalnn.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tubpokfn.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2qolwhtzb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpsjmgq.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdyvwzkp.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2cosyiufi.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2htrbobvj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jirzkcqx.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2weubuxkh.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsuoxtgy.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmhlasp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2mrigcepn.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddbjowfl.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmttqtm.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2rxeyrhxo.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2rikrtzel.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpbezum.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yixvukni.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihcxwidd.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2fytvpqkt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnnkfzzn.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdzukhk.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdtpofd.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2srscgpkg.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uloeynzp.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bguyejsb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhcwssd.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2zbucoyvy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwkoymia.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2knoladbz.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkbfexb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2eecsdyow.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxbhdgr.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2lvaeqbpn.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmtwexb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2arkdivpi.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2zyyibptm.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvambzi.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2unqkvwds.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2fbozghwo.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwbanoa.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ikrwnqpv.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvejtws.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2xurbdczn.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2euyuvclu.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkrqysy.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2opdjsczs.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2jdhhvhrb.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2dmbeumbd.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2diyqrert.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgeyghb.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2aiuczaaj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2alvtspfd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2gsorkicl.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnnrlai.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2yhorpift.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2vfherbry.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2meracgqr.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ndsejjph.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnbqdaz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2vpoojqlh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmzopcg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwvwcct.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2veokxebi.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lngjvajt.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2tdghprkg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2zqubhcbh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhnfbnm.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvteujz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2kecspsik.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2qvyvjykh.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpdxjhc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgwsimur.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhtotmp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjnnnzrf.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgovyid.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2grabghlw.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vuvtrqaa.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2oiloplnb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2uculbbde.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqchkgw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbdadbu.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbzudzt.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2vxepahro.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2mmzzpzgf.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqwqtwgk.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2lozrkval.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2itgguefb.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqvlemf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2iqleflwo.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qplxtmxa.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ligdxnmh.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqyjwew.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtvvxvg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bnnoduya.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fyyhmzdw.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2mldndewb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxfydah.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2osxysnrd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2uegdjewk.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjlgjsn.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2albvccml.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2hztpnqzs.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2eudaqjye.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkupspj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ahbjciul.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2bajtglme.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrwjdiq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2jojgzzfs.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2axeocuop.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rywcvjkk.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrhwokyf.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nthnsbpd.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnpwnjzy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2itbrmvxd.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbigjguz.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kgkbjscl.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2syoelviu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhabmblu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2abicatbr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpuzqjhf.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgnrugd.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfrppuq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2cilzraak.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2myqipzme.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cifathqb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvdrzgh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sujzadpb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2moixwduy.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmzzxwg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqomschx.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxszdqtq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbaydkh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxecrvua.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwyazhn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2kpznavqv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2taossdcb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2jflwcrza.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pntvygbo.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ziortdlz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmcubmt.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2vshwjbcb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfsffcwr.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fmuuypue.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lewbnqyj.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyptysdh.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wkvkpune.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hvsphdfb.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdozrhc.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2szblkyjd.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2onsfkujh.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxdmlql.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwohqiu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2frfpiwyh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvkxmrxz.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbbemtv.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkngnnty.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqkyzxql.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvmdjml.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwrzccg.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyrvngjp.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vjsklcdl.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvczowzj.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjqbnux.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2plmxzqbm.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqlbnon.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2krqyhnro.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2telwruaf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iiboyxli.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gudzvgak.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2alrloopg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhyxlpu.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmuiurm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2klnbjmso.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzbrugs.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwpwxvv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2avndweqd.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwbouos.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2dcjsmkti.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2qnozvlyz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvtbvtcm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2luofqvsd.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2esjjcbcb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrdnfgo.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2efcqndat.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrbjmzu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2knqzsouz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2misdkqaj.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ddcbmpue.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2rstdlzng.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmekhoyp.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2nuxnvgtq.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvxpjet.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqkisfx.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qctlowic.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2niocbmak.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqyfceq.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2audqfnaf.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjdmqqk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2diydlzwg.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnociec.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2umsrcxdh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2ceogqxck.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnuaiece.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2unvvdgpa.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2jiuuvoyv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2oarjmrfw.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2nnguiiau.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxlaztr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmyaqshu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2eandssuh.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzwiith.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2tpodjcqi.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdgltrl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xbcmcruq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2chbmvuqw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mstmwhrk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqmdurh.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmuihnor.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubeudnqc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2chgblked.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ehogxkkl.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmiwmxqe.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2amjedaaw.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2heukmdzi.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ppypxsgk.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2apyqaclu.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2akjqniuv.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2sdlcwvzl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2fifjmnte.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2gooycswv.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2fzegvwxi.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xnkjzfpf.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbmklme.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyfaszvh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwbchdl.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzaggjv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjszqzh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkpbmaj.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfzghub.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2bjycpnyy.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2dilussvd.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ztsqyabf.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqowrmz.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjbxulr.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xufojyrj.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfgqrolq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrmlfqo.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kborvmbh.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2idddzwdx.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2ivcmpgms.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2llzwflom.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqopjlm.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywozsrnv.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2cherozjs.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhpejyj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2otitfozv.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ozluwxbc.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2yqfwolps.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cueewkgg.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2selwider.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zulwlkqi.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2axgaorot.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2csubesnr.html


<!-- 参考信息 -->