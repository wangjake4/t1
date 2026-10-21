代发 wailian999

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.xuanzx.com/Article/details/gtdwiaaffd.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jianghu66.top/Article/details/gtjwhgcocs.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.tianlin.xyz/Article/details/gtihznezkb.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.iojbl.cn/Article/details/gtbuigfjyo.html

[B13] 判断是否为数字
来源：http://dali.yj20258.top/Article/details/gtpskqspqt.html

Py:   isinstance(x, (int, float))
来源：http://dali.yj20258888.top/Article/details/gtysrpbvpn.html

PHP:  is_numeric($x)
来源：http://dali.xinyue.icu/Article/details/gtierddtjn.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daxiang520.top/Article/details/gtntzaljiv.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhoulong.xyz/Article/details/gtjzwygetf.html

Java: x instanceof Number
来源：http://dali.316326.xyz/Article/details/gtpsqqdfyp.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.daxiang520.top/Article/details/gtexbgnuvj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.iojbl.cn/Article/details/gtzaxucuec.html

C#:   x is int or double or decimal
来源：http://dali.gogol.net.cn/Article/details/gtjxwqwjfu.html

[B14] 判断值是否在集合内
来源：http://dali.nwbrower.top/Article/details/gtiooyqkym.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jqgfzy.top/Article/details/gthgboakvi.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.cheryme.top/Article/details/gtqeouxvji.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zdqjudy.top/Article/details/gtnwdodkfn.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.cqqwz.cn/Article/details/gtnkqmgodl.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.birdmap.top/Article/details/gtpjkzlcje.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.smart0.xyz/Article/details/gtpfhndgnt.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ybcxt.top/Article/details/gtddnyctnt.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzdpoithm.html

[B15] 布尔运算与取反
来源：http://dali.birdmap.top/Article/details/gtjvuexgwt.html

Py:   a and b or not c
来源：http://dali.haohaochexian.top/Article/details/gtzbasqqvi.html

PHP:  $a && $b || !$c
来源：http://dali.ybcxt.top/Article/details/gtmlvcidfq.html

JS:   a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gtlcmteluq.html

TS:   a && b || !c
来源：http://dali.meibo888.top/Article/details/gtsvrtcbml.html

Java: a && b || !c
来源：http://dali.hnqzz.top/Article/details/gtktmohliz.html

Go:   a && b || !c
来源：http://dali.wangdashe.top/Article/details/gtdxtupxww.html

Ruby: a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gtxaaqwbyi.html

C#:   a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gtwnbvyvkw.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.birdmap.top/Article/details/gtbsmopuve.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gtcnofhnzj.html

PHP:  if (!$data) { return; }
来源：http://dali.meibo888.top/Article/details/gthgvozuqv.html

JS:   if (!data) return;
来源：http://dali.shuidangran.top/Article/details/gtxljppspb.html

TS:   if (!data) return;
来源：http://dali.cashguo.top/Article/details/gthebfvdsx.html

Java: if (data == null) return;
来源：http://dali.ydzc1.top/Article/details/gtucztxybm.html

Go:   if data == nil { return }
来源：http://dali.yj20258.top/Article/details/gtbaawaejg.html

Ruby: return if data.nil?
来源：http://dali.ywan-chungtsiang.top/Article/details/gttldvkiye.html

C#:   if (data == null) return;
来源：http://dali.snrcjt.cn/Article/details/gtcdimsmcb.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtgnrsnlhj.html

C. 函数与作用域
来源：http://dali.hywenlv.cn/Article/details/gthsyzelow.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtivctccmu.html

[C01] 定义函数
来源：http://dali.yuxming.cn/Article/details/gtctirqcrd.html

Py:   def add(a, b): return a + b
来源：http://dali.sxryk.cn/Article/details/gtbtwtgyjz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gtrsntkasf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtpgqrpwvi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtyhddakjy.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.sweek.top/Article/details/gtjyoeguls.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.pycfn.com/Article/details/gtzubvgrps.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cheryme.top/Article/details/gtwxbqhowu.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gtfsndznce.html

[C02] 默认参数
来源：http://dali.xuetiantiany.cn/Article/details/gtfgjwrfic.html

Py:   def greet(name="World"): return name
来源：http://dali.jianghu66.top/Article/details/gtasjxpnhx.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ivvv.top/Article/details/gtddfuklds.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.aizwys.cn/Article/details/gtnfrverct.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.sweek.top/Article/details/gtlmqabbuf.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cucudq.cn/Article/details/gtcbejhbjw.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.dianchejie.cn/Article/details/gtpffyunlo.html

Ruby: def greet(name = "World") = name
来源：http://dali.jinghuilouyu.cn/Article/details/gticjaaqij.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.svipenyu.cn/Article/details/gtbvxaluua.html

[C03] 可变参数
来源：http://dali.kuanghao11.cn/Article/details/gtcmiksydr.html

Py:   def total(*args): return sum(args)
来源：http://dali.wangdashe.top/Article/details/gtadndajap.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yangfankeji.com/Article/details/gtxueodwjg.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jqgufenzy.top/Article/details/gtbyrudijc.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.316326.xyz/Article/details/gtjpljassx.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xinyue.icu/Article/details/gtvdjczvac.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jlsjyb.cn/Article/details/gttyagzusg.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hongshengwenyu.top/Article/details/gtikjsepyy.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.sufxvd.cn/Article/details/gtbhqfqttj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.nanxuanxn.top/Article/details/gtzhywdbrc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.redwolf501.top/Article/details/gtqzlfenkw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.pycfn.com/Article/details/gtgfhodfnf.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yanxiufei.cn/Article/details/gthipbppxc.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.andypj.xyz/Article/details/gtngqvlvgc.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.meibo888.top/Article/details/gtxnbiaqgm.html

Go:   // 无：用配置结构体参数
来源：http://dali.sweek.top/Article/details/gttetjdwfw.html

Ruby: f(a: 1, b: 2)
来源：http://dali.sufxvd.cn/Article/details/gtchqvrbhv.html

C#:   f(a: 1, b: 2)
来源：http://dali.yanxiufei.cn/Article/details/gtewhohbvo.html

[C05] 返回多个值
来源：http://dali.jinqigufen.top/Article/details/gtphpymtvy.html

Py:   return a, b
来源：http://dali.316326.xyz/Article/details/gtycxpyrxu.html

PHP:  return [$a, $b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzjphclea.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhengqikj.top/Article/details/gteijtxhgm.html

TS:   return { a, b };
来源：http://dali.nwbrower.top/Article/details/gtupsekuki.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.wangshuangyany.cn/Article/details/gtoacwrqmq.html

Go:   return a, b
来源：http://dali.zycfv.cn/Article/details/gtetubnjmn.html

Ruby: return a, b
来源：http://dali.hywenlv.cn/Article/details/gtflkdnwnk.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.redwolf501.top/Article/details/gtyiwqwgwr.html

[C06] 匿名函数 / lambda
来源：http://dali.dashuyun.cn/Article/details/gtsyoagixz.html

Py:   square = lambda x: x * x
来源：http://dali.shangyingyoupin.top/Article/details/gtdcvwnaok.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jlsjyb.cn/Article/details/gtjnfzbpxy.html

JS:   const square = x => x * x;
来源：http://dali.dianchejie.cn/Article/details/gtwstuvkps.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gtemawycca.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xinyue.icu/Article/details/gtkxaavghx.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.guowangkeji.top/Article/details/gtbbejrhdp.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ehwqpu.com/Article/details/gtrakcitth.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hammf.cn/Article/details/gtuhcrtbqj.html

[C07] 把函数作为参数传入
来源：http://dali.yonumen.top/Article/details/gtoniwjujv.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.dashuyun.cn/Article/details/gtuhlwimcw.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.nanxinkj.top/Article/details/gtrqbhjodz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttraggfhn.html

TS:   arr.map(String)
来源：http://dali.aibaodan.cn/Article/details/gtgnheiyzq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zdqjudy.top/Article/details/gtxchmugth.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.pycfn.com/Article/details/gtelmkczkh.html

Ruby: arr.map(&:upcase)
来源：http://dali.shangyingyoupin.top/Article/details/gttdswmokv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgojcitky.html

[C08] 闭包
来源：http://dali.hysaishi.cn/Article/details/gtoxnxvqdx.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.chenlongwang.top/Article/details/gtoqxsgjew.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.quarkkingdee.top/Article/details/gtainssebr.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yangfankeji.com/Article/details/gtmqlfsdfh.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.daxiang520.top/Article/details/gtwgasniyn.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hammf.cn/Article/details/gtmoleawtz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shuidangran.top/Article/details/gtsnjxzzkd.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xuetiantiany.cn/Article/details/gtavzzkhoo.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shangyingyoupin.top/Article/details/gtywvzkyls.html

[C09] 递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtqlfbhlqb.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.birdmap.top/Article/details/gtgmsvgjqt.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.sweek.top/Article/details/gtsdfhdeis.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigufen.top/Article/details/gtjstffbsp.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zycfv.cn/Article/details/gtvyvinvmt.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.smart0.xyz/Article/details/gtobaakseg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hfpthk.cn/Article/details/gtgrtcyvxi.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yj20258888.top/Article/details/gtkzyychjl.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxtxptqwh.html

[C10] 变量作用域
来源：http://dali.yangfankeji.com/Article/details/gtnhrnwxbx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.shzxlz.cn/Article/details/gtmekafgqa.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.snrcjt.cn/Article/details/gtjywwglxz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xinyue.icu/Article/details/gtjxxszsnb.html

TS:   同 JS
来源：http://dali.birdmap.top/Article/details/gtdxjysaqe.html

Java: 方法内为块级作用域
来源：http://dali.sxryk.cn/Article/details/gtqaaznbhm.html

Go:   花括号块级作用域
来源：http://dali.daxiang520.top/Article/details/gtgamycotk.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.meibo888.top/Article/details/gtqxumyrnd.html

C#:   块级作用域
来源：http://dali.gogol.net.cn/Article/details/gtrtmprujy.html

[C11] 模块导入与导出
来源：http://dali.ppjwa.cn/Article/details/gttoeppkjj.html

Py:   from module import func
来源：http://dali.ybcxt.top/Article/details/gtqrqygrmy.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.pengpengdd.cyou/Article/details/gtcoykcvcy.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.0kj1m.cn/Article/details/gtkuzkxhyd.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yj20258888.top/Article/details/gtmjvvsmss.html

Java: import java.util.List;
来源：http://dali.shangyingyoupin.top/Article/details/gtenacppfe.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sysykeji.top/Article/details/gthegnraqh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.pycfn.com/Article/details/gtintnbkox.html

C#:   using System.Text;
来源：http://dali.aizwys.cn/Article/details/gtmjrtdrzp.html

[C12] 立即执行函数 IIFE
来源：http://dali.cdnleiting.top/Article/details/gtlcvekppo.html

Py:   (lambda: print("run"))()
来源：http://dali.xuanzx.com/Article/details/gtsvdptbwe.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yangfankeji.com/Article/details/gtsyxsgzos.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ppjwa.cn/Article/details/gtxjlbnnef.html

TS:   (() => { console.log("run"); })();
来源：http://dali.quarkkingdee.top/Article/details/gthagvolwu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shuidangran.top/Article/details/gttnshtzmf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.chenjidiqi.icu/Article/details/gtegrmfpfx.html

Ruby: -> { puts "run" }.call
来源：http://dali.wangshuangyany.cn/Article/details/gtodtjpjkc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.wangdashe.top/Article/details/gttflwlbiz.html

[C13] 类型声明 / 类型注解
来源：http://dali.hnxiangtu.top/Article/details/gtmfkyeiug.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.fzhhl.top/Article/details/gtvyajsfsw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqmdbfmsg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.guowangkeji.top/Article/details/gtzotvspbf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gtrpjfqbnk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtpjuihphc.html

Go:   func add(a, b int) int
来源：http://dali.hnxiangtu.top/Article/details/gtlkvwpdxm.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sweek.top/Article/details/gtsmhixehg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shzxlz.cn/Article/details/gtvhtrtltm.html

[C14] 泛型函数
来源：http://dali.ydzc1.top/Article/details/gtedjrudbs.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.pycfn.com/Article/details/gtfuqfklcv.html

PHP:  // 无泛型
来源：http://dali.fzhhl.top/Article/details/gtpjbdzksq.html

JS:   // 无泛型
来源：http://dali.mhx1999.top/Article/details/gtdnjjrske.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xuetiantiany.cn/Article/details/gtzeatnkxo.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhoulong.xyz/Article/details/gtpxyrqbog.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.aibaodan.cn/Article/details/gtfqbtkwod.html

Ruby: # 无泛型
来源：http://dali.fzhhl.top/Article/details/gtemgkjdpt.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhixingplan.top/Article/details/gtkazatdgf.html

[C15] 解构 / 展开参数
来源：http://dali.yj20258888.top/Article/details/gteqqbqkbl.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yonumen.top/Article/details/gtqenqlsrr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhengqikj.top/Article/details/gtvhkfbllk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xuetiantiany.cn/Article/details/gttqewqtkt.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jyoumei.cn/Article/details/gtigqikbqp.html

Java: // 无解构
来源：http://dali.ivvv.top/Article/details/gtpegjzors.html

Go:   // 无解构
来源：http://dali.cheryme.top/Article/details/gtyhzxufcu.html

Ruby: a, b = pair
来源：http://dali.wangdashe.top/Article/details/gtxfzvsrlz.html

C#:   var (a, b) = pair;
来源：http://dali.gogol.net.cn/Article/details/gtfdzjgyyo.html

[C16] 函数 / 方法重载
来源：http://dali.yangfankeji.com/Article/details/gtlbfadpcb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xuanzx.com/Article/details/gthauvfynf.html

PHP:  // 无重载
来源：http://dali.316326.xyz/Article/details/gtohdntnpx.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cashguo.top/Article/details/gtwfnsftkn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhoulong.xyz/Article/details/gtyxobmkkw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuyqfrrzl.html

Go:   // 无重载：用不同函数名
来源：http://dali.hfpthk.cn/Article/details/gtcaqrpifn.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yueranfly.top/Article/details/gtghuydmcl.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gogol.net.cn/Article/details/gtcxztvpnc.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtvrxargnw.html

D. 数组 / 列表 / 集合
来源：http://dali.zycfv.cn/Article/details/gtkwwdjlez.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtlppkcakb.html

[D01] 创建数组 / 列表
来源：http://dali.gzhubu.top/Article/details/gtijervrgy.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sxryk.cn/Article/details/gtmxawiwxs.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.birdmap.top/Article/details/gtldynakgs.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.daxiang520.top/Article/details/gtcoloqwbp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.kuanghao11.cn/Article/details/gtaikvyjeh.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.c1oappe.top/Article/details/gtlgtzdztv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.feifeiyinyue.top/Article/details/gtjebomoro.html

Ruby: arr = [1, 2, 3]
来源：http://dali.fzhhl.top/Article/details/gtvniucahk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmbkcvzjt.html

[D02] 追加元素到末尾
来源：http://dali.feifeiyinyue.top/Article/details/gtcadxpodg.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjvixoxir.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shzxlz.cn/Article/details/gtxmnxpjzr.html

JS:   arr.push(4);
来源：http://dali.gogol.net.cn/Article/details/gtpzgpijyz.html

TS:   arr.push(4);
来源：http://dali.yj20258888.top/Article/details/gtpknmoclj.html

Java: list.add(4);
来源：http://dali.birdmap.top/Article/details/gtdbguzoii.html

Go:   arr = append(arr, 4)
来源：http://dali.chenzaomai.com/Article/details/gtvcajrocw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.tian-w.cn/Article/details/gteyoavyxk.html

C#:   list.Add(4);
来源：http://dali.yanxiufei.cn/Article/details/gteztncxui.html

[D03] 在指定位置插入元素
来源：http://dali.316326.xyz/Article/details/gtttqnkgbt.html

Py:   arr.insert(0, 0)
来源：http://dali.ydzc1.top/Article/details/gteascnowq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jiagoushi.top/Article/details/gtykuikgne.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.wangdashe.top/Article/details/gtsvfiipbp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yuanzhike.top/Article/details/gtvcwiqdzf.html

Java: list.add(0, 0);
来源：http://dali.yj20258888.top/Article/details/gtykovqotm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yanxiufei.cn/Article/details/gtwgbwovad.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yj202588.top/Article/details/gtbkfhrmfy.html

C#:   list.Insert(0, 0);
来源：http://dali.xuanzx.com/Article/details/gtgqxscilp.html

[D04] 删除元素
来源：http://dali.hywenlv.cn/Article/details/gtalnwmkrg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpkwndgom.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtihihyext.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yj20258888.top/Article/details/gtjciiqxos.html

TS:   arr.splice(0, 1);
来源：http://dali.mhx1999.top/Article/details/gtglybtqch.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jinqigfzy.top/Article/details/gtrhejhyet.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jinqigufen.top/Article/details/gtxxqfrdwb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.316326.xyz/Article/details/gtbrcekjir.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.tanke756.top/Article/details/gtcssiqbqk.html

[D05] 访问与修改元素
来源：http://dali.cashguo.top/Article/details/gtpxmtnlff.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nwbrower.top/Article/details/gtjqxuyysw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinghuilouyu.cn/Article/details/gtwihuzcco.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.guowangkeji.top/Article/details/gtrfugdzyx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.chenjidiqi.icu/Article/details/gtngdjqohn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hnxiangtu.top/Article/details/gtdvudpnhf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.chenlongwang.top/Article/details/gtvysxojhz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gteojmglby.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gtqvdameam.html

[D06] 数组长度
来源：http://dali.nwbrower.top/Article/details/gtnruaphoa.html

Py:   len(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtekenzxmf.html

PHP:  count($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtnidnymde.html

JS:   arr.length
来源：http://dali.jlsjyb.cn/Article/details/gtxxezxlbd.html

TS:   arr.length
来源：http://dali.jlsjyb.cn/Article/details/gtsydmesxz.html

Java: list.size();
来源：http://dali.shangyingyoupin.top/Article/details/gtelmiesub.html

Go:   len(arr)
来源：http://dali.aibaodan.cn/Article/details/gtbwmsgmni.html

Ruby: arr.length; arr.size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyinextvy.html

C#:   list.Count;
来源：http://dali.yangfankeji.com/Article/details/gtzsbkwibt.html

[D07] 切片 / 取子数组
来源：http://dali.fzhhl.top/Article/details/gtnlrwpzyk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xinyue.icu/Article/details/gteknjghxj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shzxlz.cn/Article/details/gtieosocso.html

JS:   arr.slice(1, 4);
来源：http://dali.nanxuanxn.top/Article/details/gthjcyowlo.html

TS:   arr.slice(1, 4);
来源：http://dali.ehwqpu.com/Article/details/gtzugkfqac.html

Java: list.subList(1, 4);
来源：http://dali.chenlongwang.top/Article/details/gtgonhdrya.html

Go:   arr[1:4]
来源：http://dali.cashguo.top/Article/details/gtickzevmc.html

Ruby: arr[1, 3]
来源：http://dali.cheryme.top/Article/details/gtdipbqjno.html

C#:   list.GetRange(1, 3);
来源：http://dali.jiagoushi.top/Article/details/gtltifvukq.html

[D08] 合并两个数组
来源：http://dali.wangshuangyany.cn/Article/details/gttkwhfvgu.html

Py:   a + b;  a.extend(b)
来源：http://dali.xinyue.icu/Article/details/gtxrlypbsi.html

PHP:  array_merge($a, $b);
来源：http://dali.ivvv.top/Article/details/gtrdmcdqxk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenzaomai.com/Article/details/gtnuwtvffu.html

TS:   [...a, ...b];
来源：http://dali.chenlongwang.top/Article/details/gtwnrinlye.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hysaishi.cn/Article/details/gttleymdxe.html

Go:   append(a, b...)
来源：http://dali.c1oappe.top/Article/details/gtlhodspvx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shzxlz.cn/Article/details/gtdniynfrv.html

C#:   a.Concat(b).ToList()
来源：http://dali.gogol.net.cn/Article/details/gtdhkczzcf.html

[D09] 排序（升序）
来源：http://dali.yonumen.top/Article/details/gtuwdnczoy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.0kj1m.cn/Article/details/gtccmnnzqh.html

PHP:  sort($arr);
来源：http://dali.shuidangran.top/Article/details/gtrhtlnyia.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.chenzaomai.com/Article/details/gtmhiztseo.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.dianchejie.cn/Article/details/gtoyqpgvqp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yueranfly.top/Article/details/gtqwlgrmvm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtpgasqolt.html

Ruby: arr.sort
来源：http://dali.daria6918.cn/Article/details/gtshjxrgcy.html

C#:   list.Sort();
来源：http://dali.nwbrower.top/Article/details/gtvgltvvsw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zycfv.cn/Article/details/gtvhvphsoo.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinqigfzy.top/Article/details/gtnhxfbims.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpwgpaarz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aibaodan.cn/Article/details/gtostrkanp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hongshengwenyu.top/Article/details/gtbmeumybh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.kuanghao11.cn/Article/details/gtbkjyrxuo.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.pengpengdd.cyou/Article/details/gtloqutftb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gogol.net.cn/Article/details/gtoyfdrzxm.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.nanxuanxn.top/Article/details/gtpiyqvdda.html

[D11] 反转数组
来源：http://dali.gzhubu.top/Article/details/gtvphanrzz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yuanzhike.top/Article/details/gtyljabpyc.html

PHP:  array_reverse($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtnincifut.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.quarkkingdee.top/Article/details/gtexxslocd.html

TS:   [...arr].reverse();
来源：http://dali.hywenlv.cn/Article/details/gtlombntxh.html

Java: Collections.reverse(list);
来源：http://dali.guannengcc.top/Article/details/gtwivxvgdw.html

Go:   slices.Reverse(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtgubyieru.html

Ruby: arr.reverse
来源：http://dali.yuanzhike.top/Article/details/gtnqdufzps.html

C#:   list.Reverse();
来源：http://dali.316326.xyz/Article/details/gtsrbiwokb.html

[D12] 查找元素下标
来源：http://dali.gotoacloud.top/Article/details/gtttwfprwx.html

Py:   arr.index(x);  x in arr
来源：http://dali.hammf.cn/Article/details/gtuuurmyvz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.sweek.top/Article/details/gtpljmihmy.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yuxming.cn/Article/details/gtjozbmvrd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gzhubu.top/Article/details/gtcpvqrxki.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtggvfneqs.html

Go:   slices.Index(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtaxsyquxh.html

Ruby: arr.index(x)
来源：http://dali.ydzc1.top/Article/details/gtfwlcmcov.html

C#:   list.IndexOf(x);
来源：http://dali.svipenyu.cn/Article/details/gtffniiyjl.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yuxming.cn/Article/details/gtafecryru.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.wangdashe.top/Article/details/gtqeocgrdk.html


<!-- 参考信息 -->