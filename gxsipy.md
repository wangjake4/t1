代发 wailian999

Go:   a && b || !c
来源：http://dali.havefunace.top/Article/details/gtyonbghmg.html

Ruby: a && b || !c
来源：http://dali.9152youxi.cn/Article/details/gtvzwvngrh.html

C#:   a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gthsughehe.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.nwbrower.top/Article/details/gtfraqwkgv.html

Py:   if not data: return
来源：http://dali.guannengcc.top/Article/details/gtdobhuzcd.html

PHP:  if (!$data) { return; }
来源：http://dali.ivvv.top/Article/details/gtokyriucm.html

JS:   if (!data) return;
来源：http://dali.ehwqpu.com/Article/details/gtucwbjlgr.html

TS:   if (!data) return;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqzozqfbq.html

Java: if (data == null) return;
来源：http://dali.sufxvd.cn/Article/details/gtdjgxlhxn.html

Go:   if data == nil { return }
来源：http://dali.ppjwa.cn/Article/details/gtirgpcqdb.html

Ruby: return if data.nil?
来源：http://dali.dashuyun.cn/Article/details/gteliaokbn.html

C#:   if (data == null) return;
来源：http://dali.cqqwz.cn/Article/details/gthmvauzxv.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtwofplyph.html

C. 函数与作用域
来源：http://dali.xylfe.cn/Article/details/gtwvhhfuvb.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtakpnukoc.html

[C01] 定义函数
来源：http://dali.ppjwa.cn/Article/details/gteyclfiqe.html

Py:   def add(a, b): return a + b
来源：http://dali.pycfn.com/Article/details/gtpkoxycmq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.9152youxi.cn/Article/details/gttwoddyjl.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cheryme.top/Article/details/gtibnqlkjo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yonumen.top/Article/details/gtyqwnuend.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtsasblmei.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.sysykeji.top/Article/details/gtikfjwdrc.html

Ruby: def add(a, b); a + b; end
来源：http://dali.meibo888.top/Article/details/gtrajzvktt.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gttwwlnibl.html

[C02] 默认参数
来源：http://dali.aizwys.cn/Article/details/gtrjqqngft.html

Py:   def greet(name="World"): return name
来源：http://dali.cheryme.top/Article/details/gtuzhdoyyz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jinqigfzy.top/Article/details/gtdjehjiph.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnstmhmxo.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.sufxvd.cn/Article/details/gtjdncuxqb.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.iojbl.cn/Article/details/gtxfxcyrua.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpomnwhna.html

Ruby: def greet(name = "World") = name
来源：http://dali.ivvv.top/Article/details/gtcccxlbnt.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gotoacloud.top/Article/details/gtbappqbbe.html

[C03] 可变参数
来源：http://dali.redwolf501.top/Article/details/gtgphqrmsg.html

Py:   def total(*args): return sum(args)
来源：http://dali.hongshengwenyu.top/Article/details/gtbzufyatd.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xziqi.cn/Article/details/gtyifazkdn.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvugfqpnw.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hnqzz.top/Article/details/gttviunpdh.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xuanzx.com/Article/details/gtospkymco.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xuetiantiany.cn/Article/details/gtavxfynqs.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinqigfzy.top/Article/details/gtusoflvqv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.meibo888.top/Article/details/gtbkjssazm.html

[C04] 命名参数 / 关键字参数
来源：http://dali.xuetiantiany.cn/Article/details/gtigleamkb.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhoulong.xyz/Article/details/gtvxplpmeu.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shzxlz.cn/Article/details/gtzrwjkgrd.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zycfv.cn/Article/details/gttzlfwuof.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zdqjudy.top/Article/details/gtnkawsskm.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xuanzx.com/Article/details/gtnbuxddeh.html

Go:   // 无：用配置结构体参数
来源：http://dali.yueranfly.top/Article/details/gtbfxeyvqe.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hammf.cn/Article/details/gtnhejdaje.html

C#:   f(a: 1, b: 2)
来源：http://dali.xuanzx.com/Article/details/gtnfgmyyey.html

[C05] 返回多个值
来源：http://dali.jqgufenzy.top/Article/details/gtxqerorul.html

Py:   return a, b
来源：http://dali.c1oappe.top/Article/details/gthiwbolfp.html

PHP:  return [$a, $b];
来源：http://dali.jianghu66.top/Article/details/gtbsmuvfwy.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlhayzabq.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gtzcxmaseg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.pengpengdd.cyou/Article/details/gtlppgshvq.html

Go:   return a, b
来源：http://dali.zhengqikj.top/Article/details/gtmlpqtfko.html

Ruby: return a, b
来源：http://dali.guowangkeji.top/Article/details/gttamlcgaj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xuanzx.com/Article/details/gtdnspzxsy.html

[C06] 匿名函数 / lambda
来源：http://dali.hammf.cn/Article/details/gtxijhemzk.html

Py:   square = lambda x: x * x
来源：http://dali.wangshuangyany.cn/Article/details/gtojleoheb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jinqigufen.top/Article/details/gtkwqihhdt.html

JS:   const square = x => x * x;
来源：http://dali.jqgfzy.top/Article/details/gtktobngxo.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.gaohongyu789.top/Article/details/gthzwlveym.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.tian-w.cn/Article/details/gtquwnjbnl.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jinqigfzy.top/Article/details/gtcfxggttb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yuxming.cn/Article/details/gtjkyixfau.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.gotoacloud.top/Article/details/gtfujqwfbi.html

[C07] 把函数作为参数传入
来源：http://dali.guowangkeji.top/Article/details/gtdxmmoacc.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shangyingyoupin.top/Article/details/gtposamkmg.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.c1oappe.top/Article/details/gtcbkobuei.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdkkazvpw.html

TS:   arr.map(String)
来源：http://dali.xinyue.icu/Article/details/gtohcpptsv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zdqjudy.top/Article/details/gtgterbhnr.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ywan-chungtsiang.top/Article/details/gttcqfgobl.html

Ruby: arr.map(&:upcase)
来源：http://dali.iojbl.cn/Article/details/gtlcqqeqxr.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yuanzhike.top/Article/details/gtnrsxfddp.html

[C08] 闭包
来源：http://dali.jinyuanbaomall.cn/Article/details/gtorlohpfq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.9152youxi.cn/Article/details/gtbptsihbq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.kuanghao11.cn/Article/details/gtpdikkbeu.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.kuanghao11.cn/Article/details/gtanzuypzw.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yj20258.top/Article/details/gtfnvadcso.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hywenlv.cn/Article/details/gtnswkwelw.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtludcxzcq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.haohaochexian.top/Article/details/gtaiywhvow.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.mhx1999.top/Article/details/gtrqigvdpd.html

[C09] 递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbmuwrzdm.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yonumen.top/Article/details/gtyxwryclv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.sysykeji.top/Article/details/gtieawwkzl.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.vqdsnc.cn/Article/details/gturqoxxol.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sweek.top/Article/details/gtezhexgwa.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.dianchejie.cn/Article/details/gtnjziixqz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.gotoacloud.top/Article/details/gtbiukgdgc.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.haohaochexian.top/Article/details/gtdaeppwgi.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yj20258.top/Article/details/gtxudwmoya.html

[C10] 变量作用域
来源：http://dali.tian-w.cn/Article/details/gtkmyhfjrr.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hywenlv.cn/Article/details/gtacdnsizr.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.pengpengdd.cyou/Article/details/gtnundxfuj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.andypj.xyz/Article/details/gtqeycxcgg.html

TS:   同 JS
来源：http://dali.cdnleiting.top/Article/details/gtihevafyi.html

Java: 方法内为块级作用域
来源：http://dali.hfpthk.cn/Article/details/gtpemzducr.html

Go:   花括号块级作用域
来源：http://dali.aibaodan.cn/Article/details/gtpzkbspvl.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jinqigfzy.top/Article/details/gtgduiwfpa.html

C#:   块级作用域
来源：http://dali.yueranfly.top/Article/details/gtichjevbe.html

[C11] 模块导入与导出
来源：http://dali.tian-w.cn/Article/details/gtkpgdlmxy.html

Py:   from module import func
来源：http://dali.zycfv.cn/Article/details/gtpmlwbmcf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.dashuyun.cn/Article/details/gtygtrvrgz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.daria6918.cn/Article/details/gtaeuzynwf.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.meibo888.top/Article/details/gtvthvdymy.html

Java: import java.util.List;
来源：http://dali.hywenlv.cn/Article/details/gtxieerxlz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xinyue.icu/Article/details/gtkhqgkjyc.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.nanxuanxn.top/Article/details/gtkhfrpfak.html

C#:   using System.Text;
来源：http://dali.jlsjyb.cn/Article/details/gtcasrlvku.html

[C12] 立即执行函数 IIFE
来源：http://dali.xziqi.cn/Article/details/gtdjhrsqsk.html

Py:   (lambda: print("run"))()
来源：http://dali.cucudq.cn/Article/details/gtphqwxujq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.gzhubu.top/Article/details/gtdsagxxzh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hammf.cn/Article/details/gtgfoozeuv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yueranfly.top/Article/details/gtqhdxssel.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hnxiangtu.top/Article/details/gtdrhcztgu.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtljiveyqw.html

Ruby: -> { puts "run" }.call
来源：http://dali.jyoumei.cn/Article/details/gtekjopxiz.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtgeivrgxp.html

[C13] 类型声明 / 类型注解
来源：http://dali.nanxinkj.top/Article/details/gtaulmnnoe.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.redwolf501.top/Article/details/gtfbwbvucs.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xziqi.cn/Article/details/gtmojbiocm.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.aibaodan.cn/Article/details/gtdrlvxwoz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtfbvpzepr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gtboykgjqf.html

Go:   func add(a, b int) int
来源：http://dali.birdmap.top/Article/details/gtkkcrwaml.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.aizwys.cn/Article/details/gtikalpias.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.316326.xyz/Article/details/gtocdlafre.html

[C14] 泛型函数
来源：http://dali.cheryme.top/Article/details/gtqfznqzqa.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.daxiang520.top/Article/details/gtbhseyrfi.html

PHP:  // 无泛型
来源：http://dali.zycfv.cn/Article/details/gtmooyoovj.html

JS:   // 无泛型
来源：http://dali.ivvv.top/Article/details/gttfajbldb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yuxming.cn/Article/details/gtaidvhzep.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.fzhhl.top/Article/details/gtoahkernk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.pycfn.com/Article/details/gtywouujhd.html

Ruby: # 无泛型
来源：http://dali.zhiwuduotai.top/Article/details/gtvfsvlmhg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.tian-w.cn/Article/details/gtrlhpyjxo.html

[C15] 解构 / 展开参数
来源：http://dali.zhixingplan.top/Article/details/gtephnjddb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.havefunace.top/Article/details/gtizezuigp.html

PHP:  [$a, $b] = $pair;
来源：http://dali.sxryk.cn/Article/details/gtmluqhjup.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cashguo.top/Article/details/gtyfszfmke.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cashguo.top/Article/details/gtzmwgflcp.html

Java: // 无解构
来源：http://dali.chenlongwang.top/Article/details/gtclhpknjf.html

Go:   // 无解构
来源：http://dali.xziqi.cn/Article/details/gtxwfpkfns.html

Ruby: a, b = pair
来源：http://dali.nwbrower.top/Article/details/gtwjckuetg.html

C#:   var (a, b) = pair;
来源：http://dali.shuidangran.top/Article/details/gtjkoxoowv.html

[C16] 函数 / 方法重载
来源：http://dali.jyoumei.cn/Article/details/gtcdkduxry.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.wangdashe.top/Article/details/gtgpeogdll.html

PHP:  // 无重载
来源：http://dali.daria6918.cn/Article/details/gtwyimmawh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.nanxuanxn.top/Article/details/gtrnuhgdrf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.bjfxy.top/Article/details/gtzonogkkz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtzqrivmzj.html

Go:   // 无重载：用不同函数名
来源：http://dali.kuanghao11.cn/Article/details/gtzxutunsm.html

Ruby: # 无重载：靠动态参数
来源：http://dali.0kj1m.cn/Article/details/gtdvlgxjhd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.quarkkingdee.top/Article/details/gtemfkjvgv.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtwiajhcba.html

D. 数组 / 列表 / 集合
来源：http://dali.ybcxt.top/Article/details/gtpahcntpk.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gthbzwxlso.html

[D01] 创建数组 / 列表
来源：http://dali.mhx1999.top/Article/details/gtfilrebba.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.havefunace.top/Article/details/gtifziyflh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.dashuyun.cn/Article/details/gtfwczhoth.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yanxiufei.cn/Article/details/gtvowtucfh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.tanke756.top/Article/details/gtrruakfyc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.sxryk.cn/Article/details/gtibdulbyu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.316326.xyz/Article/details/gtndaxikmf.html

Ruby: arr = [1, 2, 3]
来源：http://dali.mhx1999.top/Article/details/gtcxagtifq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.chenlongwang.top/Article/details/gtifbmatcx.html

[D02] 追加元素到末尾
来源：http://dali.chenlongwang.top/Article/details/gtlcjtjobi.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hongshengwenyu.top/Article/details/gtotoexcja.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.nanxinkj.top/Article/details/gtggnumyak.html

JS:   arr.push(4);
来源：http://dali.dashuyun.cn/Article/details/gtwazawjeg.html

TS:   arr.push(4);
来源：http://dali.9152youxi.cn/Article/details/gtxqxkgbyv.html

Java: list.add(4);
来源：http://dali.cdnleiting.top/Article/details/gtuajthouo.html

Go:   arr = append(arr, 4)
来源：http://dali.yuxming.cn/Article/details/gtcfxhxemo.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jinqigfzy.top/Article/details/gtfuibnbxo.html

C#:   list.Add(4);
来源：http://dali.fengsongda.top/Article/details/gtmdghjcwz.html

[D03] 在指定位置插入元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gttlbwrbbe.html

Py:   arr.insert(0, 0)
来源：http://dali.yuxming.cn/Article/details/gtcnbdeuvd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zycfv.cn/Article/details/gtshakgfyo.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.wangshuangyany.cn/Article/details/gtwtqmgqjg.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.bjfxy.top/Article/details/gtucpxbkvd.html

Java: list.add(0, 0);
来源：http://dali.tanke756.top/Article/details/gtefahowrb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gzhubu.top/Article/details/gtrwvcsyux.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhoulong.xyz/Article/details/gtfoffdxbl.html

C#:   list.Insert(0, 0);
来源：http://dali.chenzaomai.com/Article/details/gtktzjwibd.html

[D04] 删除元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxkqnemms.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hammf.cn/Article/details/gtfbqkcews.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hfpthk.cn/Article/details/gtcdtxbevr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ppjwa.cn/Article/details/gtxmidxurw.html

TS:   arr.splice(0, 1);
来源：http://dali.guowangkeji.top/Article/details/gtaykbecby.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.aizwys.cn/Article/details/gtchauwgzl.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.c1oappe.top/Article/details/gtvjrbyvzc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.sysykeji.top/Article/details/gtucbnvijm.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yvedp.cn/Article/details/gtvnthnijc.html

[D05] 访问与修改元素
来源：http://dali.zhiwuduotai.top/Article/details/gtqreodfkn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aizwys.cn/Article/details/gtnpkdjgyk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.dianchejie.cn/Article/details/gtlysyegpm.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yangfankeji.com/Article/details/gtrglizthy.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzoqgxoyv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zycfv.cn/Article/details/gtaaxafecz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hongshengwenyu.top/Article/details/gtglgrhwgs.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hongshengwenyu.top/Article/details/gtojnjrcxh.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.aibaodan.cn/Article/details/gtpjwaxbsl.html

[D06] 数组长度
来源：http://dali.shangyingyoupin.top/Article/details/gtxbogcjrn.html

Py:   len(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtbgeohcwm.html

PHP:  count($arr);
来源：http://dali.yueranfly.top/Article/details/gtlikihngd.html

JS:   arr.length
来源：http://dali.gaohongyu789.top/Article/details/gtadjxzbfn.html

TS:   arr.length
来源：http://dali.fzhhl.top/Article/details/gtixlchfdt.html

Java: list.size();
来源：http://dali.iojbl.cn/Article/details/gtihsyndbd.html

Go:   len(arr)
来源：http://dali.cqqwz.cn/Article/details/gtdluboabc.html

Ruby: arr.length; arr.size
来源：http://dali.0kj1m.cn/Article/details/gtdvtpjswj.html

C#:   list.Count;
来源：http://dali.hammf.cn/Article/details/gterkwhaei.html

[D07] 切片 / 取子数组
来源：http://dali.xuetiantiany.cn/Article/details/gtkdjqddnz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.wangdashe.top/Article/details/gtpddrwtst.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.wangdashe.top/Article/details/gtihhrwdjh.html

JS:   arr.slice(1, 4);
来源：http://dali.zhoulong.xyz/Article/details/gtnmzusfiw.html

TS:   arr.slice(1, 4);
来源：http://dali.smart0.xyz/Article/details/gtjtovumhr.html

Java: list.subList(1, 4);
来源：http://dali.yanxiufei.cn/Article/details/gtokternkf.html

Go:   arr[1:4]
来源：http://dali.0kj1m.cn/Article/details/gtfzvgnxcf.html

Ruby: arr[1, 3]
来源：http://dali.aibaodan.cn/Article/details/gtwwnobyze.html

C#:   list.GetRange(1, 3);
来源：http://dali.iojbl.cn/Article/details/gthcqhjmey.html

[D08] 合并两个数组
来源：http://dali.yj202588.top/Article/details/gttvtmfrbp.html

Py:   a + b;  a.extend(b)
来源：http://dali.jianghu66.top/Article/details/gtsozutfrb.html

PHP:  array_merge($a, $b);
来源：http://dali.zdqjudy.top/Article/details/gtcycyudux.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.nwbrower.top/Article/details/gtwplybsdp.html

TS:   [...a, ...b];
来源：http://dali.shuidangran.top/Article/details/gtahmahihk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hnxiangtu.top/Article/details/gtefmxfmnk.html

Go:   append(a, b...)
来源：http://dali.jinqigfzy.top/Article/details/gtcvslosjs.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhiwuduotai.top/Article/details/gtafoihxur.html

C#:   a.Concat(b).ToList()
来源：http://dali.daria6918.cn/Article/details/gtjqlobpnu.html

[D09] 排序（升序）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmflpionl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pengpengdd.cyou/Article/details/gtuyduesfg.html

PHP:  sort($arr);
来源：http://dali.gogol.net.cn/Article/details/gthwofnika.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xziqi.cn/Article/details/gtifuaidln.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.daria6918.cn/Article/details/gthgsagpjl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yanxiufei.cn/Article/details/gtligiqpve.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yangfankeji.com/Article/details/gthxjbvrqx.html

Ruby: arr.sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpxanikvd.html

C#:   list.Sort();
来源：http://dali.jinqigufen.top/Article/details/gtyxowakcj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.smart0.xyz/Article/details/gtxnvssczg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jqgfzy.top/Article/details/gtvpydqtif.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jianghu66.top/Article/details/gtazxvtkos.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tianlin.xyz/Article/details/gtqgghubwh.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gtzmcvxbrc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cheryme.top/Article/details/gtpgwhcpkx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.iojbl.cn/Article/details/gthqycprui.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinqigfzy.top/Article/details/gtwaofkgnt.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtflyporxv.html

[D11] 反转数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjemrtcru.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jlsjyb.cn/Article/details/gtkmslbycx.html

PHP:  array_reverse($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtdxzijrns.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcxyvsumz.html

TS:   [...arr].reverse();
来源：http://dali.0kj1m.cn/Article/details/gtinwbrytb.html

Java: Collections.reverse(list);
来源：http://dali.hfpthk.cn/Article/details/gtbrdbydfk.html

Go:   slices.Reverse(arr)
来源：http://dali.meibo888.top/Article/details/gtxamsyuhs.html

Ruby: arr.reverse
来源：http://dali.xuanzx.com/Article/details/gtfalckmbg.html

C#:   list.Reverse();
来源：http://dali.xinyue.icu/Article/details/gtznyjqnsd.html

[D12] 查找元素下标
来源：http://dali.jiagoushi.top/Article/details/gtygdbcepg.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhiwuduotai.top/Article/details/gtzfaxnlbj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.meibo888.top/Article/details/gtvagrskcs.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.quarkkingdee.top/Article/details/gtgnkqtwvx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gtaqmrfjti.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.nwbrower.top/Article/details/gtlvedcdws.html

Go:   slices.Index(arr, x)
来源：http://dali.daria6918.cn/Article/details/gttuofnrru.html

Ruby: arr.index(x)
来源：http://dali.svipenyu.cn/Article/details/gtifrwxmuk.html

C#:   list.IndexOf(x);
来源：http://dali.yj20258888.top/Article/details/gtiwmglbxk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hysaishi.cn/Article/details/gtqgpcyoaa.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.gaohongyu789.top/Article/details/gtnawstscn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hnxiangtu.top/Article/details/gtdibmskrk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zycfv.cn/Article/details/gtpslgfgak.html

TS:   arr.filter(x => x > 3)
来源：http://dali.quarkkingdee.top/Article/details/gthfxmsmtn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.svipenyu.cn/Article/details/gtwhlqzyji.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.haohaochexian.top/Article/details/gtegbbclwt.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhengqikj.top/Article/details/gtrprqzvbs.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yongpay.top/Article/details/gtqhaziqal.html

[D14] 映射转换（每个元素变形）
来源：http://dali.vqdsnc.cn/Article/details/gtcnxkjdyf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.nanxuanxn.top/Article/details/gtogcbqppl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtdvwkbbvc.html

JS:   arr.map(x => x * 2)
来源：http://dali.yvedp.cn/Article/details/gtqrizmzjg.html

TS:   arr.map(x => x * 2)
来源：http://dali.c1oappe.top/Article/details/gtuanmefwo.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cheryme.top/Article/details/gtlbptcxes.html

Go:   // 手写循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqnxnivfw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yj202588.top/Article/details/gtoduufurz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sweek.top/Article/details/gtkbbjmrmr.html

[D15] 去重
来源：http://dali.cdnleiting.top/Article/details/gtsnqecgbp.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.fzhhl.top/Article/details/gtnpljclyf.html

PHP:  array_unique($arr);
来源：http://dali.ppjwa.cn/Article/details/gtpkimtiux.html

JS:   [...new Set(arr)]
来源：http://dali.zhongyouzk.top/Article/details/gthrqwzxff.html

TS:   [...new Set(arr)]
来源：http://dali.gaohongyu789.top/Article/details/gtuafjtwfs.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.wangshuangyany.cn/Article/details/gtpwyhmwuw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.tianlin.xyz/Article/details/gtlloccmts.html

Ruby: arr.uniq
来源：http://dali.shanyushiyangtech.top/Article/details/gtllwgrdez.html

C#:   list.Distinct().ToList()
来源：http://dali.aizwys.cn/Article/details/gtiwpyoasa.html

[D16] 求和与平均值
来源：http://dali.wangshuangyany.cn/Article/details/gtjhnjdodw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cucudq.cn/Article/details/gtaprquszd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hywenlv.cn/Article/details/gtvqfdoorz.html


<!-- 参考信息 -->