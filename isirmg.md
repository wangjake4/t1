代发 wailian999

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yonumen.top/Article/details/gtisohazrw.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zdqjudy.top/Article/details/gtjvbfagut.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhoulong.xyz/Article/details/gtbkulvraw.html

[B12] 跳出多层循环
来源：http://dali.9152youxi.cn/Article/details/gtiscfhrrp.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.mhx1999.top/Article/details/gtwpmivnxd.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cashguo.top/Article/details/gtqteepqto.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yueranfly.top/Article/details/gtinhkcpdl.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yvedp.cn/Article/details/gthiypuvqm.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenjidiqi.icu/Article/details/gtnfkjhaok.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.fzhhl.top/Article/details/gtogvcckhi.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yj20258.top/Article/details/gtwvnsnhfh.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yvedp.cn/Article/details/gthxottsek.html

[B13] 判断是否为数字
来源：http://dali.nwbrower.top/Article/details/gtbxjweebs.html

Py:   isinstance(x, (int, float))
来源：http://dali.jyoumei.cn/Article/details/gtjietrddi.html

PHP:  is_numeric($x)
来源：http://dali.316326.xyz/Article/details/gtdmlspshs.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.c1oappe.top/Article/details/gtbfodskuz.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yvedp.cn/Article/details/gtcqlmfqeu.html

Java: x instanceof Number
来源：http://dali.cdnleiting.top/Article/details/gtitwnbqdw.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.0kj1m.cn/Article/details/gttpuivdvx.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jinqigufen.top/Article/details/gtbblgvqbk.html

C#:   x is int or double or decimal
来源：http://dali.cqqwz.cn/Article/details/gtwudkuzth.html

[B14] 判断值是否在集合内
来源：http://dali.shuidangran.top/Article/details/gtzhfnubvt.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shanyushiyangtech.top/Article/details/gtvfdusqjj.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.aibaodan.cn/Article/details/gtedjirkyc.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttwumtezd.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.chenlongwang.top/Article/details/gtodbxqxkt.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.gotoacloud.top/Article/details/gtihqnwrnz.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtucskkzvc.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhengqikj.top/Article/details/gtqvotjzsr.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hywenlv.cn/Article/details/gthnlzilgb.html

[B15] 布尔运算与取反
来源：http://dali.pengpengdd.cyou/Article/details/gtrheotbpx.html

Py:   a and b or not c
来源：http://dali.kuanghao11.cn/Article/details/gtgkxxxlvz.html

PHP:  $a && $b || !$c
来源：http://dali.feifeiyinyue.top/Article/details/gtipbmocvk.html

JS:   a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gtwteidwzb.html

TS:   a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gtwajaqzku.html

Java: a && b || !c
来源：http://dali.yuxming.cn/Article/details/gtetrdsniu.html

Go:   a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gtmwwemcgp.html

Ruby: a && b || !c
来源：http://dali.hammf.cn/Article/details/gtkexhknwi.html

C#:   a && b || !c
来源：http://dali.shuidangran.top/Article/details/gtbztpndnz.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.shzxlz.cn/Article/details/gtgvqfolse.html

Py:   if not data: return
来源：http://dali.zdqjudy.top/Article/details/gtpyuuaqmj.html

PHP:  if (!$data) { return; }
来源：http://dali.vqdsnc.cn/Article/details/gtnadorerk.html

JS:   if (!data) return;
来源：http://dali.c1oappe.top/Article/details/gtvrqcukwk.html

TS:   if (!data) return;
来源：http://dali.dianchejie.cn/Article/details/gtokoptnyn.html

Java: if (data == null) return;
来源：http://dali.tanke756.top/Article/details/gthffgcvua.html

Go:   if data == nil { return }
来源：http://dali.chenlongwang.top/Article/details/gtqceuzyfh.html

Ruby: return if data.nil?
来源：http://dali.jiagoushi.top/Article/details/gtrgvzdojq.html

C#:   if (data == null) return;
来源：http://dali.daxiang520.top/Article/details/gtmvutjzvh.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtfgdrmxay.html

C. 函数与作用域
来源：http://dali.sweek.top/Article/details/gteuxulats.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtoffanaow.html

[C01] 定义函数
来源：http://dali.pengpengdd.cyou/Article/details/gtjncahscb.html

Py:   def add(a, b): return a + b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcbvqosia.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sxryk.cn/Article/details/gtrfulvzoj.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtddbnoyet.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj20258.top/Article/details/gtcbcamgwc.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gtvwtrfxuv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsuczwgqy.html

Ruby: def add(a, b); a + b; end
来源：http://dali.vqdsnc.cn/Article/details/gtzyffrsna.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gtwuedxzzp.html

[C02] 默认参数
来源：http://dali.quarkkingdee.top/Article/details/gtjpipelcf.html

Py:   def greet(name="World"): return name
来源：http://dali.fzhhl.top/Article/details/gtwaedizxc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjixxbgds.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtleqieqns.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.fengsongda.top/Article/details/gtwkyohdab.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.kuanghao11.cn/Article/details/gtnwsttcjf.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yuanzhike.top/Article/details/gtvtrmyacf.html

Ruby: def greet(name = "World") = name
来源：http://dali.haohaochexian.top/Article/details/gtyveazzpb.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.kuanghao11.cn/Article/details/gtaxwdgmer.html

[C03] 可变参数
来源：http://dali.fzhhl.top/Article/details/gtdalqbhty.html

Py:   def total(*args): return sum(args)
来源：http://dali.yongpay.top/Article/details/gtdhpibujb.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.daria6918.cn/Article/details/gtxjeyxrsr.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.vqdsnc.cn/Article/details/gtebvrwotd.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.redwolf501.top/Article/details/gtidkptvyr.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.guowangkeji.top/Article/details/gtblpnshzx.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yj202588.top/Article/details/gttxvnyczh.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.bjfxy.top/Article/details/gttfrmrbwm.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hammf.cn/Article/details/gtgmzjnphj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.haohaochexian.top/Article/details/gtruofmblm.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhiwuduotai.top/Article/details/gtduahpqgf.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.meibo888.top/Article/details/gtgorgmtyd.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yuxming.cn/Article/details/gtuupkgmpt.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hongshengwenyu.top/Article/details/gtrvkuhfxy.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.guannengcc.top/Article/details/gtqerjpizt.html

Go:   // 无：用配置结构体参数
来源：http://dali.daxiang520.top/Article/details/gtwxtpipau.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hfpthk.cn/Article/details/gtiyyedyog.html

C#:   f(a: 1, b: 2)
来源：http://dali.gotoacloud.top/Article/details/gtbqmvsvdb.html

[C05] 返回多个值
来源：http://dali.meibo888.top/Article/details/gtnkhvnele.html

Py:   return a, b
来源：http://dali.xuetiantiany.cn/Article/details/gttwegoivo.html

PHP:  return [$a, $b];
来源：http://dali.feifeiyinyue.top/Article/details/gtkhymdubp.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yanxiufei.cn/Article/details/gtmmqnibzw.html

TS:   return { a, b };
来源：http://dali.yonumen.top/Article/details/gtqfohmyai.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shanyushiyangkeji.top/Article/details/gtshkqkhoy.html

Go:   return a, b
来源：http://dali.feifeiyinyue.top/Article/details/gtetjiefpe.html

Ruby: return a, b
来源：http://dali.haohaochexian.top/Article/details/gtwvuktgjc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.fzhhl.top/Article/details/gttcreoqij.html

[C06] 匿名函数 / lambda
来源：http://dali.hammf.cn/Article/details/gtqrwgvhtf.html

Py:   square = lambda x: x * x
来源：http://dali.ydzc1.top/Article/details/gtmuwjpefo.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zycfv.cn/Article/details/gtupnrdips.html

JS:   const square = x => x * x;
来源：http://dali.aizwys.cn/Article/details/gtpikeebfj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ydzc1.top/Article/details/gtlmswdief.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ydzc1.top/Article/details/gtoutdcgjm.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.gzhubu.top/Article/details/gtgnsyguej.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shuidangran.top/Article/details/gtmctlruoe.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjqoyyxfy.html

[C07] 把函数作为参数传入
来源：http://dali.jinghuilouyu.cn/Article/details/gtftpmnoiw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.c1oappe.top/Article/details/gtrjdvalat.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sufxvd.cn/Article/details/gtsfxrpljw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlsiuwlhy.html

TS:   arr.map(String)
来源：http://dali.birdmap.top/Article/details/gtpxzjhuym.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.haohaochexian.top/Article/details/gtrxvqvyrh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.chenlongwang.top/Article/details/gtzszdkkra.html

Ruby: arr.map(&:upcase)
来源：http://dali.feifeiyinyue.top/Article/details/gtzvhiqiya.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.fengsongda.top/Article/details/gtnygijglw.html

[C08] 闭包
来源：http://dali.yongpay.top/Article/details/gtsvocacrf.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.316326.xyz/Article/details/gtqczsqjpz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.tanke756.top/Article/details/gtniiufymc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hysaishi.cn/Article/details/gtcvhadcvm.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.havefunace.top/Article/details/gthmkowtds.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xylfe.cn/Article/details/gthhyauowf.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhongyouzk.top/Article/details/gtkraaxtzv.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yj20258.top/Article/details/gtogvtrhbz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnfcnfqim.html

[C09] 递归
来源：http://dali.jqgufenzy.top/Article/details/gtynljsccw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jlsjyb.cn/Article/details/gtiacjnpkm.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jlsjyb.cn/Article/details/gtyrlrnixy.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hysaishi.cn/Article/details/gtebjqscht.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtblduqgyk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yj20258888.top/Article/details/gtctqvdstu.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.svipenyu.cn/Article/details/gtnpxdkgmn.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ivvv.top/Article/details/gtdyohegak.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shuidangran.top/Article/details/gtxrggmylt.html

[C10] 变量作用域
来源：http://dali.ybcxt.top/Article/details/gtnpfflskq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.aibaodan.cn/Article/details/gtqrrccbmg.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xziqi.cn/Article/details/gtdhuzjdli.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.sysykeji.top/Article/details/gtwmuzkluk.html

TS:   同 JS
来源：http://dali.cdnleiting.top/Article/details/gtnlupgtlx.html

Java: 方法内为块级作用域
来源：http://dali.feifeiyinyue.top/Article/details/gtozhxqdiy.html

Go:   花括号块级作用域
来源：http://dali.hammf.cn/Article/details/gtxyefjbty.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.kuanghao11.cn/Article/details/gtfwynpjxe.html

C#:   块级作用域
来源：http://dali.havefunace.top/Article/details/gtvnnohbum.html

[C11] 模块导入与导出
来源：http://dali.yanxiufei.cn/Article/details/gtcgghruas.html

Py:   from module import func
来源：http://dali.gaohongyu789.top/Article/details/gtcnstakws.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yueranfly.top/Article/details/gtvgoyxtqd.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sweek.top/Article/details/gtzyhswrou.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.pycfn.com/Article/details/gtiwgwbprd.html

Java: import java.util.List;
来源：http://dali.nanxinkj.top/Article/details/gtdwvruxmo.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.gotoacloud.top/Article/details/gtdmjdrynh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cdnleiting.top/Article/details/gteryxhvga.html

C#:   using System.Text;
来源：http://dali.ehwqpu.com/Article/details/gtghrdwmwd.html

[C12] 立即执行函数 IIFE
来源：http://dali.xuetiantiany.cn/Article/details/gtkdgiudqs.html

Py:   (lambda: print("run"))()
来源：http://dali.zhoulong.xyz/Article/details/gtdgsllyws.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jyoumei.cn/Article/details/gtkelfqjzv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hongshengwenyu.top/Article/details/gtvudlawkl.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yangfankeji.com/Article/details/gtmebtehhs.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinqigfzy.top/Article/details/gtwfwlbeot.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hysaishi.cn/Article/details/gtnohwuuce.html

Ruby: -> { puts "run" }.call
来源：http://dali.andypj.xyz/Article/details/gtlbgrwtig.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jinqigufen.top/Article/details/gtvjxjhyko.html

[C13] 类型声明 / 类型注解
来源：http://dali.mhx1999.top/Article/details/gtyanttvdm.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.redwolf501.top/Article/details/gtndfkkmuf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.c1oappe.top/Article/details/gtwzmybtir.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.nwbrower.top/Article/details/gtrvxxnzag.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gtcavxslrl.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gttytzccbl.html

Go:   func add(a, b int) int
来源：http://dali.fzhhl.top/Article/details/gtvbqdvsho.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shanyushiyangtech.top/Article/details/gtqgrvmhcz.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zycfv.cn/Article/details/gtfznsfaid.html

[C14] 泛型函数
来源：http://dali.tianlin.xyz/Article/details/gthpnyzbhg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.9152youxi.cn/Article/details/gtayeefekg.html

PHP:  // 无泛型
来源：http://dali.yj20258.top/Article/details/gtoclmeyfs.html

JS:   // 无泛型
来源：http://dali.zhoulong.xyz/Article/details/gtwtiighqt.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xinyue.icu/Article/details/gtgbzgujti.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.haohaochexian.top/Article/details/gtwxkegpii.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.chenlongwang.top/Article/details/gtfodfwjdy.html

Ruby: # 无泛型
来源：http://dali.yonumen.top/Article/details/gtdrzlqrpw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shanyushiyangkeji.top/Article/details/gteiqljryl.html

[C15] 解构 / 展开参数
来源：http://dali.haohaochexian.top/Article/details/gtldaibxka.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hammf.cn/Article/details/gtiwlqbwbd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.iojbl.cn/Article/details/gtflmnmldi.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.haohaochexian.top/Article/details/gthdbktduf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.mhx1999.top/Article/details/gtmwawxctm.html

Java: // 无解构
来源：http://dali.birdmap.top/Article/details/gthzuhfdym.html

Go:   // 无解构
来源：http://dali.shangyingyoupin.top/Article/details/gtkjwpqlyn.html

Ruby: a, b = pair
来源：http://dali.andypj.xyz/Article/details/gtotrhxvzk.html

C#:   var (a, b) = pair;
来源：http://dali.fzhhl.top/Article/details/gtwdhkhxzl.html

[C16] 函数 / 方法重载
来源：http://dali.nanxuanxn.top/Article/details/gtyohxatfr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.mhx1999.top/Article/details/gtwjvltyol.html

PHP:  // 无重载
来源：http://dali.andypj.xyz/Article/details/gtrqglcvbp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jqgufenzy.top/Article/details/gtzcgpciqp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.meibo888.top/Article/details/gtuxmtsmzh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xziqi.cn/Article/details/gtbnuwjaag.html

Go:   // 无重载：用不同函数名
来源：http://dali.yj202588.top/Article/details/gtzzkdlfju.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhixingplan.top/Article/details/gtnjbwwwac.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.snrcjt.cn/Article/details/gtzcqufvpc.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtenyphson.html

D. 数组 / 列表 / 集合
来源：http://dali.wangdashe.top/Article/details/gtpsbmhwwp.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtfjaasnng.html

[D01] 创建数组 / 列表
来源：http://dali.jqgfzy.top/Article/details/gtfzkudsqe.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhaomingkeji.xyz/Article/details/gtufxgpfni.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cashguo.top/Article/details/gtzocndgwd.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.0kj1m.cn/Article/details/gtbmpcjfqx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cqqwz.cn/Article/details/gthvjjsfzc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.wangdashe.top/Article/details/gtgdujxqwf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ivvv.top/Article/details/gtqltnrpnj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hongshengwenyu.top/Article/details/gtlghhvfou.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shanyushiyangtech.top/Article/details/gtfigekrmd.html

[D02] 追加元素到末尾
来源：http://dali.hysaishi.cn/Article/details/gtknfesuqz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yuanzhike.top/Article/details/gtlfzxvrcj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhixingplan.top/Article/details/gteiogaqrq.html

JS:   arr.push(4);
来源：http://dali.meibo888.top/Article/details/gtetotzjpp.html

TS:   arr.push(4);
来源：http://dali.xinyue.icu/Article/details/gtvqyytzut.html

Java: list.add(4);
来源：http://dali.jqgufenzy.top/Article/details/gtfayotqoo.html

Go:   arr = append(arr, 4)
来源：http://dali.shzxlz.cn/Article/details/gtsjhqitjw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yuxming.cn/Article/details/gtsxsunkqf.html

C#:   list.Add(4);
来源：http://dali.wangdashe.top/Article/details/gtahuxhdnu.html

[D03] 在指定位置插入元素
来源：http://dali.mhx1999.top/Article/details/gtvwvygfpx.html

Py:   arr.insert(0, 0)
来源：http://dali.chenlongwang.top/Article/details/gtxpohuzrp.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.gzhubu.top/Article/details/gtpctrjxsj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.vqdsnc.cn/Article/details/gtpupbzukg.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxvypoilw.html

Java: list.add(0, 0);
来源：http://dali.havefunace.top/Article/details/gtjfhlvxxl.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.svipenyu.cn/Article/details/gtfhlfolre.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenlongwang.top/Article/details/gtplazvwes.html

C#:   list.Insert(0, 0);
来源：http://dali.jinqigfzy.top/Article/details/gtoaejblom.html

[D04] 删除元素
来源：http://dali.iojbl.cn/Article/details/gtyjtyxtbk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.kuanghao11.cn/Article/details/gtoomslceg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sufxvd.cn/Article/details/gtfxtnntye.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.snrcjt.cn/Article/details/gtyblypbql.html

TS:   arr.splice(0, 1);
来源：http://dali.gogol.net.cn/Article/details/gtqyvigbdq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.0kj1m.cn/Article/details/gtliqcjnvw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ybcxt.top/Article/details/gtosuldsng.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.pycfn.com/Article/details/gtqovgpxmb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtclqxzqty.html

[D05] 访问与修改元素
来源：http://dali.sysykeji.top/Article/details/gtulkcrobn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.fengsongda.top/Article/details/gtmvdkjplp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sysykeji.top/Article/details/gtipjqjqup.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gtkgcamtzv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.havefunace.top/Article/details/gtnpbslvsq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cdnleiting.top/Article/details/gtebqrxpyp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfmrubbyn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgfzy.top/Article/details/gtdalmcsry.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yuxming.cn/Article/details/gtwxqlkoqn.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gtinuyrvnp.html

Py:   len(arr)
来源：http://dali.ydzc1.top/Article/details/gtzirsazqj.html

PHP:  count($arr);
来源：http://dali.daria6918.cn/Article/details/gtbcmixghm.html

JS:   arr.length
来源：http://dali.guowangkeji.top/Article/details/gtmpvleqey.html

TS:   arr.length
来源：http://dali.quarkkingdee.top/Article/details/gtrnkpujaq.html

Java: list.size();
来源：http://dali.tianlin.xyz/Article/details/gtnnlyhnbg.html

Go:   len(arr)
来源：http://dali.pycfn.com/Article/details/gtpwryxshz.html

Ruby: arr.length; arr.size
来源：http://dali.yj202588.top/Article/details/gtkdzsfewu.html

C#:   list.Count;
来源：http://dali.sweek.top/Article/details/gtntjiwwbb.html

[D07] 切片 / 取子数组
来源：http://dali.chenjidiqi.icu/Article/details/gtoetegpkw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.havefunace.top/Article/details/gtdpdrsukm.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.haohaochexian.top/Article/details/gtovekuejh.html

JS:   arr.slice(1, 4);
来源：http://dali.ydzc1.top/Article/details/gtqqtsnjqt.html

TS:   arr.slice(1, 4);
来源：http://dali.sufxvd.cn/Article/details/gtiuirqybp.html

Java: list.subList(1, 4);
来源：http://dali.cqqwz.cn/Article/details/gtqfttedey.html

Go:   arr[1:4]
来源：http://dali.kuanghao11.cn/Article/details/gtkqypanog.html

Ruby: arr[1, 3]
来源：http://dali.xuanzx.com/Article/details/gtfktrfwml.html

C#:   list.GetRange(1, 3);
来源：http://dali.iojbl.cn/Article/details/gtqsmuvfwe.html

[D08] 合并两个数组
来源：http://dali.cdnleiting.top/Article/details/gtdzhzdygb.html

Py:   a + b;  a.extend(b)
来源：http://dali.nanxinkj.top/Article/details/gttilkbrqb.html

PHP:  array_merge($a, $b);
来源：http://dali.birdmap.top/Article/details/gtvueecsda.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.smart0.xyz/Article/details/gtvahjqisw.html

TS:   [...a, ...b];
来源：http://dali.bjfxy.top/Article/details/gtazswbjpp.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xuanzx.com/Article/details/gtynwtubnj.html

Go:   append(a, b...)
来源：http://dali.ppjwa.cn/Article/details/gtcwnjzfkb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hywenlv.cn/Article/details/gtxkwckwmo.html

C#:   a.Concat(b).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttbxvinsz.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gtrvomdgkj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sweek.top/Article/details/gtbglkjdlw.html

PHP:  sort($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtxymiqldz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.bjfxy.top/Article/details/gtokxddhcg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.tanke756.top/Article/details/gtufanndzd.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cashguo.top/Article/details/gtrlrdcvvv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yonumen.top/Article/details/gtyqdjpijx.html

Ruby: arr.sort
来源：http://dali.svipenyu.cn/Article/details/gtfplrzrbv.html

C#:   list.Sort();
来源：http://dali.zycfv.cn/Article/details/gttvmlfnqz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.bjfxy.top/Article/details/gtgpxzxsec.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.nanxinkj.top/Article/details/gtudnfbrgk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.meibo888.top/Article/details/gtbbwwdbqi.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.snrcjt.cn/Article/details/gtyehohdbd.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.redwolf501.top/Article/details/gtvlxeeklc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.tian-w.cn/Article/details/gtjsvetsem.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ivvv.top/Article/details/gtpnzkmnpq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hywenlv.cn/Article/details/gtjhaedfiu.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinghuilouyu.cn/Article/details/gtazzcigrh.html

[D11] 反转数组
来源：http://dali.yongpay.top/Article/details/gtspbflduu.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtahxfwnlr.html

PHP:  array_reverse($arr);
来源：http://dali.tanke756.top/Article/details/gtdzqdlcps.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zycfv.cn/Article/details/gtqozoaqoc.html

TS:   [...arr].reverse();
来源：http://dali.cashguo.top/Article/details/gtqrdkwfwn.html

Java: Collections.reverse(list);
来源：http://dali.ivvv.top/Article/details/gthpmyirtt.html

Go:   slices.Reverse(arr)
来源：http://dali.sweek.top/Article/details/gtyntougeq.html

Ruby: arr.reverse
来源：http://dali.hfpthk.cn/Article/details/gtpmqrqcia.html

C#:   list.Reverse();
来源：http://dali.sxryk.cn/Article/details/gtvjnheobf.html

[D12] 查找元素下标
来源：http://dali.zdqjudy.top/Article/details/gtrehvsiqj.html

Py:   arr.index(x);  x in arr
来源：http://dali.svipenyu.cn/Article/details/gtvxxwoxbh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtsupxafih.html


<!-- 参考信息 -->