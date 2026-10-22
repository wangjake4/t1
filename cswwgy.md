代发 wailian999

C#:   x is int or double or decimal
来源：http://dali.ehwqpu.com/Article/details/gtgfolrdqt.html

[B14] 判断值是否在集合内
来源：http://dali.jlsjyb.cn/Article/details/gtzqoqcitf.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.dashuyun.cn/Article/details/gtokyjqvim.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yanxiufei.cn/Article/details/gtutknhyjv.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.fzhhl.top/Article/details/gtarbaoqga.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jianghu66.top/Article/details/gtovqwqemz.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ppjwa.cn/Article/details/gtpdduzifx.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.sweek.top/Article/details/gtvezanbjs.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xinyue.icu/Article/details/gtrmgtbuld.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.snrcjt.cn/Article/details/gteueseuce.html

[B15] 布尔运算与取反
来源：http://dali.smart0.xyz/Article/details/gtwjpscbqo.html

Py:   a and b or not c
来源：http://dali.jianghu66.top/Article/details/gtpmbucdck.html

PHP:  $a && $b || !$c
来源：http://dali.kuanghao11.cn/Article/details/gtgxgtwnpd.html

JS:   a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gthdbxvzps.html

TS:   a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gtejmiuhwy.html

Java: a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtiftnyeya.html

Go:   a && b || !c
来源：http://dali.andypj.xyz/Article/details/gtwutiiccb.html

Ruby: a && b || !c
来源：http://dali.hammf.cn/Article/details/gtfzwquntx.html

C#:   a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gtuayvnsfr.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yongpay.top/Article/details/gteodindhn.html

Py:   if not data: return
来源：http://dali.jyoumei.cn/Article/details/gtlbpbbtby.html

PHP:  if (!$data) { return; }
来源：http://dali.jiagoushi.top/Article/details/gtevjgihnc.html

JS:   if (!data) return;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnkwzemfe.html

TS:   if (!data) return;
来源：http://dali.dashuyun.cn/Article/details/gthjiyrmna.html

Java: if (data == null) return;
来源：http://dali.dianchejie.cn/Article/details/gtpgstafmb.html

Go:   if data == nil { return }
来源：http://dali.chenlongwang.top/Article/details/gtunbjuhbj.html

Ruby: return if data.nil?
来源：http://dali.zhixingplan.top/Article/details/gtrkymeuut.html

C#:   if (data == null) return;
来源：http://dali.aizwys.cn/Article/details/gtponosfum.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gterxjzwjs.html

C. 函数与作用域
来源：http://dali.hysaishi.cn/Article/details/gtjnzqobmz.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtlifcqnnf.html

[C01] 定义函数
来源：http://dali.wangshuangyany.cn/Article/details/gtcfmhwefy.html

Py:   def add(a, b): return a + b
来源：http://dali.316326.xyz/Article/details/gtnynzfwwb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtncqvigtt.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtfsewefzo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gtueboenka.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gtqxfaalyf.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.sxryk.cn/Article/details/gtuoidwtnl.html

Ruby: def add(a, b); a + b; end
来源：http://dali.nwbrower.top/Article/details/gtkdiakkfw.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gtqvbaadkt.html

[C02] 默认参数
来源：http://dali.hysaishi.cn/Article/details/gtlqsidora.html

Py:   def greet(name="World"): return name
来源：http://dali.wangshuangyany.cn/Article/details/gtubpxytxz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gzhubu.top/Article/details/gtzrnjtcyk.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yj20258.top/Article/details/gttptjgsas.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.birdmap.top/Article/details/gtuuzbgzlb.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zycfv.cn/Article/details/gtumtmhair.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xziqi.cn/Article/details/gtyidliudf.html

Ruby: def greet(name = "World") = name
来源：http://dali.fengsongda.top/Article/details/gtxexqirmi.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cucudq.cn/Article/details/gturqqugri.html

[C03] 可变参数
来源：http://dali.nwbrower.top/Article/details/gtyreywvgn.html

Py:   def total(*args): return sum(args)
来源：http://dali.snrcjt.cn/Article/details/gtlonydlmg.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.dashuyun.cn/Article/details/gtysebwuxh.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shzxlz.cn/Article/details/gtxwjkyqxf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xuanzx.com/Article/details/gteelkzdzl.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yvedp.cn/Article/details/gtldrwraer.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.sysykeji.top/Article/details/gtwtewlsjb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhongyouzk.top/Article/details/gtmluxfyvv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ywan-chungtsiang.top/Article/details/gthhywxsmw.html

[C04] 命名参数 / 关键字参数
来源：http://dali.dashuyun.cn/Article/details/gtdfyfylrs.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sxryk.cn/Article/details/gtichsikje.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hywenlv.cn/Article/details/gtsvdopihn.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.9152youxi.cn/Article/details/gteuafhbqa.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jqgufenzy.top/Article/details/gtyixvomvd.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.nwbrower.top/Article/details/gtchcxmstf.html

Go:   // 无：用配置结构体参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmlsqvucv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cdnleiting.top/Article/details/gtombykfcd.html

C#:   f(a: 1, b: 2)
来源：http://dali.nwbrower.top/Article/details/gthjcagbhw.html

[C05] 返回多个值
来源：http://dali.zhixingplan.top/Article/details/gtzhghmdey.html

Py:   return a, b
来源：http://dali.yangfankeji.com/Article/details/gtsoselcch.html

PHP:  return [$a, $b];
来源：http://dali.jlsjyb.cn/Article/details/gtcvdetnpp.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yonumen.top/Article/details/gtjinhlpsq.html

TS:   return { a, b };
来源：http://dali.daria6918.cn/Article/details/gtqeugdjsf.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shuidangran.top/Article/details/gtxjfruhto.html

Go:   return a, b
来源：http://dali.yueranfly.top/Article/details/gtgqsebtdc.html

Ruby: return a, b
来源：http://dali.yuanzhike.top/Article/details/gtrutrjemc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ybcxt.top/Article/details/gthjxvthjo.html

[C06] 匿名函数 / lambda
来源：http://dali.xinyue.icu/Article/details/gtvpgbhgxa.html

Py:   square = lambda x: x * x
来源：http://dali.wangdashe.top/Article/details/gtiozcewai.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.c1oappe.top/Article/details/gtagbfubwv.html

JS:   const square = x => x * x;
来源：http://dali.yj202588.top/Article/details/gtkbvlgbuk.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.guannengcc.top/Article/details/gtllldokgs.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ehwqpu.com/Article/details/gtlxhpdiop.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shangyingyoupin.top/Article/details/gtdkcpywjy.html

Ruby: square = ->(x) { x * x }
来源：http://dali.aizwys.cn/Article/details/gtoldthiwx.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cucudq.cn/Article/details/gtwuvcogqp.html

[C07] 把函数作为参数传入
来源：http://dali.hfpthk.cn/Article/details/gtnkliaclh.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zdqjudy.top/Article/details/gtsphsdgai.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sxryk.cn/Article/details/gtaamjutfy.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.316326.xyz/Article/details/gtlgaxuser.html

TS:   arr.map(String)
来源：http://dali.jianghu66.top/Article/details/gtuxilnlmw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.iojbl.cn/Article/details/gtoseavhac.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jinghuilouyu.cn/Article/details/gtviiwyzwb.html

Ruby: arr.map(&:upcase)
来源：http://dali.aizwys.cn/Article/details/gtzznmglou.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.pycfn.com/Article/details/gthvuzvohg.html

[C08] 闭包
来源：http://dali.iojbl.cn/Article/details/gtfdeugrgb.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.daxiang520.top/Article/details/gtigmxcugs.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hongshengwenyu.top/Article/details/gthlqqfwha.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hongshengwenyu.top/Article/details/gtemtlezjz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jlsjyb.cn/Article/details/gtfnstdgsk.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.mhx1999.top/Article/details/gtwgvndsxw.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhongyouzk.top/Article/details/gtkwwfiryl.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shangyingyoupin.top/Article/details/gtcldwitav.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jyoumei.cn/Article/details/gtbdaorygt.html

[C09] 递归
来源：http://dali.zdqjudy.top/Article/details/gtukxwpevm.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.meibo888.top/Article/details/gtycypbkbt.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ivvv.top/Article/details/gtixgjfrem.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ydzc1.top/Article/details/gtqneovyrm.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hongshengwenyu.top/Article/details/gtxibhhxos.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.c1oappe.top/Article/details/gtqqsgphlc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.guannengcc.top/Article/details/gtpcyttoxd.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gtwsdfkija.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.chenjidiqi.icu/Article/details/gtzvjfoubx.html

[C10] 变量作用域
来源：http://dali.nanxinkj.top/Article/details/gtsjhgxert.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xinyue.icu/Article/details/gtshrmnjgk.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.mhx1999.top/Article/details/gtbvgxmztn.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.redwolf501.top/Article/details/gtuqxuhbyh.html

TS:   同 JS
来源：http://dali.chenzaomai.com/Article/details/gtvtryllbh.html

Java: 方法内为块级作用域
来源：http://dali.shangyingyoupin.top/Article/details/gthcwpkmqu.html

Go:   花括号块级作用域
来源：http://dali.c1oappe.top/Article/details/gtgntqoipu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.sufxvd.cn/Article/details/gtuqvesijv.html

C#:   块级作用域
来源：http://dali.nwbrower.top/Article/details/gtcxtchkbm.html

[C11] 模块导入与导出
来源：http://dali.ydzc1.top/Article/details/gtevqxneqq.html

Py:   from module import func
来源：http://dali.yj20258.top/Article/details/gtjqoppqkq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhoulong.xyz/Article/details/gtrzqbhdeo.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.quarkkingdee.top/Article/details/gthnikpjas.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yueranfly.top/Article/details/gtxopxvgpr.html

Java: import java.util.List;
来源：http://dali.wangshuangyany.cn/Article/details/gtzlqtchhe.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.gaohongyu789.top/Article/details/gtmpwpehsy.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhongyouzk.top/Article/details/gtypxgovoa.html

C#:   using System.Text;
来源：http://dali.sufxvd.cn/Article/details/gtpqlgwywx.html

[C12] 立即执行函数 IIFE
来源：http://dali.svipenyu.cn/Article/details/gthmxudasy.html

Py:   (lambda: print("run"))()
来源：http://dali.yueranfly.top/Article/details/gtuajpokfi.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xylfe.cn/Article/details/gtsgpfzbpc.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gttqihkecw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.nwbrower.top/Article/details/gtyoxgmjgo.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.9152youxi.cn/Article/details/gtzjoopvzx.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yuanzhike.top/Article/details/gtyueaabkh.html

Ruby: -> { puts "run" }.call
来源：http://dali.chenjidiqi.icu/Article/details/gtowqstuqe.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cheryme.top/Article/details/gtajpvpfxm.html

[C13] 类型声明 / 类型注解
来源：http://dali.meibo888.top/Article/details/gtwernuwwz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xinyue.icu/Article/details/gtschgzieh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hfpthk.cn/Article/details/gtueqebipv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cashguo.top/Article/details/gtiykrdttr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gtcldafsee.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hammf.cn/Article/details/gtfdlkruxo.html

Go:   func add(a, b int) int
来源：http://dali.chenlongwang.top/Article/details/gthjnadpbs.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sufxvd.cn/Article/details/gtjbsiojtc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.pycfn.com/Article/details/gtjbssnrsk.html

[C14] 泛型函数
来源：http://dali.cdnleiting.top/Article/details/gtviqgkxsd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhengqikj.top/Article/details/gtffegcsqr.html

PHP:  // 无泛型
来源：http://dali.ydzc1.top/Article/details/gtllibzxgn.html

JS:   // 无泛型
来源：http://dali.chenzaomai.com/Article/details/gtthwzcore.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ppjwa.cn/Article/details/gthrlovyxe.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cdnleiting.top/Article/details/gtacsiqlbb.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hongshengwenyu.top/Article/details/gttamiajjx.html

Ruby: # 无泛型
来源：http://dali.chenjidiqi.icu/Article/details/gtenonwhad.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuufvrnoj.html

[C15] 解构 / 展开参数
来源：http://dali.quarkkingdee.top/Article/details/gtwlnyofib.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yonumen.top/Article/details/gtmdfvjqwv.html

PHP:  [$a, $b] = $pair;
来源：http://dali.dashuyun.cn/Article/details/gttgqlkwbr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.fengsongda.top/Article/details/gtfhdszkjs.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtsuoxzarm.html

Java: // 无解构
来源：http://dali.cucudq.cn/Article/details/gtluyuocfz.html

Go:   // 无解构
来源：http://dali.zhoulong.xyz/Article/details/gtbfmvgwap.html

Ruby: a, b = pair
来源：http://dali.c1oappe.top/Article/details/gtnxtodrzw.html

C#:   var (a, b) = pair;
来源：http://dali.xuetiantiany.cn/Article/details/gttyztjnnd.html

[C16] 函数 / 方法重载
来源：http://dali.redwolf501.top/Article/details/gtbnejiead.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.tian-w.cn/Article/details/gtjmzcnxaf.html

PHP:  // 无重载
来源：http://dali.yj20258.top/Article/details/gtyvermmyg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.pycfn.com/Article/details/gtqxnabokb.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yuanzhike.top/Article/details/gtpcmwdvft.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sufxvd.cn/Article/details/gtvezqqwdj.html

Go:   // 无重载：用不同函数名
来源：http://dali.nanxuanxn.top/Article/details/gtdgjbrogg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.tian-w.cn/Article/details/gtlyvrtbwe.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cashguo.top/Article/details/gtlbzfjhzi.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtbriucrgc.html

D. 数组 / 列表 / 集合
来源：http://dali.tianlin.xyz/Article/details/gtzaxxnisg.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtuzthwifu.html

[D01] 创建数组 / 列表
来源：http://dali.jianghu66.top/Article/details/gtgshspcug.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinqigufen.top/Article/details/gthjsdmdvy.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.svipenyu.cn/Article/details/gtbppgocps.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.mhx1999.top/Article/details/gtxsuicyvu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.dianchejie.cn/Article/details/gtiiaglbyf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.havefunace.top/Article/details/gtpsmjgcnv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ybcxt.top/Article/details/gthflktizc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.tianlin.xyz/Article/details/gtdnfmamzj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hongshengwenyu.top/Article/details/gtqnjxejsa.html

[D02] 追加元素到末尾
来源：http://dali.316326.xyz/Article/details/gtalybqdmk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinqigufen.top/Article/details/gtlfxavtnc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.daria6918.cn/Article/details/gtmkaclcbs.html

JS:   arr.push(4);
来源：http://dali.ybcxt.top/Article/details/gtdvmgerdu.html

TS:   arr.push(4);
来源：http://dali.316326.xyz/Article/details/gtwfuxcsre.html

Java: list.add(4);
来源：http://dali.xziqi.cn/Article/details/gtcfaoxeoa.html

Go:   arr = append(arr, 4)
来源：http://dali.gogol.net.cn/Article/details/gtbgedfyey.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.andypj.xyz/Article/details/gtwtwfgnrj.html

C#:   list.Add(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gthikmkpuc.html

[D03] 在指定位置插入元素
来源：http://dali.shzxlz.cn/Article/details/gtgprrhfgk.html

Py:   arr.insert(0, 0)
来源：http://dali.yuxming.cn/Article/details/gtxxfwbhjg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlkdaichi.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.birdmap.top/Article/details/gtsanwspbv.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.snrcjt.cn/Article/details/gtkafsnsxc.html

Java: list.add(0, 0);
来源：http://dali.haohaochexian.top/Article/details/gtifxjjeor.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.birdmap.top/Article/details/gtbqihrefh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.birdmap.top/Article/details/gtwvkybxnw.html

C#:   list.Insert(0, 0);
来源：http://dali.ppjwa.cn/Article/details/gtfsbzlrrc.html

[D04] 删除元素
来源：http://dali.bjfxy.top/Article/details/gtwszjskhk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.guannengcc.top/Article/details/gtviiznthj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.snrcjt.cn/Article/details/gtmxuwqnmn.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gtodtanwqe.html

TS:   arr.splice(0, 1);
来源：http://dali.chenzaomai.com/Article/details/gtpdftkiwb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtkkziqrqh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.havefunace.top/Article/details/gtwoxfzldb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ydzc1.top/Article/details/gtecvrviko.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yongpay.top/Article/details/gtmrroizso.html

[D05] 访问与修改元素
来源：http://dali.shangyingyoupin.top/Article/details/gtmlpmltrj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ppjwa.cn/Article/details/gtxuvhaqpb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzwqapceu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jlsjyb.cn/Article/details/gtdaaqaapa.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.dashuyun.cn/Article/details/gtkhubknwj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shanyushiyangtech.top/Article/details/gtufdbihxk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.fengsongda.top/Article/details/gttoesbxzf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.feifeiyinyue.top/Article/details/gtjcunmfep.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hywenlv.cn/Article/details/gtwmmjpbkn.html

[D06] 数组长度
来源：http://dali.guannengcc.top/Article/details/gtlkyijkve.html

Py:   len(arr)
来源：http://dali.0kj1m.cn/Article/details/gtbshthdlu.html

PHP:  count($arr);
来源：http://dali.nwbrower.top/Article/details/gtlqmwbspn.html

JS:   arr.length
来源：http://dali.wangdashe.top/Article/details/gtbchtddhv.html

TS:   arr.length
来源：http://dali.ybcxt.top/Article/details/gttllwmcjl.html

Java: list.size();
来源：http://dali.daxiang520.top/Article/details/gtfbxygxyg.html

Go:   len(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkqcuzkmw.html

Ruby: arr.length; arr.size
来源：http://dali.tanke756.top/Article/details/gtmxcawkrq.html

C#:   list.Count;
来源：http://dali.iojbl.cn/Article/details/gtspxgthkq.html

[D07] 切片 / 取子数组
来源：http://dali.jinqigfzy.top/Article/details/gtdztqaumk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.redwolf501.top/Article/details/gtywomoxew.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cashguo.top/Article/details/gtibeadtda.html

JS:   arr.slice(1, 4);
来源：http://dali.cashguo.top/Article/details/gtteoauqgj.html

TS:   arr.slice(1, 4);
来源：http://dali.jiagoushi.top/Article/details/gtpwuhlpoq.html

Java: list.subList(1, 4);
来源：http://dali.svipenyu.cn/Article/details/gtkalbdove.html

Go:   arr[1:4]
来源：http://dali.bjfxy.top/Article/details/gtfxoovauz.html

Ruby: arr[1, 3]
来源：http://dali.jinghuilouyu.cn/Article/details/gthhrrzfvx.html

C#:   list.GetRange(1, 3);
来源：http://dali.jqgufenzy.top/Article/details/gtrnjvgylx.html

[D08] 合并两个数组
来源：http://dali.c1oappe.top/Article/details/gtkejuwlve.html

Py:   a + b;  a.extend(b)
来源：http://dali.hfpthk.cn/Article/details/gtgokyfcoi.html

PHP:  array_merge($a, $b);
来源：http://dali.ehwqpu.com/Article/details/gtfwuynwct.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jlsjyb.cn/Article/details/gtispqtaay.html

TS:   [...a, ...b];
来源：http://dali.fzhhl.top/Article/details/gtqqhwgpjr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhoulong.xyz/Article/details/gtfvamiigj.html

Go:   append(a, b...)
来源：http://dali.shzxlz.cn/Article/details/gtwxbimfda.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwgpjlutq.html

C#:   a.Concat(b).ToList()
来源：http://dali.zycfv.cn/Article/details/gtkkxxdzlx.html

[D09] 排序（升序）
来源：http://dali.yanxiufei.cn/Article/details/gtmgynkiyx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmcspwjfl.html

PHP:  sort($arr);
来源：http://dali.chenzaomai.com/Article/details/gtjxvhkwlw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zycfv.cn/Article/details/gtndawbwbi.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.fengsongda.top/Article/details/gtwkzbjekq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ywan-chungtsiang.top/Article/details/gteqhyadub.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.c1oappe.top/Article/details/gtccjgzlsj.html

Ruby: arr.sort
来源：http://dali.svipenyu.cn/Article/details/gtdlttpmjb.html

C#:   list.Sort();
来源：http://dali.dashuyun.cn/Article/details/gthyntdkph.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jyoumei.cn/Article/details/gtkcahjmgj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yj20258.top/Article/details/gtqfdnrizf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcxnaucst.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ybcxt.top/Article/details/gtqiouxiuj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ppjwa.cn/Article/details/gtivmgiuxm.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.guowangkeji.top/Article/details/gtleknucfp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.andypj.xyz/Article/details/gthhdakemh.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yangfankeji.com/Article/details/gtkhrmrjcj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.birdmap.top/Article/details/gtufekvgie.html

[D11] 反转数组
来源：http://dali.nanxinkj.top/Article/details/gtcwfiojjc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.chenlongwang.top/Article/details/gthbvjoxqb.html

PHP:  array_reverse($arr);
来源：http://dali.guannengcc.top/Article/details/gtgvzmpzkz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.wangdashe.top/Article/details/gtxihnpnas.html

TS:   [...arr].reverse();
来源：http://dali.shangyingyoupin.top/Article/details/gtnyknitzf.html

Java: Collections.reverse(list);
来源：http://dali.ivvv.top/Article/details/gtytkhkjzx.html

Go:   slices.Reverse(arr)
来源：http://dali.smart0.xyz/Article/details/gtxnvrxcjn.html

Ruby: arr.reverse
来源：http://dali.andypj.xyz/Article/details/gtkchwucxs.html

C#:   list.Reverse();
来源：http://dali.chenjidiqi.icu/Article/details/gtgsbyuvnh.html

[D12] 查找元素下标
来源：http://dali.zhiwuduotai.top/Article/details/gtonfqmzjg.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhiwuduotai.top/Article/details/gtglquxjhh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.0kj1m.cn/Article/details/gtxmtyzawh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cdnleiting.top/Article/details/gtoawhqahs.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.havefunace.top/Article/details/gthzzjrnhc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.nwbrower.top/Article/details/gtifuldlqy.html

Go:   slices.Index(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtljlxgkww.html

Ruby: arr.index(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtaxpiiedi.html

C#:   list.IndexOf(x);
来源：http://dali.shzxlz.cn/Article/details/gtnuumchiq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.quarkkingdee.top/Article/details/gtqjsxkcuc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yangfankeji.com/Article/details/gtpuihycvl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jiagoushi.top/Article/details/gtmefqbjue.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jyoumei.cn/Article/details/gtwctlpxrt.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jlsjyb.cn/Article/details/gtfhyfvxum.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtfejdjiba.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nanxinkj.top/Article/details/gtninwmngm.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpmlzwqks.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkcuhhzau.html

[D14] 映射转换（每个元素变形）
来源：http://dali.feifeiyinyue.top/Article/details/gtkvxjizun.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jyoumei.cn/Article/details/gtnmuqadxh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtufvulopl.html

JS:   arr.map(x => x * 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtxbqhxwrh.html

TS:   arr.map(x => x * 2)
来源：http://dali.yj202588.top/Article/details/gtjdmjcgtp.html


<!-- 参考信息 -->