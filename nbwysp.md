代发 wailian999

PHP:  range(0, 10, 2);
来源：http://dali.cheryme.top/Article/details/gt2ptjvuxtt.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj20258888.top/Article/details/gt2wfchdhba.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xuetiantiany.cn/Article/details/gt2auwvwrli.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.guowangkeji.top/Article/details/gt2jgvcjzcu.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jqgufenzy.top/Article/details/gt2voayiego.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cbjdwbsp.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.aizwys.cn/Article/details/gt2qkufxkln.html

[B12] 跳出多层循环
来源：http://dali.pycfn.com/Article/details/gt2hdxwoomj.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yvedp.cn/Article/details/gt2ibfgoglt.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jyoumei.cn/Article/details/gt2lhxvjczw.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.guowangkeji.top/Article/details/gt2rtzyszfy.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.guannengcc.top/Article/details/gt2ioemmwlx.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.snrcjt.cn/Article/details/gt2fyrauuts.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.fengsongda.top/Article/details/gt2itqeznqw.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.dashuyun.cn/Article/details/gt2mrjcagqd.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.guannengcc.top/Article/details/gt2qcqrecsj.html

[B13] 判断是否为数字
来源：http://dali.316326.xyz/Article/details/gt2melyrwqu.html

Py:   isinstance(x, (int, float))
来源：http://dali.gaohongyu789.top/Article/details/gt2ayclstqk.html

PHP:  is_numeric($x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2reufwzba.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sysykeji.top/Article/details/gt2enabvqeu.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gzhubu.top/Article/details/gt2gaaceokx.html

Java: x instanceof Number
来源：http://dali.xuetiantiany.cn/Article/details/gt2zagzeibs.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ybcxt.top/Article/details/gt2jjcbabqd.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wipwlbqx.html

C#:   x is int or double or decimal
来源：http://dali.yj20258888.top/Article/details/gt2ziyvulfd.html

[B14] 判断值是否在集合内
来源：http://dali.shuidangran.top/Article/details/gt2jylvbcvl.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dwshrkcs.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hywenlv.cn/Article/details/gt2mdrtqhce.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2nfenuuzz.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.cheryme.top/Article/details/gt2rzwhsgjg.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yuxming.cn/Article/details/gt2pognhuzd.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.mhx1999.top/Article/details/gt2ccmkxsrg.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tcurlfgv.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yangfankeji.com/Article/details/gt2ozkkjarh.html

[B15] 布尔运算与取反
来源：http://dali.sxryk.cn/Article/details/gt2bqimtzop.html

Py:   a and b or not c
来源：http://dali.snrcjt.cn/Article/details/gt2axiksves.html

PHP:  $a && $b || !$c
来源：http://dali.xylfe.cn/Article/details/gt2rfbskxgh.html

JS:   a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gt2qkegkzhr.html

TS:   a && b || !c
来源：http://dali.yueranfly.top/Article/details/gt2llfcxzzu.html

Java: a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gt2ktlzvxvk.html

Go:   a && b || !c
来源：http://dali.yvedp.cn/Article/details/gt2btstdwtp.html

Ruby: a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gt2pepcmofk.html

C#:   a && b || !c
来源：http://dali.cheryme.top/Article/details/gt2gcbekaxj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zdqjudy.top/Article/details/gt2ppfxudcs.html

Py:   if not data: return
来源：http://dali.yangfankeji.com/Article/details/gt2oxqjxzmd.html

PHP:  if (!$data) { return; }
来源：http://dali.chenzaomai.com/Article/details/gt2kcsmkvzz.html

JS:   if (!data) return;
来源：http://dali.quarkkingdee.top/Article/details/gt2qjlvyolu.html

TS:   if (!data) return;
来源：http://dali.zhengqikj.top/Article/details/gt2mmxdcsoo.html

Java: if (data == null) return;
来源：http://dali.sufxvd.cn/Article/details/gt2wuhudvrb.html

Go:   if data == nil { return }
来源：http://dali.gogol.net.cn/Article/details/gt2lopzvaql.html

Ruby: return if data.nil?
来源：http://dali.meibo888.top/Article/details/gt2atsrkcww.html

C#:   if (data == null) return;
来源：http://dali.havefunace.top/Article/details/gt2qvhbdwpj.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2inlhcbma.html

C. 函数与作用域
来源：http://dali.ydzc1.top/Article/details/gt2slnntnsl.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2vwymsdvi.html

[C01] 定义函数
来源：http://dali.zhixingplan.top/Article/details/gt2plxvfaeo.html

Py:   def add(a, b): return a + b
来源：http://dali.aibaodan.cn/Article/details/gt2cjwkwjvn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.smart0.xyz/Article/details/gt2nqcmosop.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gt2rhojvmju.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gt2ghlsvxls.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gt2flmotrhg.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ybcxt.top/Article/details/gt2fnvqjgvh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yangfankeji.com/Article/details/gt2hwvediao.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2rogmckua.html

[C02] 默认参数
来源：http://dali.yonumen.top/Article/details/gt2nqqmipfq.html

Py:   def greet(name="World"): return name
来源：http://dali.yj20258888.top/Article/details/gt2cvwofpwr.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2mrjxuymo.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ehwqpu.com/Article/details/gt2trtuhpgv.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.snrcjt.cn/Article/details/gt2zfdczvuf.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cdnleiting.top/Article/details/gt2hokawuuf.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yj20258.top/Article/details/gt2frhkzlzj.html

Ruby: def greet(name = "World") = name
来源：http://dali.dashuyun.cn/Article/details/gt2gydwlxoi.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.svipenyu.cn/Article/details/gt2wbncdtpb.html

[C03] 可变参数
来源：http://dali.fengsongda.top/Article/details/gt2gvnsarkd.html

Py:   def total(*args): return sum(args)
来源：http://dali.pycfn.com/Article/details/gt2tbxpmglt.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.meibo888.top/Article/details/gt2ncewinml.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yvedp.cn/Article/details/gt2scyhipgw.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cdnleiting.top/Article/details/gt2eycrqozo.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.birdmap.top/Article/details/gt2fhjebwdx.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.mhx1999.top/Article/details/gt2geddmiqw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jlsjyb.cn/Article/details/gt2opfgwval.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhengqikj.top/Article/details/gt2hjvhjjir.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zycfv.cn/Article/details/gt2gnuxwiqg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vnsmyjdg.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hqityfqv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cheryme.top/Article/details/gt2utmhulka.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jyoumei.cn/Article/details/gt2adlnixcl.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.guannengcc.top/Article/details/gt2vcitvlpm.html

Go:   // 无：用配置结构体参数
来源：http://dali.sxryk.cn/Article/details/gt2nbjhbvhm.html

Ruby: f(a: 1, b: 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2wfipkaaa.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hmervtij.html

[C05] 返回多个值
来源：http://dali.yonumen.top/Article/details/gt2jjrohduw.html

Py:   return a, b
来源：http://dali.pycfn.com/Article/details/gt2nakjsefs.html

PHP:  return [$a, $b];
来源：http://dali.9152youxi.cn/Article/details/gt2dhmjxrpn.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shzxlz.cn/Article/details/gt2myvlqkmv.html

TS:   return { a, b };
来源：http://dali.hnqzz.top/Article/details/gt2qkhwaswf.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.wangshuangyany.cn/Article/details/gt2xrhratff.html

Go:   return a, b
来源：http://dali.ehwqpu.com/Article/details/gt2ibcypotj.html

Ruby: return a, b
来源：http://dali.hongshengwenyu.top/Article/details/gt2vnhhataf.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.aizwys.cn/Article/details/gt2fpjbjfhe.html

[C06] 匿名函数 / lambda
来源：http://dali.jianghu66.top/Article/details/gt2kjzmzpkk.html

Py:   square = lambda x: x * x
来源：http://dali.redwolf501.top/Article/details/gt2yteyejtv.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhengqikj.top/Article/details/gt2zsjnrtpm.html

JS:   const square = x => x * x;
来源：http://dali.316326.xyz/Article/details/gt2shlgqufd.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.0kj1m.cn/Article/details/gt2cskvtgjs.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.tianlin.xyz/Article/details/gt2onfmsqrq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.9152youxi.cn/Article/details/gt2xtqxsanj.html

Ruby: square = ->(x) { x * x }
来源：http://dali.316326.xyz/Article/details/gt2bcwlewyt.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yuxming.cn/Article/details/gt2xdozjhes.html

[C07] 把函数作为参数传入
来源：http://dali.hnxiangtu.top/Article/details/gt2quawohyx.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hammf.cn/Article/details/gt2btrjasll.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxymskdq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.guowangkeji.top/Article/details/gt2kqahayyt.html

TS:   arr.map(String)
来源：http://dali.9152youxi.cn/Article/details/gt2crruzsei.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gaohongyu789.top/Article/details/gt2ummyfllp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yongpay.top/Article/details/gt2qgokcqth.html

Ruby: arr.map(&:upcase)
来源：http://dali.yueranfly.top/Article/details/gt2zaiwwuba.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.gaohongyu789.top/Article/details/gt2nxjdiywr.html

[C08] 闭包
来源：http://dali.xziqi.cn/Article/details/gt2mqbljxud.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.aibaodan.cn/Article/details/gt2akehrfeb.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.daxiang520.top/Article/details/gt2zhmhnyhf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xinyue.icu/Article/details/gt2apcgusgf.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xylfe.cn/Article/details/gt2nxaibdde.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gzhubu.top/Article/details/gt2ommzdmcb.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.smart0.xyz/Article/details/gt2wjkagawc.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.fzhhl.top/Article/details/gt2tmrcyssd.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.smart0.xyz/Article/details/gt2tqdaakxr.html

[C09] 递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2okfdhrkq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.haohaochexian.top/Article/details/gt2rnxzqnhg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jlsjyb.cn/Article/details/gt2pkqjoyba.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ivvv.top/Article/details/gt2fbbwqmxj.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xuetiantiany.cn/Article/details/gt2tgeunquk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.chenzaomai.com/Article/details/gt2emzldjuz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.andypj.xyz/Article/details/gt2ldqazora.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.dashuyun.cn/Article/details/gt2srwtaels.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oouqhhyp.html

[C10] 变量作用域
来源：http://dali.jqgfzy.top/Article/details/gt2psvhkfsw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ppjwa.cn/Article/details/gt2bhksehae.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.kuanghao11.cn/Article/details/gt2hqjpsqpi.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gaohongyu789.top/Article/details/gt2knlzqump.html

TS:   同 JS
来源：http://dali.ybcxt.top/Article/details/gt2zcglauog.html

Java: 方法内为块级作用域
来源：http://dali.dianchejie.cn/Article/details/gt2miyihahy.html

Go:   花括号块级作用域
来源：http://dali.hongshengwenyu.top/Article/details/gt2vmfmpyso.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.redwolf501.top/Article/details/gt2ihxpmiri.html

C#:   块级作用域
来源：http://dali.bjfxy.top/Article/details/gt2qwitqcyr.html

[C11] 模块导入与导出
来源：http://dali.shangyingyoupin.top/Article/details/gt2ncxfbcrk.html

Py:   from module import func
来源：http://dali.xuetiantiany.cn/Article/details/gt2jnervnek.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.0kj1m.cn/Article/details/gt2wavwngqf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ppjwa.cn/Article/details/gt2bywfrpqb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xmilfvfu.html

Java: import java.util.List;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hmoabvwh.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yangfankeji.com/Article/details/gt2oodqgwpp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.iojbl.cn/Article/details/gt2tscsnoyi.html

C#:   using System.Text;
来源：http://dali.zhengqikj.top/Article/details/gt2nolbfxxp.html

[C12] 立即执行函数 IIFE
来源：http://dali.jinqigufen.top/Article/details/gt2hgwmehfh.html

Py:   (lambda: print("run"))()
来源：http://dali.chenzaomai.com/Article/details/gt2echptnkt.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhiwuduotai.top/Article/details/gt2htyzpuhx.html

JS:   (() => { console.log("run"); })();
来源：http://dali.pycfn.com/Article/details/gt2ngtipebu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.mhx1999.top/Article/details/gt2tlvjqgzb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.andypj.xyz/Article/details/gt2cghhzgal.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.mhx1999.top/Article/details/gt2kuymwork.html

Ruby: -> { puts "run" }.call
来源：http://dali.gaohongyu789.top/Article/details/gt2sjpmtbse.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rwyfzrgd.html

[C13] 类型声明 / 类型注解
来源：http://dali.jinqigfzy.top/Article/details/gt2fwqcazky.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shzxlz.cn/Article/details/gt2zhowbfhv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jlsjyb.cn/Article/details/gt2yzkpqykf.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zxiyrdse.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gt2lovdmiix.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2erjrboxe.html

Go:   func add(a, b int) int
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yxfnuclj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.daxiang520.top/Article/details/gt2ncvkmare.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gaohongyu789.top/Article/details/gt2zamjuxee.html

[C14] 泛型函数
来源：http://dali.nwbrower.top/Article/details/gt2ytchuypy.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wwldpwbi.html

PHP:  // 无泛型
来源：http://dali.dianchejie.cn/Article/details/gt2bbqqwczy.html

JS:   // 无泛型
来源：http://dali.zhongyouzk.top/Article/details/gt2jstywoat.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.vqdsnc.cn/Article/details/gt2culxiaby.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.guannengcc.top/Article/details/gt2wffaarlr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.mhx1999.top/Article/details/gt2rfftptju.html

Ruby: # 无泛型
来源：http://dali.bjfxy.top/Article/details/gt2hjgnmhca.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yanxiufei.cn/Article/details/gt2cpafulzc.html

[C15] 解构 / 展开参数
来源：http://dali.yj20258888.top/Article/details/gt2pnqcftce.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.tianlin.xyz/Article/details/gt2nsyjnmhw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhixingplan.top/Article/details/gt2rlzdiilh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ehwqpu.com/Article/details/gt2tpfiqizd.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2xecqfoxj.html

Java: // 无解构
来源：http://dali.sufxvd.cn/Article/details/gt2vzffpgeq.html

Go:   // 无解构
来源：http://dali.sweek.top/Article/details/gt2btdpkzed.html

Ruby: a, b = pair
来源：http://dali.xylfe.cn/Article/details/gt2ptqwydoc.html

C#:   var (a, b) = pair;
来源：http://dali.sysykeji.top/Article/details/gt2qpjedwbw.html

[C16] 函数 / 方法重载
来源：http://dali.sufxvd.cn/Article/details/gt2fhxuxzdo.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.havefunace.top/Article/details/gt2ifsdcwbh.html

PHP:  // 无重载
来源：http://dali.hammf.cn/Article/details/gt2fjdfzuzz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2etzukkyc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.daria6918.cn/Article/details/gt2jewhcafq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ivvv.top/Article/details/gt2dpipshvp.html

Go:   // 无重载：用不同函数名
来源：http://dali.guannengcc.top/Article/details/gt2uajmzamk.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhongyouzk.top/Article/details/gt2kqfuzegi.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2evnamziu.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tkvjviqt.html

D. 数组 / 列表 / 集合
来源：http://dali.tanke756.top/Article/details/gt2azjjccar.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2ybfhzseu.html

[D01] 创建数组 / 列表
来源：http://dali.meibo888.top/Article/details/gt2kqflryzx.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.nwbrower.top/Article/details/gt2phwkmbiq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.316326.xyz/Article/details/gt2tyjtgrkf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.aizwys.cn/Article/details/gt2lrdxnbio.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhixingplan.top/Article/details/gt2hmxqkcmt.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hfpthk.cn/Article/details/gt2uvhcmcew.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mfsshvmv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.snrcjt.cn/Article/details/gt2qerpaomd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.meibo888.top/Article/details/gt2howwsggp.html

[D02] 追加元素到末尾
来源：http://dali.zhoulong.xyz/Article/details/gt2oyefprzz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hnqzz.top/Article/details/gt2evkxuneh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.pengpengdd.cyou/Article/details/gt2qgfcbdxw.html

JS:   arr.push(4);
来源：http://dali.kuanghao11.cn/Article/details/gt2lsgeggsg.html

TS:   arr.push(4);
来源：http://dali.zhiwuduotai.top/Article/details/gt2xkdlbgwi.html

Java: list.add(4);
来源：http://dali.sufxvd.cn/Article/details/gt2kjxxeapx.html

Go:   arr = append(arr, 4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jqbbfbvn.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jlsjyb.cn/Article/details/gt2nevmdjbf.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ravljynk.html

[D03] 在指定位置插入元素
来源：http://dali.ydzc1.top/Article/details/gt2stpcefyx.html

Py:   arr.insert(0, 0)
来源：http://dali.gogol.net.cn/Article/details/gt2xbaofkwo.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.quarkkingdee.top/Article/details/gt2sqobxtzd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cjlnyanf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jiagoushi.top/Article/details/gt2wagafyqb.html

Java: list.add(0, 0);
来源：http://dali.jqgfzy.top/Article/details/gt2msohyzbh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2trozhhmv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.tian-w.cn/Article/details/gt2qdbltmee.html

C#:   list.Insert(0, 0);
来源：http://dali.gotoacloud.top/Article/details/gt2cuxmdxzu.html

[D04] 删除元素
来源：http://dali.kuanghao11.cn/Article/details/gt2oiaknzme.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tpjxlxuh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhixingplan.top/Article/details/gt2ykdwoyqr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shuidangran.top/Article/details/gt2fevxicmz.html

TS:   arr.splice(0, 1);
来源：http://dali.dianchejie.cn/Article/details/gt2gsgoqknw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.nanxinkj.top/Article/details/gt2xrjdabqj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yj20258888.top/Article/details/gt2kxyuihqz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2nqtmdtyc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cheryme.top/Article/details/gt2oliqvkvo.html

[D05] 访问与修改元素
来源：http://dali.tian-w.cn/Article/details/gt2nblhslej.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hongshengwenyu.top/Article/details/gt2rqgjueye.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yonumen.top/Article/details/gt2keerwyqn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.andypj.xyz/Article/details/gt2juwyjqkv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jianghu66.top/Article/details/gt2bnpiopzw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.pengpengdd.cyou/Article/details/gt2hnsbszci.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2npxwyerw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hfpthk.cn/Article/details/gt2xidjhhzl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yanxiufei.cn/Article/details/gt2yeyhwxxk.html

[D06] 数组长度
来源：http://dali.yuanzhike.top/Article/details/gt2lbbgdjho.html

Py:   len(arr)
来源：http://dali.birdmap.top/Article/details/gt2zghtdhsc.html

PHP:  count($arr);
来源：http://dali.jianghu66.top/Article/details/gt2yfscokqj.html

JS:   arr.length
来源：http://dali.iojbl.cn/Article/details/gt2hrkuelwk.html

TS:   arr.length
来源：http://dali.sufxvd.cn/Article/details/gt2vmrpaldy.html

Java: list.size();
来源：http://dali.pycfn.com/Article/details/gt2smpynpwk.html

Go:   len(arr)
来源：http://dali.yj20258.top/Article/details/gt2utgoussg.html

Ruby: arr.length; arr.size
来源：http://dali.chenzaomai.com/Article/details/gt2yrfxiwim.html

C#:   list.Count;
来源：http://dali.gogol.net.cn/Article/details/gt2whjvydej.html

[D07] 切片 / 取子数组
来源：http://dali.hammf.cn/Article/details/gt2kxaxqpha.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xcycozxm.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hammf.cn/Article/details/gt2kyainbjo.html

JS:   arr.slice(1, 4);
来源：http://dali.nanxuanxn.top/Article/details/gt2ehtuzatz.html

TS:   arr.slice(1, 4);
来源：http://dali.yj20258888.top/Article/details/gt2nansfick.html

Java: list.subList(1, 4);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ipwruhbe.html

Go:   arr[1:4]
来源：http://dali.havefunace.top/Article/details/gt2wnxptqpy.html

Ruby: arr[1, 3]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gckrvhlj.html

C#:   list.GetRange(1, 3);
来源：http://dali.cdnleiting.top/Article/details/gt2stghjeey.html

[D08] 合并两个数组
来源：http://dali.guowangkeji.top/Article/details/gt2afbcwshh.html

Py:   a + b;  a.extend(b)
来源：http://dali.nanxinkj.top/Article/details/gt2vorjecgf.html

PHP:  array_merge($a, $b);
来源：http://dali.meibo888.top/Article/details/gt2gixgmtjf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ppjwa.cn/Article/details/gt2okkpadou.html

TS:   [...a, ...b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tjtobioc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.meibo888.top/Article/details/gt2ylexfaiw.html

Go:   append(a, b...)
来源：http://dali.guannengcc.top/Article/details/gt2ljxalvuo.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jinqigufen.top/Article/details/gt2lpxlhwxv.html

C#:   a.Concat(b).ToList()
来源：http://dali.cashguo.top/Article/details/gt2gguuutxf.html

[D09] 排序（升序）
来源：http://dali.iojbl.cn/Article/details/gt2hroghgbu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258.top/Article/details/gt2vbeosdlr.html

PHP:  sort($arr);
来源：http://dali.c1oappe.top/Article/details/gt2ybiebill.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.guannengcc.top/Article/details/gt2xpsdhbyn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.kuanghao11.cn/Article/details/gt2jqqjyzfx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xinyue.icu/Article/details/gt2phwjudsg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sawsjokh.html

Ruby: arr.sort
来源：http://dali.gzhubu.top/Article/details/gt2mqhrsxke.html

C#:   list.Sort();
来源：http://dali.hnxiangtu.top/Article/details/gt2utqdpzlj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eaxrsvxf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pkbpmfzu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.svipenyu.cn/Article/details/gt2arrwyabo.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258.top/Article/details/gt2ceykxdpz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jlsjyb.cn/Article/details/gt2beivbpcc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ydzc1.top/Article/details/gt2vwoawlwa.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.fengsongda.top/Article/details/gt2mlqnahtc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.andypj.xyz/Article/details/gt2zkjtrjjg.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zdqjudy.top/Article/details/gt2vkfvcgrd.html

[D11] 反转数组
来源：http://dali.xylfe.cn/Article/details/gt2svyzzyfz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jyoumei.cn/Article/details/gt2zhhprjll.html

PHP:  array_reverse($arr);
来源：http://dali.sxryk.cn/Article/details/gt2ykdofjzx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.pengpengdd.cyou/Article/details/gt2qssxcubm.html

TS:   [...arr].reverse();
来源：http://dali.yangfankeji.com/Article/details/gt2kpskyttl.html

Java: Collections.reverse(list);
来源：http://dali.yongpay.top/Article/details/gt2kdakzrbb.html

Go:   slices.Reverse(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2kymjdulo.html

Ruby: arr.reverse
来源：http://dali.wangdashe.top/Article/details/gt2evhzqypb.html


<!-- 参考信息 -->