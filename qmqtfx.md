代发 wailian999

PHP:  range(0, 10, 2);
来源：http://dali.gaohongyu789.top/Article/details/gtlpnyveqj.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sufxvd.cn/Article/details/gtnrblyxok.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cdnleiting.top/Article/details/gttrnjymhr.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.svipenyu.cn/Article/details/gtwtxlkgub.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.chenzaomai.com/Article/details/gtjhipgkiy.html

Ruby: (0...10).step(2).to_a
来源：http://dali.wangdashe.top/Article/details/gtbxxszjbi.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.quarkkingdee.top/Article/details/gtgqmshukc.html

[B12] 跳出多层循环
来源：http://dali.pycfn.com/Article/details/gtakfwriga.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cheryme.top/Article/details/gtkmoiryey.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.redwolf501.top/Article/details/gtqmfqbyxc.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sxryk.cn/Article/details/gtnregusga.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sxryk.cn/Article/details/gtxomzmejs.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gtbofqyddj.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.sweek.top/Article/details/gtdhjpupyj.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xinyue.icu/Article/details/gtybxmibvd.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.gzhubu.top/Article/details/gttfbbkrgc.html

[B13] 判断是否为数字
来源：http://dali.shanyushiyangkeji.top/Article/details/gthizwffex.html

Py:   isinstance(x, (int, float))
来源：http://dali.hywenlv.cn/Article/details/gtrdlnmhcx.html

PHP:  is_numeric($x)
来源：http://dali.dianchejie.cn/Article/details/gtifqpkfkd.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yvedp.cn/Article/details/gtyeyjvfud.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhixingplan.top/Article/details/gtwbedjdxq.html

Java: x instanceof Number
来源：http://dali.yj20258888.top/Article/details/gthzlyrtsj.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.snrcjt.cn/Article/details/gteaxbsfpd.html

Ruby: x.is_a?(Numeric)
来源：http://dali.cdnleiting.top/Article/details/gtcrdjtdxx.html

C#:   x is int or double or decimal
来源：http://dali.gaohongyu789.top/Article/details/gtieiwdbfc.html

[B14] 判断值是否在集合内
来源：http://dali.gzhubu.top/Article/details/gtolaaavgz.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zycfv.cn/Article/details/gtczrrjqrj.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yonumen.top/Article/details/gtufvotiab.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cashguo.top/Article/details/gtvsqttwiq.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtgxppkgeq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtrkiorhof.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.0kj1m.cn/Article/details/gtauuhihmz.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.sufxvd.cn/Article/details/gtrlxpbbas.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.mhx1999.top/Article/details/gtvfjmwgpm.html

[B15] 布尔运算与取反
来源：http://dali.feifeiyinyue.top/Article/details/gtsqateqjh.html

Py:   a and b or not c
来源：http://dali.shanyushiyangkeji.top/Article/details/gttdrziugz.html

PHP:  $a && $b || !$c
来源：http://dali.tianlin.xyz/Article/details/gtfqnrsxxv.html

JS:   a && b || !c
来源：http://dali.havefunace.top/Article/details/gtqnlsmgfo.html

TS:   a && b || !c
来源：http://dali.sysykeji.top/Article/details/gtlnjzxwwe.html

Java: a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gtqoouvmhu.html

Go:   a && b || !c
来源：http://dali.ivvv.top/Article/details/gtnzdsdidx.html

Ruby: a && b || !c
来源：http://dali.aizwys.cn/Article/details/gtfstmjjfu.html

C#:   a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gtcfgktdgk.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jinghuilouyu.cn/Article/details/gtxqcucjss.html

Py:   if not data: return
来源：http://dali.wangdashe.top/Article/details/gtyfkdzyto.html

PHP:  if (!$data) { return; }
来源：http://dali.daxiang520.top/Article/details/gtgaglzaid.html

JS:   if (!data) return;
来源：http://dali.jianghu66.top/Article/details/gtaayuxkyh.html

TS:   if (!data) return;
来源：http://dali.xziqi.cn/Article/details/gthkbgseyj.html

Java: if (data == null) return;
来源：http://dali.fengsongda.top/Article/details/gtwtlijuvw.html

Go:   if data == nil { return }
来源：http://dali.daxiang520.top/Article/details/gtctubpxfe.html

Ruby: return if data.nil?
来源：http://dali.ivvv.top/Article/details/gtxzctexop.html

C#:   if (data == null) return;
来源：http://dali.yanxiufei.cn/Article/details/gtgmnrdemc.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gttavvzaky.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gtiqbvxkiq.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtxtgclxsz.html

[C01] 定义函数
来源：http://dali.yueranfly.top/Article/details/gtjalluhvi.html

Py:   def add(a, b): return a + b
来源：http://dali.cucudq.cn/Article/details/gtpdifhhoe.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtsgrftcdc.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yonumen.top/Article/details/gtpatadeoh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ivvv.top/Article/details/gtfmtqaipm.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gttguvoekg.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.gotoacloud.top/Article/details/gtemavnulc.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jianghu66.top/Article/details/gtueswfnof.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gtudsrzrnv.html

[C02] 默认参数
来源：http://dali.quarkkingdee.top/Article/details/gtlwvqaunx.html

Py:   def greet(name="World"): return name
来源：http://dali.nanxuanxn.top/Article/details/gtotnnywdr.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.dashuyun.cn/Article/details/gtfcdjqzfe.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.aizwys.cn/Article/details/gtxawnnwnn.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.pycfn.com/Article/details/gtnixuctcv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.fengsongda.top/Article/details/gtbjrjwiyj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xziqi.cn/Article/details/gtoilteluu.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhixingplan.top/Article/details/gtbifswceq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.dashuyun.cn/Article/details/gtjepobiha.html

[C03] 可变参数
来源：http://dali.zhoulong.xyz/Article/details/gtwbylmwtq.html

Py:   def total(*args): return sum(args)
来源：http://dali.cdnleiting.top/Article/details/gttqmmmmww.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yj202588.top/Article/details/gtifuszppd.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.9152youxi.cn/Article/details/gtjnsgilzf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.daxiang520.top/Article/details/gtkhkhbcbm.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.bjfxy.top/Article/details/gtaqyvlvmg.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthexbmamj.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.tianlin.xyz/Article/details/gthtsouylw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jiagoushi.top/Article/details/gtwihzfqij.html

[C04] 命名参数 / 关键字参数
来源：http://dali.quarkkingdee.top/Article/details/gtatzllupb.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjscbdzes.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xziqi.cn/Article/details/gtqsxsodvn.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yj202588.top/Article/details/gtpgnitzml.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ivvv.top/Article/details/gtyimiyuiw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zycfv.cn/Article/details/gtcpdapyka.html

Go:   // 无：用配置结构体参数
来源：http://dali.yanxiufei.cn/Article/details/gtpngrijfx.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hfpthk.cn/Article/details/gthpkshthh.html

C#:   f(a: 1, b: 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtrdjwhqts.html

[C05] 返回多个值
来源：http://dali.gogol.net.cn/Article/details/gtywurjnxv.html

Py:   return a, b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpzoscibp.html

PHP:  return [$a, $b];
来源：http://dali.sweek.top/Article/details/gtzddtgudy.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hammf.cn/Article/details/gtgfkiwolz.html

TS:   return { a, b };
来源：http://dali.yueranfly.top/Article/details/gtqzqehagz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhixingplan.top/Article/details/gtflbkpamo.html

Go:   return a, b
来源：http://dali.jyoumei.cn/Article/details/gtxhhjuzyo.html

Ruby: return a, b
来源：http://dali.daxiang520.top/Article/details/gtzgffikat.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hongshengwenyu.top/Article/details/gtokzaacpq.html

[C06] 匿名函数 / lambda
来源：http://dali.svipenyu.cn/Article/details/gtrlcrysev.html

Py:   square = lambda x: x * x
来源：http://dali.9152youxi.cn/Article/details/gtlmvksgym.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xinyue.icu/Article/details/gtuzdeexqp.html

JS:   const square = x => x * x;
来源：http://dali.yongpay.top/Article/details/gttpwebxlg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yj202588.top/Article/details/gtgwezomsn.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.daria6918.cn/Article/details/gtioxjknsa.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.mhx1999.top/Article/details/gtfgasevwp.html

Ruby: square = ->(x) { x * x }
来源：http://dali.chenzaomai.com/Article/details/gtsorqeoro.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.daxiang520.top/Article/details/gtmwjaxslu.html

[C07] 把函数作为参数传入
来源：http://dali.quarkkingdee.top/Article/details/gtfmkocpwq.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.0kj1m.cn/Article/details/gtaxipcjhd.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zycfv.cn/Article/details/gtepxoypnq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.gotoacloud.top/Article/details/gtttqwunau.html

TS:   arr.map(String)
来源：http://dali.shzxlz.cn/Article/details/gtsvmfnogz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.haohaochexian.top/Article/details/gtdvpiisos.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xuanzx.com/Article/details/gtsjwulrbi.html

Ruby: arr.map(&:upcase)
来源：http://dali.yj20258888.top/Article/details/gtdexonswf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jqgufenzy.top/Article/details/gtlymtatxm.html

[C08] 闭包
来源：http://dali.vqdsnc.cn/Article/details/gtnnoaxlbr.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.316326.xyz/Article/details/gtorytrggd.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.haohaochexian.top/Article/details/gtiwtyboah.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.316326.xyz/Article/details/gtrmnjlgax.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhiwuduotai.top/Article/details/gtqjftixsx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yongpay.top/Article/details/gtbvrdntkk.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hnxiangtu.top/Article/details/gtpcycvcow.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gogol.net.cn/Article/details/gtusepwvra.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhixingplan.top/Article/details/gtukdbxadf.html

[C09] 递归
来源：http://dali.jqgufenzy.top/Article/details/gtcjgalhzj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xziqi.cn/Article/details/gtprunmhag.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhoulong.xyz/Article/details/gtcrsauwyx.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yuanzhike.top/Article/details/gtvjydoqmb.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shangyingyoupin.top/Article/details/gtsnyktgwb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cheryme.top/Article/details/gtjgvourwu.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jianghu66.top/Article/details/gtvchaxwtj.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.pycfn.com/Article/details/gtgmhhmcpy.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yuxming.cn/Article/details/gtoptmzvcu.html

[C10] 变量作用域
来源：http://dali.yj20258888.top/Article/details/gtnkiieukl.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.pycfn.com/Article/details/gtmszpqeta.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hysaishi.cn/Article/details/gtnrxemxxw.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.tian-w.cn/Article/details/gtlpbnmtdp.html

TS:   同 JS
来源：http://dali.hywenlv.cn/Article/details/gtvhnicoyr.html

Java: 方法内为块级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gtbbkieqjd.html

Go:   花括号块级作用域
来源：http://dali.gotoacloud.top/Article/details/gteqtwsazj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jinqigufen.top/Article/details/gtoezjbgri.html

C#:   块级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpkagzxle.html

[C11] 模块导入与导出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoqvaepkq.html

Py:   from module import func
来源：http://dali.zhoulong.xyz/Article/details/gtixylnlxv.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.daria6918.cn/Article/details/gtwzmgaiux.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hammf.cn/Article/details/gtbcexvkcd.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.wangshuangyany.cn/Article/details/gtsqhbnvos.html

Java: import java.util.List;
来源：http://dali.redwolf501.top/Article/details/gtulpunivn.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hnxiangtu.top/Article/details/gtvsdjjtov.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hnqzz.top/Article/details/gtftzqhjhr.html

C#:   using System.Text;
来源：http://dali.cqqwz.cn/Article/details/gtfmplfmup.html

[C12] 立即执行函数 IIFE
来源：http://dali.yuxming.cn/Article/details/gtmncqjywx.html

Py:   (lambda: print("run"))()
来源：http://dali.iojbl.cn/Article/details/gtscrdvhzz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hnqzz.top/Article/details/gtakykyyuv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yuxming.cn/Article/details/gtfxytzbbk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jqgfzy.top/Article/details/gtgpoezasq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.andypj.xyz/Article/details/gtvtbavvwv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.wangdashe.top/Article/details/gtbwdhajze.html

Ruby: -> { puts "run" }.call
来源：http://dali.quarkkingdee.top/Article/details/gtvnprbago.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.nanxinkj.top/Article/details/gtlmuqlbst.html

[C13] 类型声明 / 类型注解
来源：http://dali.shuidangran.top/Article/details/gtwkbbsftn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hnqzz.top/Article/details/gtmwidtlso.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guowangkeji.top/Article/details/gtsdydwusk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.9152youxi.cn/Article/details/gtbjgzznth.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gtggfyxwkq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtpmouuvtj.html

Go:   func add(a, b int) int
来源：http://dali.yonumen.top/Article/details/gteivoppty.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhoulong.xyz/Article/details/gtbgwzxezl.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yonumen.top/Article/details/gtjxhuqfdn.html

[C14] 泛型函数
来源：http://dali.fengsongda.top/Article/details/gtooidloeo.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cashguo.top/Article/details/gtzuaehofp.html

PHP:  // 无泛型
来源：http://dali.pengpengdd.cyou/Article/details/gtdbqnrvgz.html

JS:   // 无泛型
来源：http://dali.yonumen.top/Article/details/gtaaeriumz.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.fengsongda.top/Article/details/gtdtjvnuwt.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.haohaochexian.top/Article/details/gtprazlpiv.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cashguo.top/Article/details/gtuedbkvei.html

Ruby: # 无泛型
来源：http://dali.yj202588.top/Article/details/gtpxtqruen.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.316326.xyz/Article/details/gtfwvdaurq.html

[C15] 解构 / 展开参数
来源：http://dali.gogol.net.cn/Article/details/gtqirpqcee.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhixingplan.top/Article/details/gtpdtqyhra.html

PHP:  [$a, $b] = $pair;
来源：http://dali.pengpengdd.cyou/Article/details/gtpwnwojmn.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.fzhhl.top/Article/details/gtslgvrohp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinqigufen.top/Article/details/gtjknarjjg.html

Java: // 无解构
来源：http://dali.hywenlv.cn/Article/details/gtaieovrfp.html

Go:   // 无解构
来源：http://dali.feifeiyinyue.top/Article/details/gtftkbebwq.html

Ruby: a, b = pair
来源：http://dali.zycfv.cn/Article/details/gtcrtclbxp.html

C#:   var (a, b) = pair;
来源：http://dali.yonumen.top/Article/details/gtdvaalkwk.html

[C16] 函数 / 方法重载
来源：http://dali.dashuyun.cn/Article/details/gtmbigqjgo.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xuanzx.com/Article/details/gtuibntaoj.html

PHP:  // 无重载
来源：http://dali.pycfn.com/Article/details/gtgphcgwim.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.c1oappe.top/Article/details/gtfruypadv.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gaohongyu789.top/Article/details/gtsqvorile.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.dianchejie.cn/Article/details/gtzibjgays.html

Go:   // 无重载：用不同函数名
来源：http://dali.jianghu66.top/Article/details/gtrxthdrui.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yongpay.top/Article/details/gtocmgspqo.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.haohaochexian.top/Article/details/gtetbfogxb.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtpebpcrpi.html

D. 数组 / 列表 / 集合
来源：http://dali.sysykeji.top/Article/details/gtdxiutvds.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtiihsxvvw.html

[D01] 创建数组 / 列表
来源：http://dali.sweek.top/Article/details/gtahiyjigo.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.daria6918.cn/Article/details/gtaaoyzgze.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.havefunace.top/Article/details/gtmdbssoqr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hywenlv.cn/Article/details/gtcmntsagc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cucudq.cn/Article/details/gtdghjfnhj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hfpthk.cn/Article/details/gtwauonoga.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gogol.net.cn/Article/details/gtqgmsgksc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.pycfn.com/Article/details/gtuoprivoh.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.redwolf501.top/Article/details/gtcujtjrkq.html

[D02] 追加元素到末尾
来源：http://dali.guannengcc.top/Article/details/gtxgzvrmdl.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.nanxinkj.top/Article/details/gtgmamarcf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.daria6918.cn/Article/details/gtadevyayc.html

JS:   arr.push(4);
来源：http://dali.jyoumei.cn/Article/details/gtkrgreosz.html

TS:   arr.push(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtrdvzudgj.html

Java: list.add(4);
来源：http://dali.jinqigufen.top/Article/details/gtzcpbqons.html

Go:   arr = append(arr, 4)
来源：http://dali.andypj.xyz/Article/details/gtddeepcue.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gogol.net.cn/Article/details/gtupzqrltc.html

C#:   list.Add(4);
来源：http://dali.yueranfly.top/Article/details/gtqgybkhsu.html

[D03] 在指定位置插入元素
来源：http://dali.pengpengdd.cyou/Article/details/gtnvxwdunp.html

Py:   arr.insert(0, 0)
来源：http://dali.yongpay.top/Article/details/gtafagmzjd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.meibo888.top/Article/details/gtoaxsivhf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhiwuduotai.top/Article/details/gtjdfjiwrb.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.sysykeji.top/Article/details/gtbmpqrkpk.html

Java: list.add(0, 0);
来源：http://dali.zhoulong.xyz/Article/details/gtxtpzilsr.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.iojbl.cn/Article/details/gtbjlvfkpf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.9152youxi.cn/Article/details/gtuwbwdozl.html

C#:   list.Insert(0, 0);
来源：http://dali.guowangkeji.top/Article/details/gtuwrzdzep.html

[D04] 删除元素
来源：http://dali.tian-w.cn/Article/details/gtqpugtdlo.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yj20258888.top/Article/details/gtznqurhdk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.daria6918.cn/Article/details/gtzdkmrsni.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yangfankeji.com/Article/details/gtjjdpjzat.html

TS:   arr.splice(0, 1);
来源：http://dali.chenjidiqi.icu/Article/details/gtkfrllklz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.wangdashe.top/Article/details/gteirsiesq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jinqigfzy.top/Article/details/gtgyelogsc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xuetiantiany.cn/Article/details/gttsoccneb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jqgfzy.top/Article/details/gtapocruub.html

[D05] 访问与修改元素
来源：http://dali.bjfxy.top/Article/details/gtrymctjfd.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258888.top/Article/details/gttkykibcj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.dashuyun.cn/Article/details/gtlaqkkkkr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhiwuduotai.top/Article/details/gtnajjkvni.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.chenlongwang.top/Article/details/gtcqhefsex.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ehwqpu.com/Article/details/gtmiytctyi.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jqgfzy.top/Article/details/gttrycegtl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ivvv.top/Article/details/gttregtqan.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hywenlv.cn/Article/details/gtyezgkzky.html

[D06] 数组长度
来源：http://dali.yueranfly.top/Article/details/gtomxkfser.html

Py:   len(arr)
来源：http://dali.nwbrower.top/Article/details/gtcdisyega.html

PHP:  count($arr);
来源：http://dali.xuanzx.com/Article/details/gtxspdrnbt.html

JS:   arr.length
来源：http://dali.hysaishi.cn/Article/details/gtukdfhhqa.html

TS:   arr.length
来源：http://dali.sweek.top/Article/details/gtlrsalwad.html

Java: list.size();
来源：http://dali.chenjidiqi.icu/Article/details/gtyjpbkoye.html

Go:   len(arr)
来源：http://dali.shuidangran.top/Article/details/gtzmbxdcqw.html

Ruby: arr.length; arr.size
来源：http://dali.nwbrower.top/Article/details/gtosjhhtox.html

C#:   list.Count;
来源：http://dali.jiagoushi.top/Article/details/gtnwymfthg.html

[D07] 切片 / 取子数组
来源：http://dali.tian-w.cn/Article/details/gtrqbyrodr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ehwqpu.com/Article/details/gtfbheaoyt.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jqgufenzy.top/Article/details/gthrdtqdto.html

JS:   arr.slice(1, 4);
来源：http://dali.guannengcc.top/Article/details/gttfjbewig.html

TS:   arr.slice(1, 4);
来源：http://dali.yueranfly.top/Article/details/gttnmdhpnd.html

Java: list.subList(1, 4);
来源：http://dali.birdmap.top/Article/details/gtxbjijvab.html

Go:   arr[1:4]
来源：http://dali.gzhubu.top/Article/details/gtzyfxduyb.html

Ruby: arr[1, 3]
来源：http://dali.cdnleiting.top/Article/details/gtyjlkmqpf.html

C#:   list.GetRange(1, 3);
来源：http://dali.yj20258.top/Article/details/gtksaummbh.html

[D08] 合并两个数组
来源：http://dali.aibaodan.cn/Article/details/gtseqfiqvo.html

Py:   a + b;  a.extend(b)
来源：http://dali.cheryme.top/Article/details/gtyxtknfov.html

PHP:  array_merge($a, $b);
来源：http://dali.cucudq.cn/Article/details/gtailpnxhe.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yvedp.cn/Article/details/gttsfwvzry.html

TS:   [...a, ...b];
来源：http://dali.cdnleiting.top/Article/details/gtkmymiiup.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.snrcjt.cn/Article/details/gtjzfwwfvn.html

Go:   append(a, b...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsfgfxnsr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhiwuduotai.top/Article/details/gttlzayvdr.html

C#:   a.Concat(b).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtoxyueghn.html

[D09] 排序（升序）
来源：http://dali.hammf.cn/Article/details/gttrvoowdm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigfzy.top/Article/details/gtvuheeuew.html

PHP:  sort($arr);
来源：http://dali.hammf.cn/Article/details/gtounyanpt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hfpthk.cn/Article/details/gtjawzfres.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhongyouzk.top/Article/details/gtgixnuxtu.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinqigfzy.top/Article/details/gtcobfgvow.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.andypj.xyz/Article/details/gtfapvkpbm.html

Ruby: arr.sort
来源：http://dali.xylfe.cn/Article/details/gtihkqbpzp.html

C#:   list.Sort();
来源：http://dali.shzxlz.cn/Article/details/gtzrwuspqo.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.aizwys.cn/Article/details/gtjclxxrbd.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gtoluxrnbk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cqqwz.cn/Article/details/gtdunexmjh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fzhhl.top/Article/details/gtwzbbhuyp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yanxiufei.cn/Article/details/gthppijqcn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.meibo888.top/Article/details/gtwjkdwchi.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zycfv.cn/Article/details/gtbioiwwzu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttpzzfmzk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.nwbrower.top/Article/details/gtakvdowvx.html

[D11] 反转数组
来源：http://dali.sufxvd.cn/Article/details/gtpkqnvilp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jianghu66.top/Article/details/gtelnpnvej.html

PHP:  array_reverse($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtwpsbdvok.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xuanzx.com/Article/details/gtkuiirchd.html

TS:   [...arr].reverse();
来源：http://dali.sweek.top/Article/details/gtnexbsmai.html

Java: Collections.reverse(list);
来源：http://dali.jianghu66.top/Article/details/gtrzwrowfu.html

Go:   slices.Reverse(arr)
来源：http://dali.nwbrower.top/Article/details/gtejwgdkgn.html

Ruby: arr.reverse
来源：http://dali.xuetiantiany.cn/Article/details/gtwvpazamo.html


<!-- 参考信息 -->