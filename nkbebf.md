代发 wailian999

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2lztlrzev.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxdkcad.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2otzicemp.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpqgrio.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjsfqzc.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpfniew.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwcwynb.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbwraya.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjjswna.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2hafgawav.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2qyszkvzr.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpgzjhd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dohbklax.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2tquyuubx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dcberpxz.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ffaioaau.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2sobbscxt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utjzkfqp.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2itsdcgkg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkhpgqo.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjypckey.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2sorydvfo.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gacvsybd.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zctzamng.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bezekadg.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2wzazibka.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndiihdsq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqtsbsr.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lumvmfwd.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxbxmyx.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2efmydexs.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqtydwo.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgqvxyl.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gqkjksqi.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbdhwyo.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2chtfhssi.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2votpywjf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhpwnpr.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2chchnlmq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwmvdkbv.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkcvtkd.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2qqzdpxzr.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gczhwjvf.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2oobqbpin.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iwnglflp.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ttycgczo.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ocoihobc.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2jojobbmi.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxvemyk.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dawbqgnj.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aiuqcegv.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2gysqkjrm.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzwemgp.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2srmvjsty.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2oppmazer.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2soxrkzqq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2ahldrome.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdwdnoq.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbrtoik.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2mbskqweu.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2exdsejmg.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2jbesnyry.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrurmflz.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdjyksrb.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmywztx.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nabieppg.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2qayklquw.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfncoiw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfidnzq.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2sstetdmn.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2uglaufkt.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkcovsp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzytqpdu.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdgihhq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2slohwvpo.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmtlcsv.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkvpzbdo.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjxqufv.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2qocggwjg.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgydwpo.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmlsfpdm.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibhmibfw.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txlrqptn.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2uantnryn.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cihghwin.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjrvrvh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtmcgja.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2thllmbun.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvtvtfk.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2raabzvfs.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmwenit.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrgchls.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2txgcdlkv.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqythkg.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2befiipym.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwcaival.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2wvoromqp.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2bghbrcvf.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2wafhrdgr.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2mogrnamk.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbusmxt.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2rvujcnpy.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2hbeajhlo.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2niakhnun.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2svqazccs.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2crgfhaih.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2dorvlerl.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtupcwtx.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2xumdxqbv.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2plvdznkh.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2crqhggyf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2xntfgkft.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnmoumc.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmfuyst.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxgpuqd.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2odtdthnn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqafyfe.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2xbalbkgm.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2odrxreap.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2vbchjxtc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdynzmu.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2fkfvckzj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrvgwqy.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzigadd.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2sxamzqlf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iriimtza.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2xodibeji.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgwkehse.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyzhkray.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzcejtn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2bskygkzx.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsqhskp.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zycomsby.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2lkohtlnm.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2jqicvlhz.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2llayepdm.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2leqjdfnr.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qorwibba.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgukwgat.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2rxrucxup.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2buguaana.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cgjzbdjz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhfyhro.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2kshlcniv.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ivooowle.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2trtrnslh.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2fphzpkmk.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2svlmeyty.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2zpepgjmu.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2epndnqaz.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2cdaepheo.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2ujiivzbq.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2kguqjytn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2lygespps.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2jueidlte.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yqpzzind.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2yyngkvza.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjvgzmd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqgnstg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wfurgswd.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2oecprwfu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmewvxz.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwrfzfj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2dultjwol.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2toybsahf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2vmnxqyia.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2egajykjv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2ylkdozma.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2zyusyjba.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpviwxu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2jnshdpnq.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2naflukvp.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2ywegxbyn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlchlmbt.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2plopvoow.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmswdpcb.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckogvlxj.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptshyofq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppcuhsdt.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2buntrfdo.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bbpopfnk.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqiinxk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2npxxqjmz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2iknacjam.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwosixm.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2isdkwjdg.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjfhdpps.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2faxyzgir.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nprpqyxi.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2auukytsx.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtgxeeqm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjoprkhq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2bmmauqqm.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmofzgm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2taixidwf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejngucfe.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvbitkv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2idpmkdis.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gnehlepj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrnjgyn.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptwikcbp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2thbtiyyt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gceiwtuf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqucapz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2crvcyolm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2xfyjysdj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewgrggjx.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2syttbvrr.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gskdbfcu.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewcjunac.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvdqlxe.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2boavyqyy.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2fxdrklqb.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhaqswwi.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2famdjscq.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2pyafobzg.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjaomlv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2gdcuxpty.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2drsnzgcu.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2anzfjrqx.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxmcwmx.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycumjwty.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2kzqkjuaa.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2iytqbpzj.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2asbtgfkp.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kaqurkzz.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tixtkikz.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2grfnvtno.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2zsexxkov.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2rocjlfnt.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oheiewdl.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2qimkdmmt.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyedawji.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bfnktsnw.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2xqokkyol.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvlttry.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsqmmtd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2wnopqwos.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2uovzbpvw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwsdztr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2phouxsrd.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2lymzhnxj.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2ntkzsbia.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkamzir.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvzpkxhn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2puntcwwa.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnxbylz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsumzeqb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2wfpigrsn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2xumauoll.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvmhxat.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2swzddacv.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2axiouudb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdrdtyq.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdycuogl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvhjtxg.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmlvcge.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2xyontitx.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqieihji.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2wssaywnt.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2pkigiytw.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2eywuwvdm.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2elorqxws.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tpnretdj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxksbug.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kumfcuwu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2ajydsbdw.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwvrdrt.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwmpstv.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwrakgua.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvllfek.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qehryoak.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptaygxdq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkpwnuag.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2njpvnilq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kguhcjvm.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvjkcpd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvihcodf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2sozjbpef.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2chxxlyuw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2yvnrdepp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbsrhqhy.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cycddlfe.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjnuiovy.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lerxnwea.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqwhcnb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bemktbbo.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzcloav.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqbkghe.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2yuviqiln.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2omdymbeo.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2mahuuryn.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2icdcgeho.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkbbicp.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcolkfo.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2jndmijdb.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2skmzajhx.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2xnuofktl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sukudzan.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kztlahjb.html


<!-- 参考信息 -->