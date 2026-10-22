代发 wailian999

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.daxiang520.top/Article/details/gt2oemzybjm.html

Ruby: (0...10).step(2).to_a
来源：http://dali.aizwys.cn/Article/details/gt2rjgexyae.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yuxming.cn/Article/details/gt2yplawgoe.html

[B12] 跳出多层循环
来源：http://dali.andypj.xyz/Article/details/gt2lzbqlqdr.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.havefunace.top/Article/details/gt2eimibisg.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hnqzz.top/Article/details/gt2gzuusfxt.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxuanxn.top/Article/details/gt2ibilecya.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hysaishi.cn/Article/details/gt2edjgvprr.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.feifeiyinyue.top/Article/details/gt2goditiqz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yuxming.cn/Article/details/gt2ocefpbkn.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.svipenyu.cn/Article/details/gt2wihlxepg.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.mhx1999.top/Article/details/gt2wemfrddb.html

[B13] 判断是否为数字
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mtmxiner.html

Py:   isinstance(x, (int, float))
来源：http://dali.yongpay.top/Article/details/gt2rquuiqen.html

PHP:  is_numeric($x)
来源：http://dali.tian-w.cn/Article/details/gt2owfykwwb.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.haohaochexian.top/Article/details/gt2faavgcul.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.haohaochexian.top/Article/details/gt2azbbulab.html

Java: x instanceof Number
来源：http://dali.zhengqikj.top/Article/details/gt2zkkciclp.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hnqzz.top/Article/details/gt2addhohiv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.haohaochexian.top/Article/details/gt2attiqxpy.html

C#:   x is int or double or decimal
来源：http://dali.gogol.net.cn/Article/details/gt2scjecyiy.html

[B14] 判断值是否在集合内
来源：http://dali.aibaodan.cn/Article/details/gt2affswxlb.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.fengsongda.top/Article/details/gt2ygvwlbua.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.fengsongda.top/Article/details/gt2njzdbxti.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.dashuyun.cn/Article/details/gt2stfosdcf.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jqgfzy.top/Article/details/gt2aajahlkr.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shuidangran.top/Article/details/gt2qrthrcoa.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qfjbfyzc.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2sturwzkv.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.sufxvd.cn/Article/details/gt2tgbsizet.html

[B15] 布尔运算与取反
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2flkctldt.html

Py:   a and b or not c
来源：http://dali.zycfv.cn/Article/details/gt2wbojndsx.html

PHP:  $a && $b || !$c
来源：http://dali.fengsongda.top/Article/details/gt2ceffnnxi.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2oatmorku.html

TS:   a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gt2tgdykapo.html

Java: a && b || !c
来源：http://dali.iojbl.cn/Article/details/gt2adfvthux.html

Go:   a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gt2fswisxnv.html

Ruby: a && b || !c
来源：http://dali.hnqzz.top/Article/details/gt2ccakapms.html

C#:   a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gt2jdqjubrk.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.0kj1m.cn/Article/details/gt2yspgoqjx.html

Py:   if not data: return
来源：http://dali.shzxlz.cn/Article/details/gt2smzddqrf.html

PHP:  if (!$data) { return; }
来源：http://dali.xuanzx.com/Article/details/gt2huugahyx.html

JS:   if (!data) return;
来源：http://dali.ybcxt.top/Article/details/gt2ddagtyax.html

TS:   if (!data) return;
来源：http://dali.svipenyu.cn/Article/details/gt2tebzvpwc.html

Java: if (data == null) return;
来源：http://dali.sysykeji.top/Article/details/gt2fqlklzcm.html

Go:   if data == nil { return }
来源：http://dali.snrcjt.cn/Article/details/gt2ufmvrnjc.html

Ruby: return if data.nil?
来源：http://dali.ehwqpu.com/Article/details/gt2wwrjulnr.html

C#:   if (data == null) return;
来源：http://dali.zycfv.cn/Article/details/gt2xlrctvyj.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2sgvzxbom.html

C. 函数与作用域
来源：http://dali.zhiwuduotai.top/Article/details/gt2sqyecaqt.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2twlbtfre.html

[C01] 定义函数
来源：http://dali.cucudq.cn/Article/details/gt2irtmzlkq.html

Py:   def add(a, b): return a + b
来源：http://dali.yj20258.top/Article/details/gt2iqtcliit.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuanzhike.top/Article/details/gt2hjbrorrf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gt2yhyyfvpc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gt2sjidhkjz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gt2wwgzyjcs.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ouvswecs.html

Ruby: def add(a, b); a + b; end
来源：http://dali.daxiang520.top/Article/details/gt2slqnoylo.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gt2prwuxavm.html

[C02] 默认参数
来源：http://dali.zhengqikj.top/Article/details/gt2ymoersfy.html

Py:   def greet(name="World"): return name
来源：http://dali.hysaishi.cn/Article/details/gt2nbghglsh.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.haohaochexian.top/Article/details/gt2kkfspchy.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ysslqzob.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.chenzaomai.com/Article/details/gt2polamepy.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.pengpengdd.cyou/Article/details/gt2iwlavdwz.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jiagoushi.top/Article/details/gt2oslqnsnk.html

Ruby: def greet(name = "World") = name
来源：http://dali.meibo888.top/Article/details/gt2zwtfhypn.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ybcxt.top/Article/details/gt2ftqcujup.html

[C03] 可变参数
来源：http://dali.yueranfly.top/Article/details/gt2vctfcyeb.html

Py:   def total(*args): return sum(args)
来源：http://dali.316326.xyz/Article/details/gt2iyavneyy.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shzxlz.cn/Article/details/gt2mqtfxxsu.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sweek.top/Article/details/gt2wyobgrmr.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xinyue.icu/Article/details/gt2vvgqkhiw.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shuidangran.top/Article/details/gt2afirxogn.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jyoumei.cn/Article/details/gt2germlhvs.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.andypj.xyz/Article/details/gt2gqatwzpp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.nwbrower.top/Article/details/gt2xomhiext.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cdnleiting.top/Article/details/gt2ozjvxnah.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.guowangkeji.top/Article/details/gt2ewodshgd.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.aibaodan.cn/Article/details/gt2vsvwkhbg.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hvljpqtu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.vqdsnc.cn/Article/details/gt2pcmqfxrq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.nwbrower.top/Article/details/gt2dmsyucqu.html

Go:   // 无：用配置结构体参数
来源：http://dali.xziqi.cn/Article/details/gt2fbaywffb.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cheryme.top/Article/details/gt2ehnjsciu.html

C#:   f(a: 1, b: 2)
来源：http://dali.9152youxi.cn/Article/details/gt2shizftkl.html

[C05] 返回多个值
来源：http://dali.xuanzx.com/Article/details/gt2antvrvdu.html

Py:   return a, b
来源：http://dali.jqgufenzy.top/Article/details/gt2rvpwwrst.html

PHP:  return [$a, $b];
来源：http://dali.hfpthk.cn/Article/details/gt2zgggafco.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.quarkkingdee.top/Article/details/gt2umxwxfgd.html

TS:   return { a, b };
来源：http://dali.mhx1999.top/Article/details/gt2fuakalbg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ehwqpu.com/Article/details/gt2rgccjvaj.html

Go:   return a, b
来源：http://dali.jinqigufen.top/Article/details/gt2tehvjagp.html

Ruby: return a, b
来源：http://dali.snrcjt.cn/Article/details/gt2mrrrvkki.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.sysykeji.top/Article/details/gt2nlspvjff.html

[C06] 匿名函数 / lambda
来源：http://dali.316326.xyz/Article/details/gt2tunjytrz.html

Py:   square = lambda x: x * x
来源：http://dali.zhoulong.xyz/Article/details/gt2hgkhnwvn.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ehoqwfnn.html

JS:   const square = x => x * x;
来源：http://dali.ppjwa.cn/Article/details/gt2mkwymvcg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ydzc1.top/Article/details/gt2fpwviplg.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.bjfxy.top/Article/details/gt2kssnflyi.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sxryk.cn/Article/details/gt2xuxxpxfu.html

Ruby: square = ->(x) { x * x }
来源：http://dali.chenjidiqi.icu/Article/details/gt2vwjpkzyj.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.dianchejie.cn/Article/details/gt2smaetevc.html

[C07] 把函数作为参数传入
来源：http://dali.jqgfzy.top/Article/details/gt2dvxfpgpo.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zycfv.cn/Article/details/gt2bctevpbm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.dianchejie.cn/Article/details/gt2etavmmjz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yj20258.top/Article/details/gt2dluutrjp.html

TS:   arr.map(String)
来源：http://dali.yanxiufei.cn/Article/details/gt2qjcgawiw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.haohaochexian.top/Article/details/gt2wkadgarh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.9152youxi.cn/Article/details/gt2ckqhnkeo.html

Ruby: arr.map(&:upcase)
来源：http://dali.yonumen.top/Article/details/gt2pyqornfu.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shuidangran.top/Article/details/gt2hplkstvf.html

[C08] 闭包
来源：http://dali.zhiwuduotai.top/Article/details/gt2nsjtttad.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2avplwfmu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.guannengcc.top/Article/details/gt2lnffgabt.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zycfv.cn/Article/details/gt2ppivkhks.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ybcxt.top/Article/details/gt2hwbtqxpr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zdqjudy.top/Article/details/gt2jpquusqu.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.feifeiyinyue.top/Article/details/gt2osqssyxq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jqgufenzy.top/Article/details/gt2mayycvsm.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cucudq.cn/Article/details/gt2hdeekeqm.html

[C09] 递归
来源：http://dali.yj20258888.top/Article/details/gt2dwgihmpx.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.kuanghao11.cn/Article/details/gt2vfzwofgt.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.nanxinkj.top/Article/details/gt2jbuirefv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yongpay.top/Article/details/gt2zjyazgdm.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xuetiantiany.cn/Article/details/gt2rtuwaipt.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.daria6918.cn/Article/details/gt2wjrzvimx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.nanxuanxn.top/Article/details/gt2qspjjkdc.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yvedp.cn/Article/details/gt2knwlmbvg.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yueranfly.top/Article/details/gt2oxysfxdh.html

[C10] 变量作用域
来源：http://dali.hongshengwenyu.top/Article/details/gt2pherjncn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.redwolf501.top/Article/details/gt2sicmauea.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sufxvd.cn/Article/details/gt2jamauygf.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.tianlin.xyz/Article/details/gt2tccumltr.html

TS:   同 JS
来源：http://dali.yangfankeji.com/Article/details/gt2gkywoliq.html

Java: 方法内为块级作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tvsmykwq.html

Go:   花括号块级作用域
来源：http://dali.wangdashe.top/Article/details/gt2gihmpidc.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cheryme.top/Article/details/gt2zhxzerhz.html

C#:   块级作用域
来源：http://dali.gogol.net.cn/Article/details/gt2glcvobdt.html

[C11] 模块导入与导出
来源：http://dali.daxiang520.top/Article/details/gt2shqfgzpb.html

Py:   from module import func
来源：http://dali.xziqi.cn/Article/details/gt2vunxzrkb.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ccgbqugp.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2tihtdxrg.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hammf.cn/Article/details/gt2gtivtcdr.html

Java: import java.util.List;
来源：http://dali.9152youxi.cn/Article/details/gt2oxggibiz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xylfe.cn/Article/details/gt2chnzplcj.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.guowangkeji.top/Article/details/gt2bcfxxtii.html

C#:   using System.Text;
来源：http://dali.meibo888.top/Article/details/gt2pokdifef.html

[C12] 立即执行函数 IIFE
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cdyewcdy.html

Py:   (lambda: print("run"))()
来源：http://dali.zdqjudy.top/Article/details/gt2mxscnvtj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.pengpengdd.cyou/Article/details/gt2alirkdgq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.haohaochexian.top/Article/details/gt2kxuzesmz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.smart0.xyz/Article/details/gt2yrhzbscf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gaohongyu789.top/Article/details/gt2zwnmybob.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jqgfzy.top/Article/details/gt2obhthnlu.html

Ruby: -> { puts "run" }.call
来源：http://dali.yuanzhike.top/Article/details/gt2aijowomb.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jyoumei.cn/Article/details/gt2njgddbxv.html

[C13] 类型声明 / 类型注解
来源：http://dali.chenjidiqi.icu/Article/details/gt2ujrjmfpy.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sufxvd.cn/Article/details/gt2lfwaqzmn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guannengcc.top/Article/details/gt2csnpwxlg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lttotbgp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gt2gzpdzknb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rymxdygm.html

Go:   func add(a, b int) int
来源：http://dali.yanxiufei.cn/Article/details/gt2tulcsgtz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cqqwz.cn/Article/details/gt2obfcbtrr.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hongshengwenyu.top/Article/details/gt2qionfqyl.html

[C14] 泛型函数
来源：http://dali.chenzaomai.com/Article/details/gt2cvmqtwaf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.kuanghao11.cn/Article/details/gt2uoyibiye.html

PHP:  // 无泛型
来源：http://dali.yangfankeji.com/Article/details/gt2jbbrypqm.html

JS:   // 无泛型
来源：http://dali.xuetiantiany.cn/Article/details/gt2ogxgifgw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hammf.cn/Article/details/gt2jsiasyvl.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.quarkkingdee.top/Article/details/gt2slixqtic.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.haohaochexian.top/Article/details/gt2mnlcwoxs.html

Ruby: # 无泛型
来源：http://dali.quarkkingdee.top/Article/details/gt2ksynzzro.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.guannengcc.top/Article/details/gt2lbenzdoi.html

[C15] 解构 / 展开参数
来源：http://dali.iojbl.cn/Article/details/gt2hqooxpgh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xziqi.cn/Article/details/gt2zpzbuntf.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xylfe.cn/Article/details/gt2pozyalzz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xylfe.cn/Article/details/gt2kcrnahny.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jianghu66.top/Article/details/gt2lximwbbw.html

Java: // 无解构
来源：http://dali.aizwys.cn/Article/details/gt2gxsinbeu.html

Go:   // 无解构
来源：http://dali.xuanzx.com/Article/details/gt2ozkwocmm.html

Ruby: a, b = pair
来源：http://dali.0kj1m.cn/Article/details/gt2yyjdnkqr.html

C#:   var (a, b) = pair;
来源：http://dali.hnxiangtu.top/Article/details/gt2gzogtmcb.html

[C16] 函数 / 方法重载
来源：http://dali.jlsjyb.cn/Article/details/gt2pbjnrgba.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.aibaodan.cn/Article/details/gt2hapeqaos.html

PHP:  // 无重载
来源：http://dali.jlsjyb.cn/Article/details/gt2tijrjhpp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.chenlongwang.top/Article/details/gt2zietbolt.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.fengsongda.top/Article/details/gt2kfyumoub.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yangfankeji.com/Article/details/gt2mwclwuoh.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2nahdxggv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinqigufen.top/Article/details/gt2ikglyuwj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cheryme.top/Article/details/gt2pvhzquba.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2yifbjfkm.html

D. 数组 / 列表 / 集合
来源：http://dali.chenjidiqi.icu/Article/details/gt2yvuunupt.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2rmfozhiv.html

[D01] 创建数组 / 列表
来源：http://dali.yj20258.top/Article/details/gt2canpjxyf.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ehwqpu.com/Article/details/gt2wlfzdzen.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yonumen.top/Article/details/gt2zgzvpmxe.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.chenzaomai.com/Article/details/gt2kpccjjeu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhoulong.xyz/Article/details/gt2zppmqlpn.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.tianlin.xyz/Article/details/gt2xqbyuxzg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.guannengcc.top/Article/details/gt2tjepngmy.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ydzc1.top/Article/details/gt2eazbzghe.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.meibo888.top/Article/details/gt2jcebijiw.html

[D02] 追加元素到末尾
来源：http://dali.pengpengdd.cyou/Article/details/gt2mgukzysk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ybcxt.top/Article/details/gt2cpzvkocg.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.sysykeji.top/Article/details/gt2kxqcpdam.html

JS:   arr.push(4);
来源：http://dali.hysaishi.cn/Article/details/gt2hegmmnyw.html

TS:   arr.push(4);
来源：http://dali.feifeiyinyue.top/Article/details/gt2prftfooe.html

Java: list.add(4);
来源：http://dali.hfpthk.cn/Article/details/gt2kqpohoik.html

Go:   arr = append(arr, 4)
来源：http://dali.gzhubu.top/Article/details/gt2njjmnugl.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xziqi.cn/Article/details/gt2vnhgqwtd.html

C#:   list.Add(4);
来源：http://dali.yuanzhike.top/Article/details/gt2lmvadylc.html

[D03] 在指定位置插入元素
来源：http://dali.dianchejie.cn/Article/details/gt2dqshwhwb.html

Py:   arr.insert(0, 0)
来源：http://dali.shuidangran.top/Article/details/gt2jcleczqr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fwsflier.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zdqjudy.top/Article/details/gt2yjaemphb.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gt2qqerusck.html

Java: list.add(0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vkftznwy.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.nwbrower.top/Article/details/gt2wgpxmwad.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xziqi.cn/Article/details/gt2aorbblwb.html

C#:   list.Insert(0, 0);
来源：http://dali.jinqigufen.top/Article/details/gt2vayesecs.html

[D04] 删除元素
来源：http://dali.pycfn.com/Article/details/gt2usanhkvx.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yuxming.cn/Article/details/gt2aqdagdzz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.iojbl.cn/Article/details/gt2wvbexndd.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinqigufen.top/Article/details/gt2ytjudwxh.html

TS:   arr.splice(0, 1);
来源：http://dali.jiagoushi.top/Article/details/gt2zuhxovij.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.fzhhl.top/Article/details/gt2azjxlcin.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.316326.xyz/Article/details/gt2jqzyjqgs.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.dianchejie.cn/Article/details/gt2fukcymed.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shzxlz.cn/Article/details/gt2fakikkrj.html

[D05] 访问与修改元素
来源：http://dali.tanke756.top/Article/details/gt2vxlhtpgf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aibaodan.cn/Article/details/gt2kaajxoii.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yuanzhike.top/Article/details/gt2rldinivb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.kuanghao11.cn/Article/details/gt2nrpcpdev.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sweek.top/Article/details/gt2kzgavkqc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinqigufen.top/Article/details/gt2bwlpkytn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yj202588.top/Article/details/gt2jeltoziu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.bjfxy.top/Article/details/gt2hczuhxvf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.tanke756.top/Article/details/gt2zpinkcxm.html

[D06] 数组长度
来源：http://dali.hnxiangtu.top/Article/details/gt2xsvipkln.html

Py:   len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uebvxdyr.html

PHP:  count($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2xnzjsuaa.html

JS:   arr.length
来源：http://dali.kuanghao11.cn/Article/details/gt2umefseoj.html

TS:   arr.length
来源：http://dali.yonumen.top/Article/details/gt2kogjzkbf.html

Java: list.size();
来源：http://dali.jqgufenzy.top/Article/details/gt2qfdxdowp.html

Go:   len(arr)
来源：http://dali.tanke756.top/Article/details/gt2xpizekoi.html

Ruby: arr.length; arr.size
来源：http://dali.c1oappe.top/Article/details/gt2nkczxvua.html

C#:   list.Count;
来源：http://dali.xuanzx.com/Article/details/gt2ihyzcfsv.html

[D07] 切片 / 取子数组
来源：http://dali.xziqi.cn/Article/details/gt2xtrhhkfu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.daxiang520.top/Article/details/gt2hylyqqvd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sweek.top/Article/details/gt2oelsnkon.html

JS:   arr.slice(1, 4);
来源：http://dali.tianlin.xyz/Article/details/gt2jhyzmulf.html

TS:   arr.slice(1, 4);
来源：http://dali.0kj1m.cn/Article/details/gt2dpdortuw.html

Java: list.subList(1, 4);
来源：http://dali.pycfn.com/Article/details/gt2ehsxzimj.html

Go:   arr[1:4]
来源：http://dali.daria6918.cn/Article/details/gt2dcesbtqz.html

Ruby: arr[1, 3]
来源：http://dali.havefunace.top/Article/details/gt2njepscwq.html

C#:   list.GetRange(1, 3);
来源：http://dali.hywenlv.cn/Article/details/gt2omrfzkpm.html

[D08] 合并两个数组
来源：http://dali.shzxlz.cn/Article/details/gt2euivxsjr.html

Py:   a + b;  a.extend(b)
来源：http://dali.haohaochexian.top/Article/details/gt2mifbksgg.html

PHP:  array_merge($a, $b);
来源：http://dali.sufxvd.cn/Article/details/gt2epfiurue.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hnqzz.top/Article/details/gt2sscqryrm.html

TS:   [...a, ...b];
来源：http://dali.wangshuangyany.cn/Article/details/gt2koztpvkv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.aibaodan.cn/Article/details/gt2ynmfevcw.html

Go:   append(a, b...)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2texhhvpy.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yonumen.top/Article/details/gt2dqsgxwor.html

C#:   a.Concat(b).ToList()
来源：http://dali.redwolf501.top/Article/details/gt2lsawhwnc.html

[D09] 排序（升序）
来源：http://dali.havefunace.top/Article/details/gt2jghhglvg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhoulong.xyz/Article/details/gt2csgrhnqt.html

PHP:  sort($arr);
来源：http://dali.fengsongda.top/Article/details/gt2rmwkprel.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hfpthk.cn/Article/details/gt2pymiomnl.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yuxming.cn/Article/details/gt2vtpelgvi.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hnqzz.top/Article/details/gt2rideubwf.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2xndqfzdi.html

Ruby: arr.sort
来源：http://dali.gogol.net.cn/Article/details/gt2pvvfhamf.html

C#:   list.Sort();
来源：http://dali.yuanzhike.top/Article/details/gt2ddkbsvct.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.havefunace.top/Article/details/gt2vdeiyfnj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shzxlz.cn/Article/details/gt2vlssrlev.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xziqi.cn/Article/details/gt2yyuvftjy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uqvcawnt.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hlxfmiax.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yueranfly.top/Article/details/gt2xnrcypnk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hnqzz.top/Article/details/gt2fszlhpfd.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jlsjyb.cn/Article/details/gt2kicryupc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.daria6918.cn/Article/details/gt2owrcxrxl.html

[D11] 反转数组
来源：http://dali.redwolf501.top/Article/details/gt2pqjngxil.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ehwqpu.com/Article/details/gt2fogtjpdm.html

PHP:  array_reverse($arr);
来源：http://dali.chenlongwang.top/Article/details/gt2ralfmnlo.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yuanzhike.top/Article/details/gt2xjvmaaze.html

TS:   [...arr].reverse();
来源：http://dali.jinqigfzy.top/Article/details/gt2ukacgbbm.html

Java: Collections.reverse(list);
来源：http://dali.sysykeji.top/Article/details/gt2hqjpqepn.html

Go:   slices.Reverse(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2djdmmysm.html

Ruby: arr.reverse
来源：http://dali.guannengcc.top/Article/details/gt2yxmrrmxn.html

C#:   list.Reverse();
来源：http://dali.tianlin.xyz/Article/details/gt2dpeezpeh.html

[D12] 查找元素下标
来源：http://dali.jinghuilouyu.cn/Article/details/gt2thbftcjf.html

Py:   arr.index(x);  x in arr
来源：http://dali.hongshengwenyu.top/Article/details/gt2gwptghwk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.svipenyu.cn/Article/details/gt2blczgzkl.html


<!-- 参考信息 -->