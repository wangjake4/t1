代发 wailian999

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hywenlv.cn/Article/details/gtmrcaermn.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yangfankeji.com/Article/details/gtqzcnylub.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.chenlongwang.top/Article/details/gtjmrcvnuv.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xylfe.cn/Article/details/gtnlyvortk.html

[B13] 判断是否为数字
来源：http://dali.zhongyouzk.top/Article/details/gtyszkdzht.html

Py:   isinstance(x, (int, float))
来源：http://dali.hammf.cn/Article/details/gtwgpowizg.html

PHP:  is_numeric($x)
来源：http://dali.quarkkingdee.top/Article/details/gtgxqbmuoo.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhixingplan.top/Article/details/gtjnkpebpe.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sysykeji.top/Article/details/gtwancumbi.html

Java: x instanceof Number
来源：http://dali.sweek.top/Article/details/gtbethhpva.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xuetiantiany.cn/Article/details/gtaobhonvp.html

Ruby: x.is_a?(Numeric)
来源：http://dali.c1oappe.top/Article/details/gtwdzvyirs.html

C#:   x is int or double or decimal
来源：http://dali.zhiwuduotai.top/Article/details/gtxqqjhgpv.html

[B14] 判断值是否在集合内
来源：http://dali.daxiang520.top/Article/details/gtclvzvvnv.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jqgufenzy.top/Article/details/gtjblvhxxd.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.0kj1m.cn/Article/details/gtsvwbafsx.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.meibo888.top/Article/details/gtoettdnfj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.fzhhl.top/Article/details/gtheedmljx.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtinhzxpnu.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.birdmap.top/Article/details/gtcjazkvku.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.smart0.xyz/Article/details/gtfkeofcma.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlhhfrxtl.html

[B15] 布尔运算与取反
来源：http://dali.tianlin.xyz/Article/details/gttnshzrll.html

Py:   a and b or not c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtocdhmzye.html

PHP:  $a && $b || !$c
来源：http://dali.yuanzhike.top/Article/details/gtpmhvfbwl.html

JS:   a && b || !c
来源：http://dali.zycfv.cn/Article/details/gtzbtgslas.html

TS:   a && b || !c
来源：http://dali.yvedp.cn/Article/details/gtsogzrlct.html

Java: a && b || !c
来源：http://dali.ivvv.top/Article/details/gtoxslcplx.html

Go:   a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gtvyywzunr.html

Ruby: a && b || !c
来源：http://dali.nwbrower.top/Article/details/gtmfunrtbs.html

C#:   a && b || !c
来源：http://dali.yj20258.top/Article/details/gtvvkfeavv.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cashguo.top/Article/details/gtmqjnbyhi.html

Py:   if not data: return
来源：http://dali.jyoumei.cn/Article/details/gtadjxtybd.html

PHP:  if (!$data) { return; }
来源：http://dali.daxiang520.top/Article/details/gtxqviiitz.html

JS:   if (!data) return;
来源：http://dali.yj20258888.top/Article/details/gtfxhvgetj.html

TS:   if (!data) return;
来源：http://dali.cucudq.cn/Article/details/gtwtwseygs.html

Java: if (data == null) return;
来源：http://dali.bjfxy.top/Article/details/gtsszzuhlz.html

Go:   if data == nil { return }
来源：http://dali.xuetiantiany.cn/Article/details/gtuzotuugg.html

Ruby: return if data.nil?
来源：http://dali.daxiang520.top/Article/details/gtprlfckcl.html

C#:   if (data == null) return;
来源：http://dali.iojbl.cn/Article/details/gtpjukmdqi.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtekquulce.html

C. 函数与作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gtapqdqray.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtgwknoypt.html

[C01] 定义函数
来源：http://dali.dashuyun.cn/Article/details/gtzabupzlh.html

Py:   def add(a, b): return a + b
来源：http://dali.zhengqikj.top/Article/details/gtclnczfxv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jiagoushi.top/Article/details/gthtzbqgui.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gtzwpvbmyb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtqifnwusy.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gtubkhtjlx.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zdqjudy.top/Article/details/gtobubchyq.html

Ruby: def add(a, b); a + b; end
来源：http://dali.gotoacloud.top/Article/details/gtnbfotdnk.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtahnrwchx.html

[C02] 默认参数
来源：http://dali.sxryk.cn/Article/details/gtcuuvygpz.html

Py:   def greet(name="World"): return name
来源：http://dali.andypj.xyz/Article/details/gtukgxqcsy.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xuanzx.com/Article/details/gtncpoucos.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtqemjimnc.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gtbokhbjyq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.kuanghao11.cn/Article/details/gttcfbmhzx.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.chenlongwang.top/Article/details/gtqsphiypr.html

Ruby: def greet(name = "World") = name
来源：http://dali.sysykeji.top/Article/details/gtlznxssfg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhoulong.xyz/Article/details/gtbjbzobhe.html

[C03] 可变参数
来源：http://dali.svipenyu.cn/Article/details/gtxlkbbpan.html

Py:   def total(*args): return sum(args)
来源：http://dali.guowangkeji.top/Article/details/gttgoycxii.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gotoacloud.top/Article/details/gtezavvlcj.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yongpay.top/Article/details/gtetorqutv.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.kuanghao11.cn/Article/details/gtcmqecsof.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.meibo888.top/Article/details/gtunxnaypp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhengqikj.top/Article/details/gtmttsnbft.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.kuanghao11.cn/Article/details/gtrbefafqj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.pengpengdd.cyou/Article/details/gtbdhhvcxk.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yuxming.cn/Article/details/gtfxroyqjt.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.havefunace.top/Article/details/gtntpzamhp.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.gotoacloud.top/Article/details/gtvhpvfscc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.havefunace.top/Article/details/gtopmjtuul.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hammf.cn/Article/details/gtewmphunu.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.gzhubu.top/Article/details/gtrolxbtxp.html

Go:   // 无：用配置结构体参数
来源：http://dali.cqqwz.cn/Article/details/gtmrepvnti.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzuqlhpwu.html

C#:   f(a: 1, b: 2)
来源：http://dali.dashuyun.cn/Article/details/gtawbabzbg.html

[C05] 返回多个值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwcemajcx.html

Py:   return a, b
来源：http://dali.hammf.cn/Article/details/gtepbcrgda.html

PHP:  return [$a, $b];
来源：http://dali.bjfxy.top/Article/details/gtlealqbdt.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ydzc1.top/Article/details/gtfhjvsggx.html

TS:   return { a, b };
来源：http://dali.wangshuangyany.cn/Article/details/gttqoedker.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zycfv.cn/Article/details/gtvjnxjvug.html

Go:   return a, b
来源：http://dali.cheryme.top/Article/details/gtvuphnaln.html

Ruby: return a, b
来源：http://dali.jlsjyb.cn/Article/details/gttfiyzphu.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xinyue.icu/Article/details/gtmkjpljob.html

[C06] 匿名函数 / lambda
来源：http://dali.dianchejie.cn/Article/details/gtsrfdayzi.html

Py:   square = lambda x: x * x
来源：http://dali.pengpengdd.cyou/Article/details/gtghssyuwo.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zdqjudy.top/Article/details/gtkdopweus.html

JS:   const square = x => x * x;
来源：http://dali.jqgufenzy.top/Article/details/gtlppwoltd.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhengqikj.top/Article/details/gteqovahbo.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.wangdashe.top/Article/details/gtvpxnrnei.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhoulong.xyz/Article/details/gtklcyhywb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.gaohongyu789.top/Article/details/gtzssemvnr.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.wangdashe.top/Article/details/gtgdevmekl.html

[C07] 把函数作为参数传入
来源：http://dali.ppjwa.cn/Article/details/gtqaaugrww.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hammf.cn/Article/details/gtretfnljd.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtbhwxmtnj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jqgfzy.top/Article/details/gtoadfauiu.html

TS:   arr.map(String)
来源：http://dali.iojbl.cn/Article/details/gtiglohlkb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtonnnqypj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yongpay.top/Article/details/gtjbdifjkt.html

Ruby: arr.map(&:upcase)
来源：http://dali.yj20258888.top/Article/details/gtxoudfdxv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.c1oappe.top/Article/details/gtnxerzytl.html

[C08] 闭包
来源：http://dali.zhongyouzk.top/Article/details/gtwwdtjopk.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.fzhhl.top/Article/details/gteivrmsmg.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.tanke756.top/Article/details/gtijsqyrlw.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shzxlz.cn/Article/details/gtvlbiwamf.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbgmzxnxm.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jinqigufen.top/Article/details/gttqnuluuq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xziqi.cn/Article/details/gtoehzsprj.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jianghu66.top/Article/details/gtyacloggu.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jqgufenzy.top/Article/details/gtylfhhrso.html

[C09] 递归
来源：http://dali.jinqigufen.top/Article/details/gtnrddsfbp.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtyqojhhak.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.daria6918.cn/Article/details/gtgpaecdek.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.wangshuangyany.cn/Article/details/gtwgccpunp.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.guowangkeji.top/Article/details/gtwlzmqkgf.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.c1oappe.top/Article/details/gtdhnhxqgz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.mhx1999.top/Article/details/gtdrnovgrt.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtbztptktl.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yj20258.top/Article/details/gtsgxjmzdc.html

[C10] 变量作用域
来源：http://dali.dianchejie.cn/Article/details/gtrfxvrzen.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hongshengwenyu.top/Article/details/gtlnyvthbe.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yvedp.cn/Article/details/gtehiavbqt.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.shangyingyoupin.top/Article/details/gtfgbrmrob.html

TS:   同 JS
来源：http://dali.sufxvd.cn/Article/details/gtuounbgrj.html

Java: 方法内为块级作用域
来源：http://dali.jinqigufen.top/Article/details/gtcitigwoq.html

Go:   花括号块级作用域
来源：http://dali.yongpay.top/Article/details/gtzxuqnkby.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.quarkkingdee.top/Article/details/gtctfkvmzp.html

C#:   块级作用域
来源：http://dali.bjfxy.top/Article/details/gtojsphihf.html

[C11] 模块导入与导出
来源：http://dali.9152youxi.cn/Article/details/gtooigxqvu.html

Py:   from module import func
来源：http://dali.ehwqpu.com/Article/details/gtodsvahcl.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxqabhpsu.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtizfxijxk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.quarkkingdee.top/Article/details/gthhmcpjzm.html

Java: import java.util.List;
来源：http://dali.wangdashe.top/Article/details/gttytywatz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xinyue.icu/Article/details/gtiiehsbxd.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yanxiufei.cn/Article/details/gtgczoxilf.html

C#:   using System.Text;
来源：http://dali.zhixingplan.top/Article/details/gthdwiyajb.html

[C12] 立即执行函数 IIFE
来源：http://dali.dashuyun.cn/Article/details/gtojxlcwbz.html

Py:   (lambda: print("run"))()
来源：http://dali.hammf.cn/Article/details/gttajzmdce.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yanxiufei.cn/Article/details/gtbvalinux.html

JS:   (() => { console.log("run"); })();
来源：http://dali.smart0.xyz/Article/details/gtugenhtwz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbmophlgf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhoulong.xyz/Article/details/gtqxmnvqhf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hywenlv.cn/Article/details/gtzlrbexsc.html

Ruby: -> { puts "run" }.call
来源：http://dali.chenjidiqi.icu/Article/details/gtrzstyxuo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjjdbrjys.html

[C13] 类型声明 / 类型注解
来源：http://dali.kuanghao11.cn/Article/details/gtijqfvsdm.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.bjfxy.top/Article/details/gtwpinmtlo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.snrcjt.cn/Article/details/gtwnkvgnou.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xuanzx.com/Article/details/gtfqgikkar.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtwlwqygsr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gtzpdddcbi.html

Go:   func add(a, b int) int
来源：http://dali.daxiang520.top/Article/details/gtycfwyhig.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jinqigfzy.top/Article/details/gtokyiyhxi.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlblzwzli.html

[C14] 泛型函数
来源：http://dali.tian-w.cn/Article/details/gtceuvqpze.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hnxiangtu.top/Article/details/gtricbzzbm.html

PHP:  // 无泛型
来源：http://dali.yj20258888.top/Article/details/gthrbcjkob.html

JS:   // 无泛型
来源：http://dali.birdmap.top/Article/details/gtwnmyzwdo.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yueranfly.top/Article/details/gtxoavyqhn.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yuanzhike.top/Article/details/gtnxrygoia.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jlsjyb.cn/Article/details/gtqmguydku.html

Ruby: # 无泛型
来源：http://dali.9152youxi.cn/Article/details/gteuysoyky.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zdqjudy.top/Article/details/gteqklvukc.html

[C15] 解构 / 展开参数
来源：http://dali.cdnleiting.top/Article/details/gtoerehybd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yonumen.top/Article/details/gtzcufgpxi.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtybhlccoc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.daria6918.cn/Article/details/gtmzzvkscg.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtaxjhrrgk.html

Java: // 无解构
来源：http://dali.daria6918.cn/Article/details/gtzmgipacr.html

Go:   // 无解构
来源：http://dali.316326.xyz/Article/details/gtoyyudvim.html

Ruby: a, b = pair
来源：http://dali.0kj1m.cn/Article/details/gtclpkvgwt.html

C#:   var (a, b) = pair;
来源：http://dali.birdmap.top/Article/details/gtwzjlikac.html

[C16] 函数 / 方法重载
来源：http://dali.cqqwz.cn/Article/details/gteylcqpeu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yj20258.top/Article/details/gtqxbkpmwy.html

PHP:  // 无重载
来源：http://dali.yueranfly.top/Article/details/gtdjqvekka.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmhfdydlp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.dianchejie.cn/Article/details/gtgvbrpoab.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cheryme.top/Article/details/gtbhpkrzwk.html

Go:   // 无重载：用不同函数名
来源：http://dali.hysaishi.cn/Article/details/gtdjhmdmjc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jiagoushi.top/Article/details/gtlrbcvexi.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhongyouzk.top/Article/details/gtmxmrckxo.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtwvwxpskb.html

D. 数组 / 列表 / 集合
来源：http://dali.jqgufenzy.top/Article/details/gtmwnsmgun.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtiqknptbj.html

[D01] 创建数组 / 列表
来源：http://dali.sysykeji.top/Article/details/gtkcgllgxs.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.dashuyun.cn/Article/details/gtxpegnbpd.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xylfe.cn/Article/details/gtulshkikt.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gtclbgrsnl.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.0kj1m.cn/Article/details/gtcpuojcir.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.redwolf501.top/Article/details/gtfadtqkrm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jqgfzy.top/Article/details/gtfuipdlym.html

Ruby: arr = [1, 2, 3]
来源：http://dali.andypj.xyz/Article/details/gtzqbtvise.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.nanxuanxn.top/Article/details/gtcpofmqgs.html

[D02] 追加元素到末尾
来源：http://dali.zhixingplan.top/Article/details/gthertojlz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhiwuduotai.top/Article/details/gtpoxrjaih.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hammf.cn/Article/details/gtorxdkvhn.html

JS:   arr.push(4);
来源：http://dali.hysaishi.cn/Article/details/gtyijfrzsi.html

TS:   arr.push(4);
来源：http://dali.yj20258888.top/Article/details/gtcudswlgb.html

Java: list.add(4);
来源：http://dali.cdnleiting.top/Article/details/gtfofveotf.html

Go:   arr = append(arr, 4)
来源：http://dali.yj20258888.top/Article/details/gtwukbgjxn.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.svipenyu.cn/Article/details/gtfsierrmz.html

C#:   list.Add(4);
来源：http://dali.cucudq.cn/Article/details/gtcgvcnxvw.html

[D03] 在指定位置插入元素
来源：http://dali.fzhhl.top/Article/details/gtzoaudsng.html

Py:   arr.insert(0, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtddhgdlch.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ivvv.top/Article/details/gtsrejvrmn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yj20258888.top/Article/details/gtsbfujrda.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhoulong.xyz/Article/details/gtdfaqixlk.html

Java: list.add(0, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtqrjcbaol.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhixingplan.top/Article/details/gtzsvlkyzg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.daxiang520.top/Article/details/gtfevansgr.html

C#:   list.Insert(0, 0);
来源：http://dali.hysaishi.cn/Article/details/gtwrdijpay.html

[D04] 删除元素
来源：http://dali.xuetiantiany.cn/Article/details/gtzsnjtfmb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.tian-w.cn/Article/details/gtxtklfavq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiwfeukld.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zdqjudy.top/Article/details/gtnqdkoxif.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gtjjjbhyrd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.havefunace.top/Article/details/gtfygilbqy.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hnqzz.top/Article/details/gtvmdfydij.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtbsqwpezh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhoulong.xyz/Article/details/gtatcfbkfr.html

[D05] 访问与修改元素
来源：http://dali.quarkkingdee.top/Article/details/gtljrnyoxs.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangdashe.top/Article/details/gtcojvxllw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cheryme.top/Article/details/gtbdwlqano.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.redwolf501.top/Article/details/gtbgfhdwej.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gaohongyu789.top/Article/details/gtqskkqwnm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinqigufen.top/Article/details/gtqgpbioot.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.quarkkingdee.top/Article/details/gtrqlcefno.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gotoacloud.top/Article/details/gtdkcbqzjl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shangyingyoupin.top/Article/details/gttkvmsanx.html

[D06] 数组长度
来源：http://dali.sxryk.cn/Article/details/gtckzujacf.html

Py:   len(arr)
来源：http://dali.nanxinkj.top/Article/details/gtblkrgdnw.html

PHP:  count($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtlzhuielu.html

JS:   arr.length
来源：http://dali.sxryk.cn/Article/details/gtnxrqsuyt.html

TS:   arr.length
来源：http://dali.jinqigufen.top/Article/details/gteppmvkzw.html

Java: list.size();
来源：http://dali.birdmap.top/Article/details/gtbznrfule.html

Go:   len(arr)
来源：http://dali.sufxvd.cn/Article/details/gtawyimzui.html

Ruby: arr.length; arr.size
来源：http://dali.hammf.cn/Article/details/gtdzvwcwwl.html

C#:   list.Count;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmbxvekpr.html

[D07] 切片 / 取子数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpihqkblc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zycfv.cn/Article/details/gtngqrogal.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.nwbrower.top/Article/details/gtkbplaprl.html

JS:   arr.slice(1, 4);
来源：http://dali.aizwys.cn/Article/details/gtkxudkcdq.html

TS:   arr.slice(1, 4);
来源：http://dali.jinqigfzy.top/Article/details/gtwljyxebf.html

Java: list.subList(1, 4);
来源：http://dali.jqgfzy.top/Article/details/gttfpmnlig.html

Go:   arr[1:4]
来源：http://dali.feifeiyinyue.top/Article/details/gtxnmrydme.html

Ruby: arr[1, 3]
来源：http://dali.guannengcc.top/Article/details/gtopggqrhz.html

C#:   list.GetRange(1, 3);
来源：http://dali.snrcjt.cn/Article/details/gtitmcipml.html

[D08] 合并两个数组
来源：http://dali.0kj1m.cn/Article/details/gtufjihqno.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinqigufen.top/Article/details/gteslbrbkf.html

PHP:  array_merge($a, $b);
来源：http://dali.jianghu66.top/Article/details/gtygevkvds.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenlongwang.top/Article/details/gtcdjsnhfh.html

TS:   [...a, ...b];
来源：http://dali.zhiwuduotai.top/Article/details/gtuitkewwm.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.0kj1m.cn/Article/details/gtnofoognk.html

Go:   append(a, b...)
来源：http://dali.yvedp.cn/Article/details/gtwhguxeaa.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhongyouzk.top/Article/details/gtdcamexfy.html

C#:   a.Concat(b).ToList()
来源：http://dali.yonumen.top/Article/details/gtlmfwcbgu.html

[D09] 排序（升序）
来源：http://dali.shuidangran.top/Article/details/gtnqucyzdc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cheryme.top/Article/details/gtrlfphyim.html

PHP:  sort($arr);
来源：http://dali.ivvv.top/Article/details/gtxwarlmbf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.sufxvd.cn/Article/details/gtpbrqpzca.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.havefunace.top/Article/details/gtzchixlyk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xziqi.cn/Article/details/gtbjsmyghc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yj202588.top/Article/details/gtjbvabrjk.html

Ruby: arr.sort
来源：http://dali.ybcxt.top/Article/details/gtlgkmoqmf.html

C#:   list.Sort();
来源：http://dali.wangdashe.top/Article/details/gtckpnodxo.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhongyouzk.top/Article/details/gtmayfzjbd.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.birdmap.top/Article/details/gtnwwivbpb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.pycfn.com/Article/details/gtleemsitl.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yvedp.cn/Article/details/gtndhjozry.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gthfxmwjyl.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.nanxinkj.top/Article/details/gtvcsnzdos.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hysaishi.cn/Article/details/gtdnsepaor.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jqgufenzy.top/Article/details/gtygqxgwvs.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xinyue.icu/Article/details/gtttnqqamb.html

[D11] 反转数组
来源：http://dali.dashuyun.cn/Article/details/gtopxtzdje.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhengqikj.top/Article/details/gtlsywgtcx.html

PHP:  array_reverse($arr);
来源：http://dali.gzhubu.top/Article/details/gthsbewjdc.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yvedp.cn/Article/details/gtsbsdcvfg.html

TS:   [...arr].reverse();
来源：http://dali.xuetiantiany.cn/Article/details/gtyovcidln.html

Java: Collections.reverse(list);
来源：http://dali.feifeiyinyue.top/Article/details/gtegfnaeim.html

Go:   slices.Reverse(arr)
来源：http://dali.gogol.net.cn/Article/details/gtoqfadfnw.html

Ruby: arr.reverse
来源：http://dali.snrcjt.cn/Article/details/gtvzcgqvpg.html

C#:   list.Reverse();
来源：http://dali.daria6918.cn/Article/details/gtprtzpvee.html

[D12] 查找元素下标
来源：http://dali.cdnleiting.top/Article/details/gtambiqzsc.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhoulong.xyz/Article/details/gtlrtncdlx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.316326.xyz/Article/details/gtnwoxgcxm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shuidangran.top/Article/details/gtqhasbntk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cheryme.top/Article/details/gttxciheln.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xinyue.icu/Article/details/gtcocsmbcc.html

Go:   slices.Index(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gtfbpwlbyj.html

Ruby: arr.index(x)
来源：http://dali.cashguo.top/Article/details/gtnrmgbwlv.html

C#:   list.IndexOf(x);
来源：http://dali.yongpay.top/Article/details/gtkhvvwjmb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.aibaodan.cn/Article/details/gtixplhotj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.c1oappe.top/Article/details/gtrjxsgyoc.html


<!-- 参考信息 -->