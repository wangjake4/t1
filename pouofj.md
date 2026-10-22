代发 wailian999

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.cdnleiting.top/Article/details/gtcckliwza.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zdqjudy.top/Article/details/gtescmwztq.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.snrcjt.cn/Article/details/gtysjyqsnl.html

[B12] 跳出多层循环
来源：http://dali.jinqigufen.top/Article/details/gtyemhipgf.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.kuanghao11.cn/Article/details/gtjgosumud.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.fzhhl.top/Article/details/gtowmwfcxi.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ivvv.top/Article/details/gtyfjdkyez.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yanxiufei.cn/Article/details/gtdmcqmpif.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.pengpengdd.cyou/Article/details/gtghaveguk.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ppjwa.cn/Article/details/gtstxjgpon.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhengqikj.top/Article/details/gtpfazchhk.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.chenzaomai.com/Article/details/gtrwwchyvu.html

[B13] 判断是否为数字
来源：http://dali.haohaochexian.top/Article/details/gtbqvekses.html

Py:   isinstance(x, (int, float))
来源：http://dali.hysaishi.cn/Article/details/gtpkaxjgxo.html

PHP:  is_numeric($x)
来源：http://dali.pengpengdd.cyou/Article/details/gtkrfhefro.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.kuanghao11.cn/Article/details/gtuqtuxkfz.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ehwqpu.com/Article/details/gtfopqxspp.html

Java: x instanceof Number
来源：http://dali.chenzaomai.com/Article/details/gtkbyuryhb.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.pycfn.com/Article/details/gtcgzneljf.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhiwuduotai.top/Article/details/gtgmahepnd.html

C#:   x is int or double or decimal
来源：http://dali.aizwys.cn/Article/details/gtdlpvtbbd.html

[B14] 判断值是否在集合内
来源：http://dali.yj20258888.top/Article/details/gtxgaeegtd.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hnqzz.top/Article/details/gtbqsqihif.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.fzhhl.top/Article/details/gtvqoivttx.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.fengsongda.top/Article/details/gtcragxkmb.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.snrcjt.cn/Article/details/gtrgwkcquc.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yj20258.top/Article/details/gtkjxaogyu.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.snrcjt.cn/Article/details/gtkjzfplhp.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhengqikj.top/Article/details/gtlrbguvdo.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yj20258888.top/Article/details/gthbnxrkol.html

[B15] 布尔运算与取反
来源：http://dali.zhoulong.xyz/Article/details/gtyffddrua.html

Py:   a and b or not c
来源：http://dali.andypj.xyz/Article/details/gtzthdhzbk.html

PHP:  $a && $b || !$c
来源：http://dali.yj20258888.top/Article/details/gtcuwvpzgy.html

JS:   a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gtqxwspzvs.html

TS:   a && b || !c
来源：http://dali.fzhhl.top/Article/details/gtvgduqcqn.html

Java: a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gtnitlmgkm.html

Go:   a && b || !c
来源：http://dali.hnqzz.top/Article/details/gtfwqxtppn.html

Ruby: a && b || !c
来源：http://dali.gzhubu.top/Article/details/gtctusuttf.html

C#:   a && b || !c
来源：http://dali.gzhubu.top/Article/details/gtbfzwnqtw.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.redwolf501.top/Article/details/gtdqmsvnqi.html

Py:   if not data: return
来源：http://dali.zhengqikj.top/Article/details/gtbzhktjwx.html

PHP:  if (!$data) { return; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkigxiznr.html

JS:   if (!data) return;
来源：http://dali.chenjidiqi.icu/Article/details/gtcjdgzkpn.html

TS:   if (!data) return;
来源：http://dali.hnxiangtu.top/Article/details/gtdtbiaklz.html

Java: if (data == null) return;
来源：http://dali.nwbrower.top/Article/details/gtkusdevps.html

Go:   if data == nil { return }
来源：http://dali.guannengcc.top/Article/details/gtlhfghmhm.html

Ruby: return if data.nil?
来源：http://dali.gzhubu.top/Article/details/gtbunbtwia.html

C#:   if (data == null) return;
来源：http://dali.bjfxy.top/Article/details/gtdeahqljf.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gteiphxupv.html

C. 函数与作用域
来源：http://dali.hnxiangtu.top/Article/details/gtuxraefsy.html

================================================================================
来源：http://dali.sweek.top/Article/details/gthqvvtiab.html

[C01] 定义函数
来源：http://dali.shangyingyoupin.top/Article/details/gtidkywkkx.html

Py:   def add(a, b): return a + b
来源：http://dali.hywenlv.cn/Article/details/gtxbexkkus.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtneleynou.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gtuqajhfrl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gtoqttidvt.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtedjdsfur.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hywenlv.cn/Article/details/gtyekndxqa.html

Ruby: def add(a, b); a + b; end
来源：http://dali.sufxvd.cn/Article/details/gtnjtpxfbt.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gtrphsmoly.html

[C02] 默认参数
来源：http://dali.hongshengwenyu.top/Article/details/gtnoqgsfot.html

Py:   def greet(name="World"): return name
来源：http://dali.fengsongda.top/Article/details/gtzfxpvyqj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzpnlclpr.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yueranfly.top/Article/details/gtlfjexeog.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yvedp.cn/Article/details/gtezdbpomn.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.guowangkeji.top/Article/details/gtsusctntu.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnpohahyx.html

Ruby: def greet(name = "World") = name
来源：http://dali.ivvv.top/Article/details/gtqkoyhtrs.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yongpay.top/Article/details/gtdbyzktcn.html

[C03] 可变参数
来源：http://dali.zhixingplan.top/Article/details/gtbttgdypl.html

Py:   def total(*args): return sum(args)
来源：http://dali.xuanzx.com/Article/details/gtafyrvsvl.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hnqzz.top/Article/details/gtjwuocdbs.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.quarkkingdee.top/Article/details/gtczalmwbz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.316326.xyz/Article/details/gttswkhqle.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hysaishi.cn/Article/details/gtgdicmzra.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gtauqggyzv.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinqigfzy.top/Article/details/gtlauycvlx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.sweek.top/Article/details/gtfyzpwmqw.html

[C04] 命名参数 / 关键字参数
来源：http://dali.xylfe.cn/Article/details/gtkkxauvhm.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yonumen.top/Article/details/gtdqyfduxl.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ehwqpu.com/Article/details/gtalotssbw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtzwrzbmcr.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcclnjqgx.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cdnleiting.top/Article/details/gtgxqydgqe.html

Go:   // 无：用配置结构体参数
来源：http://dali.jqgfzy.top/Article/details/gtjdvgcqns.html

Ruby: f(a: 1, b: 2)
来源：http://dali.birdmap.top/Article/details/gtcnjkihou.html

C#:   f(a: 1, b: 2)
来源：http://dali.yj20258888.top/Article/details/gtvsspcqlr.html

[C05] 返回多个值
来源：http://dali.hfpthk.cn/Article/details/gtmicwqsvv.html

Py:   return a, b
来源：http://dali.zhoulong.xyz/Article/details/gtwmxupcus.html

PHP:  return [$a, $b];
来源：http://dali.yueranfly.top/Article/details/gtxkacgmvp.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.meibo888.top/Article/details/gtftpsnfne.html

TS:   return { a, b };
来源：http://dali.wangdashe.top/Article/details/gtbecjxnqq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.havefunace.top/Article/details/gtevcnsdzh.html

Go:   return a, b
来源：http://dali.meibo888.top/Article/details/gtmxzrgbnu.html

Ruby: return a, b
来源：http://dali.zhengqikj.top/Article/details/gttwwcxtvj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ppjwa.cn/Article/details/gtpjamnuar.html

[C06] 匿名函数 / lambda
来源：http://dali.zdqjudy.top/Article/details/gtthwaqdtx.html

Py:   square = lambda x: x * x
来源：http://dali.gogol.net.cn/Article/details/gtfbmrssoq.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xuetiantiany.cn/Article/details/gtluaujlsf.html

JS:   const square = x => x * x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrgjxvxbq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.aizwys.cn/Article/details/gthqwfgssp.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yvedp.cn/Article/details/gtopmspbar.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.nanxinkj.top/Article/details/gtzgmwbpfg.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jinqigfzy.top/Article/details/gttkshngsf.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ppjwa.cn/Article/details/gtscloboeb.html

[C07] 把函数作为参数传入
来源：http://dali.cdnleiting.top/Article/details/gtcerudhmq.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yueranfly.top/Article/details/gtrfjjdvxo.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xuanzx.com/Article/details/gtuydimviq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.nanxuanxn.top/Article/details/gtheazazwq.html

TS:   arr.map(String)
来源：http://dali.xuanzx.com/Article/details/gtjyhtyzmz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yongpay.top/Article/details/gtoullqxbu.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shanyushiyangkeji.top/Article/details/gtokdbrqcm.html

Ruby: arr.map(&:upcase)
来源：http://dali.jyoumei.cn/Article/details/gthzsxfyqy.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.dashuyun.cn/Article/details/gtbfjkptqh.html

[C08] 闭包
来源：http://dali.zycfv.cn/Article/details/gtniqhrrhu.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhaomingkeji.xyz/Article/details/gtigtngrlw.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hysaishi.cn/Article/details/gtfouvgqgp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jlsjyb.cn/Article/details/gtnpuvesvq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hnqzz.top/Article/details/gtbzslwyxn.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cashguo.top/Article/details/gtbgrstnry.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jinghuilouyu.cn/Article/details/gttgitwbhx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.nwbrower.top/Article/details/gtsngqfqoc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.fzhhl.top/Article/details/gtbfkpnyik.html

[C09] 递归
来源：http://dali.jyoumei.cn/Article/details/gtvrqpitzr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtonlnrqmk.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.tanke756.top/Article/details/gtidxjbitc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jianghu66.top/Article/details/gtnxcrpqmb.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hammf.cn/Article/details/gthsymyosg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yvedp.cn/Article/details/gtfbodnekg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shangyingyoupin.top/Article/details/gtbdjwhhtu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.svipenyu.cn/Article/details/gtttqwdxrz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jianghu66.top/Article/details/gtvmbwmoiy.html

[C10] 变量作用域
来源：http://dali.aibaodan.cn/Article/details/gtvkvuvfzd.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ydzc1.top/Article/details/gtuejpyjzj.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.nanxuanxn.top/Article/details/gtcesycrff.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cucudq.cn/Article/details/gtdyeskxqu.html

TS:   同 JS
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsvfvguep.html

Java: 方法内为块级作用域
来源：http://dali.snrcjt.cn/Article/details/gtmwncxxxe.html

Go:   花括号块级作用域
来源：http://dali.sufxvd.cn/Article/details/gtrlocgpua.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.snrcjt.cn/Article/details/gtpmbmbslh.html

C#:   块级作用域
来源：http://dali.shangyingyoupin.top/Article/details/gtuabsbwwq.html

[C11] 模块导入与导出
来源：http://dali.jinqigufen.top/Article/details/gtzmwyaywu.html

Py:   from module import func
来源：http://dali.mhx1999.top/Article/details/gtgebroxmx.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhongyouzk.top/Article/details/gtyqjiilat.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.gogol.net.cn/Article/details/gtmxuulffk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cashguo.top/Article/details/gtipfrylyn.html

Java: import java.util.List;
来源：http://dali.gotoacloud.top/Article/details/gtypizrjds.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.redwolf501.top/Article/details/gtznvpcltk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shuidangran.top/Article/details/gtxqfotdog.html

C#:   using System.Text;
来源：http://dali.9152youxi.cn/Article/details/gtavxphjsq.html

[C12] 立即执行函数 IIFE
来源：http://dali.guowangkeji.top/Article/details/gtxjvrwiyg.html

Py:   (lambda: print("run"))()
来源：http://dali.sysykeji.top/Article/details/gtaflbudly.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hfpthk.cn/Article/details/gtkqusyyvx.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jianghu66.top/Article/details/gthfgdbzri.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jiagoushi.top/Article/details/gtbzceyiny.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhiwuduotai.top/Article/details/gtyacbvlwi.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.nanxuanxn.top/Article/details/gtmvtmwles.html

Ruby: -> { puts "run" }.call
来源：http://dali.jqgufenzy.top/Article/details/gtdhwaoomx.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.tanke756.top/Article/details/gtksqjptdc.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlleabhfo.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhoulong.xyz/Article/details/gtuifnlzkl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnqzz.top/Article/details/gtgwctliqv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.dashuyun.cn/Article/details/gthqcwgpbs.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gtmszpgkmy.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gtezqsldcp.html

Go:   func add(a, b int) int
来源：http://dali.jianghu66.top/Article/details/gtedwjzwpa.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hnxiangtu.top/Article/details/gtkvlinhsm.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xinyue.icu/Article/details/gtllabghgu.html

[C14] 泛型函数
来源：http://dali.9152youxi.cn/Article/details/gttypqgvvs.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.tanke756.top/Article/details/gtxblaoxuj.html

PHP:  // 无泛型
来源：http://dali.pycfn.com/Article/details/gtkzqizgnq.html

JS:   // 无泛型
来源：http://dali.jqgfzy.top/Article/details/gtnfemdpac.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hongshengwenyu.top/Article/details/gtjxznddjw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cheryme.top/Article/details/gterywcywi.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cashguo.top/Article/details/gtbvbmwcbl.html

Ruby: # 无泛型
来源：http://dali.yvedp.cn/Article/details/gtdkcmxvdo.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.haohaochexian.top/Article/details/gtzjassjje.html

[C15] 解构 / 展开参数
来源：http://dali.iojbl.cn/Article/details/gtllccigjh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ybcxt.top/Article/details/gtcbthxwki.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yj202588.top/Article/details/gthkwmloyl.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yanxiufei.cn/Article/details/gtzrufngmb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtywvefvwn.html

Java: // 无解构
来源：http://dali.jinghuilouyu.cn/Article/details/gtlugeirpr.html

Go:   // 无解构
来源：http://dali.jinghuilouyu.cn/Article/details/gtuwbxdydm.html

Ruby: a, b = pair
来源：http://dali.zycfv.cn/Article/details/gtbeixkdvo.html

C#:   var (a, b) = pair;
来源：http://dali.jinqigufen.top/Article/details/gtbrvgirdi.html

[C16] 函数 / 方法重载
来源：http://dali.feifeiyinyue.top/Article/details/gtqdqullpo.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.pycfn.com/Article/details/gtxediufok.html

PHP:  // 无重载
来源：http://dali.aizwys.cn/Article/details/gtmsbvwfyx.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shangyingyoupin.top/Article/details/gtibaztczt.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.iojbl.cn/Article/details/gtwdnbsowk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.meibo888.top/Article/details/gtohsvfyzp.html

Go:   // 无重载：用不同函数名
来源：http://dali.dianchejie.cn/Article/details/gtfhifiiwv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xuanzx.com/Article/details/gtkvzvnake.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.tanke756.top/Article/details/gtjfwqewly.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtlkxufetm.html

D. 数组 / 列表 / 集合
来源：http://dali.hongshengwenyu.top/Article/details/gtotwcpoks.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtsfpkdelp.html

[D01] 创建数组 / 列表
来源：http://dali.shangyingyoupin.top/Article/details/gthjufuywt.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gaohongyu789.top/Article/details/gtyyfiufty.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhongyouzk.top/Article/details/gtszujgyfn.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.nanxuanxn.top/Article/details/gtcpxnyrzw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ppjwa.cn/Article/details/gthgqgimxr.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cdnleiting.top/Article/details/gtrihvbghg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jqgufenzy.top/Article/details/gtmbnbbnla.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hammf.cn/Article/details/gthivhtrsz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shuidangran.top/Article/details/gtajbsrevc.html

[D02] 追加元素到末尾
来源：http://dali.shzxlz.cn/Article/details/gtqntsadbs.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yvedp.cn/Article/details/gtqtzyqrbb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.birdmap.top/Article/details/gtonvdmcad.html

JS:   arr.push(4);
来源：http://dali.yuxming.cn/Article/details/gtcxrhirke.html

TS:   arr.push(4);
来源：http://dali.sxryk.cn/Article/details/gtpawwlper.html

Java: list.add(4);
来源：http://dali.hywenlv.cn/Article/details/gtawjyprnu.html

Go:   arr = append(arr, 4)
来源：http://dali.zhixingplan.top/Article/details/gtoubzuune.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.chenlongwang.top/Article/details/gtdvgyldlq.html

C#:   list.Add(4);
来源：http://dali.tanke756.top/Article/details/gtzchwvzya.html

[D03] 在指定位置插入元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlcmdorel.html

Py:   arr.insert(0, 0)
来源：http://dali.zhixingplan.top/Article/details/gtjtfflikt.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.fzhhl.top/Article/details/gtqlpluouy.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.haohaochexian.top/Article/details/gtoiefrgkn.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.redwolf501.top/Article/details/gttziwsyul.html

Java: list.add(0, 0);
来源：http://dali.jyoumei.cn/Article/details/gtfgdnwxxt.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jiagoushi.top/Article/details/gtjjpdizmj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ybcxt.top/Article/details/gtjesgahwy.html

C#:   list.Insert(0, 0);
来源：http://dali.havefunace.top/Article/details/gtatdujoax.html

[D04] 删除元素
来源：http://dali.cdnleiting.top/Article/details/gthstzmitk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.smart0.xyz/Article/details/gtwfgfsyvu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yvedp.cn/Article/details/gtolaptfmk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cqqwz.cn/Article/details/gtztykguqa.html

TS:   arr.splice(0, 1);
来源：http://dali.birdmap.top/Article/details/gtcpuigqaz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.tanke756.top/Article/details/gtypptvnla.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.feifeiyinyue.top/Article/details/gttrqjypza.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.vqdsnc.cn/Article/details/gtfszdrnel.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.wangdashe.top/Article/details/gtpecjuuzl.html

[D05] 访问与修改元素
来源：http://dali.yangfankeji.com/Article/details/gtlscbsoun.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.smart0.xyz/Article/details/gttdhejjes.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yueranfly.top/Article/details/gtavqviqyt.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jqgufenzy.top/Article/details/gtwiklepne.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.nanxuanxn.top/Article/details/gtrxsmvoql.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinghuilouyu.cn/Article/details/gterbrqdok.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.wangshuangyany.cn/Article/details/gtjpjetuqf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangshuangyany.cn/Article/details/gtuquigyxi.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hysaishi.cn/Article/details/gtqrditpdt.html

[D06] 数组长度
来源：http://dali.pycfn.com/Article/details/gtamigahac.html

Py:   len(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtobhazpwj.html

PHP:  count($arr);
来源：http://dali.hnqzz.top/Article/details/gthdqsctvj.html

JS:   arr.length
来源：http://dali.dashuyun.cn/Article/details/gtmflwmsjt.html

TS:   arr.length
来源：http://dali.shangyingyoupin.top/Article/details/gtqzshvuse.html

Java: list.size();
来源：http://dali.cheryme.top/Article/details/gttqdhfhbu.html

Go:   len(arr)
来源：http://dali.guannengcc.top/Article/details/gtoymistag.html

Ruby: arr.length; arr.size
来源：http://dali.fengsongda.top/Article/details/gttkxvljao.html

C#:   list.Count;
来源：http://dali.zycfv.cn/Article/details/gtgqsqdyvv.html

[D07] 切片 / 取子数组
来源：http://dali.zycfv.cn/Article/details/gtakhuuswx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.aizwys.cn/Article/details/gtxmiqvnzl.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sxryk.cn/Article/details/gtkijzqmwl.html

JS:   arr.slice(1, 4);
来源：http://dali.xinyue.icu/Article/details/gtcplhqpdg.html

TS:   arr.slice(1, 4);
来源：http://dali.zhiwuduotai.top/Article/details/gteyelrgzg.html

Java: list.subList(1, 4);
来源：http://dali.sysykeji.top/Article/details/gtycvdbcaf.html

Go:   arr[1:4]
来源：http://dali.nanxinkj.top/Article/details/gtvudgmzpb.html

Ruby: arr[1, 3]
来源：http://dali.ppjwa.cn/Article/details/gtlpgvbkwv.html

C#:   list.GetRange(1, 3);
来源：http://dali.wangshuangyany.cn/Article/details/gthaksjpyi.html

[D08] 合并两个数组
来源：http://dali.jianghu66.top/Article/details/gtrokszjmx.html

Py:   a + b;  a.extend(b)
来源：http://dali.ydzc1.top/Article/details/gtseaqiepp.html

PHP:  array_merge($a, $b);
来源：http://dali.shuidangran.top/Article/details/gtpsgkpmom.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ehwqpu.com/Article/details/gtdwppfhzi.html

TS:   [...a, ...b];
来源：http://dali.pengpengdd.cyou/Article/details/gtqzcwhiqd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.nwbrower.top/Article/details/gtxyluflsk.html

Go:   append(a, b...)
来源：http://dali.pengpengdd.cyou/Article/details/gtymwzubgx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwtugmisd.html

C#:   a.Concat(b).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtvcexglrr.html

[D09] 排序（升序）
来源：http://dali.fzhhl.top/Article/details/gtglvmvtfq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.birdmap.top/Article/details/gthphcpjge.html

PHP:  sort($arr);
来源：http://dali.gzhubu.top/Article/details/gtwxntvqzh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ppjwa.cn/Article/details/gtmajrsloy.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.9152youxi.cn/Article/details/gtmrbezies.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.svipenyu.cn/Article/details/gtavtmoxdv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.aibaodan.cn/Article/details/gtkrvqilbk.html

Ruby: arr.sort
来源：http://dali.andypj.xyz/Article/details/gtqpfctjxg.html

C#:   list.Sort();
来源：http://dali.gzhubu.top/Article/details/gtleiqgqbp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ivvv.top/Article/details/gtxxcizxwx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gttzuzlihl.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tian-w.cn/Article/details/gtfstoatuw.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.snrcjt.cn/Article/details/gttuuovnyc.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fengsongda.top/Article/details/gtwlizkcpb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.andypj.xyz/Article/details/gtbcfemtnu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yuanzhike.top/Article/details/gtjapvowdl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gzhubu.top/Article/details/gtgslizraq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.feifeiyinyue.top/Article/details/gtnftaexzj.html

[D11] 反转数组
来源：http://dali.yj202588.top/Article/details/gtlfkydwir.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.nanxinkj.top/Article/details/gtfwfoxikg.html

PHP:  array_reverse($arr);
来源：http://dali.fzhhl.top/Article/details/gtyyzkfyvd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xziqi.cn/Article/details/gtmvyfdpgx.html

TS:   [...arr].reverse();
来源：http://dali.0kj1m.cn/Article/details/gtolpoxutk.html

Java: Collections.reverse(list);
来源：http://dali.pengpengdd.cyou/Article/details/gtzcpjwggs.html

Go:   slices.Reverse(arr)
来源：http://dali.fzhhl.top/Article/details/gtveovmbhf.html

Ruby: arr.reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gtflypgncw.html

C#:   list.Reverse();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtygcmxypu.html

[D12] 查找元素下标
来源：http://dali.ybcxt.top/Article/details/gtexmvwddl.html

Py:   arr.index(x);  x in arr
来源：http://dali.jlsjyb.cn/Article/details/gtnzirqqeq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.dashuyun.cn/Article/details/gtkewhrvbc.html


<!-- 参考信息 -->