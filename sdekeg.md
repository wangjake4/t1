代发 wailian999

PHP:  range(0, 10, 2);
来源：http://dali.xinyue.icu/Article/details/gtsxgmdmib.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhoulong.xyz/Article/details/gtilrkfeya.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.chenlongwang.top/Article/details/gtuksfyfaw.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.gaohongyu789.top/Article/details/gtwuzryehp.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.fengsongda.top/Article/details/gteeblyflm.html

Ruby: (0...10).step(2).to_a
来源：http://dali.wangshuangyany.cn/Article/details/gtlzxnqbqm.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.gzhubu.top/Article/details/gtfvdnqxzw.html

[B12] 跳出多层循环
来源：http://dali.meibo888.top/Article/details/gtjnfnhihj.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.iojbl.cn/Article/details/gtgghwzljf.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xziqi.cn/Article/details/gtmosaujip.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.daria6918.cn/Article/details/gtoeuneudf.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigfzy.top/Article/details/gtbjbctpeu.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyowzgruw.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.daria6918.cn/Article/details/gtjlwfcczw.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.feifeiyinyue.top/Article/details/gtcttmtoau.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.shzxlz.cn/Article/details/gtccapaiui.html

[B13] 判断是否为数字
来源：http://dali.gotoacloud.top/Article/details/gtyewklhsg.html

Py:   isinstance(x, (int, float))
来源：http://dali.wangshuangyany.cn/Article/details/gtlkdpwzad.html

PHP:  is_numeric($x)
来源：http://dali.dashuyun.cn/Article/details/gtpeqykcvy.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xylfe.cn/Article/details/gttsyzqrul.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj20258888.top/Article/details/gtcvtoockt.html

Java: x instanceof Number
来源：http://dali.yvedp.cn/Article/details/gtqeahtjlq.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.redwolf501.top/Article/details/gtpgpzzolw.html

Ruby: x.is_a?(Numeric)
来源：http://dali.guowangkeji.top/Article/details/gtnxcwzizw.html

C#:   x is int or double or decimal
来源：http://dali.zhoulong.xyz/Article/details/gtmvvjzecp.html

[B14] 判断值是否在集合内
来源：http://dali.zhongyouzk.top/Article/details/gtdsuytxcp.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ybcxt.top/Article/details/gtcdzhmwgc.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.tianlin.xyz/Article/details/gtcyjtigsa.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zdqjudy.top/Article/details/gtkxmpyosp.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthedcddwh.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.haohaochexian.top/Article/details/gtkytcsswf.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtonlyrkle.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgcamwpwu.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.bjfxy.top/Article/details/gtigtgfbas.html

[B15] 布尔运算与取反
来源：http://dali.nanxuanxn.top/Article/details/gtiiyqiqin.html

Py:   a and b or not c
来源：http://dali.pycfn.com/Article/details/gtjvmmkzyu.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gtfepdlvci.html

JS:   a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gtjqesdtel.html

TS:   a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gtakvefjph.html

Java: a && b || !c
来源：http://dali.hnqzz.top/Article/details/gtbpuothtt.html

Go:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gthkgqcbhw.html

Ruby: a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gttynisqtx.html

C#:   a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gtsgiarztu.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.chenzaomai.com/Article/details/gtyyxqrgtd.html

Py:   if not data: return
来源：http://dali.yvedp.cn/Article/details/gtkezalpnx.html

PHP:  if (!$data) { return; }
来源：http://dali.yj202588.top/Article/details/gtgwfkczbc.html

JS:   if (!data) return;
来源：http://dali.xinyue.icu/Article/details/gtnmrpoosj.html

TS:   if (!data) return;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtccdikqvm.html

Java: if (data == null) return;
来源：http://dali.yuxming.cn/Article/details/gtqrgxpxsq.html

Go:   if data == nil { return }
来源：http://dali.dianchejie.cn/Article/details/gtnuhkwhks.html

Ruby: return if data.nil?
来源：http://dali.hnxiangtu.top/Article/details/gttgjpvazi.html

C#:   if (data == null) return;
来源：http://dali.yongpay.top/Article/details/gtziwytgyo.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtbahralah.html

C. 函数与作用域
来源：http://dali.shuidangran.top/Article/details/gtgmuoiljk.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gteabcybow.html

[C01] 定义函数
来源：http://dali.aizwys.cn/Article/details/gtbiqrwbgj.html

Py:   def add(a, b): return a + b
来源：http://dali.snrcjt.cn/Article/details/gtjwapqjnu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gtqufonhhv.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gtbkpojqva.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gtdsaqjkah.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtrbpgxbyg.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.nwbrower.top/Article/details/gtjodcisql.html

Ruby: def add(a, b); a + b; end
来源：http://dali.dashuyun.cn/Article/details/gtwnkpaadc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtonnqecfn.html

[C02] 默认参数
来源：http://dali.gogol.net.cn/Article/details/gtbeqxllex.html

Py:   def greet(name="World"): return name
来源：http://dali.jinghuilouyu.cn/Article/details/gtqyysznwg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xylfe.cn/Article/details/gtggnvezaw.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.smart0.xyz/Article/details/gtpilqfnvw.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtwkwamocs.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.guowangkeji.top/Article/details/gttqxliuyp.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.andypj.xyz/Article/details/gtmsfvnrog.html

Ruby: def greet(name = "World") = name
来源：http://dali.jlsjyb.cn/Article/details/gttqwmpsyb.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.chenlongwang.top/Article/details/gtmjdhaxsi.html

[C03] 可变参数
来源：http://dali.jiagoushi.top/Article/details/gthnkwnvxa.html

Py:   def total(*args): return sum(args)
来源：http://dali.yuanzhike.top/Article/details/gtxsljoifg.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.bjfxy.top/Article/details/gtdagputlr.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yangfankeji.com/Article/details/gtdzeznido.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sxryk.cn/Article/details/gtwlwufvcu.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jiagoushi.top/Article/details/gtuekakbht.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ehwqpu.com/Article/details/gtoddenssv.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.0kj1m.cn/Article/details/gtvhhkgzjo.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xuanzx.com/Article/details/gtrhbnmwfx.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yuanzhike.top/Article/details/gtyywrbatp.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.birdmap.top/Article/details/gtwlobesrp.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yonumen.top/Article/details/gtjdxysvid.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.meibo888.top/Article/details/gtfwuxhwky.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.pengpengdd.cyou/Article/details/gtsfualjjn.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hfpthk.cn/Article/details/gtzfkqspzd.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gtzabmbjkm.html

Ruby: f(a: 1, b: 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtyueyqsns.html

C#:   f(a: 1, b: 2)
来源：http://dali.hnqzz.top/Article/details/gttlrqtzfz.html

[C05] 返回多个值
来源：http://dali.gotoacloud.top/Article/details/gtvbxkkugi.html

Py:   return a, b
来源：http://dali.yonumen.top/Article/details/gtztrsifoh.html

PHP:  return [$a, $b];
来源：http://dali.cashguo.top/Article/details/gtbmmahqyh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xylfe.cn/Article/details/gtlmlyccid.html

TS:   return { a, b };
来源：http://dali.zhiwuduotai.top/Article/details/gthqlkbvzx.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cqqwz.cn/Article/details/gtoyzeapxg.html

Go:   return a, b
来源：http://dali.ehwqpu.com/Article/details/gtwmmjlndf.html

Ruby: return a, b
来源：http://dali.daxiang520.top/Article/details/gtidbclykc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yangfankeji.com/Article/details/gtjytmcuxi.html

[C06] 匿名函数 / lambda
来源：http://dali.hammf.cn/Article/details/gtzqpvdoeo.html

Py:   square = lambda x: x * x
来源：http://dali.9152youxi.cn/Article/details/gtsapocimw.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.guowangkeji.top/Article/details/gthwrneumq.html

JS:   const square = x => x * x;
来源：http://dali.iojbl.cn/Article/details/gtmowyrdgg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtglqyyheq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.sysykeji.top/Article/details/gtfhsvmina.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.chenlongwang.top/Article/details/gtpagftemu.html

Ruby: square = ->(x) { x * x }
来源：http://dali.svipenyu.cn/Article/details/gtifoorwcz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yangfankeji.com/Article/details/gtpbxqsoyt.html

[C07] 把函数作为参数传入
来源：http://dali.hnqzz.top/Article/details/gtjqrodvgh.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ivvv.top/Article/details/gtwzsifhez.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtdezyefsw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cdnleiting.top/Article/details/gtxrolekvk.html

TS:   arr.map(String)
来源：http://dali.pengpengdd.cyou/Article/details/gttppbzrrv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cucudq.cn/Article/details/gtgxosrymx.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.gogol.net.cn/Article/details/gtgqcdeuqp.html

Ruby: arr.map(&:upcase)
来源：http://dali.svipenyu.cn/Article/details/gtdotnmmnu.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ydzc1.top/Article/details/gtbxizlimu.html

[C08] 闭包
来源：http://dali.yangfankeji.com/Article/details/gtxipmynoq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yvedp.cn/Article/details/gtmzzlzqdb.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.tanke756.top/Article/details/gtrfrianjr.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cucudq.cn/Article/details/gtgeankyuk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xinyue.icu/Article/details/gttbpjntld.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.haohaochexian.top/Article/details/gtqahpywvo.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtascmmavc.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yangfankeji.com/Article/details/gtbvkdgjog.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.dashuyun.cn/Article/details/gtsjshqwau.html

[C09] 递归
来源：http://dali.mhx1999.top/Article/details/gtsqnjpqcr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkpxuhwji.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.dianchejie.cn/Article/details/gtpdnzxfem.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yuxming.cn/Article/details/gttztvjmpr.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj202588.top/Article/details/gtfcjomkbc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.smart0.xyz/Article/details/gtnywimnjl.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yongpay.top/Article/details/gtaikjsoyo.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtunyyciuc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.kuanghao11.cn/Article/details/gtpzkxlnti.html

[C10] 变量作用域
来源：http://dali.hnqzz.top/Article/details/gtjcmiemsa.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hnqzz.top/Article/details/gtkgwotvrf.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hammf.cn/Article/details/gtlclecyyx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cqqwz.cn/Article/details/gtaaiswrrs.html

TS:   同 JS
来源：http://dali.guowangkeji.top/Article/details/gtkqaghtsd.html

Java: 方法内为块级作用域
来源：http://dali.shuidangran.top/Article/details/gttoggwgce.html

Go:   花括号块级作用域
来源：http://dali.hnqzz.top/Article/details/gtecuukxco.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ydzc1.top/Article/details/gtuatcvrxu.html

C#:   块级作用域
来源：http://dali.iojbl.cn/Article/details/gtvnichcqb.html

[C11] 模块导入与导出
来源：http://dali.shzxlz.cn/Article/details/gtqxjskwok.html

Py:   from module import func
来源：http://dali.snrcjt.cn/Article/details/gtoqrfsliy.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cheryme.top/Article/details/gtzvqazagp.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhiwuduotai.top/Article/details/gtzehtsfps.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.wangshuangyany.cn/Article/details/gtogisjkof.html

Java: import java.util.List;
来源：http://dali.dashuyun.cn/Article/details/gtxdtpukqo.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yj20258888.top/Article/details/gtrakpixsq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.tianlin.xyz/Article/details/gtehxoktzv.html

C#:   using System.Text;
来源：http://dali.yuxming.cn/Article/details/gtscxbuojc.html

[C12] 立即执行函数 IIFE
来源：http://dali.xuetiantiany.cn/Article/details/gtuuqhpilr.html

Py:   (lambda: print("run"))()
来源：http://dali.fengsongda.top/Article/details/gtkywdfckp.html

PHP:  (function () { echo "run"; })();
来源：http://dali.dashuyun.cn/Article/details/gtwfiyamas.html

JS:   (() => { console.log("run"); })();
来源：http://dali.fengsongda.top/Article/details/gtbndohpzc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.snrcjt.cn/Article/details/gtmitkbpkj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.nwbrower.top/Article/details/gtvfdefxxb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.haohaochexian.top/Article/details/gtlnyxvggk.html

Ruby: -> { puts "run" }.call
来源：http://dali.xziqi.cn/Article/details/gtnyieytpu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.bjfxy.top/Article/details/gtqadprtwi.html

[C13] 类型声明 / 类型注解
来源：http://dali.jyoumei.cn/Article/details/gtmqbalqxu.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cashguo.top/Article/details/gtcpolconh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhixingplan.top/Article/details/gtcmfogzgm.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xuanzx.com/Article/details/gtaghrxjox.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtapwxpajj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gtxyshlkfw.html

Go:   func add(a, b int) int
来源：http://dali.9152youxi.cn/Article/details/gtvvfzprgz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.bjfxy.top/Article/details/gttzbegqjm.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yongpay.top/Article/details/gtvckefsxv.html

[C14] 泛型函数
来源：http://dali.xziqi.cn/Article/details/gtvxpnahkp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.sxryk.cn/Article/details/gttzwpwwvb.html

PHP:  // 无泛型
来源：http://dali.guannengcc.top/Article/details/gtlurtzvhi.html

JS:   // 无泛型
来源：http://dali.sufxvd.cn/Article/details/gtahjkcpmg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.nanxinkj.top/Article/details/gtafaovbwz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gaohongyu789.top/Article/details/gtaqiwesuk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gogol.net.cn/Article/details/gtcddfsvqp.html

Ruby: # 无泛型
来源：http://dali.chenjidiqi.icu/Article/details/gtiztuzuqp.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zycfv.cn/Article/details/gtvevahtbg.html

[C15] 解构 / 展开参数
来源：http://dali.jyoumei.cn/Article/details/gtgsjymrih.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyblsmdty.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shanyushiyangtech.top/Article/details/gtwpcfumit.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.0kj1m.cn/Article/details/gtpjqvcxpi.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtupuxrits.html

Java: // 无解构
来源：http://dali.tanke756.top/Article/details/gtgauuotom.html

Go:   // 无解构
来源：http://dali.aizwys.cn/Article/details/gtzzmlhspg.html

Ruby: a, b = pair
来源：http://dali.cqqwz.cn/Article/details/gtvkrmvtue.html

C#:   var (a, b) = pair;
来源：http://dali.jyoumei.cn/Article/details/gtfxcsouam.html

[C16] 函数 / 方法重载
来源：http://dali.guannengcc.top/Article/details/gtfbbaemyj.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.iojbl.cn/Article/details/gtaqoeqllf.html

PHP:  // 无重载
来源：http://dali.xuetiantiany.cn/Article/details/gtvpmowson.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yonumen.top/Article/details/gtlblsvory.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cashguo.top/Article/details/gtiawadrfl.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shuidangran.top/Article/details/gtksuroqzl.html

Go:   // 无重载：用不同函数名
来源：http://dali.smart0.xyz/Article/details/gtbdkqfsxp.html

Ruby: # 无重载：靠动态参数
来源：http://dali.vqdsnc.cn/Article/details/gtsnzsarho.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.snrcjt.cn/Article/details/gtfhkvmnny.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtkodwnrgx.html

D. 数组 / 列表 / 集合
来源：http://dali.xziqi.cn/Article/details/gtvdtlibcr.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtxjsonpck.html

[D01] 创建数组 / 列表
来源：http://dali.hnxiangtu.top/Article/details/gtkusqdkjx.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ppjwa.cn/Article/details/gthfugvohl.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.sxryk.cn/Article/details/gtxceglhdj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtejyyernv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cheryme.top/Article/details/gtaitiflzx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cqqwz.cn/Article/details/gtpfixipzx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.tianlin.xyz/Article/details/gtxjpsbnha.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sufxvd.cn/Article/details/gtileqongl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.c1oappe.top/Article/details/gtdtfzxeji.html

[D02] 追加元素到末尾
来源：http://dali.yanxiufei.cn/Article/details/gtgeithhgq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.havefunace.top/Article/details/gtvrmijfso.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.kuanghao11.cn/Article/details/gtkczglzst.html

JS:   arr.push(4);
来源：http://dali.0kj1m.cn/Article/details/gtytpfmscb.html

TS:   arr.push(4);
来源：http://dali.tian-w.cn/Article/details/gtouncwmpb.html

Java: list.add(4);
来源：http://dali.jyoumei.cn/Article/details/gtfylallka.html

Go:   arr = append(arr, 4)
来源：http://dali.dashuyun.cn/Article/details/gtbmecerhg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.nanxuanxn.top/Article/details/gtysqxwlvh.html

C#:   list.Add(4);
来源：http://dali.jqgufenzy.top/Article/details/gtnlydqysg.html

[D03] 在指定位置插入元素
来源：http://dali.birdmap.top/Article/details/gtactquzfp.html

Py:   arr.insert(0, 0)
来源：http://dali.c1oappe.top/Article/details/gtsmquhmyo.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ydzc1.top/Article/details/gtbtnutkok.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xziqi.cn/Article/details/gtozvgqdpy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hywenlv.cn/Article/details/gtrttqcjnt.html

Java: list.add(0, 0);
来源：http://dali.yonumen.top/Article/details/gtqvnnheqb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.chenlongwang.top/Article/details/gthxhscgpg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.redwolf501.top/Article/details/gtdvomlcqa.html

C#:   list.Insert(0, 0);
来源：http://dali.vqdsnc.cn/Article/details/gtofzwzqhy.html

[D04] 删除元素
来源：http://dali.jqgfzy.top/Article/details/gtbvfhpqgb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hnxiangtu.top/Article/details/gtjccmxpml.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.fengsongda.top/Article/details/gtwndiecmb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhengqikj.top/Article/details/gtjaohbntd.html

TS:   arr.splice(0, 1);
来源：http://dali.shanyushiyangtech.top/Article/details/gthzkjfwfd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cucudq.cn/Article/details/gtgyrbfogq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jinyuanbaomall.cn/Article/details/gteptqomej.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cashguo.top/Article/details/gtmkrmfrtd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sufxvd.cn/Article/details/gthswfybbb.html

[D05] 访问与修改元素
来源：http://dali.fengsongda.top/Article/details/gtjugijiwb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangshuangyany.cn/Article/details/gtrtgacffp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinqigufen.top/Article/details/gtrprmbgnm.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.dianchejie.cn/Article/details/gtbjjigijv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwuieckho.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhaomingkeji.xyz/Article/details/gteocagdhy.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.fzhhl.top/Article/details/gtirugcebl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zycfv.cn/Article/details/gtevtpsvps.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hammf.cn/Article/details/gtsnkeojou.html

[D06] 数组长度
来源：http://dali.jqgufenzy.top/Article/details/gtsystwwii.html

Py:   len(arr)
来源：http://dali.nanxinkj.top/Article/details/gtthjzbsic.html

PHP:  count($arr);
来源：http://dali.guowangkeji.top/Article/details/gtwypcochf.html

JS:   arr.length
来源：http://dali.meibo888.top/Article/details/gtqouzsivt.html

TS:   arr.length
来源：http://dali.yuxming.cn/Article/details/gtvmwkkept.html

Java: list.size();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpafpzvea.html

Go:   len(arr)
来源：http://dali.wangdashe.top/Article/details/gtaqdjalim.html

Ruby: arr.length; arr.size
来源：http://dali.zhongyouzk.top/Article/details/gtydlgtrzy.html

C#:   list.Count;
来源：http://dali.snrcjt.cn/Article/details/gtuttpidhs.html

[D07] 切片 / 取子数组
来源：http://dali.zycfv.cn/Article/details/gtyfpqolaa.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yueranfly.top/Article/details/gtrmkyqplq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinqigufen.top/Article/details/gtlfamnofo.html

JS:   arr.slice(1, 4);
来源：http://dali.wangshuangyany.cn/Article/details/gtsizzvfhj.html

TS:   arr.slice(1, 4);
来源：http://dali.hysaishi.cn/Article/details/gtaegbarqi.html

Java: list.subList(1, 4);
来源：http://dali.sweek.top/Article/details/gtdhmhhppk.html

Go:   arr[1:4]
来源：http://dali.chenjidiqi.icu/Article/details/gtlfuphbgs.html

Ruby: arr[1, 3]
来源：http://dali.gotoacloud.top/Article/details/gtzekbhxcv.html

C#:   list.GetRange(1, 3);
来源：http://dali.yueranfly.top/Article/details/gtfcdkigxt.html

[D08] 合并两个数组
来源：http://dali.hywenlv.cn/Article/details/gtoioakqmo.html

Py:   a + b;  a.extend(b)
来源：http://dali.vqdsnc.cn/Article/details/gthijstskh.html

PHP:  array_merge($a, $b);
来源：http://dali.yonumen.top/Article/details/gtwadpbmkx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgwtexckg.html

TS:   [...a, ...b];
来源：http://dali.nanxuanxn.top/Article/details/gtujuobiuk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jinqigufen.top/Article/details/gthbrfiftt.html

Go:   append(a, b...)
来源：http://dali.aibaodan.cn/Article/details/gtauhyqhne.html

Ruby: a + b;  a.concat(b)
来源：http://dali.tanke756.top/Article/details/gtrvdlpcxp.html

C#:   a.Concat(b).ToList()
来源：http://dali.aizwys.cn/Article/details/gtulwxxekx.html

[D09] 排序（升序）
来源：http://dali.aibaodan.cn/Article/details/gtqazijnbp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigfzy.top/Article/details/gtrnlppbui.html

PHP:  sort($arr);
来源：http://dali.xziqi.cn/Article/details/gtrhbevlow.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.daria6918.cn/Article/details/gthbgtsmet.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yongpay.top/Article/details/gtvezwjdzt.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.mhx1999.top/Article/details/gtymkyelza.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ivvv.top/Article/details/gtlegezoyr.html

Ruby: arr.sort
来源：http://dali.jinqigufen.top/Article/details/gtxbqabvvm.html

C#:   list.Sort();
来源：http://dali.svipenyu.cn/Article/details/gtdztqfbvi.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhengqikj.top/Article/details/gtebtfaoef.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yongpay.top/Article/details/gteybzykwb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gtxcbqowol.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hywenlv.cn/Article/details/gtdiqztwzy.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.feifeiyinyue.top/Article/details/gtrppzgkqh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ivvv.top/Article/details/gtvjplpprk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.daria6918.cn/Article/details/gtalnnxkpk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.tianlin.xyz/Article/details/gtimqxpuxn.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.daria6918.cn/Article/details/gtwncnmela.html

[D11] 反转数组
来源：http://dali.xuanzx.com/Article/details/gtodcdrjpg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jqgufenzy.top/Article/details/gtjhahexjd.html

PHP:  array_reverse($arr);
来源：http://dali.xylfe.cn/Article/details/gtfhzwhsbu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xuetiantiany.cn/Article/details/gttfrasmuw.html

TS:   [...arr].reverse();
来源：http://dali.316326.xyz/Article/details/gtrzxosrzu.html

Java: Collections.reverse(list);
来源：http://dali.kuanghao11.cn/Article/details/gtonrjnlet.html

Go:   slices.Reverse(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtwduhints.html

Ruby: arr.reverse
来源：http://dali.jqgufenzy.top/Article/details/gtzagkmzeu.html


<!-- 参考信息 -->