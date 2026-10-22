代发 wailian999

PHP:  $a && $b || !$c
来源：http://dali.cashguo.top/Article/details/gt2cpgizjme.html

JS:   a && b || !c
来源：http://dali.cucudq.cn/Article/details/gt2ilrbbepm.html

TS:   a && b || !c
来源：http://dali.yvedp.cn/Article/details/gt2tcfyxhhw.html

Java: a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gt2dvxaemui.html

Go:   a && b || !c
来源：http://dali.yonumen.top/Article/details/gt2eniesrvp.html

Ruby: a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gt2dqytsbzy.html

C#:   a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gt2lkbebjhr.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.wangshuangyany.cn/Article/details/gt2zjhbkrwm.html

Py:   if not data: return
来源：http://dali.zhoulong.xyz/Article/details/gt2snelbrde.html

PHP:  if (!$data) { return; }
来源：http://dali.xuanzx.com/Article/details/gt2lxlzqwcw.html

JS:   if (!data) return;
来源：http://dali.tian-w.cn/Article/details/gt2jrisnewu.html

TS:   if (!data) return;
来源：http://dali.fengsongda.top/Article/details/gt2hsizbbcq.html

Java: if (data == null) return;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ncswtvbw.html

Go:   if data == nil { return }
来源：http://dali.sxryk.cn/Article/details/gt2jmpsebpz.html

Ruby: return if data.nil?
来源：http://dali.yuanzhike.top/Article/details/gt2dgfemvhq.html

C#:   if (data == null) return;
来源：http://dali.jyoumei.cn/Article/details/gt2tfzdwdcv.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2gehugcno.html

C. 函数与作用域
来源：http://dali.tian-w.cn/Article/details/gt2zlmnznrm.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2qdgaepjh.html

[C01] 定义函数
来源：http://dali.zycfv.cn/Article/details/gt2zwhptupw.html

Py:   def add(a, b): return a + b
来源：http://dali.pycfn.com/Article/details/gt2rbmcqhxm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuanzx.com/Article/details/gt2obetqoje.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gt2aljwuzqt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wwgjptbn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gt2yvlnznmq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.nwbrower.top/Article/details/gt2zanggmml.html

Ruby: def add(a, b); a + b; end
来源：http://dali.nanxinkj.top/Article/details/gt2tyhddajq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gt2dvqtwnuw.html

[C02] 默认参数
来源：http://dali.nanxinkj.top/Article/details/gt2ilxureqi.html

Py:   def greet(name="World"): return name
来源：http://dali.pycfn.com/Article/details/gt2zkoaigby.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2suiqwzvx.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2erjroilz.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ehwqpu.com/Article/details/gt2vpzrjskw.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cashguo.top/Article/details/gt2xzlpgqql.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yuxming.cn/Article/details/gt2qnqogwlb.html

Ruby: def greet(name = "World") = name
来源：http://dali.mhx1999.top/Article/details/gt2bbmifzgb.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.fzhhl.top/Article/details/gt2ghqmdkfa.html

[C03] 可变参数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kabozdii.html

Py:   def total(*args): return sum(args)
来源：http://dali.nanxinkj.top/Article/details/gt2pkgzznne.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hywenlv.cn/Article/details/gt2yhncasnf.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258888.top/Article/details/gt2czxzryat.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cqqwz.cn/Article/details/gt2xbhdxnzo.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zycfv.cn/Article/details/gt2yxotgmew.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.guowangkeji.top/Article/details/gt2uztfbotc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jqgfzy.top/Article/details/gt2kliyenla.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.daria6918.cn/Article/details/gt2wjnbyowc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.daria6918.cn/Article/details/gt2vdyywecu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zbufgrkm.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xziqi.cn/Article/details/gt2gdiosowa.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yuxming.cn/Article/details/gt2psowindn.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shzxlz.cn/Article/details/gt2priubbwk.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ivvv.top/Article/details/gt2timqhmwu.html

Go:   // 无：用配置结构体参数
来源：http://dali.sufxvd.cn/Article/details/gt2oymvhpkb.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yj20258888.top/Article/details/gt2cgwojxpn.html

C#:   f(a: 1, b: 2)
来源：http://dali.guannengcc.top/Article/details/gt2feephnbp.html

[C05] 返回多个值
来源：http://dali.ydzc1.top/Article/details/gt2ivmllogd.html

Py:   return a, b
来源：http://dali.zycfv.cn/Article/details/gt2kavatdmq.html

PHP:  return [$a, $b];
来源：http://dali.jiagoushi.top/Article/details/gt2nppkygem.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xylfe.cn/Article/details/gt2cmvassit.html

TS:   return { a, b };
来源：http://dali.xuetiantiany.cn/Article/details/gt2ejksxziu.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pyuhnlkz.html

Go:   return a, b
来源：http://dali.pycfn.com/Article/details/gt2xbfscdqm.html

Ruby: return a, b
来源：http://dali.yvedp.cn/Article/details/gt2jmbogewh.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.guowangkeji.top/Article/details/gt2icsuncnz.html

[C06] 匿名函数 / lambda
来源：http://dali.chenzaomai.com/Article/details/gt2wnlsgeii.html

Py:   square = lambda x: x * x
来源：http://dali.sufxvd.cn/Article/details/gt2gvvbnfzt.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.0kj1m.cn/Article/details/gt2zzwjstdg.html

JS:   const square = x => x * x;
来源：http://dali.shzxlz.cn/Article/details/gt2dozuajcg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.svipenyu.cn/Article/details/gt2rhntelkb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.sysykeji.top/Article/details/gt2uozdccqf.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.tian-w.cn/Article/details/gt2akojoafe.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ehwqpu.com/Article/details/gt2tinpatoo.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hysaishi.cn/Article/details/gt2jwefssco.html

[C07] 把函数作为参数传入
来源：http://dali.meibo888.top/Article/details/gt2thooqxmv.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhixingplan.top/Article/details/gt2rzxcwhzw.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.shuidangran.top/Article/details/gt2ayfpwafu.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rfzhgmmd.html

TS:   arr.map(String)
来源：http://dali.jiagoushi.top/Article/details/gt2ukylsmbp.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2ufsyierx.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zdqjudy.top/Article/details/gt2fuznkffl.html

Ruby: arr.map(&:upcase)
来源：http://dali.cucudq.cn/Article/details/gt2zjzajnib.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xylfe.cn/Article/details/gt2qpxabcqx.html

[C08] 闭包
来源：http://dali.snrcjt.cn/Article/details/gt2vwkflccz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.andypj.xyz/Article/details/gt2halqepnr.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yangfankeji.com/Article/details/gt2nttcpheu.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yueranfly.top/Article/details/gt2fcnfcsnx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.guannengcc.top/Article/details/gt2atwiwvup.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hnqzz.top/Article/details/gt2gjolnggj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yj20258888.top/Article/details/gt2sewhvdbw.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ydzc1.top/Article/details/gt2kdxvmkyp.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ybcxt.top/Article/details/gt2okpaakqw.html

[C09] 递归
来源：http://dali.nwbrower.top/Article/details/gt2xooqxucr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jyoumei.cn/Article/details/gt2dgwwqios.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uclcerki.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hammf.cn/Article/details/gt2chabmjbd.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tian-w.cn/Article/details/gt2ryhbgojl.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yanxiufei.cn/Article/details/gt2xpjspudm.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sxryk.cn/Article/details/gt2naenmxys.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhixingplan.top/Article/details/gt2mpipxhvj.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.feifeiyinyue.top/Article/details/gt2sbfuihfy.html

[C10] 变量作用域
来源：http://dali.sysykeji.top/Article/details/gt2cylrfodr.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.kuanghao11.cn/Article/details/gt2dzbflunn.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cheryme.top/Article/details/gt2ysiurvwo.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hammf.cn/Article/details/gt2ivydmzdj.html

TS:   同 JS
来源：http://dali.svipenyu.cn/Article/details/gt2rwgjkxdg.html

Java: 方法内为块级作用域
来源：http://dali.ybcxt.top/Article/details/gt2yeioiqov.html

Go:   花括号块级作用域
来源：http://dali.yj202588.top/Article/details/gt2rswmhtwf.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yvedp.cn/Article/details/gt2qhojonzj.html

C#:   块级作用域
来源：http://dali.ydzc1.top/Article/details/gt2qxnczhxs.html

[C11] 模块导入与导出
来源：http://dali.feifeiyinyue.top/Article/details/gt2ahzdzjsh.html

Py:   from module import func
来源：http://dali.feifeiyinyue.top/Article/details/gt2mmnqvjey.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.nanxuanxn.top/Article/details/gt2ovgedehf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.guowangkeji.top/Article/details/gt2gcemtvgu.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hywenlv.cn/Article/details/gt2oadpqddp.html

Java: import java.util.List;
来源：http://dali.nanxuanxn.top/Article/details/gt2filbmrdw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.vqdsnc.cn/Article/details/gt2sxsefjst.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gotoacloud.top/Article/details/gt2olyxupqa.html

C#:   using System.Text;
来源：http://dali.yj20258.top/Article/details/gt2thgdgdkd.html

[C12] 立即执行函数 IIFE
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cyfgsnec.html

Py:   (lambda: print("run"))()
来源：http://dali.havefunace.top/Article/details/gt2hlmtogwz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xinyue.icu/Article/details/gt2eijucbtj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.redwolf501.top/Article/details/gt2mgdgncch.html

TS:   (() => { console.log("run"); })();
来源：http://dali.tanke756.top/Article/details/gt2utfhirgz.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yketrdgx.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jiagoushi.top/Article/details/gt2ugjbcsfp.html

Ruby: -> { puts "run" }.call
来源：http://dali.wangshuangyany.cn/Article/details/gt2fskcexmd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.0kj1m.cn/Article/details/gt2avrjmufc.html

[C13] 类型声明 / 类型注解
来源：http://dali.redwolf501.top/Article/details/gt2ijtmujmp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wxelqpfc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxuanxn.top/Article/details/gt2hylurixa.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uxeymskn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sweek.top/Article/details/gt2xxekwsag.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2glaxcvav.html

Go:   func add(a, b int) int
来源：http://dali.nanxinkj.top/Article/details/gt2jusafjup.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yanxiufei.cn/Article/details/gt2xzqjwxyq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.iojbl.cn/Article/details/gt2hzstvciu.html

[C14] 泛型函数
来源：http://dali.sxryk.cn/Article/details/gt2kipmtwno.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cdnleiting.top/Article/details/gt2cvnwvetz.html

PHP:  // 无泛型
来源：http://dali.meibo888.top/Article/details/gt2qngbjtdk.html

JS:   // 无泛型
来源：http://dali.yueranfly.top/Article/details/gt2yekqgamw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ehwqpu.com/Article/details/gt2btygpino.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xuanzx.com/Article/details/gt2xxewcrvc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cdnleiting.top/Article/details/gt2ygvgylic.html

Ruby: # 无泛型
来源：http://dali.yj20258.top/Article/details/gt2seikkdgz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.tian-w.cn/Article/details/gt2nvfekphh.html

[C15] 解构 / 展开参数
来源：http://dali.zhongyouzk.top/Article/details/gt2jushonvq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhtxfmp.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xuanzx.com/Article/details/gt2replcimu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.birdmap.top/Article/details/gt2smprngqp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.dianchejie.cn/Article/details/gt2xfrrgqqt.html

Java: // 无解构
来源：http://dali.hywenlv.cn/Article/details/gt2ocindlcd.html

Go:   // 无解构
来源：http://dali.yangfankeji.com/Article/details/gt2pboklyxb.html

Ruby: a, b = pair
来源：http://dali.daria6918.cn/Article/details/gt2lzgajimv.html

C#:   var (a, b) = pair;
来源：http://dali.aibaodan.cn/Article/details/gt2aexdrluq.html

[C16] 函数 / 方法重载
来源：http://dali.shangyingyoupin.top/Article/details/gt2fbhclzsm.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shuidangran.top/Article/details/gt2fcjpqdna.html

PHP:  // 无重载
来源：http://dali.vqdsnc.cn/Article/details/gt2vmlvdajj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.daxiang520.top/Article/details/gt2twqpdupo.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.pycfn.com/Article/details/gt2dmidvpcx.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.chenzaomai.com/Article/details/gt2sozugzvp.html

Go:   // 无重载：用不同函数名
来源：http://dali.cheryme.top/Article/details/gt2sgnlgagl.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cheryme.top/Article/details/gt2hvpattyq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2tzuqekab.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2fyeryukq.html

D. 数组 / 列表 / 集合
来源：http://dali.quarkkingdee.top/Article/details/gt2fwaxibto.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2shwogbgq.html

[D01] 创建数组 / 列表
来源：http://dali.svipenyu.cn/Article/details/gt2yhwuosoz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ppjwa.cn/Article/details/gt2sbcrtbtn.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.dianchejie.cn/Article/details/gt2qznsdqkd.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qcudgknx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.gaohongyu789.top/Article/details/gt2flkwytsu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.c1oappe.top/Article/details/gt2tvzvxcgp.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhengqikj.top/Article/details/gt2wrcuaxnu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xziqi.cn/Article/details/gt2riynecct.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.0kj1m.cn/Article/details/gt2fuysujlj.html

[D02] 追加元素到末尾
来源：http://dali.yj20258.top/Article/details/gt2nxwkklvr.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yueranfly.top/Article/details/gt2fbftlamb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.nanxinkj.top/Article/details/gt2iijptaqb.html

JS:   arr.push(4);
来源：http://dali.jiagoushi.top/Article/details/gt2ddqeobhm.html

TS:   arr.push(4);
来源：http://dali.zhengqikj.top/Article/details/gt2evcxrknq.html

Java: list.add(4);
来源：http://dali.shuidangran.top/Article/details/gt2oxudmddm.html

Go:   arr = append(arr, 4)
来源：http://dali.jlsjyb.cn/Article/details/gt2zrkawpdz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhoulong.xyz/Article/details/gt2mhjuxxbw.html

C#:   list.Add(4);
来源：http://dali.shuidangran.top/Article/details/gt2tiynlrvc.html

[D03] 在指定位置插入元素
来源：http://dali.yonumen.top/Article/details/gt2anlqilnd.html

Py:   arr.insert(0, 0)
来源：http://dali.chenzaomai.com/Article/details/gt2agtzntzp.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.fengsongda.top/Article/details/gt2uwdocuez.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xinyue.icu/Article/details/gt2dlwmityz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shzxlz.cn/Article/details/gt2kywkufku.html

Java: list.add(0, 0);
来源：http://dali.yonumen.top/Article/details/gt2xlcceflj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hysaishi.cn/Article/details/gt2fiyrdchf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yanxiufei.cn/Article/details/gt2hadvbnkg.html

C#:   list.Insert(0, 0);
来源：http://dali.pycfn.com/Article/details/gt2irbndglp.html

[D04] 删除元素
来源：http://dali.jyoumei.cn/Article/details/gt2emnxunou.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cheryme.top/Article/details/gt2jmzgdxhz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yueranfly.top/Article/details/gt2zxapvpqf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xuetiantiany.cn/Article/details/gt2spsemhbl.html

TS:   arr.splice(0, 1);
来源：http://dali.jqgfzy.top/Article/details/gt2cionvvrz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ehwqpu.com/Article/details/gt2ddjwaaxw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yongpay.top/Article/details/gt2tnkdgdct.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.fzhhl.top/Article/details/gt2inzrfrwj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.wangshuangyany.cn/Article/details/gt2qkqbqlyp.html

[D05] 访问与修改元素
来源：http://dali.zhengqikj.top/Article/details/gt2ilhgkrqc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yanxiufei.cn/Article/details/gt2hfbgpyox.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ydzc1.top/Article/details/gt2jkbtwlhq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jqgufenzy.top/Article/details/gt2saehhzds.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.nanxinkj.top/Article/details/gt2ewlrujrd.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinqigufen.top/Article/details/gt2npxtusdl.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ivvv.top/Article/details/gt2ezaswvxd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yuxming.cn/Article/details/gt2ttusbbfj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jianghu66.top/Article/details/gt2ywcsysuf.html

[D06] 数组长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ewhswdkj.html

Py:   len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2okmmtogq.html

PHP:  count($arr);
来源：http://dali.yj202588.top/Article/details/gt2xgomgkli.html

JS:   arr.length
来源：http://dali.9152youxi.cn/Article/details/gt2bhghspme.html

TS:   arr.length
来源：http://dali.zhiwuduotai.top/Article/details/gt2chqlqrse.html

Java: list.size();
来源：http://dali.mhx1999.top/Article/details/gt2rosbezun.html

Go:   len(arr)
来源：http://dali.ybcxt.top/Article/details/gt2bpqwqmdp.html

Ruby: arr.length; arr.size
来源：http://dali.sweek.top/Article/details/gt2foawamus.html

C#:   list.Count;
来源：http://dali.vqdsnc.cn/Article/details/gt2zfsvqsuf.html

[D07] 切片 / 取子数组
来源：http://dali.0kj1m.cn/Article/details/gt2aqiewvrr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.316326.xyz/Article/details/gt2utdfhsnn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.redwolf501.top/Article/details/gt2hgvzptpb.html

JS:   arr.slice(1, 4);
来源：http://dali.andypj.xyz/Article/details/gt2gkrxhrch.html

TS:   arr.slice(1, 4);
来源：http://dali.sweek.top/Article/details/gt2asxsxfho.html

Java: list.subList(1, 4);
来源：http://dali.zhoulong.xyz/Article/details/gt2nuktrqoc.html

Go:   arr[1:4]
来源：http://dali.jiagoushi.top/Article/details/gt2sidwxust.html

Ruby: arr[1, 3]
来源：http://dali.yuanzhike.top/Article/details/gt2qkuootse.html

C#:   list.GetRange(1, 3);
来源：http://dali.wangshuangyany.cn/Article/details/gt2lwybszvw.html

[D08] 合并两个数组
来源：http://dali.svipenyu.cn/Article/details/gt2lyagneip.html

Py:   a + b;  a.extend(b)
来源：http://dali.mhx1999.top/Article/details/gt2ecqufvnv.html

PHP:  array_merge($a, $b);
来源：http://dali.cdnleiting.top/Article/details/gt2lkwhpalo.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.redwolf501.top/Article/details/gt2fhtlkotw.html

TS:   [...a, ...b];
来源：http://dali.havefunace.top/Article/details/gt2dthgduje.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yvedp.cn/Article/details/gt2nkwbqhmv.html

Go:   append(a, b...)
来源：http://dali.jinqigfzy.top/Article/details/gt2lwrcsfke.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhengqikj.top/Article/details/gt2djfonfeo.html

C#:   a.Concat(b).ToList()
来源：http://dali.yvedp.cn/Article/details/gt2alniubtx.html

[D09] 排序（升序）
来源：http://dali.nwbrower.top/Article/details/gt2sksviush.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sweek.top/Article/details/gt2mlqsfhhw.html

PHP:  sort($arr);
来源：http://dali.jinqigufen.top/Article/details/gt2vgjcoutm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhiwuduotai.top/Article/details/gt2kaxmljqo.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.0kj1m.cn/Article/details/gt2okfimnwf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhengqikj.top/Article/details/gt2kowlhhvn.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2iomqyask.html

Ruby: arr.sort
来源：http://dali.ppjwa.cn/Article/details/gt2cdorivbl.html

C#:   list.Sort();
来源：http://dali.ybcxt.top/Article/details/gt2yypfwmnn.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.nwbrower.top/Article/details/gt2ppufdnzt.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.nanxuanxn.top/Article/details/gt2uthhnmef.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.bjfxy.top/Article/details/gt2odeulgcu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hfpthk.cn/Article/details/gt2bjwpkexv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ppjwa.cn/Article/details/gt2aegtyirw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.snrcjt.cn/Article/details/gt2wvowcmvh.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yangfankeji.com/Article/details/gt2tpdgnyai.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.tianlin.xyz/Article/details/gt2cnuvhxhh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.dianchejie.cn/Article/details/gt2rbmxlhvj.html

[D11] 反转数组
来源：http://dali.sufxvd.cn/Article/details/gt2srmeeywr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sysykeji.top/Article/details/gt2mbmyxzll.html

PHP:  array_reverse($arr);
来源：http://dali.kuanghao11.cn/Article/details/gt2mtaenllf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nlydgqja.html

TS:   [...arr].reverse();
来源：http://dali.yueranfly.top/Article/details/gt2iwnaqsys.html

Java: Collections.reverse(list);
来源：http://dali.iojbl.cn/Article/details/gt2axguscew.html

Go:   slices.Reverse(arr)
来源：http://dali.yongpay.top/Article/details/gt2hhkovfts.html

Ruby: arr.reverse
来源：http://dali.hywenlv.cn/Article/details/gt2llhatiyt.html

C#:   list.Reverse();
来源：http://dali.sufxvd.cn/Article/details/gt2ruunxsqa.html

[D12] 查找元素下标
来源：http://dali.yj20258.top/Article/details/gt2ahkybzph.html

Py:   arr.index(x);  x in arr
来源：http://dali.fzhhl.top/Article/details/gt2zctnpjsy.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xinyue.icu/Article/details/gt2firqmhol.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yongpay.top/Article/details/gt2gpaqtfde.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenzaomai.com/Article/details/gt2ljxnfhyz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yueranfly.top/Article/details/gt2evhmgitf.html

Go:   slices.Index(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gt2ovldxnfv.html

Ruby: arr.index(x)
来源：http://dali.yongpay.top/Article/details/gt2qjppxuhk.html

C#:   list.IndexOf(x);
来源：http://dali.jiagoushi.top/Article/details/gt2xuvpolyj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nofctwrm.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.gotoacloud.top/Article/details/gt2yihiywlr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.guannengcc.top/Article/details/gt2ncpjhvhp.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinqigfzy.top/Article/details/gt2qoucbnju.html

TS:   arr.filter(x => x > 3)
来源：http://dali.meibo888.top/Article/details/gt2iytavhbs.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pnspdtwb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yonumen.top/Article/details/gt2wktbcvwb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sufxvd.cn/Article/details/gt2oygrehco.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.meibo888.top/Article/details/gt2tuhbdyqc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.quarkkingdee.top/Article/details/gt2ovqhmnrs.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cheryme.top/Article/details/gt2idozuxlp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hywenlv.cn/Article/details/gt2ostltryi.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ceuiuydy.html

TS:   arr.map(x => x * 2)
来源：http://dali.xuanzx.com/Article/details/gt2exxnmgni.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ohgyukjg.html

Go:   // 手写循环
来源：http://dali.guowangkeji.top/Article/details/gt2cqnlghga.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.tanke756.top/Article/details/gt2kxdzcemt.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinqigufen.top/Article/details/gt2kzaeagjk.html

[D15] 去重
来源：http://dali.cdnleiting.top/Article/details/gt2jlibpkxp.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yuxming.cn/Article/details/gt2lpdgxqbp.html

PHP:  array_unique($arr);
来源：http://dali.nwbrower.top/Article/details/gt2jkigkast.html

JS:   [...new Set(arr)]
来源：http://dali.zdqjudy.top/Article/details/gt2lhutcyrc.html

TS:   [...new Set(arr)]
来源：http://dali.gzhubu.top/Article/details/gt2zuunrdbk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.smart0.xyz/Article/details/gt2rrxevhqo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hysaishi.cn/Article/details/gt2jvxruets.html

Ruby: arr.uniq
来源：http://dali.quarkkingdee.top/Article/details/gt2zpgetqsp.html


<!-- 参考信息 -->