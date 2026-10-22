代发 wailian999

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hammf.cn/Article/details/gtbphtbegk.html

Ruby: (0...10).step(2).to_a
来源：http://dali.fengsongda.top/Article/details/gtbvpadyvu.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzbwjdbkv.html

[B12] 跳出多层循环
来源：http://dali.fzhhl.top/Article/details/gthxjohivr.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.fengsongda.top/Article/details/gtgbrcfgqi.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cashguo.top/Article/details/gtmdhsipao.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnqzz.top/Article/details/gtjzbvswai.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.c1oappe.top/Article/details/gtqbmpvsoz.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cucudq.cn/Article/details/gtctilhsio.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyflpatzw.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhengqikj.top/Article/details/gtqvqoixks.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.tanke756.top/Article/details/gtljfzuipc.html

[B13] 判断是否为数字
来源：http://dali.tian-w.cn/Article/details/gtnusaoeou.html

Py:   isinstance(x, (int, float))
来源：http://dali.jqgufenzy.top/Article/details/gtjrzzkeah.html

PHP:  is_numeric($x)
来源：http://dali.cashguo.top/Article/details/gtxiymvdav.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.smart0.xyz/Article/details/gtuacelveb.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cheryme.top/Article/details/gtgqykhout.html

Java: x instanceof Number
来源：http://dali.jianghu66.top/Article/details/gtihdyubpc.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hnqzz.top/Article/details/gtchmbriki.html

Ruby: x.is_a?(Numeric)
来源：http://dali.gzhubu.top/Article/details/gtqoydrlvf.html

C#:   x is int or double or decimal
来源：http://dali.aibaodan.cn/Article/details/gtsxsguydm.html

[B14] 判断值是否在集合内
来源：http://dali.cucudq.cn/Article/details/gtpukrftnr.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuwjieuly.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.haohaochexian.top/Article/details/gtstldypeo.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gtnhpowtjv.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.dianchejie.cn/Article/details/gtujdxgvoq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtvtzpmdty.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zdqjudy.top/Article/details/gtltqttqxp.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtarlwoink.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ivvv.top/Article/details/gtrgyajrph.html

[B15] 布尔运算与取反
来源：http://dali.dianchejie.cn/Article/details/gtqnavurij.html

Py:   a and b or not c
来源：http://dali.jinqigufen.top/Article/details/gtjgnfuxxq.html

PHP:  $a && $b || !$c
来源：http://dali.shangyingyoupin.top/Article/details/gtkgxknofn.html

JS:   a && b || !c
来源：http://dali.andypj.xyz/Article/details/gtwpdvcufx.html

TS:   a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gtcdmkmkti.html

Java: a && b || !c
来源：http://dali.fzhhl.top/Article/details/gtiyfmlkqr.html

Go:   a && b || !c
来源：http://dali.yonumen.top/Article/details/gtldrymduz.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gtnsuczjtv.html

C#:   a && b || !c
来源：http://dali.sysykeji.top/Article/details/gtvpmvdchs.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jqgfzy.top/Article/details/gthnviykka.html

Py:   if not data: return
来源：http://dali.bjfxy.top/Article/details/gtmshrqcyg.html

PHP:  if (!$data) { return; }
来源：http://dali.chenzaomai.com/Article/details/gtivrqarlx.html

JS:   if (!data) return;
来源：http://dali.pycfn.com/Article/details/gthrlpbyxi.html

TS:   if (!data) return;
来源：http://dali.316326.xyz/Article/details/gtbujsiemm.html

Java: if (data == null) return;
来源：http://dali.tianlin.xyz/Article/details/gtdisveuxe.html

Go:   if data == nil { return }
来源：http://dali.nanxinkj.top/Article/details/gtcmpewgvu.html

Ruby: return if data.nil?
来源：http://dali.shzxlz.cn/Article/details/gtzfdngdlr.html

C#:   if (data == null) return;
来源：http://dali.daria6918.cn/Article/details/gtchuaxwzt.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtcnzqwoeu.html

C. 函数与作用域
来源：http://dali.pycfn.com/Article/details/gtjdyxtidu.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtqiuxlcri.html

[C01] 定义函数
来源：http://dali.zhixingplan.top/Article/details/gtgiuqnvvo.html

Py:   def add(a, b): return a + b
来源：http://dali.nanxinkj.top/Article/details/gtqgsycalb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pycfn.com/Article/details/gtxfxwsxkq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gtdbjbkeai.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtazpolobo.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtarxmrkgt.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xuanzx.com/Article/details/gtqhzhibgk.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yueranfly.top/Article/details/gtrhwwkiye.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtmechakla.html

[C02] 默认参数
来源：http://dali.pengpengdd.cyou/Article/details/gtkrshnems.html

Py:   def greet(name="World"): return name
来源：http://dali.haohaochexian.top/Article/details/gtsmjedhca.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yuanzhike.top/Article/details/gtetssyimm.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtdarqnenj.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xziqi.cn/Article/details/gtgojurvrs.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.gzhubu.top/Article/details/gtllmpmnwf.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xylfe.cn/Article/details/gtnhfhafym.html

Ruby: def greet(name = "World") = name
来源：http://dali.aibaodan.cn/Article/details/gtvqbzcxoe.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.316326.xyz/Article/details/gtnzyaobbc.html

[C03] 可变参数
来源：http://dali.zhixingplan.top/Article/details/gtylsjlusq.html

Py:   def total(*args): return sum(args)
来源：http://dali.ybcxt.top/Article/details/gtuomcevjv.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xziqi.cn/Article/details/gtnintgdbg.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ppjwa.cn/Article/details/gtyyzvchln.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sysykeji.top/Article/details/gtbheppkje.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.bjfxy.top/Article/details/gtqclpkjsd.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yongpay.top/Article/details/gtboabpzqg.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yuxming.cn/Article/details/gtomknfgki.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jianghu66.top/Article/details/gtejwgimlv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinqigfzy.top/Article/details/gtojaiuwfw.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.mhx1999.top/Article/details/gtfltfwwwm.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.vqdsnc.cn/Article/details/gtjjiyrxhs.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ydzc1.top/Article/details/gtdiiuhjff.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yj20258888.top/Article/details/gtekjyudnj.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.gaohongyu789.top/Article/details/gtbsjlljad.html

Go:   // 无：用配置结构体参数
来源：http://dali.chenzaomai.com/Article/details/gtyrezturm.html

Ruby: f(a: 1, b: 2)
来源：http://dali.tanke756.top/Article/details/gtaxlmukqm.html

C#:   f(a: 1, b: 2)
来源：http://dali.ydzc1.top/Article/details/gtnzyzlipy.html

[C05] 返回多个值
来源：http://dali.jianghu66.top/Article/details/gtsbpvrhhc.html

Py:   return a, b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtryrxukjf.html

PHP:  return [$a, $b];
来源：http://dali.xylfe.cn/Article/details/gtijbrsisv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xinyue.icu/Article/details/gtezqwsoif.html

TS:   return { a, b };
来源：http://dali.meibo888.top/Article/details/gthnqftjfc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yj20258.top/Article/details/gtkttktfsa.html

Go:   return a, b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrfgwmqps.html

Ruby: return a, b
来源：http://dali.gzhubu.top/Article/details/gtvbuxijkv.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shangyingyoupin.top/Article/details/gtodyruyrc.html

[C06] 匿名函数 / lambda
来源：http://dali.yj20258.top/Article/details/gtzartqwys.html

Py:   square = lambda x: x * x
来源：http://dali.yj20258.top/Article/details/gtwukmxdle.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hfpthk.cn/Article/details/gtmjeguwsm.html

JS:   const square = x => x * x;
来源：http://dali.zdqjudy.top/Article/details/gtnxlyqsax.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gtzsyarawv.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hammf.cn/Article/details/gtiijzbdrx.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yanxiufei.cn/Article/details/gtvzhxcyvw.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ppjwa.cn/Article/details/gtsbuweuys.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yj202588.top/Article/details/gtoogvtghv.html

[C07] 把函数作为参数传入
来源：http://dali.shanyushiyangtech.top/Article/details/gtjdkfqpwf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.mhx1999.top/Article/details/gteviqzhin.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.dianchejie.cn/Article/details/gtulsgxeil.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ppjwa.cn/Article/details/gtowzutokk.html

TS:   arr.map(String)
来源：http://dali.jqgfzy.top/Article/details/gtapjwlodw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtmarjfsxk.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hysaishi.cn/Article/details/gtqwwsfrev.html

Ruby: arr.map(&:upcase)
来源：http://dali.dashuyun.cn/Article/details/gteakpsuot.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.birdmap.top/Article/details/gtkhuswxbv.html

[C08] 闭包
来源：http://dali.316326.xyz/Article/details/gtunxvgban.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.gzhubu.top/Article/details/gtzolynqpn.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.feifeiyinyue.top/Article/details/gtvbnwwakc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.birdmap.top/Article/details/gtnffvifqr.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hywenlv.cn/Article/details/gtdefthxsk.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ybcxt.top/Article/details/gtueqommvk.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.ydzc1.top/Article/details/gterdcmjxl.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.feifeiyinyue.top/Article/details/gtowdyubcw.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.meibo888.top/Article/details/gtquhwvdjx.html

[C09] 递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpbepmted.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpgjawzkl.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhongyouzk.top/Article/details/gtkmpyvfew.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgufenzy.top/Article/details/gtrkcvimoe.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jlsjyb.cn/Article/details/gtqtwbnath.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zdqjudy.top/Article/details/gtgsmskspi.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.iojbl.cn/Article/details/gtaaqahefo.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yueranfly.top/Article/details/gtlkvddnqs.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cqqwz.cn/Article/details/gtxetjsapm.html

[C10] 变量作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gteubixjfw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhixingplan.top/Article/details/gtsuauekbz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinqigufen.top/Article/details/gthftmxxhk.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.guannengcc.top/Article/details/gtjnihkmqa.html

TS:   同 JS
来源：http://dali.yanxiufei.cn/Article/details/gtmhpwzvva.html

Java: 方法内为块级作用域
来源：http://dali.xziqi.cn/Article/details/gtudzkbpwi.html

Go:   花括号块级作用域
来源：http://dali.birdmap.top/Article/details/gtgylavqud.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hysaishi.cn/Article/details/gtsrmrgcgq.html

C#:   块级作用域
来源：http://dali.yj20258888.top/Article/details/gtiblmikro.html

[C11] 模块导入与导出
来源：http://dali.cashguo.top/Article/details/gtzxhupmqa.html

Py:   from module import func
来源：http://dali.snrcjt.cn/Article/details/gtlksldbtq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yvedp.cn/Article/details/gtclsryhzt.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ppjwa.cn/Article/details/gtmnvvncrn.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zycfv.cn/Article/details/gtvakfotjs.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gtfehvyvcl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.316326.xyz/Article/details/gteclqvjws.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.0kj1m.cn/Article/details/gtuuhwgrew.html

C#:   using System.Text;
来源：http://dali.guannengcc.top/Article/details/gtirmbtdoz.html

[C12] 立即执行函数 IIFE
来源：http://dali.xuetiantiany.cn/Article/details/gtjauehokr.html

Py:   (lambda: print("run"))()
来源：http://dali.gzhubu.top/Article/details/gtpojkdhzu.html

PHP:  (function () { echo "run"; })();
来源：http://dali.0kj1m.cn/Article/details/gtpaemfqyh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.gaohongyu789.top/Article/details/gtiaplqddp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.havefunace.top/Article/details/gtnvozmqvp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shzxlz.cn/Article/details/gtlzaiycul.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.0kj1m.cn/Article/details/gtwstvakoj.html

Ruby: -> { puts "run" }.call
来源：http://dali.iojbl.cn/Article/details/gttpjoibwv.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gotoacloud.top/Article/details/gtkeptxuwc.html

[C13] 类型声明 / 类型注解
来源：http://dali.dianchejie.cn/Article/details/gtqfuctxyx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ybcxt.top/Article/details/gtzsyvzrhu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj202588.top/Article/details/gtmzkwdlwj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hnxiangtu.top/Article/details/gtwmtwsnfd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gtmkrblyzu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtthhrkoug.html

Go:   func add(a, b int) int
来源：http://dali.hongshengwenyu.top/Article/details/gtmpfnoosi.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.mhx1999.top/Article/details/gtzmkglpus.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hysaishi.cn/Article/details/gtgcycxunv.html

[C14] 泛型函数
来源：http://dali.svipenyu.cn/Article/details/gtycuqqhjp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ppjwa.cn/Article/details/gtueklbmbe.html

PHP:  // 无泛型
来源：http://dali.redwolf501.top/Article/details/gtawtxckxq.html

JS:   // 无泛型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtndwysjfv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.wangdashe.top/Article/details/gtsdzhshzn.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jlsjyb.cn/Article/details/gtalucrfby.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yongpay.top/Article/details/gtakunwvhf.html

Ruby: # 无泛型
来源：http://dali.yueranfly.top/Article/details/gtfiyirtux.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenzaomai.com/Article/details/gtvabgnzie.html

[C15] 解构 / 展开参数
来源：http://dali.xylfe.cn/Article/details/gtfswxaxyo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.svipenyu.cn/Article/details/gtbxgexela.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinghuilouyu.cn/Article/details/gtwacsadnq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gogol.net.cn/Article/details/gtxrlgawdf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.redwolf501.top/Article/details/gtahpuonjx.html

Java: // 无解构
来源：http://dali.hysaishi.cn/Article/details/gtmipgubdp.html

Go:   // 无解构
来源：http://dali.shuidangran.top/Article/details/gtncapgfum.html

Ruby: a, b = pair
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdanoaolr.html

C#:   var (a, b) = pair;
来源：http://dali.sufxvd.cn/Article/details/gtzfxhukdu.html

[C16] 函数 / 方法重载
来源：http://dali.hongshengwenyu.top/Article/details/gttqlqyedt.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jinyuanbaomall.cn/Article/details/gttsmyyiyv.html

PHP:  // 无重载
来源：http://dali.hfpthk.cn/Article/details/gtwgrioqrx.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.fengsongda.top/Article/details/gtexaihjpm.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yj202588.top/Article/details/gtiblrcmrm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jlsjyb.cn/Article/details/gtzrdnpach.html

Go:   // 无重载：用不同函数名
来源：http://dali.bjfxy.top/Article/details/gtwkeshzwn.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hammf.cn/Article/details/gttldqcjbv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jiagoushi.top/Article/details/gtzhchnarv.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtjfgoigfr.html

D. 数组 / 列表 / 集合
来源：http://dali.shuidangran.top/Article/details/gtnockfelr.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtpbxlrbvn.html

[D01] 创建数组 / 列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwkzsumjf.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhongyouzk.top/Article/details/gtsavwacjf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shzxlz.cn/Article/details/gtkplvkwio.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.aibaodan.cn/Article/details/gtqhpligwn.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hnqzz.top/Article/details/gtwfdkvqll.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.meibo888.top/Article/details/gtmpudfygi.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jqgufenzy.top/Article/details/gtssxuzywd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvusckqng.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.tian-w.cn/Article/details/gtxxgqlgos.html

[D02] 追加元素到末尾
来源：http://dali.pengpengdd.cyou/Article/details/gtgghdrcwa.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cdnleiting.top/Article/details/gtxlzxkqxf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hongshengwenyu.top/Article/details/gtyisxzkbe.html

JS:   arr.push(4);
来源：http://dali.yj20258888.top/Article/details/gtjuvfgnri.html

TS:   arr.push(4);
来源：http://dali.svipenyu.cn/Article/details/gthwpvoirx.html

Java: list.add(4);
来源：http://dali.kuanghao11.cn/Article/details/gthoamhzpf.html

Go:   arr = append(arr, 4)
来源：http://dali.cdnleiting.top/Article/details/gtcfodwibb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ydzc1.top/Article/details/gttlitomkx.html

C#:   list.Add(4);
来源：http://dali.yanxiufei.cn/Article/details/gtemozqpab.html

[D03] 在指定位置插入元素
来源：http://dali.dashuyun.cn/Article/details/gtfmpvntkb.html

Py:   arr.insert(0, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gthvqwtrmh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.aizwys.cn/Article/details/gtfwbtllch.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.vqdsnc.cn/Article/details/gtijjcfbbo.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxvyhyaxv.html

Java: list.add(0, 0);
来源：http://dali.hywenlv.cn/Article/details/gtajnsvrkj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.chenzaomai.com/Article/details/gtbjnuomos.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ehwqpu.com/Article/details/gtrguizeru.html

C#:   list.Insert(0, 0);
来源：http://dali.gogol.net.cn/Article/details/gtgxrvevyx.html

[D04] 删除元素
来源：http://dali.chenlongwang.top/Article/details/gtjdssnubc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.sxryk.cn/Article/details/gtmjtlqynr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hysaishi.cn/Article/details/gtpcmxnbqb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtujlanvnn.html

TS:   arr.splice(0, 1);
来源：http://dali.chenzaomai.com/Article/details/gtsumwzher.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtjfhcgclu.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.daria6918.cn/Article/details/gtiugcbmxc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.9152youxi.cn/Article/details/gtaiouvbzz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sweek.top/Article/details/gtyzzuhgyu.html

[D05] 访问与修改元素
来源：http://dali.svipenyu.cn/Article/details/gtumbyhklt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gtytygarln.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hnqzz.top/Article/details/gtvafmuynf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yuanzhike.top/Article/details/gtsawggpib.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhiwuduotai.top/Article/details/gtwbxuvwux.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.haohaochexian.top/Article/details/gtfuhhzbbj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yuanzhike.top/Article/details/gtujmiqlpb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ybcxt.top/Article/details/gtlezdvdmq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhiwuduotai.top/Article/details/gtbinbtbcn.html

[D06] 数组长度
来源：http://dali.zhoulong.xyz/Article/details/gtvwdeuhed.html

Py:   len(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtztyfseng.html

PHP:  count($arr);
来源：http://dali.guowangkeji.top/Article/details/gtrjozpnuv.html

JS:   arr.length
来源：http://dali.redwolf501.top/Article/details/gtwtnkxcmc.html

TS:   arr.length
来源：http://dali.yj202588.top/Article/details/gtgzfoacop.html

Java: list.size();
来源：http://dali.vqdsnc.cn/Article/details/gtiqnvvgga.html

Go:   len(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtjtsxrjna.html

Ruby: arr.length; arr.size
来源：http://dali.jqgufenzy.top/Article/details/gtfbztugrs.html

C#:   list.Count;
来源：http://dali.daria6918.cn/Article/details/gtsopxwlnl.html

[D07] 切片 / 取子数组
来源：http://dali.guannengcc.top/Article/details/gtpaeajtbq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.chenjidiqi.icu/Article/details/gthgfkvcfa.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yj20258888.top/Article/details/gtgbhbokum.html

JS:   arr.slice(1, 4);
来源：http://dali.ybcxt.top/Article/details/gttyecugez.html

TS:   arr.slice(1, 4);
来源：http://dali.havefunace.top/Article/details/gtrltiabzk.html

Java: list.subList(1, 4);
来源：http://dali.meibo888.top/Article/details/gtgcpsqgmn.html

Go:   arr[1:4]
来源：http://dali.fzhhl.top/Article/details/gtsftrealy.html

Ruby: arr[1, 3]
来源：http://dali.hongshengwenyu.top/Article/details/gtmnmdzxiw.html

C#:   list.GetRange(1, 3);
来源：http://dali.yuanzhike.top/Article/details/gtsalfisus.html

[D08] 合并两个数组
来源：http://dali.yvedp.cn/Article/details/gtdcndmjha.html

Py:   a + b;  a.extend(b)
来源：http://dali.xuanzx.com/Article/details/gtgwmpglly.html

PHP:  array_merge($a, $b);
来源：http://dali.yueranfly.top/Article/details/gtzxjydbid.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.kuanghao11.cn/Article/details/gtoyzuzshu.html

TS:   [...a, ...b];
来源：http://dali.sysykeji.top/Article/details/gtomaxxagz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.havefunace.top/Article/details/gtgmfxrrhs.html

Go:   append(a, b...)
来源：http://dali.shangyingyoupin.top/Article/details/gtdfzkrzds.html

Ruby: a + b;  a.concat(b)
来源：http://dali.redwolf501.top/Article/details/gtkxyvfcys.html

C#:   a.Concat(b).ToList()
来源：http://dali.nanxinkj.top/Article/details/gtzeibykfk.html

[D09] 排序（升序）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaprchrsb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenzaomai.com/Article/details/gtsvcmlmfs.html

PHP:  sort($arr);
来源：http://dali.ehwqpu.com/Article/details/gtxnifjylf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.sysykeji.top/Article/details/gtszvbahxe.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ydzc1.top/Article/details/gtyviiueht.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.316326.xyz/Article/details/gtpluqyxff.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtzvcdvjog.html

Ruby: arr.sort
来源：http://dali.xinyue.icu/Article/details/gteokjohat.html

C#:   list.Sort();
来源：http://dali.xinyue.icu/Article/details/gttigypnlt.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.vqdsnc.cn/Article/details/gtptqajfoq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cashguo.top/Article/details/gtgrndwwzf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtckbjcswc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnxiangtu.top/Article/details/gtomrznqus.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhoulong.xyz/Article/details/gtxqfitjcl.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhongyouzk.top/Article/details/gtyycbyaih.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhixingplan.top/Article/details/gtuvrgdppj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.vqdsnc.cn/Article/details/gtoihkzgdv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yonumen.top/Article/details/gtalrxxlip.html

[D11] 反转数组
来源：http://dali.andypj.xyz/Article/details/gtsarfbnph.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.smart0.xyz/Article/details/gtiyjmqwik.html

PHP:  array_reverse($arr);
来源：http://dali.zycfv.cn/Article/details/gtdhwzenqf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.c1oappe.top/Article/details/gtxpcmscdv.html

TS:   [...arr].reverse();
来源：http://dali.havefunace.top/Article/details/gtfgyqdcnj.html

Java: Collections.reverse(list);
来源：http://dali.gzhubu.top/Article/details/gtepnvwhye.html

Go:   slices.Reverse(arr)
来源：http://dali.xuanzx.com/Article/details/gtntoqiine.html

Ruby: arr.reverse
来源：http://dali.zhiwuduotai.top/Article/details/gthbehawrd.html

C#:   list.Reverse();
来源：http://dali.sysykeji.top/Article/details/gtrqtilnmq.html

[D12] 查找元素下标
来源：http://dali.wangshuangyany.cn/Article/details/gtiduxwyix.html

Py:   arr.index(x);  x in arr
来源：http://dali.gotoacloud.top/Article/details/gtmqrfcwes.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.sysykeji.top/Article/details/gtmdnajwbh.html


<!-- 参考信息 -->