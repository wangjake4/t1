代发 wailian999

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.gogol.net.cn/Article/details/gtuaznjrgs.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhengqikj.top/Article/details/gttdtckgun.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.guowangkeji.top/Article/details/gtqvcecgkn.html

[B12] 跳出多层循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtevxiqjkc.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.feifeiyinyue.top/Article/details/gtetnoqqbz.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.gotoacloud.top/Article/details/gtvnaiwxvp.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yongpay.top/Article/details/gtdggqdzff.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shangyingyoupin.top/Article/details/gtnvuswkip.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cucudq.cn/Article/details/gtychyfjfv.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yj202588.top/Article/details/gtqvcrzgwd.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.nanxuanxn.top/Article/details/gtpvkbgmpz.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhiwuduotai.top/Article/details/gtltdsiiwr.html

[B13] 判断是否为数字
来源：http://dali.316326.xyz/Article/details/gthjhjcclk.html

Py:   isinstance(x, (int, float))
来源：http://dali.jiagoushi.top/Article/details/gthvnepkge.html

PHP:  is_numeric($x)
来源：http://dali.shangyingyoupin.top/Article/details/gtgajkowve.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.havefunace.top/Article/details/gtmvilbepm.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.meibo888.top/Article/details/gtjohebbsw.html

Java: x instanceof Number
来源：http://dali.jqgfzy.top/Article/details/gthbikbril.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shuidangran.top/Article/details/gttofqwpgj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.redwolf501.top/Article/details/gthchmxmmf.html

C#:   x is int or double or decimal
来源：http://dali.ehwqpu.com/Article/details/gtmqqicvam.html

[B14] 判断值是否在集合内
来源：http://dali.aibaodan.cn/Article/details/gtygqubaqe.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ydzc1.top/Article/details/gtuoqjfgey.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.aibaodan.cn/Article/details/gtguvnqjts.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hfpthk.cn/Article/details/gtsppxieii.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.daria6918.cn/Article/details/gtaugyixpw.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yangfankeji.com/Article/details/gtmyqcfszv.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.fengsongda.top/Article/details/gtnlsfwrks.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.daxiang520.top/Article/details/gtscdybnfd.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yangfankeji.com/Article/details/gtdzrfxipr.html

[B15] 布尔运算与取反
来源：http://dali.andypj.xyz/Article/details/gtkaxclyzh.html

Py:   a and b or not c
来源：http://dali.cdnleiting.top/Article/details/gtzzftvsvz.html

PHP:  $a && $b || !$c
来源：http://dali.havefunace.top/Article/details/gtoyytlhrz.html

JS:   a && b || !c
来源：http://dali.tian-w.cn/Article/details/gtwiyygnqu.html

TS:   a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gtmacfjlzu.html

Java: a && b || !c
来源：http://dali.havefunace.top/Article/details/gtybrztkui.html

Go:   a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gtrzreqoeb.html

Ruby: a && b || !c
来源：http://dali.wangdashe.top/Article/details/gtgjlssmck.html

C#:   a && b || !c
来源：http://dali.xylfe.cn/Article/details/gthhgjignj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.nwbrower.top/Article/details/gtukfmvmgs.html

Py:   if not data: return
来源：http://dali.yonumen.top/Article/details/gtcvnnqbfg.html

PHP:  if (!$data) { return; }
来源：http://dali.cdnleiting.top/Article/details/gtqukbzsag.html

JS:   if (!data) return;
来源：http://dali.ydzc1.top/Article/details/gtgrrcyccd.html

TS:   if (!data) return;
来源：http://dali.feifeiyinyue.top/Article/details/gtcsfedxzs.html

Java: if (data == null) return;
来源：http://dali.pycfn.com/Article/details/gtgswrfxao.html

Go:   if data == nil { return }
来源：http://dali.sxryk.cn/Article/details/gtykjlfssg.html

Ruby: return if data.nil?
来源：http://dali.9152youxi.cn/Article/details/gtmkcxmemu.html

C#:   if (data == null) return;
来源：http://dali.ppjwa.cn/Article/details/gtzgssvspa.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtptxrmlfu.html

C. 函数与作用域
来源：http://dali.yueranfly.top/Article/details/gtpwrgygbq.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtlfityzwd.html

[C01] 定义函数
来源：http://dali.tian-w.cn/Article/details/gtuviwofbu.html

Py:   def add(a, b): return a + b
来源：http://dali.quarkkingdee.top/Article/details/gtxzzerutd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtkmdqkipf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtzbvfaitx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gthegtoumg.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.cheryme.top/Article/details/gtleploarh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtedorupjh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.smart0.xyz/Article/details/gtjuycmumu.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gtvhnponfi.html

[C02] 默认参数
来源：http://dali.fengsongda.top/Article/details/gtymgxdizi.html

Py:   def greet(name="World"): return name
来源：http://dali.hnqzz.top/Article/details/gtbjyvnqhg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gaohongyu789.top/Article/details/gtabndsjhe.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtlvolqcxk.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.svipenyu.cn/Article/details/gtrsnkdxmt.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.snrcjt.cn/Article/details/gtxeinerwp.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.chenzaomai.com/Article/details/gtyjdfweex.html

Ruby: def greet(name = "World") = name
来源：http://dali.gzhubu.top/Article/details/gtbcznhnjc.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xinyue.icu/Article/details/gtdkggvaed.html

[C03] 可变参数
来源：http://dali.chenzaomai.com/Article/details/gtglyzarbo.html

Py:   def total(*args): return sum(args)
来源：http://dali.c1oappe.top/Article/details/gtlofsytks.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xziqi.cn/Article/details/gtroukinhm.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jianghu66.top/Article/details/gtfbrcoldp.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xuanzx.com/Article/details/gtpfffpngh.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.9152youxi.cn/Article/details/gtzojbsyfd.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.svipenyu.cn/Article/details/gtvgatnhnf.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yonumen.top/Article/details/gtwerbkozt.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.pycfn.com/Article/details/gthyedsjpp.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinqigfzy.top/Article/details/gtrcpzhqjc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhongyouzk.top/Article/details/gtrdtsqara.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.sysykeji.top/Article/details/gtvpwozpyz.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.havefunace.top/Article/details/gtuorxjmly.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhongyouzk.top/Article/details/gtmhyfgsyn.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.wangdashe.top/Article/details/gtyoudtmdn.html

Go:   // 无：用配置结构体参数
来源：http://dali.andypj.xyz/Article/details/gtdwjrqegz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cashguo.top/Article/details/gtrdqhtxja.html

C#:   f(a: 1, b: 2)
来源：http://dali.smart0.xyz/Article/details/gtokczyvaa.html

[C05] 返回多个值
来源：http://dali.chenlongwang.top/Article/details/gtnpawcpln.html

Py:   return a, b
来源：http://dali.meibo888.top/Article/details/gtivhvdukt.html

PHP:  return [$a, $b];
来源：http://dali.ehwqpu.com/Article/details/gtxixvksqq.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jyoumei.cn/Article/details/gtxidbeish.html

TS:   return { a, b };
来源：http://dali.cqqwz.cn/Article/details/gtcusznygv.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jinqigufen.top/Article/details/gtxzkulmuo.html

Go:   return a, b
来源：http://dali.cdnleiting.top/Article/details/gtojvfzjsp.html

Ruby: return a, b
来源：http://dali.zdqjudy.top/Article/details/gtldpcjpgc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.chenzaomai.com/Article/details/gtobbpqmgr.html

[C06] 匿名函数 / lambda
来源：http://dali.cheryme.top/Article/details/gtqplovrff.html

Py:   square = lambda x: x * x
来源：http://dali.meibo888.top/Article/details/gtidugdvjb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.nanxuanxn.top/Article/details/gtzkpdfrgk.html

JS:   const square = x => x * x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbpfkwgtn.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.daxiang520.top/Article/details/gticophkmh.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.daxiang520.top/Article/details/gthoeabcqe.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.9152youxi.cn/Article/details/gthwapgejd.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xuetiantiany.cn/Article/details/gtwmxljdks.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xuetiantiany.cn/Article/details/gtuatyrbtv.html

[C07] 把函数作为参数传入
来源：http://dali.chenlongwang.top/Article/details/gtuykwktzo.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yongpay.top/Article/details/gtqjvbzfio.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.shzxlz.cn/Article/details/gtppypmmzf.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.tianlin.xyz/Article/details/gtmpiweext.html

TS:   arr.map(String)
来源：http://dali.hnqzz.top/Article/details/gttkxzdyjf.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shzxlz.cn/Article/details/gttncbpstn.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hfpthk.cn/Article/details/gtpbshknle.html

Ruby: arr.map(&:upcase)
来源：http://dali.sufxvd.cn/Article/details/gtcvfgquff.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jqgufenzy.top/Article/details/gtnjwhjesy.html

[C08] 闭包
来源：http://dali.daxiang520.top/Article/details/gtcqlazzqv.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhixingplan.top/Article/details/gtvncjqhmk.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ivvv.top/Article/details/gtmvsucana.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.pengpengdd.cyou/Article/details/gteaxxjyiy.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xuanzx.com/Article/details/gtjmgwzdwm.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.0kj1m.cn/Article/details/gtzvppebch.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.iojbl.cn/Article/details/gtgyxnfcpr.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.meibo888.top/Article/details/gtcwruhmux.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yvedp.cn/Article/details/gtgjrfeosr.html

[C09] 递归
来源：http://dali.gaohongyu789.top/Article/details/gtjxsnrthb.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.nwbrower.top/Article/details/gtnllbcvoc.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.sweek.top/Article/details/gtzruijsvg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xuetiantiany.cn/Article/details/gtujfzxyap.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.birdmap.top/Article/details/gtrvctrljx.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.daria6918.cn/Article/details/gtnxtmpvgk.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sweek.top/Article/details/gtrxkrjtjo.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.fengsongda.top/Article/details/gtkkiccyag.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.meibo888.top/Article/details/gtzghkjaeq.html

[C10] 变量作用域
来源：http://dali.chenlongwang.top/Article/details/gtbijsqnwl.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zdqjudy.top/Article/details/gtnuesczwv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.wangshuangyany.cn/Article/details/gtgqybpkfq.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ehwqpu.com/Article/details/gtdqdbfcjq.html

TS:   同 JS
来源：http://dali.andypj.xyz/Article/details/gtroofomji.html

Java: 方法内为块级作用域
来源：http://dali.vqdsnc.cn/Article/details/gtsiawwiwt.html

Go:   花括号块级作用域
来源：http://dali.aibaodan.cn/Article/details/gtgedliqlp.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cucudq.cn/Article/details/gtlrxhzcuf.html

C#:   块级作用域
来源：http://dali.zhoulong.xyz/Article/details/gtbeqhfmgq.html

[C11] 模块导入与导出
来源：http://dali.snrcjt.cn/Article/details/gtovodslrd.html

Py:   from module import func
来源：http://dali.yongpay.top/Article/details/gtwovorspi.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.fengsongda.top/Article/details/gtubkhmszc.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.nanxinkj.top/Article/details/gtnnutxbre.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.bjfxy.top/Article/details/gtckpdofbo.html

Java: import java.util.List;
来源：http://dali.chenjidiqi.icu/Article/details/gtrcxzfvbf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.vqdsnc.cn/Article/details/gtrfgvfdkn.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jqgufenzy.top/Article/details/gtruzzlckj.html

C#:   using System.Text;
来源：http://dali.yangfankeji.com/Article/details/gthcufvnoy.html

[C12] 立即执行函数 IIFE
来源：http://dali.haohaochexian.top/Article/details/gttiurgozm.html

Py:   (lambda: print("run"))()
来源：http://dali.9152youxi.cn/Article/details/gtjfeolybj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jinqigfzy.top/Article/details/gthywtgcia.html

JS:   (() => { console.log("run"); })();
来源：http://dali.kuanghao11.cn/Article/details/gtaqjsutjb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhiwuduotai.top/Article/details/gtvtqjoqkk.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzjludven.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.316326.xyz/Article/details/gtgjrnxfss.html

Ruby: -> { puts "run" }.call
来源：http://dali.pycfn.com/Article/details/gtmpmfqjtt.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.sufxvd.cn/Article/details/gtxrqdnpzf.html

[C13] 类型声明 / 类型注解
来源：http://dali.wangdashe.top/Article/details/gtwserniik.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cheryme.top/Article/details/gtxqybancl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yueranfly.top/Article/details/gtpwaphkdi.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sysykeji.top/Article/details/gtjhuvixmk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gtpcvxrfvn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gtjhbwzmzt.html

Go:   func add(a, b int) int
来源：http://dali.chenjidiqi.icu/Article/details/gtqelgrgcq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.tanke756.top/Article/details/gtnpzpnarx.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shangyingyoupin.top/Article/details/gtwtcblgpx.html

[C14] 泛型函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtinbthmmj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shuidangran.top/Article/details/gteaetpuyx.html

PHP:  // 无泛型
来源：http://dali.jlsjyb.cn/Article/details/gttgoqtggc.html

JS:   // 无泛型
来源：http://dali.feifeiyinyue.top/Article/details/gtginqqgdq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhengqikj.top/Article/details/gtgmwwsacj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.chenjidiqi.icu/Article/details/gtjvkcnuns.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gzhubu.top/Article/details/gteteixhkl.html

Ruby: # 无泛型
来源：http://dali.yvedp.cn/Article/details/gtmlvzsjfs.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hongshengwenyu.top/Article/details/gtkqwfnvco.html

[C15] 解构 / 展开参数
来源：http://dali.zycfv.cn/Article/details/gtkskpuoif.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hnxiangtu.top/Article/details/gtlkmbemml.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shanyushiyangtech.top/Article/details/gtsffpeddt.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.dashuyun.cn/Article/details/gtovnndpbb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtvxuikgmy.html

Java: // 无解构
来源：http://dali.yangfankeji.com/Article/details/gtevuloaql.html

Go:   // 无解构
来源：http://dali.yangfankeji.com/Article/details/gtdnihrocx.html

Ruby: a, b = pair
来源：http://dali.jinghuilouyu.cn/Article/details/gtaytcpfnx.html

C#:   var (a, b) = pair;
来源：http://dali.0kj1m.cn/Article/details/gtqzzmdnxp.html

[C16] 函数 / 方法重载
来源：http://dali.xinyue.icu/Article/details/gtgqeieget.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hnxiangtu.top/Article/details/gttjhbwzfo.html

PHP:  // 无重载
来源：http://dali.chenjidiqi.icu/Article/details/gtceyzqygr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.c1oappe.top/Article/details/gtncshhfqg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shzxlz.cn/Article/details/gtakuzukyi.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtlhxqmhmj.html

Go:   // 无重载：用不同函数名
来源：http://dali.cheryme.top/Article/details/gthgdzcafi.html

Ruby: # 无重载：靠动态参数
来源：http://dali.316326.xyz/Article/details/gtvbvlmxkj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xylfe.cn/Article/details/gtyhtcwbas.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyqxfsean.html

D. 数组 / 列表 / 集合
来源：http://dali.xinyue.icu/Article/details/gtvitjtygz.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtvmkwbcii.html

[D01] 创建数组 / 列表
来源：http://dali.yj20258.top/Article/details/gtjxxmosot.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sweek.top/Article/details/gtdjcierny.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.fzhhl.top/Article/details/gtiruzcuno.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcfyojqcy.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yj20258888.top/Article/details/gtihrheqna.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.feifeiyinyue.top/Article/details/gtablbvezq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hfpthk.cn/Article/details/gtlaicbsah.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yuxming.cn/Article/details/gtokoqdfoq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.daxiang520.top/Article/details/gtnzdipqna.html

[D02] 追加元素到末尾
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtntzbckfu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.tian-w.cn/Article/details/gtntaqcsax.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gaohongyu789.top/Article/details/gtkuesdege.html

JS:   arr.push(4);
来源：http://dali.bjfxy.top/Article/details/gtsdabaazm.html

TS:   arr.push(4);
来源：http://dali.jiagoushi.top/Article/details/gtaewmdjpp.html

Java: list.add(4);
来源：http://dali.sysykeji.top/Article/details/gtlcofdaia.html

Go:   arr = append(arr, 4)
来源：http://dali.zycfv.cn/Article/details/gtledpwixw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gogol.net.cn/Article/details/gtkqefpxzl.html

C#:   list.Add(4);
来源：http://dali.hongshengwenyu.top/Article/details/gtqckiscap.html

[D03] 在指定位置插入元素
来源：http://dali.xinyue.icu/Article/details/gtuopwmwqp.html

Py:   arr.insert(0, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqnofjygk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.nwbrower.top/Article/details/gtmvlqkqdh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.iojbl.cn/Article/details/gtmqfnityv.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jyoumei.cn/Article/details/gtlqkgfknl.html

Java: list.add(0, 0);
来源：http://dali.nwbrower.top/Article/details/gtctspgnwb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ivvv.top/Article/details/gtrwqobooa.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hnxiangtu.top/Article/details/gtfbhgsamy.html

C#:   list.Insert(0, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtvdismaok.html

[D04] 删除元素
来源：http://dali.jlsjyb.cn/Article/details/gthtcfttlw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.316326.xyz/Article/details/gtfzjkqrbs.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.pycfn.com/Article/details/gtihigskuf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.chenzaomai.com/Article/details/gtmfwtlaep.html

TS:   arr.splice(0, 1);
来源：http://dali.fengsongda.top/Article/details/gtgtckrwqf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.snrcjt.cn/Article/details/gtflsxmgnf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.daxiang520.top/Article/details/gtsxwjrpow.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hnqzz.top/Article/details/gtzlvupokc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hongshengwenyu.top/Article/details/gtduimltfg.html

[D05] 访问与修改元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtroitmete.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yuxming.cn/Article/details/gtxjlzywlw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.pycfn.com/Article/details/gtybmqodpu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ybcxt.top/Article/details/gtkcwekrud.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.nwbrower.top/Article/details/gtedyvchud.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shzxlz.cn/Article/details/gtkflvuxbo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yangfankeji.com/Article/details/gtyiqcsdzs.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.vqdsnc.cn/Article/details/gtjipywtek.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhoulong.xyz/Article/details/gtufunfxbg.html

[D06] 数组长度
来源：http://dali.tianlin.xyz/Article/details/gttvfdnjtj.html

Py:   len(arr)
来源：http://dali.hammf.cn/Article/details/gtkghlkuut.html

PHP:  count($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtxterqzon.html

JS:   arr.length
来源：http://dali.cucudq.cn/Article/details/gtwuxbbwfw.html

TS:   arr.length
来源：http://dali.cheryme.top/Article/details/gticwukllg.html

Java: list.size();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqxxhyrii.html

Go:   len(arr)
来源：http://dali.guannengcc.top/Article/details/gtfmjqxmyu.html

Ruby: arr.length; arr.size
来源：http://dali.snrcjt.cn/Article/details/gtbemiacjq.html

C#:   list.Count;
来源：http://dali.chenzaomai.com/Article/details/gtdyndmthg.html

[D07] 切片 / 取子数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtayxrtjmb.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjnpcordr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yueranfly.top/Article/details/gtienncwbd.html

JS:   arr.slice(1, 4);
来源：http://dali.yonumen.top/Article/details/gtmknekbeh.html

TS:   arr.slice(1, 4);
来源：http://dali.cqqwz.cn/Article/details/gtrmrylsml.html

Java: list.subList(1, 4);
来源：http://dali.xinyue.icu/Article/details/gtgrletxmv.html

Go:   arr[1:4]
来源：http://dali.jqgfzy.top/Article/details/gtzenwtyhg.html

Ruby: arr[1, 3]
来源：http://dali.chenjidiqi.icu/Article/details/gtzeujppop.html

C#:   list.GetRange(1, 3);
来源：http://dali.chenzaomai.com/Article/details/gtunxtlaif.html

[D08] 合并两个数组
来源：http://dali.andypj.xyz/Article/details/gtlbfrnrbu.html

Py:   a + b;  a.extend(b)
来源：http://dali.yangfankeji.com/Article/details/gtqbljlfmr.html

PHP:  array_merge($a, $b);
来源：http://dali.ivvv.top/Article/details/gtvxezaxrc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhongyouzk.top/Article/details/gtgzvjahkw.html

TS:   [...a, ...b];
来源：http://dali.xuanzx.com/Article/details/gtwarhxqmg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.chenzaomai.com/Article/details/gtmlrqviep.html

Go:   append(a, b...)
来源：http://dali.meibo888.top/Article/details/gtpbwmubhm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.quarkkingdee.top/Article/details/gtsyalbcqz.html

C#:   a.Concat(b).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtfpgpvbej.html

[D09] 排序（升序）
来源：http://dali.daria6918.cn/Article/details/gtbjosscqf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtctcxtnpi.html

PHP:  sort($arr);
来源：http://dali.yonumen.top/Article/details/gtxxfwjimd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hysaishi.cn/Article/details/gtuqndudpb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.bjfxy.top/Article/details/gtpsanddle.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxvvidhtx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtrizetbqe.html

Ruby: arr.sort
来源：http://dali.hnqzz.top/Article/details/gtdocjrxbe.html

C#:   list.Sort();
来源：http://dali.yuxming.cn/Article/details/gtxplvbybb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gtthzhjlfa.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gogol.net.cn/Article/details/gtztapxkxn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nwbrower.top/Article/details/gtgtrrqmdg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shuidangran.top/Article/details/gtqxwhjppi.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cucudq.cn/Article/details/gtpntbsnci.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sxryk.cn/Article/details/gtylteedyj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.tian-w.cn/Article/details/gttvigyurl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yuxming.cn/Article/details/gtxtuorqay.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hysaishi.cn/Article/details/gtjjrxpszn.html

[D11] 反转数组
来源：http://dali.yj20258888.top/Article/details/gtzxcavmwp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jiagoushi.top/Article/details/gtnfmqsosk.html

PHP:  array_reverse($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtqwsavvmn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinghuilouyu.cn/Article/details/gtsckhmewo.html

TS:   [...arr].reverse();
来源：http://dali.xylfe.cn/Article/details/gtbisitzyo.html

Java: Collections.reverse(list);
来源：http://dali.yongpay.top/Article/details/gtaagzybxp.html

Go:   slices.Reverse(arr)
来源：http://dali.jyoumei.cn/Article/details/gtbacjzumj.html

Ruby: arr.reverse
来源：http://dali.c1oappe.top/Article/details/gtyjvxsbfm.html

C#:   list.Reverse();
来源：http://dali.chenzaomai.com/Article/details/gtqzmtccjd.html

[D12] 查找元素下标
来源：http://dali.gogol.net.cn/Article/details/gtveeowkpu.html

Py:   arr.index(x);  x in arr
来源：http://dali.yongpay.top/Article/details/gttfziirpc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.daria6918.cn/Article/details/gtrzyclnze.html


<!-- 参考信息 -->