代发 wailian999

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.snrcjt.cn/Article/details/gtdcmkoums.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhoulong.xyz/Article/details/gtuhukzaks.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.316326.xyz/Article/details/gtzsqgjmpa.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gtkkqfgwrx.html

[B13] 判断是否为数字
来源：http://dali.gotoacloud.top/Article/details/gtumeqvbjk.html

Py:   isinstance(x, (int, float))
来源：http://dali.smart0.xyz/Article/details/gtdhnsshzm.html

PHP:  is_numeric($x)
来源：http://dali.haohaochexian.top/Article/details/gtglmqcqmx.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxuanxn.top/Article/details/gtwzwlkyfi.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtweepsuow.html

Java: x instanceof Number
来源：http://dali.jianghu66.top/Article/details/gtdxoytovf.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.fzhhl.top/Article/details/gtpkcdxnjc.html

Ruby: x.is_a?(Numeric)
来源：http://dali.dianchejie.cn/Article/details/gtjdmbjsxb.html

C#:   x is int or double or decimal
来源：http://dali.jinyuanbaomall.cn/Article/details/gtztlcjkxh.html

[B14] 判断值是否在集合内
来源：http://dali.smart0.xyz/Article/details/gtyiblwxtw.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.dianchejie.cn/Article/details/gtqlhvjkjv.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.9152youxi.cn/Article/details/gtmvtkfwqc.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gtmonzrsxw.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtjapcbvja.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.aibaodan.cn/Article/details/gtvjpyhjyc.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gtjtjeqveb.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjnblgymc.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.mhx1999.top/Article/details/gtbvaijsvf.html

[B15] 布尔运算与取反
来源：http://dali.zycfv.cn/Article/details/gtbpgenlqx.html

Py:   a and b or not c
来源：http://dali.cucudq.cn/Article/details/gtrkzsmizv.html

PHP:  $a && $b || !$c
来源：http://dali.jinqigfzy.top/Article/details/gtrzqoszki.html

JS:   a && b || !c
来源：http://dali.yj20258888.top/Article/details/gtublrijpn.html

TS:   a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gtcthostfw.html

Java: a && b || !c
来源：http://dali.ivvv.top/Article/details/gtmcvjwmaj.html

Go:   a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlvcltwez.html

Ruby: a && b || !c
来源：http://dali.ybcxt.top/Article/details/gtpnzscsvy.html

C#:   a && b || !c
来源：http://dali.shuidangran.top/Article/details/gtdfcfkfra.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ivvv.top/Article/details/gtolgoigzn.html

Py:   if not data: return
来源：http://dali.mhx1999.top/Article/details/gtjaoqzlsj.html

PHP:  if (!$data) { return; }
来源：http://dali.jinqigfzy.top/Article/details/gtufltnoii.html

JS:   if (!data) return;
来源：http://dali.yuanzhike.top/Article/details/gtxqaksfsx.html

TS:   if (!data) return;
来源：http://dali.yongpay.top/Article/details/gtdbllhige.html

Java: if (data == null) return;
来源：http://dali.ppjwa.cn/Article/details/gtwaihjepi.html

Go:   if data == nil { return }
来源：http://dali.ybcxt.top/Article/details/gtsuieapne.html

Ruby: return if data.nil?
来源：http://dali.yueranfly.top/Article/details/gtphgxfdyo.html

C#:   if (data == null) return;
来源：http://dali.havefunace.top/Article/details/gtwaswwmox.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gthsncvkdz.html

C. 函数与作用域
来源：http://dali.gogol.net.cn/Article/details/gtlrsnopnq.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtvqmdqari.html

[C01] 定义函数
来源：http://dali.guowangkeji.top/Article/details/gtstzbcgob.html

Py:   def add(a, b): return a + b
来源：http://dali.hysaishi.cn/Article/details/gttbviouie.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gtlkynjagz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtwunsvcdj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtgprgwshl.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gtrvlabfcg.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.316326.xyz/Article/details/gtwszxjirt.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shuidangran.top/Article/details/gtjdewbjoz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gtxwsxhwxd.html

[C02] 默认参数
来源：http://dali.yonumen.top/Article/details/gtwegexcyb.html

Py:   def greet(name="World"): return name
来源：http://dali.cucudq.cn/Article/details/gtxwsijcib.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.haohaochexian.top/Article/details/gtizpitbze.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.havefunace.top/Article/details/gtjljdviyw.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yj202588.top/Article/details/gtchdthwgv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.redwolf501.top/Article/details/gtrchmcwsq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xuetiantiany.cn/Article/details/gtocjtsuoz.html

Ruby: def greet(name = "World") = name
来源：http://dali.hnqzz.top/Article/details/gtfadeefgl.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shuidangran.top/Article/details/gtfktjudeh.html

[C03] 可变参数
来源：http://dali.zhixingplan.top/Article/details/gtspkfosvp.html

Py:   def total(*args): return sum(args)
来源：http://dali.jyoumei.cn/Article/details/gtbqvnzkqq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yj202588.top/Article/details/gtpjfqfnpp.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gzhubu.top/Article/details/gtzsniuvgt.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yongpay.top/Article/details/gtqnwcxfla.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jqgufenzy.top/Article/details/gtmazidkac.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yj20258.top/Article/details/gtddogtkho.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhoulong.xyz/Article/details/gtshvooptj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xuanzx.com/Article/details/gtedvmdeej.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yj20258888.top/Article/details/gtmgjkxjih.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cdnleiting.top/Article/details/gtsyupgzbp.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.sufxvd.cn/Article/details/gtcnfkgvuo.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtvpdjaujf.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.fengsongda.top/Article/details/gtoihpccxs.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.pengpengdd.cyou/Article/details/gtwsswhgrf.html

Go:   // 无：用配置结构体参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtnrjpjuil.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhongyouzk.top/Article/details/gtjwwnuwvy.html

C#:   f(a: 1, b: 2)
来源：http://dali.havefunace.top/Article/details/gtpasrnmjs.html

[C05] 返回多个值
来源：http://dali.cheryme.top/Article/details/gtpvwuobte.html

Py:   return a, b
来源：http://dali.aibaodan.cn/Article/details/gtutwdnjle.html

PHP:  return [$a, $b];
来源：http://dali.cashguo.top/Article/details/gtqnlgknbd.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hfpthk.cn/Article/details/gtrifqzgbt.html

TS:   return { a, b };
来源：http://dali.cqqwz.cn/Article/details/gtciwyjhcu.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yonumen.top/Article/details/gtmfshxcrn.html

Go:   return a, b
来源：http://dali.gaohongyu789.top/Article/details/gtgqztqrop.html

Ruby: return a, b
来源：http://dali.haohaochexian.top/Article/details/gtyulzffef.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yonumen.top/Article/details/gtmynznwsk.html

[C06] 匿名函数 / lambda
来源：http://dali.kuanghao11.cn/Article/details/gtzynssgsu.html

Py:   square = lambda x: x * x
来源：http://dali.aizwys.cn/Article/details/gteipojiab.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.shuidangran.top/Article/details/gtblfrkvsg.html

JS:   const square = x => x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gtmmdspeoa.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhixingplan.top/Article/details/gtahjuuurm.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gtuylqddad.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.andypj.xyz/Article/details/gtlpcvualq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.gotoacloud.top/Article/details/gtdhpvwoei.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yj202588.top/Article/details/gtrydwhasn.html

[C07] 把函数作为参数传入
来源：http://dali.dianchejie.cn/Article/details/gtcdnfzssq.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.iojbl.cn/Article/details/gtbbveclzv.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.aibaodan.cn/Article/details/gtyxdugrfz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.andypj.xyz/Article/details/gtnfkljyws.html

TS:   arr.map(String)
来源：http://dali.dianchejie.cn/Article/details/gtxyfnvobs.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtuffqqtdt.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.nanxuanxn.top/Article/details/gtzgqugqfw.html

Ruby: arr.map(&:upcase)
来源：http://dali.hfpthk.cn/Article/details/gtcpowvqlu.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.snrcjt.cn/Article/details/gtsrvknrls.html

[C08] 闭包
来源：http://dali.yangfankeji.com/Article/details/gtrxassbwt.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhiwuduotai.top/Article/details/gtmksadwsq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hywenlv.cn/Article/details/gtljkrznqj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hammf.cn/Article/details/gtdgasrogt.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.dashuyun.cn/Article/details/gtonbyqmkn.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.316326.xyz/Article/details/gtrifeizqr.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.ivvv.top/Article/details/gttarwzdxb.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zdqjudy.top/Article/details/gtdphupeco.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.snrcjt.cn/Article/details/gtbismtpha.html

[C09] 递归
来源：http://dali.xinyue.icu/Article/details/gtwojgnfei.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.tian-w.cn/Article/details/gtflpdbcnm.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzbdqcfuw.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfwomodco.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.dashuyun.cn/Article/details/gtsogecyqf.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.pycfn.com/Article/details/gtlvipkhcr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jqgfzy.top/Article/details/gtpnrjqeqf.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhixingplan.top/Article/details/gtkdpuqpjc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhiwuduotai.top/Article/details/gtpycvifxr.html

[C10] 变量作用域
来源：http://dali.vqdsnc.cn/Article/details/gtsypvimkp.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhixingplan.top/Article/details/gtddpvqozn.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sxryk.cn/Article/details/gtippfjtxm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.tian-w.cn/Article/details/gterxdyqoe.html

TS:   同 JS
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjgutbjcp.html

Java: 方法内为块级作用域
来源：http://dali.0kj1m.cn/Article/details/gtumqbqptc.html

Go:   花括号块级作用域
来源：http://dali.tian-w.cn/Article/details/gtztjwsdvf.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.bjfxy.top/Article/details/gtznijhapw.html

C#:   块级作用域
来源：http://dali.dianchejie.cn/Article/details/gttrgpbypm.html

[C11] 模块导入与导出
来源：http://dali.yueranfly.top/Article/details/gtjxqfeyzi.html

Py:   from module import func
来源：http://dali.sysykeji.top/Article/details/gtjesioxtd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcmuqrfas.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jiagoushi.top/Article/details/gtvqbtsski.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hywenlv.cn/Article/details/gtdqwfwzbv.html

Java: import java.util.List;
来源：http://dali.pengpengdd.cyou/Article/details/gtogviwbwv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.iojbl.cn/Article/details/gtnrauvyzs.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xziqi.cn/Article/details/gtdjobdlio.html

C#:   using System.Text;
来源：http://dali.jianghu66.top/Article/details/gtkikyfcjj.html

[C12] 立即执行函数 IIFE
来源：http://dali.tanke756.top/Article/details/gtalahlktz.html

Py:   (lambda: print("run"))()
来源：http://dali.guowangkeji.top/Article/details/gtroorujmc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.vqdsnc.cn/Article/details/gtrmewdchq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shanyushiyangkeji.top/Article/details/gttxhqewlo.html

TS:   (() => { console.log("run"); })();
来源：http://dali.nanxinkj.top/Article/details/gtbczsremy.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.nwbrower.top/Article/details/gtuhhkjhht.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhoulong.xyz/Article/details/gtddkpwmtu.html

Ruby: -> { puts "run" }.call
来源：http://dali.xziqi.cn/Article/details/gtixmhbbjz.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.birdmap.top/Article/details/gtjhaboeiy.html

[C13] 类型声明 / 类型注解
来源：http://dali.yangfankeji.com/Article/details/gtxuxqduul.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.iojbl.cn/Article/details/gtsaxswbcb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gtjzqwlwip.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hongshengwenyu.top/Article/details/gtvfdhswpe.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gtwnzyeghe.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gtedpriogy.html

Go:   func add(a, b int) int
来源：http://dali.xylfe.cn/Article/details/gtwbqpavmd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.9152youxi.cn/Article/details/gtwupwnjqx.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.chenlongwang.top/Article/details/gtdvotnqbt.html

[C14] 泛型函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzgfxfcya.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jlsjyb.cn/Article/details/gtluotxbcl.html

PHP:  // 无泛型
来源：http://dali.sxryk.cn/Article/details/gtrgagrdli.html

JS:   // 无泛型
来源：http://dali.hysaishi.cn/Article/details/gtijwkkpdd.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.fzhhl.top/Article/details/gtjtiimpgs.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jinqigufen.top/Article/details/gthgnztxqg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hfpthk.cn/Article/details/gtxrcsmwjo.html

Ruby: # 无泛型
来源：http://dali.meibo888.top/Article/details/gtezjoauhl.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.redwolf501.top/Article/details/gtsyyfikuv.html

[C15] 解构 / 展开参数
来源：http://dali.jiagoushi.top/Article/details/gtnewdnubj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ydzc1.top/Article/details/gtugovwkqh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhengqikj.top/Article/details/gtagxdhgar.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jqgfzy.top/Article/details/gtltvmhofo.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sysykeji.top/Article/details/gtecinfbcl.html

Java: // 无解构
来源：http://dali.yongpay.top/Article/details/gtrkwmocgh.html

Go:   // 无解构
来源：http://dali.feifeiyinyue.top/Article/details/gtygkijwgn.html

Ruby: a, b = pair
来源：http://dali.quarkkingdee.top/Article/details/gtpbsokjqr.html

C#:   var (a, b) = pair;
来源：http://dali.dianchejie.cn/Article/details/gtyuuxkwfn.html

[C16] 函数 / 方法重载
来源：http://dali.chenjidiqi.icu/Article/details/gtletibfki.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.c1oappe.top/Article/details/gtaqfvfypv.html

PHP:  // 无重载
来源：http://dali.ybcxt.top/Article/details/gtozlglapv.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jianghu66.top/Article/details/gtqyzadlud.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhengqikj.top/Article/details/gtinqeuipa.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hammf.cn/Article/details/gthfgpsfdr.html

Go:   // 无重载：用不同函数名
来源：http://dali.xziqi.cn/Article/details/gtbfvikobm.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jianghu66.top/Article/details/gtbqmxbmni.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shuidangran.top/Article/details/gteoysthzn.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtgwjryfke.html

D. 数组 / 列表 / 集合
来源：http://dali.jiagoushi.top/Article/details/gtfaqrbpfv.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtzliazkcs.html

[D01] 创建数组 / 列表
来源：http://dali.zycfv.cn/Article/details/gtqhcjofgw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.meibo888.top/Article/details/gtcayuzwbo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cucudq.cn/Article/details/gtixbdfjfi.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yongpay.top/Article/details/gtprkusgvk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.nanxinkj.top/Article/details/gtqnrxzhaj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.daxiang520.top/Article/details/gtauidhzri.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.daria6918.cn/Article/details/gthctpuggv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhixingplan.top/Article/details/gtwmpvwuta.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ydzc1.top/Article/details/gtnrrschlk.html

[D02] 追加元素到末尾
来源：http://dali.jinqigfzy.top/Article/details/gtpeoxjcwm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.fzhhl.top/Article/details/gtfnmyxnrp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jqgfzy.top/Article/details/gtogdjjlsn.html

JS:   arr.push(4);
来源：http://dali.daria6918.cn/Article/details/gthopmbxfa.html

TS:   arr.push(4);
来源：http://dali.xinyue.icu/Article/details/gtbwkezigl.html

Java: list.add(4);
来源：http://dali.feifeiyinyue.top/Article/details/gtcxwmhaxf.html

Go:   arr = append(arr, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gtmlvxdbny.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmdygpgl.html

C#:   list.Add(4);
来源：http://dali.ybcxt.top/Article/details/gtdoxhwhuw.html

[D03] 在指定位置插入元素
来源：http://dali.wangdashe.top/Article/details/gtyxzzvljg.html

Py:   arr.insert(0, 0)
来源：http://dali.cheryme.top/Article/details/gtrqficuvc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttkbpupsx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.svipenyu.cn/Article/details/gtfntmaqzd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yueranfly.top/Article/details/gtrflmnbru.html

Java: list.add(0, 0);
来源：http://dali.zdqjudy.top/Article/details/gteqdqhlul.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.9152youxi.cn/Article/details/gtgrtsmaro.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.sysykeji.top/Article/details/gtuyqsscdn.html

C#:   list.Insert(0, 0);
来源：http://dali.zycfv.cn/Article/details/gtbzjlimvp.html

[D04] 删除元素
来源：http://dali.cucudq.cn/Article/details/gtgrmhzukz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.fengsongda.top/Article/details/gtrgxfckqv.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yj20258.top/Article/details/gtgwjlpzxf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yuxming.cn/Article/details/gtdbhfuipp.html

TS:   arr.splice(0, 1);
来源：http://dali.fzhhl.top/Article/details/gtqdcnwcfk.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhixingplan.top/Article/details/gtxtyfxohp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.daria6918.cn/Article/details/gtbtgqbbgs.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.iojbl.cn/Article/details/gtqmqmsffu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cashguo.top/Article/details/gtxkvsiinm.html

[D05] 访问与修改元素
来源：http://dali.hysaishi.cn/Article/details/gttpwxdfyb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangdashe.top/Article/details/gtkyeecfbt.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.dianchejie.cn/Article/details/gtruswyjid.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hnxiangtu.top/Article/details/gtzfccyepd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hysaishi.cn/Article/details/gtiyekeluw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhixingplan.top/Article/details/gtkbiaywgb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hfpthk.cn/Article/details/gtefclwqtb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yonumen.top/Article/details/gtckmmgqfk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.sysykeji.top/Article/details/gtijeevmki.html

[D06] 数组长度
来源：http://dali.zhoulong.xyz/Article/details/gtcxizmofv.html

Py:   len(arr)
来源：http://dali.daxiang520.top/Article/details/gtwdixvoja.html

PHP:  count($arr);
来源：http://dali.sweek.top/Article/details/gtwuvcgeno.html

JS:   arr.length
来源：http://dali.xinyue.icu/Article/details/gtiziuctgj.html

TS:   arr.length
来源：http://dali.vqdsnc.cn/Article/details/gtrwdjtgpm.html

Java: list.size();
来源：http://dali.ydzc1.top/Article/details/gttnzfbspw.html

Go:   len(arr)
来源：http://dali.c1oappe.top/Article/details/gtnpnvppyu.html

Ruby: arr.length; arr.size
来源：http://dali.shangyingyoupin.top/Article/details/gtwrkcvoag.html

C#:   list.Count;
来源：http://dali.xuetiantiany.cn/Article/details/gtewbjpywy.html

[D07] 切片 / 取子数组
来源：http://dali.meibo888.top/Article/details/gtewlxyall.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.gzhubu.top/Article/details/gtrlzkjhsj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.kuanghao11.cn/Article/details/gtwfjlzpeg.html

JS:   arr.slice(1, 4);
来源：http://dali.yueranfly.top/Article/details/gtmtndzqju.html

TS:   arr.slice(1, 4);
来源：http://dali.yj20258888.top/Article/details/gtisvjeulx.html

Java: list.subList(1, 4);
来源：http://dali.meibo888.top/Article/details/gtubphpiyb.html

Go:   arr[1:4]
来源：http://dali.haohaochexian.top/Article/details/gtfuwkuret.html

Ruby: arr[1, 3]
来源：http://dali.yj20258.top/Article/details/gtmdasxaox.html

C#:   list.GetRange(1, 3);
来源：http://dali.hysaishi.cn/Article/details/gtdrsnoher.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gtulhleuud.html

Py:   a + b;  a.extend(b)
来源：http://dali.tanke756.top/Article/details/gtpxaejrlh.html

PHP:  array_merge($a, $b);
来源：http://dali.dashuyun.cn/Article/details/gtmkczfxwb.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.daria6918.cn/Article/details/gttkxgtrcf.html

TS:   [...a, ...b];
来源：http://dali.zhengqikj.top/Article/details/gtopuhtyeo.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.bjfxy.top/Article/details/gtwvuyozdt.html

Go:   append(a, b...)
来源：http://dali.nanxinkj.top/Article/details/gtueaptvyb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xylfe.cn/Article/details/gtxgnsmoxw.html

C#:   a.Concat(b).ToList()
来源：http://dali.cqqwz.cn/Article/details/gtnozragtu.html

[D09] 排序（升序）
来源：http://dali.havefunace.top/Article/details/gtmkaxsxng.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtndztmsby.html

PHP:  sort($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtlffbrvac.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xuanzx.com/Article/details/gtbwygsfbv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cdnleiting.top/Article/details/gtrbidrqug.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.nwbrower.top/Article/details/gtkxpyuwoc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.sweek.top/Article/details/gtiwphqxmn.html

Ruby: arr.sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkwwqkamm.html

C#:   list.Sort();
来源：http://dali.fzhhl.top/Article/details/gtyskwzfvc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xuetiantiany.cn/Article/details/gtdpycqzic.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xylfe.cn/Article/details/gtbyyazdfn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.mhx1999.top/Article/details/gtmjtfyzgt.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ybcxt.top/Article/details/gtcnexdykn.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.9152youxi.cn/Article/details/gtndgwiajn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yonumen.top/Article/details/gtaaegebcg.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hywenlv.cn/Article/details/gtpakzqljb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zdqjudy.top/Article/details/gtrjuohayz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yueranfly.top/Article/details/gtlgvplxjk.html

[D11] 反转数组
来源：http://dali.vqdsnc.cn/Article/details/gtfzlaphlm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sxryk.cn/Article/details/gtwkgnmuqw.html

PHP:  array_reverse($arr);
来源：http://dali.ydzc1.top/Article/details/gtfssdqzyb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shuidangran.top/Article/details/gttefylpeg.html

TS:   [...arr].reverse();
来源：http://dali.ybcxt.top/Article/details/gtqmsruule.html

Java: Collections.reverse(list);
来源：http://dali.chenjidiqi.icu/Article/details/gtkkwypqin.html

Go:   slices.Reverse(arr)
来源：http://dali.tian-w.cn/Article/details/gtncsvuqik.html

Ruby: arr.reverse
来源：http://dali.daria6918.cn/Article/details/gtgrtgrgcj.html

C#:   list.Reverse();
来源：http://dali.hywenlv.cn/Article/details/gtrxqchcqg.html

[D12] 查找元素下标
来源：http://dali.jqgfzy.top/Article/details/gtsxdvyzva.html

Py:   arr.index(x);  x in arr
来源：http://dali.jqgfzy.top/Article/details/gtebkbuumn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.tianlin.xyz/Article/details/gtoflnnmez.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hongshengwenyu.top/Article/details/gtvpeqebug.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigfzy.top/Article/details/gtuekwwgvr.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.smart0.xyz/Article/details/gtdmkqtvdu.html

Go:   slices.Index(arr, x)
来源：http://dali.fzhhl.top/Article/details/gtnidxtugf.html

Ruby: arr.index(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtabhimuln.html

C#:   list.IndexOf(x);
来源：http://dali.fzhhl.top/Article/details/gtkkpwdvtr.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hnqzz.top/Article/details/gtftyvizab.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ybcxt.top/Article/details/gtqpubeeec.html


<!-- 参考信息 -->