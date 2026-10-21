代发 wailian999

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jinqigfzy.top/Article/details/gtqurrlvdw.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yuxming.cn/Article/details/gtkpcpbfqh.html

[B11] 生成数字序列 / 区间
来源：http://dali.hfpthk.cn/Article/details/gtpyqinirx.html

Py:   list(range(0, 10, 2))
来源：http://dali.sufxvd.cn/Article/details/gtldupicuu.html

PHP:  range(0, 10, 2);
来源：http://dali.chenzaomai.com/Article/details/gtaeclksze.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yuxming.cn/Article/details/gtolsibbbl.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.smart0.xyz/Article/details/gtkdcykjue.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.xylfe.cn/Article/details/gtfbtjjccv.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhiwuduotai.top/Article/details/gtyppvytkg.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zdqjudy.top/Article/details/gtkhezcsol.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.guannengcc.top/Article/details/gtjjnseors.html

[B12] 跳出多层循环
来源：http://dali.smart0.xyz/Article/details/gtqwyzprlk.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.fengsongda.top/Article/details/gthpshxpnd.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hnxiangtu.top/Article/details/gtyxparbfk.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.guowangkeji.top/Article/details/gtwhnmxxuk.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hammf.cn/Article/details/gthvcebtxh.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ehwqpu.com/Article/details/gtzqnyaffk.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ydzc1.top/Article/details/gtcrslgwht.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yj202588.top/Article/details/gtisqizvog.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jinqigufen.top/Article/details/gtlgbbvnnv.html

[B13] 判断是否为数字
来源：http://dali.jyoumei.cn/Article/details/gtuxedwiyt.html

Py:   isinstance(x, (int, float))
来源：http://dali.feifeiyinyue.top/Article/details/gtsvemguoa.html

PHP:  is_numeric($x)
来源：http://dali.hysaishi.cn/Article/details/gtjhxalaex.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shuidangran.top/Article/details/gthstipkfw.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhongyouzk.top/Article/details/gtauqxgxpq.html

Java: x instanceof Number
来源：http://dali.havefunace.top/Article/details/gtjztzrhor.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhiwuduotai.top/Article/details/gtlsdavmhs.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yj20258888.top/Article/details/gtdohwnigq.html

C#:   x is int or double or decimal
来源：http://dali.yj20258.top/Article/details/gtnsqtzwsy.html

[B14] 判断值是否在集合内
来源：http://dali.chenzaomai.com/Article/details/gtfdpirmfe.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.feifeiyinyue.top/Article/details/gtctmivmoo.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yangfankeji.com/Article/details/gtewgffwds.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.nanxuanxn.top/Article/details/gtwzolpvuc.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yongpay.top/Article/details/gtrfikwtky.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.aizwys.cn/Article/details/gtinuiretb.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtdfuryhau.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.0kj1m.cn/Article/details/gtxkjvtijq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gttnsqjwll.html

[B15] 布尔运算与取反
来源：http://dali.yvedp.cn/Article/details/gtxiewyhcn.html

Py:   a and b or not c
来源：http://dali.shanyushiyangtech.top/Article/details/gtyzmpywml.html

PHP:  $a && $b || !$c
来源：http://dali.sweek.top/Article/details/gtbksguhjb.html

JS:   a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gtdvtoqrqi.html

TS:   a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gtiylhzlaf.html

Java: a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gtsdklwfdg.html

Go:   a && b || !c
来源：http://dali.xinyue.icu/Article/details/gtywvrrkgr.html

Ruby: a && b || !c
来源：http://dali.daria6918.cn/Article/details/gtokmeopsy.html

C#:   a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gtcxomfxmy.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jinqigufen.top/Article/details/gtfxswgorh.html

Py:   if not data: return
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkxupscsq.html

PHP:  if (!$data) { return; }
来源：http://dali.hfpthk.cn/Article/details/gtruhjdsqr.html

JS:   if (!data) return;
来源：http://dali.0kj1m.cn/Article/details/gthjmdsful.html

TS:   if (!data) return;
来源：http://dali.guannengcc.top/Article/details/gtiormigqj.html

Java: if (data == null) return;
来源：http://dali.zhoulong.xyz/Article/details/gtzprzwcia.html

Go:   if data == nil { return }
来源：http://dali.gogol.net.cn/Article/details/gtzpxjrxku.html

Ruby: return if data.nil?
来源：http://dali.ehwqpu.com/Article/details/gtdmzfksgi.html

C#:   if (data == null) return;
来源：http://dali.jinghuilouyu.cn/Article/details/gtrqsyazie.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gthmdxtfoy.html

C. 函数与作用域
来源：http://dali.ppjwa.cn/Article/details/gtlrbcwsuk.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtydfycprl.html

[C01] 定义函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrwefgjps.html

Py:   def add(a, b): return a + b
来源：http://dali.xuetiantiany.cn/Article/details/gtxbgmmrvv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgufenzy.top/Article/details/gtvfdegkti.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gtttfqjzyc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gtckberhnc.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hammf.cn/Article/details/gthdyzhlxa.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.gotoacloud.top/Article/details/gtqzldqzfo.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cqqwz.cn/Article/details/gtctqdntit.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gtwmzjjuhe.html

[C02] 默认参数
来源：http://dali.vqdsnc.cn/Article/details/gtkaeqmrop.html

Py:   def greet(name="World"): return name
来源：http://dali.yueranfly.top/Article/details/gtambfllfn.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtsvtzhlxa.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.smart0.xyz/Article/details/gtgesqhjiu.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gtdnbriddl.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hnqzz.top/Article/details/gtgrjeqgby.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shangyingyoupin.top/Article/details/gttjpjyoqa.html

Ruby: def greet(name = "World") = name
来源：http://dali.yj20258.top/Article/details/gtiocsdkdo.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhixingplan.top/Article/details/gtbpqizovi.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gtmlohwdpm.html

Py:   def total(*args): return sum(args)
来源：http://dali.shuidangran.top/Article/details/gtxzcxhdwe.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhiwuduotai.top/Article/details/gthbjoeqot.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.guannengcc.top/Article/details/gtdkaepamz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hammf.cn/Article/details/gtgnticcdu.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.c1oappe.top/Article/details/gtpgxsmjxb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.gzhubu.top/Article/details/gtwjgrudyz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hywenlv.cn/Article/details/gtklzawgpz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shanyushiyangtech.top/Article/details/gtwwgrkfbi.html

[C04] 命名参数 / 关键字参数
来源：http://dali.haohaochexian.top/Article/details/gtcquszbcg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.daria6918.cn/Article/details/gtvrlnvabq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhiwuduotai.top/Article/details/gtjzvmuabs.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jianghu66.top/Article/details/gtozpvomqs.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.aizwys.cn/Article/details/gtjcdhwnsg.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.dashuyun.cn/Article/details/gtejnosnnt.html

Go:   // 无：用配置结构体参数
来源：http://dali.gzhubu.top/Article/details/gtuemsdjln.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jqgfzy.top/Article/details/gtqfepahcx.html

C#:   f(a: 1, b: 2)
来源：http://dali.fengsongda.top/Article/details/gtmioeqkql.html

[C05] 返回多个值
来源：http://dali.guannengcc.top/Article/details/gtqlrilqoc.html

Py:   return a, b
来源：http://dali.yj202588.top/Article/details/gtnhkrcjba.html

PHP:  return [$a, $b];
来源：http://dali.tanke756.top/Article/details/gtazwkuwot.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.birdmap.top/Article/details/gtwnfsctub.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gttjzmdobe.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yuxming.cn/Article/details/gtogfpxrke.html

Go:   return a, b
来源：http://dali.jinqigfzy.top/Article/details/gtyxbndhis.html

Ruby: return a, b
来源：http://dali.gotoacloud.top/Article/details/gtfyyagrvb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ybcxt.top/Article/details/gtqizpfazh.html

[C06] 匿名函数 / lambda
来源：http://dali.kuanghao11.cn/Article/details/gtcfolypjy.html

Py:   square = lambda x: x * x
来源：http://dali.gotoacloud.top/Article/details/gtqrmccqbk.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hfpthk.cn/Article/details/gtbtbhvmze.html

JS:   const square = x => x * x;
来源：http://dali.fengsongda.top/Article/details/gtvzvwkwyn.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yanxiufei.cn/Article/details/gtytdoglqt.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zycfv.cn/Article/details/gtyiwgvpys.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shangyingyoupin.top/Article/details/gtvvpgdfdh.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjirvpsfk.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.aibaodan.cn/Article/details/gtddlbdrtw.html

[C07] 把函数作为参数传入
来源：http://dali.yongpay.top/Article/details/gtfofdygfm.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hywenlv.cn/Article/details/gtprccgvnn.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.gzhubu.top/Article/details/gtfsjctgbb.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhoulong.xyz/Article/details/gtwbnjbraf.html

TS:   arr.map(String)
来源：http://dali.gaohongyu789.top/Article/details/gtwngqkwbu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jqgufenzy.top/Article/details/gtpqmslzva.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.sufxvd.cn/Article/details/gtjlejxrgl.html

Ruby: arr.map(&:upcase)
来源：http://dali.hywenlv.cn/Article/details/gtuiyphlpq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hfpthk.cn/Article/details/gtembwljxb.html

[C08] 闭包
来源：http://dali.ivvv.top/Article/details/gtbpapvoru.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.guowangkeji.top/Article/details/gtpedqtcbn.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.dianchejie.cn/Article/details/gtzeagpfoc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yj202588.top/Article/details/gtqaonnugq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbybvilbt.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.pengpengdd.cyou/Article/details/gthtkehinh.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cheryme.top/Article/details/gtxyqshasw.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xuetiantiany.cn/Article/details/gtgyiukxtb.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yj202588.top/Article/details/gtopqftiim.html

[C09] 递归
来源：http://dali.hywenlv.cn/Article/details/gtkrzisypx.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hnqzz.top/Article/details/gtgdurszxa.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.aibaodan.cn/Article/details/gtdmjjrlaf.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ivvv.top/Article/details/gtlzyezmzy.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjqjnqgoi.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ivvv.top/Article/details/gtxqfxzrfm.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cucudq.cn/Article/details/gtqewzwubw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yvedp.cn/Article/details/gtyaftbsgj.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.wangshuangyany.cn/Article/details/gtuuvtxwgk.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gtynzwylyq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.birdmap.top/Article/details/gtcoarmzvi.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shangyingyoupin.top/Article/details/gtnnimsnbd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.guowangkeji.top/Article/details/gtzxiyvnre.html

TS:   同 JS
来源：http://dali.hywenlv.cn/Article/details/gtzrmtfiqh.html

Java: 方法内为块级作用域
来源：http://dali.cqqwz.cn/Article/details/gtfntcgtsa.html

Go:   花括号块级作用域
来源：http://dali.yanxiufei.cn/Article/details/gtimaocmhw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yuxming.cn/Article/details/gtoagwoyrj.html

C#:   块级作用域
来源：http://dali.vqdsnc.cn/Article/details/gtmpuhascr.html

[C11] 模块导入与导出
来源：http://dali.cashguo.top/Article/details/gtkcavrljl.html

Py:   from module import func
来源：http://dali.yueranfly.top/Article/details/gtivjcloqh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.tian-w.cn/Article/details/gtrulbrlzc.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinqigfzy.top/Article/details/gtjuwwfnsy.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.gaohongyu789.top/Article/details/gtqnywmtab.html

Java: import java.util.List;
来源：http://dali.zdqjudy.top/Article/details/gtmpoapbgo.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.guannengcc.top/Article/details/gtfcflvhew.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzhtuurrw.html

C#:   using System.Text;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyrjtozkb.html

[C12] 立即执行函数 IIFE
来源：http://dali.aibaodan.cn/Article/details/gtkqwfrppl.html

Py:   (lambda: print("run"))()
来源：http://dali.xuanzx.com/Article/details/gtsesjxbfy.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtijttbhtb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhengqikj.top/Article/details/gtlcmcekeo.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yj202588.top/Article/details/gtzjxkswqw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yuanzhike.top/Article/details/gtbildmwni.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gogol.net.cn/Article/details/gttcrbrjmm.html

Ruby: -> { puts "run" }.call
来源：http://dali.9152youxi.cn/Article/details/gtmietyugh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.pengpengdd.cyou/Article/details/gtjcgxwual.html

[C13] 类型声明 / 类型注解
来源：http://dali.316326.xyz/Article/details/gtnyzklldu.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yuxming.cn/Article/details/gtcigwilya.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gaohongyu789.top/Article/details/gtapvkmqgl.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.dashuyun.cn/Article/details/gthmftyjsk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gtmccnzkol.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gttyoxbxuz.html

Go:   func add(a, b int) int
来源：http://dali.hysaishi.cn/Article/details/gtrxkxzmoo.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hongshengwenyu.top/Article/details/gteavmxnjc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ivvv.top/Article/details/gtgyeezfse.html

[C14] 泛型函数
来源：http://dali.yongpay.top/Article/details/gtcvopsrxb.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jlsjyb.cn/Article/details/gtwhnhbluo.html

PHP:  // 无泛型
来源：http://dali.andypj.xyz/Article/details/gtszboszru.html

JS:   // 无泛型
来源：http://dali.aizwys.cn/Article/details/gtrxniattg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.pycfn.com/Article/details/gtfgaaaosd.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.svipenyu.cn/Article/details/gtcrbrjlko.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.guowangkeji.top/Article/details/gtdyxmmafm.html

Ruby: # 无泛型
来源：http://dali.daria6918.cn/Article/details/gtovopxrqa.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.andypj.xyz/Article/details/gtryagnaya.html

[C15] 解构 / 展开参数
来源：http://dali.jinqigufen.top/Article/details/gtfqjcqsba.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gaohongyu789.top/Article/details/gtlkpbxhfd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.feifeiyinyue.top/Article/details/gtswdurtac.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.dashuyun.cn/Article/details/gtpwhuxocn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqefvqdln.html

Java: // 无解构
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvbgzbeyo.html

Go:   // 无解构
来源：http://dali.xuetiantiany.cn/Article/details/gtchymcvij.html

Ruby: a, b = pair
来源：http://dali.andypj.xyz/Article/details/gtxwnqtdis.html

C#:   var (a, b) = pair;
来源：http://dali.yvedp.cn/Article/details/gtrdsskfzo.html

[C16] 函数 / 方法重载
来源：http://dali.birdmap.top/Article/details/gtoxdkmnxb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.gaohongyu789.top/Article/details/gtauxhqcvs.html

PHP:  // 无重载
来源：http://dali.yuxming.cn/Article/details/gthtyvcbsc.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.c1oappe.top/Article/details/gttxfnkvzq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yongpay.top/Article/details/gttlacgzmy.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jiagoushi.top/Article/details/gtwqvvhhct.html

Go:   // 无重载：用不同函数名
来源：http://dali.yuxming.cn/Article/details/gtgrafgtjk.html

Ruby: # 无重载：靠动态参数
来源：http://dali.dianchejie.cn/Article/details/gtsbiwbhwc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yonumen.top/Article/details/gtcyuheuiv.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtfihoaupv.html

D. 数组 / 列表 / 集合
来源：http://dali.nwbrower.top/Article/details/gtbktedxfl.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtsfstuiov.html

[D01] 创建数组 / 列表
来源：http://dali.yongpay.top/Article/details/gtejwrcnfg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.tianlin.xyz/Article/details/gtpdhlljxk.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.havefunace.top/Article/details/gtisfnuwco.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gotoacloud.top/Article/details/gtmsrlmibv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.316326.xyz/Article/details/gtbxuoofsj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.fzhhl.top/Article/details/gthewtyufy.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.haohaochexian.top/Article/details/gttqgkcqaj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.andypj.xyz/Article/details/gtkrchqhnf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.fengsongda.top/Article/details/gtkpnbajmj.html

[D02] 追加元素到末尾
来源：http://dali.daxiang520.top/Article/details/gtbvbgbnif.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.svipenyu.cn/Article/details/gtdlioatpp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jqgfzy.top/Article/details/gtazanfleu.html

JS:   arr.push(4);
来源：http://dali.hnqzz.top/Article/details/gtvdjgplon.html

TS:   arr.push(4);
来源：http://dali.hfpthk.cn/Article/details/gtqepynfuf.html

Java: list.add(4);
来源：http://dali.cdnleiting.top/Article/details/gtsoagcvxy.html

Go:   arr = append(arr, 4)
来源：http://dali.tianlin.xyz/Article/details/gtdhghvxod.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.chenzaomai.com/Article/details/gtyqvbvnol.html

C#:   list.Add(4);
来源：http://dali.yvedp.cn/Article/details/gtmibrmygq.html

[D03] 在指定位置插入元素
来源：http://dali.cheryme.top/Article/details/gthdlavhwa.html

Py:   arr.insert(0, 0)
来源：http://dali.fzhhl.top/Article/details/gtpgeadfhm.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtabgupcmj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shangyingyoupin.top/Article/details/gtffbnsyyd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yuanzhike.top/Article/details/gtctlvykqu.html

Java: list.add(0, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpkrncizq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jianghu66.top/Article/details/gtouexvfkf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jqgufenzy.top/Article/details/gtjlkinref.html

C#:   list.Insert(0, 0);
来源：http://dali.jqgufenzy.top/Article/details/gtbeaotjfv.html

[D04] 删除元素
来源：http://dali.daxiang520.top/Article/details/gthqepzxbu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.aibaodan.cn/Article/details/gtkwppdzqo.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtytsdojgr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.vqdsnc.cn/Article/details/gtqkocznih.html

TS:   arr.splice(0, 1);
来源：http://dali.gogol.net.cn/Article/details/gtolgiztzb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.andypj.xyz/Article/details/gtmxabgfei.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.feifeiyinyue.top/Article/details/gtjxwotimr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.quarkkingdee.top/Article/details/gtelnxesgh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.haohaochexian.top/Article/details/gtdvgiqpjc.html

[D05] 访问与修改元素
来源：http://dali.xinyue.icu/Article/details/gtzviakgst.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nwbrower.top/Article/details/gtjztjjrmn.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gtzdkrajcs.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.c1oappe.top/Article/details/gtkwzkzewl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xuanzx.com/Article/details/gtklxuldjr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhiwuduotai.top/Article/details/gtfwfaufjm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yvedp.cn/Article/details/gtuoaldwpw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.9152youxi.cn/Article/details/gthrjkenga.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.meibo888.top/Article/details/gtagjxqryf.html

[D06] 数组长度
来源：http://dali.ivvv.top/Article/details/gtzecahnrs.html

Py:   len(arr)
来源：http://dali.yongpay.top/Article/details/gtmiymcybw.html

PHP:  count($arr);
来源：http://dali.mhx1999.top/Article/details/gtucrmjlhz.html

JS:   arr.length
来源：http://dali.andypj.xyz/Article/details/gtrizlhlkk.html

TS:   arr.length
来源：http://dali.fzhhl.top/Article/details/gtbxwxuklp.html

Java: list.size();
来源：http://dali.9152youxi.cn/Article/details/gtwvurhwxc.html

Go:   len(arr)
来源：http://dali.tanke756.top/Article/details/gtqwrrlhcl.html

Ruby: arr.length; arr.size
来源：http://dali.jiagoushi.top/Article/details/gtaonxooyi.html

C#:   list.Count;
来源：http://dali.shanyushiyangtech.top/Article/details/gtpgkidxcj.html

[D07] 切片 / 取子数组
来源：http://dali.xuanzx.com/Article/details/gtjypvaqrr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.snrcjt.cn/Article/details/gtnndmfucy.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yuanzhike.top/Article/details/gtezxugkvp.html

JS:   arr.slice(1, 4);
来源：http://dali.jlsjyb.cn/Article/details/gtzvvkaqaa.html

TS:   arr.slice(1, 4);
来源：http://dali.tian-w.cn/Article/details/gtdzknsqrc.html

Java: list.subList(1, 4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtayodqjsf.html

Go:   arr[1:4]
来源：http://dali.shangyingyoupin.top/Article/details/gteykisgte.html

Ruby: arr[1, 3]
来源：http://dali.gaohongyu789.top/Article/details/gtcxlytaef.html

C#:   list.GetRange(1, 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtztnkrezp.html

[D08] 合并两个数组
来源：http://dali.gaohongyu789.top/Article/details/gtbdodiiyy.html

Py:   a + b;  a.extend(b)
来源：http://dali.tian-w.cn/Article/details/gtrnillysc.html

PHP:  array_merge($a, $b);
来源：http://dali.ivvv.top/Article/details/gtprtxxszb.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.kuanghao11.cn/Article/details/gtshqvibex.html

TS:   [...a, ...b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtppuqxsdl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jianghu66.top/Article/details/gtdsjfhyqq.html

Go:   append(a, b...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsftthrkj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sysykeji.top/Article/details/gtlnlzyfgg.html

C#:   a.Concat(b).ToList()
来源：http://dali.ppjwa.cn/Article/details/gtkzyfachw.html

[D09] 排序（升序）
来源：http://dali.xinyue.icu/Article/details/gtfufaiozm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aibaodan.cn/Article/details/gtydaqguhy.html

PHP:  sort($arr);
来源：http://dali.shuidangran.top/Article/details/gtgvmnnhzt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.aibaodan.cn/Article/details/gtxvtaiedh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhongyouzk.top/Article/details/gtjkkxtdzx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.svipenyu.cn/Article/details/gtlymihszi.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.sufxvd.cn/Article/details/gtthjfxmwj.html

Ruby: arr.sort
来源：http://dali.yanxiufei.cn/Article/details/gtbyrmbyic.html

C#:   list.Sort();
来源：http://dali.cheryme.top/Article/details/gtsrfselvx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.haohaochexian.top/Article/details/gtfrjrrlmz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.9152youxi.cn/Article/details/gtyjnoazsh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.snrcjt.cn/Article/details/gtymhbdyed.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.mhx1999.top/Article/details/gtckxdhrjn.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guowangkeji.top/Article/details/gtxbdibihm.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zdqjudy.top/Article/details/gtouhijnqy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xuanzx.com/Article/details/gtzfzcxjbd.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.smart0.xyz/Article/details/gtttpjacen.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.pengpengdd.cyou/Article/details/gtygtdsvol.html

[D11] 反转数组
来源：http://dali.pengpengdd.cyou/Article/details/gtzkxysgpo.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwmgtxrhd.html

PHP:  array_reverse($arr);
来源：http://dali.tanke756.top/Article/details/gtdlufdgnj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.daria6918.cn/Article/details/gttlcwwltz.html


<!-- 参考信息 -->