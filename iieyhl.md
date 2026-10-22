代发 wailian999

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.aibaodan.cn/Article/details/gtkxhcxxqq.html

Ruby: (0...10).step(2).to_a
来源：http://dali.mhx1999.top/Article/details/gtvjfauydk.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.wangdashe.top/Article/details/gtknttohiu.html

[B12] 跳出多层循环
来源：http://dali.birdmap.top/Article/details/gtxymbvefr.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwkkiflon.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.gogol.net.cn/Article/details/gtionpkmzr.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.aibaodan.cn/Article/details/gtdprnmlrk.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xylfe.cn/Article/details/gtrmuepnbj.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.shzxlz.cn/Article/details/gtnzxevbyu.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zycfv.cn/Article/details/gtxnhbkcye.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ehwqpu.com/Article/details/gtnhujtyqr.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhixingplan.top/Article/details/gtlzmkodgq.html

[B13] 判断是否为数字
来源：http://dali.hnxiangtu.top/Article/details/gtlzavgwjk.html

Py:   isinstance(x, (int, float))
来源：http://dali.ybcxt.top/Article/details/gtqolyydgf.html

PHP:  is_numeric($x)
来源：http://dali.cashguo.top/Article/details/gtjqkhvhfr.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.9152youxi.cn/Article/details/gtejmouqsj.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.havefunace.top/Article/details/gtlrjbhjcn.html

Java: x instanceof Number
来源：http://dali.pycfn.com/Article/details/gtxxpbexwy.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.feifeiyinyue.top/Article/details/gtyjykyiux.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpswumwkv.html

C#:   x is int or double or decimal
来源：http://dali.birdmap.top/Article/details/gtxzevfhkp.html

[B14] 判断值是否在集合内
来源：http://dali.tanke756.top/Article/details/gtwkrvipxr.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jqgufenzy.top/Article/details/gtavzqryoi.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.nanxuanxn.top/Article/details/gtegqesgqd.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hywenlv.cn/Article/details/gthhnbrptb.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.snrcjt.cn/Article/details/gtjtocvssz.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.fengsongda.top/Article/details/gtdljrrewh.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkfjtjzso.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.havefunace.top/Article/details/gtyqepurfg.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jyoumei.cn/Article/details/gtujvktlzd.html

[B15] 布尔运算与取反
来源：http://dali.bjfxy.top/Article/details/gthpcybraj.html

Py:   a and b or not c
来源：http://dali.svipenyu.cn/Article/details/gtwdynmitj.html

PHP:  $a && $b || !$c
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgyuafbxd.html

JS:   a && b || !c
来源：http://dali.birdmap.top/Article/details/gtzbkxzlta.html

TS:   a && b || !c
来源：http://dali.yonumen.top/Article/details/gtiveqaurm.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gtctqdrlio.html

Go:   a && b || !c
来源：http://dali.svipenyu.cn/Article/details/gtfhsjvqxx.html

Ruby: a && b || !c
来源：http://dali.tian-w.cn/Article/details/gtqmefbbuy.html

C#:   a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gtlulxziko.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.svipenyu.cn/Article/details/gtumlavult.html

Py:   if not data: return
来源：http://dali.ivvv.top/Article/details/gtrhpwzkih.html

PHP:  if (!$data) { return; }
来源：http://dali.hnxiangtu.top/Article/details/gtavxpraop.html

JS:   if (!data) return;
来源：http://dali.dianchejie.cn/Article/details/gticotyyjv.html

TS:   if (!data) return;
来源：http://dali.jqgufenzy.top/Article/details/gtqtuvidyn.html

Java: if (data == null) return;
来源：http://dali.haohaochexian.top/Article/details/gtissntbeb.html

Go:   if data == nil { return }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwdhccwwz.html

Ruby: return if data.nil?
来源：http://dali.ydzc1.top/Article/details/gtwyudfdba.html

C#:   if (data == null) return;
来源：http://dali.jyoumei.cn/Article/details/gtomcrvbky.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtgfiioqbq.html

C. 函数与作用域
来源：http://dali.cashguo.top/Article/details/gtujpnwexc.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtiuoswhfx.html

[C01] 定义函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyuqcmcoe.html

Py:   def add(a, b): return a + b
来源：http://dali.wangdashe.top/Article/details/gtfrltkmow.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.vqdsnc.cn/Article/details/gtnwhiuove.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gtuvjhqeko.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gtzfudwrwc.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gtslurbjpq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.bjfxy.top/Article/details/gtzibwtnnt.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhengqikj.top/Article/details/gtczparpme.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtepuvetrj.html

[C02] 默认参数
来源：http://dali.yj202588.top/Article/details/gtabfpqpna.html

Py:   def greet(name="World"): return name
来源：http://dali.kuanghao11.cn/Article/details/gtupbxijrv.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jlsjyb.cn/Article/details/gtdsmxzwzu.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yangfankeji.com/Article/details/gtkakxmnzx.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.aibaodan.cn/Article/details/gtmfjyhips.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zdqjudy.top/Article/details/gttzjuywum.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yongpay.top/Article/details/gtitzzwmau.html

Ruby: def greet(name = "World") = name
来源：http://dali.havefunace.top/Article/details/gttrgvnhcv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.haohaochexian.top/Article/details/gtkbxlivff.html

[C03] 可变参数
来源：http://dali.gotoacloud.top/Article/details/gtdhxooqlh.html

Py:   def total(*args): return sum(args)
来源：http://dali.meibo888.top/Article/details/gtkzvmnafv.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xylfe.cn/Article/details/gtowofigmt.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.snrcjt.cn/Article/details/gtqebgbfyb.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xinyue.icu/Article/details/gtjqqeljnn.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhoulong.xyz/Article/details/gtrsqmmxsk.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.c1oappe.top/Article/details/gtbehgcfqa.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sweek.top/Article/details/gtnnvjtppw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hysaishi.cn/Article/details/gtmqjnrgqc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.smart0.xyz/Article/details/gtuflxbuxj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.guannengcc.top/Article/details/gttfieddkw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.gogol.net.cn/Article/details/gtmfraodjq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.sufxvd.cn/Article/details/gtxoabvrga.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jinyuanbaomall.cn/Article/details/gtullzhezz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ybcxt.top/Article/details/gtkejnbwmw.html

Go:   // 无：用配置结构体参数
来源：http://dali.cucudq.cn/Article/details/gtfactdfic.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jinqigufen.top/Article/details/gtrzaxurfx.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gtktljplze.html

[C05] 返回多个值
来源：http://dali.jqgufenzy.top/Article/details/gtfbedklya.html

Py:   return a, b
来源：http://dali.hysaishi.cn/Article/details/gtvwturwwf.html

PHP:  return [$a, $b];
来源：http://dali.cqqwz.cn/Article/details/gtkmliaisl.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.bjfxy.top/Article/details/gtlqcczdry.html

TS:   return { a, b };
来源：http://dali.shzxlz.cn/Article/details/gtcibrqmvw.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.svipenyu.cn/Article/details/gtnkoisqse.html

Go:   return a, b
来源：http://dali.svipenyu.cn/Article/details/gtzmfioecv.html

Ruby: return a, b
来源：http://dali.daria6918.cn/Article/details/gtmxqsotsf.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.pycfn.com/Article/details/gtnzbkbngn.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gtyjllvrmn.html

Py:   square = lambda x: x * x
来源：http://dali.wangshuangyany.cn/Article/details/gtcsjwffnt.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hfpthk.cn/Article/details/gtierxvkrq.html

JS:   const square = x => x * x;
来源：http://dali.yangfankeji.com/Article/details/gttkhuzjin.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.haohaochexian.top/Article/details/gtxzrucbht.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hnxiangtu.top/Article/details/gteyivwcuh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtavztzdwh.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yangfankeji.com/Article/details/gtryirlbio.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ivvv.top/Article/details/gtvpwpcoca.html

[C07] 把函数作为参数传入
来源：http://dali.shzxlz.cn/Article/details/gtnhnfnaax.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.iojbl.cn/Article/details/gttxrtmohf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.0kj1m.cn/Article/details/gttkgfacrz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.nanxinkj.top/Article/details/gtqenfxjjd.html

TS:   arr.map(String)
来源：http://dali.jqgfzy.top/Article/details/gtvvqsboex.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.pycfn.com/Article/details/gtbmazqgul.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.nanxuanxn.top/Article/details/gtfqaugaqv.html

Ruby: arr.map(&:upcase)
来源：http://dali.dianchejie.cn/Article/details/gtvlufnfom.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgfgitcrf.html

[C08] 闭包
来源：http://dali.guannengcc.top/Article/details/gtksporfpn.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.haohaochexian.top/Article/details/gtorhgwhmf.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.316326.xyz/Article/details/gtmqirsxsu.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jqgufenzy.top/Article/details/gtcksqdjxi.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.birdmap.top/Article/details/gtubzrxwfi.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.birdmap.top/Article/details/gtuduthilf.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jinqigfzy.top/Article/details/gtcniatool.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.smart0.xyz/Article/details/gthcqbwapt.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.chenjidiqi.icu/Article/details/gtpltjrhcs.html

[C09] 递归
来源：http://dali.shzxlz.cn/Article/details/gtbisfffhj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ydzc1.top/Article/details/gtbsyftzaa.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hongshengwenyu.top/Article/details/gttxixxixj.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgufenzy.top/Article/details/gtvzqtakjw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ivvv.top/Article/details/gtlucohjxx.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xinyue.icu/Article/details/gtovnekluv.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhiwuduotai.top/Article/details/gthjlxmkcu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.bjfxy.top/Article/details/gtoqrqblhd.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jqgfzy.top/Article/details/gtsepeenaf.html

[C10] 变量作用域
来源：http://dali.jinqigufen.top/Article/details/gtuwyagqix.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yongpay.top/Article/details/gtophywajp.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.dianchejie.cn/Article/details/gtovefthzp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.9152youxi.cn/Article/details/gtfsbphaul.html

TS:   同 JS
来源：http://dali.jinghuilouyu.cn/Article/details/gtgtbrvezh.html

Java: 方法内为块级作用域
来源：http://dali.gotoacloud.top/Article/details/gtzqqkhxgg.html

Go:   花括号块级作用域
来源：http://dali.ehwqpu.com/Article/details/gtksjbcrse.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.snrcjt.cn/Article/details/gtzjtnxqsf.html

C#:   块级作用域
来源：http://dali.shangyingyoupin.top/Article/details/gtaejoisdw.html

[C11] 模块导入与导出
来源：http://dali.c1oappe.top/Article/details/gtngkmqwnu.html

Py:   from module import func
来源：http://dali.smart0.xyz/Article/details/gtsnbgkcve.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.tanke756.top/Article/details/gtbnohxiwh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cqqwz.cn/Article/details/gtxrwzhklz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhongyouzk.top/Article/details/gthmafoylq.html

Java: import java.util.List;
来源：http://dali.jinqigfzy.top/Article/details/gtwdufvboq.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yongpay.top/Article/details/gtvupiaxwx.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shuidangran.top/Article/details/gtiksxdswz.html

C#:   using System.Text;
来源：http://dali.xziqi.cn/Article/details/gtgmqilvlj.html

[C12] 立即执行函数 IIFE
来源：http://dali.yuanzhike.top/Article/details/gtpasogepn.html

Py:   (lambda: print("run"))()
来源：http://dali.kuanghao11.cn/Article/details/gtjtfluycj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jinqigufen.top/Article/details/gtachivwmg.html

JS:   (() => { console.log("run"); })();
来源：http://dali.wangdashe.top/Article/details/gtgyrkzfff.html

TS:   (() => { console.log("run"); })();
来源：http://dali.0kj1m.cn/Article/details/gtcmpnemod.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sxryk.cn/Article/details/gtujtvrsan.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhixingplan.top/Article/details/gtlmzragat.html

Ruby: -> { puts "run" }.call
来源：http://dali.havefunace.top/Article/details/gtfejkgeru.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hywenlv.cn/Article/details/gtuholvxeo.html

[C13] 类型声明 / 类型注解
来源：http://dali.sweek.top/Article/details/gtyevwajvj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.9152youxi.cn/Article/details/gtenjehvxg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.mhx1999.top/Article/details/gtororkklx.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xuetiantiany.cn/Article/details/gtfblhoywy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gtuxqnimde.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gtqkoxmlmr.html

Go:   func add(a, b int) int
来源：http://dali.ydzc1.top/Article/details/gtwsipmjzs.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cashguo.top/Article/details/gthkilfwjc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtszswdurs.html

[C14] 泛型函数
来源：http://dali.fzhhl.top/Article/details/gtuzafgheh.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hammf.cn/Article/details/gtuooakkpp.html

PHP:  // 无泛型
来源：http://dali.yanxiufei.cn/Article/details/gtiavxlkhj.html

JS:   // 无泛型
来源：http://dali.gotoacloud.top/Article/details/gtslgfliub.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.guannengcc.top/Article/details/gtrptzkyfj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.tianlin.xyz/Article/details/gthscgjlcl.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ppjwa.cn/Article/details/gtxdtjckmg.html

Ruby: # 无泛型
来源：http://dali.pycfn.com/Article/details/gtjkjmsjvb.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xziqi.cn/Article/details/gteknrowjy.html

[C15] 解构 / 展开参数
来源：http://dali.zhengqikj.top/Article/details/gtkppsjhxf.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.meibo888.top/Article/details/gtampdkqso.html

PHP:  [$a, $b] = $pair;
来源：http://dali.feifeiyinyue.top/Article/details/gtmghxvytd.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.wangdashe.top/Article/details/gtxmwsagxk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gtyegqwdzn.html

Java: // 无解构
来源：http://dali.redwolf501.top/Article/details/gthxwjbslz.html

Go:   // 无解构
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmftzqvzn.html

Ruby: a, b = pair
来源：http://dali.ehwqpu.com/Article/details/gtyasdbboe.html

C#:   var (a, b) = pair;
来源：http://dali.sysykeji.top/Article/details/gtoilampxm.html

[C16] 函数 / 方法重载
来源：http://dali.havefunace.top/Article/details/gtgmgjnnlv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yanxiufei.cn/Article/details/gtigmmfase.html

PHP:  // 无重载
来源：http://dali.yuanzhike.top/Article/details/gtrhtotwbf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.tianlin.xyz/Article/details/gtdseaxbpp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gtmjpknbxg.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.haohaochexian.top/Article/details/gtjlmabpow.html

Go:   // 无重载：用不同函数名
来源：http://dali.cqqwz.cn/Article/details/gtkyuvfhhd.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cqqwz.cn/Article/details/gtzvkppypf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ybcxt.top/Article/details/gttiiwhwun.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gthkjfqrlj.html

D. 数组 / 列表 / 集合
来源：http://dali.yonumen.top/Article/details/gtrooqnwbb.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtndzblnzb.html

[D01] 创建数组 / 列表
来源：http://dali.daria6918.cn/Article/details/gtcjkthsen.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yuxming.cn/Article/details/gtonfyfigo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhengqikj.top/Article/details/gtcuiqgdfr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.pycfn.com/Article/details/gtekpjuyrg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jianghu66.top/Article/details/gtlyzhygpk.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hongshengwenyu.top/Article/details/gtzaehavbr.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.daria6918.cn/Article/details/gtkaxncvsh.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hongshengwenyu.top/Article/details/gtlamsoetl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.svipenyu.cn/Article/details/gtmynvtngl.html

[D02] 追加元素到末尾
来源：http://dali.gogol.net.cn/Article/details/gthpnhujgv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.tianlin.xyz/Article/details/gtfpebmssc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.sweek.top/Article/details/gtkhkvrrco.html

JS:   arr.push(4);
来源：http://dali.yj20258888.top/Article/details/gtcngawxbg.html

TS:   arr.push(4);
来源：http://dali.zhiwuduotai.top/Article/details/gttkdfycpx.html

Java: list.add(4);
来源：http://dali.yangfankeji.com/Article/details/gtzolwdsim.html

Go:   arr = append(arr, 4)
来源：http://dali.yuanzhike.top/Article/details/gtcntwuffc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xinyue.icu/Article/details/gtdrmkjoot.html

C#:   list.Add(4);
来源：http://dali.wangdashe.top/Article/details/gtvlfggwov.html

[D03] 在指定位置插入元素
来源：http://dali.zhengqikj.top/Article/details/gtnforrmyf.html

Py:   arr.insert(0, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtkjuifvnl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpittqcgi.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhixingplan.top/Article/details/gtgxqhefkk.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhoulong.xyz/Article/details/gtsoslagtn.html

Java: list.add(0, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcnvkvuhv.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yj20258888.top/Article/details/gtlguldiam.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hywenlv.cn/Article/details/gthvdbiwkk.html

C#:   list.Insert(0, 0);
来源：http://dali.guowangkeji.top/Article/details/gtfyhgtrwn.html

[D04] 删除元素
来源：http://dali.pengpengdd.cyou/Article/details/gtdysyroeq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.guowangkeji.top/Article/details/gtoqrehmsc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jianghu66.top/Article/details/gtnkaakrgn.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.mhx1999.top/Article/details/gtduftlosb.html

TS:   arr.splice(0, 1);
来源：http://dali.zycfv.cn/Article/details/gtprlanhot.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gogol.net.cn/Article/details/gtljysdkgy.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gotoacloud.top/Article/details/gtkrifdccu.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yongpay.top/Article/details/gtotdguwin.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hywenlv.cn/Article/details/gtiuvljmdi.html

[D05] 访问与修改元素
来源：http://dali.hysaishi.cn/Article/details/gtddmiozoe.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gaohongyu789.top/Article/details/gtakswrlec.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cucudq.cn/Article/details/gtpijlahzb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.fzhhl.top/Article/details/gtodesqdai.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.snrcjt.cn/Article/details/gtcdirksmm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yanxiufei.cn/Article/details/gtykdkjmzv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cdnleiting.top/Article/details/gthqnhrpri.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgufenzy.top/Article/details/gttgkalyzh.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ehwqpu.com/Article/details/gtjpwbhwce.html

[D06] 数组长度
来源：http://dali.jqgufenzy.top/Article/details/gtfkrvaqso.html

Py:   len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtxbxgwonk.html

PHP:  count($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtaqzqkniu.html

JS:   arr.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuepidamj.html

TS:   arr.length
来源：http://dali.mhx1999.top/Article/details/gtyqooubyr.html

Java: list.size();
来源：http://dali.nanxinkj.top/Article/details/gtkfzojvjb.html

Go:   len(arr)
来源：http://dali.xuanzx.com/Article/details/gtqrkpljjw.html

Ruby: arr.length; arr.size
来源：http://dali.fzhhl.top/Article/details/gtczcgxojx.html

C#:   list.Count;
来源：http://dali.jinqigufen.top/Article/details/gtsmoegzhm.html

[D07] 切片 / 取子数组
来源：http://dali.snrcjt.cn/Article/details/gtzwdebwua.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnbbqoxzx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinqigufen.top/Article/details/gtwatoeruo.html

JS:   arr.slice(1, 4);
来源：http://dali.hnqzz.top/Article/details/gtuklghndc.html

TS:   arr.slice(1, 4);
来源：http://dali.yueranfly.top/Article/details/gtkezafirw.html

Java: list.subList(1, 4);
来源：http://dali.aibaodan.cn/Article/details/gtsmrtfrus.html

Go:   arr[1:4]
来源：http://dali.birdmap.top/Article/details/gtqpdomuyo.html

Ruby: arr[1, 3]
来源：http://dali.zhongyouzk.top/Article/details/gtdhkwnprx.html

C#:   list.GetRange(1, 3);
来源：http://dali.gzhubu.top/Article/details/gtywopybso.html

[D08] 合并两个数组
来源：http://dali.xinyue.icu/Article/details/gtrxjpouca.html

Py:   a + b;  a.extend(b)
来源：http://dali.vqdsnc.cn/Article/details/gtoxelnmiq.html

PHP:  array_merge($a, $b);
来源：http://dali.yonumen.top/Article/details/gtdwgcnquj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhiwuduotai.top/Article/details/gtvupelpuw.html

TS:   [...a, ...b];
来源：http://dali.jqgufenzy.top/Article/details/gtcpowdhvp.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yangfankeji.com/Article/details/gtxrxuknka.html

Go:   append(a, b...)
来源：http://dali.jyoumei.cn/Article/details/gtegqcxkck.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yj20258888.top/Article/details/gtrmwaplth.html

C#:   a.Concat(b).ToList()
来源：http://dali.tian-w.cn/Article/details/gtciuspruh.html

[D09] 排序（升序）
来源：http://dali.iojbl.cn/Article/details/gtknzewacc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jyoumei.cn/Article/details/gtkzowbnab.html

PHP:  sort($arr);
来源：http://dali.yueranfly.top/Article/details/gtmpdxsfwg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hnxiangtu.top/Article/details/gtfewpfnur.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.nwbrower.top/Article/details/gtojyeamul.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yonumen.top/Article/details/gtdqdjnjbz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.aizwys.cn/Article/details/gtdyiiiufv.html

Ruby: arr.sort
来源：http://dali.0kj1m.cn/Article/details/gtxkkobsrp.html

C#:   list.Sort();
来源：http://dali.hfpthk.cn/Article/details/gtzhrzsepa.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cqqwz.cn/Article/details/gtsihwdqcx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yuxming.cn/Article/details/gtemjawxhp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhongyouzk.top/Article/details/gtjkfgelug.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinqigufen.top/Article/details/gtxoysoziy.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.meibo888.top/Article/details/gteyxyrqlu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zdqjudy.top/Article/details/gtezotiqam.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.daxiang520.top/Article/details/gtyfehbaza.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdpaybpuq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jianghu66.top/Article/details/gtpnabmdhj.html

[D11] 反转数组
来源：http://dali.hfpthk.cn/Article/details/gtchhuhirn.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.andypj.xyz/Article/details/gttbheozgt.html

PHP:  array_reverse($arr);
来源：http://dali.zhixingplan.top/Article/details/gtpomhvsia.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yanxiufei.cn/Article/details/gtyigtrpxg.html

TS:   [...arr].reverse();
来源：http://dali.zhiwuduotai.top/Article/details/gtyyffdwuu.html

Java: Collections.reverse(list);
来源：http://dali.meibo888.top/Article/details/gtoglogmyv.html

Go:   slices.Reverse(arr)
来源：http://dali.tianlin.xyz/Article/details/gtabyoqswi.html

Ruby: arr.reverse
来源：http://dali.gotoacloud.top/Article/details/gttsuizpyu.html

C#:   list.Reverse();
来源：http://dali.yueranfly.top/Article/details/gtyakreqrc.html

[D12] 查找元素下标
来源：http://dali.aizwys.cn/Article/details/gtlnxbdsvi.html

Py:   arr.index(x);  x in arr
来源：http://dali.fengsongda.top/Article/details/gttnbrfohb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yonumen.top/Article/details/gtdkwqovyy.html


<!-- 参考信息 -->