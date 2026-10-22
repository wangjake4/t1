代发 wailian999

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xziqi.cn/Article/details/gtosqgieqr.html

Java: x instanceof Number
来源：http://dali.meibo888.top/Article/details/gtbcwvaimr.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hywenlv.cn/Article/details/gtearqrswk.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yonumen.top/Article/details/gthkrbrdxo.html

C#:   x is int or double or decimal
来源：http://dali.gogol.net.cn/Article/details/gtsmguvngt.html

[B14] 判断值是否在集合内
来源：http://dali.vqdsnc.cn/Article/details/gtrdxvisqe.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.bjfxy.top/Article/details/gtnajajria.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.wangdashe.top/Article/details/gtyijqsdkn.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gtrulcamzc.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gtqdppbtxr.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ehwqpu.com/Article/details/gtnebkurls.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ydzc1.top/Article/details/gtcyoysrsi.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.gotoacloud.top/Article/details/gtohwxhnrs.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.meibo888.top/Article/details/gtnswucxir.html

[B15] 布尔运算与取反
来源：http://dali.yongpay.top/Article/details/gtujxrzwty.html

Py:   a and b or not c
来源：http://dali.sxryk.cn/Article/details/gtlgtesjlj.html

PHP:  $a && $b || !$c
来源：http://dali.xylfe.cn/Article/details/gtbuxygdei.html

JS:   a && b || !c
来源：http://dali.jqgufenzy.top/Article/details/gtuktgcjoa.html

TS:   a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gtqqtxravd.html

Java: a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gtngptmppr.html

Go:   a && b || !c
来源：http://dali.shuidangran.top/Article/details/gttalxpbai.html

Ruby: a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gtzabdjzob.html

C#:   a && b || !c
来源：http://dali.xinyue.icu/Article/details/gtqsmpyldc.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhengqikj.top/Article/details/gtcvsnjcgx.html

Py:   if not data: return
来源：http://dali.gogol.net.cn/Article/details/gtgoqnwwup.html

PHP:  if (!$data) { return; }
来源：http://dali.zhixingplan.top/Article/details/gthvzsluzk.html

JS:   if (!data) return;
来源：http://dali.hnxiangtu.top/Article/details/gtkkbdmimq.html

TS:   if (!data) return;
来源：http://dali.jyoumei.cn/Article/details/gtwqxodvdy.html

Java: if (data == null) return;
来源：http://dali.kuanghao11.cn/Article/details/gtujluvaih.html

Go:   if data == nil { return }
来源：http://dali.andypj.xyz/Article/details/gtofxwftjx.html

Ruby: return if data.nil?
来源：http://dali.redwolf501.top/Article/details/gtfvrzwgfk.html

C#:   if (data == null) return;
来源：http://dali.sysykeji.top/Article/details/gtgqmkaomb.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtovlbjeec.html

C. 函数与作用域
来源：http://dali.zhengqikj.top/Article/details/gthjcjcpic.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtxsorligf.html

[C01] 定义函数
来源：http://dali.hywenlv.cn/Article/details/gtlmifjfhm.html

Py:   def add(a, b): return a + b
来源：http://dali.shuidangran.top/Article/details/gthafojvdo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zdqjudy.top/Article/details/gtwrkgrzag.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gtwiyasuyn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gtdeojynmm.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gtaecuucrm.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.kuanghao11.cn/Article/details/gteccuftaw.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhiwuduotai.top/Article/details/gtdfkslhhj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gtwkrtdhiu.html

[C02] 默认参数
来源：http://dali.zhiwuduotai.top/Article/details/gtqaypwvya.html

Py:   def greet(name="World"): return name
来源：http://dali.zhoulong.xyz/Article/details/gtoleabenc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.tian-w.cn/Article/details/gtwaehvyot.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ydzc1.top/Article/details/gtjnxfujqr.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gtqyksamcp.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cashguo.top/Article/details/gtrhigdkad.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jinqigufen.top/Article/details/gtpbmkvofb.html

Ruby: def greet(name = "World") = name
来源：http://dali.wangdashe.top/Article/details/gtsoitpkhx.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xuanzx.com/Article/details/gtoqswwoks.html

[C03] 可变参数
来源：http://dali.yuxming.cn/Article/details/gtmpszwulc.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhoulong.xyz/Article/details/gtlajcgesq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.cqqwz.cn/Article/details/gtkxxbnlia.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ppjwa.cn/Article/details/gttamfgblt.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tian-w.cn/Article/details/gtwhhzilxi.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yueranfly.top/Article/details/gtsiynlqzj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.mhx1999.top/Article/details/gtlbaplnyl.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.chenlongwang.top/Article/details/gtfquqklgs.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jianghu66.top/Article/details/gtijldpxwn.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jyoumei.cn/Article/details/gtzgmdgubg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhengqikj.top/Article/details/gtfphmscjr.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.gzhubu.top/Article/details/gteyvzkjwo.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.iojbl.cn/Article/details/gtsjqvgafi.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.quarkkingdee.top/Article/details/gtploghqef.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jqgfzy.top/Article/details/gtqjiphcvf.html

Go:   // 无：用配置结构体参数
来源：http://dali.zdqjudy.top/Article/details/gthhdlnhfh.html

Ruby: f(a: 1, b: 2)
来源：http://dali.daria6918.cn/Article/details/gtduntcweq.html

C#:   f(a: 1, b: 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthcaqgxpj.html

[C05] 返回多个值
来源：http://dali.cucudq.cn/Article/details/gtmhgbubcm.html

Py:   return a, b
来源：http://dali.cdnleiting.top/Article/details/gtklybvfqq.html

PHP:  return [$a, $b];
来源：http://dali.ivvv.top/Article/details/gtkrvbbzyw.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.chenzaomai.com/Article/details/gtxwmyeaxu.html

TS:   return { a, b };
来源：http://dali.vqdsnc.cn/Article/details/gtpwtkdpgk.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shanyushiyangtech.top/Article/details/gtqvvgtsdo.html

Go:   return a, b
来源：http://dali.316326.xyz/Article/details/gtnkuuyaws.html

Ruby: return a, b
来源：http://dali.fzhhl.top/Article/details/gtnfqrjmzx.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shuidangran.top/Article/details/gtudvyppwl.html

[C06] 匿名函数 / lambda
来源：http://dali.wangdashe.top/Article/details/gtgvvrvign.html

Py:   square = lambda x: x * x
来源：http://dali.yj20258.top/Article/details/gtpiiwuwlt.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ydzc1.top/Article/details/gtaxprocca.html

JS:   const square = x => x * x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqnrrefyz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjmfedjjc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yj20258888.top/Article/details/gtmtpxecql.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.chenjidiqi.icu/Article/details/gtrxtyifro.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yueranfly.top/Article/details/gtpaexgmbs.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shanyushiyangtech.top/Article/details/gtowawnxwr.html

[C07] 把函数作为参数传入
来源：http://dali.hnqzz.top/Article/details/gtaeknoukk.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yangfankeji.com/Article/details/gtwcdtkydj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.nanxuanxn.top/Article/details/gtyukogrbn.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.chenlongwang.top/Article/details/gtvokfjocx.html

TS:   arr.map(String)
来源：http://dali.sxryk.cn/Article/details/gtakckcywt.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shuidangran.top/Article/details/gtbiatfhxi.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shanyushiyangtech.top/Article/details/gtzqsmmcxs.html

Ruby: arr.map(&:upcase)
来源：http://dali.yongpay.top/Article/details/gtbvobyzkg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhiwuduotai.top/Article/details/gtxsyuotsd.html

[C08] 闭包
来源：http://dali.kuanghao11.cn/Article/details/gtlxsrfpzu.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.tianlin.xyz/Article/details/gtmudixstx.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jqgfzy.top/Article/details/gtcuvxnfco.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ybcxt.top/Article/details/gtzaadtojn.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ppjwa.cn/Article/details/gtesiexamw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.andypj.xyz/Article/details/gthjpigjqt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.ydzc1.top/Article/details/gttgvqxdmp.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.bjfxy.top/Article/details/gtrtcurlls.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cashguo.top/Article/details/gtjbooeinz.html

[C09] 递归
来源：http://dali.yuxming.cn/Article/details/gtbjweeevf.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.gzhubu.top/Article/details/gtxzmtxifl.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cqqwz.cn/Article/details/gtthszttea.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gogol.net.cn/Article/details/gtdihhimxv.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gogol.net.cn/Article/details/gtsxgjanpe.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.nwbrower.top/Article/details/gtvgloukjm.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.tianlin.xyz/Article/details/gtyhhsuhtv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hammf.cn/Article/details/gtjmsxqumz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zdqjudy.top/Article/details/gtlymgjaxd.html

[C10] 变量作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gthyqxypvl.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yuanzhike.top/Article/details/gtixxcpizu.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.gogol.net.cn/Article/details/gtxomrzuol.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jyoumei.cn/Article/details/gtglcgvnvi.html

TS:   同 JS
来源：http://dali.daxiang520.top/Article/details/gtjhfvlnqp.html

Java: 方法内为块级作用域
来源：http://dali.fzhhl.top/Article/details/gtgbqrfxjj.html

Go:   花括号块级作用域
来源：http://dali.jianghu66.top/Article/details/gtvrcrbmzi.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhixingplan.top/Article/details/gtkkmqadel.html

C#:   块级作用域
来源：http://dali.zhongyouzk.top/Article/details/gtohfcqnbz.html

[C11] 模块导入与导出
来源：http://dali.nanxinkj.top/Article/details/gtdbwduxen.html

Py:   from module import func
来源：http://dali.cucudq.cn/Article/details/gtfwfsbnaw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jqgufenzy.top/Article/details/gtewnzxlcj.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yuxming.cn/Article/details/gtxmvjrxcq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.chenlongwang.top/Article/details/gtqbxbvmcs.html

Java: import java.util.List;
来源：http://dali.shanyushiyangtech.top/Article/details/gtkrfafrkj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.gzhubu.top/Article/details/gtrfwklehy.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shanyushiyangtech.top/Article/details/gtbmpjqfyq.html

C#:   using System.Text;
来源：http://dali.bjfxy.top/Article/details/gtzqhtgnku.html

[C12] 立即执行函数 IIFE
来源：http://dali.jqgfzy.top/Article/details/gtvcmajivf.html

Py:   (lambda: print("run"))()
来源：http://dali.chenzaomai.com/Article/details/gtzfkomqau.html

PHP:  (function () { echo "run"; })();
来源：http://dali.svipenyu.cn/Article/details/gtiafjdemx.html

JS:   (() => { console.log("run"); })();
来源：http://dali.andypj.xyz/Article/details/gtyxxqypfx.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ehwqpu.com/Article/details/gtejecwlyx.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gzhubu.top/Article/details/gtxtflerzm.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hnqzz.top/Article/details/gtayldlshy.html

Ruby: -> { puts "run" }.call
来源：http://dali.hongshengwenyu.top/Article/details/gtczvjywwd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.pycfn.com/Article/details/gtaoxibohp.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gtydvojkdm.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sweek.top/Article/details/gtssuyikkl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gtudsfdhmv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hysaishi.cn/Article/details/gtkksqsiec.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj202588.top/Article/details/gthuruqtfa.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gtvsjsbyni.html

Go:   func add(a, b int) int
来源：http://dali.sufxvd.cn/Article/details/gtpadhlaln.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ppjwa.cn/Article/details/gtzzevapwq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinghuilouyu.cn/Article/details/gtmqbgaboy.html

[C14] 泛型函数
来源：http://dali.bjfxy.top/Article/details/gtcyzxdfmv.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.pengpengdd.cyou/Article/details/gtpynbfljk.html

PHP:  // 无泛型
来源：http://dali.hnqzz.top/Article/details/gtxujbtseh.html

JS:   // 无泛型
来源：http://dali.hongshengwenyu.top/Article/details/gtifplowrk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cheryme.top/Article/details/gtazymxspc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.birdmap.top/Article/details/gtojchidjy.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zdqjudy.top/Article/details/gtdwiqpduj.html

Ruby: # 无泛型
来源：http://dali.hfpthk.cn/Article/details/gtnuexceau.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jyoumei.cn/Article/details/gtbtsfuiwc.html

[C15] 解构 / 展开参数
来源：http://dali.jinqigfzy.top/Article/details/gtbtcdovix.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shuidangran.top/Article/details/gtbjwkiqkv.html

PHP:  [$a, $b] = $pair;
来源：http://dali.redwolf501.top/Article/details/gtutyhiunw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.mhx1999.top/Article/details/gtmihezhoq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zdqjudy.top/Article/details/gtkyagakwi.html

Java: // 无解构
来源：http://dali.xuanzx.com/Article/details/gtkwkezkzi.html

Go:   // 无解构
来源：http://dali.jqgfzy.top/Article/details/gtziiidlta.html

Ruby: a, b = pair
来源：http://dali.wangshuangyany.cn/Article/details/gtxudctued.html

C#:   var (a, b) = pair;
来源：http://dali.andypj.xyz/Article/details/gtcbggeugq.html

[C16] 函数 / 方法重载
来源：http://dali.vqdsnc.cn/Article/details/gtaroziwty.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.pengpengdd.cyou/Article/details/gtagouieuq.html

PHP:  // 无重载
来源：http://dali.yj202588.top/Article/details/gtzokhrhui.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cheryme.top/Article/details/gtgbiztpwm.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.havefunace.top/Article/details/gtahzvepkv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.c1oappe.top/Article/details/gtdwzkupnm.html

Go:   // 无重载：用不同函数名
来源：http://dali.andypj.xyz/Article/details/gtnxbpeddo.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtshxnajxx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jyoumei.cn/Article/details/gtydthypzl.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtensdhzun.html

D. 数组 / 列表 / 集合
来源：http://dali.xziqi.cn/Article/details/gtpftqtuww.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtuesylfki.html

[D01] 创建数组 / 列表
来源：http://dali.jqgfzy.top/Article/details/gtcxlydgey.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.daria6918.cn/Article/details/gtwyxcktat.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhiwuduotai.top/Article/details/gtkvizbzfw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.andypj.xyz/Article/details/gtaedkzwfa.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.sxryk.cn/Article/details/gtufbxesno.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.fzhhl.top/Article/details/gttgrqgopj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinghuilouyu.cn/Article/details/gtzjlilehd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.birdmap.top/Article/details/gtctgbzvxa.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.kuanghao11.cn/Article/details/gtbzeozesu.html

[D02] 追加元素到末尾
来源：http://dali.zhixingplan.top/Article/details/gtrdcninmd.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinghuilouyu.cn/Article/details/gtnkopvhgl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jlsjyb.cn/Article/details/gtjshpuqjt.html

JS:   arr.push(4);
来源：http://dali.mhx1999.top/Article/details/gtblyyqbmo.html

TS:   arr.push(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoxsptkdi.html

Java: list.add(4);
来源：http://dali.yueranfly.top/Article/details/gtrpvflesx.html

Go:   arr = append(arr, 4)
来源：http://dali.gogol.net.cn/Article/details/gtuzoushft.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.fengsongda.top/Article/details/gtpequxtrk.html

C#:   list.Add(4);
来源：http://dali.pengpengdd.cyou/Article/details/gtmzjjrgmw.html

[D03] 在指定位置插入元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtvwpdwhit.html

Py:   arr.insert(0, 0)
来源：http://dali.zhengqikj.top/Article/details/gtqrwgptll.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.kuanghao11.cn/Article/details/gtpuihkmbj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shanyushiyangkeji.top/Article/details/gttsnyvmrx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ydzc1.top/Article/details/gtostgjprk.html

Java: list.add(0, 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtdxtjqgiu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.vqdsnc.cn/Article/details/gtgfcdacwt.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ppjwa.cn/Article/details/gtlityfrpr.html

C#:   list.Insert(0, 0);
来源：http://dali.sxryk.cn/Article/details/gtikhqlhiq.html

[D04] 删除元素
来源：http://dali.cucudq.cn/Article/details/gtljyrfavk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.iojbl.cn/Article/details/gtxqhnjoxt.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.gogol.net.cn/Article/details/gtrjibcnbk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhengqikj.top/Article/details/gthjmcuksf.html

TS:   arr.splice(0, 1);
来源：http://dali.hywenlv.cn/Article/details/gtslmayfuu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yj202588.top/Article/details/gttvzczqmp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.pycfn.com/Article/details/gtutdephny.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cdnleiting.top/Article/details/gtknpkzwkq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jiagoushi.top/Article/details/gtjkmvtrlm.html

[D05] 访问与修改元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtulsrotfi.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhongyouzk.top/Article/details/gtnycvruuf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.quarkkingdee.top/Article/details/gtatpwetjg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.9152youxi.cn/Article/details/gtlvjkuxxh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.meibo888.top/Article/details/gtezwketht.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.chenjidiqi.icu/Article/details/gtuweyumuq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shuidangran.top/Article/details/gtkpqfojxj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj202588.top/Article/details/gtserkewad.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zycfv.cn/Article/details/gtztiyplax.html

[D06] 数组长度
来源：http://dali.nanxinkj.top/Article/details/gtlxumyohu.html

Py:   len(arr)
来源：http://dali.sufxvd.cn/Article/details/gtjklntqtv.html

PHP:  count($arr);
来源：http://dali.daxiang520.top/Article/details/gtfvqzokvr.html

JS:   arr.length
来源：http://dali.cqqwz.cn/Article/details/gtdzsbvzch.html

TS:   arr.length
来源：http://dali.zhengqikj.top/Article/details/gtgyjzsxoy.html

Java: list.size();
来源：http://dali.dianchejie.cn/Article/details/gtmdmzqeti.html

Go:   len(arr)
来源：http://dali.hysaishi.cn/Article/details/gtuouxqtmb.html

Ruby: arr.length; arr.size
来源：http://dali.pengpengdd.cyou/Article/details/gtkphvwqco.html

C#:   list.Count;
来源：http://dali.zycfv.cn/Article/details/gtpjvycgdj.html

[D07] 切片 / 取子数组
来源：http://dali.zhixingplan.top/Article/details/gtmwlwakei.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jianghu66.top/Article/details/gtknvbnfkm.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yonumen.top/Article/details/gtfojwkhcm.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gtuttdvxwv.html

TS:   arr.slice(1, 4);
来源：http://dali.meibo888.top/Article/details/gtkcyhbczn.html

Java: list.subList(1, 4);
来源：http://dali.pengpengdd.cyou/Article/details/gtggzuzset.html

Go:   arr[1:4]
来源：http://dali.shangyingyoupin.top/Article/details/gtsdyqlnnz.html

Ruby: arr[1, 3]
来源：http://dali.mhx1999.top/Article/details/gtpihysueq.html

C#:   list.GetRange(1, 3);
来源：http://dali.yj202588.top/Article/details/gtvtqgevlm.html

[D08] 合并两个数组
来源：http://dali.nanxuanxn.top/Article/details/gtgxjxgzea.html

Py:   a + b;  a.extend(b)
来源：http://dali.shzxlz.cn/Article/details/gtcawsamtk.html

PHP:  array_merge($a, $b);
来源：http://dali.smart0.xyz/Article/details/gtjeofihuj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sysykeji.top/Article/details/gtlmkbgqga.html

TS:   [...a, ...b];
来源：http://dali.shzxlz.cn/Article/details/gtmlwyqfts.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cdnleiting.top/Article/details/gtlpdbqskt.html

Go:   append(a, b...)
来源：http://dali.daria6918.cn/Article/details/gtqmnhewfp.html

Ruby: a + b;  a.concat(b)
来源：http://dali.quarkkingdee.top/Article/details/gtlvtkwuox.html

C#:   a.Concat(b).ToList()
来源：http://dali.zdqjudy.top/Article/details/gtxyxjfvwc.html

[D09] 排序（升序）
来源：http://dali.jqgfzy.top/Article/details/gtygqaumpw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258.top/Article/details/gthxqqfdfr.html

PHP:  sort($arr);
来源：http://dali.jqgfzy.top/Article/details/gtbmvpxbii.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhoulong.xyz/Article/details/gtneaidaxm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cashguo.top/Article/details/gtsoxxeiea.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.haohaochexian.top/Article/details/gtqfymzebx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zdqjudy.top/Article/details/gtfoxxmhaa.html

Ruby: arr.sort
来源：http://dali.haohaochexian.top/Article/details/gtjkqgfhzl.html

C#:   list.Sort();
来源：http://dali.ehwqpu.com/Article/details/gtpqxohlbt.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.dianchejie.cn/Article/details/gtsocoavfe.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yangfankeji.com/Article/details/gtyefgtxjp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.birdmap.top/Article/details/gtlzekfces.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhengqikj.top/Article/details/gtxsyyhksc.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzrwtaycm.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.chenzaomai.com/Article/details/gtejcygqml.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.sysykeji.top/Article/details/gtgfvmxmxg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnqqwjkmx.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sxryk.cn/Article/details/gtdvztjbas.html

[D11] 反转数组
来源：http://dali.tian-w.cn/Article/details/gtfoqmmwjw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.gaohongyu789.top/Article/details/gtndwichmz.html

PHP:  array_reverse($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtedcjmppg.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.fzhhl.top/Article/details/gtkzgesiig.html

TS:   [...arr].reverse();
来源：http://dali.yj202588.top/Article/details/gtuvwbvyhr.html

Java: Collections.reverse(list);
来源：http://dali.cdnleiting.top/Article/details/gtstuyqbst.html

Go:   slices.Reverse(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtomokemcp.html

Ruby: arr.reverse
来源：http://dali.zhiwuduotai.top/Article/details/gtwwtjegnn.html

C#:   list.Reverse();
来源：http://dali.zhixingplan.top/Article/details/gtragozsax.html

[D12] 查找元素下标
来源：http://dali.yueranfly.top/Article/details/gtaankrpch.html

Py:   arr.index(x);  x in arr
来源：http://dali.yj20258888.top/Article/details/gtvpeycbed.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtilaqpedm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.meibo888.top/Article/details/gtdvzqpsuv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.feifeiyinyue.top/Article/details/gtjqkgucwm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.316326.xyz/Article/details/gteiymjwee.html

Go:   slices.Index(arr, x)
来源：http://dali.gzhubu.top/Article/details/gtmjqgxagn.html

Ruby: arr.index(x)
来源：http://dali.yvedp.cn/Article/details/gtqsppsgue.html

C#:   list.IndexOf(x);
来源：http://dali.chenlongwang.top/Article/details/gtdnzmmjbh.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hywenlv.cn/Article/details/gtinwuxvfy.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.316326.xyz/Article/details/gtxjphkfvc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jiagoushi.top/Article/details/gtztelnofm.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpncmkzss.html

TS:   arr.filter(x => x > 3)
来源：http://dali.dianchejie.cn/Article/details/gtcajxqjez.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtlzdkumaq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hongshengwenyu.top/Article/details/gtjdcahjyl.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jianghu66.top/Article/details/gtdaaocjun.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hywenlv.cn/Article/details/gtpmpqyrii.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shangyingyoupin.top/Article/details/gtvojmnplr.html


<!-- 参考信息 -->