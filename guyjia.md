代发 wailian999

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.xuetiantiany.cn/Article/details/gtblatrpnb.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jinghuilouyu.cn/Article/details/gthvhbonsp.html

[B11] 生成数字序列 / 区间
来源：http://dali.316326.xyz/Article/details/gtvpeelqbf.html

Py:   list(range(0, 10, 2))
来源：http://dali.xylfe.cn/Article/details/gtbjtxigcf.html

PHP:  range(0, 10, 2);
来源：http://dali.xinyue.icu/Article/details/gtgfibreev.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shzxlz.cn/Article/details/gtitbagaii.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbgklziwu.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.tian-w.cn/Article/details/gtdkdmgspu.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.tian-w.cn/Article/details/gtlbdshsfl.html

Ruby: (0...10).step(2).to_a
来源：http://dali.guannengcc.top/Article/details/gtrzskgaih.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.9152youxi.cn/Article/details/gtwhawplvl.html

[B12] 跳出多层循环
来源：http://dali.daria6918.cn/Article/details/gtdksxvcbt.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jinyuanbaomall.cn/Article/details/gthkwdvtcv.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cheryme.top/Article/details/gtxhqtpawm.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gotoacloud.top/Article/details/gtvovnilxq.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shzxlz.cn/Article/details/gtpcpgajcx.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.birdmap.top/Article/details/gtaeynsvjl.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yongpay.top/Article/details/gtysgvexyc.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.cqqwz.cn/Article/details/gtzecocwgv.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.daxiang520.top/Article/details/gtitprprfn.html

[B13] 判断是否为数字
来源：http://dali.pycfn.com/Article/details/gthtjcdaye.html

Py:   isinstance(x, (int, float))
来源：http://dali.xuanzx.com/Article/details/gtclabzpgb.html

PHP:  is_numeric($x)
来源：http://dali.aibaodan.cn/Article/details/gtaaqqvcmh.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ehwqpu.com/Article/details/gtbaxyusyk.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zycfv.cn/Article/details/gtsqxptzau.html

Java: x instanceof Number
来源：http://dali.iojbl.cn/Article/details/gtezfszvvp.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cdnleiting.top/Article/details/gthjpxdsae.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zycfv.cn/Article/details/gtplfjsast.html

C#:   x is int or double or decimal
来源：http://dali.xziqi.cn/Article/details/gtannffkfm.html

[B14] 判断值是否在集合内
来源：http://dali.hongshengwenyu.top/Article/details/gtdvizlnhk.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cashguo.top/Article/details/gtaamiqvrn.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.daxiang520.top/Article/details/gtkxynmfyg.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsdsoqexk.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gtleblusur.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwnymafvi.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yuanzhike.top/Article/details/gtklwacfxo.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xylfe.cn/Article/details/gtailugwyt.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gtwnovwewl.html

[B15] 布尔运算与取反
来源：http://dali.jqgufenzy.top/Article/details/gtopiufbbo.html

Py:   a and b or not c
来源：http://dali.chenzaomai.com/Article/details/gtzttkemdu.html

PHP:  $a && $b || !$c
来源：http://dali.dianchejie.cn/Article/details/gtnkgdjqnv.html

JS:   a && b || !c
来源：http://dali.tian-w.cn/Article/details/gtuaibkaoy.html

TS:   a && b || !c
来源：http://dali.birdmap.top/Article/details/gtdtwkpkai.html

Java: a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gthwnydmim.html

Go:   a && b || !c
来源：http://dali.birdmap.top/Article/details/gteonhaxnp.html

Ruby: a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnnuwoqto.html

C#:   a && b || !c
来源：http://dali.tianlin.xyz/Article/details/gtysghvhpk.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.pycfn.com/Article/details/gtexqkcfrs.html

Py:   if not data: return
来源：http://dali.birdmap.top/Article/details/gtpnkpqxwy.html

PHP:  if (!$data) { return; }
来源：http://dali.tianlin.xyz/Article/details/gtuxzcqqwm.html

JS:   if (!data) return;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtftastnyk.html

TS:   if (!data) return;
来源：http://dali.smart0.xyz/Article/details/gtrdeoimqv.html

Java: if (data == null) return;
来源：http://dali.wangdashe.top/Article/details/gtadbbomrx.html

Go:   if data == nil { return }
来源：http://dali.xuetiantiany.cn/Article/details/gtovynythp.html

Ruby: return if data.nil?
来源：http://dali.zdqjudy.top/Article/details/gtasmnzufx.html

C#:   if (data == null) return;
来源：http://dali.shangyingyoupin.top/Article/details/gtadxbygam.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtivogsujs.html

C. 函数与作用域
来源：http://dali.zhixingplan.top/Article/details/gtwapgodpz.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtaemmfzql.html

[C01] 定义函数
来源：http://dali.jqgfzy.top/Article/details/gtmyiimdii.html

Py:   def add(a, b): return a + b
来源：http://dali.bjfxy.top/Article/details/gtrudxrqfo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gtpixprxjz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gttjkehvmg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tanke756.top/Article/details/gtdyfxfjad.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gtwvnjenak.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.gzhubu.top/Article/details/gtiinnnfyu.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xylfe.cn/Article/details/gtwsvzwnfx.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gtiqxmbhyx.html

[C02] 默认参数
来源：http://dali.smart0.xyz/Article/details/gtomwktxdj.html

Py:   def greet(name="World"): return name
来源：http://dali.ehwqpu.com/Article/details/gthkpdkfej.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtdbmchskd.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xinyue.icu/Article/details/gtnzxrbbtb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hysaishi.cn/Article/details/gtlxgnblnk.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yongpay.top/Article/details/gtekydnbmr.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhoulong.xyz/Article/details/gtjqfwhils.html

Ruby: def greet(name = "World") = name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtogjoxpiz.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.smart0.xyz/Article/details/gtplnayhzv.html

[C03] 可变参数
来源：http://dali.zdqjudy.top/Article/details/gtjgpsatnb.html

Py:   def total(*args): return sum(args)
来源：http://dali.jqgufenzy.top/Article/details/gtnjftcgel.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.cqqwz.cn/Article/details/gtihkrwdhc.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfmvmycpd.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.iojbl.cn/Article/details/gtijiuhign.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.mhx1999.top/Article/details/gtbgxfdtdo.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.c1oappe.top/Article/details/gtkhqwnuhh.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxldwlriy.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yueranfly.top/Article/details/gtkqtfkjcs.html

[C04] 命名参数 / 关键字参数
来源：http://dali.aizwys.cn/Article/details/gtowxwppat.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.daria6918.cn/Article/details/gtgmnqndfo.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.sufxvd.cn/Article/details/gtsqdksnhx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.guannengcc.top/Article/details/gtcwavmxer.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shangyingyoupin.top/Article/details/gtpvdaodok.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yvedp.cn/Article/details/gtmhrrqghb.html

Go:   // 无：用配置结构体参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbezeeunr.html

Ruby: f(a: 1, b: 2)
来源：http://dali.mhx1999.top/Article/details/gtbxhtvegr.html

C#:   f(a: 1, b: 2)
来源：http://dali.316326.xyz/Article/details/gtnxuxtpvz.html

[C05] 返回多个值
来源：http://dali.jyoumei.cn/Article/details/gtahddbiiq.html

Py:   return a, b
来源：http://dali.jqgfzy.top/Article/details/gtbmdvivfq.html

PHP:  return [$a, $b];
来源：http://dali.xinyue.icu/Article/details/gtrfozmcro.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ivvv.top/Article/details/gtbvdzhzsj.html

TS:   return { a, b };
来源：http://dali.smart0.xyz/Article/details/gtuxgntova.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.pengpengdd.cyou/Article/details/gtezuurjrm.html

Go:   return a, b
来源：http://dali.meibo888.top/Article/details/gtrvivxnde.html

Ruby: return a, b
来源：http://dali.hfpthk.cn/Article/details/gtywictvii.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yj20258.top/Article/details/gtctfkqnpl.html

[C06] 匿名函数 / lambda
来源：http://dali.shangyingyoupin.top/Article/details/gtrsmhymyr.html

Py:   square = lambda x: x * x
来源：http://dali.jyoumei.cn/Article/details/gtqzgpzavn.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cashguo.top/Article/details/gtibuayxwi.html

JS:   const square = x => x * x;
来源：http://dali.jinqigufen.top/Article/details/gtxuovwsqo.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xylfe.cn/Article/details/gthyqlmyjn.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.meibo888.top/Article/details/gtzedvbbcg.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sxryk.cn/Article/details/gtiontbdcu.html

Ruby: square = ->(x) { x * x }
来源：http://dali.chenjidiqi.icu/Article/details/gttnchazxo.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.tian-w.cn/Article/details/gtyenbhfaw.html

[C07] 把函数作为参数传入
来源：http://dali.hywenlv.cn/Article/details/gtaxdladam.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.316326.xyz/Article/details/gtluturbzt.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.shuidangran.top/Article/details/gtjeejrars.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.daxiang520.top/Article/details/gtnfdtvfvg.html

TS:   arr.map(String)
来源：http://dali.fzhhl.top/Article/details/gtwzvhqkcz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ybcxt.top/Article/details/gtuaubnapk.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yj20258.top/Article/details/gtvlbjbfni.html

Ruby: arr.map(&:upcase)
来源：http://dali.pycfn.com/Article/details/gtfbrsvxox.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zycfv.cn/Article/details/gtxzhwkugl.html

[C08] 闭包
来源：http://dali.jqgfzy.top/Article/details/gterhvhilh.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xuetiantiany.cn/Article/details/gtyddjvstw.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzyjlggun.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yj202588.top/Article/details/gtbampcvux.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xinyue.icu/Article/details/gttqvqbbgx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hnxiangtu.top/Article/details/gtjdkxhvrp.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sweek.top/Article/details/gtwrodeqfd.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.0kj1m.cn/Article/details/gtoxbfoldo.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.birdmap.top/Article/details/gtfmxtklhs.html

[C09] 递归
来源：http://dali.hongshengwenyu.top/Article/details/gtipsejezo.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ydzc1.top/Article/details/gtmltptcig.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.chenlongwang.top/Article/details/gturortdiq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.feifeiyinyue.top/Article/details/gtrkejxqrm.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gogol.net.cn/Article/details/gtpxrodauy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.0kj1m.cn/Article/details/gtheetjkly.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cashguo.top/Article/details/gtingbjwop.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hfpthk.cn/Article/details/gtazwmmdir.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.guannengcc.top/Article/details/gtfqepgvkr.html

[C10] 变量作用域
来源：http://dali.ydzc1.top/Article/details/gtovcmzrqt.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.havefunace.top/Article/details/gtingptoed.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.9152youxi.cn/Article/details/gtxvfgmxoy.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.guannengcc.top/Article/details/gtdzqwguds.html

TS:   同 JS
来源：http://dali.smart0.xyz/Article/details/gtohgcaveu.html

Java: 方法内为块级作用域
来源：http://dali.yongpay.top/Article/details/gthaefdzuk.html

Go:   花括号块级作用域
来源：http://dali.daria6918.cn/Article/details/gtavnijkrd.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.birdmap.top/Article/details/gtxifmabqc.html

C#:   块级作用域
来源：http://dali.316326.xyz/Article/details/gtnsgtjlvb.html

[C11] 模块导入与导出
来源：http://dali.jlsjyb.cn/Article/details/gttxayoboc.html

Py:   from module import func
来源：http://dali.hnxiangtu.top/Article/details/gtkxwzelpc.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.smart0.xyz/Article/details/gtqkgesfls.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yj202588.top/Article/details/gtzstwqmjz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hongshengwenyu.top/Article/details/gtohqxpfkx.html

Java: import java.util.List;
来源：http://dali.havefunace.top/Article/details/gtiinhgyxg.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hysaishi.cn/Article/details/gteaqbfews.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.sysykeji.top/Article/details/gtkduejdfk.html

C#:   using System.Text;
来源：http://dali.snrcjt.cn/Article/details/gtbgdxwave.html

[C12] 立即执行函数 IIFE
来源：http://dali.smart0.xyz/Article/details/gtmrwphzzi.html

Py:   (lambda: print("run"))()
来源：http://dali.sweek.top/Article/details/gtzrmvqdbj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.nwbrower.top/Article/details/gtyaiedxic.html

JS:   (() => { console.log("run"); })();
来源：http://dali.c1oappe.top/Article/details/gthxuupbiv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ehwqpu.com/Article/details/gtghkrxvtt.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gtlwsbulyz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.wangshuangyany.cn/Article/details/gtsilezlij.html

Ruby: -> { puts "run" }.call
来源：http://dali.xziqi.cn/Article/details/gtmpqpubeo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cqqwz.cn/Article/details/gtegkyhmpi.html

[C13] 类型声明 / 类型注解
来源：http://dali.yj20258888.top/Article/details/gtsasmlesx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xuanzx.com/Article/details/gtolpzzedd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gogol.net.cn/Article/details/gttvysmiwm.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gaohongyu789.top/Article/details/gtefloenmw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gtuakxbjrf.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gtfgltxvfp.html

Go:   func add(a, b int) int
来源：http://dali.iojbl.cn/Article/details/gtipeojmld.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cucudq.cn/Article/details/gtfwtcnmgy.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jqgfzy.top/Article/details/gtpshednez.html

[C14] 泛型函数
来源：http://dali.hnxiangtu.top/Article/details/gtixphaany.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.snrcjt.cn/Article/details/gtjsnvgbzf.html

PHP:  // 无泛型
来源：http://dali.cucudq.cn/Article/details/gtxcjgwcrm.html

JS:   // 无泛型
来源：http://dali.tian-w.cn/Article/details/gtkecbddcb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.nwbrower.top/Article/details/gtlyvokkal.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.daria6918.cn/Article/details/gtpeyopkoi.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvgelsojy.html

Ruby: # 无泛型
来源：http://dali.gogol.net.cn/Article/details/gtnmctiedm.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.andypj.xyz/Article/details/gtxludustc.html

[C15] 解构 / 展开参数
来源：http://dali.yvedp.cn/Article/details/gtptfirepm.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.chenlongwang.top/Article/details/gtgnwvyftr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xziqi.cn/Article/details/gtmyxzgbuf.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtfhpqdxyh.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjbsaetft.html

Java: // 无解构
来源：http://dali.9152youxi.cn/Article/details/gtrrvobzng.html

Go:   // 无解构
来源：http://dali.dashuyun.cn/Article/details/gtyfujnvvt.html

Ruby: a, b = pair
来源：http://dali.snrcjt.cn/Article/details/gtgaoxvnab.html

C#:   var (a, b) = pair;
来源：http://dali.hysaishi.cn/Article/details/gtzzdcadff.html

[C16] 函数 / 方法重载
来源：http://dali.chenlongwang.top/Article/details/gtnvhinqjc.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ppjwa.cn/Article/details/gtibkypkdu.html

PHP:  // 无重载
来源：http://dali.shangyingyoupin.top/Article/details/gtkogpbowt.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.gotoacloud.top/Article/details/gtbbqzenmu.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jqgufenzy.top/Article/details/gtsmcesldx.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xziqi.cn/Article/details/gtpxmrjsxc.html

Go:   // 无重载：用不同函数名
来源：http://dali.kuanghao11.cn/Article/details/gtwxspkfgq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jlsjyb.cn/Article/details/gtiyxdiymc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.tanke756.top/Article/details/gtytdwzgni.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtkjxjdlca.html

D. 数组 / 列表 / 集合
来源：http://dali.sxryk.cn/Article/details/gtpbwijger.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtufeqevyp.html

[D01] 创建数组 / 列表
来源：http://dali.tanke756.top/Article/details/gtbvamlryb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.havefunace.top/Article/details/gtnsrorvnw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.aizwys.cn/Article/details/gtvukvcqek.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ppjwa.cn/Article/details/gtxkkonxjh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.gaohongyu789.top/Article/details/gtddrqhxxj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.316326.xyz/Article/details/gtlslovhml.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.aibaodan.cn/Article/details/gtjpgdmizv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sweek.top/Article/details/gtjbizetqj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.nanxuanxn.top/Article/details/gtgoxmsndt.html

[D02] 追加元素到末尾
来源：http://dali.yj20258888.top/Article/details/gtqfikxiwp.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hysaishi.cn/Article/details/gtpjkqbfyy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shzxlz.cn/Article/details/gtloslqqfo.html

JS:   arr.push(4);
来源：http://dali.tianlin.xyz/Article/details/gtzulnbklr.html

TS:   arr.push(4);
来源：http://dali.xinyue.icu/Article/details/gtuutslguy.html

Java: list.add(4);
来源：http://dali.ppjwa.cn/Article/details/gtljzfvcxm.html

Go:   arr = append(arr, 4)
来源：http://dali.zdqjudy.top/Article/details/gtvbfoxsvz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.andypj.xyz/Article/details/gtciasjdvo.html

C#:   list.Add(4);
来源：http://dali.yangfankeji.com/Article/details/gtoqcjzmas.html

[D03] 在指定位置插入元素
来源：http://dali.zhengqikj.top/Article/details/gtmyirsqbi.html

Py:   arr.insert(0, 0)
来源：http://dali.snrcjt.cn/Article/details/gtwjtxtyyc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.316326.xyz/Article/details/gtdmcdscpv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.birdmap.top/Article/details/gtppuiiijj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jqgufenzy.top/Article/details/gtmwjyggjo.html

Java: list.add(0, 0);
来源：http://dali.cheryme.top/Article/details/gtiktemtkv.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xinyue.icu/Article/details/gtdqklyyqb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cashguo.top/Article/details/gtfrbicwwa.html

C#:   list.Insert(0, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtfbwtaiag.html

[D04] 删除元素
来源：http://dali.yueranfly.top/Article/details/gtxmgojjos.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.tianlin.xyz/Article/details/gtngnszvhr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtmrzvzvlo.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.bjfxy.top/Article/details/gtvehbytsj.html

TS:   arr.splice(0, 1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmiviewiu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhixingplan.top/Article/details/gtzqrqksvw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jyoumei.cn/Article/details/gtupufqmjm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.nwbrower.top/Article/details/gtdimrbean.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.smart0.xyz/Article/details/gttegyicyy.html

[D05] 访问与修改元素
来源：http://dali.chenjidiqi.icu/Article/details/gthmawfniz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gtldvzgsyh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yanxiufei.cn/Article/details/gtfchfcdqj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yuxming.cn/Article/details/gtohohktsi.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.aibaodan.cn/Article/details/gtjbtnswjm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cdnleiting.top/Article/details/gtqsowappt.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinqigfzy.top/Article/details/gtqoxihpvz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cqqwz.cn/Article/details/gtzokkyoae.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cdnleiting.top/Article/details/gtdfvvnzvn.html

[D06] 数组长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmfliuqar.html

Py:   len(arr)
来源：http://dali.jiagoushi.top/Article/details/gthojepnzz.html

PHP:  count($arr);
来源：http://dali.ppjwa.cn/Article/details/gtjzrfqcym.html

JS:   arr.length
来源：http://dali.0kj1m.cn/Article/details/gtymoeueli.html

TS:   arr.length
来源：http://dali.nwbrower.top/Article/details/gtktvjdetr.html

Java: list.size();
来源：http://dali.svipenyu.cn/Article/details/gtjsgnocox.html

Go:   len(arr)
来源：http://dali.hnqzz.top/Article/details/gtdrctgxnr.html

Ruby: arr.length; arr.size
来源：http://dali.ivvv.top/Article/details/gtkfnhnnur.html

C#:   list.Count;
来源：http://dali.zycfv.cn/Article/details/gtiegvlyum.html

[D07] 切片 / 取子数组
来源：http://dali.ppjwa.cn/Article/details/gthflfhhyr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shanyushiyangkeji.top/Article/details/gthssstvmx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvkisyyqf.html

JS:   arr.slice(1, 4);
来源：http://dali.feifeiyinyue.top/Article/details/gthkiplrej.html

TS:   arr.slice(1, 4);
来源：http://dali.yueranfly.top/Article/details/gtlaaaahna.html

Java: list.subList(1, 4);
来源：http://dali.yanxiufei.cn/Article/details/gthkpyoodd.html

Go:   arr[1:4]
来源：http://dali.birdmap.top/Article/details/gtfenxreos.html

Ruby: arr[1, 3]
来源：http://dali.jyoumei.cn/Article/details/gtemzsirwa.html

C#:   list.GetRange(1, 3);
来源：http://dali.jyoumei.cn/Article/details/gthujdqnkj.html

[D08] 合并两个数组
来源：http://dali.cqqwz.cn/Article/details/gtjtncgrmp.html

Py:   a + b;  a.extend(b)
来源：http://dali.chenjidiqi.icu/Article/details/gtnqcuqrwt.html

PHP:  array_merge($a, $b);
来源：http://dali.vqdsnc.cn/Article/details/gtbcflcgyw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sysykeji.top/Article/details/gtmnmxlmcq.html

TS:   [...a, ...b];
来源：http://dali.sweek.top/Article/details/gtwdmefuwz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yonumen.top/Article/details/gtvrkgsfax.html

Go:   append(a, b...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlqpmtjjm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.smart0.xyz/Article/details/gtbgeexdqh.html

C#:   a.Concat(b).ToList()
来源：http://dali.0kj1m.cn/Article/details/gtcwkyluuz.html

[D09] 排序（升序）
来源：http://dali.cqqwz.cn/Article/details/gtfasebihq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwshdlyws.html

PHP:  sort($arr);
来源：http://dali.shzxlz.cn/Article/details/gtfevcdwen.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yueranfly.top/Article/details/gtdjihphuq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.tanke756.top/Article/details/gtxtiucbud.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hongshengwenyu.top/Article/details/gtxnyjjzua.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yj202588.top/Article/details/gtfxinbcbx.html

Ruby: arr.sort
来源：http://dali.chenlongwang.top/Article/details/gtbgwjiaoe.html

C#:   list.Sort();
来源：http://dali.zhoulong.xyz/Article/details/gtjcucthed.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.dashuyun.cn/Article/details/gtnqpvrach.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.meibo888.top/Article/details/gtwsafnvpf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.birdmap.top/Article/details/gtcsgceybs.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hongshengwenyu.top/Article/details/gtkvjhirqi.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnxiangtu.top/Article/details/gtzflpcfvh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xuanzx.com/Article/details/gtiagpoutg.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shuidangran.top/Article/details/gthjxxbrpg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sxryk.cn/Article/details/gtzzkxowgp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sufxvd.cn/Article/details/gtbcribtrf.html

[D11] 反转数组
来源：http://dali.hongshengwenyu.top/Article/details/gtxgwpsoqv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shuidangran.top/Article/details/gtdnolmpuj.html

PHP:  array_reverse($arr);
来源：http://dali.guannengcc.top/Article/details/gtahujobim.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.pycfn.com/Article/details/gtxyodbnyi.html


<!-- 参考信息 -->