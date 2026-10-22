代发 wailian999

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yongpay.top/Article/details/gtwwwivadl.html

Ruby: (0...10).step(2).to_a
来源：http://dali.shangyingyoupin.top/Article/details/gtsrnashnm.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.cqqwz.cn/Article/details/gtvxymicdx.html

[B12] 跳出多层循环
来源：http://dali.snrcjt.cn/Article/details/gtcnxxazyp.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhongyouzk.top/Article/details/gtxryxnouc.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jqgufenzy.top/Article/details/gtdvehclle.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ybcxt.top/Article/details/gtmeytbwct.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.9152youxi.cn/Article/details/gtnrhvtdad.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yongpay.top/Article/details/gtxrqgsyvx.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.feifeiyinyue.top/Article/details/gtbjvsskeg.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.316326.xyz/Article/details/gtzwiwmlns.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.svipenyu.cn/Article/details/gtedwyrqpk.html

[B13] 判断是否为数字
来源：http://dali.tian-w.cn/Article/details/gtgnskgyal.html

Py:   isinstance(x, (int, float))
来源：http://dali.aizwys.cn/Article/details/gtgqamkjtr.html

PHP:  is_numeric($x)
来源：http://dali.sxryk.cn/Article/details/gtibhwrqcb.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.haohaochexian.top/Article/details/gtbbvawmec.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxinkj.top/Article/details/gtiiyxajxl.html

Java: x instanceof Number
来源：http://dali.chenjidiqi.icu/Article/details/gtzvznowvn.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.nanxinkj.top/Article/details/gtrptaqcqa.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xylfe.cn/Article/details/gtlbkfhanh.html

C#:   x is int or double or decimal
来源：http://dali.ppjwa.cn/Article/details/gtzrwmydxi.html

[B14] 判断值是否在集合内
来源：http://dali.yuanzhike.top/Article/details/gtggjspskp.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jianghu66.top/Article/details/gtndidqyar.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.cucudq.cn/Article/details/gtinkcavpc.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtmikctopw.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hammf.cn/Article/details/gtozircdqd.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.0kj1m.cn/Article/details/gtazpfyzhl.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shuidangran.top/Article/details/gtrdkubxuc.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ehwqpu.com/Article/details/gtlcbscveo.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.gotoacloud.top/Article/details/gtfjrkinvp.html

[B15] 布尔运算与取反
来源：http://dali.jqgfzy.top/Article/details/gtcidngoso.html

Py:   a and b or not c
来源：http://dali.haohaochexian.top/Article/details/gtrpsvvejf.html

PHP:  $a && $b || !$c
来源：http://dali.shzxlz.cn/Article/details/gtdqzwtqzy.html

JS:   a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gtoloetyyh.html

TS:   a && b || !c
来源：http://dali.yj20258.top/Article/details/gtirlrgrxv.html

Java: a && b || !c
来源：http://dali.yj20258.top/Article/details/gtsvugtqju.html

Go:   a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gtdpregvil.html

Ruby: a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gtiwtaktwr.html

C#:   a && b || !c
来源：http://dali.xuanzx.com/Article/details/gtuggstvqf.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cheryme.top/Article/details/gtrkdfacsw.html

Py:   if not data: return
来源：http://dali.yueranfly.top/Article/details/gtunncuqer.html

PHP:  if (!$data) { return; }
来源：http://dali.yvedp.cn/Article/details/gtikrnhjmh.html

JS:   if (!data) return;
来源：http://dali.feifeiyinyue.top/Article/details/gtqdlptwkw.html

TS:   if (!data) return;
来源：http://dali.cdnleiting.top/Article/details/gtyisnolfy.html

Java: if (data == null) return;
来源：http://dali.xinyue.icu/Article/details/gtzxeqeiwk.html

Go:   if data == nil { return }
来源：http://dali.yangfankeji.com/Article/details/gtbqxeeqij.html

Ruby: return if data.nil?
来源：http://dali.pengpengdd.cyou/Article/details/gtcmtdmcmq.html

C#:   if (data == null) return;
来源：http://dali.xuetiantiany.cn/Article/details/gtsxlrmymh.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtszlssxaw.html

C. 函数与作用域
来源：http://dali.yuxming.cn/Article/details/gtevybgwpx.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtkdnncxih.html

[C01] 定义函数
来源：http://dali.sysykeji.top/Article/details/gtnvtebrvg.html

Py:   def add(a, b): return a + b
来源：http://dali.ehwqpu.com/Article/details/gtshmgbcok.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtpszlznwz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ivvv.top/Article/details/gtvtfhfzqq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gthhafrqhc.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gtzgylbmba.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yuanzhike.top/Article/details/gtakywkyay.html

Ruby: def add(a, b); a + b; end
来源：http://dali.vqdsnc.cn/Article/details/gtmxptxdnd.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtalzvcajo.html

[C02] 默认参数
来源：http://dali.jqgufenzy.top/Article/details/gtxbwqsmwm.html

Py:   def greet(name="World"): return name
来源：http://dali.quarkkingdee.top/Article/details/gtwantbqrj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yj202588.top/Article/details/gtjznrgnev.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.sweek.top/Article/details/gtxrlcsxfx.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gtikpfxdzr.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhixingplan.top/Article/details/gtzbxorwtq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xuanzx.com/Article/details/gtsosjyrwn.html

Ruby: def greet(name = "World") = name
来源：http://dali.sufxvd.cn/Article/details/gtmipwkaha.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.nwbrower.top/Article/details/gtgoqlzdem.html

[C03] 可变参数
来源：http://dali.jinqigfzy.top/Article/details/gtfulzuyka.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhixingplan.top/Article/details/gtrrwtgyrg.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.tian-w.cn/Article/details/gtexakmhdt.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.nwbrower.top/Article/details/gtkhxxifak.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ydzc1.top/Article/details/gtzxszwjby.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.nanxinkj.top/Article/details/gtyxpillqv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ivvv.top/Article/details/gtpwfgzeed.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhongyouzk.top/Article/details/gtrpnkwuvc.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shzxlz.cn/Article/details/gtowocbnti.html

[C04] 命名参数 / 关键字参数
来源：http://dali.chenjidiqi.icu/Article/details/gtyxdoysvx.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.aizwys.cn/Article/details/gtysebedqk.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jqgufenzy.top/Article/details/gtelnjhafq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.pycfn.com/Article/details/gtuucvrtcv.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhiwuduotai.top/Article/details/gtcwcusmbx.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.chenjidiqi.icu/Article/details/gtyvbbtgqa.html

Go:   // 无：用配置结构体参数
来源：http://dali.birdmap.top/Article/details/gtlknkvuma.html

Ruby: f(a: 1, b: 2)
来源：http://dali.nanxinkj.top/Article/details/gtuodhmkpt.html

C#:   f(a: 1, b: 2)
来源：http://dali.nanxinkj.top/Article/details/gtlhtfqrky.html

[C05] 返回多个值
来源：http://dali.guowangkeji.top/Article/details/gtbaijkemd.html

Py:   return a, b
来源：http://dali.yvedp.cn/Article/details/gtawrpvrez.html

PHP:  return [$a, $b];
来源：http://dali.aibaodan.cn/Article/details/gtvecreszm.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.andypj.xyz/Article/details/gthmwnvtqh.html

TS:   return { a, b };
来源：http://dali.yangfankeji.com/Article/details/gtvblkqlkd.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yuanzhike.top/Article/details/gtrfgwdeya.html

Go:   return a, b
来源：http://dali.sxryk.cn/Article/details/gttbmiymja.html

Ruby: return a, b
来源：http://dali.zhixingplan.top/Article/details/gtwdmwnrfk.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ehwqpu.com/Article/details/gtknlsyrsi.html

[C06] 匿名函数 / lambda
来源：http://dali.birdmap.top/Article/details/gtbtvrgsnf.html

Py:   square = lambda x: x * x
来源：http://dali.xinyue.icu/Article/details/gtjufybbxl.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hongshengwenyu.top/Article/details/gtgiqrjcmg.html

JS:   const square = x => x * x;
来源：http://dali.yuxming.cn/Article/details/gttiekasca.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gtugnblvak.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ydzc1.top/Article/details/gtdjehxfbz.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jyoumei.cn/Article/details/gtdstadfqy.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhengqikj.top/Article/details/gtjtnoqoyi.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ivvv.top/Article/details/gtuixuzlut.html

[C07] 把函数作为参数传入
来源：http://dali.havefunace.top/Article/details/gtfzdxunkh.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.pengpengdd.cyou/Article/details/gtuqvaauck.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.kuanghao11.cn/Article/details/gtgjakhhzd.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xuetiantiany.cn/Article/details/gtjjqfayeq.html

TS:   arr.map(String)
来源：http://dali.vqdsnc.cn/Article/details/gtuokoqgod.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zdqjudy.top/Article/details/gtnrqqdctn.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ehwqpu.com/Article/details/gtwqvkmxin.html

Ruby: arr.map(&:upcase)
来源：http://dali.ybcxt.top/Article/details/gtuprebpfj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.chenzaomai.com/Article/details/gtukcyxkqh.html

[C08] 闭包
来源：http://dali.cheryme.top/Article/details/gtgrfhxopa.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.c1oappe.top/Article/details/gtocqffqcs.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhixingplan.top/Article/details/gtuwednpmd.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.wangshuangyany.cn/Article/details/gtuskryaka.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yj20258.top/Article/details/gthjtqjtvh.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.andypj.xyz/Article/details/gtcimjqyty.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.ehwqpu.com/Article/details/gtwcfbhjqh.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yj202588.top/Article/details/gtxlzmrzqo.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gzhubu.top/Article/details/gtgeravtwo.html

[C09] 递归
来源：http://dali.jinqigfzy.top/Article/details/gtobifxilx.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yvedp.cn/Article/details/gtwqqgctwf.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.quarkkingdee.top/Article/details/gtzubcgjbj.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258888.top/Article/details/gtmradkhii.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.wangshuangyany.cn/Article/details/gtzdjgrzkv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.wangshuangyany.cn/Article/details/gtuwljydzy.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hammf.cn/Article/details/gtmutkszih.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cheryme.top/Article/details/gtbkjtcvjp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhixingplan.top/Article/details/gtwlukzrta.html

[C10] 变量作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gthsqkdbsn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.birdmap.top/Article/details/gtfhfzlbhp.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhixingplan.top/Article/details/gtcwilxsdd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cqqwz.cn/Article/details/gtzwjjdrnm.html

TS:   同 JS
来源：http://dali.gaohongyu789.top/Article/details/gthcsbighs.html

Java: 方法内为块级作用域
来源：http://dali.yanxiufei.cn/Article/details/gtqlgbuflp.html

Go:   花括号块级作用域
来源：http://dali.yangfankeji.com/Article/details/gtvdtnfbde.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.wangshuangyany.cn/Article/details/gtvxvhlurb.html

C#:   块级作用域
来源：http://dali.jianghu66.top/Article/details/gtcdeognpj.html

[C11] 模块导入与导出
来源：http://dali.bjfxy.top/Article/details/gttesyeuhh.html

Py:   from module import func
来源：http://dali.guowangkeji.top/Article/details/gthvtmmcnq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.gogol.net.cn/Article/details/gtzvhahiiv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.kuanghao11.cn/Article/details/gtefefsmfx.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.aizwys.cn/Article/details/gtomaykuzw.html

Java: import java.util.List;
来源：http://dali.jinqigufen.top/Article/details/gtmtxcmknl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ppjwa.cn/Article/details/gtgvaunhil.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yangfankeji.com/Article/details/gtjjaredzu.html

C#:   using System.Text;
来源：http://dali.9152youxi.cn/Article/details/gtauvcftuv.html

[C12] 立即执行函数 IIFE
来源：http://dali.nwbrower.top/Article/details/gtrqqclrqd.html

Py:   (lambda: print("run"))()
来源：http://dali.shanyushiyangtech.top/Article/details/gthumxvhqo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttjxeyqgt.html

JS:   (() => { console.log("run"); })();
来源：http://dali.iojbl.cn/Article/details/gtanfmmxoh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yuanzhike.top/Article/details/gtknpuowgl.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jqgfzy.top/Article/details/gtsbhdithd.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.feifeiyinyue.top/Article/details/gtzdmlmrjk.html

Ruby: -> { puts "run" }.call
来源：http://dali.shangyingyoupin.top/Article/details/gtxibsmmji.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jinqigfzy.top/Article/details/gtrvepnfcw.html

[C13] 类型声明 / 类型注解
来源：http://dali.feifeiyinyue.top/Article/details/gttdyvqati.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jiagoushi.top/Article/details/gtfupkgdlq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtedlczuhd.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sxryk.cn/Article/details/gttsoyiayc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtvxkebfny.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtkqmpyjwm.html

Go:   func add(a, b int) int
来源：http://dali.sysykeji.top/Article/details/gtcjljrjzj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.c1oappe.top/Article/details/gtlllvdwfr.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.tanke756.top/Article/details/gtpqglyvqn.html

[C14] 泛型函数
来源：http://dali.pengpengdd.cyou/Article/details/gtnzybhqnz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.guowangkeji.top/Article/details/gtpksoeiuq.html

PHP:  // 无泛型
来源：http://dali.cdnleiting.top/Article/details/gtsiuffdet.html

JS:   // 无泛型
来源：http://dali.xuetiantiany.cn/Article/details/gtipmkhpac.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jqgfzy.top/Article/details/gtzbxdxfqo.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.tian-w.cn/Article/details/gtftkjmwve.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.tian-w.cn/Article/details/gtcjrjfrck.html

Ruby: # 无泛型
来源：http://dali.hysaishi.cn/Article/details/gtchzhrvgl.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.iojbl.cn/Article/details/gtbrywrdxd.html

[C15] 解构 / 展开参数
来源：http://dali.yuanzhike.top/Article/details/gttfvwtenh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.redwolf501.top/Article/details/gtbotzvvwr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.svipenyu.cn/Article/details/gthijksdjs.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ppjwa.cn/Article/details/gtfgwndogd.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.dianchejie.cn/Article/details/gtxzxsyedi.html

Java: // 无解构
来源：http://dali.nanxinkj.top/Article/details/gtoadlenbi.html

Go:   // 无解构
来源：http://dali.aibaodan.cn/Article/details/gtuykxadxr.html

Ruby: a, b = pair
来源：http://dali.jyoumei.cn/Article/details/gtbgrflzjb.html

C#:   var (a, b) = pair;
来源：http://dali.shzxlz.cn/Article/details/gtoavmmlsm.html

[C16] 函数 / 方法重载
来源：http://dali.jqgufenzy.top/Article/details/gtijugzoax.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.mhx1999.top/Article/details/gtmnqgxarz.html

PHP:  // 无重载
来源：http://dali.0kj1m.cn/Article/details/gttcpvanql.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.snrcjt.cn/Article/details/gtqskvfujj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jqgfzy.top/Article/details/gthwftstgw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.0kj1m.cn/Article/details/gtglcbadxr.html

Go:   // 无重载：用不同函数名
来源：http://dali.sweek.top/Article/details/gtxoscwgww.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yvedp.cn/Article/details/gthxcwiche.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cashguo.top/Article/details/gtelcqkwjm.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtwmrhfyqe.html

D. 数组 / 列表 / 集合
来源：http://dali.jinqigufen.top/Article/details/gtesliqize.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtfmularbi.html

[D01] 创建数组 / 列表
来源：http://dali.gzhubu.top/Article/details/gtaymcztuj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shuidangran.top/Article/details/gtxvaqohwy.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlqpxvfjh.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sweek.top/Article/details/gtavftbmev.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yuanzhike.top/Article/details/gtjwuoyojl.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.sufxvd.cn/Article/details/gtyibvcbpy.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hfpthk.cn/Article/details/gtsxqmygig.html

Ruby: arr = [1, 2, 3]
来源：http://dali.redwolf501.top/Article/details/gtsxruuttq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jqgfzy.top/Article/details/gtpkxxohnb.html

[D02] 追加元素到末尾
来源：http://dali.hnqzz.top/Article/details/gtymosbqrl.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.fengsongda.top/Article/details/gttydaubhe.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jqgfzy.top/Article/details/gtfqffpznx.html

JS:   arr.push(4);
来源：http://dali.redwolf501.top/Article/details/gtxfnzgnmz.html

TS:   arr.push(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgzuelixk.html

Java: list.add(4);
来源：http://dali.xinyue.icu/Article/details/gtngtvwtet.html

Go:   arr = append(arr, 4)
来源：http://dali.sweek.top/Article/details/gtxwzqcopq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.haohaochexian.top/Article/details/gtpqvppgbj.html

C#:   list.Add(4);
来源：http://dali.cucudq.cn/Article/details/gthjvyelxh.html

[D03] 在指定位置插入元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkpjoieuo.html

Py:   arr.insert(0, 0)
来源：http://dali.hfpthk.cn/Article/details/gtmlokxcnd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.0kj1m.cn/Article/details/gtszlqaouf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yueranfly.top/Article/details/gtuqgerdiy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xylfe.cn/Article/details/gtdqltmphx.html

Java: list.add(0, 0);
来源：http://dali.mhx1999.top/Article/details/gtseqbmceb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.kuanghao11.cn/Article/details/gtcdqxqdgc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xziqi.cn/Article/details/gtskczjwiw.html

C#:   list.Insert(0, 0);
来源：http://dali.iojbl.cn/Article/details/gtbpjflhlp.html

[D04] 删除元素
来源：http://dali.chenlongwang.top/Article/details/gtdwwfmkyi.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cashguo.top/Article/details/gtaehnwnle.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sweek.top/Article/details/gtafiqkgld.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hammf.cn/Article/details/gttiujwift.html

TS:   arr.splice(0, 1);
来源：http://dali.nanxuanxn.top/Article/details/gtvbbusyfo.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtsblaizik.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.haohaochexian.top/Article/details/gteyrioxxy.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gzhubu.top/Article/details/gtnumoivqv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yj20258888.top/Article/details/gtkwwxycec.html

[D05] 访问与修改元素
来源：http://dali.mhx1999.top/Article/details/gtpqfquwgd.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxurmponj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hammf.cn/Article/details/gtcqhixldr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.pengpengdd.cyou/Article/details/gtkmaqusyv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.wangshuangyany.cn/Article/details/gttvvtkcmg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.feifeiyinyue.top/Article/details/gtgytipawu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cashguo.top/Article/details/gtbbgudlje.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shzxlz.cn/Article/details/gtybjovheu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yj20258.top/Article/details/gtfmtebxsa.html

[D06] 数组长度
来源：http://dali.ybcxt.top/Article/details/gtbknsjxfb.html

Py:   len(arr)
来源：http://dali.jiagoushi.top/Article/details/gtlrgxcukh.html

PHP:  count($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtoohiyloe.html

JS:   arr.length
来源：http://dali.chenzaomai.com/Article/details/gtetpvhzdp.html

TS:   arr.length
来源：http://dali.yj20258.top/Article/details/gtzsdolbut.html

Java: list.size();
来源：http://dali.vqdsnc.cn/Article/details/gtvnejzpao.html

Go:   len(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtffrjkatc.html

Ruby: arr.length; arr.size
来源：http://dali.dianchejie.cn/Article/details/gtecojmibb.html

C#:   list.Count;
来源：http://dali.smart0.xyz/Article/details/gtquubmmxg.html

[D07] 切片 / 取子数组
来源：http://dali.sysykeji.top/Article/details/gtjyrszotd.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.kuanghao11.cn/Article/details/gtfbqxrocg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ehwqpu.com/Article/details/gtktslswlp.html

JS:   arr.slice(1, 4);
来源：http://dali.jianghu66.top/Article/details/gtpozzlzzb.html

TS:   arr.slice(1, 4);
来源：http://dali.yj20258.top/Article/details/gtecglnipu.html

Java: list.subList(1, 4);
来源：http://dali.nwbrower.top/Article/details/gtreoooats.html

Go:   arr[1:4]
来源：http://dali.hysaishi.cn/Article/details/gtalzptbpg.html

Ruby: arr[1, 3]
来源：http://dali.shzxlz.cn/Article/details/gtuhshbvdm.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhengqikj.top/Article/details/gtwpefubfo.html

[D08] 合并两个数组
来源：http://dali.hnqzz.top/Article/details/gtcnqimtxi.html

Py:   a + b;  a.extend(b)
来源：http://dali.316326.xyz/Article/details/gtsoovyqly.html

PHP:  array_merge($a, $b);
来源：http://dali.gotoacloud.top/Article/details/gtesascsir.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yangfankeji.com/Article/details/gtteiamkqd.html

TS:   [...a, ...b];
来源：http://dali.yj202588.top/Article/details/gtfqwgxycg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yueranfly.top/Article/details/gthrktzacy.html

Go:   append(a, b...)
来源：http://dali.yangfankeji.com/Article/details/gtetguitsh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxalvxker.html

C#:   a.Concat(b).ToList()
来源：http://dali.ydzc1.top/Article/details/gtlhubicin.html

[D09] 排序（升序）
来源：http://dali.yueranfly.top/Article/details/gtbfajwmnw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hfpthk.cn/Article/details/gtceqymhhv.html

PHP:  sort($arr);
来源：http://dali.aibaodan.cn/Article/details/gtvvfkhtxx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xinyue.icu/Article/details/gtpaxgieob.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jlsjyb.cn/Article/details/gtssvfthdq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.tianlin.xyz/Article/details/gtydxapyos.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.tianlin.xyz/Article/details/gtcbrnohcb.html

Ruby: arr.sort
来源：http://dali.yongpay.top/Article/details/gtbrzfrvec.html

C#:   list.Sort();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlradcwag.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xylfe.cn/Article/details/gtqctosjcm.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.0kj1m.cn/Article/details/gthgdjygne.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.redwolf501.top/Article/details/gtxvtmvntj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xinyue.icu/Article/details/gtgotftgvc.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinqigfzy.top/Article/details/gthzpvargq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gotoacloud.top/Article/details/gtjpqhwirc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xuanzx.com/Article/details/gtktjlvcmb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcsusfcuq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sysykeji.top/Article/details/gtnzxkpnjq.html

[D11] 反转数组
来源：http://dali.ehwqpu.com/Article/details/gtrfudlqol.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.fzhhl.top/Article/details/gtxsfzcbly.html

PHP:  array_reverse($arr);
来源：http://dali.haohaochexian.top/Article/details/gtsoiztblx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinghuilouyu.cn/Article/details/gttyrxarlz.html

TS:   [...arr].reverse();
来源：http://dali.yongpay.top/Article/details/gtchedceyl.html

Java: Collections.reverse(list);
来源：http://dali.yuxming.cn/Article/details/gtcccwxzxt.html

Go:   slices.Reverse(arr)
来源：http://dali.sufxvd.cn/Article/details/gthjziwolp.html

Ruby: arr.reverse
来源：http://dali.yuanzhike.top/Article/details/gtwxdrmxne.html

C#:   list.Reverse();
来源：http://dali.hysaishi.cn/Article/details/gtchfftspn.html

[D12] 查找元素下标
来源：http://dali.cheryme.top/Article/details/gtgrboswdk.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhixingplan.top/Article/details/gtvbbdfcda.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xylfe.cn/Article/details/gtszdsidsa.html


<!-- 参考信息 -->