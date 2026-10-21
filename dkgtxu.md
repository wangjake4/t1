代发 wailian999

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxinkj.top/Article/details/gtxtkwjwnb.html

Java: x instanceof Number
来源：http://dali.shzxlz.cn/Article/details/gtqlryxblr.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.bjfxy.top/Article/details/gttaavuuol.html

Ruby: x.is_a?(Numeric)
来源：http://dali.svipenyu.cn/Article/details/gtewziiecu.html

C#:   x is int or double or decimal
来源：http://dali.gzhubu.top/Article/details/gtxakchnbw.html

[B14] 判断值是否在集合内
来源：http://dali.ivvv.top/Article/details/gtshhpbiip.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.guannengcc.top/Article/details/gtghdcamkc.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yj202588.top/Article/details/gtxpkqmopr.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.fengsongda.top/Article/details/gtzzsfrxli.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ydzc1.top/Article/details/gtnieauxyo.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.birdmap.top/Article/details/gtuffthbgn.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.havefunace.top/Article/details/gtyxeplucj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gtdtokktth.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.chenzaomai.com/Article/details/gtxugysies.html

[B15] 布尔运算与取反
来源：http://dali.mhx1999.top/Article/details/gtvsohvzyz.html

Py:   a and b or not c
来源：http://dali.zhoulong.xyz/Article/details/gtypvybyez.html

PHP:  $a && $b || !$c
来源：http://dali.birdmap.top/Article/details/gteemencxu.html

JS:   a && b || !c
来源：http://dali.guannengcc.top/Article/details/gtyorfptyk.html

TS:   a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gtjtphwsjb.html

Java: a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gtvdezcehq.html

Go:   a && b || !c
来源：http://dali.yuxming.cn/Article/details/gtonfuinoo.html

Ruby: a && b || !c
来源：http://dali.hnqzz.top/Article/details/gttddmwlwo.html

C#:   a && b || !c
来源：http://dali.redwolf501.top/Article/details/gtkqpfmzgi.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yanxiufei.cn/Article/details/gtyayzkxyq.html

Py:   if not data: return
来源：http://dali.zhixingplan.top/Article/details/gtmpqjszfv.html

PHP:  if (!$data) { return; }
来源：http://dali.daria6918.cn/Article/details/gtyquytgfn.html

JS:   if (!data) return;
来源：http://dali.pengpengdd.cyou/Article/details/gtfamqaktb.html

TS:   if (!data) return;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttnfomkjw.html

Java: if (data == null) return;
来源：http://dali.yanxiufei.cn/Article/details/gtsbodilmw.html

Go:   if data == nil { return }
来源：http://dali.tianlin.xyz/Article/details/gtaszusukl.html

Ruby: return if data.nil?
来源：http://dali.nanxuanxn.top/Article/details/gtmdzhwacy.html

C#:   if (data == null) return;
来源：http://dali.cdnleiting.top/Article/details/gtjdgnqmjz.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtrdahyokv.html

C. 函数与作用域
来源：http://dali.hywenlv.cn/Article/details/gtbfrifohh.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtqgnyckwi.html

[C01] 定义函数
来源：http://dali.quarkkingdee.top/Article/details/gtpjzrxyws.html

Py:   def add(a, b): return a + b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtspbapiij.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gtvsryfaar.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gtydhotioi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ivvv.top/Article/details/gtppwvzdli.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gtmsweluyv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yuxming.cn/Article/details/gtczqdhfrh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.pycfn.com/Article/details/gthhznqnzk.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtnbkskkge.html

[C02] 默认参数
来源：http://dali.jyoumei.cn/Article/details/gthkgbdzvw.html

Py:   def greet(name="World"): return name
来源：http://dali.0kj1m.cn/Article/details/gtkotxhkwi.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.kuanghao11.cn/Article/details/gtfjuedjhh.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yuanzhike.top/Article/details/gtdazrojai.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xinyue.icu/Article/details/gtbverfhfe.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.gaohongyu789.top/Article/details/gtuqnysbwx.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.feifeiyinyue.top/Article/details/gtfuudwnsm.html

Ruby: def greet(name = "World") = name
来源：http://dali.wangdashe.top/Article/details/gtsixlaegv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hammf.cn/Article/details/gtvrxcfrpf.html

[C03] 可变参数
来源：http://dali.cashguo.top/Article/details/gteavpgljm.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhoulong.xyz/Article/details/gtsjvkmcvh.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.guowangkeji.top/Article/details/gtqzicyprl.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ppjwa.cn/Article/details/gtyeklgnhs.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmzerkpec.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.havefunace.top/Article/details/gtuwpazxkq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.0kj1m.cn/Article/details/gtbwixmynu.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.shangyingyoupin.top/Article/details/gtbhefeyig.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cheryme.top/Article/details/gtsesqtbdq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.fzhhl.top/Article/details/gtohuvkjba.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.dashuyun.cn/Article/details/gtkofeorft.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.chenjidiqi.icu/Article/details/gtbprquxtq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ybcxt.top/Article/details/gtneafecjr.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gtplhphxoe.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cashguo.top/Article/details/gtjujbxmlo.html

Go:   // 无：用配置结构体参数
来源：http://dali.nanxinkj.top/Article/details/gtagclvyqm.html

Ruby: f(a: 1, b: 2)
来源：http://dali.pycfn.com/Article/details/gtvzjvfwrj.html

C#:   f(a: 1, b: 2)
来源：http://dali.xinyue.icu/Article/details/gtzjketpus.html

[C05] 返回多个值
来源：http://dali.zhixingplan.top/Article/details/gtabttvvdc.html

Py:   return a, b
来源：http://dali.ivvv.top/Article/details/gtndscyftr.html

PHP:  return [$a, $b];
来源：http://dali.xuanzx.com/Article/details/gtzzsdrlug.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.dianchejie.cn/Article/details/gtgkejelhe.html

TS:   return { a, b };
来源：http://dali.andypj.xyz/Article/details/gtehxeuxcb.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jinqigfzy.top/Article/details/gthsjqyyow.html

Go:   return a, b
来源：http://dali.vqdsnc.cn/Article/details/gtmmrtnwby.html

Ruby: return a, b
来源：http://dali.hammf.cn/Article/details/gthqupvndn.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.guannengcc.top/Article/details/gtvzoxocax.html

[C06] 匿名函数 / lambda
来源：http://dali.0kj1m.cn/Article/details/gttscobluq.html

Py:   square = lambda x: x * x
来源：http://dali.jianghu66.top/Article/details/gtxmmqopns.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.guannengcc.top/Article/details/gtdicicytu.html

JS:   const square = x => x * x;
来源：http://dali.jiagoushi.top/Article/details/gtuclzqeym.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yueranfly.top/Article/details/gtrzjgllty.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.chenlongwang.top/Article/details/gtjcbjwfpj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaanhcgew.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yj20258.top/Article/details/gtitdzlhyx.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hammf.cn/Article/details/gtdeehvaqi.html

[C07] 把函数作为参数传入
来源：http://dali.hysaishi.cn/Article/details/gtufltauov.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jqgufenzy.top/Article/details/gtychgazhj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.fzhhl.top/Article/details/gtrfvgrijy.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gttkysxsmu.html

TS:   arr.map(String)
来源：http://dali.guannengcc.top/Article/details/gtzksanudz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.redwolf501.top/Article/details/gtyacppksc.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.guowangkeji.top/Article/details/gtdzgasbky.html

Ruby: arr.map(&:upcase)
来源：http://dali.yj202588.top/Article/details/gtmpbbnpdj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cucudq.cn/Article/details/gtxbwqjlvp.html

[C08] 闭包
来源：http://dali.sxryk.cn/Article/details/gtafabzhkw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hywenlv.cn/Article/details/gtsjmrlbxi.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yj202588.top/Article/details/gtngrkjdap.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hywenlv.cn/Article/details/gtbhnxlgkf.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zycfv.cn/Article/details/gttmtozkgc.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shanyushiyangtech.top/Article/details/gtxoaincli.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jqgufenzy.top/Article/details/gtylxelehk.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuzhhrauu.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gogol.net.cn/Article/details/gteorazrir.html

[C09] 递归
来源：http://dali.yongpay.top/Article/details/gtlkunostz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yj20258.top/Article/details/gtiekppgcn.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.tanke756.top/Article/details/gtanifranh.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtidtupsww.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shuidangran.top/Article/details/gtdxzmmaka.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmsnawfnn.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hfpthk.cn/Article/details/gtrgfxfpjr.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtnstylnby.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.kuanghao11.cn/Article/details/gtnactorbu.html

[C10] 变量作用域
来源：http://dali.shzxlz.cn/Article/details/gtrhpjjyno.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinqigfzy.top/Article/details/gtqklehrud.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yj20258.top/Article/details/gtsxgrlmci.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xziqi.cn/Article/details/gtwbwaksbf.html

TS:   同 JS
来源：http://dali.aibaodan.cn/Article/details/gtnpctoppu.html

Java: 方法内为块级作用域
来源：http://dali.zhongyouzk.top/Article/details/gtmdmlkjut.html

Go:   花括号块级作用域
来源：http://dali.vqdsnc.cn/Article/details/gtlsrmnznw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hammf.cn/Article/details/gttxijojse.html

C#:   块级作用域
来源：http://dali.chenjidiqi.icu/Article/details/gtuoqzbxta.html

[C11] 模块导入与导出
来源：http://dali.hongshengwenyu.top/Article/details/gtsuacqisr.html

Py:   from module import func
来源：http://dali.jiagoushi.top/Article/details/gtbzmibbaa.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.fzhhl.top/Article/details/gtlkgwtpwu.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jqgfzy.top/Article/details/gtzjwwumrd.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xylfe.cn/Article/details/gtywqkywvq.html

Java: import java.util.List;
来源：http://dali.yuanzhike.top/Article/details/gtispcvorw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.nanxinkj.top/Article/details/gttubgowxx.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.sysykeji.top/Article/details/gtrgedgnat.html

C#:   using System.Text;
来源：http://dali.pengpengdd.cyou/Article/details/gtpqaqzlek.html

[C12] 立即执行函数 IIFE
来源：http://dali.feifeiyinyue.top/Article/details/gtywipkceg.html

Py:   (lambda: print("run"))()
来源：http://dali.redwolf501.top/Article/details/gtxhkdrwhb.html

PHP:  (function () { echo "run"; })();
来源：http://dali.aibaodan.cn/Article/details/gtiqhxpktq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.andypj.xyz/Article/details/gtqbwwugpe.html

TS:   (() => { console.log("run"); })();
来源：http://dali.gaohongyu789.top/Article/details/gtitnxfoct.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cashguo.top/Article/details/gtnkpxmrkh.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.mhx1999.top/Article/details/gtonfjsozq.html

Ruby: -> { puts "run" }.call
来源：http://dali.svipenyu.cn/Article/details/gtnxgmfdsy.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.redwolf501.top/Article/details/gtlhxhictm.html

[C13] 类型声明 / 类型注解
来源：http://dali.iojbl.cn/Article/details/gtazhhwiyt.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hnxiangtu.top/Article/details/gtcdfmukqm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xziqi.cn/Article/details/gtzmsnwcyt.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.tanke756.top/Article/details/gtmjoajllo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gtqwtatatg.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjpjlimce.html

Go:   func add(a, b int) int
来源：http://dali.shuidangran.top/Article/details/gtuklamvya.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sxryk.cn/Article/details/gtvykxdidq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jianghu66.top/Article/details/gtvinfcxtm.html

[C14] 泛型函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfibvjmqr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xuetiantiany.cn/Article/details/gtexumhtiq.html

PHP:  // 无泛型
来源：http://dali.vqdsnc.cn/Article/details/gtimmwpqwp.html

JS:   // 无泛型
来源：http://dali.shanyushiyangtech.top/Article/details/gtpgotjium.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.mhx1999.top/Article/details/gtbnodyvbu.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hammf.cn/Article/details/gtqgivdjfh.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.aibaodan.cn/Article/details/gtsrfpdoyp.html

Ruby: # 无泛型
来源：http://dali.zhoulong.xyz/Article/details/gtxgnvpvml.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenlongwang.top/Article/details/gteayeomyf.html

[C15] 解构 / 展开参数
来源：http://dali.kuanghao11.cn/Article/details/gthppzrztu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaynpjuvn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gotoacloud.top/Article/details/gtilqtznit.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hfpthk.cn/Article/details/gtyphsfhie.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.tanke756.top/Article/details/gtjxmkfhwv.html

Java: // 无解构
来源：http://dali.cashguo.top/Article/details/gthxulfjie.html

Go:   // 无解构
来源：http://dali.sufxvd.cn/Article/details/gtpnmlnllj.html

Ruby: a, b = pair
来源：http://dali.mhx1999.top/Article/details/gtdlvapuhh.html

C#:   var (a, b) = pair;
来源：http://dali.wangdashe.top/Article/details/gtbkhxdorr.html

[C16] 函数 / 方法重载
来源：http://dali.hywenlv.cn/Article/details/gtbydccdig.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.guowangkeji.top/Article/details/gtkqsnzmpg.html

PHP:  // 无重载
来源：http://dali.sufxvd.cn/Article/details/gtannchiqa.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinyuanbaomall.cn/Article/details/gtunmnbokv.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zycfv.cn/Article/details/gttxzdhlwh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xuanzx.com/Article/details/gtpcyjycuj.html

Go:   // 无重载：用不同函数名
来源：http://dali.guowangkeji.top/Article/details/gtikabgfva.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hysaishi.cn/Article/details/gtqvntrdxs.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.snrcjt.cn/Article/details/gtnjhwnwgi.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtxfigrzdm.html

D. 数组 / 列表 / 集合
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqefcadrj.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtxekngshl.html

[D01] 创建数组 / 列表
来源：http://dali.smart0.xyz/Article/details/gtjsgamhwv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpysrfthx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ivvv.top/Article/details/gtjbfuzypq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.chenlongwang.top/Article/details/gtdsnfxpng.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.sxryk.cn/Article/details/gtcvpligeh.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhixingplan.top/Article/details/gtinonwycd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zdqjudy.top/Article/details/gtnylapxtz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zdqjudy.top/Article/details/gtvdsxayyf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.tianlin.xyz/Article/details/gtxbovprdd.html

[D02] 追加元素到末尾
来源：http://dali.chenjidiqi.icu/Article/details/gtktfmckjb.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zdqjudy.top/Article/details/gtmmapejno.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.wangshuangyany.cn/Article/details/gtonqbaijb.html

JS:   arr.push(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtsjoqcoej.html

TS:   arr.push(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgeejyfvu.html

Java: list.add(4);
来源：http://dali.hammf.cn/Article/details/gtzhwanxsv.html

Go:   arr = append(arr, 4)
来源：http://dali.gaohongyu789.top/Article/details/gtmyqjfhny.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.dashuyun.cn/Article/details/gtafxewsrk.html

C#:   list.Add(4);
来源：http://dali.nanxinkj.top/Article/details/gtavwlmpix.html

[D03] 在指定位置插入元素
来源：http://dali.chenzaomai.com/Article/details/gttwfjgluk.html

Py:   arr.insert(0, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtvncdgyar.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yj20258888.top/Article/details/gtlswbwxdo.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.pycfn.com/Article/details/gtpiwydrkn.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.quarkkingdee.top/Article/details/gtwfjmkuer.html

Java: list.add(0, 0);
来源：http://dali.cdnleiting.top/Article/details/gttlfjrvub.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shzxlz.cn/Article/details/gtviyagank.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.aibaodan.cn/Article/details/gtirlkmkmr.html

C#:   list.Insert(0, 0);
来源：http://dali.daxiang520.top/Article/details/gtzefqloxn.html

[D04] 删除元素
来源：http://dali.smart0.xyz/Article/details/gtohuhscbt.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.quarkkingdee.top/Article/details/gtlpqzfiss.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtsixoneyw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hammf.cn/Article/details/gthixxajbj.html

TS:   arr.splice(0, 1);
来源：http://dali.zhixingplan.top/Article/details/gtnyroemmp.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yuanzhike.top/Article/details/gthhlmmjjm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.snrcjt.cn/Article/details/gtdkwlbgtt.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.chenjidiqi.icu/Article/details/gtbponvqpv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhixingplan.top/Article/details/gtllkbemmp.html

[D05] 访问与修改元素
来源：http://dali.xuetiantiany.cn/Article/details/gtrwhyhvwx.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.0kj1m.cn/Article/details/gtprpagbtr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hammf.cn/Article/details/gtihwyrmrh.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.nanxuanxn.top/Article/details/gtpkgdbzxi.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.haohaochexian.top/Article/details/gthymnjrna.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xylfe.cn/Article/details/gtfhpokpnb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.dashuyun.cn/Article/details/gtgzsdeofb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xuetiantiany.cn/Article/details/gtsoefblfj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.tian-w.cn/Article/details/gtodiymxkl.html

[D06] 数组长度
来源：http://dali.daria6918.cn/Article/details/gtfddbkbpr.html

Py:   len(arr)
来源：http://dali.wangdashe.top/Article/details/gtwlvdpueo.html

PHP:  count($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtfrohuvop.html

JS:   arr.length
来源：http://dali.wangdashe.top/Article/details/gtrjwkqojb.html

TS:   arr.length
来源：http://dali.aibaodan.cn/Article/details/gthiawczng.html

Java: list.size();
来源：http://dali.sysykeji.top/Article/details/gtdxjkoxfa.html

Go:   len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtvirlhzac.html

Ruby: arr.length; arr.size
来源：http://dali.wangshuangyany.cn/Article/details/gtnvbwkiil.html

C#:   list.Count;
来源：http://dali.redwolf501.top/Article/details/gtpjjemsnf.html

[D07] 切片 / 取子数组
来源：http://dali.ppjwa.cn/Article/details/gtkpkovgrg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ybcxt.top/Article/details/gtgkjyctra.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zdqjudy.top/Article/details/gtrqxkutya.html

JS:   arr.slice(1, 4);
来源：http://dali.birdmap.top/Article/details/gtsnfnropt.html

TS:   arr.slice(1, 4);
来源：http://dali.guannengcc.top/Article/details/gtqkrtvimh.html

Java: list.subList(1, 4);
来源：http://dali.aizwys.cn/Article/details/gtpfhjecoi.html

Go:   arr[1:4]
来源：http://dali.meibo888.top/Article/details/gtvsxgyomk.html

Ruby: arr[1, 3]
来源：http://dali.yongpay.top/Article/details/gtmlityumi.html

C#:   list.GetRange(1, 3);
来源：http://dali.9152youxi.cn/Article/details/gtohnfsbma.html

[D08] 合并两个数组
来源：http://dali.ydzc1.top/Article/details/gtcgbpleni.html

Py:   a + b;  a.extend(b)
来源：http://dali.havefunace.top/Article/details/gtqedbvpob.html

PHP:  array_merge($a, $b);
来源：http://dali.yuanzhike.top/Article/details/gtzwcyljut.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xuanzx.com/Article/details/gtjipxvpzl.html

TS:   [...a, ...b];
来源：http://dali.sufxvd.cn/Article/details/gtadjhwmdt.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shzxlz.cn/Article/details/gtuuybgnve.html

Go:   append(a, b...)
来源：http://dali.yuanzhike.top/Article/details/gtuobkqkef.html

Ruby: a + b;  a.concat(b)
来源：http://dali.aizwys.cn/Article/details/gtniprcxwb.html

C#:   a.Concat(b).ToList()
来源：http://dali.zycfv.cn/Article/details/gtrsmiawbi.html

[D09] 排序（升序）
来源：http://dali.nanxinkj.top/Article/details/gtkfeudhrc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258.top/Article/details/gtycqeuaeq.html

PHP:  sort($arr);
来源：http://dali.yongpay.top/Article/details/gthxxbrodl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.smart0.xyz/Article/details/gtnlomjmhe.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthygfsoce.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hnqzz.top/Article/details/gtxjcaslpp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.tianlin.xyz/Article/details/gtjavtmfsz.html

Ruby: arr.sort
来源：http://dali.nanxinkj.top/Article/details/gtqajzvimc.html

C#:   list.Sort();
来源：http://dali.jlsjyb.cn/Article/details/gtekcgfpri.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.pengpengdd.cyou/Article/details/gtknuvbopl.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yangfankeji.com/Article/details/gtpnostumv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nwbrower.top/Article/details/gtlkhabnbt.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.smart0.xyz/Article/details/gtiykqvdgw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.kuanghao11.cn/Article/details/gtqaiacmfb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.daxiang520.top/Article/details/gthpiguonp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhiwuduotai.top/Article/details/gtwvrpnoll.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.fengsongda.top/Article/details/gtgncjeyyc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jiagoushi.top/Article/details/gtvofupdco.html

[D11] 反转数组
来源：http://dali.shzxlz.cn/Article/details/gtliximllo.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sufxvd.cn/Article/details/gtpnufohgw.html

PHP:  array_reverse($arr);
来源：http://dali.guannengcc.top/Article/details/gtfmwxvtfs.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gogol.net.cn/Article/details/gtvquenzjh.html

TS:   [...arr].reverse();
来源：http://dali.sweek.top/Article/details/gtjacduszc.html

Java: Collections.reverse(list);
来源：http://dali.bjfxy.top/Article/details/gtxedufopi.html

Go:   slices.Reverse(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbjkrjgvm.html

Ruby: arr.reverse
来源：http://dali.quarkkingdee.top/Article/details/gtsqjcanqi.html

C#:   list.Reverse();
来源：http://dali.ydzc1.top/Article/details/gtwnliycrh.html

[D12] 查找元素下标
来源：http://dali.svipenyu.cn/Article/details/gtfxnaypqn.html

Py:   arr.index(x);  x in arr
来源：http://dali.yj20258.top/Article/details/gtemeixijl.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.aizwys.cn/Article/details/gtzkyabhsl.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.quarkkingdee.top/Article/details/gtwdcmcgsz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.316326.xyz/Article/details/gtnotnwjru.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.nanxuanxn.top/Article/details/gtdlpekkqq.html

Go:   slices.Index(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtsiuxgafp.html

Ruby: arr.index(x)
来源：http://dali.yvedp.cn/Article/details/gtcztsnohn.html

C#:   list.IndexOf(x);
来源：http://dali.iojbl.cn/Article/details/gterqzerti.html

[D13] 过滤（保留满足条件的）
来源：http://dali.andypj.xyz/Article/details/gtfykhfadx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cheryme.top/Article/details/gtqlzhhsdt.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinqigufen.top/Article/details/gtwlqpyqxt.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yangfankeji.com/Article/details/gtoqnkrfny.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvrlfltpu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zycfv.cn/Article/details/gtsdmwpssw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhoulong.xyz/Article/details/gtmvmtrijk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.guowangkeji.top/Article/details/gtmfqncine.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.aibaodan.cn/Article/details/gtwevvfqpf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gotoacloud.top/Article/details/gtkkfzciqf.html


<!-- 参考信息 -->