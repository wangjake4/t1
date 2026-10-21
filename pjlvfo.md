代发 wailian999

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.dianchejie.cn/Article/details/gtrfrptlig.html

Ruby: (0...10).step(2).to_a
来源：http://dali.chenlongwang.top/Article/details/gtejefzjpr.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.tanke756.top/Article/details/gtbznlgatt.html

[B12] 跳出多层循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtqfmasxzk.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgibnxful.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.kuanghao11.cn/Article/details/gtcgoiwxwp.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfimdouqd.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.pengpengdd.cyou/Article/details/gtqhfulavs.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.vqdsnc.cn/Article/details/gtxdulkydt.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xziqi.cn/Article/details/gttluwqsoh.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ybcxt.top/Article/details/gteaqhxgcq.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.pycfn.com/Article/details/gtgdxidmfh.html

[B13] 判断是否为数字
来源：http://dali.shanyushiyangtech.top/Article/details/gtnqxqztet.html

Py:   isinstance(x, (int, float))
来源：http://dali.hfpthk.cn/Article/details/gtlueocjna.html

PHP:  is_numeric($x)
来源：http://dali.jyoumei.cn/Article/details/gtktgzueuc.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.birdmap.top/Article/details/gtqyraxjjg.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yongpay.top/Article/details/gtdttaujrl.html

Java: x instanceof Number
来源：http://dali.xziqi.cn/Article/details/gtblpwzioe.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hywenlv.cn/Article/details/gtfbpbsweo.html

Ruby: x.is_a?(Numeric)
来源：http://dali.wangshuangyany.cn/Article/details/gtnkxrdagv.html

C#:   x is int or double or decimal
来源：http://dali.ivvv.top/Article/details/gtogwzeglk.html

[B14] 判断值是否在集合内
来源：http://dali.zycfv.cn/Article/details/gtqbhvpwic.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.fengsongda.top/Article/details/gtafgwpszv.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jqgufenzy.top/Article/details/gtgferyflz.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258888.top/Article/details/gtkkvddowq.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.tian-w.cn/Article/details/gtgvyayhdx.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.svipenyu.cn/Article/details/gtiqgrwweg.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.cucudq.cn/Article/details/gtnhvljkcq.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yangfankeji.com/Article/details/gtaaffxwmd.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.cdnleiting.top/Article/details/gtbdzaxypn.html

[B15] 布尔运算与取反
来源：http://dali.cucudq.cn/Article/details/gtnxedjjix.html

Py:   a and b or not c
来源：http://dali.havefunace.top/Article/details/gtsgymejvd.html

PHP:  $a && $b || !$c
来源：http://dali.ppjwa.cn/Article/details/gtmelblbey.html

JS:   a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gtktxdhjgi.html

TS:   a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gtqatkgzxs.html

Java: a && b || !c
来源：http://dali.ivvv.top/Article/details/gtfknyxfez.html

Go:   a && b || !c
来源：http://dali.havefunace.top/Article/details/gtkayszuqe.html

Ruby: a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gtkazjzogn.html

C#:   a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gtsbtgnedl.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.shzxlz.cn/Article/details/gtylgqxcrv.html

Py:   if not data: return
来源：http://dali.cheryme.top/Article/details/gttkpfwbrx.html

PHP:  if (!$data) { return; }
来源：http://dali.dashuyun.cn/Article/details/gtgfzsooph.html

JS:   if (!data) return;
来源：http://dali.shanyushiyangtech.top/Article/details/gtummpqxkz.html

TS:   if (!data) return;
来源：http://dali.zhongyouzk.top/Article/details/gtgfmisdsx.html

Java: if (data == null) return;
来源：http://dali.sysykeji.top/Article/details/gtlktrytnc.html

Go:   if data == nil { return }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsubdqfay.html

Ruby: return if data.nil?
来源：http://dali.meibo888.top/Article/details/gtqrjfgklq.html

C#:   if (data == null) return;
来源：http://dali.sufxvd.cn/Article/details/gtedbnynzp.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtkshnlomc.html

C. 函数与作用域
来源：http://dali.aibaodan.cn/Article/details/gtrlcliwmu.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtojbieshf.html

[C01] 定义函数
来源：http://dali.iojbl.cn/Article/details/gteaonmihx.html

Py:   def add(a, b): return a + b
来源：http://dali.zhoulong.xyz/Article/details/gtmruemmmu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.redwolf501.top/Article/details/gtqicxgblp.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gtnyjiwnlg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gthadmugmc.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.cashguo.top/Article/details/gtfhrnecfq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.daxiang520.top/Article/details/gtniltmpwi.html

Ruby: def add(a, b); a + b; end
来源：http://dali.svipenyu.cn/Article/details/gtpehexswq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gtobmzdhxe.html

[C02] 默认参数
来源：http://dali.hnqzz.top/Article/details/gtdztbgslo.html

Py:   def greet(name="World"): return name
来源：http://dali.jyoumei.cn/Article/details/gtrioggeah.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnuawwapo.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hnqzz.top/Article/details/gtrfveynvs.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hnqzz.top/Article/details/gtgglibliy.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhoulong.xyz/Article/details/gtunplymuo.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.gotoacloud.top/Article/details/gthlptnmtw.html

Ruby: def greet(name = "World") = name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrcyolfxw.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.tianlin.xyz/Article/details/gtujaazdja.html

[C03] 可变参数
来源：http://dali.jinghuilouyu.cn/Article/details/gthmyhiydy.html

Py:   def total(*args): return sum(args)
来源：http://dali.nanxinkj.top/Article/details/gtinccbsmm.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlbbmprrq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tian-w.cn/Article/details/gtppmmklwf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yuanzhike.top/Article/details/gtysygfaiw.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.andypj.xyz/Article/details/gtzxgndrdm.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yueranfly.top/Article/details/gtalruaawh.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jqgufenzy.top/Article/details/gtaanuxbpt.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hfpthk.cn/Article/details/gtbncvhhln.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ybcxt.top/Article/details/gtechhfqtz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.wangdashe.top/Article/details/gtostmrelh.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.pengpengdd.cyou/Article/details/gtflzxojop.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsmvrgciv.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jinghuilouyu.cn/Article/details/gtevuprmax.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cashguo.top/Article/details/gtaicpsznn.html

Go:   // 无：用配置结构体参数
来源：http://dali.yongpay.top/Article/details/gtizctgxky.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cqqwz.cn/Article/details/gtfehygmob.html

C#:   f(a: 1, b: 2)
来源：http://dali.yj20258.top/Article/details/gtdmxfknev.html

[C05] 返回多个值
来源：http://dali.wangdashe.top/Article/details/gtgjslbyoa.html

Py:   return a, b
来源：http://dali.zycfv.cn/Article/details/gtfrpqwipb.html

PHP:  return [$a, $b];
来源：http://dali.zhoulong.xyz/Article/details/gtexuxjceh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jqgufenzy.top/Article/details/gtovvqtsws.html

TS:   return { a, b };
来源：http://dali.guowangkeji.top/Article/details/gtqtcszlvn.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.chenzaomai.com/Article/details/gtjtxtayzp.html

Go:   return a, b
来源：http://dali.yj202588.top/Article/details/gtghpjkyfj.html

Ruby: return a, b
来源：http://dali.hfpthk.cn/Article/details/gtyhvvwldb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpijvyizc.html

[C06] 匿名函数 / lambda
来源：http://dali.cdnleiting.top/Article/details/gtrxbskztn.html

Py:   square = lambda x: x * x
来源：http://dali.svipenyu.cn/Article/details/gtgholqogd.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jqgfzy.top/Article/details/gtuliyxuzc.html

JS:   const square = x => x * x;
来源：http://dali.tianlin.xyz/Article/details/gtzesptdbc.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shanyushiyangtech.top/Article/details/gthkzpniwm.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.aizwys.cn/Article/details/gtlfmlfzwq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jinqigfzy.top/Article/details/gtpsrjatav.html

Ruby: square = ->(x) { x * x }
来源：http://dali.andypj.xyz/Article/details/gtrwdnlnsy.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinqigfzy.top/Article/details/gtexengvas.html

[C07] 把函数作为参数传入
来源：http://dali.xylfe.cn/Article/details/gtvfwspret.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jianghu66.top/Article/details/gtueoltlyb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zdqjudy.top/Article/details/gtwflbkckl.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.haohaochexian.top/Article/details/gtcepyciee.html

TS:   arr.map(String)
来源：http://dali.havefunace.top/Article/details/gtgtlzclht.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.chenlongwang.top/Article/details/gtgikpqvax.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hammf.cn/Article/details/gtrnvzzirx.html

Ruby: arr.map(&:upcase)
来源：http://dali.cucudq.cn/Article/details/gthanwkegg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.9152youxi.cn/Article/details/gtqeccouoa.html

[C08] 闭包
来源：http://dali.hywenlv.cn/Article/details/gtwbrgjsed.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjtzbaqzt.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.tianlin.xyz/Article/details/gtjlqxumcg.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.quarkkingdee.top/Article/details/gtqagpawor.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yueranfly.top/Article/details/gtxeavwbkx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zycfv.cn/Article/details/gthhmqwmzf.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cashguo.top/Article/details/gtkukqumfu.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.aibaodan.cn/Article/details/gtdobjugiv.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.redwolf501.top/Article/details/gtjkrwupsk.html

[C09] 递归
来源：http://dali.xinyue.icu/Article/details/gtppqqxyec.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.daxiang520.top/Article/details/gtzvplfvhk.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gtewkakijq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jianghu66.top/Article/details/gtwzijpyut.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.snrcjt.cn/Article/details/gtdyehsgpr.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cqqwz.cn/Article/details/gtxrzattio.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sxryk.cn/Article/details/gtofqfxwqc.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ybcxt.top/Article/details/gtmatzgywz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.haohaochexian.top/Article/details/gtmayvgeir.html

[C10] 变量作用域
来源：http://dali.cucudq.cn/Article/details/gtcsmbukog.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.mhx1999.top/Article/details/gtufcckdfu.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinqigufen.top/Article/details/gtyhtsjorf.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yvedp.cn/Article/details/gtpsqwrapl.html

TS:   同 JS
来源：http://dali.yvedp.cn/Article/details/gtyrqeywnx.html

Java: 方法内为块级作用域
来源：http://dali.smart0.xyz/Article/details/gtvxokrwkc.html

Go:   花括号块级作用域
来源：http://dali.ydzc1.top/Article/details/gtjclvtmyn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hongshengwenyu.top/Article/details/gtvhufiahx.html

C#:   块级作用域
来源：http://dali.quarkkingdee.top/Article/details/gtluvltpyj.html

[C11] 模块导入与导出
来源：http://dali.mhx1999.top/Article/details/gtcdzebvko.html

Py:   from module import func
来源：http://dali.sufxvd.cn/Article/details/gtiqjfybcw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jianghu66.top/Article/details/gtvvvsmwaw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.meibo888.top/Article/details/gtcmlfkzda.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.daria6918.cn/Article/details/gtareoftsc.html

Java: import java.util.List;
来源：http://dali.gotoacloud.top/Article/details/gtwhcswpvn.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhoulong.xyz/Article/details/gtlxbahtze.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gogol.net.cn/Article/details/gtqvyfouxd.html

C#:   using System.Text;
来源：http://dali.birdmap.top/Article/details/gtfqjoneml.html

[C12] 立即执行函数 IIFE
来源：http://dali.chenzaomai.com/Article/details/gtosrjuqej.html

Py:   (lambda: print("run"))()
来源：http://dali.sxryk.cn/Article/details/gtinuzjvgt.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hnqzz.top/Article/details/gtmzrxbuwh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yj20258.top/Article/details/gtbyzvcmwf.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shangyingyoupin.top/Article/details/gtezqbvvgt.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cashguo.top/Article/details/gthgaolpho.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cucudq.cn/Article/details/gtbwbnxezr.html

Ruby: -> { puts "run" }.call
来源：http://dali.wangshuangyany.cn/Article/details/gtckivedxf.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yangfankeji.com/Article/details/gtqwxgfxkh.html

[C13] 类型声明 / 类型注解
来源：http://dali.hysaishi.cn/Article/details/gtddlqriyd.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sufxvd.cn/Article/details/gtyihzfjzh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuxming.cn/Article/details/gtxoxijvsl.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhoulong.xyz/Article/details/gtctiyodvp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gtgrpjocsb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gtoazhiskx.html

Go:   func add(a, b int) int
来源：http://dali.gaohongyu789.top/Article/details/gtdjsedlht.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yuxming.cn/Article/details/gtkwrguylf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.quarkkingdee.top/Article/details/gtxcblqxjl.html

[C14] 泛型函数
来源：http://dali.meibo888.top/Article/details/gtddxtrhfj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.0kj1m.cn/Article/details/gtehgedmym.html

PHP:  // 无泛型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuefavtna.html

JS:   // 无泛型
来源：http://dali.gotoacloud.top/Article/details/gtyvuibboz.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.redwolf501.top/Article/details/gtativadsl.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.c1oappe.top/Article/details/gtywhbhher.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sysykeji.top/Article/details/gtcchvkfyh.html

Ruby: # 无泛型
来源：http://dali.gzhubu.top/Article/details/gtieajyczt.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cqqwz.cn/Article/details/gtvwcajjhz.html

[C15] 解构 / 展开参数
来源：http://dali.smart0.xyz/Article/details/gtfyyzthor.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.daxiang520.top/Article/details/gtgbyitcwb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.wangshuangyany.cn/Article/details/gtbdlvgjfb.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xuanzx.com/Article/details/gtlftugmsg.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jlsjyb.cn/Article/details/gthlgydfqq.html

Java: // 无解构
来源：http://dali.zhongyouzk.top/Article/details/gtmvfhukmt.html

Go:   // 无解构
来源：http://dali.hongshengwenyu.top/Article/details/gtwcrxhbum.html

Ruby: a, b = pair
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdspxwvwa.html

C#:   var (a, b) = pair;
来源：http://dali.xuanzx.com/Article/details/gtfnayjerl.html

[C16] 函数 / 方法重载
来源：http://dali.ywan-chungtsiang.top/Article/details/gtybewgvwb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.guowangkeji.top/Article/details/gtllxwvkfi.html

PHP:  // 无重载
来源：http://dali.wangdashe.top/Article/details/gtufdcnlhz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jqgfzy.top/Article/details/gtpjtlgrjn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yangfankeji.com/Article/details/gtlhwmvpgp.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.9152youxi.cn/Article/details/gtmbuqnepp.html

Go:   // 无重载：用不同函数名
来源：http://dali.shuidangran.top/Article/details/gtspxesgxy.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ybcxt.top/Article/details/gtqwnrmubp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yangfankeji.com/Article/details/gtpbxgtglf.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtkbotrvya.html

D. 数组 / 列表 / 集合
来源：http://dali.yuanzhike.top/Article/details/gtzbcvatbg.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtafptbywv.html

[D01] 创建数组 / 列表
来源：http://dali.yj20258.top/Article/details/gtdoezbozq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shanyushiyangkeji.top/Article/details/gtktknfwuj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xuetiantiany.cn/Article/details/gteslpbiid.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yj202588.top/Article/details/gtdgrdfwem.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.guannengcc.top/Article/details/gtvopdaopa.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xziqi.cn/Article/details/gtilmvbptg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinqigfzy.top/Article/details/gtodpgwlcw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhongyouzk.top/Article/details/gtdclnedyp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xuanzx.com/Article/details/gtkooyefdq.html

[D02] 追加元素到末尾
来源：http://dali.yongpay.top/Article/details/gtnqqzxxtx.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.wangdashe.top/Article/details/gtdlkdxtum.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gaohongyu789.top/Article/details/gtmxlttvce.html

JS:   arr.push(4);
来源：http://dali.hywenlv.cn/Article/details/gtsoxslonw.html

TS:   arr.push(4);
来源：http://dali.jyoumei.cn/Article/details/gtjtchwljw.html

Java: list.add(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfnpqmias.html

Go:   arr = append(arr, 4)
来源：http://dali.ppjwa.cn/Article/details/gtitedxbmz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yuxming.cn/Article/details/gtqfrpfriy.html

C#:   list.Add(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsametvdm.html

[D03] 在指定位置插入元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxwobvesi.html

Py:   arr.insert(0, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtptnnlzob.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sufxvd.cn/Article/details/gtxompfqrm.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.feifeiyinyue.top/Article/details/gtzrfbkqks.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.316326.xyz/Article/details/gtwakvngim.html

Java: list.add(0, 0);
来源：http://dali.yuanzhike.top/Article/details/gtrbawmxcn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sweek.top/Article/details/gtvejhxcdd.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xinyue.icu/Article/details/gtpihhnacg.html

C#:   list.Insert(0, 0);
来源：http://dali.shuidangran.top/Article/details/gtahrufziv.html

[D04] 删除元素
来源：http://dali.daria6918.cn/Article/details/gtduicurdd.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.0kj1m.cn/Article/details/gtlnlcskca.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sxryk.cn/Article/details/gtzxvoxsox.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hnqzz.top/Article/details/gteukmayrw.html

TS:   arr.splice(0, 1);
来源：http://dali.feifeiyinyue.top/Article/details/gteocpfgks.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jqgfzy.top/Article/details/gtwunkrxrv.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hongshengwenyu.top/Article/details/gtkwxjjrmc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yuanzhike.top/Article/details/gteenlzrsv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jqgfzy.top/Article/details/gtlazhlvck.html

[D05] 访问与修改元素
来源：http://dali.316326.xyz/Article/details/gtoauxjukp.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.mhx1999.top/Article/details/gtaumkwyka.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gtmiqgfpda.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.nanxinkj.top/Article/details/gtbnvigjkd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.quarkkingdee.top/Article/details/gtgjjaydta.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ehwqpu.com/Article/details/gtvreqamwx.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.snrcjt.cn/Article/details/gtklwvxrhx.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.daxiang520.top/Article/details/gtwhdiqjrk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yj202588.top/Article/details/gtyxhoamil.html

[D06] 数组长度
来源：http://dali.gaohongyu789.top/Article/details/gtliaoxllz.html

Py:   len(arr)
来源：http://dali.ybcxt.top/Article/details/gtmltcokpg.html

PHP:  count($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gthnvfvpte.html

JS:   arr.length
来源：http://dali.sxryk.cn/Article/details/gtchnsqdkc.html

TS:   arr.length
来源：http://dali.yuxming.cn/Article/details/gterysyryk.html

Java: list.size();
来源：http://dali.hysaishi.cn/Article/details/gtwnkocguq.html

Go:   len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgsqubxhk.html

Ruby: arr.length; arr.size
来源：http://dali.shangyingyoupin.top/Article/details/gtrimfgpdc.html

C#:   list.Count;
来源：http://dali.zhixingplan.top/Article/details/gtcispyhng.html

[D07] 切片 / 取子数组
来源：http://dali.hongshengwenyu.top/Article/details/gtncprxeli.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jianghu66.top/Article/details/gtcjamlxno.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hysaishi.cn/Article/details/gtdlzxddti.html

JS:   arr.slice(1, 4);
来源：http://dali.gzhubu.top/Article/details/gtpsgdamaz.html

TS:   arr.slice(1, 4);
来源：http://dali.pycfn.com/Article/details/gtoujkusjk.html

Java: list.subList(1, 4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsxtzqjnh.html

Go:   arr[1:4]
来源：http://dali.cashguo.top/Article/details/gtvzrzlnaf.html

Ruby: arr[1, 3]
来源：http://dali.iojbl.cn/Article/details/gthazmwrbh.html

C#:   list.GetRange(1, 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkhrmpwzy.html

[D08] 合并两个数组
来源：http://dali.gogol.net.cn/Article/details/gtqsroyoxg.html

Py:   a + b;  a.extend(b)
来源：http://dali.tian-w.cn/Article/details/gthhixdcmg.html

PHP:  array_merge($a, $b);
来源：http://dali.gzhubu.top/Article/details/gtohcigdxi.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.haohaochexian.top/Article/details/gtzdgnmtde.html

TS:   [...a, ...b];
来源：http://dali.xuetiantiany.cn/Article/details/gthxpospks.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.bjfxy.top/Article/details/gtjodwpjfo.html

Go:   append(a, b...)
来源：http://dali.c1oappe.top/Article/details/gtctwnwtnv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.daxiang520.top/Article/details/gtypngpmlz.html

C#:   a.Concat(b).ToList()
来源：http://dali.tanke756.top/Article/details/gtddvnafmq.html

[D09] 排序（升序）
来源：http://dali.zhoulong.xyz/Article/details/gtbxklefmc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.wangshuangyany.cn/Article/details/gtmyquuabq.html

PHP:  sort($arr);
来源：http://dali.hnqzz.top/Article/details/gtjukcuqcb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shzxlz.cn/Article/details/gtjowkrmwi.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shuidangran.top/Article/details/gtcukdmkdr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.vqdsnc.cn/Article/details/gtfanxbcnf.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtubrgcbvy.html

Ruby: arr.sort
来源：http://dali.dashuyun.cn/Article/details/gtywecpsgc.html

C#:   list.Sort();
来源：http://dali.yueranfly.top/Article/details/gttxxjmxux.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hysaishi.cn/Article/details/gthdoxqqop.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ehwqpu.com/Article/details/gtasgqtwcm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.316326.xyz/Article/details/gtladhlqje.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258888.top/Article/details/gtcvnikkmt.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daxiang520.top/Article/details/gtbhvajxsn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.guannengcc.top/Article/details/gtwxsxmjgn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.pycfn.com/Article/details/gtvswftgsb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yongpay.top/Article/details/gtovaoaqwd.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.meibo888.top/Article/details/gthuyrmjux.html

[D11] 反转数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtglvkronx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ybcxt.top/Article/details/gtoibqaucs.html

PHP:  array_reverse($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtpgwdebqx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yj202588.top/Article/details/gttnscjvdd.html

TS:   [...arr].reverse();
来源：http://dali.hammf.cn/Article/details/gtvuigimtz.html

Java: Collections.reverse(list);
来源：http://dali.shzxlz.cn/Article/details/gtvnydpmpw.html

Go:   slices.Reverse(arr)
来源：http://dali.andypj.xyz/Article/details/gtflzedzqv.html

Ruby: arr.reverse
来源：http://dali.svipenyu.cn/Article/details/gtowsgaaqs.html

C#:   list.Reverse();
来源：http://dali.daria6918.cn/Article/details/gtvptzuonj.html

[D12] 查找元素下标
来源：http://dali.shzxlz.cn/Article/details/gtkzajvfld.html

Py:   arr.index(x);  x in arr
来源：http://dali.havefunace.top/Article/details/gtrsjqqrxq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jqgufenzy.top/Article/details/gtyogstoil.html


<!-- 参考信息 -->