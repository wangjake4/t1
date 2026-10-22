代发 wailian999

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.pycfn.com/Article/details/gt2cvgdheij.html

Ruby: (0...10).step(2).to_a
来源：http://dali.nwbrower.top/Article/details/gt2mumpqpdb.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.cdnleiting.top/Article/details/gt2nypbsrlg.html

[B12] 跳出多层循环
来源：http://dali.ivvv.top/Article/details/gt2hhlfnnox.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.dashuyun.cn/Article/details/gt2cyjvwvwo.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xylfe.cn/Article/details/gt2zykoyahl.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xinyue.icu/Article/details/gt2cejsimkg.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnqzz.top/Article/details/gt2ovgqpzdc.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cashguo.top/Article/details/gt2zfhslkcd.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.nwbrower.top/Article/details/gt2nyljwxdj.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yonumen.top/Article/details/gt2gdiezfxe.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pansjmqw.html

[B13] 判断是否为数字
来源：http://dali.sufxvd.cn/Article/details/gt2fholfeft.html

Py:   isinstance(x, (int, float))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rtfafvfk.html

PHP:  is_numeric($x)
来源：http://dali.meibo888.top/Article/details/gt2fcasizks.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhixingplan.top/Article/details/gt2ryrisapo.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2djjycfer.html

Java: x instanceof Number
来源：http://dali.tanke756.top/Article/details/gt2cqgbuuel.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.gzhubu.top/Article/details/gt2ojgshxcm.html

Ruby: x.is_a?(Numeric)
来源：http://dali.guowangkeji.top/Article/details/gt2cwzlzudk.html

C#:   x is int or double or decimal
来源：http://dali.vqdsnc.cn/Article/details/gt2onevhmem.html

[B14] 判断值是否在集合内
来源：http://dali.chenjidiqi.icu/Article/details/gt2imdfnjsh.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lxvvmcue.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zlyycbsx.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.dianchejie.cn/Article/details/gt2mwgyntfx.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.xylfe.cn/Article/details/gt2qbxpzsgw.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.gzhubu.top/Article/details/gt2micudemi.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zytljtdr.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pcupnrlk.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.chenzaomai.com/Article/details/gt2ieuuvtio.html

[B15] 布尔运算与取反
来源：http://dali.yj20258.top/Article/details/gt2xfaztvau.html

Py:   a and b or not c
来源：http://dali.shzxlz.cn/Article/details/gt2dozxunoh.html

PHP:  $a && $b || !$c
来源：http://dali.jinghuilouyu.cn/Article/details/gt2osjuomwm.html

JS:   a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gt2hnycugfb.html

TS:   a && b || !c
来源：http://dali.316326.xyz/Article/details/gt2jpoeoqic.html

Java: a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gt2kbamwrcf.html

Go:   a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gt2nfdtwbhu.html

Ruby: a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gt2jikdntai.html

C#:   a && b || !c
来源：http://dali.iojbl.cn/Article/details/gt2lfcqnart.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zycfv.cn/Article/details/gt2chhotphd.html

Py:   if not data: return
来源：http://dali.yonumen.top/Article/details/gt2hhtjuwsi.html

PHP:  if (!$data) { return; }
来源：http://dali.haohaochexian.top/Article/details/gt2hbdgwqzy.html

JS:   if (!data) return;
来源：http://dali.quarkkingdee.top/Article/details/gt2nvdazilk.html

TS:   if (!data) return;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2opapatln.html

Java: if (data == null) return;
来源：http://dali.nanxuanxn.top/Article/details/gt2cxskpzxp.html

Go:   if data == nil { return }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ggraixyl.html

Ruby: return if data.nil?
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2daadllqv.html

C#:   if (data == null) return;
来源：http://dali.9152youxi.cn/Article/details/gt2whypqlol.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2yoaepmsm.html

C. 函数与作用域
来源：http://dali.zhixingplan.top/Article/details/gt2ghwoyuax.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2ruexuwfe.html

[C01] 定义函数
来源：http://dali.jyoumei.cn/Article/details/gt2ssazrjkq.html

Py:   def add(a, b): return a + b
来源：http://dali.hammf.cn/Article/details/gt2isnkozvr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhixingplan.top/Article/details/gt2eyxetyxb.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gt2acsihpgs.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hammf.cn/Article/details/gt2tlrykfmx.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gt2kuhvhvjb.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.dianchejie.cn/Article/details/gt2yxpqakwn.html

Ruby: def add(a, b); a + b; end
来源：http://dali.aizwys.cn/Article/details/gt2kcviyqyq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gt2umkophho.html

[C02] 默认参数
来源：http://dali.tanke756.top/Article/details/gt2oijvvdau.html

Py:   def greet(name="World"): return name
来源：http://dali.quarkkingdee.top/Article/details/gt2guopaycm.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2qfmrmdqc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qgqyyypm.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhflwbbu.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.sxryk.cn/Article/details/gt2xnczwntl.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.nanxuanxn.top/Article/details/gt2upoticqs.html

Ruby: def greet(name = "World") = name
来源：http://dali.tian-w.cn/Article/details/gt2doohskjn.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yangfankeji.com/Article/details/gt2qhfthcdj.html

[C03] 可变参数
来源：http://dali.chenzaomai.com/Article/details/gt2xlrxcsyo.html

Py:   def total(*args): return sum(args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eaxecsmu.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2zipcgvoa.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cashguo.top/Article/details/gt2sbgbxlih.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenlongwang.top/Article/details/gt2ircyftio.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ybcxt.top/Article/details/gt2ltyaslum.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.chenzaomai.com/Article/details/gt2vandrwuw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.mhx1999.top/Article/details/gt2jazgvuxl.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yvedp.cn/Article/details/gt2fcuzltsd.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinqigfzy.top/Article/details/gt2iusbrvvd.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.c1oappe.top/Article/details/gt2dgjhuxuu.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2czrkdfek.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2einmpumy.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cucudq.cn/Article/details/gt2sgmvpotm.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.gzhubu.top/Article/details/gt2cakmwvkg.html

Go:   // 无：用配置结构体参数
来源：http://dali.jyoumei.cn/Article/details/gt2sptmkmtc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hywenlv.cn/Article/details/gt2xhqpfhmv.html

C#:   f(a: 1, b: 2)
来源：http://dali.cashguo.top/Article/details/gt2mbmoukar.html

[C05] 返回多个值
来源：http://dali.gaohongyu789.top/Article/details/gt2mnjnmoof.html

Py:   return a, b
来源：http://dali.meibo888.top/Article/details/gt2hxcnravi.html

PHP:  return [$a, $b];
来源：http://dali.nanxuanxn.top/Article/details/gt2hobilyxx.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yj20258.top/Article/details/gt2xnurclob.html

TS:   return { a, b };
来源：http://dali.dianchejie.cn/Article/details/gt2xgnbywsd.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zycfv.cn/Article/details/gt2ppwaybnt.html

Go:   return a, b
来源：http://dali.yongpay.top/Article/details/gt2xmojwjbp.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2urkoiift.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fzhpnzws.html

[C06] 匿名函数 / lambda
来源：http://dali.yj202588.top/Article/details/gt2vuhhamgp.html

Py:   square = lambda x: x * x
来源：http://dali.tanke756.top/Article/details/gt2yhmuwrkz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.quarkkingdee.top/Article/details/gt2gemaycyk.html

JS:   const square = x => x * x;
来源：http://dali.zhongyouzk.top/Article/details/gt2vlclexov.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hnxiangtu.top/Article/details/gt2cgxycovb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yuanzhike.top/Article/details/gt2liemdgsl.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jyoumei.cn/Article/details/gt2fhilbdmb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.andypj.xyz/Article/details/gt2suruvwck.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cqqwz.cn/Article/details/gt2dxwbcjdg.html

[C07] 把函数作为参数传入
来源：http://dali.hammf.cn/Article/details/gt2rfdkuzsq.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.wangshuangyany.cn/Article/details/gt2lazauryk.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2yigmzlvj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ivvv.top/Article/details/gt2oexsjopd.html

TS:   arr.map(String)
来源：http://dali.gaohongyu789.top/Article/details/gt2ynfrtigr.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.9152youxi.cn/Article/details/gt2sjwposve.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cqqwz.cn/Article/details/gt2fjhynwzq.html

Ruby: arr.map(&:upcase)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bgjribte.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.0kj1m.cn/Article/details/gt2jutonzql.html

[C08] 闭包
来源：http://dali.kuanghao11.cn/Article/details/gt2aiwzjcru.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.sysykeji.top/Article/details/gt2cnxzepmx.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ihurthth.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhengqikj.top/Article/details/gt2vqqiqiam.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bdizazyu.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhixingplan.top/Article/details/gt2gtxbraok.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yj202588.top/Article/details/gt2phnfexmd.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xziqi.cn/Article/details/gt2zrzpcaxh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhongyouzk.top/Article/details/gt2gjlzszag.html

[C09] 递归
来源：http://dali.yvedp.cn/Article/details/gt2zjemqkvt.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.havefunace.top/Article/details/gt2bisaiqfk.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.nwbrower.top/Article/details/gt2wblawegv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lnyhakgj.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhiwuduotai.top/Article/details/gt2ucgeokjv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.sysykeji.top/Article/details/gt2vccmvfvj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hywenlv.cn/Article/details/gt2ofofehbc.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.sxryk.cn/Article/details/gt2ebqemlal.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qqxpktab.html

[C10] 变量作用域
来源：http://dali.feifeiyinyue.top/Article/details/gt2vstedamf.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ydzc1.top/Article/details/gt2nphbhefs.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.gotoacloud.top/Article/details/gt2fepllqqb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.chenzaomai.com/Article/details/gt2saijfmdg.html

TS:   同 JS
来源：http://dali.zhiwuduotai.top/Article/details/gt2kbpnuuez.html

Java: 方法内为块级作用域
来源：http://dali.pycfn.com/Article/details/gt2pqyvowsr.html

Go:   花括号块级作用域
来源：http://dali.redwolf501.top/Article/details/gt2qtzeytri.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shuidangran.top/Article/details/gt2clmnhxtr.html

C#:   块级作用域
来源：http://dali.yuxming.cn/Article/details/gt2ylaookuu.html

[C11] 模块导入与导出
来源：http://dali.jyoumei.cn/Article/details/gt2xzjpeqif.html

Py:   from module import func
来源：http://dali.hnqzz.top/Article/details/gt2snewxaif.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.9152youxi.cn/Article/details/gt2rxxxavje.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.pycfn.com/Article/details/gt2azqfkjdh.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xylfe.cn/Article/details/gt2msslpeda.html

Java: import java.util.List;
来源：http://dali.yj20258888.top/Article/details/gt2zfayhbst.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.nanxuanxn.top/Article/details/gt2rfpwscyq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mebunekp.html

C#:   using System.Text;
来源：http://dali.ehwqpu.com/Article/details/gt2dxwrzick.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhiwuduotai.top/Article/details/gt2xlcnyiua.html

Py:   (lambda: print("run"))()
来源：http://dali.hysaishi.cn/Article/details/gt2gezlcemv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.redwolf501.top/Article/details/gt2wtoainwe.html

JS:   (() => { console.log("run"); })();
来源：http://dali.iojbl.cn/Article/details/gt2laynrjhp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yj20258.top/Article/details/gt2czuhudpi.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yueranfly.top/Article/details/gt2sxesyyvq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.daria6918.cn/Article/details/gt2fdfumysq.html

Ruby: -> { puts "run" }.call
来源：http://dali.tianlin.xyz/Article/details/gt2jfklvczp.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ivvv.top/Article/details/gt2vepmlgrm.html

[C13] 类型声明 / 类型注解
来源：http://dali.cashguo.top/Article/details/gt2gsefiosu.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.fengsongda.top/Article/details/gt2thwlbqzk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cheryme.top/Article/details/gt2qearekvz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.aibaodan.cn/Article/details/gt2izansrjo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gt2csmftgym.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hoodabii.html

Go:   func add(a, b int) int
来源：http://dali.iojbl.cn/Article/details/gt2spjhhkln.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xuetiantiany.cn/Article/details/gt2psfbqtda.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jqgfzy.top/Article/details/gt2pgfnfita.html

[C14] 泛型函数
来源：http://dali.dianchejie.cn/Article/details/gt2pzuseaqj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2btslemzp.html

PHP:  // 无泛型
来源：http://dali.tanke756.top/Article/details/gt2diuzlkhi.html

JS:   // 无泛型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wzrnheck.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.gotoacloud.top/Article/details/gt2yuyohmuk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.nwbrower.top/Article/details/gt2xvezfapr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xinyue.icu/Article/details/gt2qhzojzwv.html

Ruby: # 无泛型
来源：http://dali.tanke756.top/Article/details/gt2tpggnjjp.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhixingplan.top/Article/details/gt2xnvhfxxv.html

[C15] 解构 / 展开参数
来源：http://dali.hammf.cn/Article/details/gt2vfiowteh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.nwbrower.top/Article/details/gt2fqxiwjpz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.snrcjt.cn/Article/details/gt2ofvpvqgc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yvedp.cn/Article/details/gt2zbmkjgpa.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xziqi.cn/Article/details/gt2ygmsavny.html

Java: // 无解构
来源：http://dali.aizwys.cn/Article/details/gt2kwtkcjpc.html

Go:   // 无解构
来源：http://dali.feifeiyinyue.top/Article/details/gt2ddoizcjb.html

Ruby: a, b = pair
来源：http://dali.nanxuanxn.top/Article/details/gt2thguuaxj.html

C#:   var (a, b) = pair;
来源：http://dali.zhongyouzk.top/Article/details/gt2aoewapsx.html

[C16] 函数 / 方法重载
来源：http://dali.mhx1999.top/Article/details/gt2ibiexxhl.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.redwolf501.top/Article/details/gt2oumbresz.html

PHP:  // 无重载
来源：http://dali.yvedp.cn/Article/details/gt2uxreupyq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ehwqpu.com/Article/details/gt2rajrilhg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yj20258.top/Article/details/gt2sdzsgboa.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jianghu66.top/Article/details/gt2zmpfnqto.html

Go:   // 无重载：用不同函数名
来源：http://dali.dashuyun.cn/Article/details/gt2awsilimp.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yj20258888.top/Article/details/gt2dvljhvjj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2zqkbeonx.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2czzwmfyf.html

D. 数组 / 列表 / 集合
来源：http://dali.guannengcc.top/Article/details/gt2tzzfmuzi.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mztqfurb.html

[D01] 创建数组 / 列表
来源：http://dali.guannengcc.top/Article/details/gt2qtgcpade.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.iojbl.cn/Article/details/gt2npajryav.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xylfe.cn/Article/details/gt2dlymegxb.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hywenlv.cn/Article/details/gt2gnkzaleb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hywenlv.cn/Article/details/gt2rlctavtg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hywenlv.cn/Article/details/gt2bxtsurlu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.nwbrower.top/Article/details/gt2derofbey.html

Ruby: arr = [1, 2, 3]
来源：http://dali.guowangkeji.top/Article/details/gt2birlexmn.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yuxming.cn/Article/details/gt2wqobvymv.html

[D02] 追加元素到末尾
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hblqqqya.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.fengsongda.top/Article/details/gt2vhzsjffi.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.dianchejie.cn/Article/details/gt2antamjkw.html

JS:   arr.push(4);
来源：http://dali.zhiwuduotai.top/Article/details/gt2gcvdxnhk.html

TS:   arr.push(4);
来源：http://dali.hnxiangtu.top/Article/details/gt2ioexucku.html

Java: list.add(4);
来源：http://dali.hnqzz.top/Article/details/gt2mqvvxkhv.html

Go:   arr = append(arr, 4)
来源：http://dali.andypj.xyz/Article/details/gt2vucnlgpv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cqqwz.cn/Article/details/gt2qfzmkjli.html

C#:   list.Add(4);
来源：http://dali.sxryk.cn/Article/details/gt2ksgblczj.html

[D03] 在指定位置插入元素
来源：http://dali.feifeiyinyue.top/Article/details/gt2qfaxjtfr.html

Py:   arr.insert(0, 0)
来源：http://dali.jinqigufen.top/Article/details/gt2vstnongs.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.feifeiyinyue.top/Article/details/gt2adbenper.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gotoacloud.top/Article/details/gt2nvlcjfnp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.redwolf501.top/Article/details/gt2fchphzmk.html

Java: list.add(0, 0);
来源：http://dali.quarkkingdee.top/Article/details/gt2fyhnyraz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hnxiangtu.top/Article/details/gt2uogefyai.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xuanzx.com/Article/details/gt2zycwcdee.html

C#:   list.Insert(0, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gt2hbmsvoqz.html

[D04] 删除元素
来源：http://dali.nanxuanxn.top/Article/details/gt2myjnzyud.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.fzhhl.top/Article/details/gt2hscdubsu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.fengsongda.top/Article/details/gt2vcpotmwg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zptzopzo.html

TS:   arr.splice(0, 1);
来源：http://dali.aibaodan.cn/Article/details/gt2kmdpgfez.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhengqikj.top/Article/details/gt2luudpxup.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vwiihbqc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhixingplan.top/Article/details/gt2xanpouto.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sysykeji.top/Article/details/gt2crbqpldq.html

[D05] 访问与修改元素
来源：http://dali.yongpay.top/Article/details/gt2vxzypjwb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.quarkkingdee.top/Article/details/gt2lzwidrbh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yuanzhike.top/Article/details/gt2aqmqapjw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ehwqpu.com/Article/details/gt2wtxkvoex.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jiagoushi.top/Article/details/gt2qstkepaj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.wangdashe.top/Article/details/gt2myhwgpef.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shuidangran.top/Article/details/gt2vgydypwh.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.daria6918.cn/Article/details/gt2xulkhxpm.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.mhx1999.top/Article/details/gt2lqkehyvv.html

[D06] 数组长度
来源：http://dali.ybcxt.top/Article/details/gt2islualyv.html

Py:   len(arr)
来源：http://dali.pycfn.com/Article/details/gt2yntqlwao.html

PHP:  count($arr);
来源：http://dali.hysaishi.cn/Article/details/gt2foiycdmu.html

JS:   arr.length
来源：http://dali.zhengqikj.top/Article/details/gt2rsmjzqxx.html

TS:   arr.length
来源：http://dali.jlsjyb.cn/Article/details/gt2dkvbqcwj.html

Java: list.size();
来源：http://dali.xuetiantiany.cn/Article/details/gt2icyrtkrf.html

Go:   len(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2fzwogusj.html

Ruby: arr.length; arr.size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nlnirzxn.html

C#:   list.Count;
来源：http://dali.guannengcc.top/Article/details/gt2uooqnqoe.html

[D07] 切片 / 取子数组
来源：http://dali.fzhhl.top/Article/details/gt2yylpzyxb.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yanxiufei.cn/Article/details/gt2gjblkltk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.aibaodan.cn/Article/details/gt2kfdgovrc.html

JS:   arr.slice(1, 4);
来源：http://dali.hnqzz.top/Article/details/gt2gmlyabnk.html

TS:   arr.slice(1, 4);
来源：http://dali.xuanzx.com/Article/details/gt2nfozsptf.html

Java: list.subList(1, 4);
来源：http://dali.zhiwuduotai.top/Article/details/gt2nwfwlvea.html

Go:   arr[1:4]
来源：http://dali.gotoacloud.top/Article/details/gt2xtdjwzgz.html

Ruby: arr[1, 3]
来源：http://dali.chenlongwang.top/Article/details/gt2xcrssuha.html

C#:   list.GetRange(1, 3);
来源：http://dali.jqgfzy.top/Article/details/gt2exwgcbdb.html

[D08] 合并两个数组
来源：http://dali.hnqzz.top/Article/details/gt2ajrfvwqi.html

Py:   a + b;  a.extend(b)
来源：http://dali.xinyue.icu/Article/details/gt2ivjptikl.html

PHP:  array_merge($a, $b);
来源：http://dali.gaohongyu789.top/Article/details/gt2ospeztrq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.fzhhl.top/Article/details/gt2rkhjbngy.html

TS:   [...a, ...b];
来源：http://dali.nanxinkj.top/Article/details/gt2oqiadpau.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jqgufenzy.top/Article/details/gt2mtokcdns.html

Go:   append(a, b...)
来源：http://dali.yonumen.top/Article/details/gt2gcyjvhho.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cucudq.cn/Article/details/gt2iqhzkgir.html

C#:   a.Concat(b).ToList()
来源：http://dali.ybcxt.top/Article/details/gt2sbtmotlz.html

[D09] 排序（升序）
来源：http://dali.xylfe.cn/Article/details/gt2kggwfptt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yueranfly.top/Article/details/gt2vvopezvn.html

PHP:  sort($arr);
来源：http://dali.pycfn.com/Article/details/gt2frugkqfd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhengqikj.top/Article/details/gt2cuuascud.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ppjwa.cn/Article/details/gt2atdfpxvl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yvedp.cn/Article/details/gt2xpshvryh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2avnptfuk.html

Ruby: arr.sort
来源：http://dali.andypj.xyz/Article/details/gt2exdculez.html

C#:   list.Sort();
来源：http://dali.316326.xyz/Article/details/gt2ypkhodwn.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.birdmap.top/Article/details/gt2wojgyqlx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.vqdsnc.cn/Article/details/gt2cjwqwsvu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xuanzx.com/Article/details/gt2deadjbcy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aibaodan.cn/Article/details/gt2krbgdbaj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nwbrower.top/Article/details/gt2rhryztqy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ydzc1.top/Article/details/gt2ajlgcaqd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zycfv.cn/Article/details/gt2veomfvzx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.tian-w.cn/Article/details/gt2vxnmbnkf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinghuilouyu.cn/Article/details/gt2duyfssnp.html

[D11] 反转数组
来源：http://dali.yongpay.top/Article/details/gt2godudpoq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.fengsongda.top/Article/details/gt2vqhyfsab.html

PHP:  array_reverse($arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2xsfnjqsx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yanxiufei.cn/Article/details/gt2lknvrtai.html

TS:   [...arr].reverse();
来源：http://dali.kuanghao11.cn/Article/details/gt2qfhcskex.html

Java: Collections.reverse(list);
来源：http://dali.yonumen.top/Article/details/gt2ecmioimz.html

Go:   slices.Reverse(arr)
来源：http://dali.hnqzz.top/Article/details/gt2jbucercm.html

Ruby: arr.reverse
来源：http://dali.hnqzz.top/Article/details/gt2mktwakjb.html

C#:   list.Reverse();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2axmuxaoh.html

[D12] 查找元素下标
来源：http://dali.yonumen.top/Article/details/gt2zynijphy.html

Py:   arr.index(x);  x in arr
来源：http://dali.ehwqpu.com/Article/details/gt2kjfshrrb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.dashuyun.cn/Article/details/gt2nbceymqc.html


<!-- 参考信息 -->