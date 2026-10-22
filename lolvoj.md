代发 wailian999

PHP:  range(0, 10, 2);
来源：http://dali.bjfxy.top/Article/details/gtuuajtnre.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinqigufen.top/Article/details/gtrgmroefm.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.c1oappe.top/Article/details/gtocjbtnvw.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.gogol.net.cn/Article/details/gtslmtigyh.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.bjfxy.top/Article/details/gtstfnopwx.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhiwuduotai.top/Article/details/gtbfnjqeuj.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.pycfn.com/Article/details/gtfdjvysxg.html

[B12] 跳出多层循环
来源：http://dali.daria6918.cn/Article/details/gtgtpctgvk.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.c1oappe.top/Article/details/gtgdetfnta.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.kuanghao11.cn/Article/details/gtzructwpa.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhixingplan.top/Article/details/gtbgfxlske.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.daria6918.cn/Article/details/gtigkfazly.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zycfv.cn/Article/details/gtboxfhytr.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.gzhubu.top/Article/details/gtrcqeijen.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ppjwa.cn/Article/details/gttewswdsp.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.tianlin.xyz/Article/details/gtxanxmxco.html

[B13] 判断是否为数字
来源：http://dali.cheryme.top/Article/details/gtsahdjwvq.html

Py:   isinstance(x, (int, float))
来源：http://dali.wangdashe.top/Article/details/gtuaeuuqkn.html

PHP:  is_numeric($x)
来源：http://dali.nanxinkj.top/Article/details/gtbaiujtya.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.316326.xyz/Article/details/gtjahpemid.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zycfv.cn/Article/details/gtbbomghsl.html

Java: x instanceof Number
来源：http://dali.fzhhl.top/Article/details/gtzsfrzfdg.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.kuanghao11.cn/Article/details/gtqueqcwmf.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ydzc1.top/Article/details/gtjdtkoohh.html

C#:   x is int or double or decimal
来源：http://dali.feifeiyinyue.top/Article/details/gtqbpsvcwh.html

[B14] 判断值是否在集合内
来源：http://dali.gotoacloud.top/Article/details/gtbebpoobr.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yanxiufei.cn/Article/details/gtuzkpzctp.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hnxiangtu.top/Article/details/gtxpomdkms.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.dashuyun.cn/Article/details/gtaukfjqtw.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258888.top/Article/details/gtgxsbzccr.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.dianchejie.cn/Article/details/gtkdjavjzt.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.sysykeji.top/Article/details/gtezyeyczc.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.cdnleiting.top/Article/details/gtunpnbrin.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xylfe.cn/Article/details/gttaczisoo.html

[B15] 布尔运算与取反
来源：http://dali.yvedp.cn/Article/details/gtgyqdvmjb.html

Py:   a and b or not c
来源：http://dali.zhixingplan.top/Article/details/gtekpksyrh.html

PHP:  $a && $b || !$c
来源：http://dali.xinyue.icu/Article/details/gtoghaswma.html

JS:   a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gtnzhubbdl.html

TS:   a && b || !c
来源：http://dali.zycfv.cn/Article/details/gtfnvituvd.html

Java: a && b || !c
来源：http://dali.yangfankeji.com/Article/details/gtplfabmvv.html

Go:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gttmmhpxwf.html

Ruby: a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gtdovpesif.html

C#:   a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gtbbfnjfxi.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zycfv.cn/Article/details/gtgrhawnwt.html

Py:   if not data: return
来源：http://dali.daria6918.cn/Article/details/gtcltjelfc.html

PHP:  if (!$data) { return; }
来源：http://dali.zhoulong.xyz/Article/details/gtybxpftoh.html

JS:   if (!data) return;
来源：http://dali.jianghu66.top/Article/details/gtlmszdxry.html

TS:   if (!data) return;
来源：http://dali.andypj.xyz/Article/details/gtrxowvzrm.html

Java: if (data == null) return;
来源：http://dali.havefunace.top/Article/details/gtaciteheh.html

Go:   if data == nil { return }
来源：http://dali.nwbrower.top/Article/details/gtepdkwbdp.html

Ruby: return if data.nil?
来源：http://dali.feifeiyinyue.top/Article/details/gtufrrcrgd.html

C#:   if (data == null) return;
来源：http://dali.kuanghao11.cn/Article/details/gtrzqsjzvh.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtobihfbtf.html

C. 函数与作用域
来源：http://dali.aizwys.cn/Article/details/gtzvvixmen.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtpgfetxor.html

[C01] 定义函数
来源：http://dali.0kj1m.cn/Article/details/gtqrpavspe.html

Py:   def add(a, b): return a + b
来源：http://dali.nwbrower.top/Article/details/gtpzmzgfvd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gaohongyu789.top/Article/details/gtkdgzaxpi.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gttjzhmqnh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cheryme.top/Article/details/gtniggpvll.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gtycinqnlk.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.tian-w.cn/Article/details/gtrsbfmfxt.html

Ruby: def add(a, b); a + b; end
来源：http://dali.guannengcc.top/Article/details/gtnflsjrpa.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtmllmjrwl.html

[C02] 默认参数
来源：http://dali.dashuyun.cn/Article/details/gtvutlndbt.html

Py:   def greet(name="World"): return name
来源：http://dali.9152youxi.cn/Article/details/gtyfcasgfz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xylfe.cn/Article/details/gtbxoisbdi.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtllfndwvo.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xinyue.icu/Article/details/gtajtneqxf.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.meibo888.top/Article/details/gtxoqtrvxn.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jyoumei.cn/Article/details/gtyiedcqkj.html

Ruby: def greet(name = "World") = name
来源：http://dali.bjfxy.top/Article/details/gtihwmubxw.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shzxlz.cn/Article/details/gtjhsguaxk.html

[C03] 可变参数
来源：http://dali.gotoacloud.top/Article/details/gtqgedwmsm.html

Py:   def total(*args): return sum(args)
来源：http://dali.hammf.cn/Article/details/gtxcxibuhk.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.smart0.xyz/Article/details/gtrjqahhqt.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hnxiangtu.top/Article/details/gtficgxiwi.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sweek.top/Article/details/gtuwbpsuxs.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhongyouzk.top/Article/details/gtgppigzbb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.chenzaomai.com/Article/details/gtacpnnomw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.tianlin.xyz/Article/details/gtnlshfsue.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhengqikj.top/Article/details/gtgiougjib.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jqgufenzy.top/Article/details/gtwjcmhxys.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xuanzx.com/Article/details/gtrrblqfzy.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jianghu66.top/Article/details/gtftejqgmv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ydzc1.top/Article/details/gtcfpjiyey.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.quarkkingdee.top/Article/details/gtibtfrovj.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shangyingyoupin.top/Article/details/gtpyjhcyor.html

Go:   // 无：用配置结构体参数
来源：http://dali.cqqwz.cn/Article/details/gtysozuqtl.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xylfe.cn/Article/details/gtzpbsidwt.html

C#:   f(a: 1, b: 2)
来源：http://dali.0kj1m.cn/Article/details/gtlktzujnd.html

[C05] 返回多个值
来源：http://dali.xinyue.icu/Article/details/gtrtdnidbd.html

Py:   return a, b
来源：http://dali.zhengqikj.top/Article/details/gtgfbdlmgk.html

PHP:  return [$a, $b];
来源：http://dali.smart0.xyz/Article/details/gtkilvdtrk.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcwlhrezd.html

TS:   return { a, b };
来源：http://dali.iojbl.cn/Article/details/gtdoweybet.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ybcxt.top/Article/details/gtymcbffao.html

Go:   return a, b
来源：http://dali.ppjwa.cn/Article/details/gtsflkjrfp.html

Ruby: return a, b
来源：http://dali.sweek.top/Article/details/gtuptreqkr.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.sysykeji.top/Article/details/gtwuomskdo.html

[C06] 匿名函数 / lambda
来源：http://dali.jqgfzy.top/Article/details/gtjzpxjyyj.html

Py:   square = lambda x: x * x
来源：http://dali.c1oappe.top/Article/details/gtevfqnsco.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.feifeiyinyue.top/Article/details/gtnoeznkvg.html

JS:   const square = x => x * x;
来源：http://dali.ppjwa.cn/Article/details/gtngdbccts.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hfpthk.cn/Article/details/gtzhexmrqa.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.haohaochexian.top/Article/details/gtzaezrspf.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xziqi.cn/Article/details/gtigmenjxu.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hnxiangtu.top/Article/details/gtmfkhghpj.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yongpay.top/Article/details/gtosuxrntg.html

[C07] 把函数作为参数传入
来源：http://dali.wangshuangyany.cn/Article/details/gtubzvvwiy.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.daxiang520.top/Article/details/gtlihkbatc.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdpuhkjrf.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.nanxinkj.top/Article/details/gtvwhasssq.html

TS:   arr.map(String)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxfcpqxsg.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ydzc1.top/Article/details/gtotgvkckq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hammf.cn/Article/details/gtvekfprdl.html

Ruby: arr.map(&:upcase)
来源：http://dali.yuxming.cn/Article/details/gtqancgfpl.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.dashuyun.cn/Article/details/gtkwdbmtrs.html

[C08] 闭包
来源：http://dali.shangyingyoupin.top/Article/details/gthrdtxqeo.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hongshengwenyu.top/Article/details/gtkaknppxf.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.nwbrower.top/Article/details/gtzpvewphq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.tianlin.xyz/Article/details/gtikrhywgu.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.mhx1999.top/Article/details/gtavmnzdft.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhongyouzk.top/Article/details/gtlipsyoww.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.tanke756.top/Article/details/gtdufwmjhn.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hnxiangtu.top/Article/details/gtgnlgaqyr.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jqgufenzy.top/Article/details/gtzorjnbdh.html

[C09] 递归
来源：http://dali.zycfv.cn/Article/details/gtqvelfxpb.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jiagoushi.top/Article/details/gtnvbjmhno.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhiwuduotai.top/Article/details/gtqreqogng.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.kuanghao11.cn/Article/details/gtlshsuock.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yanxiufei.cn/Article/details/gtidejumpb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zycfv.cn/Article/details/gtnlmxyqaf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.kuanghao11.cn/Article/details/gtnecswklb.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhoulong.xyz/Article/details/gttidkjwjj.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ppjwa.cn/Article/details/gtkkrqobax.html

[C10] 变量作用域
来源：http://dali.xziqi.cn/Article/details/gtspqfcmfg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.sufxvd.cn/Article/details/gtywpqrusl.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.fzhhl.top/Article/details/gtjbvmsrej.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.9152youxi.cn/Article/details/gtayqltdvz.html

TS:   同 JS
来源：http://dali.hysaishi.cn/Article/details/gtpiuhijsl.html

Java: 方法内为块级作用域
来源：http://dali.smart0.xyz/Article/details/gtsgpkpodq.html

Go:   花括号块级作用域
来源：http://dali.316326.xyz/Article/details/gtylwhsysu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.andypj.xyz/Article/details/gtccsypqep.html

C#:   块级作用域
来源：http://dali.feifeiyinyue.top/Article/details/gtztobljcg.html

[C11] 模块导入与导出
来源：http://dali.c1oappe.top/Article/details/gtaafxrsqw.html

Py:   from module import func
来源：http://dali.hammf.cn/Article/details/gtzackrgnf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.sysykeji.top/Article/details/gtwufmkvym.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.guowangkeji.top/Article/details/gtznwihyqr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.gotoacloud.top/Article/details/gtenakegoi.html

Java: import java.util.List;
来源：http://dali.chenlongwang.top/Article/details/gtsumjofbi.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.nanxuanxn.top/Article/details/gtihuxluro.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtowdipift.html

C#:   using System.Text;
来源：http://dali.jianghu66.top/Article/details/gtvsfzqozq.html

[C12] 立即执行函数 IIFE
来源：http://dali.vqdsnc.cn/Article/details/gtayxxfihy.html

Py:   (lambda: print("run"))()
来源：http://dali.zhongyouzk.top/Article/details/gtuarkztmc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.wangdashe.top/Article/details/gtuopazctw.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xinyue.icu/Article/details/gtvszqpwpq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hysaishi.cn/Article/details/gtsywiwblo.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cheryme.top/Article/details/gtfduvnpyc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.chenlongwang.top/Article/details/gtsiuviuea.html

Ruby: -> { puts "run" }.call
来源：http://dali.guowangkeji.top/Article/details/gtagscwsev.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jinqigfzy.top/Article/details/gtpboiiwis.html

[C13] 类型声明 / 类型注解
来源：http://dali.jinghuilouyu.cn/Article/details/gtomoolung.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.andypj.xyz/Article/details/gtfjzqbhey.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gotoacloud.top/Article/details/gthwyjkkwh.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.tian-w.cn/Article/details/gtatohlord.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gtvqrusbii.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtwrbgcaeb.html

Go:   func add(a, b int) int
来源：http://dali.jiagoushi.top/Article/details/gtsgdvnebq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.daxiang520.top/Article/details/gtrsmgbznq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtswqyzjma.html

[C14] 泛型函数
来源：http://dali.aizwys.cn/Article/details/gtdcyczpky.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.wangdashe.top/Article/details/gtzhlrrpys.html

PHP:  // 无泛型
来源：http://dali.zhongyouzk.top/Article/details/gtkzoumejg.html

JS:   // 无泛型
来源：http://dali.zdqjudy.top/Article/details/gtfqeqcgvb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.fengsongda.top/Article/details/gtmskbfzrs.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xylfe.cn/Article/details/gthvpknccq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhixingplan.top/Article/details/gtiwnhujtc.html

Ruby: # 无泛型
来源：http://dali.tianlin.xyz/Article/details/gtrbqqjlor.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.daxiang520.top/Article/details/gtvqxkngdf.html

[C15] 解构 / 展开参数
来源：http://dali.chenjidiqi.icu/Article/details/gtrvpoxmdd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.nwbrower.top/Article/details/gtwakjbppw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hysaishi.cn/Article/details/gtpipzosme.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.dianchejie.cn/Article/details/gtspqvzjxt.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yueranfly.top/Article/details/gtzdmlajqf.html

Java: // 无解构
来源：http://dali.birdmap.top/Article/details/gtlmnqlira.html

Go:   // 无解构
来源：http://dali.cqqwz.cn/Article/details/gthvowuiou.html

Ruby: a, b = pair
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlbdpucjl.html

C#:   var (a, b) = pair;
来源：http://dali.cucudq.cn/Article/details/gtfuerdkpj.html

[C16] 函数 / 方法重载
来源：http://dali.yj202588.top/Article/details/gtjthzlhzl.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.chenjidiqi.icu/Article/details/gtflmliszf.html

PHP:  // 无重载
来源：http://dali.nanxuanxn.top/Article/details/gtsdfcaiqa.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.chenlongwang.top/Article/details/gticriqpdr.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxqaocmbz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.tianlin.xyz/Article/details/gthjwqtddf.html

Go:   // 无重载：用不同函数名
来源：http://dali.gaohongyu789.top/Article/details/gtfdvfjhcu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.bjfxy.top/Article/details/gtmuwebtkb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.tianlin.xyz/Article/details/gtluoigfsj.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtgbbevxcu.html

D. 数组 / 列表 / 集合
来源：http://dali.guannengcc.top/Article/details/gtbjnlhage.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtoxrcjrnj.html

[D01] 创建数组 / 列表
来源：http://dali.sysykeji.top/Article/details/gtffxtxzls.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xylfe.cn/Article/details/gthoussrux.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ehwqpu.com/Article/details/gtxylxxudw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.redwolf501.top/Article/details/gtrvrozcte.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.sufxvd.cn/Article/details/gtpextzezg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.iojbl.cn/Article/details/gtxdickqtm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.tanke756.top/Article/details/gtbwodrjlf.html

Ruby: arr = [1, 2, 3]
来源：http://dali.wangshuangyany.cn/Article/details/gtwlnhulwg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinyuanbaomall.cn/Article/details/gttsswflmx.html

[D02] 追加元素到末尾
来源：http://dali.gaohongyu789.top/Article/details/gthkgnuvre.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xuanzx.com/Article/details/gtxkqnyjaf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.vqdsnc.cn/Article/details/gtpzkhqkgv.html

JS:   arr.push(4);
来源：http://dali.yj202588.top/Article/details/gtdoscpnyw.html

TS:   arr.push(4);
来源：http://dali.xuanzx.com/Article/details/gtoognsjcm.html

Java: list.add(4);
来源：http://dali.hywenlv.cn/Article/details/gtzavmjhqa.html

Go:   arr = append(arr, 4)
来源：http://dali.svipenyu.cn/Article/details/gtoftwzrim.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.dashuyun.cn/Article/details/gtcbylbptv.html

C#:   list.Add(4);
来源：http://dali.jqgufenzy.top/Article/details/gtpasnnxki.html

[D03] 在指定位置插入元素
来源：http://dali.316326.xyz/Article/details/gtgjqseduj.html

Py:   arr.insert(0, 0)
来源：http://dali.havefunace.top/Article/details/gtfozbmtot.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jyoumei.cn/Article/details/gtzqkzmtdy.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hnxiangtu.top/Article/details/gtkfjuiexi.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zdqjudy.top/Article/details/gtzntllmfe.html

Java: list.add(0, 0);
来源：http://dali.jlsjyb.cn/Article/details/gtynkwqnrq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sysykeji.top/Article/details/gtkanczvej.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhiwuduotai.top/Article/details/gtafcgfers.html

C#:   list.Insert(0, 0);
来源：http://dali.cqqwz.cn/Article/details/gtzuxludwp.html

[D04] 删除元素
来源：http://dali.hongshengwenyu.top/Article/details/gtozyebnno.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yuxming.cn/Article/details/gtccbodvmk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtpmldpayi.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gotoacloud.top/Article/details/gtujcfdomu.html

TS:   arr.splice(0, 1);
来源：http://dali.zhoulong.xyz/Article/details/gtxcmuifia.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yongpay.top/Article/details/gtwejnrvhs.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zycfv.cn/Article/details/gtjnqgolac.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.pycfn.com/Article/details/gttgnyxtkn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hnxiangtu.top/Article/details/gtwacyhpwx.html

[D05] 访问与修改元素
来源：http://dali.dashuyun.cn/Article/details/gtjqfjpcuc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yangfankeji.com/Article/details/gtorwauimx.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shuidangran.top/Article/details/gtznbnbviy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zycfv.cn/Article/details/gtdtbyylzt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yueranfly.top/Article/details/gtvyowmuak.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.daria6918.cn/Article/details/gtowhkobeg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yvedp.cn/Article/details/gtkgjrrxai.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhengqikj.top/Article/details/gtmuuefxiw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhongyouzk.top/Article/details/gtwvecaeyt.html

[D06] 数组长度
来源：http://dali.jinqigufen.top/Article/details/gtgwuzpmqi.html

Py:   len(arr)
来源：http://dali.aizwys.cn/Article/details/gtbrljgkag.html

PHP:  count($arr);
来源：http://dali.daria6918.cn/Article/details/gtkeloiewc.html

JS:   arr.length
来源：http://dali.sweek.top/Article/details/gtqzrodasi.html

TS:   arr.length
来源：http://dali.svipenyu.cn/Article/details/gtnzkqwtaa.html

Java: list.size();
来源：http://dali.zhoulong.xyz/Article/details/gtymzaphcp.html

Go:   len(arr)
来源：http://dali.fzhhl.top/Article/details/gtxokeqida.html

Ruby: arr.length; arr.size
来源：http://dali.yuanzhike.top/Article/details/gtuwvqcdxk.html

C#:   list.Count;
来源：http://dali.andypj.xyz/Article/details/gtbhbqmpqh.html

[D07] 切片 / 取子数组
来源：http://dali.ppjwa.cn/Article/details/gtmknrwbea.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.wangdashe.top/Article/details/gtknqapbya.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ppjwa.cn/Article/details/gtbrojyccr.html

JS:   arr.slice(1, 4);
来源：http://dali.cashguo.top/Article/details/gtdqpjweby.html

TS:   arr.slice(1, 4);
来源：http://dali.guowangkeji.top/Article/details/gtrolqwwgm.html

Java: list.subList(1, 4);
来源：http://dali.xziqi.cn/Article/details/gttwwkjwdu.html

Go:   arr[1:4]
来源：http://dali.dianchejie.cn/Article/details/gtnwztmflm.html

Ruby: arr[1, 3]
来源：http://dali.xinyue.icu/Article/details/gtavnduldh.html

C#:   list.GetRange(1, 3);
来源：http://dali.ydzc1.top/Article/details/gtufkzufvg.html

[D08] 合并两个数组
来源：http://dali.yvedp.cn/Article/details/gtmmbmzpei.html

Py:   a + b;  a.extend(b)
来源：http://dali.quarkkingdee.top/Article/details/gtefmhufxt.html

PHP:  array_merge($a, $b);
来源：http://dali.sweek.top/Article/details/gtuwazkhem.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.dashuyun.cn/Article/details/gtiydjgexe.html

TS:   [...a, ...b];
来源：http://dali.guannengcc.top/Article/details/gtysysmazr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ivvv.top/Article/details/gtmkbdnmmi.html

Go:   append(a, b...)
来源：http://dali.snrcjt.cn/Article/details/gthifhnjkl.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ydzc1.top/Article/details/gtfkezhajj.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhengqikj.top/Article/details/gtvunvncas.html

[D09] 排序（升序）
来源：http://dali.wangshuangyany.cn/Article/details/gtfvckszll.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pengpengdd.cyou/Article/details/gtxlywdxsm.html

PHP:  sort($arr);
来源：http://dali.ppjwa.cn/Article/details/gtbetlcyij.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ydzc1.top/Article/details/gtphpadkdo.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hysaishi.cn/Article/details/gtcwssmxhf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hnqzz.top/Article/details/gtsbqvsckg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ehwqpu.com/Article/details/gtkpshhave.html

Ruby: arr.sort
来源：http://dali.smart0.xyz/Article/details/gtewcfvsys.html

C#:   list.Sort();
来源：http://dali.ydzc1.top/Article/details/gtbromxtnw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.andypj.xyz/Article/details/gthntvyglh.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.wangshuangyany.cn/Article/details/gtozafdkhi.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.snrcjt.cn/Article/details/gtgwldpldl.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.havefunace.top/Article/details/gtbmghtdvp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gogol.net.cn/Article/details/gtoruznmgn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.dashuyun.cn/Article/details/gtnjvowahy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.iojbl.cn/Article/details/gtoanlerho.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hongshengwenyu.top/Article/details/gtulzeezsp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shangyingyoupin.top/Article/details/gtjeihirtn.html

[D11] 反转数组
来源：http://dali.jqgfzy.top/Article/details/gtscczqmxb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.dianchejie.cn/Article/details/gtxswywrvz.html

PHP:  array_reverse($arr);
来源：http://dali.zhixingplan.top/Article/details/gtoerphuaf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.daria6918.cn/Article/details/gtahvxuqzs.html

TS:   [...arr].reverse();
来源：http://dali.svipenyu.cn/Article/details/gtfvknpqqx.html

Java: Collections.reverse(list);
来源：http://dali.yuanzhike.top/Article/details/gtcmpkvlzc.html

Go:   slices.Reverse(arr)
来源：http://dali.sxryk.cn/Article/details/gtrtykbiox.html

Ruby: arr.reverse
来源：http://dali.yj20258.top/Article/details/gtmxznnpdt.html


<!-- 参考信息 -->