代发 wailian999

PHP:  range(0, 10, 2);
来源：http://dali.ppjwa.cn/Article/details/gtobammdur.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.0kj1m.cn/Article/details/gtggxqlmep.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.kuanghao11.cn/Article/details/gtwewanaao.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.shzxlz.cn/Article/details/gtvkqelzjs.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.tian-w.cn/Article/details/gtgavridgj.html

Ruby: (0...10).step(2).to_a
来源：http://dali.shangyingyoupin.top/Article/details/gtelbsgkpx.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.havefunace.top/Article/details/gtbanflnab.html

[B12] 跳出多层循环
来源：http://dali.yj20258888.top/Article/details/gttzzgapmp.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.c1oappe.top/Article/details/gtiasmmeoq.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.shzxlz.cn/Article/details/gtycnpprtd.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenlongwang.top/Article/details/gtetyjenro.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hongshengwenyu.top/Article/details/gtodtqchqa.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenlongwang.top/Article/details/gtpuymmyyx.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jyoumei.cn/Article/details/gtkrpnnezc.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yonumen.top/Article/details/gtryruawcx.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yvedp.cn/Article/details/gtgzkymhvu.html

[B13] 判断是否为数字
来源：http://dali.ydzc1.top/Article/details/gtswkpllpd.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhongyouzk.top/Article/details/gtgkbzrlhm.html

PHP:  is_numeric($x)
来源：http://dali.vqdsnc.cn/Article/details/gtendlqhik.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cheryme.top/Article/details/gtubnbkjhm.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.snrcjt.cn/Article/details/gtxulvuhqe.html

Java: x instanceof Number
来源：http://dali.fengsongda.top/Article/details/gtqvvxvilu.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.0kj1m.cn/Article/details/gtcukbfpbt.html

Ruby: x.is_a?(Numeric)
来源：http://dali.mhx1999.top/Article/details/gtpsbetkaj.html

C#:   x is int or double or decimal
来源：http://dali.ybcxt.top/Article/details/gtjsuodgmx.html

[B14] 判断值是否在集合内
来源：http://dali.cdnleiting.top/Article/details/gtzqnmyphg.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.haohaochexian.top/Article/details/gtwpbzzqyd.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.chenlongwang.top/Article/details/gtnxqvnvtm.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.gzhubu.top/Article/details/gtdxxopabv.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtfxritkwj.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.sysykeji.top/Article/details/gttdnhylta.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtoflppvhm.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.nanxinkj.top/Article/details/gtsgajkhty.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gtfjmztlro.html

[B15] 布尔运算与取反
来源：http://dali.birdmap.top/Article/details/gtrgugfssp.html

Py:   a and b or not c
来源：http://dali.zdqjudy.top/Article/details/gtiklozhge.html

PHP:  $a && $b || !$c
来源：http://dali.andypj.xyz/Article/details/gtmbfdwyna.html

JS:   a && b || !c
来源：http://dali.yueranfly.top/Article/details/gtptkjylre.html

TS:   a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gttbvwduth.html

Java: a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gtlnhpodpk.html

Go:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtbqpkbmdy.html

Ruby: a && b || !c
来源：http://dali.gzhubu.top/Article/details/gtzwvaidbs.html

C#:   a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gtuzdvuive.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cheryme.top/Article/details/gtphinbbab.html

Py:   if not data: return
来源：http://dali.shuidangran.top/Article/details/gtimwwlvzl.html

PHP:  if (!$data) { return; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttvglokae.html

JS:   if (!data) return;
来源：http://dali.haohaochexian.top/Article/details/gtsjsnmtzt.html

TS:   if (!data) return;
来源：http://dali.jianghu66.top/Article/details/gtypfnjizl.html

Java: if (data == null) return;
来源：http://dali.cheryme.top/Article/details/gtctpceyqa.html

Go:   if data == nil { return }
来源：http://dali.yangfankeji.com/Article/details/gtxuahpyws.html

Ruby: return if data.nil?
来源：http://dali.birdmap.top/Article/details/gtcvpsvakx.html

C#:   if (data == null) return;
来源：http://dali.sysykeji.top/Article/details/gtddhvkrud.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtfrhydfan.html

C. 函数与作用域
来源：http://dali.hammf.cn/Article/details/gtjdgodfux.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtczedwtpv.html

[C01] 定义函数
来源：http://dali.316326.xyz/Article/details/gtlptfngkj.html

Py:   def add(a, b): return a + b
来源：http://dali.kuanghao11.cn/Article/details/gtrzjffheg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tian-w.cn/Article/details/gtltkotnas.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gtonsuhobk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtmeihpbma.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtnwdevzjp.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ivvv.top/Article/details/gtlrmmvbng.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shangyingyoupin.top/Article/details/gtbkskyyge.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtjhpoveeq.html

[C02] 默认参数
来源：http://dali.jinqigfzy.top/Article/details/gtbgxzfamr.html

Py:   def greet(name="World"): return name
来源：http://dali.cashguo.top/Article/details/gtzfdejsmi.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.sxryk.cn/Article/details/gtsxnreldz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gthsqbbrxl.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.sufxvd.cn/Article/details/gtkmvxvary.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zdqjudy.top/Article/details/gtpubrspie.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.nanxinkj.top/Article/details/gtjqssfxox.html

Ruby: def greet(name = "World") = name
来源：http://dali.iojbl.cn/Article/details/gtuhlfvegr.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.sysykeji.top/Article/details/gtguecsfen.html

[C03] 可变参数
来源：http://dali.aizwys.cn/Article/details/gtpavgzpeg.html

Py:   def total(*args): return sum(args)
来源：http://dali.ydzc1.top/Article/details/gtulqohfvu.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.tanke756.top/Article/details/gtodshiovs.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xylfe.cn/Article/details/gtfoiuqobu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258888.top/Article/details/gtelmvmgup.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.aibaodan.cn/Article/details/gtyrldzlkg.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ivvv.top/Article/details/gthvokcaez.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ybcxt.top/Article/details/gttazrzurw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xuanzx.com/Article/details/gtqqhthahz.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jiagoushi.top/Article/details/gthekufsib.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.andypj.xyz/Article/details/gtandclexi.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.daxiang520.top/Article/details/gtzgexzoll.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.snrcjt.cn/Article/details/gtexypcdvp.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.sxryk.cn/Article/details/gtfwrhxlws.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yuxming.cn/Article/details/gtqipqrflc.html

Go:   // 无：用配置结构体参数
来源：http://dali.jlsjyb.cn/Article/details/gtnicusnph.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jianghu66.top/Article/details/gtklfkmnjz.html

C#:   f(a: 1, b: 2)
来源：http://dali.daxiang520.top/Article/details/gtjhutgfve.html

[C05] 返回多个值
来源：http://dali.meibo888.top/Article/details/gtrlgtnruz.html

Py:   return a, b
来源：http://dali.yuanzhike.top/Article/details/gtngljeyvs.html

PHP:  return [$a, $b];
来源：http://dali.havefunace.top/Article/details/gteqelgwxx.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yj20258.top/Article/details/gtqwlitles.html

TS:   return { a, b };
来源：http://dali.ppjwa.cn/Article/details/gtygqbguqk.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.nwbrower.top/Article/details/gtcqvfouym.html

Go:   return a, b
来源：http://dali.guowangkeji.top/Article/details/gteeelzhxi.html

Ruby: return a, b
来源：http://dali.zhengqikj.top/Article/details/gttlenkcqu.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cashguo.top/Article/details/gtltfspikl.html

[C06] 匿名函数 / lambda
来源：http://dali.xylfe.cn/Article/details/gtxmdtulvz.html

Py:   square = lambda x: x * x
来源：http://dali.gotoacloud.top/Article/details/gtfdsfcixn.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.guowangkeji.top/Article/details/gtzqtxvnlk.html

JS:   const square = x => x * x;
来源：http://dali.hywenlv.cn/Article/details/gtqmintqsl.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.meibo888.top/Article/details/gtxbhkbyfx.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xziqi.cn/Article/details/gtvzuatcvl.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtocdahkec.html

Ruby: square = ->(x) { x * x }
来源：http://dali.fengsongda.top/Article/details/gtkcyygofb.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cqqwz.cn/Article/details/gtrzekqgeb.html

[C07] 把函数作为参数传入
来源：http://dali.wangdashe.top/Article/details/gtybzjhztl.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.iojbl.cn/Article/details/gtybnnrggo.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.ivvv.top/Article/details/gtlpqcttli.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hammf.cn/Article/details/gtiwctbfhy.html

TS:   arr.map(String)
来源：http://dali.bjfxy.top/Article/details/gttcjqepzc.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.dashuyun.cn/Article/details/gtmenvcghh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhengqikj.top/Article/details/gtdzhisxya.html

Ruby: arr.map(&:upcase)
来源：http://dali.daria6918.cn/Article/details/gtmprigjcn.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.guannengcc.top/Article/details/gtzatwxvrn.html

[C08] 闭包
来源：http://dali.shanyushiyangtech.top/Article/details/gtzzqemzhv.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gtfqaderme.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.dashuyun.cn/Article/details/gtfhsymhki.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhengqikj.top/Article/details/gtowkthcvf.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhengqikj.top/Article/details/gtjonuyjcu.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.andypj.xyz/Article/details/gtxykeyokc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.svipenyu.cn/Article/details/gtjcfonczr.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hysaishi.cn/Article/details/gtudhcmgdp.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jianghu66.top/Article/details/gtbkqnemhu.html

[C09] 递归
来源：http://dali.mhx1999.top/Article/details/gtviiggbkg.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.gzhubu.top/Article/details/gtryrxoiut.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jianghu66.top/Article/details/gtqpwytfgs.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gaohongyu789.top/Article/details/gtwyuyiylp.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.c1oappe.top/Article/details/gtepoxwexs.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zdqjudy.top/Article/details/gtozhjrxoi.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.chenlongwang.top/Article/details/gtkhytlfqq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.guannengcc.top/Article/details/gtseopvfye.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yangfankeji.com/Article/details/gtwhfyaofy.html

[C10] 变量作用域
来源：http://dali.xziqi.cn/Article/details/gthqtfbqpc.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jqgufenzy.top/Article/details/gtntbqukcp.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinqigufen.top/Article/details/gtfvumogqy.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.quarkkingdee.top/Article/details/gthitreaio.html

TS:   同 JS
来源：http://dali.xziqi.cn/Article/details/gtrnweross.html

Java: 方法内为块级作用域
来源：http://dali.redwolf501.top/Article/details/gtyaqusrla.html

Go:   花括号块级作用域
来源：http://dali.andypj.xyz/Article/details/gthgsesmba.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.iojbl.cn/Article/details/gtsavmqlfn.html

C#:   块级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrawtwsvj.html

[C11] 模块导入与导出
来源：http://dali.ehwqpu.com/Article/details/gtnllxjozj.html

Py:   from module import func
来源：http://dali.xziqi.cn/Article/details/gtmndnipbp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.snrcjt.cn/Article/details/gtzfuycszq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtikjnhwth.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhengqikj.top/Article/details/gtbjhhiaps.html

Java: import java.util.List;
来源：http://dali.fzhhl.top/Article/details/gtttesnolt.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shuidangran.top/Article/details/gtvduokmmk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xziqi.cn/Article/details/gtqortyure.html

C#:   using System.Text;
来源：http://dali.daria6918.cn/Article/details/gtdudlvycl.html

[C12] 立即执行函数 IIFE
来源：http://dali.hnqzz.top/Article/details/gttlzgemzj.html

Py:   (lambda: print("run"))()
来源：http://dali.zhongyouzk.top/Article/details/gtiqxltltk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.tian-w.cn/Article/details/gthsuvpcns.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinghuilouyu.cn/Article/details/gtnlmlxfgz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jqgfzy.top/Article/details/gtpmveyyha.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cucudq.cn/Article/details/gtiiyedpqk.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shanyushiyangtech.top/Article/details/gtuxeebcwo.html

Ruby: -> { puts "run" }.call
来源：http://dali.yueranfly.top/Article/details/gtzmpzsvgo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.birdmap.top/Article/details/gtvfmcbzyo.html

[C13] 类型声明 / 类型注解
来源：http://dali.redwolf501.top/Article/details/gtmfdfgqau.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.vqdsnc.cn/Article/details/gtqcidrhsf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenzaomai.com/Article/details/gtiwmkigaa.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.pengpengdd.cyou/Article/details/gtygyiquzi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtndmgwwfl.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gthfvuoyvc.html

Go:   func add(a, b int) int
来源：http://dali.shzxlz.cn/Article/details/gtpdjojaos.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.smart0.xyz/Article/details/gtuydsxoqy.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yanxiufei.cn/Article/details/gtkwoungqx.html

[C14] 泛型函数
来源：http://dali.sxryk.cn/Article/details/gtysqbpbog.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jqgfzy.top/Article/details/gtnfjyhhjj.html

PHP:  // 无泛型
来源：http://dali.xylfe.cn/Article/details/gtuklpmvga.html

JS:   // 无泛型
来源：http://dali.yvedp.cn/Article/details/gtpuubtfrz.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yonumen.top/Article/details/gttintgjry.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.aizwys.cn/Article/details/gtpvlbnhkb.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zdqjudy.top/Article/details/gtrhmautyf.html

Ruby: # 无泛型
来源：http://dali.yueranfly.top/Article/details/gtevwiqtam.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yonumen.top/Article/details/gtyfahyfxb.html

[C15] 解构 / 展开参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbleipyhb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jqgufenzy.top/Article/details/gtfckxzenr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ehwqpu.com/Article/details/gtxhvmnhwd.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtdkefnmut.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtttgbhelk.html

Java: // 无解构
来源：http://dali.ybcxt.top/Article/details/gtowmgdkjy.html

Go:   // 无解构
来源：http://dali.sweek.top/Article/details/gtvyeijcke.html

Ruby: a, b = pair
来源：http://dali.daria6918.cn/Article/details/gtpwssyvdl.html

C#:   var (a, b) = pair;
来源：http://dali.hnxiangtu.top/Article/details/gtqlevkgbg.html

[C16] 函数 / 方法重载
来源：http://dali.snrcjt.cn/Article/details/gtjtagjlre.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.birdmap.top/Article/details/gtejhkgtgy.html

PHP:  // 无重载
来源：http://dali.vqdsnc.cn/Article/details/gtambmupic.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jlsjyb.cn/Article/details/gtddoftdal.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.nwbrower.top/Article/details/gtfnukfkdm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.daria6918.cn/Article/details/gtlxucxmrp.html

Go:   // 无重载：用不同函数名
来源：http://dali.andypj.xyz/Article/details/gtmpovujpg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhongyouzk.top/Article/details/gtyvnkuqvj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gaohongyu789.top/Article/details/gthcspwldm.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtqikwprux.html

D. 数组 / 列表 / 集合
来源：http://dali.xziqi.cn/Article/details/gtifqockbk.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtqqlzssbj.html

[D01] 创建数组 / 列表
来源：http://dali.zhengqikj.top/Article/details/gtlxicbtvz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yuanzhike.top/Article/details/gtobvlznxx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hfpthk.cn/Article/details/gtfecsbvyg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.kuanghao11.cn/Article/details/gtmsxidqoj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jlsjyb.cn/Article/details/gtgogfilqe.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yvedp.cn/Article/details/gtdymycgpi.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.aizwys.cn/Article/details/gtxfsrvfin.html

Ruby: arr = [1, 2, 3]
来源：http://dali.aizwys.cn/Article/details/gtubfofcpw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhiwuduotai.top/Article/details/gtdafsbtlr.html

[D02] 追加元素到末尾
来源：http://dali.yangfankeji.com/Article/details/gtijghrcqz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsmaaunob.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.pycfn.com/Article/details/gtyfacqvds.html

JS:   arr.push(4);
来源：http://dali.zdqjudy.top/Article/details/gtzyymvwkm.html

TS:   arr.push(4);
来源：http://dali.wangdashe.top/Article/details/gtfaryekwf.html

Java: list.add(4);
来源：http://dali.daxiang520.top/Article/details/gtlbszssrc.html

Go:   arr = append(arr, 4)
来源：http://dali.0kj1m.cn/Article/details/gtavclrtzo.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hfpthk.cn/Article/details/gtokbauzcr.html

C#:   list.Add(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrgegyksr.html

[D03] 在指定位置插入元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtywafjjqk.html

Py:   arr.insert(0, 0)
来源：http://dali.birdmap.top/Article/details/gtgunsqvfo.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hongshengwenyu.top/Article/details/gtgyyafcqb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.iojbl.cn/Article/details/gtrocxpfxq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hnxiangtu.top/Article/details/gtmyxsnten.html

Java: list.add(0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmfmzbwoq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.chenjidiqi.icu/Article/details/gtocljisup.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.nwbrower.top/Article/details/gtslamjwga.html

C#:   list.Insert(0, 0);
来源：http://dali.yonumen.top/Article/details/gtuuyjrzfp.html

[D04] 删除元素
来源：http://dali.pycfn.com/Article/details/gtscqzruuq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cucudq.cn/Article/details/gtrtlkiurj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yuxming.cn/Article/details/gtbatxhida.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.mhx1999.top/Article/details/gtnairnclr.html

TS:   arr.splice(0, 1);
来源：http://dali.chenzaomai.com/Article/details/gtlvotphqv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hywenlv.cn/Article/details/gtuelgiikw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xuetiantiany.cn/Article/details/gtnorqtiae.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtahkrdwqd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hysaishi.cn/Article/details/gtcnnftdas.html

[D05] 访问与修改元素
来源：http://dali.cucudq.cn/Article/details/gtjzqnkpil.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ivvv.top/Article/details/gtfugsbipz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.gogol.net.cn/Article/details/gtapbydcgr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hongshengwenyu.top/Article/details/gtyrhrxwqy.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gotoacloud.top/Article/details/gtmvvnhqer.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.nanxuanxn.top/Article/details/gtuhdcjbsy.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqzweysyo.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yongpay.top/Article/details/gtlilwhldb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ppjwa.cn/Article/details/gtrpirisws.html

[D06] 数组长度
来源：http://dali.xylfe.cn/Article/details/gthkxqbgsy.html

Py:   len(arr)
来源：http://dali.ivvv.top/Article/details/gtebzpnuen.html

PHP:  count($arr);
来源：http://dali.sweek.top/Article/details/gtpaahicpl.html

JS:   arr.length
来源：http://dali.ydzc1.top/Article/details/gtngsvyvwi.html

TS:   arr.length
来源：http://dali.dianchejie.cn/Article/details/gtktoestxl.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gtitxqmrri.html

Go:   len(arr)
来源：http://dali.ehwqpu.com/Article/details/gtusjbtpqj.html

Ruby: arr.length; arr.size
来源：http://dali.zhoulong.xyz/Article/details/gtstwlwtrc.html

C#:   list.Count;
来源：http://dali.aibaodan.cn/Article/details/gtfhitwujh.html

[D07] 切片 / 取子数组
来源：http://dali.chenlongwang.top/Article/details/gtyrasigyw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.mhx1999.top/Article/details/gtiaiadsuw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cdnleiting.top/Article/details/gtgiqfysfx.html

JS:   arr.slice(1, 4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtntvplsiz.html

TS:   arr.slice(1, 4);
来源：http://dali.zhongyouzk.top/Article/details/gtzdpggryx.html

Java: list.subList(1, 4);
来源：http://dali.dashuyun.cn/Article/details/gtqiyxhgpg.html

Go:   arr[1:4]
来源：http://dali.wangdashe.top/Article/details/gtypdkwgga.html

Ruby: arr[1, 3]
来源：http://dali.xylfe.cn/Article/details/gtbyzoqspw.html

C#:   list.GetRange(1, 3);
来源：http://dali.quarkkingdee.top/Article/details/gtbbgdwlir.html

[D08] 合并两个数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtykwnojrg.html

Py:   a + b;  a.extend(b)
来源：http://dali.hywenlv.cn/Article/details/gtnkovqrev.html

PHP:  array_merge($a, $b);
来源：http://dali.meibo888.top/Article/details/gtpvolipxg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhoulong.xyz/Article/details/gtfssvlxet.html

TS:   [...a, ...b];
来源：http://dali.daria6918.cn/Article/details/gtrnefgiot.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yuanzhike.top/Article/details/gtzhjntmtu.html

Go:   append(a, b...)
来源：http://dali.sxryk.cn/Article/details/gtxunatybp.html

Ruby: a + b;  a.concat(b)
来源：http://dali.smart0.xyz/Article/details/gtfaqoysmp.html

C#:   a.Concat(b).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtwtttabpx.html

[D09] 排序（升序）
来源：http://dali.guowangkeji.top/Article/details/gttscvhgkv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yongpay.top/Article/details/gtilzvlduc.html

PHP:  sort($arr);
来源：http://dali.ppjwa.cn/Article/details/gtbfyvorkc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.aizwys.cn/Article/details/gtzptcrdes.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinghuilouyu.cn/Article/details/gtwjdwvqel.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenlongwang.top/Article/details/gtxfcuqkag.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hysaishi.cn/Article/details/gtdpaxfqon.html

Ruby: arr.sort
来源：http://dali.gogol.net.cn/Article/details/gtgynjqxsh.html

C#:   list.Sort();
来源：http://dali.cqqwz.cn/Article/details/gtfljeoxns.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yueranfly.top/Article/details/gtdbawyfym.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ivvv.top/Article/details/gtszrzkjfy.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.redwolf501.top/Article/details/gtcrvfgzac.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dashuyun.cn/Article/details/gtopbbimhd.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.quarkkingdee.top/Article/details/gturixdedr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinghuilouyu.cn/Article/details/gtgwsndfth.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.nanxuanxn.top/Article/details/gttaobzara.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.chenzaomai.com/Article/details/gtrgyfyyvr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jqgfzy.top/Article/details/gtvwnvjxxu.html

[D11] 反转数组
来源：http://dali.yanxiufei.cn/Article/details/gtrumkspqq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jinqigfzy.top/Article/details/gtckklazrk.html

PHP:  array_reverse($arr);
来源：http://dali.meibo888.top/Article/details/gtxbakkcza.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhoulong.xyz/Article/details/gtmcunojym.html

TS:   [...arr].reverse();
来源：http://dali.ivvv.top/Article/details/gtywdqytcb.html

Java: Collections.reverse(list);
来源：http://dali.9152youxi.cn/Article/details/gtucqrrkij.html

Go:   slices.Reverse(arr)
来源：http://dali.ydzc1.top/Article/details/gtbixscjgm.html

Ruby: arr.reverse
来源：http://dali.cdnleiting.top/Article/details/gtkzbahgkx.html


<!-- 参考信息 -->