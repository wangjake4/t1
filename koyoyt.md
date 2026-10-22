代发 wailian999

PHP:  range(0, 10, 2);
来源：http://dali.xylfe.cn/Article/details/gt2cjybajon.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jyoumei.cn/Article/details/gt2rkfrkwla.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sysykeji.top/Article/details/gt2tqtvtrda.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jqgfzy.top/Article/details/gt2dfoirflq.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.gogol.net.cn/Article/details/gt2lxlfviwy.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ojzeaulm.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.nwbrower.top/Article/details/gt2azblzoyj.html

[B12] 跳出多层循环
来源：http://dali.jlsjyb.cn/Article/details/gt2qpcnytbx.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hongshengwenyu.top/Article/details/gt2khynabmt.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cdnleiting.top/Article/details/gt2iprcatel.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gotoacloud.top/Article/details/gt2wghnwqag.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.fengsongda.top/Article/details/gt2qbpbsijb.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.sxryk.cn/Article/details/gt2jeijquxm.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2fxyukmhe.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.iojbl.cn/Article/details/gt2cidgfrmo.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.haohaochexian.top/Article/details/gt2stwcbtdt.html

[B13] 判断是否为数字
来源：http://dali.chenjidiqi.icu/Article/details/gt2vkhbcvxb.html

Py:   isinstance(x, (int, float))
来源：http://dali.c1oappe.top/Article/details/gt2enwxbori.html

PHP:  is_numeric($x)
来源：http://dali.jlsjyb.cn/Article/details/gt2goowyiah.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj20258.top/Article/details/gt2tirljdvy.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenlongwang.top/Article/details/gt2ffusgfzd.html

Java: x instanceof Number
来源：http://dali.ppjwa.cn/Article/details/gt2yplmkads.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.haohaochexian.top/Article/details/gt2dizocijs.html

Ruby: x.is_a?(Numeric)
来源：http://dali.cdnleiting.top/Article/details/gt2lqdhshsy.html

C#:   x is int or double or decimal
来源：http://dali.aizwys.cn/Article/details/gt2srdvmcjv.html

[B14] 判断值是否在集合内
来源：http://dali.ppjwa.cn/Article/details/gt2hwldlfft.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.nanxinkj.top/Article/details/gt2mwbdutqs.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yuanzhike.top/Article/details/gt2sntpykum.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ivvv.top/Article/details/gt2cvqfeahv.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.gogol.net.cn/Article/details/gt2euvelrdf.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2ihycpjbz.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yj20258888.top/Article/details/gt2iqzmvrui.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.guowangkeji.top/Article/details/gt2joggkukb.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yangfankeji.com/Article/details/gt2lqxrmuai.html

[B15] 布尔运算与取反
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gyghztam.html

Py:   a and b or not c
来源：http://dali.zhixingplan.top/Article/details/gt2zpsfsask.html

PHP:  $a && $b || !$c
来源：http://dali.smart0.xyz/Article/details/gt2ckdcbmfw.html

JS:   a && b || !c
来源：http://dali.pycfn.com/Article/details/gt2omzaxmjz.html

TS:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gt2aiesolxu.html

Java: a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gt2shtatdmi.html

Go:   a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ycolfjqn.html

Ruby: a && b || !c
来源：http://dali.c1oappe.top/Article/details/gt2cfdkomgt.html

C#:   a && b || !c
来源：http://dali.tianlin.xyz/Article/details/gt2nodzqnle.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlyydbu.html

Py:   if not data: return
来源：http://dali.iojbl.cn/Article/details/gt2utfrwqkq.html

PHP:  if (!$data) { return; }
来源：http://dali.hfpthk.cn/Article/details/gt2zjqhpmsq.html

JS:   if (!data) return;
来源：http://dali.fzhhl.top/Article/details/gt2wkkcihaq.html

TS:   if (!data) return;
来源：http://dali.tanke756.top/Article/details/gt2mfjfgddi.html

Java: if (data == null) return;
来源：http://dali.snrcjt.cn/Article/details/gt2ulfujpgt.html

Go:   if data == nil { return }
来源：http://dali.ppjwa.cn/Article/details/gt2yrarrvhr.html

Ruby: return if data.nil?
来源：http://dali.vqdsnc.cn/Article/details/gt2fbjatrzj.html

C#:   if (data == null) return;
来源：http://dali.jinqigfzy.top/Article/details/gt2emgkbxyu.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2aipiyrcj.html

C. 函数与作用域
来源：http://dali.yanxiufei.cn/Article/details/gt2xlulsnfu.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2yaqmyyqm.html

[C01] 定义函数
来源：http://dali.quarkkingdee.top/Article/details/gt2enbacmbs.html

Py:   def add(a, b): return a + b
来源：http://dali.gzhubu.top/Article/details/gt2qpcyjlsb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gt2rosubdnu.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gt2fixzvwkh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qcesbixh.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gt2dxssvenh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.haohaochexian.top/Article/details/gt2ytnasccc.html

Ruby: def add(a, b); a + b; end
来源：http://dali.pycfn.com/Article/details/gt2idxplwvj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sommzjmq.html

[C02] 默认参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2sqxetnko.html

Py:   def greet(name="World"): return name
来源：http://dali.hysaishi.cn/Article/details/gt2vwhpgeby.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zycfv.cn/Article/details/gt2cdlryuhh.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wknmrmta.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zdqjudy.top/Article/details/gt2qrhdmgab.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.iojbl.cn/Article/details/gt2olvhcayj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.kuanghao11.cn/Article/details/gt2htgoppts.html

Ruby: def greet(name = "World") = name
来源：http://dali.ehwqpu.com/Article/details/gt2lffzqanv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.dashuyun.cn/Article/details/gt2tacmunip.html

[C03] 可变参数
来源：http://dali.gotoacloud.top/Article/details/gt2lbpiinjn.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uxagnfii.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhongyouzk.top/Article/details/gt2ztahauti.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhengqikj.top/Article/details/gt2irzvdbia.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.aibaodan.cn/Article/details/gt2vebvmizg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jianghu66.top/Article/details/gt2rlmgyspp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zycfv.cn/Article/details/gt2rhuwrhsz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zycfv.cn/Article/details/gt2felpirjv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2opfrjuua.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gotoacloud.top/Article/details/gt2behvrawz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2niibhkfv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.tanke756.top/Article/details/gt2eckybgiv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rarkwnpp.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yongpay.top/Article/details/gt2ulnzdisr.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.daria6918.cn/Article/details/gt2hupbkwtm.html

Go:   // 无：用配置结构体参数
来源：http://dali.guowangkeji.top/Article/details/gt2ybzjnguh.html

Ruby: f(a: 1, b: 2)
来源：http://dali.guannengcc.top/Article/details/gt2pnofkmfa.html

C#:   f(a: 1, b: 2)
来源：http://dali.yj20258.top/Article/details/gt2xkeslnot.html

[C05] 返回多个值
来源：http://dali.daria6918.cn/Article/details/gt2qomhsuvb.html

Py:   return a, b
来源：http://dali.daria6918.cn/Article/details/gt2qygbtnxq.html

PHP:  return [$a, $b];
来源：http://dali.jqgufenzy.top/Article/details/gt2udotlcis.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.meibo888.top/Article/details/gt2joyiljhm.html

TS:   return { a, b };
来源：http://dali.9152youxi.cn/Article/details/gt2ohpkeylz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hnqzz.top/Article/details/gt2ocqgfryt.html

Go:   return a, b
来源：http://dali.zhoulong.xyz/Article/details/gt2hsicehst.html

Ruby: return a, b
来源：http://dali.snrcjt.cn/Article/details/gt2dmnsbjqz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yangfankeji.com/Article/details/gt2ykexsvqk.html

[C06] 匿名函数 / lambda
来源：http://dali.shzxlz.cn/Article/details/gt2nlzbqefj.html

Py:   square = lambda x: x * x
来源：http://dali.c1oappe.top/Article/details/gt2wokdttce.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.fzhhl.top/Article/details/gt2qdezhyde.html

JS:   const square = x => x * x;
来源：http://dali.jqgfzy.top/Article/details/gt2gbrybnen.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zdqjudy.top/Article/details/gt2twrlnqkv.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.smart0.xyz/Article/details/gt2ykehpefi.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yuxming.cn/Article/details/gt2bokwmtpf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.redwolf501.top/Article/details/gt2iqlwgzkf.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xxghjqjr.html

[C07] 把函数作为参数传入
来源：http://dali.cqqwz.cn/Article/details/gt2cryirhdv.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jqgufenzy.top/Article/details/gt2jqyiplzl.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cashguo.top/Article/details/gt2ftoqwmmg.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zycfv.cn/Article/details/gt2skjoxcjv.html

TS:   arr.map(String)
来源：http://dali.xziqi.cn/Article/details/gt2bhzoxybi.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ivvv.top/Article/details/gt2gddrkkna.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.sxryk.cn/Article/details/gt2bjeyvoxh.html

Ruby: arr.map(&:upcase)
来源：http://dali.yj202588.top/Article/details/gt2arefmmjv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yj202588.top/Article/details/gt2evmdgnin.html

[C08] 闭包
来源：http://dali.svipenyu.cn/Article/details/gt2ockxmotd.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jqgfzy.top/Article/details/gt2coysuoyd.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nfybelsc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.haohaochexian.top/Article/details/gt2fzqcslwk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2xcmwomkz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xylfe.cn/Article/details/gt2erxqiqlt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.ppjwa.cn/Article/details/gt2hwnnppnx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yangfankeji.com/Article/details/gt2maiddbyg.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hammf.cn/Article/details/gt2fjrdshgf.html

[C09] 递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cahzjxml.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xuanzx.com/Article/details/gt2uicftecw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.mhx1999.top/Article/details/gt2ruxhcgmr.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yuanzhike.top/Article/details/gt2twzhtqwc.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xuetiantiany.cn/Article/details/gt2hrpchazu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.quarkkingdee.top/Article/details/gt2axvghbke.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shzxlz.cn/Article/details/gt2fstxkpco.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.fzhhl.top/Article/details/gt2uvwltvpg.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cucudq.cn/Article/details/gt2npensdsf.html

[C10] 变量作用域
来源：http://dali.fzhhl.top/Article/details/gt2gjzoftyf.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhixingplan.top/Article/details/gt2kxmnjmrd.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cqqwz.cn/Article/details/gt2isitphsp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yangfankeji.com/Article/details/gt2kncazvpf.html

TS:   同 JS
来源：http://dali.ybcxt.top/Article/details/gt2uwhtiyhx.html

Java: 方法内为块级作用域
来源：http://dali.meibo888.top/Article/details/gt2ytksoczz.html

Go:   花括号块级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gt2tqrxofuy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yuxming.cn/Article/details/gt2yyvfamnh.html

C#:   块级作用域
来源：http://dali.shzxlz.cn/Article/details/gt2fnifunzl.html

[C11] 模块导入与导出
来源：http://dali.iojbl.cn/Article/details/gt2yyafxsgw.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2hizdhork.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hfpthk.cn/Article/details/gt2tisgrxtv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhoulong.xyz/Article/details/gt2kzwucqcr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.aizwys.cn/Article/details/gt2rghinjwm.html

Java: import java.util.List;
来源：http://dali.yvedp.cn/Article/details/gt2cubmoijt.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.c1oappe.top/Article/details/gt2jplxnzrm.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wugkkwfp.html

C#:   using System.Text;
来源：http://dali.jqgufenzy.top/Article/details/gt2imncghwc.html

[C12] 立即执行函数 IIFE
来源：http://dali.gogol.net.cn/Article/details/gt2xugvwasq.html

Py:   (lambda: print("run"))()
来源：http://dali.aibaodan.cn/Article/details/gt2usqwnxut.html

PHP:  (function () { echo "run"; })();
来源：http://dali.pengpengdd.cyou/Article/details/gt2ivstadfq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.gzhubu.top/Article/details/gt2yguezqvu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.smart0.xyz/Article/details/gt2qiesvxiz.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.316326.xyz/Article/details/gt2btesdtxo.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.sweek.top/Article/details/gt2irxaxxqt.html

Ruby: -> { puts "run" }.call
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mcobqdad.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jqgfzy.top/Article/details/gt2aiwiafpl.html

[C13] 类型声明 / 类型注解
来源：http://dali.9152youxi.cn/Article/details/gt2chcenypt.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.nanxinkj.top/Article/details/gt2qnjfcybk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dashuyun.cn/Article/details/gt2tyguejxb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shzxlz.cn/Article/details/gt2oqvjtoud.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gt2nvypdylb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gt2toyazorc.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2qaebqqsk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zycfv.cn/Article/details/gt2ivsfhhgh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cucudq.cn/Article/details/gt2wjunmewy.html

[C14] 泛型函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2omjrlecb.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.tanke756.top/Article/details/gt2pdubgcoc.html

PHP:  // 无泛型
来源：http://dali.sweek.top/Article/details/gt2qwyqwwud.html

JS:   // 无泛型
来源：http://dali.zhiwuduotai.top/Article/details/gt2xnybspmt.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2fadhelmm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.quarkkingdee.top/Article/details/gt2lkldclwg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hongshengwenyu.top/Article/details/gt2irepgpwm.html

Ruby: # 无泛型
来源：http://dali.jyoumei.cn/Article/details/gt2usujcfzb.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zycfv.cn/Article/details/gt2abtogjpq.html

[C15] 解构 / 展开参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2szhmxqtu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.guannengcc.top/Article/details/gt2nswgjrwv.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhongyouzk.top/Article/details/gt2ziwwwatr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2elunllcd.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gogol.net.cn/Article/details/gt2qjfqdyow.html

Java: // 无解构
来源：http://dali.gzhubu.top/Article/details/gt2zzapepam.html

Go:   // 无解构
来源：http://dali.havefunace.top/Article/details/gt2ujiolcam.html

Ruby: a, b = pair
来源：http://dali.jqgufenzy.top/Article/details/gt2ceohumjn.html

C#:   var (a, b) = pair;
来源：http://dali.yj20258888.top/Article/details/gt2dvsshzka.html

[C16] 函数 / 方法重载
来源：http://dali.cqqwz.cn/Article/details/gt2lxvkbrzk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.dashuyun.cn/Article/details/gt2jhtjkifc.html

PHP:  // 无重载
来源：http://dali.xinyue.icu/Article/details/gt2bfasvfxc.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hywenlv.cn/Article/details/gt2wrloxiia.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yueranfly.top/Article/details/gt2rjtqodan.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2egsgmdjw.html

Go:   // 无重载：用不同函数名
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qbufkinl.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yuxming.cn/Article/details/gt2iukjhiov.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2mlimgpjx.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bwculuok.html

D. 数组 / 列表 / 集合
来源：http://dali.gaohongyu789.top/Article/details/gt2enabhjyc.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2cppyckhc.html

[D01] 创建数组 / 列表
来源：http://dali.jqgfzy.top/Article/details/gt2wuizoptc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.daxiang520.top/Article/details/gt2slpgcvbi.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.pengpengdd.cyou/Article/details/gt2stpmqjql.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ivvv.top/Article/details/gt2nbomroym.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.gotoacloud.top/Article/details/gt2xwtduqld.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mofxezwb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.smart0.xyz/Article/details/gt2kdetciya.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sysykeji.top/Article/details/gt2ubnjsdwe.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cucudq.cn/Article/details/gt2xbbxegdz.html

[D02] 追加元素到末尾
来源：http://dali.nanxinkj.top/Article/details/gt2fdfohbdr.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.wangdashe.top/Article/details/gt2qymawkir.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhongyouzk.top/Article/details/gt2iztnysdu.html

JS:   arr.push(4);
来源：http://dali.chenlongwang.top/Article/details/gt2twezbynh.html

TS:   arr.push(4);
来源：http://dali.cdnleiting.top/Article/details/gt2hvojqnsk.html

Java: list.add(4);
来源：http://dali.cheryme.top/Article/details/gt2gcmvjogb.html

Go:   arr = append(arr, 4)
来源：http://dali.yvedp.cn/Article/details/gt2gjdspjqd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhixingplan.top/Article/details/gt2ykhdczbe.html

C#:   list.Add(4);
来源：http://dali.ybcxt.top/Article/details/gt2vxykvibk.html

[D03] 在指定位置插入元素
来源：http://dali.yongpay.top/Article/details/gt2xaxyoiqb.html

Py:   arr.insert(0, 0)
来源：http://dali.jqgfzy.top/Article/details/gt2jyrtfihv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.quarkkingdee.top/Article/details/gt2vovvsaty.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.birdmap.top/Article/details/gt2jnplqisp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.guannengcc.top/Article/details/gt2fnbfoioc.html

Java: list.add(0, 0);
来源：http://dali.hysaishi.cn/Article/details/gt2zqtdokyi.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.havefunace.top/Article/details/gt2qakpaqtv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cashguo.top/Article/details/gt2tnnijmnf.html

C#:   list.Insert(0, 0);
来源：http://dali.wangdashe.top/Article/details/gt2wpaudwya.html

[D04] 删除元素
来源：http://dali.zycfv.cn/Article/details/gt2ndvsmhmj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.nanxinkj.top/Article/details/gt2obedpmil.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yj20258.top/Article/details/gt2vvqjvnwa.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cucudq.cn/Article/details/gt2hdgdfvvy.html

TS:   arr.splice(0, 1);
来源：http://dali.wangshuangyany.cn/Article/details/gt2boysxaoi.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.tianlin.xyz/Article/details/gt2mvugahpg.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ejpjffvu.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ehwqpu.com/Article/details/gt2reycvqbj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cdnleiting.top/Article/details/gt2zytxoeqt.html

[D05] 访问与修改元素
来源：http://dali.chenlongwang.top/Article/details/gt2pghylvvq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gotoacloud.top/Article/details/gt2lobazojq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sufxvd.cn/Article/details/gt2cwoiyyni.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.chenjidiqi.icu/Article/details/gt2yynhwoep.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sysykeji.top/Article/details/gt2oiqwsrtc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.haohaochexian.top/Article/details/gt2cfwxovtc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yangfankeji.com/Article/details/gt2riyignqt.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cheryme.top/Article/details/gt2yloulixw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yvedp.cn/Article/details/gt2antkfapo.html

[D06] 数组长度
来源：http://dali.chenlongwang.top/Article/details/gt2wdqbczaw.html

Py:   len(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2prnyqnih.html

PHP:  count($arr);
来源：http://dali.cucudq.cn/Article/details/gt2yqwnsinv.html

JS:   arr.length
来源：http://dali.hnxiangtu.top/Article/details/gt2ltfpzvot.html

TS:   arr.length
来源：http://dali.zhongyouzk.top/Article/details/gt2fptbvaxz.html

Java: list.size();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wwgodoou.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aretcsxe.html

Ruby: arr.length; arr.size
来源：http://dali.316326.xyz/Article/details/gt2qylmydzl.html

C#:   list.Count;
来源：http://dali.jinqigfzy.top/Article/details/gt2zxdmmxoh.html

[D07] 切片 / 取子数组
来源：http://dali.hfpthk.cn/Article/details/gt2lcabiaoh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sysykeji.top/Article/details/gt2rcefbopa.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.daria6918.cn/Article/details/gt2dtyrlrrj.html

JS:   arr.slice(1, 4);
来源：http://dali.yangfankeji.com/Article/details/gt2aarqrdon.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2iegfloyv.html

Java: list.subList(1, 4);
来源：http://dali.shzxlz.cn/Article/details/gt2bstjoyro.html

Go:   arr[1:4]
来源：http://dali.jlsjyb.cn/Article/details/gt2bsvpnoai.html

Ruby: arr[1, 3]
来源：http://dali.hysaishi.cn/Article/details/gt2jqupnqpx.html

C#:   list.GetRange(1, 3);
来源：http://dali.svipenyu.cn/Article/details/gt2xwiapbws.html

[D08] 合并两个数组
来源：http://dali.jinqigfzy.top/Article/details/gt2krchehgf.html

Py:   a + b;  a.extend(b)
来源：http://dali.ehwqpu.com/Article/details/gt2nnaefmjz.html

PHP:  array_merge($a, $b);
来源：http://dali.havefunace.top/Article/details/gt2xxwhwigi.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.aibaodan.cn/Article/details/gt2rgsmsmtr.html

TS:   [...a, ...b];
来源：http://dali.cheryme.top/Article/details/gt2dtsnkbpi.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.fzhhl.top/Article/details/gt2ueopwquw.html

Go:   append(a, b...)
来源：http://dali.yangfankeji.com/Article/details/gt2mvqofhoa.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hnxiangtu.top/Article/details/gt2intktgut.html

C#:   a.Concat(b).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gt2nzqptwcd.html

[D09] 排序（升序）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uyrdxrfi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gerduvcz.html

PHP:  sort($arr);
来源：http://dali.ydzc1.top/Article/details/gt2zzylsxzk.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cashguo.top/Article/details/gt2jbpykgod.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.svipenyu.cn/Article/details/gt2bjsclidw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.nanxuanxn.top/Article/details/gt2vgbglhks.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2plautwft.html

Ruby: arr.sort
来源：http://dali.feifeiyinyue.top/Article/details/gt2mqhxxdfr.html

C#:   list.Sort();
来源：http://dali.jianghu66.top/Article/details/gt2vhdftgwr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.fzhhl.top/Article/details/gt2cwagctea.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shzxlz.cn/Article/details/gt2qfveszke.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenjidiqi.icu/Article/details/gt2fhszpsob.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgfzy.top/Article/details/gt2hnrfslnh.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgufenzy.top/Article/details/gt2zglianfj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhixingplan.top/Article/details/gt2dnyszhve.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.snrcjt.cn/Article/details/gt2osnjgdwg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xuanzx.com/Article/details/gt2pkitsnoi.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.bjfxy.top/Article/details/gt2pbtdvglg.html

[D11] 反转数组
来源：http://dali.zhiwuduotai.top/Article/details/gt2vfbijmsh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.gotoacloud.top/Article/details/gt2pagvjhhl.html

PHP:  array_reverse($arr);
来源：http://dali.ehwqpu.com/Article/details/gt2wcemkvxg.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hywenlv.cn/Article/details/gt2qlpfjxvh.html

TS:   [...arr].reverse();
来源：http://dali.shuidangran.top/Article/details/gt2bmdanbim.html

Java: Collections.reverse(list);
来源：http://dali.hammf.cn/Article/details/gt2uofamokz.html

Go:   slices.Reverse(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2lqqldgfe.html

Ruby: arr.reverse
来源：http://dali.jlsjyb.cn/Article/details/gt2ronbnhsp.html


<!-- 参考信息 -->