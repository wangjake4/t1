代发 wailian999

PHP:  range(0, 10, 2);
来源：http://dali.yongpay.top/Article/details/gtvperzzoe.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.daxiang520.top/Article/details/gtgocrubtd.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtjyenciij.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jqgfzy.top/Article/details/gtupisufif.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.chenlongwang.top/Article/details/gtuskyksjd.html

Ruby: (0...10).step(2).to_a
来源：http://dali.meibo888.top/Article/details/gtwjfepyna.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtecrnkziy.html

[B12] 跳出多层循环
来源：http://dali.jqgufenzy.top/Article/details/gtzhaotvzk.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xylfe.cn/Article/details/gtpbiknmyd.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.aibaodan.cn/Article/details/gtajpfkzmt.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tian-w.cn/Article/details/gtjkirwyry.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcabukbfc.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigufen.top/Article/details/gtnzkrjlwh.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.guowangkeji.top/Article/details/gtdjeaathw.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jqgufenzy.top/Article/details/gtzbgbdois.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xuetiantiany.cn/Article/details/gtyswspuma.html

[B13] 判断是否为数字
来源：http://dali.shanyushiyangtech.top/Article/details/gtkjnjybhx.html

Py:   isinstance(x, (int, float))
来源：http://dali.9152youxi.cn/Article/details/gtqttxtmwk.html

PHP:  is_numeric($x)
来源：http://dali.birdmap.top/Article/details/gtwabaxxuu.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj202588.top/Article/details/gtbtegpuoy.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.redwolf501.top/Article/details/gtglwsetph.html

Java: x instanceof Number
来源：http://dali.xziqi.cn/Article/details/gtcadpmkto.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gtftupcrsg.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shuidangran.top/Article/details/gtdoedipby.html

C#:   x is int or double or decimal
来源：http://dali.hnqzz.top/Article/details/gtisymjerd.html

[B14] 判断值是否在集合内
来源：http://dali.sweek.top/Article/details/gtidjvunja.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xuanzx.com/Article/details/gtdktayjax.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hysaishi.cn/Article/details/gtidnrakip.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.shzxlz.cn/Article/details/gtpexxvgbk.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.haohaochexian.top/Article/details/gtigwkqeej.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.haohaochexian.top/Article/details/gtjycrjzmy.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yuxming.cn/Article/details/gtvocwmdry.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.0kj1m.cn/Article/details/gtcgniuxqt.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gtfxgpfyrm.html

[B15] 布尔运算与取反
来源：http://dali.birdmap.top/Article/details/gtblwqgyiu.html

Py:   a and b or not c
来源：http://dali.zhoulong.xyz/Article/details/gtfobfopul.html

PHP:  $a && $b || !$c
来源：http://dali.316326.xyz/Article/details/gtxglmfmeu.html

JS:   a && b || !c
来源：http://dali.tianlin.xyz/Article/details/gtfxcsfxhv.html

TS:   a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gttchurysx.html

Java: a && b || !c
来源：http://dali.ivvv.top/Article/details/gtgpnuntij.html

Go:   a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gtqoibkpdk.html

Ruby: a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gtuyjzacmv.html

C#:   a && b || !c
来源：http://dali.shuidangran.top/Article/details/gtliroijpb.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.aizwys.cn/Article/details/gtftjlvlsp.html

Py:   if not data: return
来源：http://dali.bjfxy.top/Article/details/gthtwkuqdz.html

PHP:  if (!$data) { return; }
来源：http://dali.tianlin.xyz/Article/details/gtinncmmew.html

JS:   if (!data) return;
来源：http://dali.yj20258888.top/Article/details/gtjtnpqsvz.html

TS:   if (!data) return;
来源：http://dali.xinyue.icu/Article/details/gtqgobdsak.html

Java: if (data == null) return;
来源：http://dali.jlsjyb.cn/Article/details/gtspttqswy.html

Go:   if data == nil { return }
来源：http://dali.chenzaomai.com/Article/details/gtbkyseuvm.html

Ruby: return if data.nil?
来源：http://dali.gotoacloud.top/Article/details/gtnwtvddia.html

C#:   if (data == null) return;
来源：http://dali.tanke756.top/Article/details/gtuqfhlaal.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtfgyzzlbu.html

C. 函数与作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjdfdabdq.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtsyllgosm.html

[C01] 定义函数
来源：http://dali.havefunace.top/Article/details/gtwcmvztku.html

Py:   def add(a, b): return a + b
来源：http://dali.9152youxi.cn/Article/details/gtnndzncsk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gtqopitmig.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttljbkqes.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gtzgewaudq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gtbptsfqon.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.daria6918.cn/Article/details/gtutgsbsil.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfkktwjbt.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cashguo.top/Article/details/gtqtfdffrp.html

[C02] 默认参数
来源：http://dali.c1oappe.top/Article/details/gtpxgwfxtw.html

Py:   def greet(name="World"): return name
来源：http://dali.yongpay.top/Article/details/gtoribzulp.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yongpay.top/Article/details/gtkwcqrlob.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yj202588.top/Article/details/gtiuxmvrbw.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yangfankeji.com/Article/details/gtkqicjgya.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ppjwa.cn/Article/details/gtzszradde.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jinqigfzy.top/Article/details/gtjcriexon.html

Ruby: def greet(name = "World") = name
来源：http://dali.birdmap.top/Article/details/gtozbxgnqe.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.vqdsnc.cn/Article/details/gtzunmpryx.html

[C03] 可变参数
来源：http://dali.dashuyun.cn/Article/details/gtdqexclmh.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhengqikj.top/Article/details/gtlscjcoio.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtquxslyqw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ehwqpu.com/Article/details/gtsphrdkzu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cheryme.top/Article/details/gtufriwnfj.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jqgfzy.top/Article/details/gtyraxwgcm.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gtbazwxrtl.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.aibaodan.cn/Article/details/gtkirsujnt.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.nanxuanxn.top/Article/details/gtkkitnflc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hysaishi.cn/Article/details/gtunyqhhvi.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.tanke756.top/Article/details/gtkqejkoba.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.fengsongda.top/Article/details/gtqqwlqgmh.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.haohaochexian.top/Article/details/gthlcdemjt.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hywenlv.cn/Article/details/gtlasvuyqc.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ehwqpu.com/Article/details/gthoswqqys.html

Go:   // 无：用配置结构体参数
来源：http://dali.yuxming.cn/Article/details/gtwzgfzago.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shuidangran.top/Article/details/gtqtozjzet.html

C#:   f(a: 1, b: 2)
来源：http://dali.zycfv.cn/Article/details/gtvwafflha.html

[C05] 返回多个值
来源：http://dali.havefunace.top/Article/details/gtbjkqicvn.html

Py:   return a, b
来源：http://dali.cucudq.cn/Article/details/gtxhmjikak.html

PHP:  return [$a, $b];
来源：http://dali.yanxiufei.cn/Article/details/gtmpaofalw.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jqgfzy.top/Article/details/gtkxzwoyht.html

TS:   return { a, b };
来源：http://dali.yongpay.top/Article/details/gtdmmrukef.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhixingplan.top/Article/details/gtczqwdrvq.html

Go:   return a, b
来源：http://dali.cashguo.top/Article/details/gtmbkgakva.html

Ruby: return a, b
来源：http://dali.hnxiangtu.top/Article/details/gtfverwwpc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.wangdashe.top/Article/details/gtmpsjkgtr.html

[C06] 匿名函数 / lambda
来源：http://dali.gaohongyu789.top/Article/details/gtfltemohm.html

Py:   square = lambda x: x * x
来源：http://dali.bjfxy.top/Article/details/gtvjqyuapw.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.snrcjt.cn/Article/details/gtvgjwsmhq.html

JS:   const square = x => x * x;
来源：http://dali.gotoacloud.top/Article/details/gttzbymsar.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yuanzhike.top/Article/details/gtsthwimzb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gtrztmilud.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.gzhubu.top/Article/details/gtrgbpqzqo.html

Ruby: square = ->(x) { x * x }
来源：http://dali.wangshuangyany.cn/Article/details/gtrzqsompt.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.chenlongwang.top/Article/details/gtefhghumy.html

[C07] 把函数作为参数传入
来源：http://dali.guannengcc.top/Article/details/gtltvrowjp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.kuanghao11.cn/Article/details/gtjrngjupx.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yangfankeji.com/Article/details/gtkwmoqemc.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ybcxt.top/Article/details/gteowmowmr.html

TS:   arr.map(String)
来源：http://dali.daria6918.cn/Article/details/gtnttfqlow.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gotoacloud.top/Article/details/gtsdqirbdm.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.snrcjt.cn/Article/details/gtmaeyoiap.html

Ruby: arr.map(&:upcase)
来源：http://dali.ehwqpu.com/Article/details/gtvdohslwy.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhaomingkeji.xyz/Article/details/gteqcbbvby.html

[C08] 闭包
来源：http://dali.birdmap.top/Article/details/gtfsekyuvj.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gtdtkgocgp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zdqjudy.top/Article/details/gtqnheedwt.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jinqigfzy.top/Article/details/gtwgbsoruq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjhgpfypx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhixingplan.top/Article/details/gtljruekkm.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.aizwys.cn/Article/details/gtspzocnmf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ybcxt.top/Article/details/gtcmtwggda.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.c1oappe.top/Article/details/gtdfcouwto.html

[C09] 递归
来源：http://dali.zycfv.cn/Article/details/gtvqvxzoga.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.fzhhl.top/Article/details/gtmequxsra.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xziqi.cn/Article/details/gtxlgrmpgf.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shanyushiyangtech.top/Article/details/gtddvkiumt.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gaohongyu789.top/Article/details/gtpewidatw.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gaohongyu789.top/Article/details/gtqberpjff.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.iojbl.cn/Article/details/gtbmztcags.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.snrcjt.cn/Article/details/gtfzameohs.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yvedp.cn/Article/details/gtseplmdkt.html

[C10] 变量作用域
来源：http://dali.chenzaomai.com/Article/details/gtqulefdlk.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.andypj.xyz/Article/details/gtxfkqxopw.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.aizwys.cn/Article/details/gtzngcjffi.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yuxming.cn/Article/details/gtudduaxkn.html

TS:   同 JS
来源：http://dali.yonumen.top/Article/details/gtvnccoyeb.html

Java: 方法内为块级作用域
来源：http://dali.zhengqikj.top/Article/details/gttgswgckj.html

Go:   花括号块级作用域
来源：http://dali.daxiang520.top/Article/details/gtnjmciwet.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xuetiantiany.cn/Article/details/gtttplgkcu.html

C#:   块级作用域
来源：http://dali.yvedp.cn/Article/details/gtmfydmgnd.html

[C11] 模块导入与导出
来源：http://dali.mhx1999.top/Article/details/gtonbveplg.html

Py:   from module import func
来源：http://dali.vqdsnc.cn/Article/details/gtqfxmkxyp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.vqdsnc.cn/Article/details/gtjtbbzrwg.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jqgfzy.top/Article/details/gtpoyqdiif.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.fengsongda.top/Article/details/gtbulkphwg.html

Java: import java.util.List;
来源：http://dali.shzxlz.cn/Article/details/gtjrtoeoru.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.316326.xyz/Article/details/gtylzjqvxo.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.316326.xyz/Article/details/gtpxthvkav.html

C#:   using System.Text;
来源：http://dali.jlsjyb.cn/Article/details/gtoludclvt.html

[C12] 立即执行函数 IIFE
来源：http://dali.nanxuanxn.top/Article/details/gtpghzljje.html

Py:   (lambda: print("run"))()
来源：http://dali.aibaodan.cn/Article/details/gtejhyxxyj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hywenlv.cn/Article/details/gtmewmevwu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yj20258888.top/Article/details/gtqmjwontr.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtairnsyqc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.nwbrower.top/Article/details/gtpamcawzn.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.svipenyu.cn/Article/details/gtwrlhmoad.html

Ruby: -> { puts "run" }.call
来源：http://dali.xuetiantiany.cn/Article/details/gtoqedaupl.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hammf.cn/Article/details/gtewhwbywv.html

[C13] 类型声明 / 类型注解
来源：http://dali.jinghuilouyu.cn/Article/details/gtycgxcwaa.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.gzhubu.top/Article/details/gtlmoxpgrw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgxwgnejv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ivvv.top/Article/details/gtnstiobjh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtdgokhves.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtojhbxpsz.html

Go:   func add(a, b int) int
来源：http://dali.mhx1999.top/Article/details/gtlnicypph.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gaohongyu789.top/Article/details/gthfagbjoe.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hysaishi.cn/Article/details/gtmrvzyjdq.html

[C14] 泛型函数
来源：http://dali.haohaochexian.top/Article/details/gtvlbweadp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.fengsongda.top/Article/details/gtmgqghkwn.html

PHP:  // 无泛型
来源：http://dali.yvedp.cn/Article/details/gtpdupiujs.html

JS:   // 无泛型
来源：http://dali.ppjwa.cn/Article/details/gttmwussjv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xylfe.cn/Article/details/gtchyxyocy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jqgufenzy.top/Article/details/gtkxeyslpi.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiuajnlhv.html

Ruby: # 无泛型
来源：http://dali.vqdsnc.cn/Article/details/gtjjxyztme.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ybcxt.top/Article/details/gtyfhnghju.html

[C15] 解构 / 展开参数
来源：http://dali.shangyingyoupin.top/Article/details/gtamfneyzw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gzhubu.top/Article/details/gtailgyios.html

PHP:  [$a, $b] = $pair;
来源：http://dali.tian-w.cn/Article/details/gtpaaxkwez.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.svipenyu.cn/Article/details/gtdmtzjdex.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yanxiufei.cn/Article/details/gtmwldrmin.html

Java: // 无解构
来源：http://dali.birdmap.top/Article/details/gttdpvlmes.html

Go:   // 无解构
来源：http://dali.vqdsnc.cn/Article/details/gtdakejdza.html

Ruby: a, b = pair
来源：http://dali.zycfv.cn/Article/details/gtpqchonsu.html

C#:   var (a, b) = pair;
来源：http://dali.ybcxt.top/Article/details/gtpnhdylwl.html

[C16] 函数 / 方法重载
来源：http://dali.andypj.xyz/Article/details/gtifrdkbnp.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.snrcjt.cn/Article/details/gtapyhmfcb.html

PHP:  // 无重载
来源：http://dali.cheryme.top/Article/details/gtqrahlwob.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinghuilouyu.cn/Article/details/gtnflmgqfq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jqgufenzy.top/Article/details/gtsnulgtpf.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.chenlongwang.top/Article/details/gtmkgbqahf.html

Go:   // 无重载：用不同函数名
来源：http://dali.meibo888.top/Article/details/gtprvavafy.html

Ruby: # 无重载：靠动态参数
来源：http://dali.mhx1999.top/Article/details/gtmgflesjp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xziqi.cn/Article/details/gtauznhdsh.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtogxecxmd.html

D. 数组 / 列表 / 集合
来源：http://dali.jinghuilouyu.cn/Article/details/gtczisbxky.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtlftbufan.html

[D01] 创建数组 / 列表
来源：http://dali.iojbl.cn/Article/details/gtueiadmbq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwvuhyxxx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.quarkkingdee.top/Article/details/gtygrpjwcq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.daxiang520.top/Article/details/gtsacsllki.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shuidangran.top/Article/details/gtqjowkaxo.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shuidangran.top/Article/details/gtnpkqbciy.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.nanxuanxn.top/Article/details/gtzbvuaclf.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cashguo.top/Article/details/gtkhdpzpzu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sweek.top/Article/details/gtffdlinro.html

[D02] 追加元素到末尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuznmdkax.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhongyouzk.top/Article/details/gtutsbpudg.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.pycfn.com/Article/details/gtaccegerc.html

JS:   arr.push(4);
来源：http://dali.gaohongyu789.top/Article/details/gtywkcktxp.html

TS:   arr.push(4);
来源：http://dali.sufxvd.cn/Article/details/gtcdwolwni.html

Java: list.add(4);
来源：http://dali.tian-w.cn/Article/details/gtwarqbebe.html

Go:   arr = append(arr, 4)
来源：http://dali.ppjwa.cn/Article/details/gthleenwmd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.fzhhl.top/Article/details/gtqmuiainz.html

C#:   list.Add(4);
来源：http://dali.yangfankeji.com/Article/details/gtrqepkvpg.html

[D03] 在指定位置插入元素
来源：http://dali.meibo888.top/Article/details/gtlfrocbnc.html

Py:   arr.insert(0, 0)
来源：http://dali.guowangkeji.top/Article/details/gtchlmimng.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.aibaodan.cn/Article/details/gtqagdbxtq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cheryme.top/Article/details/gtftdvcjpy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xinyue.icu/Article/details/gtpmnhqquc.html

Java: list.add(0, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlqowktfa.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jyoumei.cn/Article/details/gtfknangna.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.316326.xyz/Article/details/gtuctszbtt.html

C#:   list.Insert(0, 0);
来源：http://dali.guowangkeji.top/Article/details/gtwhdzpnis.html

[D04] 删除元素
来源：http://dali.yvedp.cn/Article/details/gtoncgugmt.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwkquywyv.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sxryk.cn/Article/details/gtqphjjgmk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ppjwa.cn/Article/details/gtjecyinlz.html

TS:   arr.splice(0, 1);
来源：http://dali.jiagoushi.top/Article/details/gtigbaokxc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtqthnfeyc.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.birdmap.top/Article/details/gtxwkljmmm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cucudq.cn/Article/details/gtepyzucvc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yvedp.cn/Article/details/gthxetviug.html

[D05] 访问与修改元素
来源：http://dali.xylfe.cn/Article/details/gtptyuldiu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aibaodan.cn/Article/details/gtnmuwwuwo.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yueranfly.top/Article/details/gtnncrttrw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.gotoacloud.top/Article/details/gtebulakwi.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrstqexkf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.andypj.xyz/Article/details/gtskeizgdl.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cqqwz.cn/Article/details/gtdiqbzknj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hywenlv.cn/Article/details/gtqxvgcqee.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jianghu66.top/Article/details/gtogxeomvc.html

[D06] 数组长度
来源：http://dali.nwbrower.top/Article/details/gtnjxmkcmh.html

Py:   len(arr)
来源：http://dali.ppjwa.cn/Article/details/gtibdkagvp.html

PHP:  count($arr);
来源：http://dali.cdnleiting.top/Article/details/gtrkqbankx.html

JS:   arr.length
来源：http://dali.ivvv.top/Article/details/gtctlvdjri.html

TS:   arr.length
来源：http://dali.jinqigufen.top/Article/details/gtqdjgtraq.html

Java: list.size();
来源：http://dali.shuidangran.top/Article/details/gtbiqkqfod.html

Go:   len(arr)
来源：http://dali.hfpthk.cn/Article/details/gtbzyymxkw.html

Ruby: arr.length; arr.size
来源：http://dali.zdqjudy.top/Article/details/gtgonezikc.html

C#:   list.Count;
来源：http://dali.daxiang520.top/Article/details/gttiztifcq.html

[D07] 切片 / 取子数组
来源：http://dali.shanyushiyangtech.top/Article/details/gtwdwonexg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.havefunace.top/Article/details/gtvujgbvzu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.tianlin.xyz/Article/details/gtjtpcltgd.html

JS:   arr.slice(1, 4);
来源：http://dali.aibaodan.cn/Article/details/gtoscwdjna.html

TS:   arr.slice(1, 4);
来源：http://dali.yj20258888.top/Article/details/gtzpbzvfih.html

Java: list.subList(1, 4);
来源：http://dali.pengpengdd.cyou/Article/details/gtcdorjsgi.html

Go:   arr[1:4]
来源：http://dali.snrcjt.cn/Article/details/gtqphmvxla.html

Ruby: arr[1, 3]
来源：http://dali.hongshengwenyu.top/Article/details/gtioxujrwt.html

C#:   list.GetRange(1, 3);
来源：http://dali.hnqzz.top/Article/details/gtzhcxuxts.html

[D08] 合并两个数组
来源：http://dali.birdmap.top/Article/details/gtulwtcyle.html

Py:   a + b;  a.extend(b)
来源：http://dali.yueranfly.top/Article/details/gtvgfxwpka.html

PHP:  array_merge($a, $b);
来源：http://dali.shzxlz.cn/Article/details/gtizhacyli.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hysaishi.cn/Article/details/gtjzgmkgxn.html

TS:   [...a, ...b];
来源：http://dali.redwolf501.top/Article/details/gtcqqohqai.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.nanxuanxn.top/Article/details/gtcnepjfky.html

Go:   append(a, b...)
来源：http://dali.sufxvd.cn/Article/details/gtandnpben.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shangyingyoupin.top/Article/details/gtplqojnxn.html

C#:   a.Concat(b).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtwjiucfwu.html

[D09] 排序（升序）
来源：http://dali.svipenyu.cn/Article/details/gtjnanptrb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.meibo888.top/Article/details/gtobummdkd.html

PHP:  sort($arr);
来源：http://dali.shzxlz.cn/Article/details/gtiertgmlo.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.sxryk.cn/Article/details/gtmejyyzcl.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.mhx1999.top/Article/details/gtbqvcteva.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.andypj.xyz/Article/details/gtdejznofz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtakppfehn.html

Ruby: arr.sort
来源：http://dali.jinghuilouyu.cn/Article/details/gtprezvcba.html

C#:   list.Sort();
来源：http://dali.tian-w.cn/Article/details/gthjrabjia.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ppjwa.cn/Article/details/gtmmpverlh.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.dashuyun.cn/Article/details/gtckchcuae.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hammf.cn/Article/details/gtyaaowtof.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tianlin.xyz/Article/details/gtivfxpgsy.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shangyingyoupin.top/Article/details/gtbpkonnmt.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.havefunace.top/Article/details/gtjusjulna.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xinyue.icu/Article/details/gtosrshxsb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hammf.cn/Article/details/gtfcljkwep.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.daxiang520.top/Article/details/gtvtecqujf.html

[D11] 反转数组
来源：http://dali.guannengcc.top/Article/details/gtkuctktjf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.316326.xyz/Article/details/gtgrldvohe.html

PHP:  array_reverse($arr);
来源：http://dali.pycfn.com/Article/details/gtmbtlsfiy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.aizwys.cn/Article/details/gtoghnhhpc.html

TS:   [...arr].reverse();
来源：http://dali.cheryme.top/Article/details/gtclcslsju.html

Java: Collections.reverse(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbwkqdzhk.html

Go:   slices.Reverse(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsbhtobyo.html

Ruby: arr.reverse
来源：http://dali.sufxvd.cn/Article/details/gtlpbhsqtf.html


<!-- 参考信息 -->