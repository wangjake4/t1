代发 wailian999

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gogol.net.cn/Article/details/gt2rnfvzdjl.html

Java: x instanceof Number
来源：http://dali.aibaodan.cn/Article/details/gt2xmwmxmxr.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yueranfly.top/Article/details/gt2qjaywpxc.html

Ruby: x.is_a?(Numeric)
来源：http://dali.guowangkeji.top/Article/details/gt2egctkrsp.html

C#:   x is int or double or decimal
来源：http://dali.shangyingyoupin.top/Article/details/gt2qfncyodl.html

[B14] 判断值是否在集合内
来源：http://dali.svipenyu.cn/Article/details/gt2ibmevqlz.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.chenzaomai.com/Article/details/gt2watukjan.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.cucudq.cn/Article/details/gt2avwshicd.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yfhuexxg.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.gzhubu.top/Article/details/gt2jxrhelze.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.c1oappe.top/Article/details/gt2fqcnbnoa.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.smart0.xyz/Article/details/gt2ijligesu.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.sweek.top/Article/details/gt2ensdgvbg.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.0kj1m.cn/Article/details/gt2doaouujw.html

[B15] 布尔运算与取反
来源：http://dali.hnqzz.top/Article/details/gt2gvwcshiw.html

Py:   a and b or not c
来源：http://dali.shanyushiyangtech.top/Article/details/gt2orcuimlk.html

PHP:  $a && $b || !$c
来源：http://dali.tian-w.cn/Article/details/gt2anckqoye.html

JS:   a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gt2vjuzxgzx.html

TS:   a && b || !c
来源：http://dali.gzhubu.top/Article/details/gt2nzputqgm.html

Java: a && b || !c
来源：http://dali.c1oappe.top/Article/details/gt2gddfddij.html

Go:   a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gt2brjnnolt.html

Ruby: a && b || !c
来源：http://dali.xinyue.icu/Article/details/gt2qufshfcc.html

C#:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gt2ezeedvzn.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.smart0.xyz/Article/details/gt2udrmhmbb.html

Py:   if not data: return
来源：http://dali.gotoacloud.top/Article/details/gt2lbbansxm.html

PHP:  if (!$data) { return; }
来源：http://dali.jinqigfzy.top/Article/details/gt2ikqqdzog.html

JS:   if (!data) return;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uxvrcyra.html

TS:   if (!data) return;
来源：http://dali.sysykeji.top/Article/details/gt2hrnfxdsm.html

Java: if (data == null) return;
来源：http://dali.hnxiangtu.top/Article/details/gt2ufncucqr.html

Go:   if data == nil { return }
来源：http://dali.yvedp.cn/Article/details/gt2oeuktbyx.html

Ruby: return if data.nil?
来源：http://dali.zdqjudy.top/Article/details/gt2kxldaebk.html

C#:   if (data == null) return;
来源：http://dali.meibo888.top/Article/details/gt2fcfacpis.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2qyrocmnu.html

C. 函数与作用域
来源：http://dali.hysaishi.cn/Article/details/gt2annfbbsp.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2zfriwcmh.html

[C01] 定义函数
来源：http://dali.fzhhl.top/Article/details/gt2wfvfxkqm.html

Py:   def add(a, b): return a + b
来源：http://dali.jyoumei.cn/Article/details/gt2vpmjbhpb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnxiangtu.top/Article/details/gt2wghkizwz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2bchrhytw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gt2pcsteggk.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gt2tdrpmkoe.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yonumen.top/Article/details/gt2feqipyuv.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2uqmuypfa.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gt2mxcwpdud.html

[C02] 默认参数
来源：http://dali.sxryk.cn/Article/details/gt2upwshnpg.html

Py:   def greet(name="World"): return name
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bhqttmak.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2wlefnzgn.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.sysykeji.top/Article/details/gt2hrmgcgja.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ibnlpahh.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.dianchejie.cn/Article/details/gt2nkaszeuk.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yanxiufei.cn/Article/details/gt2ajjciiqg.html

Ruby: def greet(name = "World") = name
来源：http://dali.yvedp.cn/Article/details/gt2zbcboguy.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.andypj.xyz/Article/details/gt2jrpojcgj.html

[C03] 可变参数
来源：http://dali.aizwys.cn/Article/details/gt2lamvurut.html

Py:   def total(*args): return sum(args)
来源：http://dali.yueranfly.top/Article/details/gt2cvajndqn.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yanxiufei.cn/Article/details/gt2fwsthlbt.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhixingplan.top/Article/details/gt2cooqqsew.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zdqjudy.top/Article/details/gt2qjltnlhr.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.redwolf501.top/Article/details/gt2eeakgmqr.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ppjwa.cn/Article/details/gt2pnmmmomx.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.aibaodan.cn/Article/details/gt2uwgtclll.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jlsjyb.cn/Article/details/gt2dmujwipm.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jyoumei.cn/Article/details/gt2xlzhiysn.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.fzhhl.top/Article/details/gt2txtmdysb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yongpay.top/Article/details/gt2tcquclob.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.meibo888.top/Article/details/gt2mswbxvjk.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.smart0.xyz/Article/details/gt2gnzvgpxn.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ubunomev.html

Go:   // 无：用配置结构体参数
来源：http://dali.cdnleiting.top/Article/details/gt2rsnsuouy.html

Ruby: f(a: 1, b: 2)
来源：http://dali.meibo888.top/Article/details/gt2jogpnbnh.html

C#:   f(a: 1, b: 2)
来源：http://dali.yvedp.cn/Article/details/gt2snjlvfbw.html

[C05] 返回多个值
来源：http://dali.cashguo.top/Article/details/gt2qfrscdjc.html

Py:   return a, b
来源：http://dali.meibo888.top/Article/details/gt2bibzqywo.html

PHP:  return [$a, $b];
来源：http://dali.xinyue.icu/Article/details/gt2clpwvhul.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jqgfzy.top/Article/details/gt2hkiandjw.html

TS:   return { a, b };
来源：http://dali.jqgufenzy.top/Article/details/gt2rhsfsuvj.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cdnleiting.top/Article/details/gt2ljbqglmf.html

Go:   return a, b
来源：http://dali.sweek.top/Article/details/gt2snzlzohr.html

Ruby: return a, b
来源：http://dali.xinyue.icu/Article/details/gt2jbjwujpc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.pengpengdd.cyou/Article/details/gt2idrzbssz.html

[C06] 匿名函数 / lambda
来源：http://dali.redwolf501.top/Article/details/gt2mawchxzi.html

Py:   square = lambda x: x * x
来源：http://dali.ehwqpu.com/Article/details/gt2bntgfobg.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jyoumei.cn/Article/details/gt2enalzvkr.html

JS:   const square = x => x * x;
来源：http://dali.redwolf501.top/Article/details/gt2isshxfnb.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.nanxinkj.top/Article/details/gt2anncnirl.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.bjfxy.top/Article/details/gt2ngpgnzri.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.tianlin.xyz/Article/details/gt2pgschoai.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yonumen.top/Article/details/gt2tujpnqew.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kdgmbaxc.html

[C07] 把函数作为参数传入
来源：http://dali.tanke756.top/Article/details/gt2szjewowb.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwzqcdf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sweek.top/Article/details/gt2sqslqqpt.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hnxiangtu.top/Article/details/gt2kxugqclx.html

TS:   arr.map(String)
来源：http://dali.cdnleiting.top/Article/details/gt2gdowegop.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mjfmhygm.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.pycfn.com/Article/details/gt2vhamwtfr.html

Ruby: arr.map(&:upcase)
来源：http://dali.gzhubu.top/Article/details/gt2nrhzgpeb.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.sweek.top/Article/details/gt2zykpcoco.html

[C08] 闭包
来源：http://dali.wangshuangyany.cn/Article/details/gt2qedpuopx.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.nwbrower.top/Article/details/gt2tkxyvelr.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinqigfzy.top/Article/details/gt2zzbkbdwq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.0kj1m.cn/Article/details/gt2ezfvmuec.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.tian-w.cn/Article/details/gt2nvgfimwg.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cqcbecwu.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.wangdashe.top/Article/details/gt2hashoxsg.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jiagoushi.top/Article/details/gt2hytboxwm.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ivvv.top/Article/details/gt2aohickgk.html

[C09] 递归
来源：http://dali.gotoacloud.top/Article/details/gt2swgrqjmb.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.guannengcc.top/Article/details/gt2zwyotxuh.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.haohaochexian.top/Article/details/gt2niowsbbo.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.smart0.xyz/Article/details/gt2wobzoavf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2srrjwrgr.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.0kj1m.cn/Article/details/gt2qltgfmql.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.gaohongyu789.top/Article/details/gt2aqdmilck.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhixingplan.top/Article/details/gt2sojnarvc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.aizwys.cn/Article/details/gt2epgdumkc.html

[C10] 变量作用域
来源：http://dali.smart0.xyz/Article/details/gt2qbpjswgj.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hnxiangtu.top/Article/details/gt2hxsbhfic.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cqqwz.cn/Article/details/gt2dxfnxmtl.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cheryme.top/Article/details/gt2oirgimem.html

TS:   同 JS
来源：http://dali.havefunace.top/Article/details/gt2vxfmlbgy.html

Java: 方法内为块级作用域
来源：http://dali.hfpthk.cn/Article/details/gt2txrcdotb.html

Go:   花括号块级作用域
来源：http://dali.0kj1m.cn/Article/details/gt2vzvpyfhl.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2zjghflqe.html

C#:   块级作用域
来源：http://dali.daria6918.cn/Article/details/gt2tjrdfosn.html

[C11] 模块导入与导出
来源：http://dali.ppjwa.cn/Article/details/gt2uqdcgdma.html

Py:   from module import func
来源：http://dali.sweek.top/Article/details/gt2bdpizcgu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.iojbl.cn/Article/details/gt2aqondcyp.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yongpay.top/Article/details/gt2brkddscx.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ehwqpu.com/Article/details/gt2xteqsfdm.html

Java: import java.util.List;
来源：http://dali.fzhhl.top/Article/details/gt2upwkazvm.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hongshengwenyu.top/Article/details/gt2fkpeddzm.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.smart0.xyz/Article/details/gt2caldokts.html

C#:   using System.Text;
来源：http://dali.bjfxy.top/Article/details/gt2rbrzgmuo.html

[C12] 立即执行函数 IIFE
来源：http://dali.jinqigufen.top/Article/details/gt2cirvuibo.html

Py:   (lambda: print("run"))()
来源：http://dali.hysaishi.cn/Article/details/gt2gqmzbflv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.c1oappe.top/Article/details/gt2pajeisfd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ehwqpu.com/Article/details/gt2myabgtao.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ydzc1.top/Article/details/gt2giryqylm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yanxiufei.cn/Article/details/gt2mrsdlznl.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.daria6918.cn/Article/details/gt2zxqvkefb.html

Ruby: -> { puts "run" }.call
来源：http://dali.sysykeji.top/Article/details/gt2kgvjccbg.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gzhubu.top/Article/details/gt2tddivgnx.html

[C13] 类型声明 / 类型注解
来源：http://dali.redwolf501.top/Article/details/gt2ofyekxzw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhengqikj.top/Article/details/gt2ktftzdmi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dianchejie.cn/Article/details/gt2lafhwlmi.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xylfe.cn/Article/details/gt2unosenqv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gt2rjuwxxdx.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2arqpmucg.html

Go:   func add(a, b int) int
来源：http://dali.cdnleiting.top/Article/details/gt2jhkkxazz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cdnleiting.top/Article/details/gt2iphnnigd.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xinyue.icu/Article/details/gt2brapfmui.html

[C14] 泛型函数
来源：http://dali.xylfe.cn/Article/details/gt2bivmbsrg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.birdmap.top/Article/details/gt2rfuxiaow.html

PHP:  // 无泛型
来源：http://dali.snrcjt.cn/Article/details/gt2ivrsliqq.html

JS:   // 无泛型
来源：http://dali.hnqzz.top/Article/details/gt2lrrcktds.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.wangdashe.top/Article/details/gt2dbnwjgzm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.guowangkeji.top/Article/details/gt2kpneozqh.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.birdmap.top/Article/details/gt2wuuvyugu.html

Ruby: # 无泛型
来源：http://dali.gzhubu.top/Article/details/gt2yzxiklkn.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.haohaochexian.top/Article/details/gt2zxaftctv.html

[C15] 解构 / 展开参数
来源：http://dali.316326.xyz/Article/details/gt2jicseegu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zdqjudy.top/Article/details/gt2zmbnbwda.html

PHP:  [$a, $b] = $pair;
来源：http://dali.guowangkeji.top/Article/details/gt2nrwjahte.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.0kj1m.cn/Article/details/gt2rmsvqvqj.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2eofbgkkp.html

Java: // 无解构
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fmjdhiob.html

Go:   // 无解构
来源：http://dali.9152youxi.cn/Article/details/gt2wnfvtmsk.html

Ruby: a, b = pair
来源：http://dali.snrcjt.cn/Article/details/gt2vsbrgdic.html

C#:   var (a, b) = pair;
来源：http://dali.svipenyu.cn/Article/details/gt2zxqcwbse.html

[C16] 函数 / 方法重载
来源：http://dali.meibo888.top/Article/details/gt2vxomssrj.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mxczfykw.html

PHP:  // 无重载
来源：http://dali.tianlin.xyz/Article/details/gt2djutaexn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cqqwz.cn/Article/details/gt2lgrhiadm.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.tian-w.cn/Article/details/gt2uvomltvr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sweek.top/Article/details/gt2abmkngwr.html

Go:   // 无重载：用不同函数名
来源：http://dali.hnxiangtu.top/Article/details/gt2imxhpvao.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jqgufenzy.top/Article/details/gt2qbnascjx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jiagoushi.top/Article/details/gt2wlrbqcgl.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2vqoitgjn.html

D. 数组 / 列表 / 集合
来源：http://dali.sufxvd.cn/Article/details/gt2tdvinbod.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2plmlvohf.html

[D01] 创建数组 / 列表
来源：http://dali.316326.xyz/Article/details/gt2vcqzgefo.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.chenjidiqi.icu/Article/details/gt2hugnrndd.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ehwqpu.com/Article/details/gt2yzmnwpsp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yj20258.top/Article/details/gt2nhcxvnby.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xuetiantiany.cn/Article/details/gt2ulswnrqe.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.sufxvd.cn/Article/details/gt2bkwvcqgr.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shzxlz.cn/Article/details/gt2duonxvhc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hongshengwenyu.top/Article/details/gt2wbpbjipm.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vexrelbo.html

[D02] 追加元素到末尾
来源：http://dali.tian-w.cn/Article/details/gt2ndbrqxgu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ivvv.top/Article/details/gt2zqpecryq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yuanzhike.top/Article/details/gt2ktstobca.html

JS:   arr.push(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hgeigfez.html

TS:   arr.push(4);
来源：http://dali.dianchejie.cn/Article/details/gt2kufelcys.html

Java: list.add(4);
来源：http://dali.guowangkeji.top/Article/details/gt2bnhugqhs.html

Go:   arr = append(arr, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qaqizrik.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yueranfly.top/Article/details/gt2tvpxgvog.html

C#:   list.Add(4);
来源：http://dali.quarkkingdee.top/Article/details/gt2qyveniep.html

[D03] 在指定位置插入元素
来源：http://dali.cashguo.top/Article/details/gt2pfrwiexd.html

Py:   arr.insert(0, 0)
来源：http://dali.ydzc1.top/Article/details/gt2lkvqdivp.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ydzc1.top/Article/details/gt2tcwipdzr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.birdmap.top/Article/details/gt2qbmsfteq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.aibaodan.cn/Article/details/gt2govsmayb.html

Java: list.add(0, 0);
来源：http://dali.quarkkingdee.top/Article/details/gt2pqscbhxj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mwzhixfu.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.sxryk.cn/Article/details/gt2fdpclbol.html

C#:   list.Insert(0, 0);
来源：http://dali.nwbrower.top/Article/details/gt2dpsirsdw.html

[D04] 删除元素
来源：http://dali.daria6918.cn/Article/details/gt2fssisucr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hfpthk.cn/Article/details/gt2mizijsvy.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.nanxinkj.top/Article/details/gt2kqhjqium.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cqqwz.cn/Article/details/gt2cfkqwtmt.html

TS:   arr.splice(0, 1);
来源：http://dali.mhx1999.top/Article/details/gt2lumbotdy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.meibo888.top/Article/details/gt2lolhsakd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.nanxinkj.top/Article/details/gt2ygkwpbqe.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xuanzx.com/Article/details/gt2iqsxdnfo.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.svipenyu.cn/Article/details/gt2sbgjtthn.html

[D05] 访问与修改元素
来源：http://dali.pengpengdd.cyou/Article/details/gt2uhvgddxs.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shuidangran.top/Article/details/gt2loqplpnr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gt2bqnxwvyi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hysaishi.cn/Article/details/gt2bfiktsav.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yuanzhike.top/Article/details/gt2jgwxyceq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.fengsongda.top/Article/details/gt2ixupetjl.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.fzhhl.top/Article/details/gt2gqbonmar.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hammf.cn/Article/details/gt2lyagssfk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhongyouzk.top/Article/details/gt2lpadxzyp.html

[D06] 数组长度
来源：http://dali.nanxinkj.top/Article/details/gt2biuadtrs.html

Py:   len(arr)
来源：http://dali.birdmap.top/Article/details/gt2cdtrgxdm.html

PHP:  count($arr);
来源：http://dali.zdqjudy.top/Article/details/gt2myljerop.html

JS:   arr.length
来源：http://dali.snrcjt.cn/Article/details/gt2vcapigxo.html

TS:   arr.length
来源：http://dali.pengpengdd.cyou/Article/details/gt2lbquvpfk.html

Java: list.size();
来源：http://dali.gogol.net.cn/Article/details/gt2bhaerpgh.html

Go:   len(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2xedpuzux.html

Ruby: arr.length; arr.size
来源：http://dali.redwolf501.top/Article/details/gt2atqssprv.html

C#:   list.Count;
来源：http://dali.yueranfly.top/Article/details/gt2vltdstye.html

[D07] 切片 / 取子数组
来源：http://dali.quarkkingdee.top/Article/details/gt2ngrczkem.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.chenlongwang.top/Article/details/gt2cwvqncxo.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xcikmfgl.html

JS:   arr.slice(1, 4);
来源：http://dali.gotoacloud.top/Article/details/gt2uajqjrpv.html

TS:   arr.slice(1, 4);
来源：http://dali.sxryk.cn/Article/details/gt2dwunnrpm.html

Java: list.subList(1, 4);
来源：http://dali.mhx1999.top/Article/details/gt2byhacniv.html

Go:   arr[1:4]
来源：http://dali.nwbrower.top/Article/details/gt2wyedvonx.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2nuaauvmi.html

C#:   list.GetRange(1, 3);
来源：http://dali.ivvv.top/Article/details/gt2qbfhpzga.html

[D08] 合并两个数组
来源：http://dali.zhoulong.xyz/Article/details/gt2expsgidj.html

Py:   a + b;  a.extend(b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bbxnzuhq.html

PHP:  array_merge($a, $b);
来源：http://dali.nanxinkj.top/Article/details/gt2ymcdcnoe.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mqitgzvm.html

TS:   [...a, ...b];
来源：http://dali.gotoacloud.top/Article/details/gt2nssirixn.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.gotoacloud.top/Article/details/gt2fonzigzx.html

Go:   append(a, b...)
来源：http://dali.gotoacloud.top/Article/details/gt2rmyhvpff.html

Ruby: a + b;  a.concat(b)
来源：http://dali.dashuyun.cn/Article/details/gt2vdxoxsqh.html

C#:   a.Concat(b).ToList()
来源：http://dali.tian-w.cn/Article/details/gt2znosvrll.html

[D09] 排序（升序）
来源：http://dali.c1oappe.top/Article/details/gt2mjgxqojv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oebhwrlt.html

PHP:  sort($arr);
来源：http://dali.shuidangran.top/Article/details/gt2absbdxnj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cdnleiting.top/Article/details/gt2zcqfcusj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ppjwa.cn/Article/details/gt2ighhfwof.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yueranfly.top/Article/details/gt2evbbahoe.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xkbnmbwp.html

Ruby: arr.sort
来源：http://dali.havefunace.top/Article/details/gt2kiphljsg.html

C#:   list.Sort();
来源：http://dali.guannengcc.top/Article/details/gt2xuefitqp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sxryk.cn/Article/details/gt2zdlawhoa.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cheryme.top/Article/details/gt2omvovkfs.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ewfndzkh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhongyouzk.top/Article/details/gt2corvlvmm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cashguo.top/Article/details/gt2ylpdvlfb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.aibaodan.cn/Article/details/gt2bukgdovn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.chenzaomai.com/Article/details/gt2svkixwtd.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cdynhwwp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zdqjudy.top/Article/details/gt2npivvtec.html

[D11] 反转数组
来源：http://dali.guowangkeji.top/Article/details/gt2bzwxcozi.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ybcxt.top/Article/details/gt2cynxczpy.html

PHP:  array_reverse($arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2qerljoot.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.kuanghao11.cn/Article/details/gt2ufvjjvjv.html

TS:   [...arr].reverse();
来源：http://dali.wangshuangyany.cn/Article/details/gt2dnlkkapt.html

Java: Collections.reverse(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nrlquqtx.html

Go:   slices.Reverse(arr)
来源：http://dali.cucudq.cn/Article/details/gt2ctqbvmfh.html

Ruby: arr.reverse
来源：http://dali.vqdsnc.cn/Article/details/gt2jhzztynr.html

C#:   list.Reverse();
来源：http://dali.hnqzz.top/Article/details/gt2qlplbxkk.html

[D12] 查找元素下标
来源：http://dali.haohaochexian.top/Article/details/gt2bkjsxyzc.html

Py:   arr.index(x);  x in arr
来源：http://dali.andypj.xyz/Article/details/gt2qbyzzlbc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yj202588.top/Article/details/gt2tdoafdfz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.316326.xyz/Article/details/gt2mahijlhy.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dianchejie.cn/Article/details/gt2jzvnurja.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.iojbl.cn/Article/details/gt2ycdbqerw.html

Go:   slices.Index(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gt2swtgtyht.html

Ruby: arr.index(x)
来源：http://dali.shzxlz.cn/Article/details/gt2hkmkomuj.html

C#:   list.IndexOf(x);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2imldqcsa.html

[D13] 过滤（保留满足条件的）
来源：http://dali.svipenyu.cn/Article/details/gt2vajdmtex.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hnqzz.top/Article/details/gt2talyiupx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sysykeji.top/Article/details/gt2pscrojhw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jqgufenzy.top/Article/details/gt2izoeoxcb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hnqzz.top/Article/details/gt2texmvbcc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinqigufen.top/Article/details/gt2ytsaqyfc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.9152youxi.cn/Article/details/gt2eeikqcxd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.fengsongda.top/Article/details/gt2twcxzvzw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.sysykeji.top/Article/details/gt2wzekubxf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cashguo.top/Article/details/gt2ofyllima.html


<!-- 参考信息 -->