代发 wailian999

[B13] 判断是否为数字
来源：http://dali.zhixingplan.top/Article/details/gteafcpjlk.html

Py:   isinstance(x, (int, float))
来源：http://dali.aibaodan.cn/Article/details/gtbmwqswfq.html

PHP:  is_numeric($x)
来源：http://dali.hammf.cn/Article/details/gtbxagoscw.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sweek.top/Article/details/gtrwlcfgbp.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.guannengcc.top/Article/details/gtaoqosqam.html

Java: x instanceof Number
来源：http://dali.yongpay.top/Article/details/gtbamwqytn.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.guannengcc.top/Article/details/gtgapzelyu.html

Ruby: x.is_a?(Numeric)
来源：http://dali.guannengcc.top/Article/details/gtsptuatil.html

C#:   x is int or double or decimal
来源：http://dali.yongpay.top/Article/details/gttjkijurr.html

[B14] 判断值是否在集合内
来源：http://dali.cashguo.top/Article/details/gtmhavqnti.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.tianlin.xyz/Article/details/gtsbcpfunj.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hnxiangtu.top/Article/details/gtpabxdtzg.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbgfggzkn.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtublepemv.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhengqikj.top/Article/details/gtiukczcjb.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxvvyeejh.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyywijzri.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.sxryk.cn/Article/details/gtrudnkmpa.html

[B15] 布尔运算与取反
来源：http://dali.redwolf501.top/Article/details/gtmjadvrdl.html

Py:   a and b or not c
来源：http://dali.daria6918.cn/Article/details/gtnnumerml.html

PHP:  $a && $b || !$c
来源：http://dali.wangdashe.top/Article/details/gtdjznxccp.html

JS:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gtbxupimfg.html

TS:   a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gtqoykhass.html

Java: a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gtfinvfgzx.html

Go:   a && b || !c
来源：http://dali.smart0.xyz/Article/details/gtdqpcujbd.html

Ruby: a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gtbgwoddzs.html

C#:   a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gtntxwwktf.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yongpay.top/Article/details/gtqalicxew.html

Py:   if not data: return
来源：http://dali.jianghu66.top/Article/details/gtvbqszvdo.html

PHP:  if (!$data) { return; }
来源：http://dali.svipenyu.cn/Article/details/gtcmkqxicl.html

JS:   if (!data) return;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuuameudf.html

TS:   if (!data) return;
来源：http://dali.dashuyun.cn/Article/details/gtjufdfpml.html

Java: if (data == null) return;
来源：http://dali.ppjwa.cn/Article/details/gtgnnclpyp.html

Go:   if data == nil { return }
来源：http://dali.chenlongwang.top/Article/details/gtfdoivvpy.html

Ruby: return if data.nil?
来源：http://dali.hfpthk.cn/Article/details/gtytfyrexi.html

C#:   if (data == null) return;
来源：http://dali.zhengqikj.top/Article/details/gtxqqlzynn.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtdopdotjl.html

C. 函数与作用域
来源：http://dali.wangshuangyany.cn/Article/details/gtyfhpxmjl.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtbcbytynv.html

[C01] 定义函数
来源：http://dali.yuxming.cn/Article/details/gtjvidptkn.html

Py:   def add(a, b): return a + b
来源：http://dali.shzxlz.cn/Article/details/gtcndyutzm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dashuyun.cn/Article/details/gtawnttcis.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gtfpondewl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gtngjlepfy.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gtmlxcpbgq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.nanxuanxn.top/Article/details/gtxihkgkkd.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jqgufenzy.top/Article/details/gtqsjgikxd.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gtaqpbylxv.html

[C02] 默认参数
来源：http://dali.xuetiantiany.cn/Article/details/gtnulcqlak.html

Py:   def greet(name="World"): return name
来源：http://dali.sysykeji.top/Article/details/gtsclmofks.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hfpthk.cn/Article/details/gtrgqvflkh.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yuanzhike.top/Article/details/gtsoupwzso.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.meibo888.top/Article/details/gtvcswyonj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hnqzz.top/Article/details/gtzxinuuqf.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hfpthk.cn/Article/details/gtyyghkemn.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhongyouzk.top/Article/details/gtaudmrzje.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ybcxt.top/Article/details/gtpwnifxvq.html

[C03] 可变参数
来源：http://dali.xuanzx.com/Article/details/gtosqgvdui.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhoulong.xyz/Article/details/gtomjvueou.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.sxryk.cn/Article/details/gttmliwqxw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ydzc1.top/Article/details/gtpsqpndcz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.aibaodan.cn/Article/details/gtqhagxbvu.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yangfankeji.com/Article/details/gtagadfcxb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yj20258888.top/Article/details/gtakxygmbi.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.aizwys.cn/Article/details/gtzvhoqupm.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jianghu66.top/Article/details/gtkuebjgik.html

[C04] 命名参数 / 关键字参数
来源：http://dali.smart0.xyz/Article/details/gtsjjikpgm.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yuxming.cn/Article/details/gtnfbllwjw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhongyouzk.top/Article/details/gternzanlz.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.wangdashe.top/Article/details/gtjngvqvlz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hysaishi.cn/Article/details/gtxjatxceu.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.0kj1m.cn/Article/details/gtexldlwvr.html

Go:   // 无：用配置结构体参数
来源：http://dali.hnxiangtu.top/Article/details/gtfxivaxei.html

Ruby: f(a: 1, b: 2)
来源：http://dali.wangdashe.top/Article/details/gtchzjklwz.html

C#:   f(a: 1, b: 2)
来源：http://dali.sysykeji.top/Article/details/gthhwavotb.html

[C05] 返回多个值
来源：http://dali.chenlongwang.top/Article/details/gtnnfbzdfq.html

Py:   return a, b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkvfjvpuw.html

PHP:  return [$a, $b];
来源：http://dali.yongpay.top/Article/details/gtudeugnfl.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.nanxinkj.top/Article/details/gtfpsmtyht.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gtlysjrknz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.quarkkingdee.top/Article/details/gthnsukxbe.html

Go:   return a, b
来源：http://dali.ydzc1.top/Article/details/gtpxhzuipm.html

Ruby: return a, b
来源：http://dali.wangshuangyany.cn/Article/details/gtzgulcfud.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.kuanghao11.cn/Article/details/gthqxvfxtw.html

[C06] 匿名函数 / lambda
来源：http://dali.xuanzx.com/Article/details/gteipefscy.html

Py:   square = lambda x: x * x
来源：http://dali.guowangkeji.top/Article/details/gtzcsrevwr.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gttwzqbzwb.html

JS:   const square = x => x * x;
来源：http://dali.daria6918.cn/Article/details/gtvlkxpenc.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shangyingyoupin.top/Article/details/gthepiqdws.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xylfe.cn/Article/details/gtojnsirvi.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sysykeji.top/Article/details/gtkbttsksd.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yvedp.cn/Article/details/gttlhnnutw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.chenlongwang.top/Article/details/gthciigpzg.html

[C07] 把函数作为参数传入
来源：http://dali.ydzc1.top/Article/details/gtmjhogque.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yueranfly.top/Article/details/gtrwalsppp.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sxryk.cn/Article/details/gtyylivqcq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.haohaochexian.top/Article/details/gtozxjhgyb.html

TS:   arr.map(String)
来源：http://dali.sweek.top/Article/details/gtppfmpqin.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.9152youxi.cn/Article/details/gtbaorpxbo.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.meibo888.top/Article/details/gtxckskonq.html

Ruby: arr.map(&:upcase)
来源：http://dali.jqgfzy.top/Article/details/gttvtuarnd.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.birdmap.top/Article/details/gtwoyrsrvb.html

[C08] 闭包
来源：http://dali.yuxming.cn/Article/details/gtvnzswfgv.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cqqwz.cn/Article/details/gtgvasbpyd.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yangfankeji.com/Article/details/gtnfuiuorg.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.sysykeji.top/Article/details/gtkitdokri.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jlsjyb.cn/Article/details/gtbjgiyjqm.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jyoumei.cn/Article/details/gtkgnaphzj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jqgufenzy.top/Article/details/gtedfcxzhm.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gtvvazlqag.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ybcxt.top/Article/details/gthciyzwhj.html

[C09] 递归
来源：http://dali.daria6918.cn/Article/details/gthgqlqhpp.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhixingplan.top/Article/details/gtxodwepcy.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.havefunace.top/Article/details/gtlxlbijtb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shanyushiyangtech.top/Article/details/gtevggrssv.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigfzy.top/Article/details/gtwtpjyqyk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.wangdashe.top/Article/details/gtpsiiwqum.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.wangshuangyany.cn/Article/details/gtgmcqcrus.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.sufxvd.cn/Article/details/gtrhiiwlfy.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.tanke756.top/Article/details/gtkbdohxpm.html

[C10] 变量作用域
来源：http://dali.ivvv.top/Article/details/gtulxnptbv.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xziqi.cn/Article/details/gtcizpegxj.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinghuilouyu.cn/Article/details/gttvwbmjfw.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.pengpengdd.cyou/Article/details/gtwgqttgnn.html

TS:   同 JS
来源：http://dali.havefunace.top/Article/details/gtskggnktj.html

Java: 方法内为块级作用域
来源：http://dali.snrcjt.cn/Article/details/gtzkzexsim.html

Go:   花括号块级作用域
来源：http://dali.daria6918.cn/Article/details/gtehvtdpyx.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfqaogsi.html

C#:   块级作用域
来源：http://dali.kuanghao11.cn/Article/details/gtshhdzhuf.html

[C11] 模块导入与导出
来源：http://dali.dianchejie.cn/Article/details/gtbjalvzwr.html

Py:   from module import func
来源：http://dali.hnxiangtu.top/Article/details/gtqksayxmj.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shanyushiyangtech.top/Article/details/gtovhncbdv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.iojbl.cn/Article/details/gtrqkapygk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gtajbshipv.html

Java: import java.util.List;
来源：http://dali.guowangkeji.top/Article/details/gtxifhxxbt.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jyoumei.cn/Article/details/gtngilvaeo.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yj202588.top/Article/details/gtgunirhns.html

C#:   using System.Text;
来源：http://dali.daxiang520.top/Article/details/gtffxiscjf.html

[C12] 立即执行函数 IIFE
来源：http://dali.jiagoushi.top/Article/details/gtzweobwrf.html

Py:   (lambda: print("run"))()
来源：http://dali.havefunace.top/Article/details/gtqsavwvqh.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hnxiangtu.top/Article/details/gtbxsucaeu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.pycfn.com/Article/details/gtkdvoouux.html

TS:   (() => { console.log("run"); })();
来源：http://dali.gzhubu.top/Article/details/gtubfrtcnl.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.redwolf501.top/Article/details/gthcyzqyyu.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinqigfzy.top/Article/details/gtwsdcaeil.html

Ruby: -> { puts "run" }.call
来源：http://dali.yj20258.top/Article/details/gtjpajwltx.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.mhx1999.top/Article/details/gtvyeozcho.html

[C13] 类型声明 / 类型注解
来源：http://dali.birdmap.top/Article/details/gtaypyhuaw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shzxlz.cn/Article/details/gtjrvojncf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gaohongyu789.top/Article/details/gtfxtafwnb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hysaishi.cn/Article/details/gtakbeipsv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gtmdtxkows.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gtdlxilhwc.html

Go:   func add(a, b int) int
来源：http://dali.kuanghao11.cn/Article/details/gtmamdkacy.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhoulong.xyz/Article/details/gtmhcmjjiy.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.sysykeji.top/Article/details/gtmwzllipf.html

[C14] 泛型函数
来源：http://dali.316326.xyz/Article/details/gtkcvpzygj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shuidangran.top/Article/details/gtohmyffvz.html

PHP:  // 无泛型
来源：http://dali.nanxuanxn.top/Article/details/gtmquvwynz.html

JS:   // 无泛型
来源：http://dali.hywenlv.cn/Article/details/gtxyerdhwn.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.chenlongwang.top/Article/details/gtjceafvei.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.tianlin.xyz/Article/details/gtmclpnpgd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.iojbl.cn/Article/details/gtxtlypank.html

Ruby: # 无泛型
来源：http://dali.xinyue.icu/Article/details/gtjturtrhf.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.mhx1999.top/Article/details/gtbbikcrbk.html

[C15] 解构 / 展开参数
来源：http://dali.jinqigfzy.top/Article/details/gtapvptgzk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yangfankeji.com/Article/details/gtamqscate.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhoulong.xyz/Article/details/gtiamvadzp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhengqikj.top/Article/details/gtqvnoeeoe.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbashibbf.html

Java: // 无解构
来源：http://dali.ywan-chungtsiang.top/Article/details/gtttqvaufp.html

Go:   // 无解构
来源：http://dali.vqdsnc.cn/Article/details/gtbokmuzao.html

Ruby: a, b = pair
来源：http://dali.smart0.xyz/Article/details/gtvomqxcuh.html

C#:   var (a, b) = pair;
来源：http://dali.fengsongda.top/Article/details/gtitfremxu.html

[C16] 函数 / 方法重载
来源：http://dali.tian-w.cn/Article/details/gtjtqifmqa.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jinqigufen.top/Article/details/gtcymtbyfm.html

PHP:  // 无重载
来源：http://dali.shanyushiyangtech.top/Article/details/gtgubocgsm.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhixingplan.top/Article/details/gtntzfrinw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.guowangkeji.top/Article/details/gtkapnxiim.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gthsxvguyb.html

Go:   // 无重载：用不同函数名
来源：http://dali.andypj.xyz/Article/details/gtcmriubui.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hammf.cn/Article/details/gtvoaptpnq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yj202588.top/Article/details/gtaedpviuu.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtvscewoxd.html

D. 数组 / 列表 / 集合
来源：http://dali.haohaochexian.top/Article/details/gtwetxvakw.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtxceqmyki.html

[D01] 创建数组 / 列表
来源：http://dali.andypj.xyz/Article/details/gtkrpocubq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gaohongyu789.top/Article/details/gtovcwuchz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.0kj1m.cn/Article/details/gtnnvkwoqs.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.guannengcc.top/Article/details/gtvvtcntlt.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.gaohongyu789.top/Article/details/gtsjynoqzg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.wangshuangyany.cn/Article/details/gtraegqsqr.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jqgufenzy.top/Article/details/gtafpjputn.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinqigfzy.top/Article/details/gtwboeimgz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yonumen.top/Article/details/gtyieogtix.html

[D02] 追加元素到末尾
来源：http://dali.daria6918.cn/Article/details/gtowrdhkjz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.birdmap.top/Article/details/gtdsmtdswx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.fzhhl.top/Article/details/gtyihwlmxn.html

JS:   arr.push(4);
来源：http://dali.guowangkeji.top/Article/details/gtevcvibqg.html

TS:   arr.push(4);
来源：http://dali.jqgufenzy.top/Article/details/gthibwoamb.html

Java: list.add(4);
来源：http://dali.yanxiufei.cn/Article/details/gtstrwydaw.html

Go:   arr = append(arr, 4)
来源：http://dali.ehwqpu.com/Article/details/gtcqmncafy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cheryme.top/Article/details/gthlfrdlie.html

C#:   list.Add(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcxfrudul.html

[D03] 在指定位置插入元素
来源：http://dali.smart0.xyz/Article/details/gttyqvstms.html

Py:   arr.insert(0, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtayicoymh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hfpthk.cn/Article/details/gttlkmaeyg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jqgfzy.top/Article/details/gtnwihlcnx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hywenlv.cn/Article/details/gtmummbmpl.html

Java: list.add(0, 0);
来源：http://dali.meibo888.top/Article/details/gtaddlfbmf.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.snrcjt.cn/Article/details/gtogflurtv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.nanxuanxn.top/Article/details/gtieqwaptq.html

C#:   list.Insert(0, 0);
来源：http://dali.nanxuanxn.top/Article/details/gthccqdtod.html

[D04] 删除元素
来源：http://dali.jyoumei.cn/Article/details/gtjqvnuqew.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ehwqpu.com/Article/details/gtyrbdgkef.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yj202588.top/Article/details/gtznllvqmn.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zycfv.cn/Article/details/gtzvbsausk.html

TS:   arr.splice(0, 1);
来源：http://dali.zhengqikj.top/Article/details/gtmiovofiv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yangfankeji.com/Article/details/gtrdnuxpwc.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.snrcjt.cn/Article/details/gtiyaoszqu.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.9152youxi.cn/Article/details/gtiqgmiufd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jiagoushi.top/Article/details/gtjiedqpkg.html

[D05] 访问与修改元素
来源：http://dali.yuxming.cn/Article/details/gtetidvdlm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhengqikj.top/Article/details/gtysdnqrlv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xylfe.cn/Article/details/gtirqjfnpc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinghuilouyu.cn/Article/details/gtndkyiqco.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yongpay.top/Article/details/gteleqvfaj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.wangdashe.top/Article/details/gtbligeuyo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sweek.top/Article/details/gtfjjrumrk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmoktuqrj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.andypj.xyz/Article/details/gtikvahitc.html

[D06] 数组长度
来源：http://dali.cqqwz.cn/Article/details/gtpyemxllc.html

Py:   len(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtaqkskglu.html

PHP:  count($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtvxmhroeq.html

JS:   arr.length
来源：http://dali.dianchejie.cn/Article/details/gtalmuahgu.html

TS:   arr.length
来源：http://dali.yanxiufei.cn/Article/details/gtinvubmnv.html

Java: list.size();
来源：http://dali.sysykeji.top/Article/details/gteokyuxxi.html

Go:   len(arr)
来源：http://dali.yangfankeji.com/Article/details/gtgdauwqgf.html

Ruby: arr.length; arr.size
来源：http://dali.316326.xyz/Article/details/gtltmzqcai.html

C#:   list.Count;
来源：http://dali.svipenyu.cn/Article/details/gtvrswiskl.html

[D07] 切片 / 取子数组
来源：http://dali.c1oappe.top/Article/details/gtbkysviih.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xylfe.cn/Article/details/gttrayvojz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtabipmouv.html

JS:   arr.slice(1, 4);
来源：http://dali.jqgfzy.top/Article/details/gtnvekuiam.html

TS:   arr.slice(1, 4);
来源：http://dali.316326.xyz/Article/details/gtrrzxkdzb.html

Java: list.subList(1, 4);
来源：http://dali.aizwys.cn/Article/details/gtxevelgod.html

Go:   arr[1:4]
来源：http://dali.aibaodan.cn/Article/details/gtlgweldsh.html

Ruby: arr[1, 3]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlsndcclq.html

C#:   list.GetRange(1, 3);
来源：http://dali.zdqjudy.top/Article/details/gtimqokzqp.html

[D08] 合并两个数组
来源：http://dali.sufxvd.cn/Article/details/gtrhihzryt.html

Py:   a + b;  a.extend(b)
来源：http://dali.hnqzz.top/Article/details/gtmixaygii.html

PHP:  array_merge($a, $b);
来源：http://dali.mhx1999.top/Article/details/gtpshvvrhs.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.9152youxi.cn/Article/details/gtzlguykow.html

TS:   [...a, ...b];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtachhkvrf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.fzhhl.top/Article/details/gtorsvthye.html

Go:   append(a, b...)
来源：http://dali.pycfn.com/Article/details/gtloudwkcs.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sxryk.cn/Article/details/gtwgeewfpi.html

C#:   a.Concat(b).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtcfqevjty.html

[D09] 排序（升序）
来源：http://dali.cheryme.top/Article/details/gtplhtczdh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jiagoushi.top/Article/details/gtvoeygvxy.html

PHP:  sort($arr);
来源：http://dali.cdnleiting.top/Article/details/gtwsquieyt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xuanzx.com/Article/details/gtelfigsee.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.316326.xyz/Article/details/gtxukjuiah.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cucudq.cn/Article/details/gtlskpytyt.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.9152youxi.cn/Article/details/gtpqbtatjf.html

Ruby: arr.sort
来源：http://dali.fzhhl.top/Article/details/gtwrwlbevq.html

C#:   list.Sort();
来源：http://dali.vqdsnc.cn/Article/details/gtyvrydjkp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gtuybxvevd.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hysaishi.cn/Article/details/gtxiarpcah.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.dianchejie.cn/Article/details/gtgjyxuoll.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ybcxt.top/Article/details/gtojssrsxv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jlsjyb.cn/Article/details/gtegixmlbi.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.birdmap.top/Article/details/gtdyawiwel.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gogol.net.cn/Article/details/gtmtrvynhl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cdnleiting.top/Article/details/gtrvjqakdz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhixingplan.top/Article/details/gttyxnkujm.html

[D11] 反转数组
来源：http://dali.smart0.xyz/Article/details/gtgxqupoai.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xylfe.cn/Article/details/gtxpejsqqv.html

PHP:  array_reverse($arr);
来源：http://dali.dashuyun.cn/Article/details/gtjdsouwel.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xinyue.icu/Article/details/gtetkoypfo.html

TS:   [...arr].reverse();
来源：http://dali.tian-w.cn/Article/details/gtyphznvjf.html

Java: Collections.reverse(list);
来源：http://dali.pycfn.com/Article/details/gtcquplwhz.html

Go:   slices.Reverse(arr)
来源：http://dali.yvedp.cn/Article/details/gtbsidedfd.html

Ruby: arr.reverse
来源：http://dali.fzhhl.top/Article/details/gthcomwzby.html

C#:   list.Reverse();
来源：http://dali.sufxvd.cn/Article/details/gtkfjcdmzp.html

[D12] 查找元素下标
来源：http://dali.xziqi.cn/Article/details/gtufrbzthr.html

Py:   arr.index(x);  x in arr
来源：http://dali.yangfankeji.com/Article/details/gtmmirzhvf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shzxlz.cn/Article/details/gtjxrtmqfe.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aibaodan.cn/Article/details/gtwextpksn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtthsutceq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.nanxuanxn.top/Article/details/gtllcmfyiv.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtprcxlohz.html

Ruby: arr.index(x)
来源：http://dali.chenzaomai.com/Article/details/gtrvjlruct.html

C#:   list.IndexOf(x);
来源：http://dali.dianchejie.cn/Article/details/gtflphokcc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.feifeiyinyue.top/Article/details/gtunpjcxtt.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hammf.cn/Article/details/gthzdwdnlo.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sufxvd.cn/Article/details/gtkxtxcigr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gzhubu.top/Article/details/gthyygfbgc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.sufxvd.cn/Article/details/gtqvmrvdla.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcpfiwrhm.html


<!-- 参考信息 -->