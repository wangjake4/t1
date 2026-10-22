代发 wailian999

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yueranfly.top/Article/details/gt2mhhfxunc.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.sysykeji.top/Article/details/gt2trykafwv.html

[B11] 生成数字序列 / 区间
来源：http://dali.chenjidiqi.icu/Article/details/gt2qjsyiuwx.html

Py:   list(range(0, 10, 2))
来源：http://dali.chenzaomai.com/Article/details/gt2kjkrvymk.html

PHP:  range(0, 10, 2);
来源：http://dali.cashguo.top/Article/details/gt2czzfsaqz.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yangfankeji.com/Article/details/gt2ojbpgvlw.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gotoacloud.top/Article/details/gt2cmoycrej.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.daria6918.cn/Article/details/gt2wpupjahl.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.sweek.top/Article/details/gt2xxrtihgr.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xuetiantiany.cn/Article/details/gt2gurshcwf.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.andypj.xyz/Article/details/gt2jxdqisin.html

[B12] 跳出多层循环
来源：http://dali.shzxlz.cn/Article/details/gt2ysbzbbbn.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jlsjyb.cn/Article/details/gt2vsdytrjz.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.daxiang520.top/Article/details/gt2mzkfmiqm.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xuetiantiany.cn/Article/details/gt2szzqfuby.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.daxiang520.top/Article/details/gt2lvtxkvkb.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vycvhgah.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zdqjudy.top/Article/details/gt2ybtgggrj.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2rbehkwei.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.feifeiyinyue.top/Article/details/gt2bdwawvsv.html

[B13] 判断是否为数字
来源：http://dali.tanke756.top/Article/details/gt2zuslzkfz.html

Py:   isinstance(x, (int, float))
来源：http://dali.nanxuanxn.top/Article/details/gt2zyjqtskd.html

PHP:  is_numeric($x)
来源：http://dali.guannengcc.top/Article/details/gt2zrgjilay.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dggaychp.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eurrpgsd.html

Java: x instanceof Number
来源：http://dali.andypj.xyz/Article/details/gt2yyshttnc.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.gzhubu.top/Article/details/gt2gzqwssnh.html

Ruby: x.is_a?(Numeric)
来源：http://dali.svipenyu.cn/Article/details/gt2budtvfio.html

C#:   x is int or double or decimal
来源：http://dali.yvedp.cn/Article/details/gt2fdcgxwnv.html

[B14] 判断值是否在集合内
来源：http://dali.birdmap.top/Article/details/gt2oflxadfb.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.sysykeji.top/Article/details/gt2bcqlctfi.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.gogol.net.cn/Article/details/gt2ilhfibev.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ladgvjcq.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ppjwa.cn/Article/details/gt2vpdgcaej.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yuxming.cn/Article/details/gt2qjgqcudb.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.c1oappe.top/Article/details/gt2jjofvsoe.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.aizwys.cn/Article/details/gt2rlxowneb.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ehwqpu.com/Article/details/gt2rkovfwhn.html

[B15] 布尔运算与取反
来源：http://dali.ivvv.top/Article/details/gt2sdfmvjyk.html

Py:   a and b or not c
来源：http://dali.vqdsnc.cn/Article/details/gt2dvptqxyh.html

PHP:  $a && $b || !$c
来源：http://dali.cqqwz.cn/Article/details/gt2pjlqielj.html

JS:   a && b || !c
来源：http://dali.tian-w.cn/Article/details/gt2yggiyslm.html

TS:   a && b || !c
来源：http://dali.zycfv.cn/Article/details/gt2jxhncyuq.html

Java: a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gt2wzkfnubp.html

Go:   a && b || !c
来源：http://dali.daxiang520.top/Article/details/gt2lvompqbg.html

Ruby: a && b || !c
来源：http://dali.tian-w.cn/Article/details/gt2wczueqlo.html

C#:   a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gt2ctowvfgm.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yuanzhike.top/Article/details/gt2wdgguceu.html

Py:   if not data: return
来源：http://dali.iojbl.cn/Article/details/gt2angywxzz.html

PHP:  if (!$data) { return; }
来源：http://dali.yonumen.top/Article/details/gt2rsjkhvop.html

JS:   if (!data) return;
来源：http://dali.xinyue.icu/Article/details/gt2rxhohdly.html

TS:   if (!data) return;
来源：http://dali.yongpay.top/Article/details/gt2nsrliffc.html

Java: if (data == null) return;
来源：http://dali.birdmap.top/Article/details/gt2suxqutps.html

Go:   if data == nil { return }
来源：http://dali.cheryme.top/Article/details/gt2tlaknqhv.html

Ruby: return if data.nil?
来源：http://dali.guowangkeji.top/Article/details/gt2gkwvtuxp.html

C#:   if (data == null) return;
来源：http://dali.9152youxi.cn/Article/details/gt2lrpkczvx.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2xdcoynsg.html

C. 函数与作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jtxzmyzv.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2sxfjvyxn.html

[C01] 定义函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2tobcdknq.html

Py:   def add(a, b): return a + b
来源：http://dali.jianghu66.top/Article/details/gt2duororvw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.fzhhl.top/Article/details/gt2gbaaeeem.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gt2edvcfezs.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2niqwxaro.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.cashguo.top/Article/details/gt2keouhorv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yanxiufei.cn/Article/details/gt2tlxdiktz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cucudq.cn/Article/details/gt2ffgbhwqy.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gt2ruyomhwn.html

[C02] 默认参数
来源：http://dali.cheryme.top/Article/details/gt2qkykzfsp.html

Py:   def greet(name="World"): return name
来源：http://dali.mhx1999.top/Article/details/gt2ssdmjlnq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hywenlv.cn/Article/details/gt2hxmwtcuz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.c1oappe.top/Article/details/gt2ccrzibqa.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.havefunace.top/Article/details/gt2fhxyleax.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.aizwys.cn/Article/details/gt2jfuydzfq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hnxiangtu.top/Article/details/gt2vvncisfx.html

Ruby: def greet(name = "World") = name
来源：http://dali.chenzaomai.com/Article/details/gt2gppiexwt.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.sweek.top/Article/details/gt2afhmbfgk.html

[C03] 可变参数
来源：http://dali.vqdsnc.cn/Article/details/gt2yumogoip.html

Py:   def total(*args): return sum(args)
来源：http://dali.ppjwa.cn/Article/details/gt2ptdewgmz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.nanxuanxn.top/Article/details/gt2jghvxjcc.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2mglksffe.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gogol.net.cn/Article/details/gt2dfprokzg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhixingplan.top/Article/details/gt2orcerzpw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.gotoacloud.top/Article/details/gt2qtlgobyc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.0kj1m.cn/Article/details/gt2dchdkduc.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xuanzx.com/Article/details/gt2iipnxpgk.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhixingplan.top/Article/details/gt2poswhwal.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yongpay.top/Article/details/gt2ppxunkok.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ydzc1.top/Article/details/gt2hsswjdrb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.birdmap.top/Article/details/gt2jnnvyznj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jlsjyb.cn/Article/details/gt2mlghhvbp.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oqfgkleu.html

Go:   // 无：用配置结构体参数
来源：http://dali.vqdsnc.cn/Article/details/gt2khpcsahp.html

Ruby: f(a: 1, b: 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xlisccif.html

C#:   f(a: 1, b: 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2slkyvvsn.html

[C05] 返回多个值
来源：http://dali.hnxiangtu.top/Article/details/gt2ywasawkn.html

Py:   return a, b
来源：http://dali.guannengcc.top/Article/details/gt2uxkkmjzv.html

PHP:  return [$a, $b];
来源：http://dali.tian-w.cn/Article/details/gt2xrwuxpip.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.dianchejie.cn/Article/details/gt2nqawgkmv.html

TS:   return { a, b };
来源：http://dali.ybcxt.top/Article/details/gt2qrdalmje.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sxryk.cn/Article/details/gt2kjhckslh.html

Go:   return a, b
来源：http://dali.fzhhl.top/Article/details/gt2kwkdwwaf.html

Ruby: return a, b
来源：http://dali.yuanzhike.top/Article/details/gt2hlnqwkwc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.kuanghao11.cn/Article/details/gt2wpgnrrme.html

[C06] 匿名函数 / lambda
来源：http://dali.vqdsnc.cn/Article/details/gt2bnuxgyjv.html

Py:   square = lambda x: x * x
来源：http://dali.tanke756.top/Article/details/gt2vyqydpnj.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yuanzhike.top/Article/details/gt2vtubyqdt.html

JS:   const square = x => x * x;
来源：http://dali.yj20258888.top/Article/details/gt2pptwxgsd.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jinqigfzy.top/Article/details/gt2xoshsyet.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.chenlongwang.top/Article/details/gt2dsepsqoi.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jqgfzy.top/Article/details/gt2qpgnseni.html

Ruby: square = ->(x) { x * x }
来源：http://dali.vqdsnc.cn/Article/details/gt2tovofnnk.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.gzhubu.top/Article/details/gt2oycscggn.html

[C07] 把函数作为参数传入
来源：http://dali.hfpthk.cn/Article/details/gt2ooqukmvy.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.gotoacloud.top/Article/details/gt2hzfazykr.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hjpuzqfv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shzxlz.cn/Article/details/gt2kzxtcrmy.html

TS:   arr.map(String)
来源：http://dali.pycfn.com/Article/details/gt2wjpoysss.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2shaadmym.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hysaishi.cn/Article/details/gt2zqgkoonc.html

Ruby: arr.map(&:upcase)
来源：http://dali.gzhubu.top/Article/details/gt2indypjnw.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.aizwys.cn/Article/details/gt2jrgbfcuy.html

[C08] 闭包
来源：http://dali.meibo888.top/Article/details/gt2enkhynvf.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yvedp.cn/Article/details/gt2zjqjtxxr.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2fgxewvqg.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.c1oappe.top/Article/details/gt2mrccwirk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.snrcjt.cn/Article/details/gt2gxpckjsz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yangfankeji.com/Article/details/gt2gjcgmfgn.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.quarkkingdee.top/Article/details/gt2qfvuyrvq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yanxiufei.cn/Article/details/gt2zsuwwcxe.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yuxming.cn/Article/details/gt2zppaimse.html

[C09] 递归
来源：http://dali.hywenlv.cn/Article/details/gt2kvnuryzj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.redwolf501.top/Article/details/gt2svykiihu.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.havefunace.top/Article/details/gt2piqbyxhl.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgfzy.top/Article/details/gt2bjogmsae.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.haohaochexian.top/Article/details/gt2pdqqybkl.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jianghu66.top/Article/details/gt2mjemunxu.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.nwbrower.top/Article/details/gt2lvenbjmi.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.havefunace.top/Article/details/gt2ckxkpesm.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.svipenyu.cn/Article/details/gt2astinxkj.html

[C10] 变量作用域
来源：http://dali.cucudq.cn/Article/details/gt2mehkzvar.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yonumen.top/Article/details/gt2dlwoqywl.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jqgufenzy.top/Article/details/gt2jdptqpnu.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.kuanghao11.cn/Article/details/gt2aaghlzjr.html

TS:   同 JS
来源：http://dali.snrcjt.cn/Article/details/gt2soscoqyo.html

Java: 方法内为块级作用域
来源：http://dali.vqdsnc.cn/Article/details/gt2nrewmqxt.html

Go:   花括号块级作用域
来源：http://dali.cheryme.top/Article/details/gt2tuqqngwy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cucudq.cn/Article/details/gt2evgsqnmc.html

C#:   块级作用域
来源：http://dali.fengsongda.top/Article/details/gt2oaficjub.html

[C11] 模块导入与导出
来源：http://dali.yuxming.cn/Article/details/gt2rbgccvuy.html

Py:   from module import func
来源：http://dali.zhengqikj.top/Article/details/gt2vepmycyi.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hnxiangtu.top/Article/details/gt2tiefgffo.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhengqikj.top/Article/details/gt2voogczrn.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ppjwa.cn/Article/details/gt2rkejkewa.html

Java: import java.util.List;
来源：http://dali.hnqzz.top/Article/details/gt2lpfgflgq.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hnxiangtu.top/Article/details/gt2jmchjoqr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xziqi.cn/Article/details/gt2xpnczimb.html

C#:   using System.Text;
来源：http://dali.yueranfly.top/Article/details/gt2ufztibgz.html

[C12] 立即执行函数 IIFE
来源：http://dali.cashguo.top/Article/details/gt2qzvmkwuq.html

Py:   (lambda: print("run"))()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lgxjkano.html

PHP:  (function () { echo "run"; })();
来源：http://dali.guannengcc.top/Article/details/gt2retzhmao.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yuanzhike.top/Article/details/gt2ryunatoe.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jqgfzy.top/Article/details/gt2pdbxwbik.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinqigufen.top/Article/details/gt2hntobhlb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gzhubu.top/Article/details/gt2eqpkwsra.html

Ruby: -> { puts "run" }.call
来源：http://dali.yuxming.cn/Article/details/gt2zheyjgar.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hysaishi.cn/Article/details/gt2bcibqdbw.html

[C13] 类型声明 / 类型注解
来源：http://dali.xuetiantiany.cn/Article/details/gt2gaduobki.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.tian-w.cn/Article/details/gt2rmlcucyg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xylfe.cn/Article/details/gt2qeacywje.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jyoumei.cn/Article/details/gt2nqeksxfb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gt2albnvfsf.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gt2ephafufj.html

Go:   func add(a, b int) int
来源：http://dali.jlsjyb.cn/Article/details/gt2aenzsqpk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.chenlongwang.top/Article/details/gt2ljxepzan.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ydzc1.top/Article/details/gt2pwdlqqqp.html

[C14] 泛型函数
来源：http://dali.cdnleiting.top/Article/details/gt2kvzgeern.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jqgfzy.top/Article/details/gt2ftovxvgk.html

PHP:  // 无泛型
来源：http://dali.vqdsnc.cn/Article/details/gt2ymqsxhzb.html

JS:   // 无泛型
来源：http://dali.havefunace.top/Article/details/gt2kozggvhe.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jiagoushi.top/Article/details/gt2tqfvwhxz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ofnvnxxi.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhiwuduotai.top/Article/details/gt2rgkceoou.html

Ruby: # 无泛型
来源：http://dali.yj20258888.top/Article/details/gt2dmmhosvl.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zdqjudy.top/Article/details/gt2baoadobz.html

[C15] 解构 / 展开参数
来源：http://dali.jyoumei.cn/Article/details/gt2ioiouzkm.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.guannengcc.top/Article/details/gt2chpwfqre.html

PHP:  [$a, $b] = $pair;
来源：http://dali.316326.xyz/Article/details/gt2flyofyqu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2okkuuian.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ppjwa.cn/Article/details/gt2hdogqlws.html

Java: // 无解构
来源：http://dali.guowangkeji.top/Article/details/gt2yuqbiafv.html

Go:   // 无解构
来源：http://dali.pengpengdd.cyou/Article/details/gt2wefqakek.html

Ruby: a, b = pair
来源：http://dali.hnqzz.top/Article/details/gt2zhkfcici.html

C#:   var (a, b) = pair;
来源：http://dali.cqqwz.cn/Article/details/gt2ctaesppp.html

[C16] 函数 / 方法重载
来源：http://dali.hongshengwenyu.top/Article/details/gt2xiarifhs.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yuanzhike.top/Article/details/gt2atmrjbmq.html

PHP:  // 无重载
来源：http://dali.iojbl.cn/Article/details/gt2tqjyixtb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.sufxvd.cn/Article/details/gt2hxryxipb.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.pengpengdd.cyou/Article/details/gt2nwjoalzz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.bjfxy.top/Article/details/gt2zpoxgeat.html

Go:   // 无重载：用不同函数名
来源：http://dali.jqgufenzy.top/Article/details/gt2txbqrpup.html

Ruby: # 无重载：靠动态参数
来源：http://dali.nwbrower.top/Article/details/gt2vdvfchym.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cashguo.top/Article/details/gt2hhxeerwj.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2qiblmfmf.html

D. 数组 / 列表 / 集合
来源：http://dali.daxiang520.top/Article/details/gt2wejnjdkl.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2wijnmwnu.html

[D01] 创建数组 / 列表
来源：http://dali.zhengqikj.top/Article/details/gt2kjjnpxgd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sysykeji.top/Article/details/gt2ttxxduzn.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jqgufenzy.top/Article/details/gt2ivmdjfia.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pglkiaoa.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cucudq.cn/Article/details/gt2ssxdhylv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.sysykeji.top/Article/details/gt2rcczhqxb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cucudq.cn/Article/details/gt2xtxhqltv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sxryk.cn/Article/details/gt2pwwghnht.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cqqwz.cn/Article/details/gt2dhierver.html

[D02] 追加元素到末尾
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uslbmkfe.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xziqi.cn/Article/details/gt2iyepkyfm.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.nanxinkj.top/Article/details/gt2xsndqfxq.html

JS:   arr.push(4);
来源：http://dali.hnxiangtu.top/Article/details/gt2fpntdggk.html

TS:   arr.push(4);
来源：http://dali.hnqzz.top/Article/details/gt2goropsym.html

Java: list.add(4);
来源：http://dali.sxryk.cn/Article/details/gt2ndrsipbd.html

Go:   arr = append(arr, 4)
来源：http://dali.jiagoushi.top/Article/details/gt2xxmyigas.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.tanke756.top/Article/details/gt2kjahxfjt.html

C#:   list.Add(4);
来源：http://dali.jqgufenzy.top/Article/details/gt2wkjudaja.html

[D03] 在指定位置插入元素
来源：http://dali.ivvv.top/Article/details/gt2ieejynwy.html

Py:   arr.insert(0, 0)
来源：http://dali.0kj1m.cn/Article/details/gt2jjvnpidt.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eyponsyq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gogol.net.cn/Article/details/gt2eknhvego.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.birdmap.top/Article/details/gt2ctohbsvc.html

Java: list.add(0, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gt2xcueposw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jqgfzy.top/Article/details/gt2tjgilirs.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.dianchejie.cn/Article/details/gt2vxyxrogw.html

C#:   list.Insert(0, 0);
来源：http://dali.9152youxi.cn/Article/details/gt2ecjranuu.html

[D04] 删除元素
来源：http://dali.tanke756.top/Article/details/gt2wyvxdemc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ldeweegm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jianghu66.top/Article/details/gt2gnindzsa.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.quarkkingdee.top/Article/details/gt2flejlpib.html

TS:   arr.splice(0, 1);
来源：http://dali.pengpengdd.cyou/Article/details/gt2cpkokycz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.kuanghao11.cn/Article/details/gt2dlswyvyo.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jqgfzy.top/Article/details/gt2qwmbrqfi.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ivvv.top/Article/details/gt2ymyxkhce.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhongyouzk.top/Article/details/gt2xsbpuocv.html

[D05] 访问与修改元素
来源：http://dali.daria6918.cn/Article/details/gt2srhxdtqb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gt2piwaqbic.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.andypj.xyz/Article/details/gt2ruqgwhkw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xuetiantiany.cn/Article/details/gt2tiejavcf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.tian-w.cn/Article/details/gt2eymzcwbh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.quarkkingdee.top/Article/details/gt2ozehcavb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hfpthk.cn/Article/details/gt2vqiayatu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jiagoushi.top/Article/details/gt2ksikwhrc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.sysykeji.top/Article/details/gt2wqtyprfg.html

[D06] 数组长度
来源：http://dali.zhoulong.xyz/Article/details/gt2fghsbfhk.html

Py:   len(arr)
来源：http://dali.mhx1999.top/Article/details/gt2orvyawwh.html

PHP:  count($arr);
来源：http://dali.316326.xyz/Article/details/gt2qawyoxfo.html

JS:   arr.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ppmcprub.html

TS:   arr.length
来源：http://dali.svipenyu.cn/Article/details/gt2mkrgfzdn.html

Java: list.size();
来源：http://dali.316326.xyz/Article/details/gt2gjguqygk.html

Go:   len(arr)
来源：http://dali.pycfn.com/Article/details/gt2bhpzbzwt.html

Ruby: arr.length; arr.size
来源：http://dali.feifeiyinyue.top/Article/details/gt2cfyzwnmt.html

C#:   list.Count;
来源：http://dali.haohaochexian.top/Article/details/gt2ckkxbmga.html

[D07] 切片 / 取子数组
来源：http://dali.gotoacloud.top/Article/details/gt2wjnrvhzi.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.daria6918.cn/Article/details/gt2hqccgzel.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.chenjidiqi.icu/Article/details/gt2oabbmvqi.html

JS:   arr.slice(1, 4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2svvnlovb.html

TS:   arr.slice(1, 4);
来源：http://dali.zdqjudy.top/Article/details/gt2cgroczcb.html

Java: list.subList(1, 4);
来源：http://dali.sufxvd.cn/Article/details/gt2gjtbtjre.html

Go:   arr[1:4]
来源：http://dali.daria6918.cn/Article/details/gt2ngqdfaip.html

Ruby: arr[1, 3]
来源：http://dali.ivvv.top/Article/details/gt2yficiznh.html

C#:   list.GetRange(1, 3);
来源：http://dali.havefunace.top/Article/details/gt2odduiaax.html

[D08] 合并两个数组
来源：http://dali.snrcjt.cn/Article/details/gt2mtcfxjhi.html

Py:   a + b;  a.extend(b)
来源：http://dali.meibo888.top/Article/details/gt2zukwrmiz.html

PHP:  array_merge($a, $b);
来源：http://dali.redwolf501.top/Article/details/gt2nixftgim.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.guannengcc.top/Article/details/gt2gqopohah.html

TS:   [...a, ...b];
来源：http://dali.zhixingplan.top/Article/details/gt2igubwfen.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.gogol.net.cn/Article/details/gt2hkoopgfw.html

Go:   append(a, b...)
来源：http://dali.yanxiufei.cn/Article/details/gt2lduvzwty.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xziqi.cn/Article/details/gt2kausvbfk.html

C#:   a.Concat(b).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gt2zycgcvkc.html

[D09] 排序（升序）
来源：http://dali.xziqi.cn/Article/details/gt2hzqncjmi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.quarkkingdee.top/Article/details/gt2ocuokvas.html

PHP:  sort($arr);
来源：http://dali.sxryk.cn/Article/details/gt2trqilout.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ivvv.top/Article/details/gt2pxzkjpvb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.tianlin.xyz/Article/details/gt2wpyvojns.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhengqikj.top/Article/details/gt2lupluqee.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2tvyuuwsq.html

Ruby: arr.sort
来源：http://dali.zycfv.cn/Article/details/gt2cywjxjvy.html

C#:   list.Sort();
来源：http://dali.ehwqpu.com/Article/details/gt2oqhnwhxy.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xuetiantiany.cn/Article/details/gt2wsvkgwex.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.chenzaomai.com/Article/details/gt2ijrsupda.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cqqwz.cn/Article/details/gt2hvutgruh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fengsongda.top/Article/details/gt2igkrbhmt.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.c1oappe.top/Article/details/gt2hxxxxscg.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jqgfzy.top/Article/details/gt2xdipztnj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cashguo.top/Article/details/gt2kablbyqz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zdqjudy.top/Article/details/gt2zgcezcoz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhoulong.xyz/Article/details/gt2kxbdzuby.html

[D11] 反转数组
来源：http://dali.vqdsnc.cn/Article/details/gt2xcehmywn.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.vqdsnc.cn/Article/details/gt2kemxiojw.html

PHP:  array_reverse($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2fuynxmvy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.chenlongwang.top/Article/details/gt2wdrsiubd.html


<!-- 参考信息 -->