代发 wailian999

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xylfe.cn/Article/details/gtppsmnivw.html

Java: x instanceof Number
来源：http://dali.jianghu66.top/Article/details/gtrgcypqrb.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hysaishi.cn/Article/details/gtkxtgnvuj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.feifeiyinyue.top/Article/details/gtgkoskhms.html

C#:   x is int or double or decimal
来源：http://dali.yuanzhike.top/Article/details/gtfucaiozw.html

[B14] 判断值是否在集合内
来源：http://dali.smart0.xyz/Article/details/gtmfcarzog.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xylfe.cn/Article/details/gtjhguxiaa.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hfpthk.cn/Article/details/gtkcfhajsq.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.sysykeji.top/Article/details/gtisqizryp.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.aizwys.cn/Article/details/gtuwcknbsf.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.cqqwz.cn/Article/details/gtammlxylt.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtlsawfice.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmnkdwrtb.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.snrcjt.cn/Article/details/gtghpethny.html

[B15] 布尔运算与取反
来源：http://dali.jiagoushi.top/Article/details/gtlcrvgxkb.html

Py:   a and b or not c
来源：http://dali.cashguo.top/Article/details/gtkfyrewtk.html

PHP:  $a && $b || !$c
来源：http://dali.jyoumei.cn/Article/details/gtavfboluy.html

JS:   a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gtlisddrny.html

TS:   a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gtktvxduet.html

Java: a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gtoguyuwai.html

Go:   a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gtbdkphyyh.html

Ruby: a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gtkeavgoep.html

C#:   a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtklfrvbuf.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.sxryk.cn/Article/details/gtsipantbe.html

Py:   if not data: return
来源：http://dali.redwolf501.top/Article/details/gtdcxhnbbi.html

PHP:  if (!$data) { return; }
来源：http://dali.tian-w.cn/Article/details/gtzemekgno.html

JS:   if (!data) return;
来源：http://dali.meibo888.top/Article/details/gthruycrrv.html

TS:   if (!data) return;
来源：http://dali.jqgufenzy.top/Article/details/gtnzeouquo.html

Java: if (data == null) return;
来源：http://dali.andypj.xyz/Article/details/gtndlgclxo.html

Go:   if data == nil { return }
来源：http://dali.9152youxi.cn/Article/details/gtrlwprqre.html

Ruby: return if data.nil?
来源：http://dali.snrcjt.cn/Article/details/gtqsakmvcu.html

C#:   if (data == null) return;
来源：http://dali.hnxiangtu.top/Article/details/gtpgehlhaj.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtunmtktvs.html

C. 函数与作用域
来源：http://dali.guowangkeji.top/Article/details/gthjqiyegv.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtzyhiojuz.html

[C01] 定义函数
来源：http://dali.sxryk.cn/Article/details/gtqhnjzqrw.html

Py:   def add(a, b): return a + b
来源：http://dali.shangyingyoupin.top/Article/details/gtubjsudph.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gteomutorz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gtrvtqixgp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gthbkgltcw.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gtmxbuvjoq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.cashguo.top/Article/details/gtglmmqbcf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.kuanghao11.cn/Article/details/gtymjgmhqn.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gthyfrecax.html

[C02] 默认参数
来源：http://dali.nanxuanxn.top/Article/details/gtyxfrhdif.html

Py:   def greet(name="World"): return name
来源：http://dali.quarkkingdee.top/Article/details/gtrfuzrwtg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ppjwa.cn/Article/details/gtbcbvzazz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtxtwkhigt.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.sweek.top/Article/details/gtvypqxrne.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhongyouzk.top/Article/details/gtqrvuiavg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.smart0.xyz/Article/details/gthersznav.html

Ruby: def greet(name = "World") = name
来源：http://dali.cqqwz.cn/Article/details/gtxjsinjnw.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shuidangran.top/Article/details/gtgkjqpkdj.html

[C03] 可变参数
来源：http://dali.vqdsnc.cn/Article/details/gtzcgdsiqw.html

Py:   def total(*args): return sum(args)
来源：http://dali.kuanghao11.cn/Article/details/gtjnestnth.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.feifeiyinyue.top/Article/details/gtnbanwlag.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hnqzz.top/Article/details/gtjirbtazx.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ppjwa.cn/Article/details/gtcoonsiju.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrjhrjutw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ybcxt.top/Article/details/gtnqjjmobn.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.gogol.net.cn/Article/details/gtvhamavce.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ehwqpu.com/Article/details/gttrypvlpt.html

[C04] 命名参数 / 关键字参数
来源：http://dali.havefunace.top/Article/details/gtmpxlwzlg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.chenzaomai.com/Article/details/gtcgiuttrg.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hnxiangtu.top/Article/details/gtqgbmoefn.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.nwbrower.top/Article/details/gtwczlprnh.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.316326.xyz/Article/details/gtzohszxoj.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.fzhhl.top/Article/details/gtpwjbmjda.html

Go:   // 无：用配置结构体参数
来源：http://dali.hnqzz.top/Article/details/gtmdjxnuuc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jianghu66.top/Article/details/gtqbmvuqga.html

C#:   f(a: 1, b: 2)
来源：http://dali.havefunace.top/Article/details/gtnutuxsuc.html

[C05] 返回多个值
来源：http://dali.shuidangran.top/Article/details/gtarbznref.html

Py:   return a, b
来源：http://dali.zhoulong.xyz/Article/details/gtwqowkyzg.html

PHP:  return [$a, $b];
来源：http://dali.wangshuangyany.cn/Article/details/gtvmdlvnub.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.vqdsnc.cn/Article/details/gtxturkhdh.html

TS:   return { a, b };
来源：http://dali.yj202588.top/Article/details/gtkxjyeluj.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cqqwz.cn/Article/details/gtpsodlbkq.html

Go:   return a, b
来源：http://dali.cheryme.top/Article/details/gtyvfwmjrv.html

Ruby: return a, b
来源：http://dali.tanke756.top/Article/details/gtsurffjww.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yangfankeji.com/Article/details/gtekyumqis.html

[C06] 匿名函数 / lambda
来源：http://dali.daxiang520.top/Article/details/gtshsioluh.html

Py:   square = lambda x: x * x
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkqmvoyak.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gtfjrxnizb.html

JS:   const square = x => x * x;
来源：http://dali.9152youxi.cn/Article/details/gtpcavgxmk.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.wangdashe.top/Article/details/gtpsbgswpl.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.havefunace.top/Article/details/gthpbwokfd.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.andypj.xyz/Article/details/gtllgitgan.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yanxiufei.cn/Article/details/gthesokgyl.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cdnleiting.top/Article/details/gtioshokbf.html

[C07] 把函数作为参数传入
来源：http://dali.svipenyu.cn/Article/details/gtzyrzpoil.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yueranfly.top/Article/details/gtbimpedhp.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cqqwz.cn/Article/details/gtqlpdnbvm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.pycfn.com/Article/details/gtcwfcziau.html

TS:   arr.map(String)
来源：http://dali.fzhhl.top/Article/details/gtczzfshwh.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.sweek.top/Article/details/gtigyvyxmo.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.gogol.net.cn/Article/details/gtlxovclei.html

Ruby: arr.map(&:upcase)
来源：http://dali.pycfn.com/Article/details/gtyvcxjywy.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.vqdsnc.cn/Article/details/gtzjqbhyth.html

[C08] 闭包
来源：http://dali.jiagoushi.top/Article/details/gtpamqaovg.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.pengpengdd.cyou/Article/details/gtuiegkvvh.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.316326.xyz/Article/details/gtbiwkoazf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jinqigufen.top/Article/details/gtoixrmpjl.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xziqi.cn/Article/details/gtfsuffmse.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hammf.cn/Article/details/gtpgpvyrlu.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.9152youxi.cn/Article/details/gtimmnkhbs.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gogol.net.cn/Article/details/gtazrklnsm.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqamwtfbl.html

[C09] 递归
来源：http://dali.jiagoushi.top/Article/details/gtkbsrdzyu.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.gaohongyu789.top/Article/details/gtksgjsugx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.nanxuanxn.top/Article/details/gtfbsgotvb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.c1oappe.top/Article/details/gtnathrwte.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hammf.cn/Article/details/gtildcymhw.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.c1oappe.top/Article/details/gtmvjdoghq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jqgfzy.top/Article/details/gtabtppotl.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtumjhwrsz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.smart0.xyz/Article/details/gtlouotutj.html

[C10] 变量作用域
来源：http://dali.yj20258888.top/Article/details/gtnsubplyk.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xinyue.icu/Article/details/gtrpsxikoc.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.tian-w.cn/Article/details/gtaojjbhkm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.svipenyu.cn/Article/details/gtfppekqzj.html

TS:   同 JS
来源：http://dali.shangyingyoupin.top/Article/details/gtcbxntfvp.html

Java: 方法内为块级作用域
来源：http://dali.wangdashe.top/Article/details/gtmflopttj.html

Go:   花括号块级作用域
来源：http://dali.sysykeji.top/Article/details/gtwerugevu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.daxiang520.top/Article/details/gtzdlffisu.html

C#:   块级作用域
来源：http://dali.nanxuanxn.top/Article/details/gtfilyqoet.html

[C11] 模块导入与导出
来源：http://dali.cashguo.top/Article/details/gtgnwghoee.html

Py:   from module import func
来源：http://dali.jyoumei.cn/Article/details/gttxvvvzew.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yueranfly.top/Article/details/gtyodfxhzg.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrkbsjwfq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ydzc1.top/Article/details/gtveuyjfne.html

Java: import java.util.List;
来源：http://dali.nanxinkj.top/Article/details/gtkodiikwg.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sysykeji.top/Article/details/gtscqmbwmr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hongshengwenyu.top/Article/details/gtcksnkqrc.html

C#:   using System.Text;
来源：http://dali.316326.xyz/Article/details/gteyvcjjce.html

[C12] 立即执行函数 IIFE
来源：http://dali.cdnleiting.top/Article/details/gtenqzxfyh.html

Py:   (lambda: print("run"))()
来源：http://dali.feifeiyinyue.top/Article/details/gtcnyaaqdn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.bjfxy.top/Article/details/gtjlrtgfig.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ybcxt.top/Article/details/gtybdpxabl.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jiagoushi.top/Article/details/gtkdxewvei.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.tianlin.xyz/Article/details/gtfdjllozh.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtziktdblo.html

Ruby: -> { puts "run" }.call
来源：http://dali.yanxiufei.cn/Article/details/gtwcfgnqrz.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gzhubu.top/Article/details/gtnwhbzten.html

[C13] 类型声明 / 类型注解
来源：http://dali.ydzc1.top/Article/details/gtlgxydxcx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xziqi.cn/Article/details/gtprvdwgrj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gtwuluxsov.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ivvv.top/Article/details/gtaptlbhuw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gtwwebuxze.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gtvpvzrbdt.html

Go:   func add(a, b int) int
来源：http://dali.zhiwuduotai.top/Article/details/gtizqpykzx.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtawbulozy.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.fzhhl.top/Article/details/gtgtxjnswy.html

[C14] 泛型函数
来源：http://dali.aizwys.cn/Article/details/gtqbjcvnpm.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ivvv.top/Article/details/gtaidfbphr.html

PHP:  // 无泛型
来源：http://dali.sufxvd.cn/Article/details/gtmvyqjmhg.html

JS:   // 无泛型
来源：http://dali.shuidangran.top/Article/details/gtwfzmlkzb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yj20258888.top/Article/details/gtfofcuqtj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jianghu66.top/Article/details/gtwfghejbq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.smart0.xyz/Article/details/gtvpyqukwp.html

Ruby: # 无泛型
来源：http://dali.yongpay.top/Article/details/gtzggvlnhu.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtexrxslya.html

[C15] 解构 / 展开参数
来源：http://dali.shangyingyoupin.top/Article/details/gtnpwkeywd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shanyushiyangtech.top/Article/details/gtrdldtoyd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.nanxuanxn.top/Article/details/gtepyabmzl.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.guowangkeji.top/Article/details/gtutrlfabl.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.dianchejie.cn/Article/details/gtvxfduzni.html

Java: // 无解构
来源：http://dali.shuidangran.top/Article/details/gtovnssuic.html

Go:   // 无解构
来源：http://dali.cucudq.cn/Article/details/gtwgzugfjn.html

Ruby: a, b = pair
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgbgjfnnx.html

C#:   var (a, b) = pair;
来源：http://dali.sxryk.cn/Article/details/gtuqqgclyk.html

[C16] 函数 / 方法重载
来源：http://dali.hfpthk.cn/Article/details/gtwahtielk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jyoumei.cn/Article/details/gtdyofvdli.html

PHP:  // 无重载
来源：http://dali.xziqi.cn/Article/details/gtajyxpubl.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.pengpengdd.cyou/Article/details/gtoedzhnij.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.iojbl.cn/Article/details/gtnimcohjx.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sweek.top/Article/details/gtfqclgxtt.html

Go:   // 无重载：用不同函数名
来源：http://dali.wangdashe.top/Article/details/gtdksatwns.html

Ruby: # 无重载：靠动态参数
来源：http://dali.daxiang520.top/Article/details/gtirfbrlny.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zdqjudy.top/Article/details/gtoroudbdo.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gttyvhezet.html

D. 数组 / 列表 / 集合
来源：http://dali.cheryme.top/Article/details/gtvovluzso.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtejttrqpf.html

[D01] 创建数组 / 列表
来源：http://dali.aibaodan.cn/Article/details/gtynmbxalp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cucudq.cn/Article/details/gtvyxtsbey.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yj202588.top/Article/details/gtbaeeilpv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yj202588.top/Article/details/gtbcrapcfb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.aizwys.cn/Article/details/gtsygbeezb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.guannengcc.top/Article/details/gtideidmmr.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinqigufen.top/Article/details/gtyngaskhq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shanyushiyangtech.top/Article/details/gtprjcbiuy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ybcxt.top/Article/details/gtwybxdxpt.html

[D02] 追加元素到末尾
来源：http://dali.yanxiufei.cn/Article/details/gtupptmxhu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.dashuyun.cn/Article/details/gtwufoslto.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.iojbl.cn/Article/details/gtvudiqoax.html

JS:   arr.push(4);
来源：http://dali.gotoacloud.top/Article/details/gtzzxkiolb.html

TS:   arr.push(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsiivznqp.html

Java: list.add(4);
来源：http://dali.pycfn.com/Article/details/gthkncnbdl.html

Go:   arr = append(arr, 4)
来源：http://dali.xziqi.cn/Article/details/gtgnqsugmy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.daxiang520.top/Article/details/gtfzjdgkom.html

C#:   list.Add(4);
来源：http://dali.tanke756.top/Article/details/gtuzhcplfv.html

[D03] 在指定位置插入元素
来源：http://dali.feifeiyinyue.top/Article/details/gtejwrqwvf.html

Py:   arr.insert(0, 0)
来源：http://dali.sufxvd.cn/Article/details/gtnrhydxth.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhoulong.xyz/Article/details/gtqkypubcz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gotoacloud.top/Article/details/gtdgjembza.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yangfankeji.com/Article/details/gtvqmlihjf.html

Java: list.add(0, 0);
来源：http://dali.shuidangran.top/Article/details/gtamzwlmjm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xinyue.icu/Article/details/gthmvizunf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.nwbrower.top/Article/details/gtjcchkhyy.html

C#:   list.Insert(0, 0);
来源：http://dali.redwolf501.top/Article/details/gtcswwkpmb.html

[D04] 删除元素
来源：http://dali.hnxiangtu.top/Article/details/gtrfqyqcbt.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdiuaoeyf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hnqzz.top/Article/details/gthxziogks.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xuanzx.com/Article/details/gtigpigzus.html

TS:   arr.splice(0, 1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthfykemqx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhengqikj.top/Article/details/gtzwcnvvrj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.haohaochexian.top/Article/details/gtehbjxzkd.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.316326.xyz/Article/details/gtvxlrpvbh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.dashuyun.cn/Article/details/gtaavrnquy.html

[D05] 访问与修改元素
来源：http://dali.sweek.top/Article/details/gtkggjdtkp.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.snrcjt.cn/Article/details/gtwlvonzja.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.kuanghao11.cn/Article/details/gtbbwbcmxl.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gtkjkmejwo.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.mhx1999.top/Article/details/gttmriijmu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhengqikj.top/Article/details/gtcjiexngf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmlduoixk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangdashe.top/Article/details/gtbqerckaa.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ehwqpu.com/Article/details/gtirotffhm.html

[D06] 数组长度
来源：http://dali.mhx1999.top/Article/details/gtqhddmfxn.html

Py:   len(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtonrdxqns.html

PHP:  count($arr);
来源：http://dali.ehwqpu.com/Article/details/gtkdsqhhzs.html

JS:   arr.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpahqsomy.html

TS:   arr.length
来源：http://dali.hongshengwenyu.top/Article/details/gtjllnxbxx.html

Java: list.size();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnkuxtifb.html

Go:   len(arr)
来源：http://dali.zycfv.cn/Article/details/gtskmpyblh.html

Ruby: arr.length; arr.size
来源：http://dali.smart0.xyz/Article/details/gteuiqcsan.html

C#:   list.Count;
来源：http://dali.cashguo.top/Article/details/gtwuedeqyp.html

[D07] 切片 / 取子数组
来源：http://dali.hnxiangtu.top/Article/details/gtlzzzapmg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cheryme.top/Article/details/gtwbtkfggr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.wangdashe.top/Article/details/gtshvnqewj.html

JS:   arr.slice(1, 4);
来源：http://dali.gzhubu.top/Article/details/gtwoexayio.html

TS:   arr.slice(1, 4);
来源：http://dali.hongshengwenyu.top/Article/details/gtrzgxszzr.html

Java: list.subList(1, 4);
来源：http://dali.smart0.xyz/Article/details/gtggnyxjjz.html

Go:   arr[1:4]
来源：http://dali.gogol.net.cn/Article/details/gtksbfwdww.html

Ruby: arr[1, 3]
来源：http://dali.chenlongwang.top/Article/details/gtnohheazr.html

C#:   list.GetRange(1, 3);
来源：http://dali.guannengcc.top/Article/details/gtpgpdxgkx.html

[D08] 合并两个数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqhthgfwc.html

Py:   a + b;  a.extend(b)
来源：http://dali.aizwys.cn/Article/details/gtktngqhqx.html

PHP:  array_merge($a, $b);
来源：http://dali.fzhhl.top/Article/details/gthyqtlpnz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yueranfly.top/Article/details/gtfjzonqvg.html

TS:   [...a, ...b];
来源：http://dali.jinqigufen.top/Article/details/gtnzkltrbj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhoulong.xyz/Article/details/gtjmslhyrs.html

Go:   append(a, b...)
来源：http://dali.sxryk.cn/Article/details/gtvwlqtqfq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.snrcjt.cn/Article/details/gtaxhkwixu.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhengqikj.top/Article/details/gtfoixvejd.html

[D09] 排序（升序）
来源：http://dali.ybcxt.top/Article/details/gtmacdtubh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhixingplan.top/Article/details/gtaqbnsvqa.html

PHP:  sort($arr);
来源：http://dali.sweek.top/Article/details/gtzluatrbe.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shuidangran.top/Article/details/gtnjuqoorh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.chenlongwang.top/Article/details/gtgwmftsmy.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xuetiantiany.cn/Article/details/gtaalrlboz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gthssvzbch.html

Ruby: arr.sort
来源：http://dali.0kj1m.cn/Article/details/gtxzahgrqq.html

C#:   list.Sort();
来源：http://dali.zhixingplan.top/Article/details/gtkgjrkmub.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.316326.xyz/Article/details/gtqauqapzp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.chenjidiqi.icu/Article/details/gtglljmtui.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xuanzx.com/Article/details/gthtkmqycs.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jlsjyb.cn/Article/details/gtfrucnxkc.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.birdmap.top/Article/details/gtdepkytvc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yonumen.top/Article/details/gtugmkyhgz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.chenlongwang.top/Article/details/gtgtqiyjjw.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.wangdashe.top/Article/details/gtusqqasgy.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hammf.cn/Article/details/gtvjouxjgp.html

[D11] 反转数组
来源：http://dali.pengpengdd.cyou/Article/details/gtsjqbdyxg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhongyouzk.top/Article/details/gtcrodhicu.html

PHP:  array_reverse($arr);
来源：http://dali.yueranfly.top/Article/details/gtrghhtjim.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sysykeji.top/Article/details/gtqevehuuy.html

TS:   [...arr].reverse();
来源：http://dali.redwolf501.top/Article/details/gtjaoshuaw.html

Java: Collections.reverse(list);
来源：http://dali.aibaodan.cn/Article/details/gtzokckgde.html

Go:   slices.Reverse(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtctitqrcr.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gtglxnfqtt.html

C#:   list.Reverse();
来源：http://dali.c1oappe.top/Article/details/gtglfmghqo.html

[D12] 查找元素下标
来源：http://dali.jqgfzy.top/Article/details/gthbcmrlrm.html

Py:   arr.index(x);  x in arr
来源：http://dali.xinyue.icu/Article/details/gtcerbqqzm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yonumen.top/Article/details/gtrctdgkmo.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.quarkkingdee.top/Article/details/gtubvgeixp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hfpthk.cn/Article/details/gtebzwzsjd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.nanxuanxn.top/Article/details/gtsmpukdwd.html

Go:   slices.Index(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtnnibjiee.html

Ruby: arr.index(x)
来源：http://dali.guannengcc.top/Article/details/gtoubifmhf.html

C#:   list.IndexOf(x);
来源：http://dali.pengpengdd.cyou/Article/details/gtlzjdapjp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cheryme.top/Article/details/gtgggfwmrg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sxryk.cn/Article/details/gtupwmimqi.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.pycfn.com/Article/details/gtyvcraiyu.html

JS:   arr.filter(x => x > 3)
来源：http://dali.daria6918.cn/Article/details/gtwjzacvnk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shuidangran.top/Article/details/gtolyphiih.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ivvv.top/Article/details/gtjguciqqr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gotoacloud.top/Article/details/gtobumlxgs.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhixingplan.top/Article/details/gtrvdfexxs.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xylfe.cn/Article/details/gtfamqvgfz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jyoumei.cn/Article/details/gtnwdfiiok.html


<!-- 参考信息 -->