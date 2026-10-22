代发 wailian999

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2omnpvqqj.html

Java: x instanceof Number
来源：http://dali.chenlongwang.top/Article/details/gt2yjatcffk.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jinqigfzy.top/Article/details/gt2rrsiwsqg.html

Ruby: x.is_a?(Numeric)
来源：http://dali.guowangkeji.top/Article/details/gt2cdhsmsxy.html

C#:   x is int or double or decimal
来源：http://dali.pengpengdd.cyou/Article/details/gt2lmyemqcr.html

[B14] 判断值是否在集合内
来源：http://dali.xuanzx.com/Article/details/gt2auxnvvoo.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.guowangkeji.top/Article/details/gt2vryohgcu.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhengqikj.top/Article/details/gt2jqgxcjci.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2lwjebxez.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.c1oappe.top/Article/details/gt2vaebeczz.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.sxryk.cn/Article/details/gt2kqvfguxc.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.meibo888.top/Article/details/gt2pionbnow.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yvedp.cn/Article/details/gt2lwtetkmt.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.tian-w.cn/Article/details/gt2lcepuqna.html

[B15] 布尔运算与取反
来源：http://dali.zhongyouzk.top/Article/details/gt2gcoqrvch.html

Py:   a and b or not c
来源：http://dali.kuanghao11.cn/Article/details/gt2clujkmhv.html

PHP:  $a && $b || !$c
来源：http://dali.xuetiantiany.cn/Article/details/gt2koakthlo.html

JS:   a && b || !c
来源：http://dali.ydzc1.top/Article/details/gt2gvrjpqyn.html

TS:   a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gt2sgmbesjy.html

Java: a && b || !c
来源：http://dali.ivvv.top/Article/details/gt2qjwpzuhi.html

Go:   a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gt2lvjdaamw.html

Ruby: a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jgcyzaei.html

C#:   a && b || !c
来源：http://dali.cucudq.cn/Article/details/gt2ktokdkuw.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ppjwa.cn/Article/details/gt2pdfrqxdu.html

Py:   if not data: return
来源：http://dali.jianghu66.top/Article/details/gt2ngeuwlzt.html

PHP:  if (!$data) { return; }
来源：http://dali.hnqzz.top/Article/details/gt2tczxrueg.html

JS:   if (!data) return;
来源：http://dali.tianlin.xyz/Article/details/gt2piludteg.html

TS:   if (!data) return;
来源：http://dali.nwbrower.top/Article/details/gt2apokcoha.html

Java: if (data == null) return;
来源：http://dali.gogol.net.cn/Article/details/gt2umkygvbp.html

Go:   if data == nil { return }
来源：http://dali.cashguo.top/Article/details/gt2ioldpbql.html

Ruby: return if data.nil?
来源：http://dali.gaohongyu789.top/Article/details/gt2dmdfebtw.html

C#:   if (data == null) return;
来源：http://dali.yonumen.top/Article/details/gt2nqaatvhv.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2tmugmoze.html

C. 函数与作用域
来源：http://dali.daxiang520.top/Article/details/gt2gasdtxcf.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2nzamzvsu.html

[C01] 定义函数
来源：http://dali.ivvv.top/Article/details/gt2bhdoywzx.html

Py:   def add(a, b): return a + b
来源：http://dali.guowangkeji.top/Article/details/gt2btfljnwz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2twihbhch.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gt2vipemxsx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gt2hdekvofq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gt2rsmqoqii.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jinqigufen.top/Article/details/gt2jngntbrc.html

Ruby: def add(a, b); a + b; end
来源：http://dali.dianchejie.cn/Article/details/gt2cyupjtla.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gt2fgqnybhu.html

[C02] 默认参数
来源：http://dali.dianchejie.cn/Article/details/gt2tfqlqdix.html

Py:   def greet(name="World"): return name
来源：http://dali.sysykeji.top/Article/details/gt2wjguzroo.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.nwbrower.top/Article/details/gt2sdpsmfdz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2wfnsfadn.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.fzhhl.top/Article/details/gt2pgzysxkp.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.0kj1m.cn/Article/details/gt2vewydggm.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.tianlin.xyz/Article/details/gt2gcpuoxnn.html

Ruby: def greet(name = "World") = name
来源：http://dali.9152youxi.cn/Article/details/gt2pcdgwerf.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.guowangkeji.top/Article/details/gt2klckddpk.html

[C03] 可变参数
来源：http://dali.chenzaomai.com/Article/details/gt2lokzsvqr.html

Py:   def total(*args): return sum(args)
来源：http://dali.cdnleiting.top/Article/details/gt2quqsyxip.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.daria6918.cn/Article/details/gt2ffrdkfrk.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sxryk.cn/Article/details/gt2mvyzpqnr.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenzaomai.com/Article/details/gt2tejdpfrw.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2unfwvjln.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.fzhhl.top/Article/details/gt2lpceaiuu.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xinyue.icu/Article/details/gt2nbmwadlh.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.daria6918.cn/Article/details/gt2hhvvpuyu.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hywenlv.cn/Article/details/gt2fbrewarl.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhoulong.xyz/Article/details/gt2otzlwlpw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.quarkkingdee.top/Article/details/gt2froqngch.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jyoumei.cn/Article/details/gt2oagrngla.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.quarkkingdee.top/Article/details/gt2utqcyfhj.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.chenjidiqi.icu/Article/details/gt2rrqfxysx.html

Go:   // 无：用配置结构体参数
来源：http://dali.feifeiyinyue.top/Article/details/gt2cmlmgtic.html

Ruby: f(a: 1, b: 2)
来源：http://dali.haohaochexian.top/Article/details/gt2gaxfkxyk.html

C#:   f(a: 1, b: 2)
来源：http://dali.birdmap.top/Article/details/gt2urhgaebc.html

[C05] 返回多个值
来源：http://dali.zhixingplan.top/Article/details/gt2zkmkuujj.html

Py:   return a, b
来源：http://dali.316326.xyz/Article/details/gt2lgmcywcg.html

PHP:  return [$a, $b];
来源：http://dali.guannengcc.top/Article/details/gt2scmhxhrr.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.meibo888.top/Article/details/gt2ijthmeyx.html

TS:   return { a, b };
来源：http://dali.xylfe.cn/Article/details/gt2zrgutaeb.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.gotoacloud.top/Article/details/gt2jejbyzuu.html

Go:   return a, b
来源：http://dali.jinqigfzy.top/Article/details/gt2cqmtoayr.html

Ruby: return a, b
来源：http://dali.smart0.xyz/Article/details/gt2lgkddovy.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cashguo.top/Article/details/gt2ilsehvfz.html

[C06] 匿名函数 / lambda
来源：http://dali.hongshengwenyu.top/Article/details/gt2sffbimpq.html

Py:   square = lambda x: x * x
来源：http://dali.guannengcc.top/Article/details/gt2vseefumf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.daxiang520.top/Article/details/gt2bgqbchfc.html

JS:   const square = x => x * x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oooiceyo.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cqqwz.cn/Article/details/gt2cmnffqvs.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.cucudq.cn/Article/details/gt2xudrjipa.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sxryk.cn/Article/details/gt2dkpigjac.html

Ruby: square = ->(x) { x * x }
来源：http://dali.gzhubu.top/Article/details/gt2mhqighym.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yonumen.top/Article/details/gt2svrtyzlk.html

[C07] 把函数作为参数传入
来源：http://dali.zhixingplan.top/Article/details/gt2sixusozc.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ybcxt.top/Article/details/gt2ndqssimj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.svipenyu.cn/Article/details/gt2ruzlfqky.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hnqzz.top/Article/details/gt2mugcvahh.html

TS:   arr.map(String)
来源：http://dali.yuanzhike.top/Article/details/gt2keoitqzz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shuidangran.top/Article/details/gt2lzunswbj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mbsjkrpt.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxuixplr.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.316326.xyz/Article/details/gt2njnvlitl.html

[C08] 闭包
来源：http://dali.guowangkeji.top/Article/details/gt2gapstilk.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.sweek.top/Article/details/gt2hjazajsj.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zycfv.cn/Article/details/gt2ltdmfmsp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yangfankeji.com/Article/details/gt2zfxrtlcf.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xuanzx.com/Article/details/gt2lhbcxcsi.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhiwuduotai.top/Article/details/gt2ndrqohmo.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.andypj.xyz/Article/details/gt2yksodiub.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yanxiufei.cn/Article/details/gt2mtxncouu.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yanxiufei.cn/Article/details/gt2xzdsjddg.html

[C09] 递归
来源：http://dali.c1oappe.top/Article/details/gt2avlicxaj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jinqigfzy.top/Article/details/gt2baqdcvrl.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.mhx1999.top/Article/details/gt2ptgvowsz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xuetiantiany.cn/Article/details/gt2fpsvzlke.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wptsralc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.iojbl.cn/Article/details/gt2jdjsxdpu.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hywenlv.cn/Article/details/gt2ooyjsteb.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cheryme.top/Article/details/gt2syzrfelt.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.gaohongyu789.top/Article/details/gt2oypqzuss.html

[C10] 变量作用域
来源：http://dali.nanxuanxn.top/Article/details/gt2dlvolzbc.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hywenlv.cn/Article/details/gt2azvrxadp.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.nanxinkj.top/Article/details/gt2hzgvpfqu.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.mhx1999.top/Article/details/gt2wsmovurt.html

TS:   同 JS
来源：http://dali.xylfe.cn/Article/details/gt2czqchqsl.html

Java: 方法内为块级作用域
来源：http://dali.havefunace.top/Article/details/gt2urzrtiyr.html

Go:   花括号块级作用域
来源：http://dali.yongpay.top/Article/details/gt2xzwotody.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ydzc1.top/Article/details/gt2ohppdbil.html

C#:   块级作用域
来源：http://dali.yueranfly.top/Article/details/gt2fgkfpzkr.html

[C11] 模块导入与导出
来源：http://dali.fzhhl.top/Article/details/gt2igljocie.html

Py:   from module import func
来源：http://dali.meibo888.top/Article/details/gt2alzadlnd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jlsjyb.cn/Article/details/gt2lbiszrbm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yuxming.cn/Article/details/gt2qozbbwcr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cqqwz.cn/Article/details/gt2yreppvle.html

Java: import java.util.List;
来源：http://dali.zhiwuduotai.top/Article/details/gt2zskxlvgh.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.dashuyun.cn/Article/details/gt2leddzsja.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cdnleiting.top/Article/details/gt2jdddhnxc.html

C#:   using System.Text;
来源：http://dali.haohaochexian.top/Article/details/gt2urkpityj.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhiwuduotai.top/Article/details/gt2vpeyomtq.html

Py:   (lambda: print("run"))()
来源：http://dali.tianlin.xyz/Article/details/gt2gpbwfcrk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.fzhhl.top/Article/details/gt2jxdchgpx.html

JS:   (() => { console.log("run"); })();
来源：http://dali.haohaochexian.top/Article/details/gt2zimsxmqg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.wangdashe.top/Article/details/gt2gkhlyghw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cashguo.top/Article/details/gt2ftsppsyd.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.pengpengdd.cyou/Article/details/gt2zwfjmbrr.html

Ruby: -> { puts "run" }.call
来源：http://dali.hongshengwenyu.top/Article/details/gt2wozllrvt.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xziqi.cn/Article/details/gt2ykrrbddk.html

[C13] 类型声明 / 类型注解
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bibgwwac.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ppjwa.cn/Article/details/gt2uzyofyan.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sysykeji.top/Article/details/gt2jhbpngep.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.guowangkeji.top/Article/details/gt2texytvfg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gt2uzakwuew.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gt2qbvzrvov.html

Go:   func add(a, b int) int
来源：http://dali.havefunace.top/Article/details/gt2tezgggga.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.daria6918.cn/Article/details/gt2eiyvuair.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.meibo888.top/Article/details/gt2xkbqkwdc.html

[C14] 泛型函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2lfjzbnoc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ymadmpic.html

PHP:  // 无泛型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bpjdeagw.html

JS:   // 无泛型
来源：http://dali.chenjidiqi.icu/Article/details/gt2ynnpwurb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ybcxt.top/Article/details/gt2sqxvbhse.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shuidangran.top/Article/details/gt2hmkbkyiy.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.c1oappe.top/Article/details/gt2kfphyzsx.html

Ruby: # 无泛型
来源：http://dali.gogol.net.cn/Article/details/gt2trxlgchw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cucudq.cn/Article/details/gt2jmglosec.html

[C15] 解构 / 展开参数
来源：http://dali.yvedp.cn/Article/details/gt2lmckuyce.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jqgfzy.top/Article/details/gt2skjepzvn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhoulong.xyz/Article/details/gt2wnwzxdug.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wyqkthsc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ukkynmjn.html

Java: // 无解构
来源：http://dali.snrcjt.cn/Article/details/gt2xzwfvxnt.html

Go:   // 无解构
来源：http://dali.nwbrower.top/Article/details/gt2kmcchwzm.html

Ruby: a, b = pair
来源：http://dali.jinqigfzy.top/Article/details/gt2fxcoxehu.html

C#:   var (a, b) = pair;
来源：http://dali.ybcxt.top/Article/details/gt2zhjxtdsj.html

[C16] 函数 / 方法重载
来源：http://dali.ppjwa.cn/Article/details/gt2xhwzjkoh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.aizwys.cn/Article/details/gt2taakcwzl.html

PHP:  // 无重载
来源：http://dali.birdmap.top/Article/details/gt2lehvfllo.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.daria6918.cn/Article/details/gt2tiqeiucs.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ydzc1.top/Article/details/gt2oiwwnyns.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jeknclzs.html

Go:   // 无重载：用不同函数名
来源：http://dali.tian-w.cn/Article/details/gt2mgepbpgr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rtsylpmr.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2elnjwqcz.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2dfoaffvz.html

D. 数组 / 列表 / 集合
来源：http://dali.xziqi.cn/Article/details/gt2rakatwuh.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2ofcuxbgw.html

[D01] 创建数组 / 列表
来源：http://dali.chenzaomai.com/Article/details/gt2ixnoiuuj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.316326.xyz/Article/details/gt2yzuhstao.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.birdmap.top/Article/details/gt2nxcaxosm.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.316326.xyz/Article/details/gt2ggenndfy.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.daria6918.cn/Article/details/gt2xqkknfts.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zmtnofso.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jqgufenzy.top/Article/details/gt2ziezrwxd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vqmwvpcx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shuidangran.top/Article/details/gt2iyvjukqc.html

[D02] 追加元素到末尾
来源：http://dali.gotoacloud.top/Article/details/gt2fbjuchrn.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.nanxuanxn.top/Article/details/gt2ikmeybxe.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gogol.net.cn/Article/details/gt2iotdxhzb.html

JS:   arr.push(4);
来源：http://dali.pycfn.com/Article/details/gt2upzyayrp.html

TS:   arr.push(4);
来源：http://dali.yonumen.top/Article/details/gt2bzglxwgh.html

Java: list.add(4);
来源：http://dali.tian-w.cn/Article/details/gt2qwlaxedv.html

Go:   arr = append(arr, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jzziojln.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jqgufenzy.top/Article/details/gt2agprbxed.html

C#:   list.Add(4);
来源：http://dali.shuidangran.top/Article/details/gt2nuxroiwz.html

[D03] 在指定位置插入元素
来源：http://dali.feifeiyinyue.top/Article/details/gt2dxqvsdar.html

Py:   arr.insert(0, 0)
来源：http://dali.daria6918.cn/Article/details/gt2sbnmyohu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinqigufen.top/Article/details/gt2cbsmmzsk.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gogol.net.cn/Article/details/gt2hkoiyrlf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xziqi.cn/Article/details/gt2vilkwlto.html

Java: list.add(0, 0);
来源：http://dali.tian-w.cn/Article/details/gt2junomawv.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.vqdsnc.cn/Article/details/gt2livwkiin.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vziawaas.html

C#:   list.Insert(0, 0);
来源：http://dali.zdqjudy.top/Article/details/gt2vypcetmk.html

[D04] 删除元素
来源：http://dali.aizwys.cn/Article/details/gt2aciccrce.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.andypj.xyz/Article/details/gt2ajrrymyf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2hojnexcs.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gotoacloud.top/Article/details/gt2mrvrveot.html

TS:   arr.splice(0, 1);
来源：http://dali.feifeiyinyue.top/Article/details/gt2rzhgrwry.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xinyue.icu/Article/details/gt2izrojcnm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xuanzx.com/Article/details/gt2hloeqopv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hfpthk.cn/Article/details/gt2dyrlyjfn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.tian-w.cn/Article/details/gt2atuoenos.html

[D05] 访问与修改元素
来源：http://dali.zhoulong.xyz/Article/details/gt2oozwacyf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj202588.top/Article/details/gt2vcfvdsmc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oorfxrrk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shuidangran.top/Article/details/gt2mklgpysn.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhiwuduotai.top/Article/details/gt2efmvwcke.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.svipenyu.cn/Article/details/gt2caxmjmqa.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.daxiang520.top/Article/details/gt2brfzppxp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xinyue.icu/Article/details/gt2dudppxqf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yj20258.top/Article/details/gt2werdgijq.html

[D06] 数组长度
来源：http://dali.daria6918.cn/Article/details/gt2jahdnwlo.html

Py:   len(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xciasrjm.html

PHP:  count($arr);
来源：http://dali.ybcxt.top/Article/details/gt2rhkmejpg.html

JS:   arr.length
来源：http://dali.fengsongda.top/Article/details/gt2hnxjjwpy.html

TS:   arr.length
来源：http://dali.0kj1m.cn/Article/details/gt2bfvathtr.html

Java: list.size();
来源：http://dali.yj202588.top/Article/details/gt2fneaxfhc.html

Go:   len(arr)
来源：http://dali.pycfn.com/Article/details/gt2ibtxpxku.html

Ruby: arr.length; arr.size
来源：http://dali.jqgfzy.top/Article/details/gt2ujdxeyiz.html

C#:   list.Count;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yqzjqrcq.html

[D07] 切片 / 取子数组
来源：http://dali.cheryme.top/Article/details/gt2pmdlcmnk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.gotoacloud.top/Article/details/gt2lgynzrhh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.wangdashe.top/Article/details/gt2fenkfdqh.html

JS:   arr.slice(1, 4);
来源：http://dali.ppjwa.cn/Article/details/gt2egxutpto.html

TS:   arr.slice(1, 4);
来源：http://dali.jqgfzy.top/Article/details/gt2adebnjtr.html

Java: list.subList(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gt2fyzdmodl.html

Go:   arr[1:4]
来源：http://dali.chenzaomai.com/Article/details/gt2nsfkmoqa.html

Ruby: arr[1, 3]
来源：http://dali.xinyue.icu/Article/details/gt2xhwhdgwv.html

C#:   list.GetRange(1, 3);
来源：http://dali.yanxiufei.cn/Article/details/gt2qelotfen.html

[D08] 合并两个数组
来源：http://dali.gogol.net.cn/Article/details/gt2nmgwmwtq.html

Py:   a + b;  a.extend(b)
来源：http://dali.chenjidiqi.icu/Article/details/gt2yfchnhgd.html

PHP:  array_merge($a, $b);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2obiuxsrz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.andypj.xyz/Article/details/gt2wjwgmcxf.html

TS:   [...a, ...b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fayguiew.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cashguo.top/Article/details/gt2qqexpgtd.html

Go:   append(a, b...)
来源：http://dali.nanxuanxn.top/Article/details/gt2puanyqdj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2gnmgoxmh.html

C#:   a.Concat(b).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gt2dzjntizv.html

[D09] 排序（升序）
来源：http://dali.yonumen.top/Article/details/gt2zuxskgaf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.redwolf501.top/Article/details/gt2bocxsrsx.html

PHP:  sort($arr);
来源：http://dali.yuanzhike.top/Article/details/gt2xvvdezeb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.birdmap.top/Article/details/gt2gkuekzje.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xuanzx.com/Article/details/gt2whrljuuh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xziqi.cn/Article/details/gt2mnzbvccm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2kiezfpxv.html

Ruby: arr.sort
来源：http://dali.yongpay.top/Article/details/gt2atjbpgti.html

C#:   list.Sort();
来源：http://dali.jianghu66.top/Article/details/gt2fjhkwxmn.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinqigfzy.top/Article/details/gt2hwghmdxl.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cqqwz.cn/Article/details/gt2uphmgmlb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tian-w.cn/Article/details/gt2qsvopfmb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hysaishi.cn/Article/details/gt2tyeatfxs.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xylfe.cn/Article/details/gt2shrkalwz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cucudq.cn/Article/details/gt2xjbdguuq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhiwuduotai.top/Article/details/gt2ctofjfqb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.havefunace.top/Article/details/gt2lsrvkiun.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kzuqvhnm.html

[D11] 反转数组
来源：http://dali.yonumen.top/Article/details/gt2rdmscaqj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cucudq.cn/Article/details/gt2pyhbqeoi.html

PHP:  array_reverse($arr);
来源：http://dali.yongpay.top/Article/details/gt2bgpedvqh.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.redwolf501.top/Article/details/gt2gpfsizpn.html

TS:   [...arr].reverse();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yokytrgn.html

Java: Collections.reverse(list);
来源：http://dali.sufxvd.cn/Article/details/gt2ekodieeg.html

Go:   slices.Reverse(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2wndjswmi.html

Ruby: arr.reverse
来源：http://dali.zhengqikj.top/Article/details/gt2prnbyryo.html

C#:   list.Reverse();
来源：http://dali.snrcjt.cn/Article/details/gt2zyxfzeci.html

[D12] 查找元素下标
来源：http://dali.ybcxt.top/Article/details/gt2mxddupvg.html

Py:   arr.index(x);  x in arr
来源：http://dali.hfpthk.cn/Article/details/gt2ikadkroi.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2oyndwetf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxinkj.top/Article/details/gt2kloenbcg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cucudq.cn/Article/details/gt2depbuquo.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.tian-w.cn/Article/details/gt2kiftyrtr.html

Go:   slices.Index(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gt2dqqatjtv.html

Ruby: arr.index(x)
来源：http://dali.0kj1m.cn/Article/details/gt2pibxosrl.html

C#:   list.IndexOf(x);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jcfvbsso.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hnqzz.top/Article/details/gt2uddcbyjk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.redwolf501.top/Article/details/gt2hpgghgbu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.wangdashe.top/Article/details/gt2dbpbkjbx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.pycfn.com/Article/details/gt2nqiuqqub.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cdnleiting.top/Article/details/gt2kxvhzeha.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ppjwa.cn/Article/details/gt2mbamfhkk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hnqzz.top/Article/details/gt2zspbypfh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ayqndbet.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yongpay.top/Article/details/gt2rxiptxpl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gotoacloud.top/Article/details/gt2kpqrfsvf.html


<!-- 参考信息 -->