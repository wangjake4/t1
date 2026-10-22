代发 wailian999

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2fuuswaub.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjssmbg.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2upoxrjqa.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdbjqfr.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhuayrr.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2orntccxc.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2lnzsglwh.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2edospbzw.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fzsiuklh.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2oovypxsy.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxzrdvf.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2doxgxzvz.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhsjwrkw.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2tpbuhgeh.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyiflkwu.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2zllzmhxo.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2weobgxtq.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqfyexd.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2bcluctzz.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozomowqc.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwzuyck.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ielaoxhs.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjegckg.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhiclil.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqulozww.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghtkullb.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqquazk.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2tadzjuxh.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfyxwiz.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2fvahbqsz.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2hlaijuhj.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2rcuwgivt.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwomjiu.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkegwtk.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2wxabddli.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2grawhnmt.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2elsiytga.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbejybu.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2afefxydr.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhetjlw.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzjonco.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsrscpt.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfwbaii.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2sunrbhic.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2smzsredu.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2mkeyqagz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zteopiws.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2onrlwoqr.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2vxsjrvbz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmgtckmg.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilpxouwv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuacronq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyocqzxv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsnzmnxj.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdtetos.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bejiajyo.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nyguvavz.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2cujmoxlx.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnexxrc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2shyzifrv.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqzpdyb.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwkkrbb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vguspmaz.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqbvkog.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpyzgnkj.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tbagewsv.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjmgdwt.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmoxoasi.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdtwgxd.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ziudtlbv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjgcbuwv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2qekricwj.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2apntmluc.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzgggsd.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzzojft.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrmxbio.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hufjfziw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bibdexuv.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2wwykwaxr.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2bwktlpkc.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vvaseaff.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vslfpfbq.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2geqmfjqi.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2ztfchbfo.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxkczkp.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2lilkiaat.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxwjpip.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2mangghxh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2fwkkzfrx.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2eqxbfdxd.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2imixcwun.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2ritfldop.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqiidca.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjqecha.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbzklrf.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpisxlhe.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2uypedvff.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujyssgcg.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcpiytpd.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzlfizmt.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmzjbgr.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2kzkpmgek.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdzjbop.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyikxcse.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhvsrzh.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2huyvfsel.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wmpfvqhi.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2nivhnlke.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahtshvfy.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmvrkux.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2qlcbzhrl.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdqzdti.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqylhzd.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvjjtwj.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibtquihq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtiynxv.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vokxplmb.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmnjjxz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvurggl.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hsossavi.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nltwzeoj.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vprvaydq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2grcmqscx.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkaxbdd.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2spsekmtb.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2miykaetb.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2txhzaxpw.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2clzornlg.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjjlodb.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2hekyhuim.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2ereeoffo.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2fnyvbvlx.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2sckrqfru.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2utzakvvq.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2mudowrqy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2szffagrb.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2vttffzuq.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2cfyivlyz.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2rffyiduc.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxeqcxsp.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2rjebjpfa.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2hqpfkkma.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbadpjsd.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2zhriwpok.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbxqfzb.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2yyefocyx.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2yersvljj.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2hfakyeuo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2msnlniep.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2sbothhmi.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ggonupwp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2bsdwobyr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2xawmvfxn.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmvefhm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfmkgrx.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2psxdckfm.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2gceplxla.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwshgwqr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2jhnukogq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwujwhm.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqglawry.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2afwzjphs.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnmxlbh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2zebnqdpb.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pnnkvhrk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2aspldjhn.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2adlpgdnm.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2alxpzxvr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhubhaiv.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlsjdrtm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyugidtf.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2aobmgylp.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2kazjnroj.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqbhvow.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2mlvmhuvo.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgzbkjo.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2davuebpx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vswdrpyt.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jcydtlps.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2hefngltw.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2blqyafnx.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfhisgh.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfjlfbz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2ychcobwa.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2ddqzticc.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqceswy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwhnbrj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sawocyye.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2xiasesyh.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbhrdbp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2stftxdoj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cfygcbvw.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2yyaeupzp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmbtfnv.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wauhxayq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2drszdecp.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtoobnp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2osrsixus.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhfdvha.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2fpytwjvx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2xgmizsyh.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2uizyotwr.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnmbgtv.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhfqeno.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkvsqei.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvyxysg.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdtcfom.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrwhbmt.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2agueuged.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwmokku.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwbdfpb.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzeuzcd.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nmghplpt.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2aopabhfc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rposcqdf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2jultxkuq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbuppirc.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2grizimpq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2grxgkjzy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmzloloa.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvjkiad.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lszjjogd.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddcfqlks.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2isdgiruc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzuywby.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2piyguuji.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnoxghmp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2asazxgtq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmziwsxo.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjcnwvco.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2venbbblx.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2tgryrcam.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmyunvcr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2tywckkiy.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvpgjvyn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2lihketjz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2cpgxbdbm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ykaknwgd.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2luchvvrd.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xdrdynam.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qegviyqn.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbulxpzc.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdyrnhv.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgfkclc.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjybpoa.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkdpyfi.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2wcskctlo.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnimzwyx.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2uoakerbn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2qjoxaznu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcsnceek.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2aedokmmz.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mogfsngx.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzyskkpj.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2blrkdung.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2iepidvjh.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvmbrhv.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjubouw.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqdoxviv.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqiqcdzx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqqlipva.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2fegbggae.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cquzmgxv.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqovlhhq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhcibyf.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tunxqtbs.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2luwncwjq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtwbdcx.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnrojil.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2enykzpsa.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwllbrrd.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2rghndkti.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdeorcyv.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2tmgijzod.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvkuowe.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2khxsepug.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybsnvpzc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgktcru.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtrwdtb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzhymoja.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2tacuknru.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2ekehlhfy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2kppxlnyk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2utkiicsq.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wqdxrcsh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2eiqralyt.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gffrkzts.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2bhtevhtx.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwxlodi.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdaossjo.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2djqdrzvi.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2fcnflbhu.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2yzybhkjg.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfbjebh.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2luhaxhzv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxrtbxcj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yppbjwyj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2oiejhqrg.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2frgbltly.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xaijrfeg.html


<!-- 参考信息 -->