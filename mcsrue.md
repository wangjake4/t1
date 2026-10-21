代发 wailian999

================================================================================
来源：http://dali.cheryme.top/Article/details/gtebymdukj.html

C. 函数与作用域
来源：http://dali.sysykeji.top/Article/details/gtvnltcrfv.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtscomubtx.html

[C01] 定义函数
来源：http://dali.yonumen.top/Article/details/gtnpkzjeyp.html

Py:   def add(a, b): return a + b
来源：http://dali.smart0.xyz/Article/details/gtkihkfcfn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yvedp.cn/Article/details/gtdkbapuyv.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gtluyenyfs.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gtdxwdnwcy.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gtqarhzoxa.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.shuidangran.top/Article/details/gtzamkqhny.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hysaishi.cn/Article/details/gtlryivxbh.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gthnirclac.html

[C02] 默认参数
来源：http://dali.jlsjyb.cn/Article/details/gthabdclou.html

Py:   def greet(name="World"): return name
来源：http://dali.fengsongda.top/Article/details/gtcfxdhdkr.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.nanxinkj.top/Article/details/gtvxqnctvs.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.sweek.top/Article/details/gtzloocgbx.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtaxjydyde.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.iojbl.cn/Article/details/gtybntnrow.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.quarkkingdee.top/Article/details/gtaluacyki.html

Ruby: def greet(name = "World") = name
来源：http://dali.birdmap.top/Article/details/gtmzbdcbvs.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jinqigfzy.top/Article/details/gtyhwoasmt.html

[C03] 可变参数
来源：http://dali.yj20258.top/Article/details/gtibkludaq.html

Py:   def total(*args): return sum(args)
来源：http://dali.9152youxi.cn/Article/details/gtnqogyafl.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.andypj.xyz/Article/details/gtkvpxpgrz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sufxvd.cn/Article/details/gtjiociaed.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yonumen.top/Article/details/gtblhsxnin.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.daria6918.cn/Article/details/gtvxyhdwev.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hysaishi.cn/Article/details/gtbrkzkqqw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yongpay.top/Article/details/gtbiojndcd.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jinqigfzy.top/Article/details/gtuqpintbs.html

[C04] 命名参数 / 关键字参数
来源：http://dali.chenzaomai.com/Article/details/gtalozuxiu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ivvv.top/Article/details/gtnalfplbg.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hfpthk.cn/Article/details/gtyqbaewmx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.gzhubu.top/Article/details/gthiqfagyd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.gotoacloud.top/Article/details/gtmdakoxhr.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvyfjhzqw.html

Go:   // 无：用配置结构体参数
来源：http://dali.yj202588.top/Article/details/gtbmyqnvjc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cdnleiting.top/Article/details/gtoygappnq.html

C#:   f(a: 1, b: 2)
来源：http://dali.cucudq.cn/Article/details/gtemhawrxl.html

[C05] 返回多个值
来源：http://dali.zhaomingkeji.xyz/Article/details/gthljtvswo.html

Py:   return a, b
来源：http://dali.xinyue.icu/Article/details/gtzbiyxllu.html

PHP:  return [$a, $b];
来源：http://dali.dashuyun.cn/Article/details/gtvktdowlj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jinqigfzy.top/Article/details/gtjlmyuzfo.html

TS:   return { a, b };
来源：http://dali.jianghu66.top/Article/details/gtgjjpdyvo.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.wangdashe.top/Article/details/gtyvcxorhl.html

Go:   return a, b
来源：http://dali.aizwys.cn/Article/details/gtrwfauret.html

Ruby: return a, b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttstdxyuo.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.pengpengdd.cyou/Article/details/gtvoiqqnqy.html

[C06] 匿名函数 / lambda
来源：http://dali.ydzc1.top/Article/details/gtiqjjxbdc.html

Py:   square = lambda x: x * x
来源：http://dali.fengsongda.top/Article/details/gtcsmgukxg.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.0kj1m.cn/Article/details/gtituyxqlz.html

JS:   const square = x => x * x;
来源：http://dali.yangfankeji.com/Article/details/gtokbdifbt.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cqqwz.cn/Article/details/gtohkjkwdt.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hysaishi.cn/Article/details/gtkuommkwb.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.chenlongwang.top/Article/details/gtngumjxya.html

Ruby: square = ->(x) { x * x }
来源：http://dali.9152youxi.cn/Article/details/gtfblhhoda.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hnxiangtu.top/Article/details/gtwcifedrj.html

[C07] 把函数作为参数传入
来源：http://dali.yvedp.cn/Article/details/gtmhezostc.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ydzc1.top/Article/details/gtuoesiuwk.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtalxosolf.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.nanxinkj.top/Article/details/gtbvxsparh.html

TS:   arr.map(String)
来源：http://dali.ppjwa.cn/Article/details/gtnwfvusbc.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gtfmqloafo.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.sweek.top/Article/details/gtmktkncpd.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinqigfzy.top/Article/details/gtgbjnkfor.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yueranfly.top/Article/details/gtgcvpbtvz.html

[C08] 闭包
来源：http://dali.chenlongwang.top/Article/details/gtxfyrfbpn.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.sufxvd.cn/Article/details/gtjxzvgxbu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.kuanghao11.cn/Article/details/gtsbpzxwjy.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhengqikj.top/Article/details/gtodaebufy.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhixingplan.top/Article/details/gtuwkdgkoh.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shuidangran.top/Article/details/gtkvqblmua.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.tian-w.cn/Article/details/gtjumtuvrz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.kuanghao11.cn/Article/details/gtojkcundu.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.nanxinkj.top/Article/details/gtoukmuxdk.html

[C09] 递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsxfejscu.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yj20258888.top/Article/details/gtlsupxtkg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.tianlin.xyz/Article/details/gtlfwisjuz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.feifeiyinyue.top/Article/details/gticsxlehu.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yangfankeji.com/Article/details/gtfpqqpnog.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.chenjidiqi.icu/Article/details/gtbqzzqenk.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shzxlz.cn/Article/details/gtmplnqfym.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cqqwz.cn/Article/details/gtnppmwpla.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.0kj1m.cn/Article/details/gtshhhceos.html

[C10] 变量作用域
来源：http://dali.cdnleiting.top/Article/details/gtqldtyoxo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yonumen.top/Article/details/gtbefcxegj.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.guowangkeji.top/Article/details/gtsheialtg.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.daxiang520.top/Article/details/gtqfshvwgw.html

TS:   同 JS
来源：http://dali.chenjidiqi.icu/Article/details/gtuftbzwii.html

Java: 方法内为块级作用域
来源：http://dali.hongshengwenyu.top/Article/details/gtkehrhzwo.html

Go:   花括号块级作用域
来源：http://dali.ppjwa.cn/Article/details/gtaakbarhx.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.gotoacloud.top/Article/details/gtnzkslhuk.html

C#:   块级作用域
来源：http://dali.fzhhl.top/Article/details/gtzqtzocxo.html

[C11] 模块导入与导出
来源：http://dali.guannengcc.top/Article/details/gtbxpgbgst.html

Py:   from module import func
来源：http://dali.andypj.xyz/Article/details/gtyzjvrisu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xziqi.cn/Article/details/gttpcyghjo.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.guowangkeji.top/Article/details/gtqkwgonjt.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jianghu66.top/Article/details/gtnteqtvkq.html

Java: import java.util.List;
来源：http://dali.xinyue.icu/Article/details/gtosfbyhex.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shzxlz.cn/Article/details/gtupxgwdge.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.smart0.xyz/Article/details/gturhcueqv.html

C#:   using System.Text;
来源：http://dali.pycfn.com/Article/details/gtlliorgil.html

[C12] 立即执行函数 IIFE
来源：http://dali.havefunace.top/Article/details/gtgvxpimfa.html

Py:   (lambda: print("run"))()
来源：http://dali.bjfxy.top/Article/details/gtjpsayixy.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shangyingyoupin.top/Article/details/gtxyxmqlnp.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cashguo.top/Article/details/gtiladvtha.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhoulong.xyz/Article/details/gtpmgmpkxr.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.vqdsnc.cn/Article/details/gtlqpgammy.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvgnarxak.html

Ruby: -> { puts "run" }.call
来源：http://dali.xziqi.cn/Article/details/gtwcwhmgvf.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cashguo.top/Article/details/gtxjrxvfsc.html

[C13] 类型声明 / 类型注解
来源：http://dali.yonumen.top/Article/details/gtlqwpzkyd.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cheryme.top/Article/details/gtxebijcrg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gtapoysooo.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yanxiufei.cn/Article/details/gttkhkkyec.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtgqeerxui.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gtbmiencij.html

Go:   func add(a, b int) int
来源：http://dali.cucudq.cn/Article/details/gtvjweckhv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.daria6918.cn/Article/details/gtbrrwlivi.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.feifeiyinyue.top/Article/details/gtmnnaocxn.html

[C14] 泛型函数
来源：http://dali.jinqigufen.top/Article/details/gtzdjeloct.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.fengsongda.top/Article/details/gtyqxrmbxt.html

PHP:  // 无泛型
来源：http://dali.yj202588.top/Article/details/gtrysrpkyd.html

JS:   // 无泛型
来源：http://dali.shuidangran.top/Article/details/gtmavaktry.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzojigers.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gaohongyu789.top/Article/details/gtcbcufllc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhoulong.xyz/Article/details/gtyanomxoa.html

Ruby: # 无泛型
来源：http://dali.daxiang520.top/Article/details/gtbejdgiah.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.guowangkeji.top/Article/details/gtqedbxtgt.html

[C15] 解构 / 展开参数
来源：http://dali.9152youxi.cn/Article/details/gtvulgxvet.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yanxiufei.cn/Article/details/gtsebeobsf.html

PHP:  [$a, $b] = $pair;
来源：http://dali.9152youxi.cn/Article/details/gtwzfptjjk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yj20258.top/Article/details/gtsjofzdqg.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gogol.net.cn/Article/details/gtxyyimqne.html

Java: // 无解构
来源：http://dali.svipenyu.cn/Article/details/gtoifvkscf.html

Go:   // 无解构
来源：http://dali.quarkkingdee.top/Article/details/gtdknavplo.html

Ruby: a, b = pair
来源：http://dali.jinghuilouyu.cn/Article/details/gtecyrpnem.html

C#:   var (a, b) = pair;
来源：http://dali.aibaodan.cn/Article/details/gtdtbljdnw.html

[C16] 函数 / 方法重载
来源：http://dali.hammf.cn/Article/details/gtcyedcgjc.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.birdmap.top/Article/details/gttvgleevh.html

PHP:  // 无重载
来源：http://dali.guowangkeji.top/Article/details/gtwcfjuoor.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhoulong.xyz/Article/details/gtcoaseayj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ehwqpu.com/Article/details/gtihvjynzl.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zdqjudy.top/Article/details/gtazpvvzwk.html

Go:   // 无重载：用不同函数名
来源：http://dali.dianchejie.cn/Article/details/gtbmnixtkt.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ehwqpu.com/Article/details/gtvacwuspf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.kuanghao11.cn/Article/details/gteqakpkhi.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtmkunzdzn.html

D. 数组 / 列表 / 集合
来源：http://dali.mhx1999.top/Article/details/gtrvqinbdm.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtrmnapqfe.html

[D01] 创建数组 / 列表
来源：http://dali.zhengqikj.top/Article/details/gtlckbyogl.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hammf.cn/Article/details/gtxpkjaehv.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.tianlin.xyz/Article/details/gtimzmgjfv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnhwjoaqx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jinghuilouyu.cn/Article/details/gtjocettog.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shanyushiyangtech.top/Article/details/gthhvqsfta.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.smart0.xyz/Article/details/gtcppptjqo.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yangfankeji.com/Article/details/gtjddidmks.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sufxvd.cn/Article/details/gtragyptyk.html

[D02] 追加元素到末尾
来源：http://dali.chenzaomai.com/Article/details/gtwbiywscb.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.havefunace.top/Article/details/gtmozphllt.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtadokosno.html

JS:   arr.push(4);
来源：http://dali.guowangkeji.top/Article/details/gtlugmkdjj.html

TS:   arr.push(4);
来源：http://dali.zhixingplan.top/Article/details/gtevbvnxhu.html

Java: list.add(4);
来源：http://dali.9152youxi.cn/Article/details/gthznllukp.html

Go:   arr = append(arr, 4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwgmpeppm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ydzc1.top/Article/details/gtxmaksnes.html

C#:   list.Add(4);
来源：http://dali.smart0.xyz/Article/details/gtobzhjdud.html

[D03] 在指定位置插入元素
来源：http://dali.sweek.top/Article/details/gtuaaiojnl.html

Py:   arr.insert(0, 0)
来源：http://dali.xuanzx.com/Article/details/gtksaoclnj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.daxiang520.top/Article/details/gtsauhdtgd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gtdpeimxvn.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zdqjudy.top/Article/details/gtmruhcxuc.html

Java: list.add(0, 0);
来源：http://dali.dashuyun.cn/Article/details/gtvcwtwmrz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xuanzx.com/Article/details/gtcwgpqsin.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.bjfxy.top/Article/details/gtbupajfek.html

C#:   list.Insert(0, 0);
来源：http://dali.guowangkeji.top/Article/details/gtynvjdfax.html

[D04] 删除元素
来源：http://dali.ppjwa.cn/Article/details/gthpsnikrg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.redwolf501.top/Article/details/gtbmbketji.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.chenlongwang.top/Article/details/gtkrlngcsa.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gzhubu.top/Article/details/gtpwlgqufz.html

TS:   arr.splice(0, 1);
来源：http://dali.yanxiufei.cn/Article/details/gtrkgmlfiz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.meibo888.top/Article/details/gtamynxjvh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.nwbrower.top/Article/details/gtxqmwttwq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.nwbrower.top/Article/details/gtftipzezn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.svipenyu.cn/Article/details/gtncsgsjwm.html

[D05] 访问与修改元素
来源：http://dali.svipenyu.cn/Article/details/gtdrgefpwv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenjidiqi.icu/Article/details/gtlenlckcb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.snrcjt.cn/Article/details/gtvzrlesco.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.c1oappe.top/Article/details/gtpkdzesxn.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.0kj1m.cn/Article/details/gtpqupnkxb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.bjfxy.top/Article/details/gtcszywxvc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.nanxuanxn.top/Article/details/gtklcimmil.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxuanxn.top/Article/details/gtbkzrktfk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.sysykeji.top/Article/details/gtdwxuxhyh.html

[D06] 数组长度
来源：http://dali.tianlin.xyz/Article/details/gtmbratryp.html

Py:   len(arr)
来源：http://dali.dashuyun.cn/Article/details/gtiuhfadwu.html

PHP:  count($arr);
来源：http://dali.sweek.top/Article/details/gtnwcoenfv.html

JS:   arr.length
来源：http://dali.kuanghao11.cn/Article/details/gtiglpddjm.html

TS:   arr.length
来源：http://dali.zhixingplan.top/Article/details/gtymzukwtb.html

Java: list.size();
来源：http://dali.cashguo.top/Article/details/gtupgjqfno.html

Go:   len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtafapapwq.html

Ruby: arr.length; arr.size
来源：http://dali.hywenlv.cn/Article/details/gtcwbniare.html

C#:   list.Count;
来源：http://dali.dashuyun.cn/Article/details/gtljegkllr.html

[D07] 切片 / 取子数组
来源：http://dali.pengpengdd.cyou/Article/details/gttrwmnite.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhixingplan.top/Article/details/gteczjsngh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdbebzkbd.html

JS:   arr.slice(1, 4);
来源：http://dali.haohaochexian.top/Article/details/gtxyhmdakn.html

TS:   arr.slice(1, 4);
来源：http://dali.aizwys.cn/Article/details/gtosvevgkv.html

Java: list.subList(1, 4);
来源：http://dali.cucudq.cn/Article/details/gtwyyyuzro.html

Go:   arr[1:4]
来源：http://dali.chenzaomai.com/Article/details/gtjkihkbbe.html

Ruby: arr[1, 3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsjfejara.html

C#:   list.GetRange(1, 3);
来源：http://dali.316326.xyz/Article/details/gtczlzfsef.html

[D08] 合并两个数组
来源：http://dali.guannengcc.top/Article/details/gtbjfuowwu.html

Py:   a + b;  a.extend(b)
来源：http://dali.hfpthk.cn/Article/details/gtwhvcjanz.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gtoizaimca.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.quarkkingdee.top/Article/details/gtcwaybglr.html

TS:   [...a, ...b];
来源：http://dali.gzhubu.top/Article/details/gtzpgtxlny.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.havefunace.top/Article/details/gtrfidthpm.html

Go:   append(a, b...)
来源：http://dali.tian-w.cn/Article/details/gthwfccurt.html

Ruby: a + b;  a.concat(b)
来源：http://dali.aizwys.cn/Article/details/gtbvnqeljj.html

C#:   a.Concat(b).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtbahxonjw.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gttjaziytw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jyoumei.cn/Article/details/gtmeuhgcxz.html

PHP:  sort($arr);
来源：http://dali.xuanzx.com/Article/details/gttatkjebm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.andypj.xyz/Article/details/gtddsnodoc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yj20258888.top/Article/details/gtkyhrspqq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sweek.top/Article/details/gtcvwrfekm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jyoumei.cn/Article/details/gtyfrqfzls.html

Ruby: arr.sort
来源：http://dali.jianghu66.top/Article/details/gtjyqhrodw.html

C#:   list.Sort();
来源：http://dali.quarkkingdee.top/Article/details/gtoivprary.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.guannengcc.top/Article/details/gtmulmqbrt.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yvedp.cn/Article/details/gtpfelbpgu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.haohaochexian.top/Article/details/gthgxbtunw.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dashuyun.cn/Article/details/gtipoywbpj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hfpthk.cn/Article/details/gtkrrxaamk.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cashguo.top/Article/details/gtrqbcmceu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yuxming.cn/Article/details/gthzshzcsq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gogol.net.cn/Article/details/gtxwkclbhx.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yueranfly.top/Article/details/gtckoyewgs.html

[D11] 反转数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkfofenme.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yj202588.top/Article/details/gtzloqugsm.html

PHP:  array_reverse($arr);
来源：http://dali.yuanzhike.top/Article/details/gtuojwcwna.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hnqzz.top/Article/details/gtlhodwquy.html

TS:   [...arr].reverse();
来源：http://dali.jinqigufen.top/Article/details/gttgyjffvz.html

Java: Collections.reverse(list);
来源：http://dali.gogol.net.cn/Article/details/gtcrsiwabd.html

Go:   slices.Reverse(arr)
来源：http://dali.yvedp.cn/Article/details/gtwnnjscev.html

Ruby: arr.reverse
来源：http://dali.cqqwz.cn/Article/details/gteervjjqm.html

C#:   list.Reverse();
来源：http://dali.yueranfly.top/Article/details/gtlffqxepw.html

[D12] 查找元素下标
来源：http://dali.shuidangran.top/Article/details/gtvbynexeh.html

Py:   arr.index(x);  x in arr
来源：http://dali.redwolf501.top/Article/details/gtidbhbayv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yj20258.top/Article/details/gttlqzkyci.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzrdjvnva.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ppjwa.cn/Article/details/gtvwmprxrx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xuanzx.com/Article/details/gtogbomses.html

Go:   slices.Index(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gtdcosiyzk.html

Ruby: arr.index(x)
来源：http://dali.zhengqikj.top/Article/details/gtfjorkiap.html

C#:   list.IndexOf(x);
来源：http://dali.cashguo.top/Article/details/gtxyywpxnw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xinyue.icu/Article/details/gtmfddafnj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cucudq.cn/Article/details/gtiasyfjpn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.kuanghao11.cn/Article/details/gtcorhfmkl.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hysaishi.cn/Article/details/gtcntujsyy.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmbntfovf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.tanke756.top/Article/details/gtnunzpapx.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xuanzx.com/Article/details/gtkcfciiri.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yvedp.cn/Article/details/gtsughqeqj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cheryme.top/Article/details/gtttpzqpos.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzsqpzcjp.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.feifeiyinyue.top/Article/details/gtzaxwamoa.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jianghu66.top/Article/details/gtsjrkgcjz.html

JS:   arr.map(x => x * 2)
来源：http://dali.jlsjyb.cn/Article/details/gthzzxvqiv.html

TS:   arr.map(x => x * 2)
来源：http://dali.sufxvd.cn/Article/details/gtxxkindrd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hfpthk.cn/Article/details/gtmwznuflr.html

Go:   // 手写循环
来源：http://dali.andypj.xyz/Article/details/gtjjhwlzau.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ybcxt.top/Article/details/gtplxsrzwg.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtxoodsngo.html

[D15] 去重
来源：http://dali.haohaochexian.top/Article/details/gteqdxresw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cqqwz.cn/Article/details/gtotizfwyr.html

PHP:  array_unique($arr);
来源：http://dali.dianchejie.cn/Article/details/gthnuvkzle.html

JS:   [...new Set(arr)]
来源：http://dali.pycfn.com/Article/details/gthdkikrtv.html

TS:   [...new Set(arr)]
来源：http://dali.cashguo.top/Article/details/gtsijbifga.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhoulong.xyz/Article/details/gtnynwggoh.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shanyushiyangtech.top/Article/details/gtshgawpwd.html

Ruby: arr.uniq
来源：http://dali.fzhhl.top/Article/details/gthyobvwee.html

C#:   list.Distinct().ToList()
来源：http://dali.smart0.xyz/Article/details/gtitrmbmxz.html

[D16] 求和与平均值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsuunisnv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cqqwz.cn/Article/details/gtyrtbrsjx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yvedp.cn/Article/details/gtwrjjojoy.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.snrcjt.cn/Article/details/gtvpiyatgx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tian-w.cn/Article/details/gtysdyqcfo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yonumen.top/Article/details/gtnewspkue.html

Go:   // 手写循环累加
来源：http://dali.gaohongyu789.top/Article/details/gtmgpmgppy.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yangfankeji.com/Article/details/gtezcbfcbn.html

C#:   list.Sum();  list.Average()
来源：http://dali.jinghuilouyu.cn/Article/details/gtnpkadthm.html

[D17] 最大值与最小值
来源：http://dali.birdmap.top/Article/details/gtkxvkpped.html

Py:   max(arr);  min(arr)
来源：http://dali.jqgfzy.top/Article/details/gtdqrbaahe.html

PHP:  max($arr);  min($arr);
来源：http://dali.cqqwz.cn/Article/details/gtiedildwu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtpipbwheh.html

TS:   Math.max(...arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtspuvqmtg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.kuanghao11.cn/Article/details/gtvmwsoizo.html


<!-- 参考信息 -->