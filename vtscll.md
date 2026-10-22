代发 wailian999

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtudfsuqkf.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.chenlongwang.top/Article/details/gtyvvuuwaz.html

[B15] 布尔运算与取反
来源：http://dali.hongshengwenyu.top/Article/details/gtmvztfwon.html

Py:   a and b or not c
来源：http://dali.iojbl.cn/Article/details/gtyfxhkone.html

PHP:  $a && $b || !$c
来源：http://dali.aizwys.cn/Article/details/gtgkkvqqwm.html

JS:   a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gtrdzsawzo.html

TS:   a && b || !c
来源：http://dali.daxiang520.top/Article/details/gtfpnjrzwn.html

Java: a && b || !c
来源：http://dali.316326.xyz/Article/details/gtypnwgqhq.html

Go:   a && b || !c
来源：http://dali.smart0.xyz/Article/details/gtegvajkga.html

Ruby: a && b || !c
来源：http://dali.smart0.xyz/Article/details/gtzvsuxvnk.html

C#:   a && b || !c
来源：http://dali.yj202588.top/Article/details/gtztyxfeac.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ppjwa.cn/Article/details/gtolpfvgix.html

Py:   if not data: return
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvjtonrgc.html

PHP:  if (!$data) { return; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtchyuqsgx.html

JS:   if (!data) return;
来源：http://dali.ydzc1.top/Article/details/gtzqbkcpyw.html

TS:   if (!data) return;
来源：http://dali.dashuyun.cn/Article/details/gtzbrdmcdm.html

Java: if (data == null) return;
来源：http://dali.ybcxt.top/Article/details/gtygcoiycf.html

Go:   if data == nil { return }
来源：http://dali.yueranfly.top/Article/details/gtwfecxbwt.html

Ruby: return if data.nil?
来源：http://dali.tanke756.top/Article/details/gtbwgrdpbs.html

C#:   if (data == null) return;
来源：http://dali.quarkkingdee.top/Article/details/gtuclpiiwe.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtqkvekszc.html

C. 函数与作用域
来源：http://dali.jqgfzy.top/Article/details/gtavlqdovb.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gthkeiracy.html

[C01] 定义函数
来源：http://dali.wangdashe.top/Article/details/gtdiqfjkfo.html

Py:   def add(a, b): return a + b
来源：http://dali.xinyue.icu/Article/details/gtyrfrjwhx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gteitvadsq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gtfmzsyhkd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gtrrbiehpk.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtndwkmawg.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yonumen.top/Article/details/gtnrgkvcas.html

Ruby: def add(a, b); a + b; end
来源：http://dali.daxiang520.top/Article/details/gtmouazvmw.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gtlczvikic.html

[C02] 默认参数
来源：http://dali.fzhhl.top/Article/details/gttjdxdbho.html

Py:   def greet(name="World"): return name
来源：http://dali.jinqigufen.top/Article/details/gtqtoirrcl.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gotoacloud.top/Article/details/gtqlmbdber.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gtkwrctzrk.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtpflagogo.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbpkwyhfp.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.birdmap.top/Article/details/gtwfbxqszc.html

Ruby: def greet(name = "World") = name
来源：http://dali.vqdsnc.cn/Article/details/gtyjtavtek.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cheryme.top/Article/details/gtphasoqfa.html

[C03] 可变参数
来源：http://dali.zhoulong.xyz/Article/details/gtvgqmdzsd.html

Py:   def total(*args): return sum(args)
来源：http://dali.nanxinkj.top/Article/details/gtpqbnhnvv.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ybcxt.top/Article/details/gtyyjpztef.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hywenlv.cn/Article/details/gtdaeoqzzp.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jiagoushi.top/Article/details/gtluimxhgv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jlsjyb.cn/Article/details/gtcxtauadd.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.0kj1m.cn/Article/details/gtihivknfo.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.guowangkeji.top/Article/details/gtqdtxgmnb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.tian-w.cn/Article/details/gtwzdtewow.html

[C04] 命名参数 / 关键字参数
来源：http://dali.fzhhl.top/Article/details/gtzrvkvobd.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.nanxinkj.top/Article/details/gtppcazncj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.wangshuangyany.cn/Article/details/gtnlgihqcl.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cdnleiting.top/Article/details/gtjyrpfzts.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gtjzoyjwhl.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ppjwa.cn/Article/details/gtvnibfwhw.html

Go:   // 无：用配置结构体参数
来源：http://dali.jiagoushi.top/Article/details/gtyynswisu.html

Ruby: f(a: 1, b: 2)
来源：http://dali.redwolf501.top/Article/details/gtjmpflxnk.html

C#:   f(a: 1, b: 2)
来源：http://dali.svipenyu.cn/Article/details/gtsnzhniye.html

[C05] 返回多个值
来源：http://dali.zhoulong.xyz/Article/details/gtnmtcxmfm.html

Py:   return a, b
来源：http://dali.hnxiangtu.top/Article/details/gtzueuounn.html

PHP:  return [$a, $b];
来源：http://dali.chenjidiqi.icu/Article/details/gtltjvahmy.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.gzhubu.top/Article/details/gteqipblzm.html

TS:   return { a, b };
来源：http://dali.316326.xyz/Article/details/gtjqhavdnx.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cdnleiting.top/Article/details/gtbwfoudrc.html

Go:   return a, b
来源：http://dali.jinghuilouyu.cn/Article/details/gtwbfmrkux.html

Ruby: return a, b
来源：http://dali.wangshuangyany.cn/Article/details/gtwmsyqfyb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xuanzx.com/Article/details/gtbkvasusm.html

[C06] 匿名函数 / lambda
来源：http://dali.c1oappe.top/Article/details/gtpbrktpcq.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gtdwbnglqi.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.sysykeji.top/Article/details/gtlszhwsfs.html

JS:   const square = x => x * x;
来源：http://dali.jinqigufen.top/Article/details/gtquljdafc.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.feifeiyinyue.top/Article/details/gtsjicxtmd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yongpay.top/Article/details/gtyyekkfnp.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sufxvd.cn/Article/details/gtvpoawwrm.html

Ruby: square = ->(x) { x * x }
来源：http://dali.smart0.xyz/Article/details/gtsfsvebes.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ybcxt.top/Article/details/gtzkfkvrom.html

[C07] 把函数作为参数传入
来源：http://dali.jlsjyb.cn/Article/details/gtlrtjkqhx.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hysaishi.cn/Article/details/gtsfwhjadz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.0kj1m.cn/Article/details/gtwayzuvuh.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.aibaodan.cn/Article/details/gtrlviinxi.html

TS:   arr.map(String)
来源：http://dali.birdmap.top/Article/details/gtqknlmmdz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xuanzx.com/Article/details/gtwxrulqbv.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yueranfly.top/Article/details/gtszcymdju.html

Ruby: arr.map(&:upcase)
来源：http://dali.nanxuanxn.top/Article/details/gtnbsxszys.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.redwolf501.top/Article/details/gtlgmxbvyo.html

[C08] 闭包
来源：http://dali.jinghuilouyu.cn/Article/details/gtafmzfwrs.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.sweek.top/Article/details/gtubdwlunv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtavaiujto.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtomnpbxnm.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.meibo888.top/Article/details/gtpiuhqnqr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.dashuyun.cn/Article/details/gtrzzswiht.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zycfv.cn/Article/details/gtcotgyohe.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ydzc1.top/Article/details/gtopnqsudi.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.snrcjt.cn/Article/details/gtvbklzash.html

[C09] 递归
来源：http://dali.bjfxy.top/Article/details/gthcpadqgb.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.kuanghao11.cn/Article/details/gtlnjipfrb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gaohongyu789.top/Article/details/gtojdjdprz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnsfmmeow.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xylfe.cn/Article/details/gtrgfwrfbu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.daria6918.cn/Article/details/gtaihqeemu.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hysaishi.cn/Article/details/gtlmqtdztc.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.sxryk.cn/Article/details/gtbdjhoidp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.guowangkeji.top/Article/details/gtjlobiuby.html

[C10] 变量作用域
来源：http://dali.birdmap.top/Article/details/gtvuhuryru.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ybcxt.top/Article/details/gtzytfltrn.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.tanke756.top/Article/details/gtqrsfsgjs.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jqgufenzy.top/Article/details/gtlwnxsvny.html

TS:   同 JS
来源：http://dali.ivvv.top/Article/details/gtrratasii.html

Java: 方法内为块级作用域
来源：http://dali.yangfankeji.com/Article/details/gtkdcmzyoe.html

Go:   花括号块级作用域
来源：http://dali.pycfn.com/Article/details/gtovhivaqo.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.iojbl.cn/Article/details/gtmjnntgus.html

C#:   块级作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gtikvilcbb.html

[C11] 模块导入与导出
来源：http://dali.yongpay.top/Article/details/gttyqgckdi.html

Py:   from module import func
来源：http://dali.yuxming.cn/Article/details/gtockacoyp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.sufxvd.cn/Article/details/gtatlsaqfn.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.tianlin.xyz/Article/details/gtswqcyhbh.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jyoumei.cn/Article/details/gtgqaibkuq.html

Java: import java.util.List;
来源：http://dali.zhongyouzk.top/Article/details/gtcjcnrihx.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.nanxinkj.top/Article/details/gthdzfvzzg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hongshengwenyu.top/Article/details/gtcitmqclp.html

C#:   using System.Text;
来源：http://dali.yuanzhike.top/Article/details/gttsnknnld.html

[C12] 立即执行函数 IIFE
来源：http://dali.vqdsnc.cn/Article/details/gtqfexpplh.html

Py:   (lambda: print("run"))()
来源：http://dali.zhengqikj.top/Article/details/gtykoezeqt.html

PHP:  (function () { echo "run"; })();
来源：http://dali.pengpengdd.cyou/Article/details/gtzqidkord.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shuidangran.top/Article/details/gtrpqqpwfw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hysaishi.cn/Article/details/gtzjramwfe.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.wangdashe.top/Article/details/gtbdrrdmvu.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzjwoglxh.html

Ruby: -> { puts "run" }.call
来源：http://dali.yongpay.top/Article/details/gtseclgahh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.fengsongda.top/Article/details/gtvhyoudzn.html

[C13] 类型声明 / 类型注解
来源：http://dali.hfpthk.cn/Article/details/gtvmiahjnk.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgsyeeqyy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtharpzywm.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cucudq.cn/Article/details/gtbztxhkuo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj202588.top/Article/details/gtqcjzbmaz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gtrzkmzwut.html

Go:   func add(a, b int) int
来源：http://dali.smart0.xyz/Article/details/gtwulxvjrj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shuidangran.top/Article/details/gtayvkqbjn.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jianghu66.top/Article/details/gtpavzeqyi.html

[C14] 泛型函数
来源：http://dali.yanxiufei.cn/Article/details/gtvgqkwzvz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.kuanghao11.cn/Article/details/gtihbkrosg.html

PHP:  // 无泛型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyvtlrwfm.html

JS:   // 无泛型
来源：http://dali.yuxming.cn/Article/details/gtjqrxrlpl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jyoumei.cn/Article/details/gthooxbfzp.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jyoumei.cn/Article/details/gtnehqmkyr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.chenlongwang.top/Article/details/gthllotral.html

Ruby: # 无泛型
来源：http://dali.hammf.cn/Article/details/gtbstahidh.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.smart0.xyz/Article/details/gtkqbdoseg.html

[C15] 解构 / 展开参数
来源：http://dali.redwolf501.top/Article/details/gtfotzwxxs.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hongshengwenyu.top/Article/details/gtbkzfwpgu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gzhubu.top/Article/details/gtuxabejrl.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yueranfly.top/Article/details/gtkrfumpid.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.chenlongwang.top/Article/details/gtotycplpz.html

Java: // 无解构
来源：http://dali.jiagoushi.top/Article/details/gtdbdscvhk.html

Go:   // 无解构
来源：http://dali.tian-w.cn/Article/details/gthrywjsip.html

Ruby: a, b = pair
来源：http://dali.sysykeji.top/Article/details/gtnojaqkak.html

C#:   var (a, b) = pair;
来源：http://dali.ywan-chungtsiang.top/Article/details/gttqpsbrwk.html

[C16] 函数 / 方法重载
来源：http://dali.xziqi.cn/Article/details/gtmeohmuyz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cqqwz.cn/Article/details/gtntjwwhem.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gtyqwinyad.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.fzhhl.top/Article/details/gtglvimomz.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.nwbrower.top/Article/details/gtnlxdthkm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoxkjagkb.html

Go:   // 无重载：用不同函数名
来源：http://dali.tian-w.cn/Article/details/gtvimadxnw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hammf.cn/Article/details/gtzzioagah.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.dashuyun.cn/Article/details/gtbhuzmldq.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtwrnwnxlx.html

D. 数组 / 列表 / 集合
来源：http://dali.shzxlz.cn/Article/details/gtdwfsfcyx.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtbdlrwuys.html

[D01] 创建数组 / 列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtauwjtvfb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yangfankeji.com/Article/details/gtsyorivrz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shuidangran.top/Article/details/gtmfouwoym.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hysaishi.cn/Article/details/gtjnxvjcaa.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.nanxuanxn.top/Article/details/gtcolaqvet.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.mhx1999.top/Article/details/gtxsijmyyl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gzhubu.top/Article/details/gtazrmydkj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cheryme.top/Article/details/gtihmrwhqg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.tanke756.top/Article/details/gtfomnfqkv.html

[D02] 追加元素到末尾
来源：http://dali.svipenyu.cn/Article/details/gtdiyjfqag.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtesaqhcmb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxteypmnx.html

JS:   arr.push(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtguwhzcrk.html

TS:   arr.push(4);
来源：http://dali.wangshuangyany.cn/Article/details/gtzdiegxke.html

Java: list.add(4);
来源：http://dali.shangyingyoupin.top/Article/details/gttwzoqbnf.html

Go:   arr = append(arr, 4)
来源：http://dali.jianghu66.top/Article/details/gtdmxeadww.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gotoacloud.top/Article/details/gtwsboxleh.html

C#:   list.Add(4);
来源：http://dali.zhongyouzk.top/Article/details/gtdisisnca.html

[D03] 在指定位置插入元素
来源：http://dali.jyoumei.cn/Article/details/gtwknljelm.html

Py:   arr.insert(0, 0)
来源：http://dali.haohaochexian.top/Article/details/gtfptmuxec.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jyoumei.cn/Article/details/gtxloebwhf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.meibo888.top/Article/details/gtzsdvcabw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.fzhhl.top/Article/details/gtlaijgvqh.html

Java: list.add(0, 0);
来源：http://dali.jianghu66.top/Article/details/gtwfuziuit.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cucudq.cn/Article/details/gtgaakzdgq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ybcxt.top/Article/details/gtvpouxshn.html

C#:   list.Insert(0, 0);
来源：http://dali.tianlin.xyz/Article/details/gtfrsqwabh.html

[D04] 删除元素
来源：http://dali.yvedp.cn/Article/details/gtnbedizmi.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.aizwys.cn/Article/details/gtxpcnsaiu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xziqi.cn/Article/details/gtofzydiim.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sysykeji.top/Article/details/gtvwvbezbw.html

TS:   arr.splice(0, 1);
来源：http://dali.hnqzz.top/Article/details/gtydmiwtln.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jinqigfzy.top/Article/details/gtihxjcdmq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.vqdsnc.cn/Article/details/gtwhexgckh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhengqikj.top/Article/details/gtbtfslxub.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.birdmap.top/Article/details/gtrtbyqkpu.html

[D05] 访问与修改元素
来源：http://dali.jinqigfzy.top/Article/details/gtrmepmxrs.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenlongwang.top/Article/details/gtkevsntdv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xylfe.cn/Article/details/gtpagmggeq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.fengsongda.top/Article/details/gtleygtpeh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.tianlin.xyz/Article/details/gtmteoiszr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yangfankeji.com/Article/details/gtbjkbvktz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cheryme.top/Article/details/gttfxzsimw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hywenlv.cn/Article/details/gtchsxfbis.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yvedp.cn/Article/details/gtcsbtbzvw.html

[D06] 数组长度
来源：http://dali.gaohongyu789.top/Article/details/gtfdddzwci.html

Py:   len(arr)
来源：http://dali.hnqzz.top/Article/details/gtujzbxard.html

PHP:  count($arr);
来源：http://dali.svipenyu.cn/Article/details/gtbqnrlrxi.html

JS:   arr.length
来源：http://dali.kuanghao11.cn/Article/details/gtvxhekizi.html

TS:   arr.length
来源：http://dali.yj20258888.top/Article/details/gthvhuvajf.html

Java: list.size();
来源：http://dali.ybcxt.top/Article/details/gtucfaordp.html

Go:   len(arr)
来源：http://dali.ydzc1.top/Article/details/gtomvhhsly.html

Ruby: arr.length; arr.size
来源：http://dali.chenzaomai.com/Article/details/gtrphbenhv.html

C#:   list.Count;
来源：http://dali.feifeiyinyue.top/Article/details/gtlnhfsdmg.html

[D07] 切片 / 取子数组
来源：http://dali.kuanghao11.cn/Article/details/gtvxbrfkpg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hnxiangtu.top/Article/details/gtcirhxdby.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.gaohongyu789.top/Article/details/gtnpwbrvnq.html

JS:   arr.slice(1, 4);
来源：http://dali.pycfn.com/Article/details/gtfljsviwy.html

TS:   arr.slice(1, 4);
来源：http://dali.haohaochexian.top/Article/details/gtqrmhyylj.html

Java: list.subList(1, 4);
来源：http://dali.havefunace.top/Article/details/gtrgpjsrha.html

Go:   arr[1:4]
来源：http://dali.cqqwz.cn/Article/details/gtcehkvwjk.html

Ruby: arr[1, 3]
来源：http://dali.fengsongda.top/Article/details/gtljyvqllt.html

C#:   list.GetRange(1, 3);
来源：http://dali.ppjwa.cn/Article/details/gtpvdejxhq.html

[D08] 合并两个数组
来源：http://dali.cheryme.top/Article/details/gtdvizeyto.html

Py:   a + b;  a.extend(b)
来源：http://dali.bjfxy.top/Article/details/gtxathrrtg.html

PHP:  array_merge($a, $b);
来源：http://dali.cdnleiting.top/Article/details/gtahaeyccv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xuanzx.com/Article/details/gttluhgyuh.html

TS:   [...a, ...b];
来源：http://dali.svipenyu.cn/Article/details/gtltxcimsd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.nanxinkj.top/Article/details/gtjmznsizs.html

Go:   append(a, b...)
来源：http://dali.haohaochexian.top/Article/details/gtmxhdnmrz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gtjpncisxi.html

C#:   a.Concat(b).ToList()
来源：http://dali.nwbrower.top/Article/details/gtsskpettd.html

[D09] 排序（升序）
来源：http://dali.dashuyun.cn/Article/details/gthvmnuqvl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cucudq.cn/Article/details/gtynilmyxc.html

PHP:  sort($arr);
来源：http://dali.sysykeji.top/Article/details/gtfqvhqbvw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.guannengcc.top/Article/details/gtvycimhaw.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.0kj1m.cn/Article/details/gtgfybxqzq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sweek.top/Article/details/gttggterxy.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cqqwz.cn/Article/details/gtsrgfowkj.html

Ruby: arr.sort
来源：http://dali.zhengqikj.top/Article/details/gtrcmuhrmi.html

C#:   list.Sort();
来源：http://dali.zhoulong.xyz/Article/details/gtkmbqpqmd.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.bjfxy.top/Article/details/gtozjlaejy.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.bjfxy.top/Article/details/gtzlrxkbxy.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenlongwang.top/Article/details/gtcdrrnser.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258.top/Article/details/gtgvhantrc.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnxiangtu.top/Article/details/gtqvzxfrbh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.quarkkingdee.top/Article/details/gtwmuaopyk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.snrcjt.cn/Article/details/gtzlgahwse.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gaohongyu789.top/Article/details/gtxibvyamy.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpoxwssim.html

[D11] 反转数组
来源：http://dali.chenjidiqi.icu/Article/details/gtrryduyao.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.birdmap.top/Article/details/gthrwdbfmc.html

PHP:  array_reverse($arr);
来源：http://dali.birdmap.top/Article/details/gtfhtfdlqg.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhixingplan.top/Article/details/gtqmknnlhr.html

TS:   [...arr].reverse();
来源：http://dali.hysaishi.cn/Article/details/gtnvrnxwlq.html

Java: Collections.reverse(list);
来源：http://dali.sysykeji.top/Article/details/gtcqggyyls.html

Go:   slices.Reverse(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwqfeegyi.html

Ruby: arr.reverse
来源：http://dali.yonumen.top/Article/details/gtsllmdumv.html

C#:   list.Reverse();
来源：http://dali.shanyushiyangtech.top/Article/details/gtcjaujpub.html

[D12] 查找元素下标
来源：http://dali.jinqigfzy.top/Article/details/gtbigvqpnq.html

Py:   arr.index(x);  x in arr
来源：http://dali.dashuyun.cn/Article/details/gtftnvvhhi.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.mhx1999.top/Article/details/gtzauzhggh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tianlin.xyz/Article/details/gtthsnmfkh.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhixingplan.top/Article/details/gtvmmgsmuq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.guowangkeji.top/Article/details/gtmirorrvo.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtehlqepnb.html

Ruby: arr.index(x)
来源：http://dali.andypj.xyz/Article/details/gteqwwpsqk.html

C#:   list.IndexOf(x);
来源：http://dali.yueranfly.top/Article/details/gtqgefmgxc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cdnleiting.top/Article/details/gtzarjfdrf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtranzyqre.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhoulong.xyz/Article/details/gtojsojvci.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhongyouzk.top/Article/details/gtlphrntkl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xinyue.icu/Article/details/gtahlrcodd.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cdnleiting.top/Article/details/gtjtwoqjsu.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nanxuanxn.top/Article/details/gtxlvcfept.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhixingplan.top/Article/details/gtsgxyqdab.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtuoaelwpa.html

[D14] 映射转换（每个元素变形）
来源：http://dali.fengsongda.top/Article/details/gtraejbgjd.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shuidangran.top/Article/details/gtiszjuzjx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtsxxjlzbj.html

JS:   arr.map(x => x * 2)
来源：http://dali.daxiang520.top/Article/details/gtuigsmczp.html

TS:   arr.map(x => x * 2)
来源：http://dali.shzxlz.cn/Article/details/gtlglwmzdo.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.mhx1999.top/Article/details/gtsonuvuxy.html

Go:   // 手写循环
来源：http://dali.yuanzhike.top/Article/details/gtxbgnenmi.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yueranfly.top/Article/details/gtyzwliwjq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yonumen.top/Article/details/gtzzxkvnom.html

[D15] 去重
来源：http://dali.gogol.net.cn/Article/details/gtvodosujx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.guowangkeji.top/Article/details/gtkhttdufc.html

PHP:  array_unique($arr);
来源：http://dali.hfpthk.cn/Article/details/gtdowauqai.html

JS:   [...new Set(arr)]
来源：http://dali.shuidangran.top/Article/details/gtqjggisrz.html


<!-- 参考信息 -->