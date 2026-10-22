代发 wailian999

PHP:  range(0, 10, 2);
来源：http://dali.vqdsnc.cn/Article/details/gt2jvbuggmv.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yueranfly.top/Article/details/gt2colpbyzl.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tanke756.top/Article/details/gt2iocphvyx.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.nanxuanxn.top/Article/details/gt2uvxpvriu.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.cdnleiting.top/Article/details/gt2jawnhdym.html

Ruby: (0...10).step(2).to_a
来源：http://dali.shuidangran.top/Article/details/gt2wpeexgts.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yj20258.top/Article/details/gt2kprhmcbn.html

[B12] 跳出多层循环
来源：http://dali.shzxlz.cn/Article/details/gt2rxrmnnti.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.pycfn.com/Article/details/gt2hhtbobyw.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cdnleiting.top/Article/details/gt2idxlowob.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.guannengcc.top/Article/details/gt2mgzrccer.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rrqiuwff.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgufenzy.top/Article/details/gt2zgeixywd.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ybcxt.top/Article/details/gt2cgrnrwpj.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.vqdsnc.cn/Article/details/gt2jkdstoez.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.0kj1m.cn/Article/details/gt2uqrivnmx.html

[B13] 判断是否为数字
来源：http://dali.pengpengdd.cyou/Article/details/gt2srjsaomw.html

Py:   isinstance(x, (int, float))
来源：http://dali.dashuyun.cn/Article/details/gt2fqyljmgb.html

PHP:  is_numeric($x)
来源：http://dali.chenzaomai.com/Article/details/gt2wnsitrus.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2mfmalhce.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hysaishi.cn/Article/details/gt2hyeqibnm.html

Java: x instanceof Number
来源：http://dali.xinyue.icu/Article/details/gt2fzgntbwz.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xinyue.icu/Article/details/gt2ibirlbrh.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yvedp.cn/Article/details/gt2bmliswxd.html

C#:   x is int or double or decimal
来源：http://dali.tianlin.xyz/Article/details/gt2sdzmlgox.html

[B14] 判断值是否在集合内
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bhtnjahp.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.andypj.xyz/Article/details/gt2eunxcrta.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.ybcxt.top/Article/details/gt2hedzxlpr.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ybcxt.top/Article/details/gt2kkcatjic.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.bjfxy.top/Article/details/gt2tvoaxuha.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ehwqpu.com/Article/details/gt2oarxrami.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yonumen.top/Article/details/gt2ovrkegkt.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhixingplan.top/Article/details/gt2sbuvuobj.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.andypj.xyz/Article/details/gt2rwvghija.html

[B15] 布尔运算与取反
来源：http://dali.fzhhl.top/Article/details/gt2nbtyvgsi.html

Py:   a and b or not c
来源：http://dali.xziqi.cn/Article/details/gt2xllkgpgo.html

PHP:  $a && $b || !$c
来源：http://dali.hysaishi.cn/Article/details/gt2zqizxqlb.html

JS:   a && b || !c
来源：http://dali.fzhhl.top/Article/details/gt2cnkyjcvy.html

TS:   a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gt2ezjghjbg.html

Java: a && b || !c
来源：http://dali.xuanzx.com/Article/details/gt2abktgdqr.html

Go:   a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gt2bpqwgwrb.html

Ruby: a && b || !c
来源：http://dali.cheryme.top/Article/details/gt2levuomle.html

C#:   a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gt2fzdibrco.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.daxiang520.top/Article/details/gt2ffcybfaf.html

Py:   if not data: return
来源：http://dali.hammf.cn/Article/details/gt2hmstiord.html

PHP:  if (!$data) { return; }
来源：http://dali.hywenlv.cn/Article/details/gt2bnrbmwth.html

JS:   if (!data) return;
来源：http://dali.pengpengdd.cyou/Article/details/gt2ldfxeeih.html

TS:   if (!data) return;
来源：http://dali.316326.xyz/Article/details/gt2eazxwnnt.html

Java: if (data == null) return;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jciutxsp.html

Go:   if data == nil { return }
来源：http://dali.ehwqpu.com/Article/details/gt2ruyfujna.html

Ruby: return if data.nil?
来源：http://dali.zdqjudy.top/Article/details/gt2vrkgmkay.html

C#:   if (data == null) return;
来源：http://dali.316326.xyz/Article/details/gt2duhawrae.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2atgrhmpj.html

C. 函数与作用域
来源：http://dali.wangdashe.top/Article/details/gt2yepsdent.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2zzjbqfkj.html

[C01] 定义函数
来源：http://dali.gogol.net.cn/Article/details/gt2hxbwhrzi.html

Py:   def add(a, b): return a + b
来源：http://dali.dianchejie.cn/Article/details/gt2vgwcjgzf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sweek.top/Article/details/gt2aldickse.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gt2zyanpzyr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gt2eulknkfq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ebupbjdo.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ivvv.top/Article/details/gt2unwrezlm.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhixingplan.top/Article/details/gt2grlisjbu.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gt2tpxfxzqw.html

[C02] 默认参数
来源：http://dali.hammf.cn/Article/details/gt2ulsebint.html

Py:   def greet(name="World"): return name
来源：http://dali.hongshengwenyu.top/Article/details/gt2prqlnaba.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.iojbl.cn/Article/details/gt2dptfcolh.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2iblqngtb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.316326.xyz/Article/details/gt2kcvraipu.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.andypj.xyz/Article/details/gt2uebvexga.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.sufxvd.cn/Article/details/gt2bscbtoet.html

Ruby: def greet(name = "World") = name
来源：http://dali.jinqigfzy.top/Article/details/gt2nhmrsnbx.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.meibo888.top/Article/details/gt2jwdugjsl.html

[C03] 可变参数
来源：http://dali.gaohongyu789.top/Article/details/gt2grqmsdre.html

Py:   def total(*args): return sum(args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yhcfvqlf.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2vsxafxta.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jlsjyb.cn/Article/details/gt2dumruyll.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sufxvd.cn/Article/details/gt2lkdhsrpn.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cdnleiting.top/Article/details/gt2hpjrpcjd.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jinqigufen.top/Article/details/gt2pxuytdeu.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.guowangkeji.top/Article/details/gt2wmpmogrg.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.dashuyun.cn/Article/details/gt2rtufokko.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gogol.net.cn/Article/details/gt2oujlsekv.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.nanxuanxn.top/Article/details/gt2efwftvdg.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cdnleiting.top/Article/details/gt2pjkrvyci.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.dianchejie.cn/Article/details/gt2oddpqkkd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.quarkkingdee.top/Article/details/gt2mfwicxyq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ppjwa.cn/Article/details/gt2wpnmpxrh.html

Go:   // 无：用配置结构体参数
来源：http://dali.mhx1999.top/Article/details/gt2xajspvnc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yj20258.top/Article/details/gt2raibngon.html

C#:   f(a: 1, b: 2)
来源：http://dali.andypj.xyz/Article/details/gt2ptskppyx.html

[C05] 返回多个值
来源：http://dali.tianlin.xyz/Article/details/gt2klklkwli.html

Py:   return a, b
来源：http://dali.guannengcc.top/Article/details/gt2asmufypm.html

PHP:  return [$a, $b];
来源：http://dali.xinyue.icu/Article/details/gt2vepryqaa.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.daria6918.cn/Article/details/gt2bdnpevtj.html

TS:   return { a, b };
来源：http://dali.redwolf501.top/Article/details/gt2mvoecgxx.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.mhx1999.top/Article/details/gt2bsiqbkbc.html

Go:   return a, b
来源：http://dali.hammf.cn/Article/details/gt2mppztlle.html

Ruby: return a, b
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bpgpuopy.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.c1oappe.top/Article/details/gt2vwdwnloj.html

[C06] 匿名函数 / lambda
来源：http://dali.zhixingplan.top/Article/details/gt2bsqvfzcr.html

Py:   square = lambda x: x * x
来源：http://dali.xuanzx.com/Article/details/gt2qvgzdbuu.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.bjfxy.top/Article/details/gt2ztjesvke.html

JS:   const square = x => x * x;
来源：http://dali.cheryme.top/Article/details/gt2drqyssoq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.havefunace.top/Article/details/gt2phtulmxh.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.gaohongyu789.top/Article/details/gt2hnoegczc.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yj202588.top/Article/details/gt2jibduqbs.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hongshengwenyu.top/Article/details/gt2uibbmjuo.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.guowangkeji.top/Article/details/gt2rmxyvhhu.html

[C07] 把函数作为参数传入
来源：http://dali.meibo888.top/Article/details/gt2drlpclnb.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cqqwz.cn/Article/details/gt2niikptec.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yonumen.top/Article/details/gt2pzignjqd.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jqgfzy.top/Article/details/gt2qalxcoky.html

TS:   arr.map(String)
来源：http://dali.9152youxi.cn/Article/details/gt2pktyvtwh.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.tian-w.cn/Article/details/gt2joazqyjg.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.wangdashe.top/Article/details/gt2ebijiwzl.html

Ruby: arr.map(&:upcase)
来源：http://dali.sxryk.cn/Article/details/gt2zfujnhuq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yj20258888.top/Article/details/gt2wbaadfuv.html

[C08] 闭包
来源：http://dali.chenzaomai.com/Article/details/gt2auyphcpv.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hywenlv.cn/Article/details/gt2nwwlgmqr.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.tanke756.top/Article/details/gt2ceekbrak.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.wangdashe.top/Article/details/gt2futgwxhd.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.redwolf501.top/Article/details/gt2nxzysmdx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hnxiangtu.top/Article/details/gt2gfdzghyx.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.dashuyun.cn/Article/details/gt2lfogkyii.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.mhx1999.top/Article/details/gt2smvmxjxl.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gogol.net.cn/Article/details/gt2mrvikneh.html

[C09] 递归
来源：http://dali.svipenyu.cn/Article/details/gt2sqvpahpd.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ppjwa.cn/Article/details/gt2ymiuambl.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2gpfzpkky.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nanxuanxn.top/Article/details/gt2pbzbymkk.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.aibaodan.cn/Article/details/gt2buvrnjiy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yj202588.top/Article/details/gt2ewvqtrvz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.tanke756.top/Article/details/gt2milbfrrw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxcizvz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bpbwfktg.html

[C10] 变量作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uxgjzdop.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cucudq.cn/Article/details/gt2qhhrulud.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ehwqpu.com/Article/details/gt2aujzpqul.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.tian-w.cn/Article/details/gt2bfoxzdel.html

TS:   同 JS
来源：http://dali.ivvv.top/Article/details/gt2yzkuuzkd.html

Java: 方法内为块级作用域
来源：http://dali.jyoumei.cn/Article/details/gt2cwgnjyrq.html

Go:   花括号块级作用域
来源：http://dali.ybcxt.top/Article/details/gt2xavcxxdk.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zycfv.cn/Article/details/gt2jgjdoqfz.html

C#:   块级作用域
来源：http://dali.smart0.xyz/Article/details/gt2ywjxaogx.html

[C11] 模块导入与导出
来源：http://dali.yvedp.cn/Article/details/gt2pwfhouhw.html

Py:   from module import func
来源：http://dali.hfpthk.cn/Article/details/gt2rjtzgrsb.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ivvv.top/Article/details/gt2zffcyjtx.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhoulong.xyz/Article/details/gt2xmqmftjd.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cqqwz.cn/Article/details/gt2cvygtmyp.html

Java: import java.util.List;
来源：http://dali.redwolf501.top/Article/details/gt2qurfgygx.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yuanzhike.top/Article/details/gt2googslij.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ppjwa.cn/Article/details/gt2dxrcaclv.html

C#:   using System.Text;
来源：http://dali.yj20258.top/Article/details/gt2ezmhrden.html

[C12] 立即执行函数 IIFE
来源：http://dali.snrcjt.cn/Article/details/gt2labcvgct.html

Py:   (lambda: print("run"))()
来源：http://dali.wangshuangyany.cn/Article/details/gt2lpdxsujn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ehwqpu.com/Article/details/gt2pmpzxckt.html

JS:   (() => { console.log("run"); })();
来源：http://dali.meibo888.top/Article/details/gt2bmpkctor.html

TS:   (() => { console.log("run"); })();
来源：http://dali.andypj.xyz/Article/details/gt2tjryfald.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jiagoushi.top/Article/details/gt2gpihlfbe.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gzhubu.top/Article/details/gt2snxbsybq.html

Ruby: -> { puts "run" }.call
来源：http://dali.iojbl.cn/Article/details/gt2yfxtgemt.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ydzc1.top/Article/details/gt2zflekyfm.html

[C13] 类型声明 / 类型注解
来源：http://dali.fzhhl.top/Article/details/gt2vojvmvyq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhongyouzk.top/Article/details/gt2rcjkmpmp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sysykeji.top/Article/details/gt2oaglnedm.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.wangdashe.top/Article/details/gt2nwxwmmol.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrycykjg.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.birdmap.top/Article/details/gt2ylzjbcks.html

Go:   func add(a, b int) int
来源：http://dali.nanxinkj.top/Article/details/gt2fefdlcgi.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.fengsongda.top/Article/details/gt2bcenbdmv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yj20258888.top/Article/details/gt2uwnzvqea.html

[C14] 泛型函数
来源：http://dali.gaohongyu789.top/Article/details/gt2tghyjkuf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ydzc1.top/Article/details/gt2gqrbdoov.html

PHP:  // 无泛型
来源：http://dali.hywenlv.cn/Article/details/gt2atdlvwws.html

JS:   // 无泛型
来源：http://dali.cucudq.cn/Article/details/gt2xbrocgdh.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.gotoacloud.top/Article/details/gt2khldfulb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jlsjyb.cn/Article/details/gt2grtjkycy.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cdnleiting.top/Article/details/gt2nvpgknrm.html

Ruby: # 无泛型
来源：http://dali.cdnleiting.top/Article/details/gt2jewjklzk.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.sxryk.cn/Article/details/gt2ersietet.html

[C15] 解构 / 展开参数
来源：http://dali.shuidangran.top/Article/details/gt2ugtyqxpo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fvrqtmvk.html

PHP:  [$a, $b] = $pair;
来源：http://dali.nwbrower.top/Article/details/gt2wgnizitr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.dashuyun.cn/Article/details/gt2uopfufoo.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yj202588.top/Article/details/gt2sozpvuqg.html

Java: // 无解构
来源：http://dali.ivvv.top/Article/details/gt2rmelaneu.html

Go:   // 无解构
来源：http://dali.aibaodan.cn/Article/details/gt2ipqczlqm.html

Ruby: a, b = pair
来源：http://dali.cucudq.cn/Article/details/gt2owzzfztd.html

C#:   var (a, b) = pair;
来源：http://dali.yvedp.cn/Article/details/gt2fvdvfhfh.html

[C16] 函数 / 方法重载
来源：http://dali.yanxiufei.cn/Article/details/gt2qcbebtkr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.tanke756.top/Article/details/gt2tocymleu.html

PHP:  // 无重载
来源：http://dali.316326.xyz/Article/details/gt2bdpqlbnm.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jianghu66.top/Article/details/gt2iprbhqeu.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.redwolf501.top/Article/details/gt2ugfswdnn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.wangdashe.top/Article/details/gt2ciamlzki.html

Go:   // 无重载：用不同函数名
来源：http://dali.dianchejie.cn/Article/details/gt2ssyvwuko.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vghnnphs.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2amgcrych.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2xbnbjagr.html

D. 数组 / 列表 / 集合
来源：http://dali.sufxvd.cn/Article/details/gt2toylmpwh.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2fchqxsjw.html

[D01] 创建数组 / 列表
来源：http://dali.yongpay.top/Article/details/gt2csvghauw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.chenzaomai.com/Article/details/gt2znrlagoi.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.fengsongda.top/Article/details/gt2tapvrpms.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cucudq.cn/Article/details/gt2ylxgrqri.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yj202588.top/Article/details/gt2gybmhgxs.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yuanzhike.top/Article/details/gt2msolnjrn.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yangfankeji.com/Article/details/gt2ctrgesto.html

Ruby: arr = [1, 2, 3]
来源：http://dali.tanke756.top/Article/details/gt2ydjrflcv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mjvllsox.html

[D02] 追加元素到末尾
来源：http://dali.xuetiantiany.cn/Article/details/gt2dvktpwzi.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zdqjudy.top/Article/details/gt2jqplvvmm.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cdnleiting.top/Article/details/gt2wlqmczsz.html

JS:   arr.push(4);
来源：http://dali.feifeiyinyue.top/Article/details/gt2mlscxmgj.html

TS:   arr.push(4);
来源：http://dali.hnxiangtu.top/Article/details/gt2ueikfkcu.html

Java: list.add(4);
来源：http://dali.chenzaomai.com/Article/details/gt2tmaqkakx.html

Go:   arr = append(arr, 4)
来源：http://dali.jinqigufen.top/Article/details/gt2vvwrqeua.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yueranfly.top/Article/details/gt2gyxplkqo.html

C#:   list.Add(4);
来源：http://dali.meibo888.top/Article/details/gt2xlfblsfb.html

[D03] 在指定位置插入元素
来源：http://dali.yanxiufei.cn/Article/details/gt2ngpycwji.html

Py:   arr.insert(0, 0)
来源：http://dali.jinqigufen.top/Article/details/gt2zttrqisq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xziqi.cn/Article/details/gt2zgpdxspr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.haohaochexian.top/Article/details/gt2pfvpwfsk.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fxrftees.html

Java: list.add(0, 0);
来源：http://dali.zhengqikj.top/Article/details/gt2vusfrnxd.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.andypj.xyz/Article/details/gt2ilpuxjvp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.andypj.xyz/Article/details/gt2clxfsdfe.html

C#:   list.Insert(0, 0);
来源：http://dali.snrcjt.cn/Article/details/gt2nmruubmt.html

[D04] 删除元素
来源：http://dali.ybcxt.top/Article/details/gt2nwfugfkl.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.gaohongyu789.top/Article/details/gt2oulgavbj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jinqigufen.top/Article/details/gt2tqsufkck.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jlsjyb.cn/Article/details/gt2pgtwlyxt.html

TS:   arr.splice(0, 1);
来源：http://dali.sxryk.cn/Article/details/gt2rmpfbqvf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.haohaochexian.top/Article/details/gt2bperbnpg.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.iojbl.cn/Article/details/gt2kjncaoge.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yuanzhike.top/Article/details/gt2mosqknmo.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yqfisbme.html

[D05] 访问与修改元素
来源：http://dali.pycfn.com/Article/details/gt2yxgqhtit.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258888.top/Article/details/gt2sfexinum.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.haohaochexian.top/Article/details/gt2eciyatmy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhiwuduotai.top/Article/details/gt2tudmqpxg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2canlttsl.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gzhubu.top/Article/details/gt2usbfqwxn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ivvv.top/Article/details/gt2enndppva.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenjidiqi.icu/Article/details/gt2ibppyahb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xziqi.cn/Article/details/gt2hsjvszrh.html

[D06] 数组长度
来源：http://dali.tanke756.top/Article/details/gt2robgwjuy.html

Py:   len(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xfwiwcqg.html

PHP:  count($arr);
来源：http://dali.yvedp.cn/Article/details/gt2vgyzmnez.html

JS:   arr.length
来源：http://dali.yanxiufei.cn/Article/details/gt2qqyejiwl.html

TS:   arr.length
来源：http://dali.hfpthk.cn/Article/details/gt2irffwqfp.html

Java: list.size();
来源：http://dali.yanxiufei.cn/Article/details/gt2jbvsbfow.html

Go:   len(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2akwfmiwc.html

Ruby: arr.length; arr.size
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ixuzjnux.html

C#:   list.Count;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nnoukiyo.html

[D07] 切片 / 取子数组
来源：http://dali.zhongyouzk.top/Article/details/gt2buqunzbx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cdnleiting.top/Article/details/gt2fhrzlnyq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xziqi.cn/Article/details/gt2egtirinf.html

JS:   arr.slice(1, 4);
来源：http://dali.pycfn.com/Article/details/gt2inofmvpy.html

TS:   arr.slice(1, 4);
来源：http://dali.ivvv.top/Article/details/gt2aaugphqv.html

Java: list.subList(1, 4);
来源：http://dali.shuidangran.top/Article/details/gt2davbllis.html

Go:   arr[1:4]
来源：http://dali.havefunace.top/Article/details/gt2tcugukma.html

Ruby: arr[1, 3]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yjwjbxue.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxzluqv.html

[D08] 合并两个数组
来源：http://dali.snrcjt.cn/Article/details/gt2wdmjzsnc.html

Py:   a + b;  a.extend(b)
来源：http://dali.quarkkingdee.top/Article/details/gt2wlnxukew.html

PHP:  array_merge($a, $b);
来源：http://dali.hnxiangtu.top/Article/details/gt2vbkprguu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.gogol.net.cn/Article/details/gt2uczfflti.html

TS:   [...a, ...b];
来源：http://dali.cucudq.cn/Article/details/gt2brluocki.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.chenlongwang.top/Article/details/gt2xqgjtgpt.html

Go:   append(a, b...)
来源：http://dali.c1oappe.top/Article/details/gt2vnlgoslw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yj20258.top/Article/details/gt2jxsrqlrp.html

C#:   a.Concat(b).ToList()
来源：http://dali.yongpay.top/Article/details/gt2xmpdoxxo.html

[D09] 排序（升序）
来源：http://dali.ybcxt.top/Article/details/gt2ouhkbmoo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258.top/Article/details/gt2dnfsyazl.html

PHP:  sort($arr);
来源：http://dali.pycfn.com/Article/details/gt2tcjbwexq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.mhx1999.top/Article/details/gt2jbrpareh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.daria6918.cn/Article/details/gt2dxphqcsy.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.bjfxy.top/Article/details/gt2ajhtjhly.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.daxiang520.top/Article/details/gt2kfxzrjuy.html

Ruby: arr.sort
来源：http://dali.hfpthk.cn/Article/details/gt2tkhhkjbe.html

C#:   list.Sort();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fldsntwm.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.fengsongda.top/Article/details/gt2agyauyyw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.0kj1m.cn/Article/details/gt2iqyumkpf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenjidiqi.icu/Article/details/gt2jeiijdwg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dashuyun.cn/Article/details/gt2swsaiftk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuetiantiany.cn/Article/details/gt2btbfifoi.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.c1oappe.top/Article/details/gt2eztsjgzc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.9152youxi.cn/Article/details/gt2koxheuvs.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.quarkkingdee.top/Article/details/gt2yyiqgmos.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.tian-w.cn/Article/details/gt2niylrcsy.html

[D11] 反转数组
来源：http://dali.yj20258.top/Article/details/gt2xspnzjul.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yj202588.top/Article/details/gt2uhehcaxl.html

PHP:  array_reverse($arr);
来源：http://dali.ybcxt.top/Article/details/gt2yqpkwvlf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.316326.xyz/Article/details/gt2mpxtwilt.html

TS:   [...arr].reverse();
来源：http://dali.gaohongyu789.top/Article/details/gt2dfhwzhje.html

Java: Collections.reverse(list);
来源：http://dali.zhixingplan.top/Article/details/gt2yviuyybt.html

Go:   slices.Reverse(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ptswxgax.html

Ruby: arr.reverse
来源：http://dali.jianghu66.top/Article/details/gt2zezhvllf.html


<!-- 参考信息 -->