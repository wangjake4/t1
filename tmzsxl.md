代发 wailian999

PHP:  $a && $b || !$c
来源：http://dali.jyoumei.cn/Article/details/gt2xegucper.html

JS:   a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gt2lkjwspkj.html

TS:   a && b || !c
来源：http://dali.iojbl.cn/Article/details/gt2bxkcexhw.html

Java: a && b || !c
来源：http://dali.cheryme.top/Article/details/gt2mkubwocf.html

Go:   a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gt2wdctmytq.html

Ruby: a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gt2mqhlpjyc.html

C#:   a && b || !c
来源：http://dali.sysykeji.top/Article/details/gt2tffjdgjh.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zycfv.cn/Article/details/gt2yielavfa.html

Py:   if not data: return
来源：http://dali.shuidangran.top/Article/details/gt2pldgonop.html

PHP:  if (!$data) { return; }
来源：http://dali.hnqzz.top/Article/details/gt2orujwkjz.html

JS:   if (!data) return;
来源：http://dali.hnxiangtu.top/Article/details/gt2lbnyqguk.html

TS:   if (!data) return;
来源：http://dali.pengpengdd.cyou/Article/details/gt2vrednnpd.html

Java: if (data == null) return;
来源：http://dali.tian-w.cn/Article/details/gt2corswwvn.html

Go:   if data == nil { return }
来源：http://dali.jinqigfzy.top/Article/details/gt2xlmwqlbo.html

Ruby: return if data.nil?
来源：http://dali.fzhhl.top/Article/details/gt2ouotkxwr.html

C#:   if (data == null) return;
来源：http://dali.cdnleiting.top/Article/details/gt2pmtssnjc.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2yycfjhdh.html

C. 函数与作用域
来源：http://dali.zhixingplan.top/Article/details/gt2bfudkmhw.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2piuhkmpx.html

[C01] 定义函数
来源：http://dali.cheryme.top/Article/details/gt2cpaaiycc.html

Py:   def add(a, b): return a + b
来源：http://dali.jinqigufen.top/Article/details/gt2jyjwazvv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gt2mmtlpngt.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gt2mbjwmyrq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2fwooghcs.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gt2lxqrakyh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hovjajby.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hysaishi.cn/Article/details/gt2hlqyqhmq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gt2czqomqfs.html

[C02] 默认参数
来源：http://dali.zhengqikj.top/Article/details/gt2jtvqjmuj.html

Py:   def greet(name="World"): return name
来源：http://dali.jinqigfzy.top/Article/details/gt2ideicdae.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.sufxvd.cn/Article/details/gt2sgazkmot.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.gzhubu.top/Article/details/gt2znphzmwo.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.snrcjt.cn/Article/details/gt2mmubixjj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.svipenyu.cn/Article/details/gt2hczkcdfr.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.redwolf501.top/Article/details/gt2nxogdegy.html

Ruby: def greet(name = "World") = name
来源：http://dali.ivvv.top/Article/details/gt2hfbtvcsc.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xinyue.icu/Article/details/gt2albgmhcl.html

[C03] 可变参数
来源：http://dali.iojbl.cn/Article/details/gt2dsdjhxzd.html

Py:   def total(*args): return sum(args)
来源：http://dali.sysykeji.top/Article/details/gt2maztxlps.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.9152youxi.cn/Article/details/gt2lyfogoet.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2cgeeugxj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhongyouzk.top/Article/details/gt2vtejbhcj.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.tanke756.top/Article/details/gt2ockvsyrs.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ydzc1.top/Article/details/gt2phsnsmhc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xhidalmw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.feifeiyinyue.top/Article/details/gt2mfaazqtq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cucudq.cn/Article/details/gt2zlowaunp.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2dbbucowi.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yvedp.cn/Article/details/gt2xysmktsx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.pycfn.com/Article/details/gt2fxiwxwev.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.gzhubu.top/Article/details/gt2vutoxuiy.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zdqjudy.top/Article/details/gt2bfiblfaa.html

Go:   // 无：用配置结构体参数
来源：http://dali.aizwys.cn/Article/details/gt2epuuuvsa.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yongpay.top/Article/details/gt2gwvdepcu.html

C#:   f(a: 1, b: 2)
来源：http://dali.ppjwa.cn/Article/details/gt2ywmqafpm.html

[C05] 返回多个值
来源：http://dali.redwolf501.top/Article/details/gt2uywezjtl.html

Py:   return a, b
来源：http://dali.tanke756.top/Article/details/gt2ttozajha.html

PHP:  return [$a, $b];
来源：http://dali.havefunace.top/Article/details/gt2puyaepmk.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yuxming.cn/Article/details/gt2pssvcjtm.html

TS:   return { a, b };
来源：http://dali.yj20258888.top/Article/details/gt2fjtzgdkr.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ppjwa.cn/Article/details/gt2tdlzcllb.html

Go:   return a, b
来源：http://dali.dianchejie.cn/Article/details/gt2doucmkgk.html

Ruby: return a, b
来源：http://dali.nwbrower.top/Article/details/gt2ruvpvlcz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yonumen.top/Article/details/gt2lxrphkqh.html

[C06] 匿名函数 / lambda
来源：http://dali.guannengcc.top/Article/details/gt2iaujrwxw.html

Py:   square = lambda x: x * x
来源：http://dali.jianghu66.top/Article/details/gt2axssmeqd.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2swwwtfvy.html

JS:   const square = x => x * x;
来源：http://dali.cashguo.top/Article/details/gt2mialetjx.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jiagoushi.top/Article/details/gt2vksputcf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hsbwcejj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2engyzbwh.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hammf.cn/Article/details/gt2yftmkgmh.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shangyingyoupin.top/Article/details/gt2cpzqfemb.html

[C07] 把函数作为参数传入
来源：http://dali.shzxlz.cn/Article/details/gt2hhaegsgj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.guannengcc.top/Article/details/gt2sdzfrssc.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.guowangkeji.top/Article/details/gt2gcjqzhpi.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hammf.cn/Article/details/gt2ekloptyc.html

TS:   arr.map(String)
来源：http://dali.hongshengwenyu.top/Article/details/gt2oxnbkgpr.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.wangdashe.top/Article/details/gt2wnkjtdzh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yanxiufei.cn/Article/details/gt2plucdvge.html

Ruby: arr.map(&:upcase)
来源：http://dali.meibo888.top/Article/details/gt2nqrmusgm.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.gaohongyu789.top/Article/details/gt2zzjhroti.html

[C08] 闭包
来源：http://dali.birdmap.top/Article/details/gt2mvrwbyeb.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.pycfn.com/Article/details/gt2nrzyftty.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.gogol.net.cn/Article/details/gt2eufofbxz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.iojbl.cn/Article/details/gt2aryshuwq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jianghu66.top/Article/details/gt2subduyca.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.nanxinkj.top/Article/details/gt2sgjifdgs.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hfpthk.cn/Article/details/gt2anphishk.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhoulong.xyz/Article/details/gt2ljwyptoc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.havefunace.top/Article/details/gt2pyrardjw.html

[C09] 递归
来源：http://dali.tianlin.xyz/Article/details/gt2vtfzqvcm.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhongyouzk.top/Article/details/gt2prxdemti.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yvedp.cn/Article/details/gt2jxelbxvg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hnqzz.top/Article/details/gt2trzvpjyi.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hywenlv.cn/Article/details/gt2ajchfagi.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cqqwz.cn/Article/details/gt2lwalanah.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.wangdashe.top/Article/details/gt2uemwnyyw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lkokbgrp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jlsjyb.cn/Article/details/gt2qidnclez.html

[C10] 变量作用域
来源：http://dali.pycfn.com/Article/details/gt2bhdzgkbk.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yvedp.cn/Article/details/gt2irebhuie.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.tianlin.xyz/Article/details/gt2xeuvmeyp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zycfv.cn/Article/details/gt2mqfrdqjo.html

TS:   同 JS
来源：http://dali.sufxvd.cn/Article/details/gt2ozhnemrs.html

Java: 方法内为块级作用域
来源：http://dali.yj20258.top/Article/details/gt2idamuqci.html

Go:   花括号块级作用域
来源：http://dali.pycfn.com/Article/details/gt2avelyxmg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ehwqpu.com/Article/details/gt2vpvtjspk.html

C#:   块级作用域
来源：http://dali.zdqjudy.top/Article/details/gt2chubomin.html

[C11] 模块导入与导出
来源：http://dali.wangshuangyany.cn/Article/details/gt2okqhcfqu.html

Py:   from module import func
来源：http://dali.sweek.top/Article/details/gt2qlvltimw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.9152youxi.cn/Article/details/gt2iwpzxnjc.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.316326.xyz/Article/details/gt2ycabolsb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jinqigfzy.top/Article/details/gt2lnzfyvcr.html

Java: import java.util.List;
来源：http://dali.tian-w.cn/Article/details/gt2ephfeuzo.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yueranfly.top/Article/details/gt2rsgtojbt.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.c1oappe.top/Article/details/gt2vjgwsxfe.html

C#:   using System.Text;
来源：http://dali.zycfv.cn/Article/details/gt2sgsqkjnn.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mcnprfaz.html

Py:   (lambda: print("run"))()
来源：http://dali.smart0.xyz/Article/details/gt2avyukpvf.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yuanzhike.top/Article/details/gt2ithvzaqz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhongyouzk.top/Article/details/gt2nxxwtgwa.html

TS:   (() => { console.log("run"); })();
来源：http://dali.iojbl.cn/Article/details/gt2oijynyxt.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gaohongyu789.top/Article/details/gt2ugpqunun.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.iojbl.cn/Article/details/gt2wftildtw.html

Ruby: -> { puts "run" }.call
来源：http://dali.yonumen.top/Article/details/gt2sighailc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2kqlhbkzm.html

[C13] 类型声明 / 类型注解
来源：http://dali.hfpthk.cn/Article/details/gt2uvresqxy.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ydebbyce.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ppwmybsr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gogol.net.cn/Article/details/gt2deewxjky.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gt2gusoocqi.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gt2xyhbntcx.html

Go:   func add(a, b int) int
来源：http://dali.zhongyouzk.top/Article/details/gt2noigeswa.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.tian-w.cn/Article/details/gt2zmrxnsky.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jlsjyb.cn/Article/details/gt2qvhvddpe.html

[C14] 泛型函数
来源：http://dali.tian-w.cn/Article/details/gt2pndrnxno.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hnxiangtu.top/Article/details/gt2yzslscqh.html

PHP:  // 无泛型
来源：http://dali.316326.xyz/Article/details/gt2vvzynglg.html

JS:   // 无泛型
来源：http://dali.birdmap.top/Article/details/gt2znwrjvfj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jyoumei.cn/Article/details/gt2ujpvwmqh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yangfankeji.com/Article/details/gt2jodicstw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.pengpengdd.cyou/Article/details/gt2pzezathw.html

Ruby: # 无泛型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pwbdczqt.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.mhx1999.top/Article/details/gt2ctcgzvij.html

[C15] 解构 / 展开参数
来源：http://dali.hnqzz.top/Article/details/gt2ifrmuigw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.aizwys.cn/Article/details/gt2lthqhxka.html

PHP:  [$a, $b] = $pair;
来源：http://dali.svipenyu.cn/Article/details/gt2izzcrfit.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2dhseckae.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.aizwys.cn/Article/details/gt2fcymeauh.html

Java: // 无解构
来源：http://dali.shzxlz.cn/Article/details/gt2esfmjxmq.html

Go:   // 无解构
来源：http://dali.wangshuangyany.cn/Article/details/gt2utsmayef.html

Ruby: a, b = pair
来源：http://dali.gogol.net.cn/Article/details/gt2spwvyoty.html

C#:   var (a, b) = pair;
来源：http://dali.chenjidiqi.icu/Article/details/gt2cveempom.html

[C16] 函数 / 方法重载
来源：http://dali.hysaishi.cn/Article/details/gt2gjwhorac.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhiwuduotai.top/Article/details/gt2hwjkzbza.html

PHP:  // 无重载
来源：http://dali.hnxiangtu.top/Article/details/gt2bfppzsql.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.wangdashe.top/Article/details/gt2hsjpuzhm.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.snrcjt.cn/Article/details/gt2fggrlfgn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sysykeji.top/Article/details/gt2dwkfimrt.html

Go:   // 无重载：用不同函数名
来源：http://dali.yonumen.top/Article/details/gt2gzodpgdp.html

Ruby: # 无重载：靠动态参数
来源：http://dali.guannengcc.top/Article/details/gt2ucibwdud.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.tian-w.cn/Article/details/gt2bqtzjkbf.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2cckagxtg.html

D. 数组 / 列表 / 集合
来源：http://dali.hongshengwenyu.top/Article/details/gt2tfuejwda.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2zridzzeg.html

[D01] 创建数组 / 列表
来源：http://dali.nwbrower.top/Article/details/gt2owolacpf.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yuxming.cn/Article/details/gt2vjmzwlmh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.sysykeji.top/Article/details/gt2kfzwrzqv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.iojbl.cn/Article/details/gt2kyuuqirf.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.redwolf501.top/Article/details/gt2eobvfyks.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.9152youxi.cn/Article/details/gt2frbluxen.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.aizwys.cn/Article/details/gt2aljshydq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.wangshuangyany.cn/Article/details/gt2hvrgaaxo.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ppjwa.cn/Article/details/gt2dgfdxpdk.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2rfkypkmc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhongyouzk.top/Article/details/gt2pmwbjmsz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xziqi.cn/Article/details/gt2mzrofwgk.html

JS:   arr.push(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2esnsjdvk.html

TS:   arr.push(4);
来源：http://dali.zdqjudy.top/Article/details/gt2wdmonazh.html

Java: list.add(4);
来源：http://dali.nwbrower.top/Article/details/gt2hmppbxry.html

Go:   arr = append(arr, 4)
来源：http://dali.zhoulong.xyz/Article/details/gt2yfujrcdu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.havefunace.top/Article/details/gt2ukmfywyn.html

C#:   list.Add(4);
来源：http://dali.ppjwa.cn/Article/details/gt2rugflyzo.html

[D03] 在指定位置插入元素
来源：http://dali.gaohongyu789.top/Article/details/gt2vppaxplm.html

Py:   arr.insert(0, 0)
来源：http://dali.zhoulong.xyz/Article/details/gt2aphkwlsg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhiwuduotai.top/Article/details/gt2kavkyocz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yongpay.top/Article/details/gt2qbjhjpts.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.nwbrower.top/Article/details/gt2vidusnew.html

Java: list.add(0, 0);
来源：http://dali.gogol.net.cn/Article/details/gt2kgflqctu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hysaishi.cn/Article/details/gt2sxzdujju.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.aibaodan.cn/Article/details/gt2odliizox.html

C#:   list.Insert(0, 0);
来源：http://dali.tanke756.top/Article/details/gt2ewnhqblp.html

[D04] 删除元素
来源：http://dali.feifeiyinyue.top/Article/details/gt2rpcfyakz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shuidangran.top/Article/details/gt2hmkmjyds.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ehwqpu.com/Article/details/gt2jstioyha.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhongyouzk.top/Article/details/gt2zdnlpfgm.html

TS:   arr.splice(0, 1);
来源：http://dali.hongshengwenyu.top/Article/details/gt2uvxizpfc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jyoumei.cn/Article/details/gt2ivgfwwlm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.birdmap.top/Article/details/gt2sevknvay.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xinyue.icu/Article/details/gt2ciyfsofh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.tian-w.cn/Article/details/gt2jivndhly.html

[D05] 访问与修改元素
来源：http://dali.chenjidiqi.icu/Article/details/gt2kqurkdrv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ehwqpu.com/Article/details/gt2ykwmrulf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.andypj.xyz/Article/details/gt2dzznanhw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yj20258.top/Article/details/gt2rjfojtmh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.haohaochexian.top/Article/details/gt2etxwygwh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hnqzz.top/Article/details/gt2dtufxlxe.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sufxvd.cn/Article/details/gt2dujnqcin.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yvedp.cn/Article/details/gt2hfpqkylr.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yonumen.top/Article/details/gt2rfmnpnao.html

[D06] 数组长度
来源：http://dali.zhengqikj.top/Article/details/gt2wbxtqpjf.html

Py:   len(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lndsijdw.html

PHP:  count($arr);
来源：http://dali.hysaishi.cn/Article/details/gt2prdpegyz.html

JS:   arr.length
来源：http://dali.ehwqpu.com/Article/details/gt2npqnvwly.html

TS:   arr.length
来源：http://dali.ivvv.top/Article/details/gt2tzezbcbq.html

Java: list.size();
来源：http://dali.yuxming.cn/Article/details/gt2vlttxzgv.html

Go:   len(arr)
来源：http://dali.ybcxt.top/Article/details/gt2kyjcshiy.html

Ruby: arr.length; arr.size
来源：http://dali.tianlin.xyz/Article/details/gt2xkzlguvu.html

C#:   list.Count;
来源：http://dali.yueranfly.top/Article/details/gt2uhhwraoz.html

[D07] 切片 / 取子数组
来源：http://dali.nanxuanxn.top/Article/details/gt2zzdeydxj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.gaohongyu789.top/Article/details/gt2mrazyfao.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2coutqxud.html

JS:   arr.slice(1, 4);
来源：http://dali.hywenlv.cn/Article/details/gt2xskeltna.html

TS:   arr.slice(1, 4);
来源：http://dali.daxiang520.top/Article/details/gt2moudtcar.html

Java: list.subList(1, 4);
来源：http://dali.cdnleiting.top/Article/details/gt2esbyscps.html

Go:   arr[1:4]
来源：http://dali.daxiang520.top/Article/details/gt2jdxconoa.html

Ruby: arr[1, 3]
来源：http://dali.vqdsnc.cn/Article/details/gt2jldcnoka.html

C#:   list.GetRange(1, 3);
来源：http://dali.tanke756.top/Article/details/gt2pftqmmuf.html

[D08] 合并两个数组
来源：http://dali.yueranfly.top/Article/details/gt2nzyscpjb.html

Py:   a + b;  a.extend(b)
来源：http://dali.shuidangran.top/Article/details/gt2xfrxgflr.html

PHP:  array_merge($a, $b);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ttgizxhl.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xziqi.cn/Article/details/gt2odmigoud.html

TS:   [...a, ...b];
来源：http://dali.yj20258.top/Article/details/gt2omsppnqu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.0kj1m.cn/Article/details/gt2psyfcztq.html

Go:   append(a, b...)
来源：http://dali.ybcxt.top/Article/details/gt2izuuqccc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fqnbssas.html

C#:   a.Concat(b).ToList()
来源：http://dali.ydzc1.top/Article/details/gt2ohcfjfsb.html

[D09] 排序（升序）
来源：http://dali.zhongyouzk.top/Article/details/gt2zkimnjew.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hongshengwenyu.top/Article/details/gt2qoxvcbdy.html

PHP:  sort($arr);
来源：http://dali.tanke756.top/Article/details/gt2mhfinhyl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.guannengcc.top/Article/details/gt2okoujvdz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cheryme.top/Article/details/gt2rrdkbxmf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.daria6918.cn/Article/details/gt2yopkfrnn.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.9152youxi.cn/Article/details/gt2yrjqyqtg.html

Ruby: arr.sort
来源：http://dali.kuanghao11.cn/Article/details/gt2ahbhptoe.html

C#:   list.Sort();
来源：http://dali.jyoumei.cn/Article/details/gt2fuhpthcp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hnxiangtu.top/Article/details/gt2ffmfmdsj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.chenzaomai.com/Article/details/gt2mohetqvg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.bjfxy.top/Article/details/gt2qqyctrbw.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sweek.top/Article/details/gt2xcdazbrr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cheryme.top/Article/details/gt2xbkfpoab.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.nanxinkj.top/Article/details/gt2ljnnmxcy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yj20258.top/Article/details/gt2rgizifhl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.smart0.xyz/Article/details/gt2hxcpzayw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.nanxinkj.top/Article/details/gt2dodmepnh.html

[D11] 反转数组
来源：http://dali.316326.xyz/Article/details/gt2jgcapvvz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shuidangran.top/Article/details/gt2ebytkdvo.html

PHP:  array_reverse($arr);
来源：http://dali.kuanghao11.cn/Article/details/gt2eshzeeuk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xuetiantiany.cn/Article/details/gt2ghrnobek.html

TS:   [...arr].reverse();
来源：http://dali.aibaodan.cn/Article/details/gt2pmpebacs.html

Java: Collections.reverse(list);
来源：http://dali.ivvv.top/Article/details/gt2zebslldd.html

Go:   slices.Reverse(arr)
来源：http://dali.fengsongda.top/Article/details/gt2zyvxepxl.html

Ruby: arr.reverse
来源：http://dali.zhixingplan.top/Article/details/gt2zlfonedy.html

C#:   list.Reverse();
来源：http://dali.zdqjudy.top/Article/details/gt2znfhjeoh.html

[D12] 查找元素下标
来源：http://dali.hywenlv.cn/Article/details/gt2otbzjshe.html

Py:   arr.index(x);  x in arr
来源：http://dali.zycfv.cn/Article/details/gt2onlziluf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cdnleiting.top/Article/details/gt2gfrejtsh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shuidangran.top/Article/details/gt2fqysyjuu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jianghu66.top/Article/details/gt2qsswqzro.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sufxvd.cn/Article/details/gt2yeddpnom.html

Go:   slices.Index(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gt2nzzciyux.html

Ruby: arr.index(x)
来源：http://dali.tanke756.top/Article/details/gt2vxhubedz.html

C#:   list.IndexOf(x);
来源：http://dali.andypj.xyz/Article/details/gt2oruwranm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.guannengcc.top/Article/details/gt2xmtyidxx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jiagoushi.top/Article/details/gt2tyqzmfkf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.smart0.xyz/Article/details/gt2oivgvcox.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xylfe.cn/Article/details/gt2dkivswqs.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhongyouzk.top/Article/details/gt2qixlsxtl.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yangfankeji.com/Article/details/gt2veufrkby.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhongyouzk.top/Article/details/gt2mpcejcqo.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zdqjudy.top/Article/details/gt2svyialjy.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2qzjscwjq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shuidangran.top/Article/details/gt2undxayvw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhiwuduotai.top/Article/details/gt2kcosokjp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cdnleiting.top/Article/details/gt2tunjnadr.html

JS:   arr.map(x => x * 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vextvwwg.html

TS:   arr.map(x => x * 2)
来源：http://dali.ydzc1.top/Article/details/gt2ouatbimm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhixingplan.top/Article/details/gt2nnmtkxmo.html

Go:   // 手写循环
来源：http://dali.gotoacloud.top/Article/details/gt2soufyqfp.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.vqdsnc.cn/Article/details/gt2rmwybncs.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.birdmap.top/Article/details/gt2ezkjwwya.html

[D15] 去重
来源：http://dali.zhongyouzk.top/Article/details/gt2auxlewck.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2icwuifun.html

PHP:  array_unique($arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2xbmyvcim.html

JS:   [...new Set(arr)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2phxwhtvk.html

TS:   [...new Set(arr)]
来源：http://dali.cashguo.top/Article/details/gt2ftpomrrr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yonumen.top/Article/details/gt2iqbtcnmq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.redwolf501.top/Article/details/gt2ztqoldzf.html

Ruby: arr.uniq
来源：http://dali.mhx1999.top/Article/details/gt2dcutvzoq.html


<!-- 参考信息 -->