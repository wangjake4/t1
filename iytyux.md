代发 wailian999

[B13] 判断是否为数字
来源：http://dali.wangshuangyany.cn/Article/details/gtjyemoahl.html

Py:   isinstance(x, (int, float))
来源：http://dali.dashuyun.cn/Article/details/gtxbtqtwjm.html

PHP:  is_numeric($x)
来源：http://dali.9152youxi.cn/Article/details/gtxqjohvjo.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gzhubu.top/Article/details/gtwijdnddb.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.redwolf501.top/Article/details/gtsgtnoing.html

Java: x instanceof Number
来源：http://dali.jiagoushi.top/Article/details/gtueuouxiy.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.svipenyu.cn/Article/details/gtxbmcztsm.html

Ruby: x.is_a?(Numeric)
来源：http://dali.fengsongda.top/Article/details/gtvtpwcamv.html

C#:   x is int or double or decimal
来源：http://dali.jyoumei.cn/Article/details/gtykhccwty.html

[B14] 判断值是否在集合内
来源：http://dali.daxiang520.top/Article/details/gtczhrbvpa.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.chenlongwang.top/Article/details/gtddwiznza.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.haohaochexian.top/Article/details/gtuuxblmmi.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yj202588.top/Article/details/gtrsvkymds.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.aibaodan.cn/Article/details/gtvlybcnlq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.redwolf501.top/Article/details/gtrmwzqbrp.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.andypj.xyz/Article/details/gtuobxefel.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ybcxt.top/Article/details/gtrqcvarwc.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yangfankeji.com/Article/details/gtldtkgwpm.html

[B15] 布尔运算与取反
来源：http://dali.bjfxy.top/Article/details/gtensklwus.html

Py:   a and b or not c
来源：http://dali.zdqjudy.top/Article/details/gtygegrfex.html

PHP:  $a && $b || !$c
来源：http://dali.jinqigfzy.top/Article/details/gtggzfcpnb.html

JS:   a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gthjfcorhn.html

TS:   a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gtvocqpcmn.html

Java: a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gtrfqmnnvr.html

Go:   a && b || !c
来源：http://dali.xylfe.cn/Article/details/gteakjfvdr.html

Ruby: a && b || !c
来源：http://dali.andypj.xyz/Article/details/gtfyaynaqt.html

C#:   a && b || !c
来源：http://dali.redwolf501.top/Article/details/gtvqoubtfo.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.haohaochexian.top/Article/details/gthtlyeifg.html

Py:   if not data: return
来源：http://dali.gzhubu.top/Article/details/gttjoszchd.html

PHP:  if (!$data) { return; }
来源：http://dali.smart0.xyz/Article/details/gtvnytjbxv.html

JS:   if (!data) return;
来源：http://dali.yueranfly.top/Article/details/gtaytsbkqz.html

TS:   if (!data) return;
来源：http://dali.ybcxt.top/Article/details/gtchfvhwmf.html

Java: if (data == null) return;
来源：http://dali.kuanghao11.cn/Article/details/gtqecgsizs.html

Go:   if data == nil { return }
来源：http://dali.kuanghao11.cn/Article/details/gtmpiebtsb.html

Ruby: return if data.nil?
来源：http://dali.feifeiyinyue.top/Article/details/gtpjctwcfe.html

C#:   if (data == null) return;
来源：http://dali.shanyushiyangtech.top/Article/details/gtwjnyvqwp.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtzmcnwqby.html

C. 函数与作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvxgwrvxz.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtbjioairx.html

[C01] 定义函数
来源：http://dali.tianlin.xyz/Article/details/gttmbhbzsy.html

Py:   def add(a, b): return a + b
来源：http://dali.sxryk.cn/Article/details/gtfdhpqpbo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hywenlv.cn/Article/details/gtbiftsvkb.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gtnrxatqsi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj202588.top/Article/details/gtazijeqdh.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gtswaevnau.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zycfv.cn/Article/details/gtvhlgfrck.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jinqigfzy.top/Article/details/gtfoyecyjm.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gtutmyhhbv.html

[C02] 默认参数
来源：http://dali.kuanghao11.cn/Article/details/gtmhovkpqk.html

Py:   def greet(name="World"): return name
来源：http://dali.xuetiantiany.cn/Article/details/gtruywslpf.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.vqdsnc.cn/Article/details/gthqrnuigo.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xziqi.cn/Article/details/gtpmxnlqwl.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtwicppldk.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.vqdsnc.cn/Article/details/gtgmqjnstr.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.dianchejie.cn/Article/details/gtuaobsbcw.html

Ruby: def greet(name = "World") = name
来源：http://dali.shuidangran.top/Article/details/gtxgzobfby.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.pengpengdd.cyou/Article/details/gtlxqbeeqv.html

[C03] 可变参数
来源：http://dali.c1oappe.top/Article/details/gtykiqwlvx.html

Py:   def total(*args): return sum(args)
来源：http://dali.jiagoushi.top/Article/details/gteaavdxut.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.c1oappe.top/Article/details/gtrmhwmcni.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shangyingyoupin.top/Article/details/gtdbnnztcv.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.bjfxy.top/Article/details/gtzkpjyckt.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yongpay.top/Article/details/gtbiqsebib.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.nwbrower.top/Article/details/gtevvdahjb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jqgfzy.top/Article/details/gtbsuujvbb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.vqdsnc.cn/Article/details/gtiadgpmhk.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hywenlv.cn/Article/details/gtvfpdbqax.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.bjfxy.top/Article/details/gtbrcoirgu.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.daria6918.cn/Article/details/gtalwiavtc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yj20258888.top/Article/details/gtdbqxsosj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.guannengcc.top/Article/details/gtgcnrbyqr.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xylfe.cn/Article/details/gtcxotfhmw.html

Go:   // 无：用配置结构体参数
来源：http://dali.chenjidiqi.icu/Article/details/gtgvjjqygo.html

Ruby: f(a: 1, b: 2)
来源：http://dali.316326.xyz/Article/details/gtskiiirig.html

C#:   f(a: 1, b: 2)
来源：http://dali.quarkkingdee.top/Article/details/gtkurnpptl.html

[C05] 返回多个值
来源：http://dali.jianghu66.top/Article/details/gtmugkejpd.html

Py:   return a, b
来源：http://dali.mhx1999.top/Article/details/gtcybkvqsm.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gttcxejrna.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yongpay.top/Article/details/gthdnweipx.html

TS:   return { a, b };
来源：http://dali.feifeiyinyue.top/Article/details/gtzrawolvo.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yj202588.top/Article/details/gttsdcjfut.html

Go:   return a, b
来源：http://dali.shzxlz.cn/Article/details/gtrvsdhurn.html

Ruby: return a, b
来源：http://dali.hnqzz.top/Article/details/gtmztqnuds.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jyoumei.cn/Article/details/gtspprmfie.html

[C06] 匿名函数 / lambda
来源：http://dali.jinyuanbaomall.cn/Article/details/gttsqplrcc.html

Py:   square = lambda x: x * x
来源：http://dali.cqqwz.cn/Article/details/gtlmfqlflb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.quarkkingdee.top/Article/details/gtaxjqbatk.html

JS:   const square = x => x * x;
来源：http://dali.zhoulong.xyz/Article/details/gtrhlwmtpr.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ydzc1.top/Article/details/gticucmzup.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hywenlv.cn/Article/details/gtpejqcyag.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.bjfxy.top/Article/details/gtpxhlvcwz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.pengpengdd.cyou/Article/details/gtadrcvqul.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhongyouzk.top/Article/details/gtuxjtpnhb.html

[C07] 把函数作为参数传入
来源：http://dali.xinyue.icu/Article/details/gtaiwxrjgn.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.pengpengdd.cyou/Article/details/gtjnxuceji.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtozhvliic.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpdqggvbf.html

TS:   arr.map(String)
来源：http://dali.mhx1999.top/Article/details/gtltufqtfq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gotoacloud.top/Article/details/gtevoaaaqp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.haohaochexian.top/Article/details/gtgnlynxvi.html

Ruby: arr.map(&:upcase)
来源：http://dali.shzxlz.cn/Article/details/gtocnmliuc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hnxiangtu.top/Article/details/gtjvzbodnp.html

[C08] 闭包
来源：http://dali.hammf.cn/Article/details/gtlkjhmrog.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ivvv.top/Article/details/gtxhrlfkli.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.nwbrower.top/Article/details/gttlpfcoyq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jyoumei.cn/Article/details/gtevwxbexh.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yvedp.cn/Article/details/gtjqmlmqlm.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ydzc1.top/Article/details/gtcltauici.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cqqwz.cn/Article/details/gtfulwcdsl.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shuidangran.top/Article/details/gtjjiilxbs.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jiagoushi.top/Article/details/gtanpjrtdq.html

[C09] 递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtpmbpxdhw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhoulong.xyz/Article/details/gtmmgssxwv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hnxiangtu.top/Article/details/gthajtrrfs.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenlongwang.top/Article/details/gtvekjeqip.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yonumen.top/Article/details/gturvlfzbw.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhiwuduotai.top/Article/details/gtbugwnrkc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zdqjudy.top/Article/details/gtveydalso.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yongpay.top/Article/details/gttojaslgn.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.snrcjt.cn/Article/details/gthitlqsfd.html

[C10] 变量作用域
来源：http://dali.quarkkingdee.top/Article/details/gtxnlzjkjd.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinqigfzy.top/Article/details/gtbutgtbdl.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jianghu66.top/Article/details/gtvzsnvivh.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpnszupjb.html

TS:   同 JS
来源：http://dali.zhongyouzk.top/Article/details/gtsqncbvsr.html

Java: 方法内为块级作用域
来源：http://dali.gzhubu.top/Article/details/gtagbazowr.html

Go:   花括号块级作用域
来源：http://dali.haohaochexian.top/Article/details/gtncjjfpoh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.guowangkeji.top/Article/details/gtgzgmgcsk.html

C#:   块级作用域
来源：http://dali.yuxming.cn/Article/details/gtyczuwatm.html

[C11] 模块导入与导出
来源：http://dali.9152youxi.cn/Article/details/gtkwyrxgob.html

Py:   from module import func
来源：http://dali.tian-w.cn/Article/details/gtprthimcd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ydzc1.top/Article/details/gtxnqhklws.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.gogol.net.cn/Article/details/gtjbrgbvhk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jqgufenzy.top/Article/details/gtatazbpmf.html

Java: import java.util.List;
来源：http://dali.yongpay.top/Article/details/gtienmdbck.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zdqjudy.top/Article/details/gtkfzjxkxp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yj20258.top/Article/details/gtkizyxxam.html

C#:   using System.Text;
来源：http://dali.yuxming.cn/Article/details/gtztmpasmp.html

[C12] 立即执行函数 IIFE
来源：http://dali.hnqzz.top/Article/details/gthfjxoxxa.html

Py:   (lambda: print("run"))()
来源：http://dali.nanxuanxn.top/Article/details/gtlrwzycye.html

PHP:  (function () { echo "run"; })();
来源：http://dali.dianchejie.cn/Article/details/gtczoiypud.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yj20258.top/Article/details/gtutaezzzx.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jinqigfzy.top/Article/details/gthsmzxhqz.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhongyouzk.top/Article/details/gtdevxedex.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.redwolf501.top/Article/details/gtfidnxcbj.html

Ruby: -> { puts "run" }.call
来源：http://dali.sysykeji.top/Article/details/gthvtkialg.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.sufxvd.cn/Article/details/gttjlkbjjr.html

[C13] 类型声明 / 类型注解
来源：http://dali.shangyingyoupin.top/Article/details/gtvypninif.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ppjwa.cn/Article/details/gtnessaohd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsqbmpgyo.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwmfdkdus.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gtcorvywmi.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzhvsirrf.html

Go:   func add(a, b int) int
来源：http://dali.zdqjudy.top/Article/details/gtxopxvgeq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.tianlin.xyz/Article/details/gtvkjnfuhd.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.redwolf501.top/Article/details/gttofxcuwq.html

[C14] 泛型函数
来源：http://dali.jyoumei.cn/Article/details/gthmzzcsoi.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.fengsongda.top/Article/details/gtrpkifxib.html

PHP:  // 无泛型
来源：http://dali.hongshengwenyu.top/Article/details/gtdhycjdar.html

JS:   // 无泛型
来源：http://dali.c1oappe.top/Article/details/gtfuzpwdyi.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yueranfly.top/Article/details/gtseyiurho.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.andypj.xyz/Article/details/gtzxknlyri.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gotoacloud.top/Article/details/gtjaegcyqx.html

Ruby: # 无泛型
来源：http://dali.havefunace.top/Article/details/gtmssossef.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jinqigufen.top/Article/details/gtuexdvctt.html

[C15] 解构 / 展开参数
来源：http://dali.daxiang520.top/Article/details/gtdfzwvhiy.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xuanzx.com/Article/details/gthfdzilxo.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yj20258.top/Article/details/gtbkmexquz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtglgvxhlr.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.bjfxy.top/Article/details/gttaklkref.html

Java: // 无解构
来源：http://dali.fzhhl.top/Article/details/gtdaxzqdme.html

Go:   // 无解构
来源：http://dali.zhoulong.xyz/Article/details/gtbirmnimi.html

Ruby: a, b = pair
来源：http://dali.jlsjyb.cn/Article/details/gtgsoxmckg.html

C#:   var (a, b) = pair;
来源：http://dali.mhx1999.top/Article/details/gtmfjbmeaq.html

[C16] 函数 / 方法重载
来源：http://dali.jlsjyb.cn/Article/details/gtfholfwth.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.chenjidiqi.icu/Article/details/gttgrzhlpt.html

PHP:  // 无重载
来源：http://dali.wangshuangyany.cn/Article/details/gtcduqvayi.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.sweek.top/Article/details/gthvwyecmp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hnxiangtu.top/Article/details/gtepfeufbd.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.nanxinkj.top/Article/details/gtshdrabus.html

Go:   // 无重载：用不同函数名
来源：http://dali.shangyingyoupin.top/Article/details/gtydvicdbw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.daria6918.cn/Article/details/gtwouiqgqo.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yuxming.cn/Article/details/gthtfttuwj.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtcenjnkjl.html

D. 数组 / 列表 / 集合
来源：http://dali.xziqi.cn/Article/details/gteflyihew.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtejqxpnuv.html

[D01] 创建数组 / 列表
来源：http://dali.cheryme.top/Article/details/gtzkalelzn.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhengqikj.top/Article/details/gtbznzbwuj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xuetiantiany.cn/Article/details/gtwtuauefm.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sxryk.cn/Article/details/gtqabdmvxx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cashguo.top/Article/details/gtptgocvvc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.sweek.top/Article/details/gtfnhltxuq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinghuilouyu.cn/Article/details/gtuowqthgg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yj202588.top/Article/details/gtgxnethjx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zycfv.cn/Article/details/gtwxjayetk.html

[D02] 追加元素到末尾
来源：http://dali.yvedp.cn/Article/details/gtvbmegbvw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shangyingyoupin.top/Article/details/gtwxgjycbp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jianghu66.top/Article/details/gtoqpcouvm.html

JS:   arr.push(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtpvztpffo.html

TS:   arr.push(4);
来源：http://dali.yj202588.top/Article/details/gtuxgsxusd.html

Java: list.add(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtcqrnydhx.html

Go:   arr = append(arr, 4)
来源：http://dali.jiagoushi.top/Article/details/gtbzjpglkp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cashguo.top/Article/details/gtcwxoqwyl.html

C#:   list.Add(4);
来源：http://dali.chenzaomai.com/Article/details/gtbhkzzggw.html

[D03] 在指定位置插入元素
来源：http://dali.daria6918.cn/Article/details/gttsqssgnr.html

Py:   arr.insert(0, 0)
来源：http://dali.jyoumei.cn/Article/details/gtsbhqjgvi.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hammf.cn/Article/details/gtmgdyyqnp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.nanxuanxn.top/Article/details/gtoauyapaj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.kuanghao11.cn/Article/details/gtrsneketm.html

Java: list.add(0, 0);
来源：http://dali.guannengcc.top/Article/details/gtpijeyxfz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zdqjudy.top/Article/details/gtnpyaucvg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zdqjudy.top/Article/details/gtzjpvjacx.html

C#:   list.Insert(0, 0);
来源：http://dali.hammf.cn/Article/details/gtqjjhgirw.html

[D04] 删除元素
来源：http://dali.yj20258888.top/Article/details/gtpqbcshue.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgnmyrwgi.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.chenzaomai.com/Article/details/gtargnrary.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.tian-w.cn/Article/details/gtcvwcowvf.html

TS:   arr.splice(0, 1);
来源：http://dali.chenjidiqi.icu/Article/details/gttzjwkwkg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shuidangran.top/Article/details/gtobpfgfvt.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jinqigfzy.top/Article/details/gtzitshdic.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.meibo888.top/Article/details/gtyipmhonw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.nwbrower.top/Article/details/gthlgrvhrb.html

[D05] 访问与修改元素
来源：http://dali.hammf.cn/Article/details/gtonwbvatc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zdqjudy.top/Article/details/gtiexoxlap.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.c1oappe.top/Article/details/gtzswrubgs.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ydzc1.top/Article/details/gtbrrdsamq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sufxvd.cn/Article/details/gtswyadpuy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.pengpengdd.cyou/Article/details/gtsbrrcqyn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gtbooircbm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cucudq.cn/Article/details/gtwmqsbzkb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yanxiufei.cn/Article/details/gtafmyxjvq.html

[D06] 数组长度
来源：http://dali.yvedp.cn/Article/details/gtnqpacfuq.html

Py:   len(arr)
来源：http://dali.hfpthk.cn/Article/details/gtzdgpftto.html

PHP:  count($arr);
来源：http://dali.svipenyu.cn/Article/details/gthxaqkyrv.html

JS:   arr.length
来源：http://dali.yvedp.cn/Article/details/gtkmapvpcs.html

TS:   arr.length
来源：http://dali.pycfn.com/Article/details/gtdkkrysuj.html

Java: list.size();
来源：http://dali.tanke756.top/Article/details/gtfqiuzsgr.html

Go:   len(arr)
来源：http://dali.snrcjt.cn/Article/details/gtjmjfihne.html

Ruby: arr.length; arr.size
来源：http://dali.zdqjudy.top/Article/details/gtyngpoptz.html

C#:   list.Count;
来源：http://dali.yanxiufei.cn/Article/details/gtrqfjwyzx.html

[D07] 切片 / 取子数组
来源：http://dali.sufxvd.cn/Article/details/gthpcoxqce.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.redwolf501.top/Article/details/gtzpxrbieg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.bjfxy.top/Article/details/gtwwnnnqjf.html

JS:   arr.slice(1, 4);
来源：http://dali.kuanghao11.cn/Article/details/gtbcozdknn.html

TS:   arr.slice(1, 4);
来源：http://dali.jqgfzy.top/Article/details/gtkjrtchpp.html

Java: list.subList(1, 4);
来源：http://dali.tianlin.xyz/Article/details/gtkuhtxcrb.html

Go:   arr[1:4]
来源：http://dali.vqdsnc.cn/Article/details/gtuiuugtfj.html

Ruby: arr[1, 3]
来源：http://dali.yangfankeji.com/Article/details/gtraotxxfu.html

C#:   list.GetRange(1, 3);
来源：http://dali.yanxiufei.cn/Article/details/gtltpzdlkd.html

[D08] 合并两个数组
来源：http://dali.jqgufenzy.top/Article/details/gtblifkinz.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhiwuduotai.top/Article/details/gtnovdgckh.html

PHP:  array_merge($a, $b);
来源：http://dali.hnqzz.top/Article/details/gtduilfvbq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sysykeji.top/Article/details/gtafpuglvz.html

TS:   [...a, ...b];
来源：http://dali.shanyushiyangtech.top/Article/details/gtolcdtzcl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.fengsongda.top/Article/details/gtgzoiipkb.html

Go:   append(a, b...)
来源：http://dali.jlsjyb.cn/Article/details/gtzfugiird.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqdhjvnnx.html

C#:   a.Concat(b).ToList()
来源：http://dali.yongpay.top/Article/details/gtlwhauqei.html

[D09] 排序（升序）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvtxeptql.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinyuanbaomall.cn/Article/details/gthkguqbqu.html

PHP:  sort($arr);
来源：http://dali.yuxming.cn/Article/details/gtdgrjhtjj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.pengpengdd.cyou/Article/details/gtertdefmf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ehwqpu.com/Article/details/gtqmqrocxe.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.feifeiyinyue.top/Article/details/gtxcqjevdx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yueranfly.top/Article/details/gtguqnlvdr.html

Ruby: arr.sort
来源：http://dali.ehwqpu.com/Article/details/gtmxdzwhqo.html

C#:   list.Sort();
来源：http://dali.yj20258.top/Article/details/gtbzzwrauj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinqigfzy.top/Article/details/gtpekjnqwh.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cucudq.cn/Article/details/gtxbtsdwtg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jiagoushi.top/Article/details/gtivuzytps.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.iojbl.cn/Article/details/gtlajxhyyn.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yvedp.cn/Article/details/gtethtrnvs.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ydzc1.top/Article/details/gtehtpfbfw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.nanxuanxn.top/Article/details/gtsqmibksp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ybcxt.top/Article/details/gtryqtyqwo.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ivvv.top/Article/details/gtaixxkdbz.html

[D11] 反转数组
来源：http://dali.yvedp.cn/Article/details/gtmcehalym.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sysykeji.top/Article/details/gttkwbabvr.html

PHP:  array_reverse($arr);
来源：http://dali.sysykeji.top/Article/details/gtsxbwxiso.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.svipenyu.cn/Article/details/gtreukebur.html

TS:   [...arr].reverse();
来源：http://dali.shzxlz.cn/Article/details/gtopjwoins.html

Java: Collections.reverse(list);
来源：http://dali.jianghu66.top/Article/details/gtqfdkmyrj.html

Go:   slices.Reverse(arr)
来源：http://dali.hnqzz.top/Article/details/gtxbrfytrg.html

Ruby: arr.reverse
来源：http://dali.jqgufenzy.top/Article/details/gttiupvsac.html

C#:   list.Reverse();
来源：http://dali.jinqigufen.top/Article/details/gtpjzmrhxf.html

[D12] 查找元素下标
来源：http://dali.zdqjudy.top/Article/details/gtklgqwnfo.html

Py:   arr.index(x);  x in arr
来源：http://dali.hnqzz.top/Article/details/gtiyosyyaj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.sufxvd.cn/Article/details/gtpqksqtqq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtrdwbfeud.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.316326.xyz/Article/details/gtnqlngxas.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.wangdashe.top/Article/details/gtjuubwmuf.html

Go:   slices.Index(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtafmnowxa.html

Ruby: arr.index(x)
来源：http://dali.snrcjt.cn/Article/details/gtxehbdntn.html

C#:   list.IndexOf(x);
来源：http://dali.kuanghao11.cn/Article/details/gtulxvposq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ehwqpu.com/Article/details/gtqxtstvvc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtipyefhwf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.iojbl.cn/Article/details/gtdtqfctqd.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zycfv.cn/Article/details/gtgzndqaww.html

TS:   arr.filter(x => x > 3)
来源：http://dali.quarkkingdee.top/Article/details/gthfrwvlwi.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtwhdkwnpv.html


<!-- 参考信息 -->