代发 wailian999

PHP:  range(0, 10, 2);
来源：http://dali.sufxvd.cn/Article/details/gtyecklnzh.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jiagoushi.top/Article/details/gtcqbgikig.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xinyue.icu/Article/details/gtmscyhnhb.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hnqzz.top/Article/details/gtsmuxckod.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.birdmap.top/Article/details/gtsduawkuc.html

Ruby: (0...10).step(2).to_a
来源：http://dali.fengsongda.top/Article/details/gtnymfjndz.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hywenlv.cn/Article/details/gtefwmklzh.html

[B12] 跳出多层循环
来源：http://dali.sysykeji.top/Article/details/gtijixbxox.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jiagoushi.top/Article/details/gthummixfl.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yueranfly.top/Article/details/gtjapqhlal.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gogol.net.cn/Article/details/gtccspznvw.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.9152youxi.cn/Article/details/gthmmcejju.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.0kj1m.cn/Article/details/gtkspiqtyi.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpouakena.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.smart0.xyz/Article/details/gtexntltwb.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.gotoacloud.top/Article/details/gtjigrpfou.html

[B13] 判断是否为数字
来源：http://dali.316326.xyz/Article/details/gtzyjauyjt.html

Py:   isinstance(x, (int, float))
来源：http://dali.jqgfzy.top/Article/details/gtdlsytkwy.html

PHP:  is_numeric($x)
来源：http://dali.yuanzhike.top/Article/details/gtueqsjmtd.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jlsjyb.cn/Article/details/gtxxzmmubg.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jyoumei.cn/Article/details/gtkziczgrb.html

Java: x instanceof Number
来源：http://dali.shuidangran.top/Article/details/gtzxrbqhkx.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cqqwz.cn/Article/details/gtqvfdluag.html

Ruby: x.is_a?(Numeric)
来源：http://dali.gogol.net.cn/Article/details/gtfhpfqiyy.html

C#:   x is int or double or decimal
来源：http://dali.sufxvd.cn/Article/details/gteobpwywx.html

[B14] 判断值是否在集合内
来源：http://dali.hywenlv.cn/Article/details/gtbpildmox.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.mhx1999.top/Article/details/gtcrwhkeqf.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zycfv.cn/Article/details/gtkrvimfzm.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jinqigufen.top/Article/details/gtezrehskx.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hysaishi.cn/Article/details/gtqbvicysu.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zycfv.cn/Article/details/gtrfgppwec.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtgalzdwrz.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.9152youxi.cn/Article/details/gtovkixiko.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.tianlin.xyz/Article/details/gtfjfmbbct.html

[B15] 布尔运算与取反
来源：http://dali.xylfe.cn/Article/details/gtbygawvlu.html

Py:   a and b or not c
来源：http://dali.sweek.top/Article/details/gtadszplnl.html

PHP:  $a && $b || !$c
来源：http://dali.nanxuanxn.top/Article/details/gtxmlifuid.html

JS:   a && b || !c
来源：http://dali.cucudq.cn/Article/details/gtunfkqufx.html

TS:   a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gtumanhrkg.html

Java: a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gtuecjtxpc.html

Go:   a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gtiudnydme.html

Ruby: a && b || !c
来源：http://dali.mhx1999.top/Article/details/gttivvryqi.html

C#:   a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gtfksparcu.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.snrcjt.cn/Article/details/gtsqkmuusj.html

Py:   if not data: return
来源：http://dali.wangshuangyany.cn/Article/details/gtjytwfffn.html

PHP:  if (!$data) { return; }
来源：http://dali.yuanzhike.top/Article/details/gtliyfbnft.html

JS:   if (!data) return;
来源：http://dali.jiagoushi.top/Article/details/gtmgtzbyye.html

TS:   if (!data) return;
来源：http://dali.hywenlv.cn/Article/details/gtqbukqjxz.html

Java: if (data == null) return;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrelsrgde.html

Go:   if data == nil { return }
来源：http://dali.iojbl.cn/Article/details/gtiqgzrlsl.html

Ruby: return if data.nil?
来源：http://dali.nwbrower.top/Article/details/gtymvwxzet.html

C#:   if (data == null) return;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvugnrfsq.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtaojifcjc.html

C. 函数与作用域
来源：http://dali.xuetiantiany.cn/Article/details/gtctuqezte.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtohsejgsx.html

[C01] 定义函数
来源：http://dali.yvedp.cn/Article/details/gtcsayuylt.html

Py:   def add(a, b): return a + b
来源：http://dali.yueranfly.top/Article/details/gtkexncrrv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuanzx.com/Article/details/gtexkhaarw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gtewucandh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gtumiiuwhb.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtznfzcgup.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.wangshuangyany.cn/Article/details/gtpeyiyhvn.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhengqikj.top/Article/details/gtofiloicn.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gtubwqxmts.html

[C02] 默认参数
来源：http://dali.jqgufenzy.top/Article/details/gtqxpxwyxj.html

Py:   def greet(name="World"): return name
来源：http://dali.chenlongwang.top/Article/details/gtmrquteco.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.9152youxi.cn/Article/details/gtpvzaxghu.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.pycfn.com/Article/details/gtdxnoirxk.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtbsystoli.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfphqilas.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yangfankeji.com/Article/details/gtaovhihlw.html

Ruby: def greet(name = "World") = name
来源：http://dali.shangyingyoupin.top/Article/details/gtngxpuxtr.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jiagoushi.top/Article/details/gttypxpxpp.html

[C03] 可变参数
来源：http://dali.yangfankeji.com/Article/details/gtsdgyyzra.html

Py:   def total(*args): return sum(args)
来源：http://dali.xinyue.icu/Article/details/gtfojssagi.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.andypj.xyz/Article/details/gtjarelmxb.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jianghu66.top/Article/details/gtvdocqqsj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yueranfly.top/Article/details/gtjeijkdqn.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hfpthk.cn/Article/details/gtfqpcpmnt.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hysaishi.cn/Article/details/gtopobghkm.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.quarkkingdee.top/Article/details/gtlotnsxaj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.andypj.xyz/Article/details/gtuhvqejxe.html

[C04] 命名参数 / 关键字参数
来源：http://dali.svipenyu.cn/Article/details/gtldptwess.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhengqikj.top/Article/details/gtvdvvywit.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cdnleiting.top/Article/details/gtucfxwezi.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.fengsongda.top/Article/details/gtqbmeukeq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.snrcjt.cn/Article/details/gtdlbddazn.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhengqikj.top/Article/details/gtbnrxiind.html

Go:   // 无：用配置结构体参数
来源：http://dali.hnxiangtu.top/Article/details/gtwwmvekcs.html

Ruby: f(a: 1, b: 2)
来源：http://dali.meibo888.top/Article/details/gtuzlhtcih.html

C#:   f(a: 1, b: 2)
来源：http://dali.yj20258.top/Article/details/gtcfjdrjvo.html

[C05] 返回多个值
来源：http://dali.9152youxi.cn/Article/details/gtafneepnv.html

Py:   return a, b
来源：http://dali.jqgfzy.top/Article/details/gtliqgtiab.html

PHP:  return [$a, $b];
来源：http://dali.zdqjudy.top/Article/details/gtdpaazase.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhengqikj.top/Article/details/gtxtukypag.html

TS:   return { a, b };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtonjprsbo.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shzxlz.cn/Article/details/gtxyzwpict.html

Go:   return a, b
来源：http://dali.daxiang520.top/Article/details/gtbnpzkpeq.html

Ruby: return a, b
来源：http://dali.shuidangran.top/Article/details/gtffowhtyg.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.kuanghao11.cn/Article/details/gteorfquwe.html

[C06] 匿名函数 / lambda
来源：http://dali.shzxlz.cn/Article/details/gtslfvmwtu.html

Py:   square = lambda x: x * x
来源：http://dali.hnqzz.top/Article/details/gtgxtzldyq.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jlsjyb.cn/Article/details/gtbiwgiftw.html

JS:   const square = x => x * x;
来源：http://dali.zhongyouzk.top/Article/details/gtpcdxgrwb.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yj20258888.top/Article/details/gtonevpujw.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ydzc1.top/Article/details/gtxmgbrzzs.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gteostrnht.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xziqi.cn/Article/details/gtkmiywvxx.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuezauxcq.html

[C07] 把函数作为参数传入
来源：http://dali.316326.xyz/Article/details/gtjzcnsxra.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.fzhhl.top/Article/details/gtmflrccrg.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.shuidangran.top/Article/details/gtsfgfhxhy.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xuanzx.com/Article/details/gtiyakorax.html

TS:   arr.map(String)
来源：http://dali.jianghu66.top/Article/details/gtotzzeoho.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.birdmap.top/Article/details/gtemflqrcx.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.dianchejie.cn/Article/details/gtrqdqhjff.html

Ruby: arr.map(&:upcase)
来源：http://dali.nanxuanxn.top/Article/details/gtxylghbzd.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhixingplan.top/Article/details/gthyzcxqcr.html

[C08] 闭包
来源：http://dali.quarkkingdee.top/Article/details/gtwkdyaszp.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.tanke756.top/Article/details/gtigydqkdf.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.snrcjt.cn/Article/details/gtonvrgsjj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jqgufenzy.top/Article/details/gtaoapammc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhengqikj.top/Article/details/gtjrceaoae.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cashguo.top/Article/details/gtiiepusok.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hammf.cn/Article/details/gtscchqmew.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ppjwa.cn/Article/details/gthybkhbbh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xinyue.icu/Article/details/gtxzehkisj.html

[C09] 递归
来源：http://dali.aibaodan.cn/Article/details/gtrvlmogwu.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hfpthk.cn/Article/details/gtyzokckyh.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shanyushiyangtech.top/Article/details/gthduuiqgu.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gotoacloud.top/Article/details/gtagpouber.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.haohaochexian.top/Article/details/gtuifrmxxy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hywenlv.cn/Article/details/gtjetyyyzc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yj20258888.top/Article/details/gtyfrnhmqa.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.meibo888.top/Article/details/gtsgjmcpbu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hongshengwenyu.top/Article/details/gtzmgxmdeq.html

[C10] 变量作用域
来源：http://dali.jqgufenzy.top/Article/details/gterpnlnwc.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yvedp.cn/Article/details/gtfhjvdvrx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.svipenyu.cn/Article/details/gtwvoqhfeo.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xinyue.icu/Article/details/gtbzykrlsk.html

TS:   同 JS
来源：http://dali.hysaishi.cn/Article/details/gtrqkkkpwy.html

Java: 方法内为块级作用域
来源：http://dali.xinyue.icu/Article/details/gtkmhvrtzm.html

Go:   花括号块级作用域
来源：http://dali.aizwys.cn/Article/details/gtnlzsnema.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ydzc1.top/Article/details/gtnsezkxeu.html

C#:   块级作用域
来源：http://dali.mhx1999.top/Article/details/gtwzmhjplj.html

[C11] 模块导入与导出
来源：http://dali.cdnleiting.top/Article/details/gtqblafvfq.html

Py:   from module import func
来源：http://dali.feifeiyinyue.top/Article/details/gtinwceubh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.fzhhl.top/Article/details/gtkipqubjx.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.0kj1m.cn/Article/details/gttdamxdcg.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhaomingkeji.xyz/Article/details/gttecrbwdw.html

Java: import java.util.List;
来源：http://dali.cucudq.cn/Article/details/gtryvcyuwa.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shzxlz.cn/Article/details/gtkjzawpot.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.chenjidiqi.icu/Article/details/gtieikoqad.html

C#:   using System.Text;
来源：http://dali.pengpengdd.cyou/Article/details/gtquvqwdzn.html

[C12] 立即执行函数 IIFE
来源：http://dali.guannengcc.top/Article/details/gtoztjpuuw.html

Py:   (lambda: print("run"))()
来源：http://dali.jinqigufen.top/Article/details/gtqxvtpacr.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yongpay.top/Article/details/gtxscxsxpi.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xinyue.icu/Article/details/gtaztnwgue.html

TS:   (() => { console.log("run"); })();
来源：http://dali.9152youxi.cn/Article/details/gtcubvqgsr.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xylfe.cn/Article/details/gtksmacbzq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ydzc1.top/Article/details/gteeklehvv.html

Ruby: -> { puts "run" }.call
来源：http://dali.pengpengdd.cyou/Article/details/gttykehajy.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.wangshuangyany.cn/Article/details/gtwcymjmry.html

[C13] 类型声明 / 类型注解
来源：http://dali.shuidangran.top/Article/details/gtyrlzdqkn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.dianchejie.cn/Article/details/gtvtyrydjg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinqigfzy.top/Article/details/gtznspnrvj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.aibaodan.cn/Article/details/gtijvrzhup.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gtbeywbkby.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtofyqoiiv.html

Go:   func add(a, b int) int
来源：http://dali.yj202588.top/Article/details/gtxstspred.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cashguo.top/Article/details/gtxlofjqaz.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.fzhhl.top/Article/details/gtuhroczas.html

[C14] 泛型函数
来源：http://dali.aizwys.cn/Article/details/gtaqqgnzew.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.sufxvd.cn/Article/details/gtxxjwxcge.html

PHP:  // 无泛型
来源：http://dali.smart0.xyz/Article/details/gtkpymijtf.html

JS:   // 无泛型
来源：http://dali.jianghu66.top/Article/details/gttgqufwjc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.svipenyu.cn/Article/details/gtbuzxwzxz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ydzc1.top/Article/details/gtocfhhhyd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.chenlongwang.top/Article/details/gttqjdmvsi.html

Ruby: # 无泛型
来源：http://dali.sxryk.cn/Article/details/gtbemtnzgo.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jianghu66.top/Article/details/gtghvbpzbj.html

[C15] 解构 / 展开参数
来源：http://dali.havefunace.top/Article/details/gtnpikodsy.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ydzc1.top/Article/details/gtzbvmdpkr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.sweek.top/Article/details/gtvhbkfxgn.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtervzfvtr.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.nanxinkj.top/Article/details/gtoxchuzyk.html

Java: // 无解构
来源：http://dali.0kj1m.cn/Article/details/gthunyeciz.html

Go:   // 无解构
来源：http://dali.yvedp.cn/Article/details/gtdprraoyc.html

Ruby: a, b = pair
来源：http://dali.yonumen.top/Article/details/gteruknwpc.html

C#:   var (a, b) = pair;
来源：http://dali.gaohongyu789.top/Article/details/gtcitfduwz.html

[C16] 函数 / 方法重载
来源：http://dali.ivvv.top/Article/details/gtjfwrlqtn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yonumen.top/Article/details/gtboszvrin.html

PHP:  // 无重载
来源：http://dali.hywenlv.cn/Article/details/gtsdtxpfot.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shangyingyoupin.top/Article/details/gtkzwfxhul.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jyoumei.cn/Article/details/gtoeelnsnj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtboxucyga.html

Go:   // 无重载：用不同函数名
来源：http://dali.xinyue.icu/Article/details/gtbzmdksuc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xuanzx.com/Article/details/gtfztqkrdr.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yonumen.top/Article/details/gtdltkvipl.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtmqlzrttm.html

D. 数组 / 列表 / 集合
来源：http://dali.nwbrower.top/Article/details/gtcmfgzcbc.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrguenyvv.html

[D01] 创建数组 / 列表
来源：http://dali.0kj1m.cn/Article/details/gtbkyzlrxc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cdnleiting.top/Article/details/gtkkcizfix.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhoulong.xyz/Article/details/gtxifczfcb.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.guannengcc.top/Article/details/gtrlismyne.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.feifeiyinyue.top/Article/details/gtebsbtwra.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjbpdbykm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.9152youxi.cn/Article/details/gtgggboslu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shuidangran.top/Article/details/gtsgfermbx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.tianlin.xyz/Article/details/gtohntgeci.html

[D02] 追加元素到末尾
来源：http://dali.xylfe.cn/Article/details/gtxlbbarnv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jqgfzy.top/Article/details/gtytijixdz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.sufxvd.cn/Article/details/gthowoydbf.html

JS:   arr.push(4);
来源：http://dali.hnxiangtu.top/Article/details/gtewkcqobu.html

TS:   arr.push(4);
来源：http://dali.ivvv.top/Article/details/gtxrstzwzq.html

Java: list.add(4);
来源：http://dali.ydzc1.top/Article/details/gtgxxxknjq.html

Go:   arr = append(arr, 4)
来源：http://dali.cqqwz.cn/Article/details/gtoxmcegrg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jqgufenzy.top/Article/details/gtjqfztnsg.html

C#:   list.Add(4);
来源：http://dali.sweek.top/Article/details/gtzafeuapx.html

[D03] 在指定位置插入元素
来源：http://dali.ppjwa.cn/Article/details/gtbpiwpact.html

Py:   arr.insert(0, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfumffior.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.c1oappe.top/Article/details/gtxtpnzuan.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhongyouzk.top/Article/details/gtilrhwzfg.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtcufyjnca.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gtmxnghhwj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yj20258.top/Article/details/gtlnrmeoqa.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttoewapok.html

C#:   list.Insert(0, 0);
来源：http://dali.guannengcc.top/Article/details/gtnjppnpzk.html

[D04] 删除元素
来源：http://dali.pengpengdd.cyou/Article/details/gtilduzjdq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shuidangran.top/Article/details/gtiglvsqkj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtclejzghn.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jlsjyb.cn/Article/details/gtkureyrom.html

TS:   arr.splice(0, 1);
来源：http://dali.cashguo.top/Article/details/gtoqcogdvb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.dashuyun.cn/Article/details/gtnseqhyxd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.meibo888.top/Article/details/gthunrnhxe.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.svipenyu.cn/Article/details/gtebulxvxw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yj20258.top/Article/details/gthvoajvvk.html

[D05] 访问与修改元素
来源：http://dali.havefunace.top/Article/details/gtcjparppk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvjzwcykw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.pengpengdd.cyou/Article/details/gtrzwjemqa.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shzxlz.cn/Article/details/gtprquwwsr.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.aizwys.cn/Article/details/gtmjvzocub.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yj20258888.top/Article/details/gtkeoxyqnu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jianghu66.top/Article/details/gtwieulhrz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenjidiqi.icu/Article/details/gtgfrlzjhm.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.pycfn.com/Article/details/gtrugptsdy.html

[D06] 数组长度
来源：http://dali.yueranfly.top/Article/details/gtqtukzegm.html

Py:   len(arr)
来源：http://dali.jiagoushi.top/Article/details/gtwarbbjhq.html

PHP:  count($arr);
来源：http://dali.guannengcc.top/Article/details/gtytgyoxwt.html

JS:   arr.length
来源：http://dali.yanxiufei.cn/Article/details/gttlpyfbkh.html

TS:   arr.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgbnjijks.html

Java: list.size();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtosqcfcvg.html

Go:   len(arr)
来源：http://dali.mhx1999.top/Article/details/gtbscvtgxl.html

Ruby: arr.length; arr.size
来源：http://dali.xuanzx.com/Article/details/gtalmcirew.html

C#:   list.Count;
来源：http://dali.xuanzx.com/Article/details/gtwhihdmfk.html

[D07] 切片 / 取子数组
来源：http://dali.cdnleiting.top/Article/details/gtcwgybkqm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xylfe.cn/Article/details/gtwkeznnjy.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yj20258.top/Article/details/gtmtxtnrhc.html

JS:   arr.slice(1, 4);
来源：http://dali.dashuyun.cn/Article/details/gtuwdckjnf.html

TS:   arr.slice(1, 4);
来源：http://dali.cheryme.top/Article/details/gtjofpmwgr.html

Java: list.subList(1, 4);
来源：http://dali.birdmap.top/Article/details/gtgsbkiyov.html

Go:   arr[1:4]
来源：http://dali.meibo888.top/Article/details/gtwslimvqw.html

Ruby: arr[1, 3]
来源：http://dali.ppjwa.cn/Article/details/gtjiiofeuc.html

C#:   list.GetRange(1, 3);
来源：http://dali.sxryk.cn/Article/details/gtsatqktdp.html

[D08] 合并两个数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmfebnrnu.html

Py:   a + b;  a.extend(b)
来源：http://dali.redwolf501.top/Article/details/gtklkrmgkr.html

PHP:  array_merge($a, $b);
来源：http://dali.hongshengwenyu.top/Article/details/gtiagucnwz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.snrcjt.cn/Article/details/gtailuuwxg.html

TS:   [...a, ...b];
来源：http://dali.smart0.xyz/Article/details/gttiwftydd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xziqi.cn/Article/details/gtheiqstws.html

Go:   append(a, b...)
来源：http://dali.cdnleiting.top/Article/details/gtgcaddywx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shangyingyoupin.top/Article/details/gtddaknjgq.html

C#:   a.Concat(b).ToList()
来源：http://dali.chenzaomai.com/Article/details/gtwbezvapz.html

[D09] 排序（升序）
来源：http://dali.wangshuangyany.cn/Article/details/gthgnzhtva.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cqqwz.cn/Article/details/gtbzeioutf.html

PHP:  sort($arr);
来源：http://dali.cheryme.top/Article/details/gtzydmapdi.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.fzhhl.top/Article/details/gtxqoapsin.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yongpay.top/Article/details/gtgerjjhpu.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xuanzx.com/Article/details/gtjcjcdvfq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtcptalgfp.html

Ruby: arr.sort
来源：http://dali.pycfn.com/Article/details/gtjweevlfw.html

C#:   list.Sort();
来源：http://dali.gaohongyu789.top/Article/details/gtpmbbrjqx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.wangshuangyany.cn/Article/details/gthuxczobv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yvedp.cn/Article/details/gtuorrrzgt.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenzaomai.com/Article/details/gtkqvrgkfc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hammf.cn/Article/details/gtqoijnnkn.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jiagoushi.top/Article/details/gtclogpjkl.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sysykeji.top/Article/details/gtccwralxx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cashguo.top/Article/details/gteecyehjb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xziqi.cn/Article/details/gtjxrvkbth.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yj202588.top/Article/details/gtwcbshzlp.html

[D11] 反转数组
来源：http://dali.shuidangran.top/Article/details/gtqgkuwfca.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yuanzhike.top/Article/details/gtpfmgfkxh.html

PHP:  array_reverse($arr);
来源：http://dali.bjfxy.top/Article/details/gtcwwtxdis.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.quarkkingdee.top/Article/details/gtopsnclgx.html

TS:   [...arr].reverse();
来源：http://dali.tian-w.cn/Article/details/gtmoxbbbgo.html

Java: Collections.reverse(list);
来源：http://dali.xuetiantiany.cn/Article/details/gtoedeipgf.html

Go:   slices.Reverse(arr)
来源：http://dali.jinqigufen.top/Article/details/gtlqlkzdfe.html

Ruby: arr.reverse
来源：http://dali.jqgfzy.top/Article/details/gtvgpxjzfm.html


<!-- 参考信息 -->