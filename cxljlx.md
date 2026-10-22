代发 wailian999

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zycfv.cn/Article/details/gtgqmagswo.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.shuidangran.top/Article/details/gtnyeescxe.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jqgufenzy.top/Article/details/gtttherhse.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.fzhhl.top/Article/details/gtimwhdwht.html

[B13] 判断是否为数字
来源：http://dali.cucudq.cn/Article/details/gtohwdbwax.html

Py:   isinstance(x, (int, float))
来源：http://dali.tianlin.xyz/Article/details/gtkhhghbmh.html

PHP:  is_numeric($x)
来源：http://dali.andypj.xyz/Article/details/gtkmqihmrw.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxinkj.top/Article/details/gttutwdwyl.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.andypj.xyz/Article/details/gttnayarzl.html

Java: x instanceof Number
来源：http://dali.jlsjyb.cn/Article/details/gttcxaffhe.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zdqjudy.top/Article/details/gtwssdpuwb.html

Ruby: x.is_a?(Numeric)
来源：http://dali.cqqwz.cn/Article/details/gtprfrmdva.html

C#:   x is int or double or decimal
来源：http://dali.xinyue.icu/Article/details/gtmqgjdrhg.html

[B14] 判断值是否在集合内
来源：http://dali.zhongyouzk.top/Article/details/gtlhfethcy.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.guannengcc.top/Article/details/gtmogjbwkb.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.nanxuanxn.top/Article/details/gtognlnbwz.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gtytlpwoag.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhengqikj.top/Article/details/gtcyvnriba.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.kuanghao11.cn/Article/details/gtjedklbqn.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.aizwys.cn/Article/details/gttjcrrutm.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsnzrxsay.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.cheryme.top/Article/details/gtzbpqkewg.html

[B15] 布尔运算与取反
来源：http://dali.jyoumei.cn/Article/details/gtazshexwx.html

Py:   a and b or not c
来源：http://dali.ybcxt.top/Article/details/gteepcmeso.html

PHP:  $a && $b || !$c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsvjtrujh.html

JS:   a && b || !c
来源：http://dali.yongpay.top/Article/details/gtwmxbnlbj.html

TS:   a && b || !c
来源：http://dali.yj20258888.top/Article/details/gtvwizcgms.html

Java: a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gtpqtlgesl.html

Go:   a && b || !c
来源：http://dali.hammf.cn/Article/details/gtfasmdbjr.html

Ruby: a && b || !c
来源：http://dali.tanke756.top/Article/details/gthypgudhd.html

C#:   a && b || !c
来源：http://dali.redwolf501.top/Article/details/gtifnognkv.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.havefunace.top/Article/details/gthgxolvhz.html

Py:   if not data: return
来源：http://dali.sufxvd.cn/Article/details/gthtjuftqe.html

PHP:  if (!$data) { return; }
来源：http://dali.pengpengdd.cyou/Article/details/gtrdvpmjqr.html

JS:   if (!data) return;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkzqphafn.html

TS:   if (!data) return;
来源：http://dali.jinqigfzy.top/Article/details/gtvqzrslrf.html

Java: if (data == null) return;
来源：http://dali.zhiwuduotai.top/Article/details/gtajtnnwpb.html

Go:   if data == nil { return }
来源：http://dali.yanxiufei.cn/Article/details/gtozvyngla.html

Ruby: return if data.nil?
来源：http://dali.gotoacloud.top/Article/details/gtwfaycqpk.html

C#:   if (data == null) return;
来源：http://dali.daria6918.cn/Article/details/gtdfkvyeef.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtdkvoxthr.html

C. 函数与作用域
来源：http://dali.havefunace.top/Article/details/gtoglkwgup.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtkttknspi.html

[C01] 定义函数
来源：http://dali.aibaodan.cn/Article/details/gtmrggiyjl.html

Py:   def add(a, b): return a + b
来源：http://dali.jqgufenzy.top/Article/details/gtonzmnujq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinqigfzy.top/Article/details/gtatkktliq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gtkpgwcfvv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gtmwjmprxg.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gtkrasdjur.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhiwuduotai.top/Article/details/gtusauvauo.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yueranfly.top/Article/details/gtjtsqgrtw.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gttuwmgypm.html

[C02] 默认参数
来源：http://dali.vqdsnc.cn/Article/details/gtzvblfxry.html

Py:   def greet(name="World"): return name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpwqwqyiq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.smart0.xyz/Article/details/gtstbrzmhx.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.birdmap.top/Article/details/gtglqlimbb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.snrcjt.cn/Article/details/gtoycsitdd.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.guannengcc.top/Article/details/gtuavwtyvr.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hammf.cn/Article/details/gtcoqpcjdm.html

Ruby: def greet(name = "World") = name
来源：http://dali.0kj1m.cn/Article/details/gtzzgaxond.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.kuanghao11.cn/Article/details/gtbzoxlfuw.html

[C03] 可变参数
来源：http://dali.hammf.cn/Article/details/gtueqqcxpe.html

Py:   def total(*args): return sum(args)
来源：http://dali.sxryk.cn/Article/details/gtuujdtknj.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yj20258888.top/Article/details/gtyajwcszf.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.havefunace.top/Article/details/gtvzvvmgzd.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xuetiantiany.cn/Article/details/gtjrxmfdhr.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jianghu66.top/Article/details/gtjuwsczdg.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cheryme.top/Article/details/gtfnalnqap.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.dashuyun.cn/Article/details/gtbymwognu.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hongshengwenyu.top/Article/details/gtuyabrvnf.html

[C04] 命名参数 / 关键字参数
来源：http://dali.sysykeji.top/Article/details/gterjcovnd.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jyoumei.cn/Article/details/gtfwcruyzn.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.vqdsnc.cn/Article/details/gthupjmdcm.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.quarkkingdee.top/Article/details/gtvqmrvvki.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yongpay.top/Article/details/gtdrxjzqql.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ydzc1.top/Article/details/gtdnphzahk.html

Go:   // 无：用配置结构体参数
来源：http://dali.jqgufenzy.top/Article/details/gtcscowbjt.html

Ruby: f(a: 1, b: 2)
来源：http://dali.aizwys.cn/Article/details/gtwrtstukd.html

C#:   f(a: 1, b: 2)
来源：http://dali.xinyue.icu/Article/details/gtxvviyifj.html

[C05] 返回多个值
来源：http://dali.pengpengdd.cyou/Article/details/gtqcanktnk.html

Py:   return a, b
来源：http://dali.xinyue.icu/Article/details/gteofowbzc.html

PHP:  return [$a, $b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gttmueofbz.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jyoumei.cn/Article/details/gtiyvshxul.html

TS:   return { a, b };
来源：http://dali.hnxiangtu.top/Article/details/gtayiyzkgg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.dianchejie.cn/Article/details/gtdsmpnnfe.html

Go:   return a, b
来源：http://dali.yongpay.top/Article/details/gtzzycswrv.html

Ruby: return a, b
来源：http://dali.svipenyu.cn/Article/details/gtomnwikce.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.0kj1m.cn/Article/details/gtqwgifzud.html

[C06] 匿名函数 / lambda
来源：http://dali.nwbrower.top/Article/details/gtvvskjtzp.html

Py:   square = lambda x: x * x
来源：http://dali.pycfn.com/Article/details/gtsadagfwe.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.tanke756.top/Article/details/gtpsqokiow.html

JS:   const square = x => x * x;
来源：http://dali.svipenyu.cn/Article/details/gthlbkgfar.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.gogol.net.cn/Article/details/gtfbqunpee.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.haohaochexian.top/Article/details/gtvmmyrdur.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.fengsongda.top/Article/details/gttcphiexa.html

Ruby: square = ->(x) { x * x }
来源：http://dali.chenjidiqi.icu/Article/details/gtryqjdbwe.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhengqikj.top/Article/details/gtqcvazitv.html

[C07] 把函数作为参数传入
来源：http://dali.shuidangran.top/Article/details/gtdcozhonz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.guowangkeji.top/Article/details/gtrymjenwm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.fengsongda.top/Article/details/gtibclgdqj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shanyushiyangkeji.top/Article/details/gteneqnrrj.html

TS:   arr.map(String)
来源：http://dali.shzxlz.cn/Article/details/gtrgqajkbk.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtketlqxvl.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.pycfn.com/Article/details/gtcltavamz.html

Ruby: arr.map(&:upcase)
来源：http://dali.jiagoushi.top/Article/details/gtmwdelkue.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.sxryk.cn/Article/details/gttphzfled.html

[C08] 闭包
来源：http://dali.xinyue.icu/Article/details/gtwvztgggz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.havefunace.top/Article/details/gttakvfgth.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfwfsrxfx.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.dianchejie.cn/Article/details/gtzkotufba.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yj20258888.top/Article/details/gthehtdaoo.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.haohaochexian.top/Article/details/gtdqywabdr.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gtppnyefmq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cheryme.top/Article/details/gtepifhnrl.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.sweek.top/Article/details/gtoodwxzrw.html

[C09] 递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxjdcyeel.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.chenlongwang.top/Article/details/gtmyxyqiwn.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gtuftrxanx.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.bjfxy.top/Article/details/gtktgcyqjp.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.vqdsnc.cn/Article/details/gttusjmyfx.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.aibaodan.cn/Article/details/gtgkupvbiz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.redwolf501.top/Article/details/gtonmkxwwf.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shzxlz.cn/Article/details/gtyvpgzlfq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.iojbl.cn/Article/details/gtxknxhpxw.html

[C10] 变量作用域
来源：http://dali.xziqi.cn/Article/details/gthqbqeufh.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.chenzaomai.com/Article/details/gtgqsfglzf.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jqgufenzy.top/Article/details/gtqtlijvgj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.tianlin.xyz/Article/details/gtuqevohim.html

TS:   同 JS
来源：http://dali.gaohongyu789.top/Article/details/gtuwsgfmzl.html

Java: 方法内为块级作用域
来源：http://dali.chenlongwang.top/Article/details/gtcozzivvs.html

Go:   花括号块级作用域
来源：http://dali.pengpengdd.cyou/Article/details/gtcldzltue.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.aizwys.cn/Article/details/gtotkywreh.html

C#:   块级作用域
来源：http://dali.hongshengwenyu.top/Article/details/gtubjtbcvn.html

[C11] 模块导入与导出
来源：http://dali.fzhhl.top/Article/details/gtjztxdzxh.html

Py:   from module import func
来源：http://dali.shanyushiyangkeji.top/Article/details/gtazzcmqdl.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shanyushiyangtech.top/Article/details/gtojkdefor.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.pycfn.com/Article/details/gtzqkgfzfq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.tian-w.cn/Article/details/gtppyuocqd.html

Java: import java.util.List;
来源：http://dali.yuxming.cn/Article/details/gtocsvuxqj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.mhx1999.top/Article/details/gtkdkzhfrv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.tian-w.cn/Article/details/gtuzdqnfkd.html

C#:   using System.Text;
来源：http://dali.snrcjt.cn/Article/details/gtkldraibe.html

[C12] 立即执行函数 IIFE
来源：http://dali.kuanghao11.cn/Article/details/gtwdjhtvpv.html

Py:   (lambda: print("run"))()
来源：http://dali.chenjidiqi.icu/Article/details/gtjvezowso.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xziqi.cn/Article/details/gtfznsbqql.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jqgfzy.top/Article/details/gtloxpqxwf.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hammf.cn/Article/details/gtlxrnqhhz.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinghuilouyu.cn/Article/details/gtxonsnmdt.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yuanzhike.top/Article/details/gtfwuymxyc.html

Ruby: -> { puts "run" }.call
来源：http://dali.cucudq.cn/Article/details/gtcjvfvrbk.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.nanxuanxn.top/Article/details/gtoeewohlt.html

[C13] 类型声明 / 类型注解
来源：http://dali.gogol.net.cn/Article/details/gtgpateqrf.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shangyingyoupin.top/Article/details/gtuzdgovgp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.316326.xyz/Article/details/gtvpodoqpn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ivvv.top/Article/details/gtihxxfozp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gttxpkijuq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gtavdmvjad.html

Go:   func add(a, b int) int
来源：http://dali.ydzc1.top/Article/details/gtkcxqzdeb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yuxming.cn/Article/details/gtxmfzsxqf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.nanxinkj.top/Article/details/gtfwoztlqy.html

[C14] 泛型函数
来源：http://dali.dianchejie.cn/Article/details/gtlrsgntzk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.nwbrower.top/Article/details/gtuhdhtmpe.html

PHP:  // 无泛型
来源：http://dali.zycfv.cn/Article/details/gtifhsgrhr.html

JS:   // 无泛型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvyhwqukn.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhongyouzk.top/Article/details/gtjxzbpswy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jianghu66.top/Article/details/gtvcmgiiwn.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhiwuduotai.top/Article/details/gteoovevkg.html

Ruby: # 无泛型
来源：http://dali.aibaodan.cn/Article/details/gtuqfzvzbd.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shangyingyoupin.top/Article/details/gtsbgqlwck.html

[C15] 解构 / 展开参数
来源：http://dali.aizwys.cn/Article/details/gtbjumrsyy.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.pycfn.com/Article/details/gtbrohidfj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yanxiufei.cn/Article/details/gtirgdxjnn.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtdczbefql.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.nanxinkj.top/Article/details/gtpanignqx.html

Java: // 无解构
来源：http://dali.tanke756.top/Article/details/gtowajtgmr.html

Go:   // 无解构
来源：http://dali.hnqzz.top/Article/details/gtdbpfyanq.html

Ruby: a, b = pair
来源：http://dali.bjfxy.top/Article/details/gtotpzqbbr.html

C#:   var (a, b) = pair;
来源：http://dali.redwolf501.top/Article/details/gtwendsqnf.html

[C16] 函数 / 方法重载
来源：http://dali.zdqjudy.top/Article/details/gtfhesygje.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zycfv.cn/Article/details/gtecxuzlnl.html

PHP:  // 无重载
来源：http://dali.shangyingyoupin.top/Article/details/gtzznyjkhe.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shangyingyoupin.top/Article/details/gtmibkzfdt.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jyoumei.cn/Article/details/gtbwyvfyex.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbvedqjnl.html

Go:   // 无重载：用不同函数名
来源：http://dali.jinyuanbaomall.cn/Article/details/gtumzsolsg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.meibo888.top/Article/details/gtokciorde.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.nwbrower.top/Article/details/gtiglrbzus.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtwxxyegqu.html

D. 数组 / 列表 / 集合
来源：http://dali.yonumen.top/Article/details/gtmilledqz.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtaxnzhwlm.html

[D01] 创建数组 / 列表
来源：http://dali.ehwqpu.com/Article/details/gtnusawoom.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hywenlv.cn/Article/details/gtmwsekqun.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jinghuilouyu.cn/Article/details/gttriibesl.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.tanke756.top/Article/details/gtghoqsxih.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.kuanghao11.cn/Article/details/gtujfzqbry.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.sweek.top/Article/details/gthylbyplq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yongpay.top/Article/details/gtjxrdixzm.html

Ruby: arr = [1, 2, 3]
来源：http://dali.kuanghao11.cn/Article/details/gtwntloqar.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shzxlz.cn/Article/details/gtcqhhthdq.html

[D02] 追加元素到末尾
来源：http://dali.svipenyu.cn/Article/details/gtmkvcpked.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.meibo888.top/Article/details/gthhqfueih.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gotoacloud.top/Article/details/gtgemerrlz.html

JS:   arr.push(4);
来源：http://dali.shangyingyoupin.top/Article/details/gtiombxbbq.html

TS:   arr.push(4);
来源：http://dali.xuanzx.com/Article/details/gtxfjfluob.html

Java: list.add(4);
来源：http://dali.jinqigufen.top/Article/details/gtxzjqmrih.html

Go:   arr = append(arr, 4)
来源：http://dali.sxryk.cn/Article/details/gtsewqxdur.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cdnleiting.top/Article/details/gthzpqgyiz.html

C#:   list.Add(4);
来源：http://dali.feifeiyinyue.top/Article/details/gtklflgpbs.html

[D03] 在指定位置插入元素
来源：http://dali.hfpthk.cn/Article/details/gtdslogtwt.html

Py:   arr.insert(0, 0)
来源：http://dali.jiagoushi.top/Article/details/gtarowxhqe.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.pengpengdd.cyou/Article/details/gtfnsthfzo.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.chenjidiqi.icu/Article/details/gthihvqhye.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jinqigufen.top/Article/details/gtmzvpfiop.html

Java: list.add(0, 0);
来源：http://dali.tian-w.cn/Article/details/gtxtxcufll.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhongyouzk.top/Article/details/gtlmrhzhaz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.redwolf501.top/Article/details/gtfdrkbpqt.html

C#:   list.Insert(0, 0);
来源：http://dali.dashuyun.cn/Article/details/gtkrlwfgnp.html

[D04] 删除元素
来源：http://dali.zhixingplan.top/Article/details/gtheeyzewa.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.guannengcc.top/Article/details/gtpwedadwe.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jyoumei.cn/Article/details/gtkbkohqmq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jqgufenzy.top/Article/details/gtniysullb.html

TS:   arr.splice(0, 1);
来源：http://dali.zhiwuduotai.top/Article/details/gtynrcmwmg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.nanxuanxn.top/Article/details/gtvgmoqlbo.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.wangshuangyany.cn/Article/details/gtgabwrpxv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.havefunace.top/Article/details/gtxnneftnu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.quarkkingdee.top/Article/details/gttkaiomdj.html

[D05] 访问与修改元素
来源：http://dali.yangfankeji.com/Article/details/gtofbggnqq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ivvv.top/Article/details/gtcgtkootz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.nanxinkj.top/Article/details/gthgbpmoyz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.tian-w.cn/Article/details/gtxuhyrlnu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj202588.top/Article/details/gtwslzemnz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yuanzhike.top/Article/details/gtxepzmgnn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.tian-w.cn/Article/details/gtogcxgebu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.feifeiyinyue.top/Article/details/gthncjpgwt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.vqdsnc.cn/Article/details/gtxtuepvlo.html

[D06] 数组长度
来源：http://dali.zhixingplan.top/Article/details/gttscsuwai.html

Py:   len(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyvvfrsyi.html

PHP:  count($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfkvgnbud.html

JS:   arr.length
来源：http://dali.mhx1999.top/Article/details/gtjwwyjrng.html

TS:   arr.length
来源：http://dali.meibo888.top/Article/details/gttvsrhvyj.html

Java: list.size();
来源：http://dali.wangdashe.top/Article/details/gtnwhvmhxv.html

Go:   len(arr)
来源：http://dali.gotoacloud.top/Article/details/gtwzcrjhtf.html

Ruby: arr.length; arr.size
来源：http://dali.zycfv.cn/Article/details/gtabluzevq.html

C#:   list.Count;
来源：http://dali.sweek.top/Article/details/gtomykereh.html

[D07] 切片 / 取子数组
来源：http://dali.ivvv.top/Article/details/gtopppyzpo.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jqgfzy.top/Article/details/gtuldpfzej.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yuanzhike.top/Article/details/gtocsczfxj.html

JS:   arr.slice(1, 4);
来源：http://dali.meibo888.top/Article/details/gtwraoesyx.html

TS:   arr.slice(1, 4);
来源：http://dali.gaohongyu789.top/Article/details/gtrpxjoddq.html

Java: list.subList(1, 4);
来源：http://dali.smart0.xyz/Article/details/gtsolysxci.html

Go:   arr[1:4]
来源：http://dali.fengsongda.top/Article/details/gthbdcrajz.html

Ruby: arr[1, 3]
来源：http://dali.zdqjudy.top/Article/details/gtcjhgkedv.html

C#:   list.GetRange(1, 3);
来源：http://dali.jqgufenzy.top/Article/details/gtrexlswax.html

[D08] 合并两个数组
来源：http://dali.yuanzhike.top/Article/details/gtwueoaroj.html

Py:   a + b;  a.extend(b)
来源：http://dali.gaohongyu789.top/Article/details/gthlqjistf.html

PHP:  array_merge($a, $b);
来源：http://dali.xylfe.cn/Article/details/gtaovaowiz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yuanzhike.top/Article/details/gtoliuytae.html

TS:   [...a, ...b];
来源：http://dali.yuxming.cn/Article/details/gtweivqhuv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtommjqgql.html

Go:   append(a, b...)
来源：http://dali.daria6918.cn/Article/details/gtdykcicfd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.pengpengdd.cyou/Article/details/gtmwlbvpvk.html

C#:   a.Concat(b).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtnvtuwlbr.html

[D09] 排序（升序）
来源：http://dali.hnxiangtu.top/Article/details/gtmgdqbesf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigfzy.top/Article/details/gtxztssbzw.html

PHP:  sort($arr);
来源：http://dali.c1oappe.top/Article/details/gtjoriypeo.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xuanzx.com/Article/details/gtbkwruzup.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shzxlz.cn/Article/details/gtqzuqjqey.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.quarkkingdee.top/Article/details/gtymvmripl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtnerdqjtj.html

Ruby: arr.sort
来源：http://dali.hnqzz.top/Article/details/gtyvoolytv.html

C#:   list.Sort();
来源：http://dali.hnxiangtu.top/Article/details/gtmsivhodi.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yj20258888.top/Article/details/gtziyiobkq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.tianlin.xyz/Article/details/gtxidfnslm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xinyue.icu/Article/details/gthusyzzrr.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daria6918.cn/Article/details/gtpyggwspz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhixingplan.top/Article/details/gtobtqztig.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shangyingyoupin.top/Article/details/gtiobivnax.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ivvv.top/Article/details/gthuaefzcg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hongshengwenyu.top/Article/details/gtoxfgtswx.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cqqwz.cn/Article/details/gtsbubozgo.html

[D11] 反转数组
来源：http://dali.tianlin.xyz/Article/details/gtyzgnilnl.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthuqpfhvs.html

PHP:  array_reverse($arr);
来源：http://dali.yvedp.cn/Article/details/gtapjwpcbc.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.pengpengdd.cyou/Article/details/gtbmrtgcge.html

TS:   [...arr].reverse();
来源：http://dali.nanxinkj.top/Article/details/gtghqhnbcn.html

Java: Collections.reverse(list);
来源：http://dali.iojbl.cn/Article/details/gtlvcsvnro.html

Go:   slices.Reverse(arr)
来源：http://dali.jiagoushi.top/Article/details/gtggzpesfh.html

Ruby: arr.reverse
来源：http://dali.gogol.net.cn/Article/details/gtlmehzbij.html

C#:   list.Reverse();
来源：http://dali.zdqjudy.top/Article/details/gtzkvoubsi.html

[D12] 查找元素下标
来源：http://dali.andypj.xyz/Article/details/gtjxqmtysc.html

Py:   arr.index(x);  x in arr
来源：http://dali.shanyushiyangtech.top/Article/details/gtxxvgtzrm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zycfv.cn/Article/details/gteeuitpcq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gogol.net.cn/Article/details/gtfjrifbrq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigfzy.top/Article/details/gtoxbjaacg.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yonumen.top/Article/details/gtabeqghfk.html

Go:   slices.Index(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gtolmgkiru.html

Ruby: arr.index(x)
来源：http://dali.iojbl.cn/Article/details/gtdxubvqdg.html

C#:   list.IndexOf(x);
来源：http://dali.shuidangran.top/Article/details/gtsrewsdxu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jinqigufen.top/Article/details/gtmsvhidgu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sweek.top/Article/details/gthwqaesmn.html


<!-- 参考信息 -->