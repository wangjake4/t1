代发 wailian999

[B13] 判断是否为数字
来源：http://dali.hongshengwenyu.top/Article/details/gtztkamsrn.html

Py:   isinstance(x, (int, float))
来源：http://dali.xuanzx.com/Article/details/gthhqqlriq.html

PHP:  is_numeric($x)
来源：http://dali.fzhhl.top/Article/details/gtotmsaaeh.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtqypyohcd.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.feifeiyinyue.top/Article/details/gttunaaeux.html

Java: x instanceof Number
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtssunczgk.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.0kj1m.cn/Article/details/gtpdfivrwn.html

Ruby: x.is_a?(Numeric)
来源：http://dali.sxryk.cn/Article/details/gtckhilmhp.html

C#:   x is int or double or decimal
来源：http://dali.nwbrower.top/Article/details/gttficevzj.html

[B14] 判断值是否在集合内
来源：http://dali.meibo888.top/Article/details/gtnjdrrvzv.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqicseprl.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.cqqwz.cn/Article/details/gtzrdoyjjx.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.9152youxi.cn/Article/details/gtpecqidww.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yonumen.top/Article/details/gtcbejxadz.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtszgtlcor.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.nwbrower.top/Article/details/gtqiyidcam.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtlnqqjupt.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.316326.xyz/Article/details/gthgpxspdp.html

[B15] 布尔运算与取反
来源：http://dali.nwbrower.top/Article/details/gtnoffgdtk.html

Py:   a and b or not c
来源：http://dali.chenzaomai.com/Article/details/gtpavivtbq.html

PHP:  $a && $b || !$c
来源：http://dali.xziqi.cn/Article/details/gtgkynnovs.html

JS:   a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gtpbobzhcd.html

TS:   a && b || !c
来源：http://dali.nwbrower.top/Article/details/gtjaoedoci.html

Java: a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gtzbvpnima.html

Go:   a && b || !c
来源：http://dali.yuxming.cn/Article/details/gtklutteqe.html

Ruby: a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gtngxdgkzd.html

C#:   a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gtywnlwsjd.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jianghu66.top/Article/details/gtrhrdpkfv.html

Py:   if not data: return
来源：http://dali.chenjidiqi.icu/Article/details/gtxyokwydp.html

PHP:  if (!$data) { return; }
来源：http://dali.zhongyouzk.top/Article/details/gtgfgeiljf.html

JS:   if (!data) return;
来源：http://dali.cheryme.top/Article/details/gtxjbmxsmz.html

TS:   if (!data) return;
来源：http://dali.tianlin.xyz/Article/details/gtuoqeomme.html

Java: if (data == null) return;
来源：http://dali.yuanzhike.top/Article/details/gtkulbypdk.html

Go:   if data == nil { return }
来源：http://dali.yonumen.top/Article/details/gtbsyiigme.html

Ruby: return if data.nil?
来源：http://dali.nwbrower.top/Article/details/gtuooxovan.html

C#:   if (data == null) return;
来源：http://dali.yj202588.top/Article/details/gtswczrnft.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtmlokmdoe.html

C. 函数与作用域
来源：http://dali.jlsjyb.cn/Article/details/gtedjmnhum.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtxmejuinc.html

[C01] 定义函数
来源：http://dali.zhongyouzk.top/Article/details/gtqpqznrpm.html

Py:   def add(a, b): return a + b
来源：http://dali.sweek.top/Article/details/gtchzacskr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gaohongyu789.top/Article/details/gtvnvfftyw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gtgtmcmrjz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtisrolztc.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gtizpfnlsh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hnqzz.top/Article/details/gthsboimut.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ybcxt.top/Article/details/gttyyljzud.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gtjvvfyscb.html

[C02] 默认参数
来源：http://dali.jianghu66.top/Article/details/gtgcttvedl.html

Py:   def greet(name="World"): return name
来源：http://dali.xinyue.icu/Article/details/gtqmldakzj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yuanzhike.top/Article/details/gtvabssvii.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtuvspjcfn.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jyoumei.cn/Article/details/gtpzdvmuac.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.c1oappe.top/Article/details/gtrvdasrll.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shangyingyoupin.top/Article/details/gttwokdvzp.html

Ruby: def greet(name = "World") = name
来源：http://dali.yongpay.top/Article/details/gthnopdrnp.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.fzhhl.top/Article/details/gteqgfjnru.html

[C03] 可变参数
来源：http://dali.xuanzx.com/Article/details/gtcevmhxrr.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhixingplan.top/Article/details/gtnalvaobv.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.tianlin.xyz/Article/details/gtebcuwnoo.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gogol.net.cn/Article/details/gtdzetmexs.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gteaghcbdp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sxryk.cn/Article/details/gtfccmpkdu.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cucudq.cn/Article/details/gtlxhsznwh.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hnqzz.top/Article/details/gtpnvithub.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhaomingkeji.xyz/Article/details/gthjzjzyso.html

[C04] 命名参数 / 关键字参数
来源：http://dali.pengpengdd.cyou/Article/details/gtotbtrbuq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gtdhyngevf.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yueranfly.top/Article/details/gtgrgueayd.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xinyue.icu/Article/details/gtjsktvxtz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.gotoacloud.top/Article/details/gtymsrhflo.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hywenlv.cn/Article/details/gtswhzwden.html

Go:   // 无：用配置结构体参数
来源：http://dali.daria6918.cn/Article/details/gtuywtrwff.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yvedp.cn/Article/details/gtqapqgafm.html

C#:   f(a: 1, b: 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtuprykihj.html

[C05] 返回多个值
来源：http://dali.jiagoushi.top/Article/details/gtdpksladn.html

Py:   return a, b
来源：http://dali.cheryme.top/Article/details/gtutudkytw.html

PHP:  return [$a, $b];
来源：http://dali.cqqwz.cn/Article/details/gtlebqslto.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ydzc1.top/Article/details/gtmzrarnqo.html

TS:   return { a, b };
来源：http://dali.zhiwuduotai.top/Article/details/gtxcnkbcqc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cashguo.top/Article/details/gttdczvnyy.html

Go:   return a, b
来源：http://dali.aizwys.cn/Article/details/gtxfmntwwu.html

Ruby: return a, b
来源：http://dali.daria6918.cn/Article/details/gthdjuhuik.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yangfankeji.com/Article/details/gtixwcqbba.html

[C06] 匿名函数 / lambda
来源：http://dali.sufxvd.cn/Article/details/gthabsqvtg.html

Py:   square = lambda x: x * x
来源：http://dali.shzxlz.cn/Article/details/gtcjibavpv.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cdnleiting.top/Article/details/gtbdjcbbnc.html

JS:   const square = x => x * x;
来源：http://dali.jlsjyb.cn/Article/details/gtloumcuqe.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gtwdwlaxfp.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.dianchejie.cn/Article/details/gtxvsvtzwa.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhixingplan.top/Article/details/gtmzaclang.html

Ruby: square = ->(x) { x * x }
来源：http://dali.guannengcc.top/Article/details/gtpeiocgks.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.birdmap.top/Article/details/gtprrhupmj.html

[C07] 把函数作为参数传入
来源：http://dali.jqgufenzy.top/Article/details/gtrqvlifao.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jqgufenzy.top/Article/details/gtfvnnmjmm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hnxiangtu.top/Article/details/gtzhkcsmez.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ehwqpu.com/Article/details/gtclhggadc.html

TS:   arr.map(String)
来源：http://dali.haohaochexian.top/Article/details/gtipvhgbhm.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.nanxuanxn.top/Article/details/gteozeikqm.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.daxiang520.top/Article/details/gtgllaiout.html

Ruby: arr.map(&:upcase)
来源：http://dali.cheryme.top/Article/details/gtbdwkklwi.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cucudq.cn/Article/details/gtiltcijyd.html

[C08] 闭包
来源：http://dali.hnqzz.top/Article/details/gttnrknjqy.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yueranfly.top/Article/details/gtxllwunbp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xylfe.cn/Article/details/gtjhujyeqx.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.sufxvd.cn/Article/details/gtoavsgegw.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ehwqpu.com/Article/details/gtimrmiqyq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.pycfn.com/Article/details/gtfqxcrarr.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.nanxinkj.top/Article/details/gtfuxspeiv.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.kuanghao11.cn/Article/details/gtjmreymnc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhixingplan.top/Article/details/gtygsaqxjo.html

[C09] 递归
来源：http://dali.ybcxt.top/Article/details/gtibamaceo.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtrxhbpfai.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.fzhhl.top/Article/details/gtvzsbjvkr.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hnqzz.top/Article/details/gtdhrzmqsg.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zycfv.cn/Article/details/gtyjchepcx.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.tian-w.cn/Article/details/gtdogrxznj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sxryk.cn/Article/details/gtxiemgimg.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xinyue.icu/Article/details/gtqyduvuab.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jqgufenzy.top/Article/details/gtciqzkemh.html

[C10] 变量作用域
来源：http://dali.chenzaomai.com/Article/details/gtnopfdtop.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gzhubu.top/Article/details/gtgsjohfxn.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.kuanghao11.cn/Article/details/gtvmyjtjsy.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.pycfn.com/Article/details/gtezchexyu.html

TS:   同 JS
来源：http://dali.dianchejie.cn/Article/details/gtxyyyrxeb.html

Java: 方法内为块级作用域
来源：http://dali.iojbl.cn/Article/details/gtubrrmgkx.html

Go:   花括号块级作用域
来源：http://dali.chenzaomai.com/Article/details/gtvimldgif.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.snrcjt.cn/Article/details/gtxuaghilf.html

C#:   块级作用域
来源：http://dali.cqqwz.cn/Article/details/gtlmweeofc.html

[C11] 模块导入与导出
来源：http://dali.meibo888.top/Article/details/gtsbdqgqzz.html

Py:   from module import func
来源：http://dali.yvedp.cn/Article/details/gtjarcbmes.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.feifeiyinyue.top/Article/details/gtmvkkxzjs.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.wangdashe.top/Article/details/gteawjdhzv.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.gotoacloud.top/Article/details/gtyxyphyuv.html

Java: import java.util.List;
来源：http://dali.zdqjudy.top/Article/details/gtdakpoytn.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ydzc1.top/Article/details/gtakweuesg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.nwbrower.top/Article/details/gtucmifelv.html

C#:   using System.Text;
来源：http://dali.yanxiufei.cn/Article/details/gttllfhalj.html

[C12] 立即执行函数 IIFE
来源：http://dali.andypj.xyz/Article/details/gtltpyasqf.html

Py:   (lambda: print("run"))()
来源：http://dali.xuanzx.com/Article/details/gtlypgpccn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.feifeiyinyue.top/Article/details/gtllgzhgvy.html

JS:   (() => { console.log("run"); })();
来源：http://dali.tianlin.xyz/Article/details/gtmuppezxo.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shzxlz.cn/Article/details/gtghvjxgiy.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yonumen.top/Article/details/gtexojivjq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yongpay.top/Article/details/gtxfhjahbc.html

Ruby: -> { puts "run" }.call
来源：http://dali.haohaochexian.top/Article/details/gtrwgkubas.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hongshengwenyu.top/Article/details/gthiqgqosr.html

[C13] 类型声明 / 类型注解
来源：http://dali.pycfn.com/Article/details/gtzivsyklp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sxryk.cn/Article/details/gtkcfkilbr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guannengcc.top/Article/details/gtswrslmqr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jyoumei.cn/Article/details/gtgaitlnac.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gtpzewpurp.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gtwceaflua.html

Go:   func add(a, b int) int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtykwvsrla.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cheryme.top/Article/details/gtgefndhrj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ywan-chungtsiang.top/Article/details/gttsicqlmc.html

[C14] 泛型函数
来源：http://dali.bjfxy.top/Article/details/gtmppsvksp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.mhx1999.top/Article/details/gthczhnqio.html

PHP:  // 无泛型
来源：http://dali.xuanzx.com/Article/details/gtinzszovv.html

JS:   // 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gtjdmdmbvo.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhengqikj.top/Article/details/gtgpxsgsdy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yonumen.top/Article/details/gtlqottwbx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gtbliwhemd.html

Ruby: # 无泛型
来源：http://dali.nanxuanxn.top/Article/details/gtjltloggj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhongyouzk.top/Article/details/gtyenpyrnr.html

[C15] 解构 / 展开参数
来源：http://dali.guannengcc.top/Article/details/gtzyaxpudd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.redwolf501.top/Article/details/gtphcwtbkx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.redwolf501.top/Article/details/gterjddkdw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.kuanghao11.cn/Article/details/gthmdhqpge.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.mhx1999.top/Article/details/gtwakxghuh.html

Java: // 无解构
来源：http://dali.ydzc1.top/Article/details/gtmjezajzi.html

Go:   // 无解构
来源：http://dali.guannengcc.top/Article/details/gttdkqtqao.html

Ruby: a, b = pair
来源：http://dali.cucudq.cn/Article/details/gtxofcwmvt.html

C#:   var (a, b) = pair;
来源：http://dali.cashguo.top/Article/details/gtfitvwtmp.html

[C16] 函数 / 方法重载
来源：http://dali.cashguo.top/Article/details/gtjbrwfjsd.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yueranfly.top/Article/details/gtixokuuxv.html

PHP:  // 无重载
来源：http://dali.jianghu66.top/Article/details/gtswenizkc.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhiwuduotai.top/Article/details/gtlsrbyopx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.andypj.xyz/Article/details/gtpnvvtlug.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shuidangran.top/Article/details/gtmdcyruwc.html

Go:   // 无重载：用不同函数名
来源：http://dali.yanxiufei.cn/Article/details/gtncdpjdfh.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shangyingyoupin.top/Article/details/gtykpeabth.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.nanxuanxn.top/Article/details/gtvscqcdol.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtncstknyl.html

D. 数组 / 列表 / 集合
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrfdhliii.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtibpuytea.html

[D01] 创建数组 / 列表
来源：http://dali.hammf.cn/Article/details/gtxqvtiphs.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.daxiang520.top/Article/details/gtgxkzommz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hnxiangtu.top/Article/details/gtmjismkjh.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.chenjidiqi.icu/Article/details/gtsvjmvwpg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.nanxuanxn.top/Article/details/gtgsiigttq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hammf.cn/Article/details/gtvqqwkuug.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yongpay.top/Article/details/gtgteejycu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.tanke756.top/Article/details/gttyayjscc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.andypj.xyz/Article/details/gtjkqcusnb.html

[D02] 追加元素到末尾
来源：http://dali.yj20258.top/Article/details/gtfoldxtya.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.bjfxy.top/Article/details/gtxyefwftj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cqqwz.cn/Article/details/gtscqsjxyo.html

JS:   arr.push(4);
来源：http://dali.hnxiangtu.top/Article/details/gturokyclx.html

TS:   arr.push(4);
来源：http://dali.chenzaomai.com/Article/details/gtgrrtvagn.html

Java: list.add(4);
来源：http://dali.vqdsnc.cn/Article/details/gtvmrsrbtp.html

Go:   arr = append(arr, 4)
来源：http://dali.guannengcc.top/Article/details/gtfbloauvr.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.haohaochexian.top/Article/details/gtoaoyjkxv.html

C#:   list.Add(4);
来源：http://dali.cqqwz.cn/Article/details/gtdhpebvic.html

[D03] 在指定位置插入元素
来源：http://dali.zhoulong.xyz/Article/details/gtfcfbbzlm.html

Py:   arr.insert(0, 0)
来源：http://dali.shzxlz.cn/Article/details/gtbcktmqmj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sweek.top/Article/details/gtgslgmrjo.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jiagoushi.top/Article/details/gtkbgwgpqa.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xylfe.cn/Article/details/gtrskxrbeg.html

Java: list.add(0, 0);
来源：http://dali.fzhhl.top/Article/details/gtncdhemgo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hammf.cn/Article/details/gtpoaptxhl.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shuidangran.top/Article/details/gttnirvvlg.html

C#:   list.Insert(0, 0);
来源：http://dali.redwolf501.top/Article/details/gtlwgvnktk.html

[D04] 删除元素
来源：http://dali.hywenlv.cn/Article/details/gtpwdxvgut.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shangyingyoupin.top/Article/details/gtplvlkodh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yongpay.top/Article/details/gtggzwnoav.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.pycfn.com/Article/details/gtkhiubfpx.html

TS:   arr.splice(0, 1);
来源：http://dali.tianlin.xyz/Article/details/gtdiwjhgnh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gogol.net.cn/Article/details/gtadoqyagg.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.pycfn.com/Article/details/gtxwqmmsbh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cheryme.top/Article/details/gtbtpnsiap.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jiagoushi.top/Article/details/gtzgsbaqpm.html

[D05] 访问与修改元素
来源：http://dali.fengsongda.top/Article/details/gtgwzlcyao.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinyuanbaomall.cn/Article/details/gtanxqgoju.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrfotrqyb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hysaishi.cn/Article/details/gtwixsxmyr.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.daxiang520.top/Article/details/gtbecodvva.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jqgfzy.top/Article/details/gtdbptxhcd.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.chenzaomai.com/Article/details/gtknxavrzj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ydzc1.top/Article/details/gtlziifwsm.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gaohongyu789.top/Article/details/gttdrkctub.html

[D06] 数组长度
来源：http://dali.hammf.cn/Article/details/gtnanpbjcq.html

Py:   len(arr)
来源：http://dali.daria6918.cn/Article/details/gtdzqlwljy.html

PHP:  count($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtadfnmkny.html

JS:   arr.length
来源：http://dali.cdnleiting.top/Article/details/gtgbsxywgp.html

TS:   arr.length
来源：http://dali.xuetiantiany.cn/Article/details/gtpownsswn.html

Java: list.size();
来源：http://dali.cheryme.top/Article/details/gtywncvhsi.html

Go:   len(arr)
来源：http://dali.gzhubu.top/Article/details/gtfbjykfaz.html

Ruby: arr.length; arr.size
来源：http://dali.yuanzhike.top/Article/details/gtfnavvfab.html

C#:   list.Count;
来源：http://dali.meibo888.top/Article/details/gtplhzqven.html

[D07] 切片 / 取子数组
来源：http://dali.aibaodan.cn/Article/details/gtpxpkdfck.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinqigfzy.top/Article/details/gtdvthasqs.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xuanzx.com/Article/details/gtbiwhsfmz.html

JS:   arr.slice(1, 4);
来源：http://dali.cashguo.top/Article/details/gtjiamacgy.html

TS:   arr.slice(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gtxxkdfvst.html

Java: list.subList(1, 4);
来源：http://dali.cqqwz.cn/Article/details/gtkaxkhtut.html

Go:   arr[1:4]
来源：http://dali.zhengqikj.top/Article/details/gttulgldrg.html

Ruby: arr[1, 3]
来源：http://dali.fzhhl.top/Article/details/gtazixvdaj.html

C#:   list.GetRange(1, 3);
来源：http://dali.pycfn.com/Article/details/gtpldqoiqx.html

[D08] 合并两个数组
来源：http://dali.birdmap.top/Article/details/gtdcvyxese.html

Py:   a + b;  a.extend(b)
来源：http://dali.gaohongyu789.top/Article/details/gtafgibczr.html

PHP:  array_merge($a, $b);
来源：http://dali.hongshengwenyu.top/Article/details/gtupxxfblx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xinyue.icu/Article/details/gtvqswdbtp.html

TS:   [...a, ...b];
来源：http://dali.wangdashe.top/Article/details/gtcbtianjv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtysyzzxzc.html

Go:   append(a, b...)
来源：http://dali.shzxlz.cn/Article/details/gtolsuageo.html

Ruby: a + b;  a.concat(b)
来源：http://dali.gzhubu.top/Article/details/gthfrdlxqm.html

C#:   a.Concat(b).ToList()
来源：http://dali.316326.xyz/Article/details/gtdjkvaixa.html

[D09] 排序（升序）
来源：http://dali.shanyushiyangtech.top/Article/details/gtgttjmlvy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgufenzy.top/Article/details/gtvnsqnrdq.html

PHP:  sort($arr);
来源：http://dali.hnqzz.top/Article/details/gtcndlffpm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yonumen.top/Article/details/gtodoffaei.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.birdmap.top/Article/details/gtmahcogou.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yuanzhike.top/Article/details/gtmvieazis.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shuidangran.top/Article/details/gtgtmcaxiw.html

Ruby: arr.sort
来源：http://dali.jinqigfzy.top/Article/details/gtsvqxqjpt.html

C#:   list.Sort();
来源：http://dali.xuetiantiany.cn/Article/details/gtxziveiuh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.nanxuanxn.top/Article/details/gtoojqvewi.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.c1oappe.top/Article/details/gtkomqglsg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xziqi.cn/Article/details/gtkkpuiczg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtraeertuy.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xziqi.cn/Article/details/gtunjpshtb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zdqjudy.top/Article/details/gtzkjlpcyj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xylfe.cn/Article/details/gthklzepqm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cashguo.top/Article/details/gtgnhhvlln.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jianghu66.top/Article/details/gtaxiszfrn.html

[D11] 反转数组
来源：http://dali.yj20258888.top/Article/details/gtowmemhqk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.pengpengdd.cyou/Article/details/gtnirthvka.html

PHP:  array_reverse($arr);
来源：http://dali.jyoumei.cn/Article/details/gtuuzuxxcy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yj202588.top/Article/details/gtewttgjyd.html

TS:   [...arr].reverse();
来源：http://dali.316326.xyz/Article/details/gtdajdnmqp.html

Java: Collections.reverse(list);
来源：http://dali.havefunace.top/Article/details/gtnregnbnk.html

Go:   slices.Reverse(arr)
来源：http://dali.bjfxy.top/Article/details/gthhsqwirg.html

Ruby: arr.reverse
来源：http://dali.chenlongwang.top/Article/details/gtegmtimew.html

C#:   list.Reverse();
来源：http://dali.jinghuilouyu.cn/Article/details/gtuqwyzhav.html

[D12] 查找元素下标
来源：http://dali.yanxiufei.cn/Article/details/gtxaddjugk.html

Py:   arr.index(x);  x in arr
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpeatbplo.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gzhubu.top/Article/details/gtwcfrepem.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.0kj1m.cn/Article/details/gtwudpgngw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yuxming.cn/Article/details/gtjikonthz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gtzxhtvfot.html

Go:   slices.Index(arr, x)
来源：http://dali.hnqzz.top/Article/details/gtvjppdqui.html

Ruby: arr.index(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthspbmhei.html

C#:   list.IndexOf(x);
来源：http://dali.zhoulong.xyz/Article/details/gtcmwjfepa.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yj20258888.top/Article/details/gtgqoxadiq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.aizwys.cn/Article/details/gtonzrkexh.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.c1oappe.top/Article/details/gtcnhqemim.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xuanzx.com/Article/details/gtcikzebfp.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jqgfzy.top/Article/details/gtzzdtglal.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ybcxt.top/Article/details/gtmuwahxxu.html


<!-- 参考信息 -->