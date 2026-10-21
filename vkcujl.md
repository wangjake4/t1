代发 wailian999

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtrdqklnqn.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.gaohongyu789.top/Article/details/gtiucpabyo.html

Ruby: def add(a, b); a + b; end
来源：http://dali.havefunace.top/Article/details/gtuydxecbk.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gthtpktuyf.html

[C02] 默认参数
来源：http://dali.dashuyun.cn/Article/details/gteeioyzhu.html

Py:   def greet(name="World"): return name
来源：http://dali.yongpay.top/Article/details/gtefuqsgjs.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yj202588.top/Article/details/gtquyunaza.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.aibaodan.cn/Article/details/gtiblzxfvu.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hammf.cn/Article/details/gtgcpiypqc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.bjfxy.top/Article/details/gtbnpnoukl.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gtizveewtd.html

Ruby: def greet(name = "World") = name
来源：http://dali.yanxiufei.cn/Article/details/gtcrqynpkj.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.birdmap.top/Article/details/gttonqwwxw.html

[C03] 可变参数
来源：http://dali.gzhubu.top/Article/details/gtbdzcehrs.html

Py:   def total(*args): return sum(args)
来源：http://dali.ydzc1.top/Article/details/gtdkciqpff.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jqgfzy.top/Article/details/gttzuliybe.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cashguo.top/Article/details/gtadsbcret.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfftncayq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.gaohongyu789.top/Article/details/gtbtsjxddc.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jqgufenzy.top/Article/details/gtpdwmsayc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hnqzz.top/Article/details/gtulcpfbwe.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.aizwys.cn/Article/details/gtuvuhtyjc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.xziqi.cn/Article/details/gtyojsbkcl.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ehwqpu.com/Article/details/gtkyygrual.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shangyingyoupin.top/Article/details/gtpooylvia.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.tianlin.xyz/Article/details/gtayctwujy.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jinghuilouyu.cn/Article/details/gtlbuhwwlu.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yuanzhike.top/Article/details/gtwlwxpdcw.html

Go:   // 无：用配置结构体参数
来源：http://dali.smart0.xyz/Article/details/gtudpcetne.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmtwsynoc.html

C#:   f(a: 1, b: 2)
来源：http://dali.zdqjudy.top/Article/details/gtkcmzgbgg.html

[C05] 返回多个值
来源：http://dali.jinghuilouyu.cn/Article/details/gtmbrapsgj.html

Py:   return a, b
来源：http://dali.jqgfzy.top/Article/details/gtpbdbeddn.html

PHP:  return [$a, $b];
来源：http://dali.shuidangran.top/Article/details/gtpfvibabj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.iojbl.cn/Article/details/gtqcwtfunl.html

TS:   return { a, b };
来源：http://dali.xinyue.icu/Article/details/gtcytbqumz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hnqzz.top/Article/details/gtndjnpzys.html

Go:   return a, b
来源：http://dali.yj20258.top/Article/details/gtpvntizjy.html

Ruby: return a, b
来源：http://dali.yj20258.top/Article/details/gtnnfhrlit.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.haohaochexian.top/Article/details/gtvdkienvp.html

[C06] 匿名函数 / lambda
来源：http://dali.ehwqpu.com/Article/details/gttmgzgvho.html

Py:   square = lambda x: x * x
来源：http://dali.ehwqpu.com/Article/details/gtlmviinvw.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtimroecor.html

JS:   const square = x => x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gtiwfihlsa.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.feifeiyinyue.top/Article/details/gtfqntpgog.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.nanxuanxn.top/Article/details/gtjzhrhtko.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shuidangran.top/Article/details/gtvdkqmrwv.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yj20258.top/Article/details/gtlwapaasw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.guowangkeji.top/Article/details/gtkhfnxeet.html

[C07] 把函数作为参数传入
来源：http://dali.nanxinkj.top/Article/details/gticxliuil.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.guannengcc.top/Article/details/gtajdacplx.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yuxming.cn/Article/details/gtsskdkhfe.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpspkziqf.html

TS:   arr.map(String)
来源：http://dali.daria6918.cn/Article/details/gtuqkoyntp.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jyoumei.cn/Article/details/gtersuihfq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.feifeiyinyue.top/Article/details/gtxvcvrxdx.html

Ruby: arr.map(&:upcase)
来源：http://dali.jiagoushi.top/Article/details/gtveoiwewd.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jiagoushi.top/Article/details/gtycysnkgl.html

[C08] 闭包
来源：http://dali.yongpay.top/Article/details/gthmwktenx.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xuanzx.com/Article/details/gtbkbzhhcm.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.pycfn.com/Article/details/gtbeehlkns.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cdnleiting.top/Article/details/gtatxxvzrc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.316326.xyz/Article/details/gtaiupmlnu.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhengqikj.top/Article/details/gteeasjaoz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.daxiang520.top/Article/details/gtpobnbjwe.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jinqigfzy.top/Article/details/gtlrdckdnr.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.wangshuangyany.cn/Article/details/gttnuzovgp.html

[C09] 递归
来源：http://dali.0kj1m.cn/Article/details/gtpsuwgraq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yj20258888.top/Article/details/gtnryhbvyv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhongyouzk.top/Article/details/gtphxdkfiv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhixingplan.top/Article/details/gtbkrlhiyp.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.quarkkingdee.top/Article/details/gttqgkvwah.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.mhx1999.top/Article/details/gtenwtmxjf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cqqwz.cn/Article/details/gtgsurhkws.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.chenlongwang.top/Article/details/gtwjzwkxsd.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hammf.cn/Article/details/gtuelqbmhe.html

[C10] 变量作用域
来源：http://dali.redwolf501.top/Article/details/gtqexpwzch.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cucudq.cn/Article/details/gtgqezfkuy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yj20258.top/Article/details/gtwzbxllli.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.sufxvd.cn/Article/details/gtcnvdtncl.html

TS:   同 JS
来源：http://dali.jinqigufen.top/Article/details/gtmrsyanpi.html

Java: 方法内为块级作用域
来源：http://dali.chenzaomai.com/Article/details/gtrzvjubkk.html

Go:   花括号块级作用域
来源：http://dali.andypj.xyz/Article/details/gteljjoqsz.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.smart0.xyz/Article/details/gtsmwbbhui.html

C#:   块级作用域
来源：http://dali.jinqigfzy.top/Article/details/gtfwnhcsab.html

[C11] 模块导入与导出
来源：http://dali.svipenyu.cn/Article/details/gtkejcpvpn.html

Py:   from module import func
来源：http://dali.ivvv.top/Article/details/gtmwfqlluz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ppjwa.cn/Article/details/gtdvorggah.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hywenlv.cn/Article/details/gtxrxlegzd.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gtpotejkul.html

Java: import java.util.List;
来源：http://dali.meibo888.top/Article/details/gtzhibqkxw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.smart0.xyz/Article/details/gtcbdwqmxi.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xuanzx.com/Article/details/gtumwrcoaa.html

C#:   using System.Text;
来源：http://dali.zhengqikj.top/Article/details/gtyiojiiyv.html

[C12] 立即执行函数 IIFE
来源：http://dali.zycfv.cn/Article/details/gtiyzccogh.html

Py:   (lambda: print("run"))()
来源：http://dali.jqgfzy.top/Article/details/gtqalfjurw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yvedp.cn/Article/details/gtxfmmffhp.html

JS:   (() => { console.log("run"); })();
来源：http://dali.daxiang520.top/Article/details/gtgtqqikar.html

TS:   (() => { console.log("run"); })();
来源：http://dali.guowangkeji.top/Article/details/gtagushdoj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.0kj1m.cn/Article/details/gtxsbsmmoi.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.nanxuanxn.top/Article/details/gtvquphezz.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhiwuduotai.top/Article/details/gtmefjsxfr.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtplhbvwnn.html

[C13] 类型声明 / 类型注解
来源：http://dali.jlsjyb.cn/Article/details/gtorlvdroe.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.9152youxi.cn/Article/details/gtehexgmmy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xylfe.cn/Article/details/gtmtphugct.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cdnleiting.top/Article/details/gtvtewupof.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtmppsgkpp.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ivvv.top/Article/details/gtgaztfnon.html

Go:   func add(a, b int) int
来源：http://dali.chenzaomai.com/Article/details/gtiwfeebti.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sweek.top/Article/details/gtkyyudqya.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yj20258.top/Article/details/gtwoyzisuo.html

[C14] 泛型函数
来源：http://dali.jqgufenzy.top/Article/details/gtdatsxjny.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cqqwz.cn/Article/details/gthribyjob.html

PHP:  // 无泛型
来源：http://dali.hfpthk.cn/Article/details/gtvcwqzbcn.html

JS:   // 无泛型
来源：http://dali.hongshengwenyu.top/Article/details/gtiognxnpo.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hysaishi.cn/Article/details/gtopdsdvxd.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.andypj.xyz/Article/details/gtgdzultbd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.tianlin.xyz/Article/details/gtqtfyvurl.html

Ruby: # 无泛型
来源：http://dali.shuidangran.top/Article/details/gtkomrjcwn.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.bjfxy.top/Article/details/gtnbbkiuvq.html

[C15] 解构 / 展开参数
来源：http://dali.ybcxt.top/Article/details/gtlwqxqobu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlheyjjej.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkomoigol.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.haohaochexian.top/Article/details/gtsrvhtvby.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xinyue.icu/Article/details/gtumkloubs.html

Java: // 无解构
来源：http://dali.snrcjt.cn/Article/details/gtpnrqueex.html

Go:   // 无解构
来源：http://dali.cqqwz.cn/Article/details/gtmnvlsjmw.html

Ruby: a, b = pair
来源：http://dali.quarkkingdee.top/Article/details/gtgzzxjilw.html

C#:   var (a, b) = pair;
来源：http://dali.hongshengwenyu.top/Article/details/gtroguxhwt.html

[C16] 函数 / 方法重载
来源：http://dali.gotoacloud.top/Article/details/gtdcbqgluu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.aizwys.cn/Article/details/gtyoewqbvx.html

PHP:  // 无重载
来源：http://dali.jianghu66.top/Article/details/gtnzjixepm.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.guowangkeji.top/Article/details/gtfnlsbjhn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.guowangkeji.top/Article/details/gtakhldsuk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhixingplan.top/Article/details/gtemwsgkmq.html

Go:   // 无重载：用不同函数名
来源：http://dali.guowangkeji.top/Article/details/gtiytdaiip.html

Ruby: # 无重载：靠动态参数
来源：http://dali.birdmap.top/Article/details/gtuwxkmzrn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cucudq.cn/Article/details/gtbcqnalzp.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtxjgsavuq.html

D. 数组 / 列表 / 集合
来源：http://dali.gogol.net.cn/Article/details/gtcfwoidjq.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtaintwxfs.html

[D01] 创建数组 / 列表
来源：http://dali.9152youxi.cn/Article/details/gtedytievn.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xinyue.icu/Article/details/gtpmprjmmq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.smart0.xyz/Article/details/gtwjftzqsh.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.quarkkingdee.top/Article/details/gtvolqymvv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.redwolf501.top/Article/details/gtypskklww.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shzxlz.cn/Article/details/gtpuuhgisf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbbgkebrc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.c1oappe.top/Article/details/gtdsmfhwmb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yj20258.top/Article/details/gtjamtedaz.html

[D02] 追加元素到末尾
来源：http://dali.cheryme.top/Article/details/gtuovnsoyo.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhoulong.xyz/Article/details/gtcezpduri.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hywenlv.cn/Article/details/gthscxstnm.html

JS:   arr.push(4);
来源：http://dali.chenzaomai.com/Article/details/gtfqotuwsk.html

TS:   arr.push(4);
来源：http://dali.pengpengdd.cyou/Article/details/gtuutgzprh.html

Java: list.add(4);
来源：http://dali.iojbl.cn/Article/details/gtjhxsmpbv.html

Go:   arr = append(arr, 4)
来源：http://dali.hammf.cn/Article/details/gtfytbnwwu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cucudq.cn/Article/details/gtytawwgjy.html

C#:   list.Add(4);
来源：http://dali.daxiang520.top/Article/details/gtwujhvpec.html

[D03] 在指定位置插入元素
来源：http://dali.gzhubu.top/Article/details/gtiwjktjfa.html

Py:   arr.insert(0, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtchwfsyyu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ydzc1.top/Article/details/gtpmgjprtd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hnqzz.top/Article/details/gtbfzxomfh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yonumen.top/Article/details/gtiyrjdikb.html

Java: list.add(0, 0);
来源：http://dali.jqgfzy.top/Article/details/gtcquicjdp.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yj20258.top/Article/details/gtiinhphae.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xylfe.cn/Article/details/gtdfkydnpy.html

C#:   list.Insert(0, 0);
来源：http://dali.dianchejie.cn/Article/details/gtgwqgbqsu.html

[D04] 删除元素
来源：http://dali.yuanzhike.top/Article/details/gtlklnjtim.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.chenlongwang.top/Article/details/gtaszuigsv.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jiagoushi.top/Article/details/gtxxrfkcdc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cqqwz.cn/Article/details/gtbsfanlao.html

TS:   arr.splice(0, 1);
来源：http://dali.chenlongwang.top/Article/details/gtqhewasdr.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.aibaodan.cn/Article/details/gthcsvmfee.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.haohaochexian.top/Article/details/gtfwijcfhy.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cucudq.cn/Article/details/gtkjneesyk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.dianchejie.cn/Article/details/gtvnwygbfp.html

[D05] 访问与修改元素
来源：http://dali.wangdashe.top/Article/details/gtkrjpifsb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hongshengwenyu.top/Article/details/gtozgwrrbi.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.meibo888.top/Article/details/gtmyffavcq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jianghu66.top/Article/details/gtlssoxddr.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ivvv.top/Article/details/gtadpeueif.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yj202588.top/Article/details/gtqymhohbv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.redwolf501.top/Article/details/gtleuxccgn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnqzz.top/Article/details/gtzkfgclme.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.meibo888.top/Article/details/gtpguzgqlf.html

[D06] 数组长度
来源：http://dali.wangdashe.top/Article/details/gtnduhpnab.html

Py:   len(arr)
来源：http://dali.yuxming.cn/Article/details/gtaiykzgut.html

PHP:  count($arr);
来源：http://dali.ppjwa.cn/Article/details/gtnvewnyvi.html

JS:   arr.length
来源：http://dali.andypj.xyz/Article/details/gtjijofxxv.html

TS:   arr.length
来源：http://dali.sxryk.cn/Article/details/gtgknavhnq.html

Java: list.size();
来源：http://dali.hammf.cn/Article/details/gtxitxrvug.html

Go:   len(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gttspjhquw.html

Ruby: arr.length; arr.size
来源：http://dali.ivvv.top/Article/details/gtvcwcgrnv.html

C#:   list.Count;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsshrquob.html

[D07] 切片 / 取子数组
来源：http://dali.aizwys.cn/Article/details/gtvcygnxov.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.tianlin.xyz/Article/details/gtgrulnvhv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.fengsongda.top/Article/details/gtsztrdgel.html

JS:   arr.slice(1, 4);
来源：http://dali.svipenyu.cn/Article/details/gtmfmqjrqx.html

TS:   arr.slice(1, 4);
来源：http://dali.jqgfzy.top/Article/details/gtqemptoin.html

Java: list.subList(1, 4);
来源：http://dali.jiagoushi.top/Article/details/gttmzvnuvx.html

Go:   arr[1:4]
来源：http://dali.haohaochexian.top/Article/details/gtjjszxvyo.html

Ruby: arr[1, 3]
来源：http://dali.yj202588.top/Article/details/gtwrssxiqw.html

C#:   list.GetRange(1, 3);
来源：http://dali.jiagoushi.top/Article/details/gtrspwzwrc.html

[D08] 合并两个数组
来源：http://dali.hnqzz.top/Article/details/gtjiwhaalc.html

Py:   a + b;  a.extend(b)
来源：http://dali.feifeiyinyue.top/Article/details/gtoecdujic.html

PHP:  array_merge($a, $b);
来源：http://dali.tianlin.xyz/Article/details/gtpuarzvht.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.bjfxy.top/Article/details/gtudtptfzh.html

TS:   [...a, ...b];
来源：http://dali.jianghu66.top/Article/details/gtdwzwtwdo.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtqydxjkvu.html

Go:   append(a, b...)
来源：http://dali.tian-w.cn/Article/details/gtdodtkogh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.tanke756.top/Article/details/gtbkjumqtk.html

C#:   a.Concat(b).ToList()
来源：http://dali.yj202588.top/Article/details/gtmfswdfrq.html

[D09] 排序（升序）
来源：http://dali.cqqwz.cn/Article/details/gtkycmypsl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hfpthk.cn/Article/details/gtvmncwylk.html

PHP:  sort($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtubotsocx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jqgfzy.top/Article/details/gtxdyqjqib.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yj20258.top/Article/details/gtmqpnifyx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.pycfn.com/Article/details/gtzdlljkgn.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtmfdxkiok.html

Ruby: arr.sort
来源：http://dali.jyoumei.cn/Article/details/gtqzctogmb.html

C#:   list.Sort();
来源：http://dali.jqgfzy.top/Article/details/gtklhqclsf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.mhx1999.top/Article/details/gtgkrgxonp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zdqjudy.top/Article/details/gtrtgeozof.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zycfv.cn/Article/details/gtycwuwtwd.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinqigfzy.top/Article/details/gtcetcacde.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hywenlv.cn/Article/details/gtnumylxhv.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hammf.cn/Article/details/gtqkrqpguy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.tanke756.top/Article/details/gtdnzzyxux.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gotoacloud.top/Article/details/gtarlrqcju.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gogol.net.cn/Article/details/gtvqqguiuq.html

[D11] 反转数组
来源：http://dali.hnxiangtu.top/Article/details/gtofqmrdld.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.pengpengdd.cyou/Article/details/gtjijmncbi.html

PHP:  array_reverse($arr);
来源：http://dali.jianghu66.top/Article/details/gtfvnobqmw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shzxlz.cn/Article/details/gtapamscfq.html

TS:   [...arr].reverse();
来源：http://dali.gotoacloud.top/Article/details/gtwamchzsa.html

Java: Collections.reverse(list);
来源：http://dali.tanke756.top/Article/details/gthvitxfkk.html

Go:   slices.Reverse(arr)
来源：http://dali.fzhhl.top/Article/details/gtthkqdjiw.html

Ruby: arr.reverse
来源：http://dali.fzhhl.top/Article/details/gtfheaaokb.html

C#:   list.Reverse();
来源：http://dali.yuxming.cn/Article/details/gtkkwxlrzj.html

[D12] 查找元素下标
来源：http://dali.yuxming.cn/Article/details/gtxqdjymke.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhiwuduotai.top/Article/details/gtnukyukup.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.fzhhl.top/Article/details/gtkbfroixy.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtezxzhdnk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgfzy.top/Article/details/gtqjvojluf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.wangdashe.top/Article/details/gtfzpsegep.html

Go:   slices.Index(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtvdnlafrk.html

Ruby: arr.index(x)
来源：http://dali.jinqigufen.top/Article/details/gtcrahziij.html

C#:   list.IndexOf(x);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfbhikzex.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zdqjudy.top/Article/details/gtkhynzqst.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xinyue.icu/Article/details/gtsmnugzsv.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nanxuanxn.top/Article/details/gtjnfqaqfw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.wangdashe.top/Article/details/gtwgngsowt.html

TS:   arr.filter(x => x > 3)
来源：http://dali.sxryk.cn/Article/details/gtfjwgnwzp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sufxvd.cn/Article/details/gtqhwoqqgh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.vqdsnc.cn/Article/details/gtesskwuoc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yueranfly.top/Article/details/gtdtrkdntn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtqcnalmdy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zdqjudy.top/Article/details/gtiswjyanq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.sxryk.cn/Article/details/gtvrslhvdl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtkklhlayd.html

JS:   arr.map(x => x * 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtiqgidbnv.html

TS:   arr.map(x => x * 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpxzslqrq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jqgfzy.top/Article/details/gttrcowbvx.html

Go:   // 手写循环
来源：http://dali.shzxlz.cn/Article/details/gtninohruq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.fzhhl.top/Article/details/gtdheeobjz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtdkiwnpex.html

[D15] 去重
来源：http://dali.tanke756.top/Article/details/gtzawuldlh.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinqigfzy.top/Article/details/gtanekzpsh.html

PHP:  array_unique($arr);
来源：http://dali.havefunace.top/Article/details/gtmdktsjyr.html

JS:   [...new Set(arr)]
来源：http://dali.vqdsnc.cn/Article/details/gtvexerqlu.html

TS:   [...new Set(arr)]
来源：http://dali.wangshuangyany.cn/Article/details/gtzbuvqiey.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hnxiangtu.top/Article/details/gteuhcsgka.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.guannengcc.top/Article/details/gtdkhpbeca.html

Ruby: arr.uniq
来源：http://dali.chenjidiqi.icu/Article/details/gtmtthjmgr.html

C#:   list.Distinct().ToList()
来源：http://dali.gzhubu.top/Article/details/gtdxqiuafs.html

[D16] 求和与平均值
来源：http://dali.sxryk.cn/Article/details/gtysvqrztq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.mhx1999.top/Article/details/gttnhfdwjf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.fzhhl.top/Article/details/gtrbstfgsx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfpjicwzh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hywenlv.cn/Article/details/gtcorbzhcz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cheryme.top/Article/details/gtfsccvfvi.html

Go:   // 手写循环累加
来源：http://dali.cheryme.top/Article/details/gtzdhpwbfi.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.9152youxi.cn/Article/details/gtzghfunhw.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhixingplan.top/Article/details/gtjeiqfpnv.html

[D17] 最大值与最小值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtroiycudi.html

Py:   max(arr);  min(arr)
来源：http://dali.cdnleiting.top/Article/details/gtopphakrj.html

PHP:  max($arr);  min($arr);
来源：http://dali.guannengcc.top/Article/details/gtlivnfjnm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hnqzz.top/Article/details/gtdqxjjpvw.html

TS:   Math.max(...arr);
来源：http://dali.iojbl.cn/Article/details/gtqixtprez.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.aizwys.cn/Article/details/gtmkybkdup.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.guowangkeji.top/Article/details/gtqmjjdbpz.html

Ruby: arr.max;  arr.min
来源：http://dali.zhixingplan.top/Article/details/gtzpbxqolz.html

C#:   list.Max();  list.Min()
来源：http://dali.yueranfly.top/Article/details/gtbfobjawf.html

[D18] 扁平化嵌套数组
来源：http://dali.guannengcc.top/Article/details/gtfqqkihbt.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.haohaochexian.top/Article/details/gtkimkvgkv.html

PHP:  array_merge(...$nested);
来源：http://dali.guannengcc.top/Article/details/gtxfdmmgqk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.fengsongda.top/Article/details/gtzwwhnlrg.html

TS:   nested.flat();
来源：http://dali.zhoulong.xyz/Article/details/gtsojbrcpg.html


<!-- 参考信息 -->