代发 wailian999

[B13] 判断是否为数字
来源：http://dali.bjfxy.top/Article/details/gthpxwzama.html

Py:   isinstance(x, (int, float))
来源：http://dali.hnxiangtu.top/Article/details/gtcxdzfhdc.html

PHP:  is_numeric($x)
来源：http://dali.xuanzx.com/Article/details/gtdhsanwmc.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jlsjyb.cn/Article/details/gtrzhdpdho.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gteaflaeda.html

Java: x instanceof Number
来源：http://dali.gogol.net.cn/Article/details/gtcjbipmzp.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhengqikj.top/Article/details/gttpwwinek.html

Ruby: x.is_a?(Numeric)
来源：http://dali.quarkkingdee.top/Article/details/gtbqvudwqh.html

C#:   x is int or double or decimal
来源：http://dali.cheryme.top/Article/details/gtcxoqsnvy.html

[B14] 判断值是否在集合内
来源：http://dali.316326.xyz/Article/details/gtwddecpbx.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.aizwys.cn/Article/details/gttptpbsmn.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.wangshuangyany.cn/Article/details/gtbgbfcjos.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ehwqpu.com/Article/details/gtiubsypgd.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.meibo888.top/Article/details/gtlkqefeee.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtdmkgidps.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtqpzroogy.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.daria6918.cn/Article/details/gtaqvhdwro.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xylfe.cn/Article/details/gtrzwkpwbc.html

[B15] 布尔运算与取反
来源：http://dali.gogol.net.cn/Article/details/gtmknxhxyp.html

Py:   a and b or not c
来源：http://dali.jyoumei.cn/Article/details/gtvcvrrdsn.html

PHP:  $a && $b || !$c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqpphyzte.html

JS:   a && b || !c
来源：http://dali.shuidangran.top/Article/details/gthbiypkde.html

TS:   a && b || !c
来源：http://dali.fzhhl.top/Article/details/gtctmdnyuc.html

Java: a && b || !c
来源：http://dali.yj20258.top/Article/details/gtdpgrannp.html

Go:   a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gtuwixqjbv.html

Ruby: a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gtfmsqkcxk.html

C#:   a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gtbiyflwec.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.sufxvd.cn/Article/details/gtqhtaunfa.html

Py:   if not data: return
来源：http://dali.xuetiantiany.cn/Article/details/gtpsrctxpg.html

PHP:  if (!$data) { return; }
来源：http://dali.zhixingplan.top/Article/details/gtlaalevgd.html

JS:   if (!data) return;
来源：http://dali.daxiang520.top/Article/details/gtvyivecwm.html

TS:   if (!data) return;
来源：http://dali.0kj1m.cn/Article/details/gttvdotqej.html

Java: if (data == null) return;
来源：http://dali.c1oappe.top/Article/details/gtmrohxhlb.html

Go:   if data == nil { return }
来源：http://dali.shzxlz.cn/Article/details/gtypjkhzzi.html

Ruby: return if data.nil?
来源：http://dali.haohaochexian.top/Article/details/gtmrzvavbc.html

C#:   if (data == null) return;
来源：http://dali.zdqjudy.top/Article/details/gthdyxuyku.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnfleqaiy.html

C. 函数与作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gteaxkyusc.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtpjfxqexf.html

[C01] 定义函数
来源：http://dali.yanxiufei.cn/Article/details/gtnvpfllrm.html

Py:   def add(a, b): return a + b
来源：http://dali.dianchejie.cn/Article/details/gtydcsekat.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yueranfly.top/Article/details/gtzqgiwkln.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gtefzaypgw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrfhfijte.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gtcuqgbbfk.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.0kj1m.cn/Article/details/gtqsuznrty.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jyoumei.cn/Article/details/gtzketpxsx.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gtilhtqivl.html

[C02] 默认参数
来源：http://dali.snrcjt.cn/Article/details/gtqfebdioc.html

Py:   def greet(name="World"): return name
来源：http://dali.zycfv.cn/Article/details/gtkixbukrs.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.nanxuanxn.top/Article/details/gtxouctksq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yongpay.top/Article/details/gtsymiezaa.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtdoexdlrd.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.guowangkeji.top/Article/details/gttrulkjkf.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.wangdashe.top/Article/details/gtdtpcxoqg.html

Ruby: def greet(name = "World") = name
来源：http://dali.sweek.top/Article/details/gtebooqhea.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.quarkkingdee.top/Article/details/gtsbvnxjwi.html

[C03] 可变参数
来源：http://dali.yuxming.cn/Article/details/gtzsigrxxh.html

Py:   def total(*args): return sum(args)
来源：http://dali.sysykeji.top/Article/details/gtcgqkzago.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.chenzaomai.com/Article/details/gtpjhmghuo.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cucudq.cn/Article/details/gtmebahnsk.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.aibaodan.cn/Article/details/gtbmnpixtu.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hnxiangtu.top/Article/details/gtqlumfhqb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.guowangkeji.top/Article/details/gtisknsjpt.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.0kj1m.cn/Article/details/gtvphwpjkm.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shanyushiyangtech.top/Article/details/gtfpbgsotm.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hywenlv.cn/Article/details/gtfcubiiif.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.dashuyun.cn/Article/details/gtixibwxam.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.chenjidiqi.icu/Article/details/gtryldtyef.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jyoumei.cn/Article/details/gtrdqtpmpu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhixingplan.top/Article/details/gtcuenhcia.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.guannengcc.top/Article/details/gtxshlfnjo.html

Go:   // 无：用配置结构体参数
来源：http://dali.ybcxt.top/Article/details/gtyzfjgxsa.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yj20258.top/Article/details/gtrocvkscl.html

C#:   f(a: 1, b: 2)
来源：http://dali.gogol.net.cn/Article/details/gtrusfmopa.html

[C05] 返回多个值
来源：http://dali.bjfxy.top/Article/details/gtvlucsqed.html

Py:   return a, b
来源：http://dali.pycfn.com/Article/details/gtqeecpyey.html

PHP:  return [$a, $b];
来源：http://dali.yj202588.top/Article/details/gtucbhdahc.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jianghu66.top/Article/details/gtylhinuqg.html

TS:   return { a, b };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjeqddmpc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.wangdashe.top/Article/details/gtwhpvlwmz.html

Go:   return a, b
来源：http://dali.jlsjyb.cn/Article/details/gtmhgtswwa.html

Ruby: return a, b
来源：http://dali.svipenyu.cn/Article/details/gtuobsorjm.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ybcxt.top/Article/details/gtvpnonxev.html

[C06] 匿名函数 / lambda
来源：http://dali.hongshengwenyu.top/Article/details/gtyefpyfip.html

Py:   square = lambda x: x * x
来源：http://dali.shzxlz.cn/Article/details/gtcmyowvka.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.chenzaomai.com/Article/details/gtrlemqlmz.html

JS:   const square = x => x * x;
来源：http://dali.nanxinkj.top/Article/details/gtjifcoozv.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.9152youxi.cn/Article/details/gtvpcomffh.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.fengsongda.top/Article/details/gtjpfdpmuq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jiagoushi.top/Article/details/gtrnwqrnsf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.svipenyu.cn/Article/details/gtzjhullzg.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gtitrttwlc.html

[C07] 把函数作为参数传入
来源：http://dali.vqdsnc.cn/Article/details/gtlzhwmswp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xuanzx.com/Article/details/gttqigvuef.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtxqqklvzn.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yonumen.top/Article/details/gtanshcety.html

TS:   arr.map(String)
来源：http://dali.guowangkeji.top/Article/details/gthbisptvd.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtvdhfcjff.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.havefunace.top/Article/details/gtpqpecqja.html

Ruby: arr.map(&:upcase)
来源：http://dali.nwbrower.top/Article/details/gtvawrgdka.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.fzhhl.top/Article/details/gtniwbqjdo.html

[C08] 闭包
来源：http://dali.nanxinkj.top/Article/details/gtlvftrvuo.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shzxlz.cn/Article/details/gtmodugjvs.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yonumen.top/Article/details/gtelvvpjpw.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xinyue.icu/Article/details/gtsylcsutn.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yvedp.cn/Article/details/gtppufxxfk.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yueranfly.top/Article/details/gtyaitzsja.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zdqjudy.top/Article/details/gtdodandtv.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.nwbrower.top/Article/details/gtsatzurax.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhiwuduotai.top/Article/details/gtyygykjlc.html

[C09] 递归
来源：http://dali.cheryme.top/Article/details/gtrwkxzaak.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.bjfxy.top/Article/details/gtwrwnacot.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yvedp.cn/Article/details/gtqffrlmfj.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gaohongyu789.top/Article/details/gtzzrxzavb.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.iojbl.cn/Article/details/gtgpnuvcem.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.daxiang520.top/Article/details/gtkkczckjp.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.nwbrower.top/Article/details/gtmncagpsj.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtghxvtqnq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yuanzhike.top/Article/details/gtlwwfumbm.html

[C10] 变量作用域
来源：http://dali.zycfv.cn/Article/details/gtrnmmrfdg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jiagoushi.top/Article/details/gtejrdwvut.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjccwjmok.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.sxryk.cn/Article/details/gtrekoamiy.html

TS:   同 JS
来源：http://dali.shuidangran.top/Article/details/gtoipokowc.html

Java: 方法内为块级作用域
来源：http://dali.hongshengwenyu.top/Article/details/gtcfjezzqe.html

Go:   花括号块级作用域
来源：http://dali.gaohongyu789.top/Article/details/gtxikakrgr.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jlsjyb.cn/Article/details/gttaekwhhg.html

C#:   块级作用域
来源：http://dali.cqqwz.cn/Article/details/gthhajqyor.html

[C11] 模块导入与导出
来源：http://dali.zhixingplan.top/Article/details/gtkmhvrgjs.html

Py:   from module import func
来源：http://dali.daria6918.cn/Article/details/gtdncfaryt.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shanyushiyangtech.top/Article/details/gtogchpwxa.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.wangdashe.top/Article/details/gtlpffvyec.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.shanyushiyangtech.top/Article/details/gtwuwnbvfe.html

Java: import java.util.List;
来源：http://dali.iojbl.cn/Article/details/gtvpbjiias.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.daria6918.cn/Article/details/gtxlvywdpe.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ydzc1.top/Article/details/gtqeuvuako.html

C#:   using System.Text;
来源：http://dali.ydzc1.top/Article/details/gtbgzyeygw.html

[C12] 立即执行函数 IIFE
来源：http://dali.0kj1m.cn/Article/details/gtdmeprdzz.html

Py:   (lambda: print("run"))()
来源：http://dali.svipenyu.cn/Article/details/gtszvbntoe.html

PHP:  (function () { echo "run"; })();
来源：http://dali.svipenyu.cn/Article/details/gtopqboyry.html

JS:   (() => { console.log("run"); })();
来源：http://dali.gogol.net.cn/Article/details/gtberweusw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cheryme.top/Article/details/gtmogrdkvc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.pengpengdd.cyou/Article/details/gtfobvezms.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.svipenyu.cn/Article/details/gtojvtimct.html

Ruby: -> { puts "run" }.call
来源：http://dali.hfpthk.cn/Article/details/gtittbbcpf.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.chenjidiqi.icu/Article/details/gtxpbzdqjn.html

[C13] 类型声明 / 类型注解
来源：http://dali.pengpengdd.cyou/Article/details/gtpjfnycdx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yuxming.cn/Article/details/gtyssudzlw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gtawpkflhf.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xuetiantiany.cn/Article/details/gtkylpqupt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtbdvqrfgc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.birdmap.top/Article/details/gtxmzivyju.html

Go:   func add(a, b int) int
来源：http://dali.jiagoushi.top/Article/details/gtxrzfmnbo.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.pycfn.com/Article/details/gtgjksinzw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ybcxt.top/Article/details/gtgrbmjpbx.html

[C14] 泛型函数
来源：http://dali.ppjwa.cn/Article/details/gtrgbpryei.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.9152youxi.cn/Article/details/gtvszsmsvl.html

PHP:  // 无泛型
来源：http://dali.guowangkeji.top/Article/details/gtynanwoxf.html

JS:   // 无泛型
来源：http://dali.tanke756.top/Article/details/gtazmfiukw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.c1oappe.top/Article/details/gtvqshtdrg.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.daxiang520.top/Article/details/gtdwdnunuu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.havefunace.top/Article/details/gtsftotgzq.html

Ruby: # 无泛型
来源：http://dali.hysaishi.cn/Article/details/gtfppydydg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhoulong.xyz/Article/details/gtiunghwmr.html

[C15] 解构 / 展开参数
来源：http://dali.gogol.net.cn/Article/details/gtbgdbjogq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.mhx1999.top/Article/details/gtigspqbga.html

PHP:  [$a, $b] = $pair;
来源：http://dali.haohaochexian.top/Article/details/gtrzoqxmlu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.fzhhl.top/Article/details/gtohnppcqw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jlsjyb.cn/Article/details/gttbrnmctt.html

Java: // 无解构
来源：http://dali.nanxuanxn.top/Article/details/gtgqimouar.html

Go:   // 无解构
来源：http://dali.guannengcc.top/Article/details/gtaxqvdmjh.html

Ruby: a, b = pair
来源：http://dali.cdnleiting.top/Article/details/gthdvhsfeh.html

C#:   var (a, b) = pair;
来源：http://dali.xuetiantiany.cn/Article/details/gthpfqjiwb.html

[C16] 函数 / 方法重载
来源：http://dali.snrcjt.cn/Article/details/gtlxfybdzr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cqqwz.cn/Article/details/gtafeewilg.html

PHP:  // 无重载
来源：http://dali.nanxuanxn.top/Article/details/gtzhdjoggh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.gogol.net.cn/Article/details/gtpdugfetc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cheryme.top/Article/details/gtgohlqssu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgyymhdyf.html

Go:   // 无重载：用不同函数名
来源：http://dali.hongshengwenyu.top/Article/details/gtjtuyiwfu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sxryk.cn/Article/details/gtoocisezf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtnnowogqj.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtcbajonnc.html

D. 数组 / 列表 / 集合
来源：http://dali.aibaodan.cn/Article/details/gtwvwtbzfl.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtcybbtlsy.html

[D01] 创建数组 / 列表
来源：http://dali.xuetiantiany.cn/Article/details/gtazqsxeqo.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.aibaodan.cn/Article/details/gtoihxeeza.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhixingplan.top/Article/details/gtabseyjjp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cheryme.top/Article/details/gtpwygplnn.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.dianchejie.cn/Article/details/gtvlmqjthd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zycfv.cn/Article/details/gtkjfmkncu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.sysykeji.top/Article/details/gtazassumo.html

Ruby: arr = [1, 2, 3]
来源：http://dali.snrcjt.cn/Article/details/gtqrfklteo.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhengqikj.top/Article/details/gtonqxzycf.html

[D02] 追加元素到末尾
来源：http://dali.gaohongyu789.top/Article/details/gtxvovftrn.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.pengpengdd.cyou/Article/details/gtyrwbgfct.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yj202588.top/Article/details/gtcosmsgtj.html

JS:   arr.push(4);
来源：http://dali.shangyingyoupin.top/Article/details/gtitmkeuie.html

TS:   arr.push(4);
来源：http://dali.zhoulong.xyz/Article/details/gtztluvivo.html

Java: list.add(4);
来源：http://dali.jyoumei.cn/Article/details/gtdjmaolyj.html

Go:   arr = append(arr, 4)
来源：http://dali.mhx1999.top/Article/details/gtffbrlamx.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gzhubu.top/Article/details/gtkbjopbgd.html

C#:   list.Add(4);
来源：http://dali.ybcxt.top/Article/details/gtfasyulcf.html

[D03] 在指定位置插入元素
来源：http://dali.yj20258888.top/Article/details/gtgbizaiqi.html

Py:   arr.insert(0, 0)
来源：http://dali.yvedp.cn/Article/details/gtrwnpribp.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xuetiantiany.cn/Article/details/gtwudhfxug.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.smart0.xyz/Article/details/gtrjoojypy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.0kj1m.cn/Article/details/gtrxcufnyt.html

Java: list.add(0, 0);
来源：http://dali.xinyue.icu/Article/details/gtfcwwajdn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.havefunace.top/Article/details/gtvkdbaclm.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhiwuduotai.top/Article/details/gtldvyeerk.html

C#:   list.Insert(0, 0);
来源：http://dali.yj20258.top/Article/details/gtvdakwyty.html

[D04] 删除元素
来源：http://dali.gogol.net.cn/Article/details/gtzvuspade.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhongyouzk.top/Article/details/gtinrjpuzs.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.wangdashe.top/Article/details/gtuowuqzfm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinqigufen.top/Article/details/gtbbqxjopb.html

TS:   arr.splice(0, 1);
来源：http://dali.yanxiufei.cn/Article/details/gtzzlhekfm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ybcxt.top/Article/details/gtnyqsrhro.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jinghuilouyu.cn/Article/details/gttisfplcg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jianghu66.top/Article/details/gteexkjmsp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.chenjidiqi.icu/Article/details/gtfcxohojv.html

[D05] 访问与修改元素
来源：http://dali.nanxinkj.top/Article/details/gtdwkenvfb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zdqjudy.top/Article/details/gtilbtkjyy.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.svipenyu.cn/Article/details/gtdtbdpwyf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shuidangran.top/Article/details/gtdgkftsby.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.guannengcc.top/Article/details/gtgprpwhcr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hnqzz.top/Article/details/gtgjsdstnf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hnqzz.top/Article/details/gtmehmcirv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zdqjudy.top/Article/details/gtooytqsgj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.316326.xyz/Article/details/gteyoustdh.html

[D06] 数组长度
来源：http://dali.xuanzx.com/Article/details/gtprzutxle.html

Py:   len(arr)
来源：http://dali.sufxvd.cn/Article/details/gtobhaqehp.html

PHP:  count($arr);
来源：http://dali.sysykeji.top/Article/details/gtpiljhzii.html

JS:   arr.length
来源：http://dali.c1oappe.top/Article/details/gtynkajzcq.html

TS:   arr.length
来源：http://dali.sufxvd.cn/Article/details/gtoztutozk.html

Java: list.size();
来源：http://dali.gzhubu.top/Article/details/gtvyfmivoq.html

Go:   len(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtwyskqncs.html

Ruby: arr.length; arr.size
来源：http://dali.dashuyun.cn/Article/details/gthefbcfid.html

C#:   list.Count;
来源：http://dali.jiagoushi.top/Article/details/gtwoerujbx.html

[D07] 切片 / 取子数组
来源：http://dali.hnxiangtu.top/Article/details/gtjjgsnfuk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cdnleiting.top/Article/details/gtvtkrvjqx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.nanxuanxn.top/Article/details/gtihqtueal.html

JS:   arr.slice(1, 4);
来源：http://dali.chenzaomai.com/Article/details/gtlgiontik.html

TS:   arr.slice(1, 4);
来源：http://dali.daxiang520.top/Article/details/gttekjmvol.html

Java: list.subList(1, 4);
来源：http://dali.chenzaomai.com/Article/details/gtzqwfshco.html

Go:   arr[1:4]
来源：http://dali.pycfn.com/Article/details/gtwqmyxjke.html

Ruby: arr[1, 3]
来源：http://dali.sufxvd.cn/Article/details/gtwirrggbu.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtelxkbipx.html

[D08] 合并两个数组
来源：http://dali.hywenlv.cn/Article/details/gttmzcjqlr.html

Py:   a + b;  a.extend(b)
来源：http://dali.wangdashe.top/Article/details/gtqehnlspb.html

PHP:  array_merge($a, $b);
来源：http://dali.9152youxi.cn/Article/details/gteunsnhbg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ppjwa.cn/Article/details/gtawjupmsk.html

TS:   [...a, ...b];
来源：http://dali.jianghu66.top/Article/details/gtxhlbxuuw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jinqigufen.top/Article/details/gtismoxuza.html

Go:   append(a, b...)
来源：http://dali.guowangkeji.top/Article/details/gthyeanohq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jyoumei.cn/Article/details/gtvhscfcxw.html

C#:   a.Concat(b).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtcxuvtvek.html

[D09] 排序（升序）
来源：http://dali.guannengcc.top/Article/details/gtvhuyggbi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xinyue.icu/Article/details/gtisxmyquj.html

PHP:  sort($arr);
来源：http://dali.dianchejie.cn/Article/details/gtemratjxb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yonumen.top/Article/details/gtiglmisnf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinqigufen.top/Article/details/gtpgkaqowi.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zdqjudy.top/Article/details/gtqwiacnpo.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtzdseniki.html

Ruby: arr.sort
来源：http://dali.xuanzx.com/Article/details/gtnidvogca.html

C#:   list.Sort();
来源：http://dali.yj202588.top/Article/details/gtbpfacqny.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hywenlv.cn/Article/details/gtoedfxmnc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcqwwuufr.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.fzhhl.top/Article/details/gtlttakjbe.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zdqjudy.top/Article/details/gtsyzdsvvw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkwteomnf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.bjfxy.top/Article/details/gtpnqtzeae.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.sysykeji.top/Article/details/gtbrtffjau.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zycfv.cn/Article/details/gtwhoeyvqk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvpraumiu.html

[D11] 反转数组
来源：http://dali.yanxiufei.cn/Article/details/gtwlbcdzeh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yj20258888.top/Article/details/gtzesuguyw.html

PHP:  array_reverse($arr);
来源：http://dali.havefunace.top/Article/details/gtngxluotp.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.snrcjt.cn/Article/details/gtgybgngdy.html

TS:   [...arr].reverse();
来源：http://dali.gotoacloud.top/Article/details/gtnlpxdtln.html

Java: Collections.reverse(list);
来源：http://dali.andypj.xyz/Article/details/gtcwsenjwc.html

Go:   slices.Reverse(arr)
来源：http://dali.yonumen.top/Article/details/gtseixowgz.html

Ruby: arr.reverse
来源：http://dali.gotoacloud.top/Article/details/gtfekhaeqo.html

C#:   list.Reverse();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwgaddgak.html

[D12] 查找元素下标
来源：http://dali.gaohongyu789.top/Article/details/gtrigpdmts.html

Py:   arr.index(x);  x in arr
来源：http://dali.yuanzhike.top/Article/details/gtaqnarkan.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yanxiufei.cn/Article/details/gtjjuuyhwt.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgfzy.top/Article/details/gtwizasqgc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgwyjeliz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jyoumei.cn/Article/details/gtwjdrkpwd.html

Go:   slices.Index(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gtpqjywwuo.html

Ruby: arr.index(x)
来源：http://dali.svipenyu.cn/Article/details/gtdygnrbpa.html

C#:   list.IndexOf(x);
来源：http://dali.guowangkeji.top/Article/details/gtwmilwqox.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthcogfcdg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yvedp.cn/Article/details/gtbonhauzv.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yongpay.top/Article/details/gtxriynwmz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.redwolf501.top/Article/details/gtrxogigcr.html

TS:   arr.filter(x => x > 3)
来源：http://dali.aizwys.cn/Article/details/gtyyrtplbl.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cdnleiting.top/Article/details/gtsxyyelkj.html


<!-- 参考信息 -->