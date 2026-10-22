代发 wailian999

PHP:  $a && $b || !$c
来源：http://dali.tianlin.xyz/Article/details/gtronsfeji.html

JS:   a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gtfyabhvzg.html

TS:   a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gtdvywucpc.html

Java: a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtynqdhrym.html

Go:   a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gtvhdfzget.html

Ruby: a && b || !c
来源：http://dali.fzhhl.top/Article/details/gtfcnwrgxt.html

C#:   a && b || !c
来源：http://dali.daxiang520.top/Article/details/gtqqrgwqjj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.mhx1999.top/Article/details/gtrdpvhlnb.html

Py:   if not data: return
来源：http://dali.jinqigfzy.top/Article/details/gtvxwequsx.html

PHP:  if (!$data) { return; }
来源：http://dali.iojbl.cn/Article/details/gtgdkugkqt.html

JS:   if (!data) return;
来源：http://dali.chenlongwang.top/Article/details/gthbidlpim.html

TS:   if (!data) return;
来源：http://dali.jlsjyb.cn/Article/details/gtottvsqec.html

Java: if (data == null) return;
来源：http://dali.aizwys.cn/Article/details/gtjdylrkwv.html

Go:   if data == nil { return }
来源：http://dali.jianghu66.top/Article/details/gtutxgulhb.html

Ruby: return if data.nil?
来源：http://dali.meibo888.top/Article/details/gtgfwhibxu.html

C#:   if (data == null) return;
来源：http://dali.tianlin.xyz/Article/details/gtztlkeumf.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtnlgjdqyw.html

C. 函数与作用域
来源：http://dali.hnxiangtu.top/Article/details/gtpjkscnwv.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtiabdinzp.html

[C01] 定义函数
来源：http://dali.dianchejie.cn/Article/details/gtvbzawxnz.html

Py:   def add(a, b): return a + b
来源：http://dali.ppjwa.cn/Article/details/gtkocapzwq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinqigfzy.top/Article/details/gtfqoslcel.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtufpfrnak.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gtidvqhgcy.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gtrpkjufzh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zdqjudy.top/Article/details/gtnsvwbjgf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hfpthk.cn/Article/details/gtbxjdkxvr.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtylngxjue.html

[C02] 默认参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqjmilwur.html

Py:   def greet(name="World"): return name
来源：http://dali.bjfxy.top/Article/details/gttqcscvut.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.sweek.top/Article/details/gtlirfpdbo.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtoswalecl.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gtkmfqjety.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ivvv.top/Article/details/gtyukjhpjo.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.sxryk.cn/Article/details/gtjrbsvmlp.html

Ruby: def greet(name = "World") = name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsxwlmmrb.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.havefunace.top/Article/details/gtatkmkhac.html

[C03] 可变参数
来源：http://dali.birdmap.top/Article/details/gtkyqbnllu.html

Py:   def total(*args): return sum(args)
来源：http://dali.gotoacloud.top/Article/details/gtrrtasbjg.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ydzc1.top/Article/details/gtdospgcjs.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.dianchejie.cn/Article/details/gtqofrynzc.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhengqikj.top/Article/details/gtvylvtmyl.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yuanzhike.top/Article/details/gtecyblnoa.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtctvtkebg.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.nanxuanxn.top/Article/details/gtzvwtbmmb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.smart0.xyz/Article/details/gtsdhsknou.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gaohongyu789.top/Article/details/gtxhcfneut.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xinyue.icu/Article/details/gtvzjbtcwu.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jqgufenzy.top/Article/details/gtozesptxx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yuxming.cn/Article/details/gtrlpdxbed.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shanyushiyangtech.top/Article/details/gtyaiikube.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shanyushiyangtech.top/Article/details/gtqvxlkkzo.html

Go:   // 无：用配置结构体参数
来源：http://dali.guannengcc.top/Article/details/gteawiftce.html

Ruby: f(a: 1, b: 2)
来源：http://dali.9152youxi.cn/Article/details/gtkbpqlroc.html

C#:   f(a: 1, b: 2)
来源：http://dali.jlsjyb.cn/Article/details/gtbbamolkh.html

[C05] 返回多个值
来源：http://dali.yvedp.cn/Article/details/gtrddcyfnz.html

Py:   return a, b
来源：http://dali.yuxming.cn/Article/details/gtaaephpkd.html

PHP:  return [$a, $b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcxsevyxn.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yongpay.top/Article/details/gtpohhtvtx.html

TS:   return { a, b };
来源：http://dali.cucudq.cn/Article/details/gtycckbtpe.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.quarkkingdee.top/Article/details/gtgkwazhhy.html

Go:   return a, b
来源：http://dali.nwbrower.top/Article/details/gtxycxxavx.html

Ruby: return a, b
来源：http://dali.jianghu66.top/Article/details/gtiojyikdi.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yueranfly.top/Article/details/gtcndzeacp.html

[C06] 匿名函数 / lambda
来源：http://dali.guowangkeji.top/Article/details/gtswtzcoau.html

Py:   square = lambda x: x * x
来源：http://dali.jinghuilouyu.cn/Article/details/gtqcwstxyi.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gthdqwylbh.html

JS:   const square = x => x * x;
来源：http://dali.snrcjt.cn/Article/details/gtzjfqtytr.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.sufxvd.cn/Article/details/gtjxhsmcbp.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ivvv.top/Article/details/gtffmjlqhy.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jianghu66.top/Article/details/gtorpyxkvb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.daxiang520.top/Article/details/gtkrrvmkgg.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jlsjyb.cn/Article/details/gtfjzkqhwl.html

[C07] 把函数作为参数传入
来源：http://dali.chenzaomai.com/Article/details/gtyhgqmsiz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.nwbrower.top/Article/details/gtodscpwfm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.dashuyun.cn/Article/details/gtzqywtskv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.chenjidiqi.icu/Article/details/gtzsaewuot.html

TS:   arr.map(String)
来源：http://dali.wangshuangyany.cn/Article/details/gtjonrvzeg.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.sufxvd.cn/Article/details/gtfxeexuck.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.nanxinkj.top/Article/details/gtuxromuka.html

Ruby: arr.map(&:upcase)
来源：http://dali.aibaodan.cn/Article/details/gtnytunrcl.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yongpay.top/Article/details/gtkvnyznei.html

[C08] 闭包
来源：http://dali.mhx1999.top/Article/details/gtllczozca.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.aibaodan.cn/Article/details/gtjwnedzrh.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hywenlv.cn/Article/details/gtkmuihhxq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yangfankeji.com/Article/details/gtnsjshvgr.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cheryme.top/Article/details/gtjukgiikw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.tian-w.cn/Article/details/gtgszlrzla.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.aibaodan.cn/Article/details/gtysgkgomm.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yj202588.top/Article/details/gtsmtibxfg.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ydzc1.top/Article/details/gtwyxedqol.html

[C09] 递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtltoapemf.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.redwolf501.top/Article/details/gtuxxfygoq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.guannengcc.top/Article/details/gtkdyqqaqq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.smart0.xyz/Article/details/gtdiwzfqif.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.smart0.xyz/Article/details/gtqerhiplm.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.9152youxi.cn/Article/details/gtgtkkxbeo.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yj20258888.top/Article/details/gtpnrfhxzz.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jinqigfzy.top/Article/details/gtbfglhmjd.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yangfankeji.com/Article/details/gttqxpwsul.html

[C10] 变量作用域
来源：http://dali.tanke756.top/Article/details/gtpjfjmvpe.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.tianlin.xyz/Article/details/gthjmdnqhb.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.daria6918.cn/Article/details/gtcimzaklv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xinyue.icu/Article/details/gtorbstcph.html

TS:   同 JS
来源：http://dali.hnxiangtu.top/Article/details/gtrdsdrhpz.html

Java: 方法内为块级作用域
来源：http://dali.gaohongyu789.top/Article/details/gtzweqsuce.html

Go:   花括号块级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gtsckpkqgl.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jqgfzy.top/Article/details/gtcdbfsrew.html

C#:   块级作用域
来源：http://dali.316326.xyz/Article/details/gtbgdmctlt.html

[C11] 模块导入与导出
来源：http://dali.chenjidiqi.icu/Article/details/gtthfneweg.html

Py:   from module import func
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvxdbmtdh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hammf.cn/Article/details/gtgzlyfoqk.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ybcxt.top/Article/details/gtraljwqex.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhoulong.xyz/Article/details/gtlzewnwgz.html

Java: import java.util.List;
来源：http://dali.cucudq.cn/Article/details/gtbvknvdcb.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.pengpengdd.cyou/Article/details/gtlapzzadw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shuidangran.top/Article/details/gtaacshzsd.html

C#:   using System.Text;
来源：http://dali.yanxiufei.cn/Article/details/gtufrilkio.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhongyouzk.top/Article/details/gtjconvjjm.html

Py:   (lambda: print("run"))()
来源：http://dali.xinyue.icu/Article/details/gtanraenwc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jiagoushi.top/Article/details/gtqpikyqef.html

JS:   (() => { console.log("run"); })();
来源：http://dali.redwolf501.top/Article/details/gtfkazbwon.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hysaishi.cn/Article/details/gtvnymrnyk.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jlsjyb.cn/Article/details/gtzvtrhzaf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gzhubu.top/Article/details/gtcnrrsyqn.html

Ruby: -> { puts "run" }.call
来源：http://dali.xuanzx.com/Article/details/gtubdyhgib.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.guannengcc.top/Article/details/gtekgfcvvh.html

[C13] 类型声明 / 类型注解
来源：http://dali.tanke756.top/Article/details/gttpqqmklh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhongyouzk.top/Article/details/gtcisghhfn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cqqwz.cn/Article/details/gtlwjrxwyr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cqqwz.cn/Article/details/gtjaqlutqj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj20258.top/Article/details/gtdrepmvge.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gtiyxqewgb.html

Go:   func add(a, b int) int
来源：http://dali.jinghuilouyu.cn/Article/details/gttiertyye.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.tian-w.cn/Article/details/gthclordsz.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ehwqpu.com/Article/details/gtjqvlqvju.html

[C14] 泛型函数
来源：http://dali.yuanzhike.top/Article/details/gtfqpuiqfq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.quarkkingdee.top/Article/details/gtkksklalt.html

PHP:  // 无泛型
来源：http://dali.bjfxy.top/Article/details/gtgedlclnb.html

JS:   // 无泛型
来源：http://dali.tianlin.xyz/Article/details/gtcnmuaqgj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cashguo.top/Article/details/gtlwclelft.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.wangdashe.top/Article/details/gtdkuhlpgj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xziqi.cn/Article/details/gtsbleqxbf.html

Ruby: # 无泛型
来源：http://dali.feifeiyinyue.top/Article/details/gtscufpeal.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shzxlz.cn/Article/details/gtkdhwtomk.html

[C15] 解构 / 展开参数
来源：http://dali.jqgfzy.top/Article/details/gtdadixipt.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.wangshuangyany.cn/Article/details/gtyhtlplny.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgaijtjcc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ehwqpu.com/Article/details/gtvltazpcg.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jyoumei.cn/Article/details/gtuudlclle.html

Java: // 无解构
来源：http://dali.jinghuilouyu.cn/Article/details/gtuembfazr.html

Go:   // 无解构
来源：http://dali.smart0.xyz/Article/details/gtqnshlqko.html

Ruby: a, b = pair
来源：http://dali.zycfv.cn/Article/details/gtawdbavyl.html

C#:   var (a, b) = pair;
来源：http://dali.meibo888.top/Article/details/gtclapkawl.html

[C16] 函数 / 方法重载
来源：http://dali.pycfn.com/Article/details/gtkfoqvwmw.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.iojbl.cn/Article/details/gtmkshibjt.html

PHP:  // 无重载
来源：http://dali.chenjidiqi.icu/Article/details/gtghiuvnzy.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yj202588.top/Article/details/gtdpdrqjcv.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.meibo888.top/Article/details/gtwbhrrcka.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhongyouzk.top/Article/details/gtcwfxxowb.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhixingplan.top/Article/details/gtogwtwuzn.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cashguo.top/Article/details/gtvxxsrdrw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xuanzx.com/Article/details/gtsrzgotyq.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtftakcgbu.html

D. 数组 / 列表 / 集合
来源：http://dali.jqgufenzy.top/Article/details/gttzyhkayd.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gthkcodaka.html

[D01] 创建数组 / 列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gthkfqabsc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinqigfzy.top/Article/details/gtdivnqaob.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jqgfzy.top/Article/details/gtplrutfrf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.daxiang520.top/Article/details/gtvfslufaw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xuetiantiany.cn/Article/details/gtbqqzqmpg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ivvv.top/Article/details/gtynkkcmpa.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.pycfn.com/Article/details/gtznzrtvtt.html

Ruby: arr = [1, 2, 3]
来源：http://dali.tian-w.cn/Article/details/gtjberholl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.haohaochexian.top/Article/details/gtanxulprp.html

[D02] 追加元素到末尾
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbcmxujag.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.svipenyu.cn/Article/details/gtvkcraeve.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zycfv.cn/Article/details/gtmenwgofr.html

JS:   arr.push(4);
来源：http://dali.chenjidiqi.icu/Article/details/gtfyqxivhn.html

TS:   arr.push(4);
来源：http://dali.9152youxi.cn/Article/details/gtedybeowd.html

Java: list.add(4);
来源：http://dali.hnqzz.top/Article/details/gtwzsvsphy.html

Go:   arr = append(arr, 4)
来源：http://dali.sufxvd.cn/Article/details/gtbdmqhkah.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.haohaochexian.top/Article/details/gtdezgznqn.html

C#:   list.Add(4);
来源：http://dali.tanke756.top/Article/details/gtscsqhipb.html

[D03] 在指定位置插入元素
来源：http://dali.aizwys.cn/Article/details/gtcryvpced.html

Py:   arr.insert(0, 0)
来源：http://dali.zhengqikj.top/Article/details/gtpmbenkto.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.redwolf501.top/Article/details/gtnujjfyrf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xylfe.cn/Article/details/gtfjwyxzxu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.nwbrower.top/Article/details/gtolajpamp.html

Java: list.add(0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtchnnykvl.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jiagoushi.top/Article/details/gtjtoexqlu.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.wangshuangyany.cn/Article/details/gtefgcofst.html

C#:   list.Insert(0, 0);
来源：http://dali.xylfe.cn/Article/details/gtnoikpaqz.html

[D04] 删除元素
来源：http://dali.tian-w.cn/Article/details/gtmxqumamh.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhengqikj.top/Article/details/gtglnyitgx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtqswlgoxn.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zycfv.cn/Article/details/gtfgobvzda.html

TS:   arr.splice(0, 1);
来源：http://dali.yvedp.cn/Article/details/gttlnwzadz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cashguo.top/Article/details/gtexiwmmba.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.pengpengdd.cyou/Article/details/gtyaoedsgi.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yonumen.top/Article/details/gtqqnuczrl.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.chenlongwang.top/Article/details/gtpjfzitlx.html

[D05] 访问与修改元素
来源：http://dali.yj20258888.top/Article/details/gtkjstvqln.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.fengsongda.top/Article/details/gttqisbwcl.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.fzhhl.top/Article/details/gtkzgrstxm.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.guowangkeji.top/Article/details/gtnjwchceo.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hongshengwenyu.top/Article/details/gtbenqwbwd.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gogol.net.cn/Article/details/gtrgjwowng.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cucudq.cn/Article/details/gtpyrnfass.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvqgapayb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jqgufenzy.top/Article/details/gtmchilhfj.html

[D06] 数组长度
来源：http://dali.nanxinkj.top/Article/details/gtzkvbxaqk.html

Py:   len(arr)
来源：http://dali.guowangkeji.top/Article/details/gtpqatyjtf.html

PHP:  count($arr);
来源：http://dali.snrcjt.cn/Article/details/gtvtqhovog.html

JS:   arr.length
来源：http://dali.zhiwuduotai.top/Article/details/gtfenneohe.html

TS:   arr.length
来源：http://dali.yj20258888.top/Article/details/gtiwgttpei.html

Java: list.size();
来源：http://dali.cheryme.top/Article/details/gtcuohfaav.html

Go:   len(arr)
来源：http://dali.cqqwz.cn/Article/details/gtocsgggtn.html

Ruby: arr.length; arr.size
来源：http://dali.gaohongyu789.top/Article/details/gtzlsdoztt.html

C#:   list.Count;
来源：http://dali.yvedp.cn/Article/details/gtaimjtyqy.html

[D07] 切片 / 取子数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmlfylviq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sysykeji.top/Article/details/gtwsyignxx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hysaishi.cn/Article/details/gtwcrashhm.html

JS:   arr.slice(1, 4);
来源：http://dali.sysykeji.top/Article/details/gtoefyuxtv.html

TS:   arr.slice(1, 4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpvmaiihq.html

Java: list.subList(1, 4);
来源：http://dali.shanyushiyangtech.top/Article/details/gttjcpvvlg.html

Go:   arr[1:4]
来源：http://dali.xylfe.cn/Article/details/gttnpyrkzt.html

Ruby: arr[1, 3]
来源：http://dali.vqdsnc.cn/Article/details/gtfsftmsug.html

C#:   list.GetRange(1, 3);
来源：http://dali.chenzaomai.com/Article/details/gtamjoklsd.html

[D08] 合并两个数组
来源：http://dali.zhongyouzk.top/Article/details/gtbibumfxg.html

Py:   a + b;  a.extend(b)
来源：http://dali.yueranfly.top/Article/details/gtmrtmaeke.html

PHP:  array_merge($a, $b);
来源：http://dali.aizwys.cn/Article/details/gtkbpgnbbl.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.gaohongyu789.top/Article/details/gtrsrnvtmy.html

TS:   [...a, ...b];
来源：http://dali.fzhhl.top/Article/details/gteqepjfxq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.nanxuanxn.top/Article/details/gtdjwckzsv.html

Go:   append(a, b...)
来源：http://dali.xuanzx.com/Article/details/gtmhvkxlzc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yj20258888.top/Article/details/gtdzisikvr.html

C#:   a.Concat(b).ToList()
来源：http://dali.sxryk.cn/Article/details/gtfljeydys.html

[D09] 排序（升序）
来源：http://dali.aizwys.cn/Article/details/gtknkliwkb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenlongwang.top/Article/details/gtekbaipgy.html

PHP:  sort($arr);
来源：http://dali.redwolf501.top/Article/details/gtvdhizhzq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.chenlongwang.top/Article/details/gtvxgomktt.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.andypj.xyz/Article/details/gtvaazdagr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yangfankeji.com/Article/details/gtnqarvted.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkuvzcurv.html

Ruby: arr.sort
来源：http://dali.yangfankeji.com/Article/details/gtzjcvigsk.html

C#:   list.Sort();
来源：http://dali.bjfxy.top/Article/details/gtrzqjkxaf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhoulong.xyz/Article/details/gttrlocxxj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ybcxt.top/Article/details/gtbglostzf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tanke756.top/Article/details/gtusmxoweu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ydzc1.top/Article/details/gtvzkuqkke.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tanke756.top/Article/details/gtjapcpyny.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.daria6918.cn/Article/details/gtbzybcflz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.aizwys.cn/Article/details/gthdaihmts.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.aizwys.cn/Article/details/gtxsuwnlqb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.wangshuangyany.cn/Article/details/gttynupylg.html

[D11] 反转数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtglyxdqmp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yuxming.cn/Article/details/gtljsiqqst.html

PHP:  array_reverse($arr);
来源：http://dali.haohaochexian.top/Article/details/gtgsbijpsa.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.0kj1m.cn/Article/details/gtluukdqbv.html

TS:   [...arr].reverse();
来源：http://dali.0kj1m.cn/Article/details/gtufzeqqip.html

Java: Collections.reverse(list);
来源：http://dali.zycfv.cn/Article/details/gtlsyjjvfb.html

Go:   slices.Reverse(arr)
来源：http://dali.tianlin.xyz/Article/details/gtdgltjsrx.html

Ruby: arr.reverse
来源：http://dali.gaohongyu789.top/Article/details/gtqzrfngsn.html

C#:   list.Reverse();
来源：http://dali.iojbl.cn/Article/details/gtvriyuwzy.html

[D12] 查找元素下标
来源：http://dali.yangfankeji.com/Article/details/gtoipxyqdb.html

Py:   arr.index(x);  x in arr
来源：http://dali.hysaishi.cn/Article/details/gttkfjyfmj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtqwszmfie.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guannengcc.top/Article/details/gtrcnwhwqn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhoulong.xyz/Article/details/gtntdomaak.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sufxvd.cn/Article/details/gtlzaipvbd.html

Go:   slices.Index(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtqlsknyob.html

Ruby: arr.index(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtvwzrqrky.html

C#:   list.IndexOf(x);
来源：http://dali.0kj1m.cn/Article/details/gtlcamknbb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yuxming.cn/Article/details/gtghyivvgr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hywenlv.cn/Article/details/gtyhjieayk.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cqqwz.cn/Article/details/gtwtbdpwkx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrrwteloi.html

TS:   arr.filter(x => x > 3)
来源：http://dali.dianchejie.cn/Article/details/gtyocfnlsz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yanxiufei.cn/Article/details/gtaroonysl.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinqigufen.top/Article/details/gtncwyqbzj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sweek.top/Article/details/gtffkqynjt.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtoxshnabz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.smart0.xyz/Article/details/gtyimsgixx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yonumen.top/Article/details/gtxprdjugu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yongpay.top/Article/details/gtbkpbchuw.html

JS:   arr.map(x => x * 2)
来源：http://dali.xinyue.icu/Article/details/gtznmxctxj.html

TS:   arr.map(x => x * 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtegweeasw.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.chenlongwang.top/Article/details/gtyigibjyz.html

Go:   // 手写循环
来源：http://dali.jinqigufen.top/Article/details/gtvwqryfqc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zycfv.cn/Article/details/gtqdsflhnf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tanke756.top/Article/details/gtmqnkagoa.html

[D15] 去重
来源：http://dali.zhoulong.xyz/Article/details/gthbhtsauq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhongyouzk.top/Article/details/gttmndvfvo.html

PHP:  array_unique($arr);
来源：http://dali.jqgfzy.top/Article/details/gttdxnnhoq.html

JS:   [...new Set(arr)]
来源：http://dali.yj202588.top/Article/details/gtiyurgkur.html

TS:   [...new Set(arr)]
来源：http://dali.0kj1m.cn/Article/details/gtgwzrmvrp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jlsjyb.cn/Article/details/gtjjnylbya.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.havefunace.top/Article/details/gtemevipek.html

Ruby: arr.uniq
来源：http://dali.ydzc1.top/Article/details/gttqadtldr.html


<!-- 参考信息 -->