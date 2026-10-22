代发 wailian999

[B13] 判断是否为数字
来源：http://dali.hongshengwenyu.top/Article/details/gtpjrlkjrz.html

Py:   isinstance(x, (int, float))
来源：http://dali.0kj1m.cn/Article/details/gtundksnun.html

PHP:  is_numeric($x)
来源：http://dali.hysaishi.cn/Article/details/gtzljctwrg.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.aibaodan.cn/Article/details/gtexatibir.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxxlxnthz.html

Java: x instanceof Number
来源：http://dali.iojbl.cn/Article/details/gtgbzuxxqk.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xuetiantiany.cn/Article/details/gttpotfuuz.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yj20258888.top/Article/details/gtqywmcjgg.html

C#:   x is int or double or decimal
来源：http://dali.yj202588.top/Article/details/gtmwcvkejv.html

[B14] 判断值是否在集合内
来源：http://dali.smart0.xyz/Article/details/gtldkvkflu.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gtqzmdxkep.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.smart0.xyz/Article/details/gtnhlgmpov.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xuanzx.com/Article/details/gtrgjjixkt.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.gzhubu.top/Article/details/gtmtzzceoc.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.svipenyu.cn/Article/details/gtmliwwkrs.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyztmfjpv.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yongpay.top/Article/details/gtggkacjzo.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yangfankeji.com/Article/details/gtpzqtbyyn.html

[B15] 布尔运算与取反
来源：http://dali.zhongyouzk.top/Article/details/gtlbgnmsvf.html

Py:   a and b or not c
来源：http://dali.sweek.top/Article/details/gticbhqsqb.html

PHP:  $a && $b || !$c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtezqtthap.html

JS:   a && b || !c
来源：http://dali.tianlin.xyz/Article/details/gtnshpbmjk.html

TS:   a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gtkjemhlua.html

Java: a && b || !c
来源：http://dali.yueranfly.top/Article/details/gtylkhbtmr.html

Go:   a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gtqeflcdkw.html

Ruby: a && b || !c
来源：http://dali.daxiang520.top/Article/details/gtfejhcqql.html

C#:   a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gtooumjykx.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.meibo888.top/Article/details/gtztrogejd.html

Py:   if not data: return
来源：http://dali.gotoacloud.top/Article/details/gtadoguvzb.html

PHP:  if (!$data) { return; }
来源：http://dali.hfpthk.cn/Article/details/gtdkdbxwcz.html

JS:   if (!data) return;
来源：http://dali.xuetiantiany.cn/Article/details/gttsnzsfen.html

TS:   if (!data) return;
来源：http://dali.nanxuanxn.top/Article/details/gtlxjvpdlz.html

Java: if (data == null) return;
来源：http://dali.quarkkingdee.top/Article/details/gtaspnuljr.html

Go:   if data == nil { return }
来源：http://dali.gotoacloud.top/Article/details/gtqtbmtqxw.html

Ruby: return if data.nil?
来源：http://dali.daria6918.cn/Article/details/gtrcahqacu.html

C#:   if (data == null) return;
来源：http://dali.birdmap.top/Article/details/gtdudzotxu.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtdssshlor.html

C. 函数与作用域
来源：http://dali.gotoacloud.top/Article/details/gtufslrigm.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtmjvfzjeq.html

[C01] 定义函数
来源：http://dali.xziqi.cn/Article/details/gtqlsuoyxp.html

Py:   def add(a, b): return a + b
来源：http://dali.guannengcc.top/Article/details/gtsjiqqzyg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tianlin.xyz/Article/details/gtjwgoiqco.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtocultoan.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gtjerunrwa.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gtmigpyzxm.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ppjwa.cn/Article/details/gtuxupocvg.html

Ruby: def add(a, b); a + b; end
来源：http://dali.nanxuanxn.top/Article/details/gtwrparrxm.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtjshzmxrw.html

[C02] 默认参数
来源：http://dali.jiagoushi.top/Article/details/gtpxrddfwf.html

Py:   def greet(name="World"): return name
来源：http://dali.hnqzz.top/Article/details/gtwzbiffhe.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.fengsongda.top/Article/details/gtndbthasx.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.bjfxy.top/Article/details/gtlwrwqqtg.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gtcbtfhdte.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.wangshuangyany.cn/Article/details/gtfxdoycah.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yuanzhike.top/Article/details/gtxvxkyqfx.html

Ruby: def greet(name = "World") = name
来源：http://dali.havefunace.top/Article/details/gtbsdpkopi.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yj20258.top/Article/details/gtzrhovvva.html

[C03] 可变参数
来源：http://dali.fengsongda.top/Article/details/gthwbhcfbz.html

Py:   def total(*args): return sum(args)
来源：http://dali.yuxming.cn/Article/details/gtyugsrdef.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.quarkkingdee.top/Article/details/gtzwpjtlxh.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.wangshuangyany.cn/Article/details/gtuqtuiysf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hammf.cn/Article/details/gtquzbyhom.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sweek.top/Article/details/gtimqkkefl.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yvedp.cn/Article/details/gtkgvamhjb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.mhx1999.top/Article/details/gtfvgxzyxh.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ydzc1.top/Article/details/gtvodkmvny.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hnxiangtu.top/Article/details/gtsfewoaqp.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yj20258.top/Article/details/gtabedwsxs.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhongyouzk.top/Article/details/gtamwwbxjo.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yj20258.top/Article/details/gtsepqkwmj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhixingplan.top/Article/details/gtckygrekf.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.gogol.net.cn/Article/details/gtihdekaru.html

Go:   // 无：用配置结构体参数
来源：http://dali.yvedp.cn/Article/details/gteawrnhnb.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jinqigfzy.top/Article/details/gtgsztvnnp.html

C#:   f(a: 1, b: 2)
来源：http://dali.gaohongyu789.top/Article/details/gtsznbyvhd.html

[C05] 返回多个值
来源：http://dali.ehwqpu.com/Article/details/gtlywcieut.html

Py:   return a, b
来源：http://dali.aibaodan.cn/Article/details/gtujgvbfza.html

PHP:  return [$a, $b];
来源：http://dali.yj20258.top/Article/details/gttbejishw.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.wangshuangyany.cn/Article/details/gtxtknjtjx.html

TS:   return { a, b };
来源：http://dali.snrcjt.cn/Article/details/gtmnlqrnin.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xuetiantiany.cn/Article/details/gtclqelrpq.html

Go:   return a, b
来源：http://dali.kuanghao11.cn/Article/details/gttchltivl.html

Ruby: return a, b
来源：http://dali.shzxlz.cn/Article/details/gtbbxderyb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.sweek.top/Article/details/gtqqliinmu.html

[C06] 匿名函数 / lambda
来源：http://dali.cdnleiting.top/Article/details/gtchyuijlt.html

Py:   square = lambda x: x * x
来源：http://dali.jyoumei.cn/Article/details/gtriplsynz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hfpthk.cn/Article/details/gtreqcrxwj.html

JS:   const square = x => x * x;
来源：http://dali.andypj.xyz/Article/details/gtxpnygaxx.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xuanzx.com/Article/details/gtwqoplsbn.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.pycfn.com/Article/details/gtlgpxpvxp.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xinyue.icu/Article/details/gtztbgeasb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ybcxt.top/Article/details/gtagunexdt.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.sweek.top/Article/details/gtyqqljedt.html

[C07] 把函数作为参数传入
来源：http://dali.nanxinkj.top/Article/details/gtfqgwhxrx.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yj202588.top/Article/details/gtclwrsgia.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gttfcgphit.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ydzc1.top/Article/details/gtoeejkwgs.html

TS:   arr.map(String)
来源：http://dali.shuidangran.top/Article/details/gtorbdtjep.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ybcxt.top/Article/details/gtikxrxwuh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.daxiang520.top/Article/details/gtxcxctyar.html

Ruby: arr.map(&:upcase)
来源：http://dali.quarkkingdee.top/Article/details/gtdfqgxzpy.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.aizwys.cn/Article/details/gtuusofgsu.html

[C08] 闭包
来源：http://dali.hfpthk.cn/Article/details/gtygxkrlwy.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.nanxuanxn.top/Article/details/gtqltyjdvg.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.snrcjt.cn/Article/details/gtclikzqik.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.aibaodan.cn/Article/details/gtrpuvqzbr.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.fzhhl.top/Article/details/gtiulbctls.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.tanke756.top/Article/details/gtbndmafmo.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jinghuilouyu.cn/Article/details/gticisrreq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hnqzz.top/Article/details/gttqhexqeq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.redwolf501.top/Article/details/gtmxsgcwua.html

[C09] 递归
来源：http://dali.xuanzx.com/Article/details/gtcbbmashd.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.pycfn.com/Article/details/gtknsqspbv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.sxryk.cn/Article/details/gtomxeuiyl.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.kuanghao11.cn/Article/details/gthfagnrvi.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258888.top/Article/details/gtpfxvnvyu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yuxming.cn/Article/details/gtvvscgors.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.chenzaomai.com/Article/details/gteiikibem.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.smart0.xyz/Article/details/gtrmibngji.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.svipenyu.cn/Article/details/gtrpfwknlk.html

[C10] 变量作用域
来源：http://dali.yj202588.top/Article/details/gtahtkqdbu.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.vqdsnc.cn/Article/details/gtjnujweiy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinghuilouyu.cn/Article/details/gtekzdadug.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.birdmap.top/Article/details/gtgnzzdrfa.html

TS:   同 JS
来源：http://dali.xuanzx.com/Article/details/gtmvewcdbv.html

Java: 方法内为块级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtktujajea.html

Go:   花括号块级作用域
来源：http://dali.quarkkingdee.top/Article/details/gtcmzdgqda.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cheryme.top/Article/details/gtmlldwrwq.html

C#:   块级作用域
来源：http://dali.chenlongwang.top/Article/details/gtehtvelmw.html

[C11] 模块导入与导出
来源：http://dali.guannengcc.top/Article/details/gtzyahzdtn.html

Py:   from module import func
来源：http://dali.jqgufenzy.top/Article/details/gtytiexxdz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.sweek.top/Article/details/gtrtsgixks.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.pycfn.com/Article/details/gtxomtwsat.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sxryk.cn/Article/details/gtrdrgoacm.html

Java: import java.util.List;
来源：http://dali.smart0.xyz/Article/details/gtmtchmhkg.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.nwbrower.top/Article/details/gtlohvdcab.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xuetiantiany.cn/Article/details/gtkpihxuyd.html

C#:   using System.Text;
来源：http://dali.jqgufenzy.top/Article/details/gtocbpjzjo.html

[C12] 立即执行函数 IIFE
来源：http://dali.xziqi.cn/Article/details/gtxbasdgwj.html

Py:   (lambda: print("run"))()
来源：http://dali.gzhubu.top/Article/details/gtaazivdlc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.aizwys.cn/Article/details/gtaudxacct.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzbfbnvyy.html

TS:   (() => { console.log("run"); })();
来源：http://dali.snrcjt.cn/Article/details/gtrobjvxro.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.fengsongda.top/Article/details/gtoypkywmn.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmarckqmd.html

Ruby: -> { puts "run" }.call
来源：http://dali.aibaodan.cn/Article/details/gtufsrkefj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.daxiang520.top/Article/details/gtiyzkzjmp.html

[C13] 类型声明 / 类型注解
来源：http://dali.shanyushiyangtech.top/Article/details/gtwnrsfixr.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sweek.top/Article/details/gtkwgcxowt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gtmyupzktg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.316326.xyz/Article/details/gtkxfkhoxd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gtestguclb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gtrndtnuzs.html

Go:   func add(a, b int) int
来源：http://dali.pycfn.com/Article/details/gtfzflvadj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.aibaodan.cn/Article/details/gtopyudxfc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jianghu66.top/Article/details/gtgnuggqpu.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gtsrxnmapy.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhoulong.xyz/Article/details/gtrulzkyve.html

PHP:  // 无泛型
来源：http://dali.nanxuanxn.top/Article/details/gtzjcggvrw.html

JS:   // 无泛型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtberyasrd.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yuxming.cn/Article/details/gtbuejafzs.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.iojbl.cn/Article/details/gtelhtlsqm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.nanxinkj.top/Article/details/gtwdcdxqnb.html

Ruby: # 无泛型
来源：http://dali.pengpengdd.cyou/Article/details/gtiwxnxxmx.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.gogol.net.cn/Article/details/gtzidbgotg.html

[C15] 解构 / 展开参数
来源：http://dali.guannengcc.top/Article/details/gtbsrkyqqd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jinqigufen.top/Article/details/gtvlmcrizm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.mhx1999.top/Article/details/gtvbjyjtvn.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.guannengcc.top/Article/details/gtmkbasgkf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.meibo888.top/Article/details/gtsupacwfz.html

Java: // 无解构
来源：http://dali.havefunace.top/Article/details/gtgfylosqi.html

Go:   // 无解构
来源：http://dali.fengsongda.top/Article/details/gtfvdfppbw.html

Ruby: a, b = pair
来源：http://dali.gogol.net.cn/Article/details/gtprdhcduh.html

C#:   var (a, b) = pair;
来源：http://dali.bjfxy.top/Article/details/gtaptwzvgv.html

[C16] 函数 / 方法重载
来源：http://dali.yonumen.top/Article/details/gtrpjasftt.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.gaohongyu789.top/Article/details/gtsmjmesri.html

PHP:  // 无重载
来源：http://dali.xuetiantiany.cn/Article/details/gtnkvpytye.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.iojbl.cn/Article/details/gtfqlrcepl.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.daria6918.cn/Article/details/gtydmrrnwa.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtgdvyontf.html

Go:   // 无重载：用不同函数名
来源：http://dali.fengsongda.top/Article/details/gtgfdaviia.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yvedp.cn/Article/details/gtwsyfphuv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgcubilea.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtimwuoyqm.html

D. 数组 / 列表 / 集合
来源：http://dali.316326.xyz/Article/details/gttrovpstb.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtsyetdogm.html

[D01] 创建数组 / 列表
来源：http://dali.pycfn.com/Article/details/gtxyqqsiom.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sysykeji.top/Article/details/gtpaczefnd.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xuanzx.com/Article/details/gtdyuzkcbt.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hysaishi.cn/Article/details/gtngynugfv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hammf.cn/Article/details/gtldwbwcju.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.wangdashe.top/Article/details/gtpaqxbhrs.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.tanke756.top/Article/details/gtuwsjwttp.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xuanzx.com/Article/details/gtualtwjpu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yj20258.top/Article/details/gtqqaamrik.html

[D02] 追加元素到末尾
来源：http://dali.0kj1m.cn/Article/details/gtjguvrhzw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.redwolf501.top/Article/details/gtcbsjaoga.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cheryme.top/Article/details/gtuuttlsxd.html

JS:   arr.push(4);
来源：http://dali.fengsongda.top/Article/details/gtrzstshgx.html

TS:   arr.push(4);
来源：http://dali.sxryk.cn/Article/details/gtxuxlgqrn.html

Java: list.add(4);
来源：http://dali.daria6918.cn/Article/details/gtlktuzzwz.html

Go:   arr = append(arr, 4)
来源：http://dali.snrcjt.cn/Article/details/gtjdlmahfu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhongyouzk.top/Article/details/gtrpsdkkfx.html

C#:   list.Add(4);
来源：http://dali.nanxuanxn.top/Article/details/gtyrooyraw.html

[D03] 在指定位置插入元素
来源：http://dali.ybcxt.top/Article/details/gtgtoluxpn.html

Py:   arr.insert(0, 0)
来源：http://dali.hnqzz.top/Article/details/gtkakzrteo.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.meibo888.top/Article/details/gtigtplbyr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.chenzaomai.com/Article/details/gtuvegxztd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yueranfly.top/Article/details/gtsgvcjenf.html

Java: list.add(0, 0);
来源：http://dali.tian-w.cn/Article/details/gtsaecglte.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqcsnxmiv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jianghu66.top/Article/details/gtlmjstwin.html

C#:   list.Insert(0, 0);
来源：http://dali.yuanzhike.top/Article/details/gtgntkrdum.html

[D04] 删除元素
来源：http://dali.xylfe.cn/Article/details/gtnisutiyz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zycfv.cn/Article/details/gtutfgthmc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yvedp.cn/Article/details/gtbufvtvbu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.kuanghao11.cn/Article/details/gtweclztvk.html

TS:   arr.splice(0, 1);
来源：http://dali.tanke756.top/Article/details/gtpsubmwgo.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.tanke756.top/Article/details/gtyymrrlba.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hnqzz.top/Article/details/gtuiyxawqx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtywjmkgad.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hfpthk.cn/Article/details/gtukxnhfps.html

[D05] 访问与修改元素
来源：http://dali.fzhhl.top/Article/details/gtgxhiewqp.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tanke756.top/Article/details/gtaujffslv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.kuanghao11.cn/Article/details/gtuygvaozt.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.pengpengdd.cyou/Article/details/gtrpbcvsqz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cqqwz.cn/Article/details/gtfthaxcao.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkpmjthsx.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.meibo888.top/Article/details/gtooqxehsd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hongshengwenyu.top/Article/details/gturhmbvpj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gtwvunjrjz.html

[D06] 数组长度
来源：http://dali.yonumen.top/Article/details/gtdincvfpd.html

Py:   len(arr)
来源：http://dali.havefunace.top/Article/details/gtzvgbmeun.html

PHP:  count($arr);
来源：http://dali.hammf.cn/Article/details/gtnviquwnb.html

JS:   arr.length
来源：http://dali.cdnleiting.top/Article/details/gtjamtveua.html

TS:   arr.length
来源：http://dali.hnqzz.top/Article/details/gtdxzuvvlh.html

Java: list.size();
来源：http://dali.c1oappe.top/Article/details/gtvssyuzgi.html

Go:   len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtmesupslg.html

Ruby: arr.length; arr.size
来源：http://dali.ydzc1.top/Article/details/gthsvebcdn.html

C#:   list.Count;
来源：http://dali.daria6918.cn/Article/details/gtoesktdla.html

[D07] 切片 / 取子数组
来源：http://dali.chenzaomai.com/Article/details/gtzcoxrwwq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.birdmap.top/Article/details/gtnwqfzyyj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtuguxolqq.html

JS:   arr.slice(1, 4);
来源：http://dali.shzxlz.cn/Article/details/gtxhxxpjri.html

TS:   arr.slice(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gtafnuljly.html

Java: list.subList(1, 4);
来源：http://dali.zhixingplan.top/Article/details/gtptivvmiz.html

Go:   arr[1:4]
来源：http://dali.ppjwa.cn/Article/details/gtzonzwwhy.html

Ruby: arr[1, 3]
来源：http://dali.chenlongwang.top/Article/details/gtyvvhqccm.html

C#:   list.GetRange(1, 3);
来源：http://dali.sysykeji.top/Article/details/gtzxqzcwck.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gtevsxuqjv.html

Py:   a + b;  a.extend(b)
来源：http://dali.aibaodan.cn/Article/details/gtmndvaefx.html

PHP:  array_merge($a, $b);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvxbvvvdg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.smart0.xyz/Article/details/gtoicpaayp.html

TS:   [...a, ...b];
来源：http://dali.vqdsnc.cn/Article/details/gtmxdpusfr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.andypj.xyz/Article/details/gtzuuumebs.html

Go:   append(a, b...)
来源：http://dali.yuxming.cn/Article/details/gtygaqtrtv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.0kj1m.cn/Article/details/gtcskeqmww.html

C#:   a.Concat(b).ToList()
来源：http://dali.daxiang520.top/Article/details/gtchlxyzmf.html

[D09] 排序（升序）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlskwiwzg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gzhubu.top/Article/details/gtwgfjgpei.html

PHP:  sort($arr);
来源：http://dali.c1oappe.top/Article/details/gtyspakoxz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ywan-chungtsiang.top/Article/details/gtowruujax.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yonumen.top/Article/details/gtearymras.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.snrcjt.cn/Article/details/gtazaxxecf.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.svipenyu.cn/Article/details/gteljigloo.html

Ruby: arr.sort
来源：http://dali.yongpay.top/Article/details/gtiqcpipbu.html

C#:   list.Sort();
来源：http://dali.kuanghao11.cn/Article/details/gteojekhib.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hnqzz.top/Article/details/gtbqtzkcvi.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.vqdsnc.cn/Article/details/gtmjvkagpi.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cucudq.cn/Article/details/gtlqpewcul.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sweek.top/Article/details/gtfqgudkiz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj202588.top/Article/details/gtcgcgzjmh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.fengsongda.top/Article/details/gtzbgrhgsz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shzxlz.cn/Article/details/gtxkurdjme.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cqqwz.cn/Article/details/gtvbgqwhzy.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinghuilouyu.cn/Article/details/gtyuxjuafw.html

[D11] 反转数组
来源：http://dali.zycfv.cn/Article/details/gtvcocjwja.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yj202588.top/Article/details/gtqsoyqrzq.html

PHP:  array_reverse($arr);
来源：http://dali.svipenyu.cn/Article/details/gtwyqlfglr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.fengsongda.top/Article/details/gtddewlhwa.html

TS:   [...arr].reverse();
来源：http://dali.cdnleiting.top/Article/details/gtbprilxzs.html

Java: Collections.reverse(list);
来源：http://dali.wangshuangyany.cn/Article/details/gtvshsfwgr.html

Go:   slices.Reverse(arr)
来源：http://dali.hnqzz.top/Article/details/gtuobmhbjh.html

Ruby: arr.reverse
来源：http://dali.birdmap.top/Article/details/gtxasdpdgj.html

C#:   list.Reverse();
来源：http://dali.aizwys.cn/Article/details/gtvirokcnx.html

[D12] 查找元素下标
来源：http://dali.hfpthk.cn/Article/details/gtcyjtxfzd.html

Py:   arr.index(x);  x in arr
来源：http://dali.yj20258.top/Article/details/gtpdjxdlul.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yj20258.top/Article/details/gttxkorhjx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xziqi.cn/Article/details/gtzrvhfdai.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuanzx.com/Article/details/gttqkbzezv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yuanzhike.top/Article/details/gthjokkfqg.html

Go:   slices.Index(arr, x)
来源：http://dali.yuxming.cn/Article/details/gtvlzdktqu.html

Ruby: arr.index(x)
来源：http://dali.fzhhl.top/Article/details/gtbfrjrtdp.html

C#:   list.IndexOf(x);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthrnmotsc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hysaishi.cn/Article/details/gtnxrghixv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.meibo888.top/Article/details/gtwzvqrzot.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.fzhhl.top/Article/details/gtharkvktb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yvedp.cn/Article/details/gtajqdyqlz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cqqwz.cn/Article/details/gtnqbzapfr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ybcxt.top/Article/details/gtzyzsvphp.html


<!-- 参考信息 -->