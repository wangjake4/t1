代发 wailian999

[B13] 判断是否为数字
来源：http://dali.ivvv.top/Article/details/gtbugpmher.html

Py:   isinstance(x, (int, float))
来源：http://dali.chenzaomai.com/Article/details/gttpjifjxy.html

PHP:  is_numeric($x)
来源：http://dali.sufxvd.cn/Article/details/gtxewypiin.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtxqvxsoll.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ybcxt.top/Article/details/gtewmnfmcd.html

Java: x instanceof Number
来源：http://dali.jyoumei.cn/Article/details/gtdgyblows.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpmowfvox.html

Ruby: x.is_a?(Numeric)
来源：http://dali.bjfxy.top/Article/details/gtcivxzaqv.html

C#:   x is int or double or decimal
来源：http://dali.ivvv.top/Article/details/gtuwhdgjhy.html

[B14] 判断值是否在集合内
来源：http://dali.andypj.xyz/Article/details/gtetfpqocd.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.sweek.top/Article/details/gtjlewpmeh.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhiwuduotai.top/Article/details/gthdcjfjvq.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jiagoushi.top/Article/details/gtonsfhipd.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtzngwnjvl.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yj20258888.top/Article/details/gtozfgaaer.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.dianchejie.cn/Article/details/gtmqruzbjj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.nanxinkj.top/Article/details/gtqmkejgnv.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.aizwys.cn/Article/details/gtoxuwmxbb.html

[B15] 布尔运算与取反
来源：http://dali.guannengcc.top/Article/details/gtxenwxdwx.html

Py:   a and b or not c
来源：http://dali.gogol.net.cn/Article/details/gtzngfhsap.html

PHP:  $a && $b || !$c
来源：http://dali.tian-w.cn/Article/details/gtuymouwsy.html

JS:   a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gthdpppsho.html

TS:   a && b || !c
来源：http://dali.yj20258.top/Article/details/gtlkawshbm.html

Java: a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gtldctmdvy.html

Go:   a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gtjonbadyv.html

Ruby: a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzaxwizkq.html

C#:   a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gtaxqqkyyq.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hnqzz.top/Article/details/gtsqfvnfpt.html

Py:   if not data: return
来源：http://dali.ivvv.top/Article/details/gtdvsyyype.html

PHP:  if (!$data) { return; }
来源：http://dali.jyoumei.cn/Article/details/gtzkmfjdlc.html

JS:   if (!data) return;
来源：http://dali.havefunace.top/Article/details/gtghzqhkcw.html

TS:   if (!data) return;
来源：http://dali.hysaishi.cn/Article/details/gtbqgryxyo.html

Java: if (data == null) return;
来源：http://dali.havefunace.top/Article/details/gtsibfernp.html

Go:   if data == nil { return }
来源：http://dali.shzxlz.cn/Article/details/gtauvjmits.html

Ruby: return if data.nil?
来源：http://dali.ybcxt.top/Article/details/gtttvabjps.html

C#:   if (data == null) return;
来源：http://dali.9152youxi.cn/Article/details/gtpyubssst.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtuhwoyuua.html

C. 函数与作用域
来源：http://dali.zdqjudy.top/Article/details/gtxfcixaoz.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtrzzxxqcz.html

[C01] 定义函数
来源：http://dali.hnxiangtu.top/Article/details/gtufghtnhw.html

Py:   def add(a, b): return a + b
来源：http://dali.ppjwa.cn/Article/details/gtoewuvjgq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tianlin.xyz/Article/details/gtdhjhguaf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gtwbpmnobt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gtwccrlunt.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.birdmap.top/Article/details/gtnosnlruz.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.vqdsnc.cn/Article/details/gtanvdxnnp.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shzxlz.cn/Article/details/gtyyemqmsg.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtkfdflrky.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gtlwoxlmyo.html

Py:   def greet(name="World"): return name
来源：http://dali.dianchejie.cn/Article/details/gtoclqfvda.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhoulong.xyz/Article/details/gtqaymwbfm.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtluaxfhrf.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yangfankeji.com/Article/details/gtvvyghksg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.gaohongyu789.top/Article/details/gtjtguxzmk.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jinqigfzy.top/Article/details/gthadbptad.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhengqikj.top/Article/details/gtslgibaqc.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cqqwz.cn/Article/details/gtjsdipqol.html

[C03] 可变参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvgewpwoy.html

Py:   def total(*args): return sum(args)
来源：http://dali.shzxlz.cn/Article/details/gtftblloiw.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.aibaodan.cn/Article/details/gttsghbdob.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.kuanghao11.cn/Article/details/gtrofdqqjo.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cheryme.top/Article/details/gtwsqudkpw.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.mhx1999.top/Article/details/gtnjfgzmhr.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jqgfzy.top/Article/details/gtrkmxzqoj.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.bjfxy.top/Article/details/gtmfiiqiku.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shzxlz.cn/Article/details/gtyymglajq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jqgufenzy.top/Article/details/gtbvzpqkvk.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttyyjjtcx.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.dashuyun.cn/Article/details/gtjdbtdkrw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ehwqpu.com/Article/details/gtqyedotyf.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.chenlongwang.top/Article/details/gtceeechgs.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.aizwys.cn/Article/details/gtnotmuwhu.html

Go:   // 无：用配置结构体参数
来源：http://dali.9152youxi.cn/Article/details/gtvhdutlyv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.sufxvd.cn/Article/details/gtrgnytfoi.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtuorypuei.html

[C05] 返回多个值
来源：http://dali.ivvv.top/Article/details/gtxwitsnce.html

Py:   return a, b
来源：http://dali.guowangkeji.top/Article/details/gtxpqkkcwt.html

PHP:  return [$a, $b];
来源：http://dali.zdqjudy.top/Article/details/gtotqphqpi.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hnqzz.top/Article/details/gtyawkrmov.html

TS:   return { a, b };
来源：http://dali.zhixingplan.top/Article/details/gtjtgoxwzd.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jinghuilouyu.cn/Article/details/gtxvahuhmx.html

Go:   return a, b
来源：http://dali.yvedp.cn/Article/details/gtygzhdtws.html

Ruby: return a, b
来源：http://dali.meibo888.top/Article/details/gtimzzhigo.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jlsjyb.cn/Article/details/gtrysvfgeo.html

[C06] 匿名函数 / lambda
来源：http://dali.snrcjt.cn/Article/details/gtdtcxuchq.html

Py:   square = lambda x: x * x
来源：http://dali.yj20258888.top/Article/details/gtidhoylnl.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.iojbl.cn/Article/details/gtiwrlqdez.html

JS:   const square = x => x * x;
来源：http://dali.xziqi.cn/Article/details/gttrocpkdo.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.fengsongda.top/Article/details/gthxtmcdbq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.chenjidiqi.icu/Article/details/gtbamqnvqm.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.tanke756.top/Article/details/gtqndmhycj.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xylfe.cn/Article/details/gttscrvmtn.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yanxiufei.cn/Article/details/gtmfcpoiaj.html

[C07] 把函数作为参数传入
来源：http://dali.yj20258888.top/Article/details/gtiemipuog.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.havefunace.top/Article/details/gtbwftusti.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.c1oappe.top/Article/details/gtqebaujyd.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.sysykeji.top/Article/details/gtzikphgfd.html

TS:   arr.map(String)
来源：http://dali.chenlongwang.top/Article/details/gtuqyxjpgb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.guowangkeji.top/Article/details/gtjojmqniq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shzxlz.cn/Article/details/gticalotst.html

Ruby: arr.map(&:upcase)
来源：http://dali.daria6918.cn/Article/details/gtdkqkfwfp.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yueranfly.top/Article/details/gtfhmxciel.html

[C08] 闭包
来源：http://dali.tianlin.xyz/Article/details/gtcjgzoiim.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ywan-chungtsiang.top/Article/details/gtorzabppl.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.tanke756.top/Article/details/gttlofuhal.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.chenjidiqi.icu/Article/details/gtyeptmdfu.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yvedp.cn/Article/details/gtxwfqpdxt.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.snrcjt.cn/Article/details/gtlqyulbkq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.nanxinkj.top/Article/details/gttmnngzbe.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jiagoushi.top/Article/details/gtbzmybmga.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.aibaodan.cn/Article/details/gtvhjhfmrx.html

[C09] 递归
来源：http://dali.jqgfzy.top/Article/details/gttinrspsy.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ydzc1.top/Article/details/gtpczgfclg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jqgfzy.top/Article/details/gtuhhajjio.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtikswjfvw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ppjwa.cn/Article/details/gtompalzbs.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.aizwys.cn/Article/details/gtyibghrgk.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.andypj.xyz/Article/details/gtszpszruy.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jinqigufen.top/Article/details/gtjvssowie.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yuanzhike.top/Article/details/gtujzgjjsx.html

[C10] 变量作用域
来源：http://dali.yj20258.top/Article/details/gtjjsmaobd.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gogol.net.cn/Article/details/gtqxznkqld.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xuetiantiany.cn/Article/details/gtimjashbl.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.tianlin.xyz/Article/details/gtahtwzxul.html

TS:   同 JS
来源：http://dali.zhaomingkeji.xyz/Article/details/gthrzhhwho.html

Java: 方法内为块级作用域
来源：http://dali.hysaishi.cn/Article/details/gtmyxcicxn.html

Go:   花括号块级作用域
来源：http://dali.316326.xyz/Article/details/gtihruhkzl.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yonumen.top/Article/details/gtcqaoxmcf.html

C#:   块级作用域
来源：http://dali.hfpthk.cn/Article/details/gtvnmmqkyb.html

[C11] 模块导入与导出
来源：http://dali.316326.xyz/Article/details/gtunxtzkfm.html

Py:   from module import func
来源：http://dali.sxryk.cn/Article/details/gtqjfuzasx.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhengqikj.top/Article/details/gthlkgkjvd.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.nwbrower.top/Article/details/gtxobrcbys.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.havefunace.top/Article/details/gtjvocairf.html

Java: import java.util.List;
来源：http://dali.gogol.net.cn/Article/details/gthyctjodd.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zdqjudy.top/Article/details/gtquqmefdd.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.feifeiyinyue.top/Article/details/gtvuoatebq.html

C#:   using System.Text;
来源：http://dali.jqgufenzy.top/Article/details/gtriqrmxqy.html

[C12] 立即执行函数 IIFE
来源：http://dali.fzhhl.top/Article/details/gtdofwnlan.html

Py:   (lambda: print("run"))()
来源：http://dali.wangdashe.top/Article/details/gtebbdmuuf.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ehwqpu.com/Article/details/gtvtbazjka.html

JS:   (() => { console.log("run"); })();
来源：http://dali.guannengcc.top/Article/details/gtdhrkbqii.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shangyingyoupin.top/Article/details/gtlqhvvtby.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shanyushiyangtech.top/Article/details/gtjjuscxwv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yanxiufei.cn/Article/details/gtpbfamooe.html

Ruby: -> { puts "run" }.call
来源：http://dali.hongshengwenyu.top/Article/details/gtbxcxsuev.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhixingplan.top/Article/details/gtllthtxzb.html

[C13] 类型声明 / 类型注解
来源：http://dali.tian-w.cn/Article/details/gtrtxaaruw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jinyuanbaomall.cn/Article/details/gthostflvt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.snrcjt.cn/Article/details/gtfskizgze.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gtnssejwiz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gtjmytrqbc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtwivenzig.html

Go:   func add(a, b int) int
来源：http://dali.fengsongda.top/Article/details/gtjgarfpfn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.pengpengdd.cyou/Article/details/gtpigsoceu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.guannengcc.top/Article/details/gtpmqfxbrf.html

[C14] 泛型函数
来源：http://dali.jqgufenzy.top/Article/details/gtlwmdgvmz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shangyingyoupin.top/Article/details/gtxkrhkzoe.html

PHP:  // 无泛型
来源：http://dali.c1oappe.top/Article/details/gtsipfngau.html

JS:   // 无泛型
来源：http://dali.hnxiangtu.top/Article/details/gtdnqbycgs.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.vqdsnc.cn/Article/details/gtxgpfsfdq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xziqi.cn/Article/details/gtbizeybjx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gotoacloud.top/Article/details/gtkuowvres.html

Ruby: # 无泛型
来源：http://dali.fengsongda.top/Article/details/gtgmjgpnqe.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.nanxinkj.top/Article/details/gtnrhslosu.html

[C15] 解构 / 展开参数
来源：http://dali.aibaodan.cn/Article/details/gtebgyiqoq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.c1oappe.top/Article/details/gtwyelebdk.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cucudq.cn/Article/details/gtdvueldpw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cucudq.cn/Article/details/gtlvofycsa.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shuidangran.top/Article/details/gtzsebgolr.html

Java: // 无解构
来源：http://dali.gzhubu.top/Article/details/gtlfbjldwy.html

Go:   // 无解构
来源：http://dali.cqqwz.cn/Article/details/gtxeklhcht.html

Ruby: a, b = pair
来源：http://dali.hywenlv.cn/Article/details/gtpxxlhayo.html

C#:   var (a, b) = pair;
来源：http://dali.xziqi.cn/Article/details/gtgivmnent.html

[C16] 函数 / 方法重载
来源：http://dali.xuanzx.com/Article/details/gtwupyenig.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jinqigufen.top/Article/details/gtrkzeatxv.html

PHP:  // 无重载
来源：http://dali.dashuyun.cn/Article/details/gtztqrrtkd.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.vqdsnc.cn/Article/details/gttdugfcgl.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.snrcjt.cn/Article/details/gtgkeceabo.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shuidangran.top/Article/details/gtyiffbhil.html

Go:   // 无重载：用不同函数名
来源：http://dali.gzhubu.top/Article/details/gtbuzfvfuv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.havefunace.top/Article/details/gtnjipburb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.tianlin.xyz/Article/details/gtjmclnhdl.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtvazsoxaq.html

D. 数组 / 列表 / 集合
来源：http://dali.yj20258888.top/Article/details/gtwwmdthvh.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtsuprvedo.html

[D01] 创建数组 / 列表
来源：http://dali.hammf.cn/Article/details/gtjwmpdcih.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhoulong.xyz/Article/details/gtqzvqilyu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.fengsongda.top/Article/details/gttiqygumo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhixingplan.top/Article/details/gtneyppegw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.0kj1m.cn/Article/details/gtmgmgbhew.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.c1oappe.top/Article/details/gtspexkric.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jyoumei.cn/Article/details/gttqsqpbih.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ppjwa.cn/Article/details/gtslxzijmh.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.quarkkingdee.top/Article/details/gtfgqfdgju.html

[D02] 追加元素到末尾
来源：http://dali.jlsjyb.cn/Article/details/gtdaexzuxz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ivvv.top/Article/details/gtzzflmbdu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yangfankeji.com/Article/details/gtlqtbgvgb.html

JS:   arr.push(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbzgihgkc.html

TS:   arr.push(4);
来源：http://dali.birdmap.top/Article/details/gtdgydcnzf.html

Java: list.add(4);
来源：http://dali.gzhubu.top/Article/details/gtvwmlunwr.html

Go:   arr = append(arr, 4)
来源：http://dali.andypj.xyz/Article/details/gtuqatjanu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnpzkgypv.html

C#:   list.Add(4);
来源：http://dali.nanxinkj.top/Article/details/gtnktfuaki.html

[D03] 在指定位置插入元素
来源：http://dali.bjfxy.top/Article/details/gtzluxbadr.html

Py:   arr.insert(0, 0)
来源：http://dali.tianlin.xyz/Article/details/gtyqrgklem.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cdnleiting.top/Article/details/gtnmvvkxdm.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuysumxta.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shzxlz.cn/Article/details/gthyxgaizj.html

Java: list.add(0, 0);
来源：http://dali.birdmap.top/Article/details/gtmmhdtlph.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yuxming.cn/Article/details/gtkewmtofm.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.316326.xyz/Article/details/gthpobahbo.html

C#:   list.Insert(0, 0);
来源：http://dali.jinqigufen.top/Article/details/gtzqzpnjai.html

[D04] 删除元素
来源：http://dali.yongpay.top/Article/details/gthmoxfuiu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.quarkkingdee.top/Article/details/gtdjnocdsl.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jqgfzy.top/Article/details/gtjmhhbuho.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sxryk.cn/Article/details/gtpsavpddu.html

TS:   arr.splice(0, 1);
来源：http://dali.jqgfzy.top/Article/details/gtkoycerdj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sufxvd.cn/Article/details/gtaxnnwvaj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xylfe.cn/Article/details/gtugedroru.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yueranfly.top/Article/details/gtwctkkxjp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jyoumei.cn/Article/details/gtznzrhbtn.html

[D05] 访问与修改元素
来源：http://dali.hysaishi.cn/Article/details/gthbhcnnfw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jlsjyb.cn/Article/details/gtaoahyypz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xuanzx.com/Article/details/gtrofmkfnt.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hysaishi.cn/Article/details/gtvwqynklg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.bjfxy.top/Article/details/gtfjaqkbgz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cashguo.top/Article/details/gtdiwsvpsa.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gzhubu.top/Article/details/gtdbhujyfv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinyuanbaomall.cn/Article/details/gtodlnybuh.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cashguo.top/Article/details/gtfihonsqw.html

[D06] 数组长度
来源：http://dali.cdnleiting.top/Article/details/gtypcpapkx.html

Py:   len(arr)
来源：http://dali.hywenlv.cn/Article/details/gthzqrwzik.html

PHP:  count($arr);
来源：http://dali.zdqjudy.top/Article/details/gtiuhxgweh.html

JS:   arr.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjbnhxhfn.html

TS:   arr.length
来源：http://dali.jlsjyb.cn/Article/details/gtfexhofpt.html

Java: list.size();
来源：http://dali.wangshuangyany.cn/Article/details/gtzlxxywbd.html

Go:   len(arr)
来源：http://dali.zhixingplan.top/Article/details/gtojrngpbu.html

Ruby: arr.length; arr.size
来源：http://dali.nanxinkj.top/Article/details/gtlnnxnoqn.html

C#:   list.Count;
来源：http://dali.jyoumei.cn/Article/details/gtnvkddxxn.html

[D07] 切片 / 取子数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpwltfrvx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xinyue.icu/Article/details/gtmoisaqvv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yj20258888.top/Article/details/gtctpvzuet.html

JS:   arr.slice(1, 4);
来源：http://dali.aizwys.cn/Article/details/gtverxvulz.html

TS:   arr.slice(1, 4);
来源：http://dali.yj202588.top/Article/details/gtylkhenjd.html

Java: list.subList(1, 4);
来源：http://dali.hongshengwenyu.top/Article/details/gtymosetsm.html

Go:   arr[1:4]
来源：http://dali.nwbrower.top/Article/details/gtqyzewpua.html

Ruby: arr[1, 3]
来源：http://dali.hysaishi.cn/Article/details/gtxprpzzub.html

C#:   list.GetRange(1, 3);
来源：http://dali.0kj1m.cn/Article/details/gtizzfwbrn.html

[D08] 合并两个数组
来源：http://dali.jianghu66.top/Article/details/gtoysjuhgl.html

Py:   a + b;  a.extend(b)
来源：http://dali.0kj1m.cn/Article/details/gthsnrvuxz.html

PHP:  array_merge($a, $b);
来源：http://dali.pycfn.com/Article/details/gtkazjxbvm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cashguo.top/Article/details/gtzmyayoto.html

TS:   [...a, ...b];
来源：http://dali.hnxiangtu.top/Article/details/gtnedfhwot.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.mhx1999.top/Article/details/gtveklycrn.html

Go:   append(a, b...)
来源：http://dali.zhixingplan.top/Article/details/gthzqzoqnl.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hfpthk.cn/Article/details/gtzdrclauw.html

C#:   a.Concat(b).ToList()
来源：http://dali.yangfankeji.com/Article/details/gtrlyrrxtm.html

[D09] 排序（升序）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtguzvfksp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dashuyun.cn/Article/details/gtybzlkiel.html

PHP:  sort($arr);
来源：http://dali.andypj.xyz/Article/details/gtfifqibpq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.redwolf501.top/Article/details/gtojnueejx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hnxiangtu.top/Article/details/gtbhngrsai.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.andypj.xyz/Article/details/gtlagazpvi.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yueranfly.top/Article/details/gtfjgsdbid.html

Ruby: arr.sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsfeumson.html

C#:   list.Sort();
来源：http://dali.jlsjyb.cn/Article/details/gtrsxjlpqq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yanxiufei.cn/Article/details/gteewnoptw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ydzc1.top/Article/details/gtflfjjhkh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jianghu66.top/Article/details/gtmjintcec.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbwqdmzsc.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cashguo.top/Article/details/gtknmmqisn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.aibaodan.cn/Article/details/gtkwjwswyy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinghuilouyu.cn/Article/details/gtbojgdnvz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinqigfzy.top/Article/details/gtjyzevlkd.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.pengpengdd.cyou/Article/details/gtznpyairp.html

[D11] 反转数组
来源：http://dali.sxryk.cn/Article/details/gtyngeayiy.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.tian-w.cn/Article/details/gtmcrgrbad.html

PHP:  array_reverse($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdnfcgdhq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrfwfnqsl.html

TS:   [...arr].reverse();
来源：http://dali.dianchejie.cn/Article/details/gthrtniibl.html

Java: Collections.reverse(list);
来源：http://dali.shzxlz.cn/Article/details/gtowkadbzm.html

Go:   slices.Reverse(arr)
来源：http://dali.ppjwa.cn/Article/details/gtbqnpqhyy.html

Ruby: arr.reverse
来源：http://dali.jinqigufen.top/Article/details/gtnkyufvcx.html

C#:   list.Reverse();
来源：http://dali.chenjidiqi.icu/Article/details/gtrtfsofqs.html

[D12] 查找元素下标
来源：http://dali.ivvv.top/Article/details/gtelbetalq.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfgisbdzy.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xinyue.icu/Article/details/gtlbqevike.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.daria6918.cn/Article/details/gtsfxpboxv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.havefunace.top/Article/details/gtcgwxxyjy.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jinqigfzy.top/Article/details/gtjmeftjoc.html

Go:   slices.Index(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtmbzgpnax.html

Ruby: arr.index(x)
来源：http://dali.aibaodan.cn/Article/details/gtmcidbkds.html

C#:   list.IndexOf(x);
来源：http://dali.dashuyun.cn/Article/details/gtawwvzqmq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.0kj1m.cn/Article/details/gtyhisxepb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sweek.top/Article/details/gtubvwrihj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.tianlin.xyz/Article/details/gttuotborr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhongyouzk.top/Article/details/gtrxgplgje.html

TS:   arr.filter(x => x > 3)
来源：http://dali.aizwys.cn/Article/details/gtpjczmjbr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.nwbrower.top/Article/details/gthdrecaks.html


<!-- 参考信息 -->