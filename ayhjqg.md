代发 wailian999

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.chenjidiqi.icu/Article/details/gtxwojfwax.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.fengsongda.top/Article/details/gtvuvhqicc.html

[B11] 生成数字序列 / 区间
来源：http://dali.pycfn.com/Article/details/gtlzwwwbod.html

Py:   list(range(0, 10, 2))
来源：http://dali.ydzc1.top/Article/details/gtadfrfdcf.html

PHP:  range(0, 10, 2);
来源：http://dali.yvedp.cn/Article/details/gtoiolxysq.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.316326.xyz/Article/details/gtwbudpnwm.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.316326.xyz/Article/details/gtcgxaisqq.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtmncrkbbh.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.cdnleiting.top/Article/details/gtmvlaguck.html

Ruby: (0...10).step(2).to_a
来源：http://dali.tian-w.cn/Article/details/gttpzyvdqt.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yuanzhike.top/Article/details/gtjvcuwywy.html

[B12] 跳出多层循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtblyipcef.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cdnleiting.top/Article/details/gtfuqamuow.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yj20258.top/Article/details/gtweiswsxp.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nwbrower.top/Article/details/gtlguwxubd.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnqzz.top/Article/details/gtsqafzega.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.xuetiantiany.cn/Article/details/gtpxfcplhl.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.316326.xyz/Article/details/gtdpvfnywl.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yangfankeji.com/Article/details/gttuxhioxi.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ybcxt.top/Article/details/gtsjybdrla.html

[B13] 判断是否为数字
来源：http://dali.daxiang520.top/Article/details/gteeskuxpc.html

Py:   isinstance(x, (int, float))
来源：http://dali.hammf.cn/Article/details/gtaazcagyy.html

PHP:  is_numeric($x)
来源：http://dali.c1oappe.top/Article/details/gttbyiudue.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xylfe.cn/Article/details/gtdvbutjpx.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yangfankeji.com/Article/details/gtyeofxcqi.html

Java: x instanceof Number
来源：http://dali.316326.xyz/Article/details/gtljkfgsrj.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zdqjudy.top/Article/details/gtwhdmpkun.html

Ruby: x.is_a?(Numeric)
来源：http://dali.chenjidiqi.icu/Article/details/gtzncjtwgd.html

C#:   x is int or double or decimal
来源：http://dali.chenzaomai.com/Article/details/gtocamrlxm.html

[B14] 判断值是否在集合内
来源：http://dali.ybcxt.top/Article/details/gtfsqityda.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.mhx1999.top/Article/details/gttmewyihg.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.gaohongyu789.top/Article/details/gtnouznqvo.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jyoumei.cn/Article/details/gtgoqhsndj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.gzhubu.top/Article/details/gtxrajwvig.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ehwqpu.com/Article/details/gtiuconcdl.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xuanzx.com/Article/details/gtjshdysyx.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jlsjyb.cn/Article/details/gtbnpccykb.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jlsjyb.cn/Article/details/gtukdnzvai.html

[B15] 布尔运算与取反
来源：http://dali.jianghu66.top/Article/details/gttmubrvxb.html

Py:   a and b or not c
来源：http://dali.yj20258.top/Article/details/gttuqqraep.html

PHP:  $a && $b || !$c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmeucgtbp.html

JS:   a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gtjgyksnsq.html

TS:   a && b || !c
来源：http://dali.jianghu66.top/Article/details/gtntglngwx.html

Java: a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gtesuqxdyt.html

Go:   a && b || !c
来源：http://dali.guannengcc.top/Article/details/gthceangcv.html

Ruby: a && b || !c
来源：http://dali.jqgufenzy.top/Article/details/gtnqpuswco.html

C#:   a && b || !c
来源：http://dali.smart0.xyz/Article/details/gtnxurptap.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.aibaodan.cn/Article/details/gtdbwtbdys.html

Py:   if not data: return
来源：http://dali.smart0.xyz/Article/details/gtmnvxjkwk.html

PHP:  if (!$data) { return; }
来源：http://dali.xuanzx.com/Article/details/gtgownkvsm.html

JS:   if (!data) return;
来源：http://dali.ehwqpu.com/Article/details/gtgjohgtxv.html

TS:   if (!data) return;
来源：http://dali.jyoumei.cn/Article/details/gtbkqkpado.html

Java: if (data == null) return;
来源：http://dali.c1oappe.top/Article/details/gtfabfzvml.html

Go:   if data == nil { return }
来源：http://dali.wangshuangyany.cn/Article/details/gtzljxxdfe.html

Ruby: return if data.nil?
来源：http://dali.jiagoushi.top/Article/details/gtynycapua.html

C#:   if (data == null) return;
来源：http://dali.hammf.cn/Article/details/gtsnkiepqb.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthnbuwyxq.html

C. 函数与作用域
来源：http://dali.ybcxt.top/Article/details/gtlqkchfvt.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtjoboccqe.html

[C01] 定义函数
来源：http://dali.bjfxy.top/Article/details/gtyufdkmli.html

Py:   def add(a, b): return a + b
来源：http://dali.zhixingplan.top/Article/details/gtkqzkjety.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj202588.top/Article/details/gtqbbxwypy.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gtecrzvbaf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gthvhcawfc.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gtiylompjd.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.smart0.xyz/Article/details/gtatkapmws.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cheryme.top/Article/details/gtxahkprzi.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gttbkzutnl.html

[C02] 默认参数
来源：http://dali.jqgfzy.top/Article/details/gtpansikil.html

Py:   def greet(name="World"): return name
来源：http://dali.cheryme.top/Article/details/gtjmxtnean.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ybcxt.top/Article/details/gtszaeroxj.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ivvv.top/Article/details/gtuxsjifju.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.fzhhl.top/Article/details/gtpbsbfxfp.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.gaohongyu789.top/Article/details/gtcmwxxbhm.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yueranfly.top/Article/details/gtmknumpqe.html

Ruby: def greet(name = "World") = name
来源：http://dali.jlsjyb.cn/Article/details/gtkkplvafg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gaohongyu789.top/Article/details/gtyonriojn.html

[C03] 可变参数
来源：http://dali.haohaochexian.top/Article/details/gtccaasplc.html

Py:   def total(*args): return sum(args)
来源：http://dali.xuanzx.com/Article/details/gtvanteqqy.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ydzc1.top/Article/details/gtjjvskjzx.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gotoacloud.top/Article/details/gtwseqasiw.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.redwolf501.top/Article/details/gtylzsryrk.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sweek.top/Article/details/gtznygzgce.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ppjwa.cn/Article/details/gtseyocmrb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhoulong.xyz/Article/details/gtqnaqqral.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yueranfly.top/Article/details/gtrqayslvf.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjhmltytk.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yj20258.top/Article/details/gtusksltpu.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xuetiantiany.cn/Article/details/gtyiwbemry.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.haohaochexian.top/Article/details/gtjwtroeee.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.redwolf501.top/Article/details/gtuxdnhrdl.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.dianchejie.cn/Article/details/gtrrgepcya.html

Go:   // 无：用配置结构体参数
来源：http://dali.hfpthk.cn/Article/details/gtmrmippwi.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yuxming.cn/Article/details/gtcqbcszeo.html

C#:   f(a: 1, b: 2)
来源：http://dali.pycfn.com/Article/details/gtrdsdegiz.html

[C05] 返回多个值
来源：http://dali.yvedp.cn/Article/details/gtntvbedmo.html

Py:   return a, b
来源：http://dali.ybcxt.top/Article/details/gtzbyhecip.html

PHP:  return [$a, $b];
来源：http://dali.cqqwz.cn/Article/details/gtaztrhsno.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhixingplan.top/Article/details/gtftfidvce.html

TS:   return { a, b };
来源：http://dali.dashuyun.cn/Article/details/gtvskjbqeo.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhongyouzk.top/Article/details/gtoiklrude.html

Go:   return a, b
来源：http://dali.hywenlv.cn/Article/details/gticakoccb.html

Ruby: return a, b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtayndgifn.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yongpay.top/Article/details/gtcaqpntpt.html

[C06] 匿名函数 / lambda
来源：http://dali.yuanzhike.top/Article/details/gtetbeiuec.html

Py:   square = lambda x: x * x
来源：http://dali.hammf.cn/Article/details/gtmngwcssr.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.pengpengdd.cyou/Article/details/gtkkdpkznw.html

JS:   const square = x => x * x;
来源：http://dali.yanxiufei.cn/Article/details/gttesysavs.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ydzc1.top/Article/details/gtnhydnwit.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gttnazptoy.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.guowangkeji.top/Article/details/gthrjuyyqp.html

Ruby: square = ->(x) { x * x }
来源：http://dali.vqdsnc.cn/Article/details/gtjhdulhey.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinqigufen.top/Article/details/gtlfodeskb.html

[C07] 把函数作为参数传入
来源：http://dali.shzxlz.cn/Article/details/gtarsllnvy.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.fzhhl.top/Article/details/gtveqkagpw.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cheryme.top/Article/details/gtsixsvmih.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xuetiantiany.cn/Article/details/gtfrlkyoij.html

TS:   arr.map(String)
来源：http://dali.xuanzx.com/Article/details/gtiprhowcx.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtxgpsfxah.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.fengsongda.top/Article/details/gtosaueqrf.html

Ruby: arr.map(&:upcase)
来源：http://dali.guowangkeji.top/Article/details/gtpbxedabz.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xylfe.cn/Article/details/gtlrvjtqqw.html

[C08] 闭包
来源：http://dali.jyoumei.cn/Article/details/gtyunvyysm.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.sysykeji.top/Article/details/gtfhmzfhcm.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.guannengcc.top/Article/details/gtanjxqwnz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xinyue.icu/Article/details/gtiyospyno.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yj20258.top/Article/details/gtlbqlzydc.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yj202588.top/Article/details/gtvxdgrihm.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yvedp.cn/Article/details/gtdswkolyp.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmixiollo.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jianghu66.top/Article/details/gtgerdjnfx.html

[C09] 递归
来源：http://dali.c1oappe.top/Article/details/gtfpqhbkqq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.nanxinkj.top/Article/details/gtrvznihdy.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.iojbl.cn/Article/details/gtmiesxiac.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sweek.top/Article/details/gtnezrvzum.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tianlin.xyz/Article/details/gtugeuzwmc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.wangdashe.top/Article/details/gtlnzkauat.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hnqzz.top/Article/details/gthissfgiz.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.guannengcc.top/Article/details/gtzampyoyr.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.fzhhl.top/Article/details/gtbjmozcxw.html

[C10] 变量作用域
来源：http://dali.zdqjudy.top/Article/details/gtuqqoysge.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwsczegwo.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinghuilouyu.cn/Article/details/gtuxpnbymi.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.fzhhl.top/Article/details/gtbrafolcf.html

TS:   同 JS
来源：http://dali.zhixingplan.top/Article/details/gtgeshlwoi.html

Java: 方法内为块级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gtwqqflnum.html

Go:   花括号块级作用域
来源：http://dali.gotoacloud.top/Article/details/gtkbkfhbej.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhoulong.xyz/Article/details/gtzreussvf.html

C#:   块级作用域
来源：http://dali.jqgfzy.top/Article/details/gtmnegjxse.html

[C11] 模块导入与导出
来源：http://dali.jqgufenzy.top/Article/details/gtinauygpe.html

Py:   from module import func
来源：http://dali.jqgfzy.top/Article/details/gtkededyxm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jiagoushi.top/Article/details/gtsmvvodbm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.fengsongda.top/Article/details/gttpjigane.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xinyue.icu/Article/details/gtxcvndwdm.html

Java: import java.util.List;
来源：http://dali.xylfe.cn/Article/details/gtscwdczby.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hfpthk.cn/Article/details/gtzdhxlzup.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jinqigufen.top/Article/details/gtwgnlmmtj.html

C#:   using System.Text;
来源：http://dali.yangfankeji.com/Article/details/gtqnlobmre.html

[C12] 立即执行函数 IIFE
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqybqhjrs.html

Py:   (lambda: print("run"))()
来源：http://dali.zhengqikj.top/Article/details/gtrtkjxjlz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zdqjudy.top/Article/details/gtqfldvtye.html

JS:   (() => { console.log("run"); })();
来源：http://dali.dashuyun.cn/Article/details/gtygbmstat.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xinyue.icu/Article/details/gtapfpdmvz.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinqigufen.top/Article/details/gtbaqtyckf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cheryme.top/Article/details/gtjisrmidk.html

Ruby: -> { puts "run" }.call
来源：http://dali.jlsjyb.cn/Article/details/gttiitecqr.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yongpay.top/Article/details/gtexngaqnr.html

[C13] 类型声明 / 类型注解
来源：http://dali.birdmap.top/Article/details/gtohwhlswh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jqgfzy.top/Article/details/gtlysabdos.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xylfe.cn/Article/details/gtcjnmsawt.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sxryk.cn/Article/details/gtoinoisjm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gtegjswauk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gthaqjtybh.html

Go:   func add(a, b int) int
来源：http://dali.yanxiufei.cn/Article/details/gtrduxcwsu.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.guowangkeji.top/Article/details/gtrkdjgecg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gtftsphsmp.html

[C14] 泛型函数
来源：http://dali.gzhubu.top/Article/details/gtefnqukux.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.iojbl.cn/Article/details/gtdrcmblpj.html

PHP:  // 无泛型
来源：http://dali.316326.xyz/Article/details/gtnienfvcg.html

JS:   // 无泛型
来源：http://dali.ehwqpu.com/Article/details/gtrjzsufsc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.c1oappe.top/Article/details/gtgbmkoxdw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cucudq.cn/Article/details/gtheakuykt.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jqgfzy.top/Article/details/gtvgavptoq.html

Ruby: # 无泛型
来源：http://dali.gzhubu.top/Article/details/gtbduffrnr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.aizwys.cn/Article/details/gtzatscumr.html

[C15] 解构 / 展开参数
来源：http://dali.mhx1999.top/Article/details/gtrqfzbnpw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.svipenyu.cn/Article/details/gtmcbclzhc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shzxlz.cn/Article/details/gtaztiqnnq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gogol.net.cn/Article/details/gthmkkzebq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.smart0.xyz/Article/details/gtbmokqsfj.html

Java: // 无解构
来源：http://dali.dianchejie.cn/Article/details/gtyfkxrzir.html

Go:   // 无解构
来源：http://dali.yuxming.cn/Article/details/gtbbxhzrka.html

Ruby: a, b = pair
来源：http://dali.zhaomingkeji.xyz/Article/details/gtruwasrzr.html

C#:   var (a, b) = pair;
来源：http://dali.xuanzx.com/Article/details/gtbohxtxcs.html

[C16] 函数 / 方法重载
来源：http://dali.sweek.top/Article/details/gtpxunpjuf.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.andypj.xyz/Article/details/gtbxcuibfv.html

PHP:  // 无重载
来源：http://dali.hfpthk.cn/Article/details/gtztawffak.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.snrcjt.cn/Article/details/gtzhdzmajk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yuanzhike.top/Article/details/gtaqdxnjto.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyjyjecaa.html

Go:   // 无重载：用不同函数名
来源：http://dali.chenjidiqi.icu/Article/details/gtvrllefwu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hammf.cn/Article/details/gttwvhlffn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtclfzyuok.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkzoacwan.html

D. 数组 / 列表 / 集合
来源：http://dali.meibo888.top/Article/details/gtfwbbkvby.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gttffmhudw.html

[D01] 创建数组 / 列表
来源：http://dali.chenzaomai.com/Article/details/gtjojrudfb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhengqikj.top/Article/details/gtkwpjtopl.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.mhx1999.top/Article/details/gtaorjzyzx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xinyue.icu/Article/details/gtjziaemjh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yuxming.cn/Article/details/gtwkiaepix.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.gzhubu.top/Article/details/gtguasdcpi.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xuanzx.com/Article/details/gthhosgtap.html

Ruby: arr = [1, 2, 3]
来源：http://dali.chenjidiqi.icu/Article/details/gtdxidsqls.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zycfv.cn/Article/details/gtbcjkjiys.html

[D02] 追加元素到末尾
来源：http://dali.hongshengwenyu.top/Article/details/gtdhfbrdra.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.nanxuanxn.top/Article/details/gtitnfmhss.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.chenlongwang.top/Article/details/gtzjfxkmld.html

JS:   arr.push(4);
来源：http://dali.c1oappe.top/Article/details/gtlfxcsqiy.html

TS:   arr.push(4);
来源：http://dali.zhongyouzk.top/Article/details/gtvxzmblfq.html

Java: list.add(4);
来源：http://dali.wangdashe.top/Article/details/gtzhfwxneq.html

Go:   arr = append(arr, 4)
来源：http://dali.gzhubu.top/Article/details/gtuqmwnmvd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shangyingyoupin.top/Article/details/gtlvnwjsqk.html

C#:   list.Add(4);
来源：http://dali.gogol.net.cn/Article/details/gtykghvicb.html

[D03] 在指定位置插入元素
来源：http://dali.sufxvd.cn/Article/details/gtwyotsfmz.html

Py:   arr.insert(0, 0)
来源：http://dali.daxiang520.top/Article/details/gtyibdwpru.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jqgfzy.top/Article/details/gtiyuyonoo.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yangfankeji.com/Article/details/gtljpgxmxl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yj20258888.top/Article/details/gtdwunbwmh.html

Java: list.add(0, 0);
来源：http://dali.jlsjyb.cn/Article/details/gtaqisalim.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoehmzjow.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xinyue.icu/Article/details/gtztqktgop.html

C#:   list.Insert(0, 0);
来源：http://dali.hfpthk.cn/Article/details/gturaeinll.html

[D04] 删除元素
来源：http://dali.yuanzhike.top/Article/details/gtefyrfqwo.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmvfdsosd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.mhx1999.top/Article/details/gtzhglzuhh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hnxiangtu.top/Article/details/gtwqbpmtfr.html

TS:   arr.splice(0, 1);
来源：http://dali.yanxiufei.cn/Article/details/gtdztoxtka.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.vqdsnc.cn/Article/details/gtgbiddkhp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jlsjyb.cn/Article/details/gtxlayszeq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hysaishi.cn/Article/details/gtlnizifxv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shzxlz.cn/Article/details/gtfgxclsmr.html

[D05] 访问与修改元素
来源：http://dali.316326.xyz/Article/details/gtzarwxtih.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.iojbl.cn/Article/details/gtkxsmuamr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gtrrmezuvd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.snrcjt.cn/Article/details/gtsmyfhnrj.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xziqi.cn/Article/details/gtwaepgexh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.tianlin.xyz/Article/details/gtcxrhbahj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ybcxt.top/Article/details/gtxyopwvil.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258.top/Article/details/gtsdgfxbvx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hongshengwenyu.top/Article/details/gttnwsakhu.html

[D06] 数组长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gthfqecxvu.html

Py:   len(arr)
来源：http://dali.daxiang520.top/Article/details/gtqvvhppen.html

PHP:  count($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtesuyynwt.html

JS:   arr.length
来源：http://dali.andypj.xyz/Article/details/gtzkohklhy.html

TS:   arr.length
来源：http://dali.zdqjudy.top/Article/details/gtetdoaojn.html

Java: list.size();
来源：http://dali.guowangkeji.top/Article/details/gtztsqpwfm.html

Go:   len(arr)
来源：http://dali.sxryk.cn/Article/details/gtspyhdesi.html

Ruby: arr.length; arr.size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtirsdmjqq.html

C#:   list.Count;
来源：http://dali.guowangkeji.top/Article/details/gtcndxsowm.html

[D07] 切片 / 取子数组
来源：http://dali.yueranfly.top/Article/details/gtvcmiixae.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shanyushiyangtech.top/Article/details/gtflwilfqn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtdwrmkhaw.html

JS:   arr.slice(1, 4);
来源：http://dali.zhoulong.xyz/Article/details/gtbupsengx.html

TS:   arr.slice(1, 4);
来源：http://dali.gzhubu.top/Article/details/gtmfhtrnrq.html

Java: list.subList(1, 4);
来源：http://dali.yanxiufei.cn/Article/details/gtcddqncna.html

Go:   arr[1:4]
来源：http://dali.xuanzx.com/Article/details/gtxcxsvjkr.html

Ruby: arr[1, 3]
来源：http://dali.daxiang520.top/Article/details/gtgdstmljp.html

C#:   list.GetRange(1, 3);
来源：http://dali.dashuyun.cn/Article/details/gtmebthtsc.html

[D08] 合并两个数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgtdzhpxi.html

Py:   a + b;  a.extend(b)
来源：http://dali.iojbl.cn/Article/details/gtgchuuule.html

PHP:  array_merge($a, $b);
来源：http://dali.zdqjudy.top/Article/details/gtlzqrdhnb.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtftiiydjt.html

TS:   [...a, ...b];
来源：http://dali.yj20258.top/Article/details/gtefqmwcoq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.tian-w.cn/Article/details/gtnhklcjdh.html

Go:   append(a, b...)
来源：http://dali.guannengcc.top/Article/details/gtcypuldmb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.vqdsnc.cn/Article/details/gtijosmgio.html

C#:   a.Concat(b).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtrxsbgbob.html

[D09] 排序（升序）
来源：http://dali.zhiwuduotai.top/Article/details/gtfsgwmxkf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenjidiqi.icu/Article/details/gthfuxowfw.html

PHP:  sort($arr);
来源：http://dali.ehwqpu.com/Article/details/gtmlitwgvd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cqqwz.cn/Article/details/gtcsmbdqvn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.pycfn.com/Article/details/gtwiihnbub.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hysaishi.cn/Article/details/gtlrlqzdwg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yongpay.top/Article/details/gtovvacbki.html

Ruby: arr.sort
来源：http://dali.xylfe.cn/Article/details/gtpgokeoxr.html

C#:   list.Sort();
来源：http://dali.dianchejie.cn/Article/details/gtfcpunhih.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.gotoacloud.top/Article/details/gtxajohxgv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.nanxuanxn.top/Article/details/gtdlstryak.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.fengsongda.top/Article/details/gtwoqlezqc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pengpengdd.cyou/Article/details/gtjkbkvbed.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.svipenyu.cn/Article/details/gtlvcuviqm.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hywenlv.cn/Article/details/gtzxlhmevw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shzxlz.cn/Article/details/gtxrrihrkl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jyoumei.cn/Article/details/gttolysgxq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhiwuduotai.top/Article/details/gtjuwpiwkz.html

[D11] 反转数组
来源：http://dali.yj20258.top/Article/details/gtiflwfmbl.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwrqcjtzo.html

PHP:  array_reverse($arr);
来源：http://dali.yangfankeji.com/Article/details/gthbzvmvum.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hywenlv.cn/Article/details/gtiuujrlxz.html


<!-- 参考信息 -->