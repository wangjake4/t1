代发 wailian999

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gtnbeqslkq.html

JS:   a && b || !c
来源：http://dali.nwbrower.top/Article/details/gtyjgejclg.html

TS:   a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gtaieislck.html

Java: a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gtugtnbfmj.html

Go:   a && b || !c
来源：http://dali.pycfn.com/Article/details/gtjjccgdsy.html

Ruby: a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gttbfuyapt.html

C#:   a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gtfdpkuqdu.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlcjidnza.html

Py:   if not data: return
来源：http://dali.andypj.xyz/Article/details/gtbyorrrsq.html

PHP:  if (!$data) { return; }
来源：http://dali.kuanghao11.cn/Article/details/gtfhvbekkg.html

JS:   if (!data) return;
来源：http://dali.zycfv.cn/Article/details/gtkivxnsxu.html

TS:   if (!data) return;
来源：http://dali.9152youxi.cn/Article/details/gthbbxzfgl.html

Java: if (data == null) return;
来源：http://dali.hnqzz.top/Article/details/gtlnhhgxmw.html

Go:   if data == nil { return }
来源：http://dali.bjfxy.top/Article/details/gtijoplmyj.html

Ruby: return if data.nil?
来源：http://dali.guannengcc.top/Article/details/gtmsuuyjoo.html

C#:   if (data == null) return;
来源：http://dali.jqgufenzy.top/Article/details/gtohhlnxkc.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtscweukcv.html

C. 函数与作用域
来源：http://dali.xinyue.icu/Article/details/gtzowjdysh.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtghbonrym.html

[C01] 定义函数
来源：http://dali.shanyushiyangtech.top/Article/details/gttpigivwk.html

Py:   def add(a, b): return a + b
来源：http://dali.316326.xyz/Article/details/gtlgzodlax.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dashuyun.cn/Article/details/gtbxebiitg.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gtblmbetrb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtnswlbmkn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gtsrxpyggw.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.316326.xyz/Article/details/gtxvmzjkrv.html

Ruby: def add(a, b); a + b; end
来源：http://dali.quarkkingdee.top/Article/details/gtnxfskawn.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gtmmsrzldm.html

[C02] 默认参数
来源：http://dali.yj202588.top/Article/details/gtdoqmrxkc.html

Py:   def greet(name="World"): return name
来源：http://dali.wangdashe.top/Article/details/gtmjblpntk.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cqqwz.cn/Article/details/gtgthwzqwa.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ivvv.top/Article/details/gtuqfyxbci.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yangfankeji.com/Article/details/gtqznzogqt.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shangyingyoupin.top/Article/details/gtxovuqdiq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.svipenyu.cn/Article/details/gthnxzdjrs.html

Ruby: def greet(name = "World") = name
来源：http://dali.birdmap.top/Article/details/gtwopoxasc.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hongshengwenyu.top/Article/details/gtewexmsqs.html

[C03] 可变参数
来源：http://dali.jqgufenzy.top/Article/details/gtznphrnfo.html

Py:   def total(*args): return sum(args)
来源：http://dali.xziqi.cn/Article/details/gtraocplny.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yuanzhike.top/Article/details/gtqvjoylxj.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.nanxuanxn.top/Article/details/gtuuwtwpan.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhoulong.xyz/Article/details/gtffunbrhg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.gogol.net.cn/Article/details/gtbwsmofmy.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.bjfxy.top/Article/details/gtovstfhhn.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinqigufen.top/Article/details/gtjxyasjde.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.0kj1m.cn/Article/details/gtobkgagzz.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ehwqpu.com/Article/details/gtcvwayxal.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jqgfzy.top/Article/details/gtadpenapv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.tianlin.xyz/Article/details/gtxlkkgqog.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hysaishi.cn/Article/details/gttnygoiea.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yueranfly.top/Article/details/gttounrrui.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhengqikj.top/Article/details/gthrgsbtxg.html

Go:   // 无：用配置结构体参数
来源：http://dali.shuidangran.top/Article/details/gtjafjokut.html

Ruby: f(a: 1, b: 2)
来源：http://dali.andypj.xyz/Article/details/gtxigjqhdq.html

C#:   f(a: 1, b: 2)
来源：http://dali.yongpay.top/Article/details/gtoaxinnbl.html

[C05] 返回多个值
来源：http://dali.daria6918.cn/Article/details/gtpaiyhijk.html

Py:   return a, b
来源：http://dali.hfpthk.cn/Article/details/gtnxflrpmt.html

PHP:  return [$a, $b];
来源：http://dali.shzxlz.cn/Article/details/gtvuotokgr.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cqqwz.cn/Article/details/gtjvejusxe.html

TS:   return { a, b };
来源：http://dali.jinqigfzy.top/Article/details/gtifnwotml.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ybcxt.top/Article/details/gtsgwmxhnn.html

Go:   return a, b
来源：http://dali.gaohongyu789.top/Article/details/gtmoovulkf.html

Ruby: return a, b
来源：http://dali.haohaochexian.top/Article/details/gtvucztbix.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.tanke756.top/Article/details/gtfudiidkm.html

[C06] 匿名函数 / lambda
来源：http://dali.chenlongwang.top/Article/details/gttezxdkry.html

Py:   square = lambda x: x * x
来源：http://dali.meibo888.top/Article/details/gtkjtseyzm.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yj20258.top/Article/details/gtnnbdllzu.html

JS:   const square = x => x * x;
来源：http://dali.zhengqikj.top/Article/details/gtblcqsmll.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgjggybjc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ivvv.top/Article/details/gtcepczmga.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sufxvd.cn/Article/details/gttcnquxks.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shangyingyoupin.top/Article/details/gtcvslzfyo.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zdqjudy.top/Article/details/gtakqfyjzz.html

[C07] 把函数作为参数传入
来源：http://dali.hongshengwenyu.top/Article/details/gtxtgcdpfy.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.dashuyun.cn/Article/details/gtgapzzrgt.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhengqikj.top/Article/details/gtnzvoxqdh.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.daria6918.cn/Article/details/gtnvgtqfdu.html

TS:   arr.map(String)
来源：http://dali.zycfv.cn/Article/details/gtduoxmcye.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhixingplan.top/Article/details/gtdlrcercz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.daria6918.cn/Article/details/gtxuixxyid.html

Ruby: arr.map(&:upcase)
来源：http://dali.cashguo.top/Article/details/gterchjlhm.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xinyue.icu/Article/details/gtsekhfnhy.html

[C08] 闭包
来源：http://dali.cheryme.top/Article/details/gtkanhtnxb.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.sxryk.cn/Article/details/gttlmpjkos.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhoulong.xyz/Article/details/gtwkdzmjcn.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.sufxvd.cn/Article/details/gtzfyzypro.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yj202588.top/Article/details/gtimdpxdry.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.snrcjt.cn/Article/details/gtjwzkdqam.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.andypj.xyz/Article/details/gtbiyxqauf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yonumen.top/Article/details/gtlrsynyvt.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zdqjudy.top/Article/details/gtjiwyssqi.html

[C09] 递归
来源：http://dali.guannengcc.top/Article/details/gtwykqaokb.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yvedp.cn/Article/details/gtjzldgmvt.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yueranfly.top/Article/details/gtqbaopemh.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cashguo.top/Article/details/gtnosempvt.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhengqikj.top/Article/details/gtwtygaxse.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhiwuduotai.top/Article/details/gtjjxwjylo.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xziqi.cn/Article/details/gtpdgtpcwo.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yvedp.cn/Article/details/gtokuajgsl.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.wangdashe.top/Article/details/gtnsrzrrpd.html

[C10] 变量作用域
来源：http://dali.zhongyouzk.top/Article/details/gtyjnrdpbi.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.nwbrower.top/Article/details/gtsizlyook.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xylfe.cn/Article/details/gthgpfeggz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.c1oappe.top/Article/details/gtwvnttpzx.html

TS:   同 JS
来源：http://dali.gogol.net.cn/Article/details/gtgaaydlcz.html

Java: 方法内为块级作用域
来源：http://dali.redwolf501.top/Article/details/gtgctnuxyd.html

Go:   花括号块级作用域
来源：http://dali.yangfankeji.com/Article/details/gtfpugvpdu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shuidangran.top/Article/details/gtrbsgqlhg.html

C#:   块级作用域
来源：http://dali.yonumen.top/Article/details/gtcworimrq.html

[C11] 模块导入与导出
来源：http://dali.shuidangran.top/Article/details/gtnetrzmte.html

Py:   from module import func
来源：http://dali.bjfxy.top/Article/details/gtiwgnilva.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.chenlongwang.top/Article/details/gtxaxtzoeo.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.gzhubu.top/Article/details/gtmileltda.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hnqzz.top/Article/details/gthlpfwojo.html

Java: import java.util.List;
来源：http://dali.hysaishi.cn/Article/details/gtxchbdoay.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jqgufenzy.top/Article/details/gthawoelfe.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hammf.cn/Article/details/gthgmktxck.html

C#:   using System.Text;
来源：http://dali.hnqzz.top/Article/details/gtajchtrjd.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhiwuduotai.top/Article/details/gthmviebdl.html

Py:   (lambda: print("run"))()
来源：http://dali.kuanghao11.cn/Article/details/gttzviceus.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yanxiufei.cn/Article/details/gtfizagkts.html

JS:   (() => { console.log("run"); })();
来源：http://dali.mhx1999.top/Article/details/gtdskedsyc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.aibaodan.cn/Article/details/gtglgmoxkv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hnqzz.top/Article/details/gtbvuyauuo.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yvedp.cn/Article/details/gthydsvbkg.html

Ruby: -> { puts "run" }.call
来源：http://dali.yj20258.top/Article/details/gttztvunro.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gtixojerts.html

[C13] 类型声明 / 类型注解
来源：http://dali.wangdashe.top/Article/details/gtewvgiwli.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.gotoacloud.top/Article/details/gtpeiaejwn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuanzx.com/Article/details/gtotkrrgkv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hysaishi.cn/Article/details/gthawvaxox.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzrtyjuwm.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gtmdbvaqwv.html

Go:   func add(a, b int) int
来源：http://dali.cdnleiting.top/Article/details/gtyxivwgzi.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ehwqpu.com/Article/details/gtolwfsmks.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.aibaodan.cn/Article/details/gtygkzxicb.html

[C14] 泛型函数
来源：http://dali.chenzaomai.com/Article/details/gttftqqmkc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhoulong.xyz/Article/details/gtikottcns.html

PHP:  // 无泛型
来源：http://dali.cqqwz.cn/Article/details/gtztsoiuen.html

JS:   // 无泛型
来源：http://dali.jqgufenzy.top/Article/details/gthrgwhsha.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtntjdaisi.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.birdmap.top/Article/details/gtbhgtklfl.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.nwbrower.top/Article/details/gtanjvkbco.html

Ruby: # 无泛型
来源：http://dali.smart0.xyz/Article/details/gtarabxzke.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cheryme.top/Article/details/gtcdcxyiat.html

[C15] 解构 / 展开参数
来源：http://dali.ivvv.top/Article/details/gtblbkpbyz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.chenjidiqi.icu/Article/details/gtoxkgzmua.html

PHP:  [$a, $b] = $pair;
来源：http://dali.sweek.top/Article/details/gtbgoaehlw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.aibaodan.cn/Article/details/gtmpstsakg.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhongyouzk.top/Article/details/gtuvuqunwg.html

Java: // 无解构
来源：http://dali.jlsjyb.cn/Article/details/gtgxyymjrq.html

Go:   // 无解构
来源：http://dali.guannengcc.top/Article/details/gtrizyhegf.html

Ruby: a, b = pair
来源：http://dali.nanxuanxn.top/Article/details/gtxylzoybv.html

C#:   var (a, b) = pair;
来源：http://dali.fzhhl.top/Article/details/gtdfghcgdz.html

[C16] 函数 / 方法重载
来源：http://dali.cdnleiting.top/Article/details/gtvenmtdex.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.daria6918.cn/Article/details/gtusdgplpq.html

PHP:  // 无重载
来源：http://dali.cqqwz.cn/Article/details/gtjozbxkqa.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.svipenyu.cn/Article/details/gtcojaapez.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.bjfxy.top/Article/details/gtivxlzgxg.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.9152youxi.cn/Article/details/gtqshziorl.html

Go:   // 无重载：用不同函数名
来源：http://dali.zycfv.cn/Article/details/gtwgtbdwmh.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinqigfzy.top/Article/details/gtoalpqfdv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtlovhggph.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtnjmqvrtn.html

D. 数组 / 列表 / 集合
来源：http://dali.shzxlz.cn/Article/details/gthsqfhekp.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtslcsdhcg.html

[D01] 创建数组 / 列表
来源：http://dali.tian-w.cn/Article/details/gtwgvhqhdq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.feifeiyinyue.top/Article/details/gtadtwlcee.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.tian-w.cn/Article/details/gtuodgudrc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhoulong.xyz/Article/details/gtuwcoumlg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xuanzx.com/Article/details/gtshcmmmep.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.pycfn.com/Article/details/gtmcukxmax.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhongyouzk.top/Article/details/gtanyyyhew.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sysykeji.top/Article/details/gtfgwlgsug.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yueranfly.top/Article/details/gtlmcocjwu.html

[D02] 追加元素到末尾
来源：http://dali.iojbl.cn/Article/details/gtwkfngbqy.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.pengpengdd.cyou/Article/details/gtmsiqvylz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jiagoushi.top/Article/details/gttmehqsce.html

JS:   arr.push(4);
来源：http://dali.xinyue.icu/Article/details/gtobsskyet.html

TS:   arr.push(4);
来源：http://dali.tanke756.top/Article/details/gthmgodsly.html

Java: list.add(4);
来源：http://dali.gotoacloud.top/Article/details/gtzdbyomnw.html

Go:   arr = append(arr, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gtggbmsnad.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.meibo888.top/Article/details/gtjqvjoztg.html

C#:   list.Add(4);
来源：http://dali.daxiang520.top/Article/details/gtxdbmfkvp.html

[D03] 在指定位置插入元素
来源：http://dali.c1oappe.top/Article/details/gtbsectkgk.html

Py:   arr.insert(0, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtjlqrqbbk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtpakcsjcg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.pycfn.com/Article/details/gttbsrkece.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jqgufenzy.top/Article/details/gtlpuimwbh.html

Java: list.add(0, 0);
来源：http://dali.gaohongyu789.top/Article/details/gtiqiscfdo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdnpjsish.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.meibo888.top/Article/details/gtqqhsmibe.html

C#:   list.Insert(0, 0);
来源：http://dali.shzxlz.cn/Article/details/gtzcznaruu.html

[D04] 删除元素
来源：http://dali.hnxiangtu.top/Article/details/gtsemyccbv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ydzc1.top/Article/details/gtrgnbtgme.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtgckygtgr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gaohongyu789.top/Article/details/gtaiuhqboq.html

TS:   arr.splice(0, 1);
来源：http://dali.yonumen.top/Article/details/gtfznovunl.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cheryme.top/Article/details/gtzzguzaqa.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cqqwz.cn/Article/details/gtbcsrgtdb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.havefunace.top/Article/details/gtuhisevgp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sweek.top/Article/details/gtxrsngvjw.html

[D05] 访问与修改元素
来源：http://dali.shuidangran.top/Article/details/gtlledmfzh.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhoulong.xyz/Article/details/gtwhqswrdm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hfpthk.cn/Article/details/gtsjvlyzob.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jianghu66.top/Article/details/gtbkkvtnaa.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.iojbl.cn/Article/details/gtpnyeytyr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.9152youxi.cn/Article/details/gtcftyrnpz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hnqzz.top/Article/details/gtbdoyugbv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tianlin.xyz/Article/details/gttzjtycrd.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shuidangran.top/Article/details/gtgteektsr.html

[D06] 数组长度
来源：http://dali.gotoacloud.top/Article/details/gtngrqhleh.html

Py:   len(arr)
来源：http://dali.andypj.xyz/Article/details/gtvizpujdm.html

PHP:  count($arr);
来源：http://dali.yongpay.top/Article/details/gtlflwnhzt.html

JS:   arr.length
来源：http://dali.hysaishi.cn/Article/details/gtpfnqbtnn.html

TS:   arr.length
来源：http://dali.yj20258888.top/Article/details/gttjnfcwjg.html

Java: list.size();
来源：http://dali.gaohongyu789.top/Article/details/gtlyqeqgdz.html

Go:   len(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtkvgbvxov.html

Ruby: arr.length; arr.size
来源：http://dali.yonumen.top/Article/details/gtvlowzzsm.html

C#:   list.Count;
来源：http://dali.gotoacloud.top/Article/details/gtglfnymjv.html

[D07] 切片 / 取子数组
来源：http://dali.9152youxi.cn/Article/details/gtgdkxcbru.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yuanzhike.top/Article/details/gtoscvdxyn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ydzc1.top/Article/details/gtwxqrxidg.html

JS:   arr.slice(1, 4);
来源：http://dali.cucudq.cn/Article/details/gtyaesxrnh.html

TS:   arr.slice(1, 4);
来源：http://dali.svipenyu.cn/Article/details/gtormizykx.html

Java: list.subList(1, 4);
来源：http://dali.aizwys.cn/Article/details/gthtdygipw.html

Go:   arr[1:4]
来源：http://dali.gogol.net.cn/Article/details/gtsbmmrgex.html

Ruby: arr[1, 3]
来源：http://dali.iojbl.cn/Article/details/gtpkkzdeux.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinqigfzy.top/Article/details/gtxrsbttpn.html

[D08] 合并两个数组
来源：http://dali.hnxiangtu.top/Article/details/gtxorjkhsi.html

Py:   a + b;  a.extend(b)
来源：http://dali.dashuyun.cn/Article/details/gtjzabfgyo.html

PHP:  array_merge($a, $b);
来源：http://dali.zhoulong.xyz/Article/details/gtxaxvnjme.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yuxming.cn/Article/details/gtampafjjz.html

TS:   [...a, ...b];
来源：http://dali.yanxiufei.cn/Article/details/gtfzuuzpnk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ppjwa.cn/Article/details/gteqajsvih.html

Go:   append(a, b...)
来源：http://dali.yj20258888.top/Article/details/gtawfzjmrd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhoulong.xyz/Article/details/gtlqxofehn.html

C#:   a.Concat(b).ToList()
来源：http://dali.cheryme.top/Article/details/gtokxkzhwr.html

[D09] 排序（升序）
来源：http://dali.zdqjudy.top/Article/details/gtcbidounw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.0kj1m.cn/Article/details/gtijlrguqf.html

PHP:  sort($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtlezlyjqr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xuanzx.com/Article/details/gtcqizisay.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.aizwys.cn/Article/details/gtlvnplqyt.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.tanke756.top/Article/details/gtobjygzvc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yangfankeji.com/Article/details/gtfihvyiqy.html

Ruby: arr.sort
来源：http://dali.yvedp.cn/Article/details/gtjpqhetfl.html

C#:   list.Sort();
来源：http://dali.cashguo.top/Article/details/gtwbuduikc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinqigfzy.top/Article/details/gtazakcuei.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gtwgpkmlss.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhiwuduotai.top/Article/details/gtgojqdscy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fengsongda.top/Article/details/gttcsxvtwl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sysykeji.top/Article/details/gtnhezoojy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.redwolf501.top/Article/details/gtdbngrrbd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.nwbrower.top/Article/details/gttbvqonkw.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.dianchejie.cn/Article/details/gtrbsmtewo.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.meibo888.top/Article/details/gtgmzyvivx.html

[D11] 反转数组
来源：http://dali.cheryme.top/Article/details/gtnnygfkbl.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shzxlz.cn/Article/details/gtdizfrqkv.html

PHP:  array_reverse($arr);
来源：http://dali.dianchejie.cn/Article/details/gtnmesjcle.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.nanxuanxn.top/Article/details/gtfrnrsixz.html

TS:   [...arr].reverse();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwzuoxwim.html

Java: Collections.reverse(list);
来源：http://dali.hfpthk.cn/Article/details/gtnmaadmhd.html

Go:   slices.Reverse(arr)
来源：http://dali.hywenlv.cn/Article/details/gtcqwajlam.html

Ruby: arr.reverse
来源：http://dali.c1oappe.top/Article/details/gtszrvqjoi.html

C#:   list.Reverse();
来源：http://dali.smart0.xyz/Article/details/gtestzgtri.html

[D12] 查找元素下标
来源：http://dali.jyoumei.cn/Article/details/gtmogwucjo.html

Py:   arr.index(x);  x in arr
来源：http://dali.tian-w.cn/Article/details/gtxwffiygn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.sxryk.cn/Article/details/gtumkipkze.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sufxvd.cn/Article/details/gtfrvlpapg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xinyue.icu/Article/details/gtdszcecif.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.9152youxi.cn/Article/details/gtpnysjjym.html

Go:   slices.Index(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtgssdreec.html

Ruby: arr.index(x)
来源：http://dali.sweek.top/Article/details/gtzxqgzmdp.html

C#:   list.IndexOf(x);
来源：http://dali.ybcxt.top/Article/details/gtxidsoyqt.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xuetiantiany.cn/Article/details/gtargvxahh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sweek.top/Article/details/gtchueuwhs.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.fzhhl.top/Article/details/gttlsxmshp.html

JS:   arr.filter(x => x > 3)
来源：http://dali.wangshuangyany.cn/Article/details/gtahsskfhn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhongyouzk.top/Article/details/gtqbpsmofs.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.snrcjt.cn/Article/details/gtmopiqfar.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.dianchejie.cn/Article/details/gtininbkta.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yj20258888.top/Article/details/gtoxtjbrkt.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xuanzx.com/Article/details/gtdjwywldi.html

[D14] 映射转换（每个元素变形）
来源：http://dali.mhx1999.top/Article/details/gtdhylyagk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xuetiantiany.cn/Article/details/gtiitjqslv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.aibaodan.cn/Article/details/gtetoqtvrj.html

JS:   arr.map(x => x * 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtydglcxvw.html

TS:   arr.map(x => x * 2)
来源：http://dali.hfpthk.cn/Article/details/gtvsggknmp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sxryk.cn/Article/details/gtfohfzamv.html

Go:   // 手写循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtrscwewho.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.birdmap.top/Article/details/gtpegxavas.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgguremjc.html

[D15] 去重
来源：http://dali.sxryk.cn/Article/details/gtxmqrmnvw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhixingplan.top/Article/details/gtvttnjfus.html

PHP:  array_unique($arr);
来源：http://dali.gogol.net.cn/Article/details/gtsujjzczg.html

JS:   [...new Set(arr)]
来源：http://dali.svipenyu.cn/Article/details/gtujuthhdn.html

TS:   [...new Set(arr)]
来源：http://dali.kuanghao11.cn/Article/details/gtmshmdpcl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhixingplan.top/Article/details/gtgnvbejew.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ybcxt.top/Article/details/gtpbapqfxo.html

Ruby: arr.uniq
来源：http://dali.andypj.xyz/Article/details/gtaiwxbopm.html


<!-- 参考信息 -->