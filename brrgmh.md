代发 wailian999

Py:   if not data: return
来源：http://dali.guowangkeji.top/Article/details/gt2waonhogl.html

PHP:  if (!$data) { return; }
来源：http://dali.zhixingplan.top/Article/details/gt2lsazivqh.html

JS:   if (!data) return;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bclhuixz.html

TS:   if (!data) return;
来源：http://dali.ehwqpu.com/Article/details/gt2zdqlbcqi.html

Java: if (data == null) return;
来源：http://dali.gogol.net.cn/Article/details/gt2fcqeppod.html

Go:   if data == nil { return }
来源：http://dali.chenzaomai.com/Article/details/gt2vicvrczd.html

Ruby: return if data.nil?
来源：http://dali.yongpay.top/Article/details/gt2xluqpacr.html

C#:   if (data == null) return;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lxrwjsps.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2dzolehxz.html

C. 函数与作用域
来源：http://dali.shangyingyoupin.top/Article/details/gt2oazvrvyl.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2oteccwbl.html

[C01] 定义函数
来源：http://dali.xuanzx.com/Article/details/gt2uyarwkfy.html

Py:   def add(a, b): return a + b
来源：http://dali.feifeiyinyue.top/Article/details/gt2eelgkgax.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sweek.top/Article/details/gt2xqtszylr.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gt2qvynqumf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gt2jbivhijo.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gt2jgtbbwbi.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2osrldyhv.html

Ruby: def add(a, b); a + b; end
来源：http://dali.haohaochexian.top/Article/details/gt2qaqxdycz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2aifxunff.html

[C02] 默认参数
来源：http://dali.guannengcc.top/Article/details/gt2kqpccvps.html

Py:   def greet(name="World"): return name
来源：http://dali.yongpay.top/Article/details/gt2nyxsqymc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cucudq.cn/Article/details/gt2zresxvsc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhengqikj.top/Article/details/gt2wcpriqkx.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zdqjudy.top/Article/details/gt2dhcixqua.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yuanzhike.top/Article/details/gt2veiqnbnx.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.iojbl.cn/Article/details/gt2limvucra.html

Ruby: def greet(name = "World") = name
来源：http://dali.smart0.xyz/Article/details/gt2dgifcpkx.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yvedp.cn/Article/details/gt2zeydlrci.html

[C03] 可变参数
来源：http://dali.birdmap.top/Article/details/gt2xecgwagz.html

Py:   def total(*args): return sum(args)
来源：http://dali.ybcxt.top/Article/details/gt2siujoaup.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zqmbvoaf.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.meibo888.top/Article/details/gt2jvfkctpi.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jiagoushi.top/Article/details/gt2ccfkvsfb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hysaishi.cn/Article/details/gt2ycjcomgx.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yltlhrbs.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2zxmjzjfa.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2lycxrunc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shuidangran.top/Article/details/gt2wmdkazam.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.0kj1m.cn/Article/details/gt2qucngvqc.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yanxiufei.cn/Article/details/gt2wlzyenzx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.9152youxi.cn/Article/details/gt2fwiqtmfe.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.wangshuangyany.cn/Article/details/gt2zhmnrogk.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.gogol.net.cn/Article/details/gt2gtinkqec.html

Go:   // 无：用配置结构体参数
来源：http://dali.gzhubu.top/Article/details/gt2vntpgmfz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yuxming.cn/Article/details/gt2pfmymliu.html

C#:   f(a: 1, b: 2)
来源：http://dali.jyoumei.cn/Article/details/gt2sdckktvl.html

[C05] 返回多个值
来源：http://dali.yvedp.cn/Article/details/gt2vavsysfu.html

Py:   return a, b
来源：http://dali.pycfn.com/Article/details/gt2pobkdjkw.html

PHP:  return [$a, $b];
来源：http://dali.haohaochexian.top/Article/details/gt2wlhqhitn.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yeuiqdkz.html

TS:   return { a, b };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2npksaegq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hongshengwenyu.top/Article/details/gt2qhhiceuu.html

Go:   return a, b
来源：http://dali.jqgufenzy.top/Article/details/gt2sqnqcckn.html

Ruby: return a, b
来源：http://dali.ybcxt.top/Article/details/gt2natatznj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.dianchejie.cn/Article/details/gt2eabcuvaq.html

[C06] 匿名函数 / lambda
来源：http://dali.chenjidiqi.icu/Article/details/gt2vwzoxpct.html

Py:   square = lambda x: x * x
来源：http://dali.ivvv.top/Article/details/gt2tyjolvta.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.daxiang520.top/Article/details/gt2odkaxsbw.html

JS:   const square = x => x * x;
来源：http://dali.bjfxy.top/Article/details/gt2vczqbkur.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.pengpengdd.cyou/Article/details/gt2yyckhpat.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dtkjmvjl.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shuidangran.top/Article/details/gt2fdkoebko.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xylfe.cn/Article/details/gt2tgiydmrg.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yj202588.top/Article/details/gt2ikjsmmqa.html

[C07] 把函数作为参数传入
来源：http://dali.shzxlz.cn/Article/details/gt2piisrvqr.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.chenlongwang.top/Article/details/gt2jzcrluhz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jinqigufen.top/Article/details/gt2tddtdfpr.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.dashuyun.cn/Article/details/gt2knbgliyu.html

TS:   arr.map(String)
来源：http://dali.jinqigufen.top/Article/details/gt2dtygerks.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jqgufenzy.top/Article/details/gt2tadyyvgh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.guannengcc.top/Article/details/gt2hbybqnvu.html

Ruby: arr.map(&:upcase)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iqokvkyf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kttctyei.html

[C08] 闭包
来源：http://dali.yonumen.top/Article/details/gt2sevapggz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.chenlongwang.top/Article/details/gt2gbrrjzwx.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.kuanghao11.cn/Article/details/gt2mwfefgwd.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tmuxiqdc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yueranfly.top/Article/details/gt2rtojianl.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.mhx1999.top/Article/details/gt2dmrpjmrf.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.9152youxi.cn/Article/details/gt2iawromga.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gaohongyu789.top/Article/details/gt2zsxokzez.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2mfkzjcuf.html

[C09] 递归
来源：http://dali.cashguo.top/Article/details/gt2dscauomh.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.dianchejie.cn/Article/details/gt2ddaufovt.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.meibo888.top/Article/details/gt2rgidudny.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.snrcjt.cn/Article/details/gt2epxdcxbo.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.meibo888.top/Article/details/gt2wzrmbmsr.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aazjqkyl.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.havefunace.top/Article/details/gt2xksxixpm.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.sweek.top/Article/details/gt2mdazgftg.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jqgufenzy.top/Article/details/gt2czxfpipi.html

[C10] 变量作用域
来源：http://dali.hywenlv.cn/Article/details/gt2jvgtpdza.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.nanxuanxn.top/Article/details/gt2szyklrqh.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yongpay.top/Article/details/gt2dpiibnke.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.nanxinkj.top/Article/details/gt2vvubcxlv.html

TS:   同 JS
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fbemhbua.html

Java: 方法内为块级作用域
来源：http://dali.sweek.top/Article/details/gt2evjilwkf.html

Go:   花括号块级作用域
来源：http://dali.jqgfzy.top/Article/details/gt2mvfdmkcy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yj20258.top/Article/details/gt2twcrhxhm.html

C#:   块级作用域
来源：http://dali.tanke756.top/Article/details/gt2iwzfoadl.html

[C11] 模块导入与导出
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hiarqhhh.html

Py:   from module import func
来源：http://dali.316326.xyz/Article/details/gt2yowkbeto.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.pycfn.com/Article/details/gt2uctoecmv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yj202588.top/Article/details/gt2nglbnxen.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yonumen.top/Article/details/gt2vrpgfsyb.html

Java: import java.util.List;
来源：http://dali.jyoumei.cn/Article/details/gt2zmwwriyz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.gotoacloud.top/Article/details/gt2vgqaeule.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.tian-w.cn/Article/details/gt2xyqanmbd.html

C#:   using System.Text;
来源：http://dali.hysaishi.cn/Article/details/gt2pbpuvkkb.html

[C12] 立即执行函数 IIFE
来源：http://dali.yonumen.top/Article/details/gt2ltanwblt.html

Py:   (lambda: print("run"))()
来源：http://dali.cdnleiting.top/Article/details/gt2mogmjchn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ydzc1.top/Article/details/gt2nbslzkgi.html

JS:   (() => { console.log("run"); })();
来源：http://dali.guannengcc.top/Article/details/gt2etzjcgxz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jqgfzy.top/Article/details/gt2zqhlgzty.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.feifeiyinyue.top/Article/details/gt2sdscdfnh.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.wangshuangyany.cn/Article/details/gt2tpyymudp.html

Ruby: -> { puts "run" }.call
来源：http://dali.sysykeji.top/Article/details/gt2itxdcwaa.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hfpthk.cn/Article/details/gt2wtpshxwq.html

[C13] 类型声明 / 类型注解
来源：http://dali.316326.xyz/Article/details/gt2qqcekunw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sysykeji.top/Article/details/gt2oouopdbx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.fzhhl.top/Article/details/gt2faldmeyk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hfpthk.cn/Article/details/gt2tnrvygfe.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gt2nqmncvgr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gt2ynxoswsc.html

Go:   func add(a, b int) int
来源：http://dali.gogol.net.cn/Article/details/gt2nqxkvnpv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jinqigfzy.top/Article/details/gt2rxcdruwh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yj202588.top/Article/details/gt2yxjihcan.html

[C14] 泛型函数
来源：http://dali.pycfn.com/Article/details/gt2hkwdyovq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.mhx1999.top/Article/details/gt2bnllupfs.html

PHP:  // 无泛型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eiegskxi.html

JS:   // 无泛型
来源：http://dali.ybcxt.top/Article/details/gt2sffrojiv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ybcxt.top/Article/details/gt2owgbvhfr.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.dianchejie.cn/Article/details/gt2eznhgknk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.bjfxy.top/Article/details/gt2tmahgldy.html

Ruby: # 无泛型
来源：http://dali.quarkkingdee.top/Article/details/gt2nchpkols.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rpebsneb.html

[C15] 解构 / 展开参数
来源：http://dali.haohaochexian.top/Article/details/gt2cumvkyhr.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.tianlin.xyz/Article/details/gt2pptoevaz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hywenlv.cn/Article/details/gt2dortlcnq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hywenlv.cn/Article/details/gt2yulrhmns.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cdnleiting.top/Article/details/gt2lrnpjded.html

Java: // 无解构
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gbydymgf.html

Go:   // 无解构
来源：http://dali.xylfe.cn/Article/details/gt2zomchurf.html

Ruby: a, b = pair
来源：http://dali.tianlin.xyz/Article/details/gt2jigidpes.html

C#:   var (a, b) = pair;
来源：http://dali.yj20258.top/Article/details/gt2oygraxqx.html

[C16] 函数 / 方法重载
来源：http://dali.aizwys.cn/Article/details/gt2twzsagvw.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hywenlv.cn/Article/details/gt2ytgvucwf.html

PHP:  // 无重载
来源：http://dali.gogol.net.cn/Article/details/gt2tqplwqkb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.pengpengdd.cyou/Article/details/gt2xscircfc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.nanxinkj.top/Article/details/gt2cllfqzwt.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.birdmap.top/Article/details/gt2idxaxgzy.html

Go:   // 无重载：用不同函数名
来源：http://dali.xylfe.cn/Article/details/gt2ggtqmghu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.316326.xyz/Article/details/gt2jnizcwmj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2iimcrqdf.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2tjnzftul.html

D. 数组 / 列表 / 集合
来源：http://dali.jinqigfzy.top/Article/details/gt2cpnhgklm.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2erawymyg.html

[D01] 创建数组 / 列表
来源：http://dali.chenjidiqi.icu/Article/details/gt2jsmkzqat.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ydzc1.top/Article/details/gt2aidacnzt.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.aibaodan.cn/Article/details/gt2igxewyws.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bskmshxr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hywenlv.cn/Article/details/gt2nyzhbrxu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.aibaodan.cn/Article/details/gt2uxwdgzkq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.sweek.top/Article/details/gt2lmxipzle.html

Ruby: arr = [1, 2, 3]
来源：http://dali.birdmap.top/Article/details/gt2gtbqbsxi.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.mhx1999.top/Article/details/gt2rnlezopw.html

[D02] 追加元素到末尾
来源：http://dali.mhx1999.top/Article/details/gt2fpdhiznp.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.smart0.xyz/Article/details/gt2pjpxravp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hysaishi.cn/Article/details/gt2ofnyhubq.html

JS:   arr.push(4);
来源：http://dali.aibaodan.cn/Article/details/gt2wosnvuqj.html

TS:   arr.push(4);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ugycvasw.html

Java: list.add(4);
来源：http://dali.shuidangran.top/Article/details/gt2hcmbihre.html

Go:   arr = append(arr, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gt2iyyhynjz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.birdmap.top/Article/details/gt2uuoorsuz.html

C#:   list.Add(4);
来源：http://dali.tian-w.cn/Article/details/gt2cvgohnkz.html

[D03] 在指定位置插入元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zotmmtko.html

Py:   arr.insert(0, 0)
来源：http://dali.gaohongyu789.top/Article/details/gt2mwyeweyv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.snrcjt.cn/Article/details/gt2ywjerlwi.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eojzambd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yuxming.cn/Article/details/gt2xozxwqlr.html

Java: list.add(0, 0);
来源：http://dali.chenlongwang.top/Article/details/gt2srajoyea.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gogol.net.cn/Article/details/gt2zmxiuuyq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.redwolf501.top/Article/details/gt2yacaighc.html

C#:   list.Insert(0, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ifelctgz.html

[D04] 删除元素
来源：http://dali.dashuyun.cn/Article/details/gt2xhlwrzga.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zmjuhsxg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jianghu66.top/Article/details/gt2rsypelyw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.c1oappe.top/Article/details/gt2pfnnqznr.html

TS:   arr.splice(0, 1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qtqismhc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cdnleiting.top/Article/details/gt2pewajqjj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hnqzz.top/Article/details/gt2nhlrxoew.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.iojbl.cn/Article/details/gt2lmrsmtei.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.wangdashe.top/Article/details/gt2qqfselsj.html

[D05] 访问与修改元素
来源：http://dali.xylfe.cn/Article/details/gt2xtrwvqyd.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.fengsongda.top/Article/details/gt2ustinhcl.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.svipenyu.cn/Article/details/gt2bgslvefq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.nwbrower.top/Article/details/gt2fpmaqlty.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jqgfzy.top/Article/details/gt2bumcktkt.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.aibaodan.cn/Article/details/gt2xagpsytz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jqgfzy.top/Article/details/gt2knjwbvnd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tanke756.top/Article/details/gt2mganjfzw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zxiggjlz.html

[D06] 数组长度
来源：http://dali.smart0.xyz/Article/details/gt2nmkyoxok.html

Py:   len(arr)
来源：http://dali.cheryme.top/Article/details/gt2ghhomado.html

PHP:  count($arr);
来源：http://dali.fengsongda.top/Article/details/gt2zmkswcah.html

JS:   arr.length
来源：http://dali.gogol.net.cn/Article/details/gt2oysdhpfx.html

TS:   arr.length
来源：http://dali.jlsjyb.cn/Article/details/gt2rmmfjytj.html

Java: list.size();
来源：http://dali.jlsjyb.cn/Article/details/gt2ngxvsgfy.html

Go:   len(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2gggwqdpp.html

Ruby: arr.length; arr.size
来源：http://dali.fzhhl.top/Article/details/gt2swpbrepu.html

C#:   list.Count;
来源：http://dali.ppjwa.cn/Article/details/gt2gjknobji.html

[D07] 切片 / 取子数组
来源：http://dali.fzhhl.top/Article/details/gt2yhcanfyv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.andypj.xyz/Article/details/gt2cujqwewc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tqfnbfqp.html

JS:   arr.slice(1, 4);
来源：http://dali.mhx1999.top/Article/details/gt2rokgyeqt.html

TS:   arr.slice(1, 4);
来源：http://dali.ybcxt.top/Article/details/gt2fubnbznm.html

Java: list.subList(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gt2qkxzyfkm.html

Go:   arr[1:4]
来源：http://dali.cqqwz.cn/Article/details/gt2ndlcvuzj.html

Ruby: arr[1, 3]
来源：http://dali.bjfxy.top/Article/details/gt2gibbgdkr.html

C#:   list.GetRange(1, 3);
来源：http://dali.wangshuangyany.cn/Article/details/gt2bgnknwcg.html

[D08] 合并两个数组
来源：http://dali.gaohongyu789.top/Article/details/gt2abjtbprd.html

Py:   a + b;  a.extend(b)
来源：http://dali.kuanghao11.cn/Article/details/gt2wibjnvru.html

PHP:  array_merge($a, $b);
来源：http://dali.iojbl.cn/Article/details/gt2cjpeyrta.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.tanke756.top/Article/details/gt2nlrkzxdx.html

TS:   [...a, ...b];
来源：http://dali.feifeiyinyue.top/Article/details/gt2xazggrwr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.iojbl.cn/Article/details/gt2xgcxncgb.html

Go:   append(a, b...)
来源：http://dali.xuanzx.com/Article/details/gt2tiqhqhdb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.0kj1m.cn/Article/details/gt2vtaujlub.html

C#:   a.Concat(b).ToList()
来源：http://dali.fengsongda.top/Article/details/gt2erymebcn.html

[D09] 排序（升序）
来源：http://dali.cucudq.cn/Article/details/gt2kejyswwn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pycfn.com/Article/details/gt2cgvegjoj.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgrblvx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2odqwgrmq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sysykeji.top/Article/details/gt2tcenhsdi.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hnqzz.top/Article/details/gt2qieoieft.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2iwhwzrce.html

Ruby: arr.sort
来源：http://dali.shangyingyoupin.top/Article/details/gt2ysuepjhs.html

C#:   list.Sort();
来源：http://dali.xziqi.cn/Article/details/gt2fhtsktzn.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ydzc1.top/Article/details/gt2gcvrrwqt.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uqrpyopn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gaohongyu789.top/Article/details/gt2ltkgyand.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nanxuanxn.top/Article/details/gt2ocnrebro.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shuidangran.top/Article/details/gt2rpcaqcom.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hfpthk.cn/Article/details/gt2sfxebdsk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinqigfzy.top/Article/details/gt2jjcobyyc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhengqikj.top/Article/details/gt2jctnwzjo.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinghuilouyu.cn/Article/details/gt2seyivyaz.html

[D11] 反转数组
来源：http://dali.ybcxt.top/Article/details/gt2fhcuskvt.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.chenzaomai.com/Article/details/gt2ycpyimfx.html

PHP:  array_reverse($arr);
来源：http://dali.xuanzx.com/Article/details/gt2absonzcb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hywenlv.cn/Article/details/gt2lrxpyicy.html

TS:   [...arr].reverse();
来源：http://dali.fzhhl.top/Article/details/gt2yzdmdpyy.html

Java: Collections.reverse(list);
来源：http://dali.pycfn.com/Article/details/gt2siejxydl.html

Go:   slices.Reverse(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qmxiowiv.html

Ruby: arr.reverse
来源：http://dali.sufxvd.cn/Article/details/gt2wvztftyg.html

C#:   list.Reverse();
来源：http://dali.pycfn.com/Article/details/gt2mmhpbyzb.html

[D12] 查找元素下标
来源：http://dali.zhiwuduotai.top/Article/details/gt2lhfgfvtv.html

Py:   arr.index(x);  x in arr
来源：http://dali.ybcxt.top/Article/details/gt2gjdvkiio.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.chenzaomai.com/Article/details/gt2bzhjjqkb.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hfpthk.cn/Article/details/gt2jxslmhyw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gotoacloud.top/Article/details/gt2ndgzbdxh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.andypj.xyz/Article/details/gt2ufeccojo.html

Go:   slices.Index(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gt2kpmkyqwf.html

Ruby: arr.index(x)
来源：http://dali.yangfankeji.com/Article/details/gt2zqvepxvi.html

C#:   list.IndexOf(x);
来源：http://dali.jianghu66.top/Article/details/gt2cpilejyj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.fengsongda.top/Article/details/gt2ithbahac.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jyoumei.cn/Article/details/gt2zmovzfeu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cucudq.cn/Article/details/gt2senqcjal.html

JS:   arr.filter(x => x > 3)
来源：http://dali.iojbl.cn/Article/details/gt2vpzaxaic.html

TS:   arr.filter(x => x > 3)
来源：http://dali.nwbrower.top/Article/details/gt2mzdtlsah.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.nwbrower.top/Article/details/gt2pifmdyxj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.chenlongwang.top/Article/details/gt2cdyizlka.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2unpejkxd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.haohaochexian.top/Article/details/gt2lmuggtfc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.birdmap.top/Article/details/gt2olhmttlk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhixingplan.top/Article/details/gt2cfluwwpu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cashguo.top/Article/details/gt2irowyzeb.html

JS:   arr.map(x => x * 2)
来源：http://dali.cucudq.cn/Article/details/gt2unaifhml.html

TS:   arr.map(x => x * 2)
来源：http://dali.guannengcc.top/Article/details/gt2cffotcls.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.quarkkingdee.top/Article/details/gt2depiwkrc.html

Go:   // 手写循环
来源：http://dali.nanxuanxn.top/Article/details/gt2dflcmzlr.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yj20258.top/Article/details/gt2ybmjwnxy.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yj20258.top/Article/details/gt2gxrmjbpk.html

[D15] 去重
来源：http://dali.jinqigufen.top/Article/details/gt2eydvxwot.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.tian-w.cn/Article/details/gt2puhfpwcz.html

PHP:  array_unique($arr);
来源：http://dali.andypj.xyz/Article/details/gt2wqgbdotn.html

JS:   [...new Set(arr)]
来源：http://dali.zycfv.cn/Article/details/gt2lhaqanni.html

TS:   [...new Set(arr)]
来源：http://dali.gogol.net.cn/Article/details/gt2mzsesvzu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.meibo888.top/Article/details/gt2uwbhcjbo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hysaishi.cn/Article/details/gt2nvwxrqvb.html

Ruby: arr.uniq
来源：http://dali.xinyue.icu/Article/details/gt2ekqwtqdi.html

C#:   list.Distinct().ToList()
来源：http://dali.hnxiangtu.top/Article/details/gt2hlobncgp.html

[D16] 求和与平均值
来源：http://dali.yuxming.cn/Article/details/gt2tdojrybl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2vrpdfzae.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yonumen.top/Article/details/gt2aktevrid.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhongyouzk.top/Article/details/gt2qcyzipxp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cucudq.cn/Article/details/gt2vxomriis.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.nwbrower.top/Article/details/gt2jvlmuole.html

Go:   // 手写循环累加
来源：http://dali.shzxlz.cn/Article/details/gt2kavkjkuf.html


<!-- 参考信息 -->