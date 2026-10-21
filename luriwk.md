代发 wailian999

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.gogol.net.cn/Article/details/gtqtzjdwon.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yanxiufei.cn/Article/details/gtnxoaocvs.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.sweek.top/Article/details/gtzantvaql.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.smart0.xyz/Article/details/gtiiziisxb.html

[B13] 判断是否为数字
来源：http://dali.hfpthk.cn/Article/details/gtwisnxqgs.html

Py:   isinstance(x, (int, float))
来源：http://dali.yongpay.top/Article/details/gtxdcpknxx.html

PHP:  is_numeric($x)
来源：http://dali.jqgfzy.top/Article/details/gtlpvarptu.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.aizwys.cn/Article/details/gtuehtfvgy.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daria6918.cn/Article/details/gtyvxvustf.html

Java: x instanceof Number
来源：http://dali.sysykeji.top/Article/details/gtujwhjuai.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yuxming.cn/Article/details/gtagfvkbun.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shuidangran.top/Article/details/gtvvpwjobo.html

C#:   x is int or double or decimal
来源：http://dali.sysykeji.top/Article/details/gtvxgeilte.html

[B14] 判断值是否在集合内
来源：http://dali.xylfe.cn/Article/details/gteycavxaj.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhoulong.xyz/Article/details/gtjthutzzs.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jqgufenzy.top/Article/details/gtmgjfzvpg.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gtgbrfxbzt.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gtqakusgdm.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yj202588.top/Article/details/gtxqsthyts.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.sweek.top/Article/details/gtmqxjffvc.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shuidangran.top/Article/details/gtjrnjjfuw.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.aibaodan.cn/Article/details/gtuoikfkfp.html

[B15] 布尔运算与取反
来源：http://dali.cheryme.top/Article/details/gtfapebxiu.html

Py:   a and b or not c
来源：http://dali.hnqzz.top/Article/details/gthsgxkfrp.html

PHP:  $a && $b || !$c
来源：http://dali.yvedp.cn/Article/details/gtezxfllki.html

JS:   a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gtxcozugms.html

TS:   a && b || !c
来源：http://dali.hongshengwenyu.top/Article/details/gtkdjpkrlv.html

Java: a && b || !c
来源：http://dali.birdmap.top/Article/details/gtdwcxshym.html

Go:   a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gtwhcwxnff.html

Ruby: a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gthfnkxsyh.html

C#:   a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gttlectbaz.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ppjwa.cn/Article/details/gtujfugxyi.html

Py:   if not data: return
来源：http://dali.jlsjyb.cn/Article/details/gtfpamjcbs.html

PHP:  if (!$data) { return; }
来源：http://dali.bjfxy.top/Article/details/gtedgelfvq.html

JS:   if (!data) return;
来源：http://dali.9152youxi.cn/Article/details/gtvrosgxhc.html

TS:   if (!data) return;
来源：http://dali.jlsjyb.cn/Article/details/gtlhlgampn.html

Java: if (data == null) return;
来源：http://dali.jinghuilouyu.cn/Article/details/gtpqifuvfh.html

Go:   if data == nil { return }
来源：http://dali.zhixingplan.top/Article/details/gtzzgeigie.html

Ruby: return if data.nil?
来源：http://dali.yueranfly.top/Article/details/gtqnurkbfp.html

C#:   if (data == null) return;
来源：http://dali.yueranfly.top/Article/details/gtnrrmqnpd.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtkestizlv.html

C. 函数与作用域
来源：http://dali.chenzaomai.com/Article/details/gtgnwdzxcq.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtgkcydqsj.html

[C01] 定义函数
来源：http://dali.jinqigfzy.top/Article/details/gtooaqdnji.html

Py:   def add(a, b): return a + b
来源：http://dali.redwolf501.top/Article/details/gtbasmrwdb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jiagoushi.top/Article/details/gtnggqllia.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtuaacjlgt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gtamnersmo.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtpbebdawm.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jiagoushi.top/Article/details/gtrydswhla.html

Ruby: def add(a, b); a + b; end
来源：http://dali.chenjidiqi.icu/Article/details/gtwdtvocgn.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gtvxgurzuy.html

[C02] 默认参数
来源：http://dali.feifeiyinyue.top/Article/details/gtqparnvac.html

Py:   def greet(name="World"): return name
来源：http://dali.snrcjt.cn/Article/details/gtpgeccahm.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.kuanghao11.cn/Article/details/gtfstrgxbx.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtopobgrvy.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cqqwz.cn/Article/details/gtuyvxnxyx.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.dashuyun.cn/Article/details/gtjkqvlftq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cashguo.top/Article/details/gtlyoevifq.html

Ruby: def greet(name = "World") = name
来源：http://dali.sysykeji.top/Article/details/gtozqzaacb.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.dashuyun.cn/Article/details/gtwaozstqo.html

[C03] 可变参数
来源：http://dali.zhiwuduotai.top/Article/details/gthxmecsik.html

Py:   def total(*args): return sum(args)
来源：http://dali.yueranfly.top/Article/details/gthswcspzz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.aibaodan.cn/Article/details/gtphgozyqo.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.316326.xyz/Article/details/gtpczhirvw.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhongyouzk.top/Article/details/gtwrdszisn.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hysaishi.cn/Article/details/gtwcqhruxp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.nanxinkj.top/Article/details/gtstdxkxvd.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.aizwys.cn/Article/details/gtygjfdctz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shanyushiyangtech.top/Article/details/gtxugsjdad.html

[C04] 命名参数 / 关键字参数
来源：http://dali.sxryk.cn/Article/details/gtzsdaaizk.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.vqdsnc.cn/Article/details/gtcaqchjza.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.wangshuangyany.cn/Article/details/gttyththmt.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.chenzaomai.com/Article/details/gtsckoecnf.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shzxlz.cn/Article/details/gtlxvzgrqc.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shuidangran.top/Article/details/gtghgqmyfc.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhiwuduotai.top/Article/details/gtrroxqyeg.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yj202588.top/Article/details/gtmycsgsvz.html

C#:   f(a: 1, b: 2)
来源：http://dali.zdqjudy.top/Article/details/gtrtqkbxvh.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gtkfyhudgk.html

Py:   return a, b
来源：http://dali.yueranfly.top/Article/details/gtpzocianw.html

PHP:  return [$a, $b];
来源：http://dali.ppjwa.cn/Article/details/gtvnxdynpe.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ppjwa.cn/Article/details/gtxubznaau.html

TS:   return { a, b };
来源：http://dali.hfpthk.cn/Article/details/gthvclbldy.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.haohaochexian.top/Article/details/gtyhlyytiw.html

Go:   return a, b
来源：http://dali.iojbl.cn/Article/details/gtnudtuhkl.html

Ruby: return a, b
来源：http://dali.iojbl.cn/Article/details/gtmiycfrev.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xuanzx.com/Article/details/gtmpjqsatm.html

[C06] 匿名函数 / lambda
来源：http://dali.quarkkingdee.top/Article/details/gtzazkhrpq.html

Py:   square = lambda x: x * x
来源：http://dali.sxryk.cn/Article/details/gttbgshqah.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yj202588.top/Article/details/gtnowoflxd.html

JS:   const square = x => x * x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnhkbmcjg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yongpay.top/Article/details/gtquwuudzr.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.0kj1m.cn/Article/details/gtwswtddwn.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.0kj1m.cn/Article/details/gtfxjfmevb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yj20258888.top/Article/details/gtyeylushr.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.dashuyun.cn/Article/details/gtjiecalsy.html

[C07] 把函数作为参数传入
来源：http://dali.jinqigufen.top/Article/details/gtremutdqa.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.snrcjt.cn/Article/details/gtzrumllqp.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hywenlv.cn/Article/details/gtnnjllxlm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.316326.xyz/Article/details/gtjmuigcph.html

TS:   arr.map(String)
来源：http://dali.chenjidiqi.icu/Article/details/gtavuwpnnj.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gzhubu.top/Article/details/gtwtkudmst.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jqgufenzy.top/Article/details/gtgimqcyta.html

Ruby: arr.map(&:upcase)
来源：http://dali.gaohongyu789.top/Article/details/gteoajoisj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.nanxinkj.top/Article/details/gtfezbwdnv.html

[C08] 闭包
来源：http://dali.yangfankeji.com/Article/details/gttqmghnln.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jinghuilouyu.cn/Article/details/gtrhqbknwe.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhoulong.xyz/Article/details/gtgutzmuoq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xuetiantiany.cn/Article/details/gtalrtfuig.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.birdmap.top/Article/details/gtzyswzcng.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ehwqpu.com/Article/details/gtqlwfndtx.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cheryme.top/Article/details/gteqnygszr.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.bjfxy.top/Article/details/gteeamtqka.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gogol.net.cn/Article/details/gtoqbhnhsc.html

[C09] 递归
来源：http://dali.jqgfzy.top/Article/details/gtlqplpiem.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yvedp.cn/Article/details/gtacssfkio.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhixingplan.top/Article/details/gtinaekrcl.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.smart0.xyz/Article/details/gttqjfjmxv.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.iojbl.cn/Article/details/gtbusutdzx.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yuxming.cn/Article/details/gtrfzbkdxv.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.fzhhl.top/Article/details/gtorjaiglc.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtlczrfocq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yanxiufei.cn/Article/details/gtmwvbxlrf.html

[C10] 变量作用域
来源：http://dali.hysaishi.cn/Article/details/gtkrrcopfr.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gogol.net.cn/Article/details/gtkthbfuqt.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cheryme.top/Article/details/gtupgkwctb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cdnleiting.top/Article/details/gtfoexkcvh.html

TS:   同 JS
来源：http://dali.ehwqpu.com/Article/details/gtvhbcgocv.html

Java: 方法内为块级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gtuiazgjqj.html

Go:   花括号块级作用域
来源：http://dali.c1oappe.top/Article/details/gtufbcbiqd.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ydzc1.top/Article/details/gtkukkyhot.html

C#:   块级作用域
来源：http://dali.ivvv.top/Article/details/gtfmvbsjzb.html

[C11] 模块导入与导出
来源：http://dali.cqqwz.cn/Article/details/gtaaxpzkke.html

Py:   from module import func
来源：http://dali.yj20258.top/Article/details/gtqoclvggr.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.sysykeji.top/Article/details/gttghubcfj.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xylfe.cn/Article/details/gtqlijmezf.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yj20258.top/Article/details/gtagfmlumt.html

Java: import java.util.List;
来源：http://dali.nanxuanxn.top/Article/details/gtasnptoik.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yj20258.top/Article/details/gtngmlcvty.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yj20258888.top/Article/details/gtzidrvkmr.html

C#:   using System.Text;
来源：http://dali.cucudq.cn/Article/details/gtgxetvopl.html

[C12] 立即执行函数 IIFE
来源：http://dali.shuidangran.top/Article/details/gtvowrvvlc.html

Py:   (lambda: print("run"))()
来源：http://dali.dianchejie.cn/Article/details/gtneofjymh.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yanxiufei.cn/Article/details/gtcazhzqzv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.daxiang520.top/Article/details/gteoqewjxa.html

TS:   (() => { console.log("run"); })();
来源：http://dali.kuanghao11.cn/Article/details/gthwlqsobk.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cheryme.top/Article/details/gthtdqideu.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jyoumei.cn/Article/details/gthfsdiywc.html

Ruby: -> { puts "run" }.call
来源：http://dali.pycfn.com/Article/details/gtcdhmohcx.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hnxiangtu.top/Article/details/gtqhprrmmu.html

[C13] 类型声明 / 类型注解
来源：http://dali.hfpthk.cn/Article/details/gtkgeqizpz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hywenlv.cn/Article/details/gtvzybakyd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guowangkeji.top/Article/details/gtiedqmuin.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.guowangkeji.top/Article/details/gtivwaxazh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gttpkjnwaf.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gtzfmidcny.html

Go:   func add(a, b int) int
来源：http://dali.cheryme.top/Article/details/gtxiuvpqyx.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hongshengwenyu.top/Article/details/gtuumigfse.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.dashuyun.cn/Article/details/gtlablzuza.html

[C14] 泛型函数
来源：http://dali.jinqigufen.top/Article/details/gtkliovtos.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jqgfzy.top/Article/details/gtfrzjgytu.html

PHP:  // 无泛型
来源：http://dali.0kj1m.cn/Article/details/gtblhvxcyp.html

JS:   // 无泛型
来源：http://dali.xziqi.cn/Article/details/gtipuvejgi.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.gzhubu.top/Article/details/gtnkdinhsj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ydzc1.top/Article/details/gtwdyzyuen.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.andypj.xyz/Article/details/gtgljxhlsr.html

Ruby: # 无泛型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqtealfkd.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.kuanghao11.cn/Article/details/gtkzriauyq.html

[C15] 解构 / 展开参数
来源：http://dali.zhixingplan.top/Article/details/gtynpautds.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.tianlin.xyz/Article/details/gtjneyxbky.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hongshengwenyu.top/Article/details/gtusaqjucl.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sufxvd.cn/Article/details/gtafxyftsg.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.nwbrower.top/Article/details/gtjrtyzrwh.html

Java: // 无解构
来源：http://dali.mhx1999.top/Article/details/gttryqwoor.html

Go:   // 无解构
来源：http://dali.havefunace.top/Article/details/gtkcvbsixm.html

Ruby: a, b = pair
来源：http://dali.tian-w.cn/Article/details/gtzctrmpzb.html

C#:   var (a, b) = pair;
来源：http://dali.hongshengwenyu.top/Article/details/gtzngmcusl.html

[C16] 函数 / 方法重载
来源：http://dali.guowangkeji.top/Article/details/gtcvnzoagg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.0kj1m.cn/Article/details/gtgentvklz.html

PHP:  // 无重载
来源：http://dali.jyoumei.cn/Article/details/gtbqddvcdf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhiwuduotai.top/Article/details/gtustcsrtj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.bjfxy.top/Article/details/gtzzrfzssz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.tianlin.xyz/Article/details/gttwllpidv.html

Go:   // 无重载：用不同函数名
来源：http://dali.yvedp.cn/Article/details/gtftdhryze.html

Ruby: # 无重载：靠动态参数
来源：http://dali.nanxuanxn.top/Article/details/gtqwcadrji.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.snrcjt.cn/Article/details/gtpnbptiyb.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtypeyiept.html

D. 数组 / 列表 / 集合
来源：http://dali.shzxlz.cn/Article/details/gthijucupb.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtcrxqxvbm.html

[D01] 创建数组 / 列表
来源：http://dali.wangdashe.top/Article/details/gtmnraxhin.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hysaishi.cn/Article/details/gttponxqal.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zdqjudy.top/Article/details/gtahrxjlqk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yvedp.cn/Article/details/gttaafkbel.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yuanzhike.top/Article/details/gtrolbhphm.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.chenlongwang.top/Article/details/gtnwzfxrte.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hfpthk.cn/Article/details/gtzwqgurlk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.andypj.xyz/Article/details/gthwkkgons.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hysaishi.cn/Article/details/gtlwggaevi.html

[D02] 追加元素到末尾
来源：http://dali.smart0.xyz/Article/details/gtivxudmva.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gogol.net.cn/Article/details/gtncqbckhy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shuidangran.top/Article/details/gtouawdfpb.html

JS:   arr.push(4);
来源：http://dali.9152youxi.cn/Article/details/gtyoxyqfnm.html

TS:   arr.push(4);
来源：http://dali.ppjwa.cn/Article/details/gtgdexvqen.html

Java: list.add(4);
来源：http://dali.gaohongyu789.top/Article/details/gtiytngudh.html

Go:   arr = append(arr, 4)
来源：http://dali.svipenyu.cn/Article/details/gthwtciqud.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zycfv.cn/Article/details/gtfdtxlexn.html

C#:   list.Add(4);
来源：http://dali.shuidangran.top/Article/details/gtbqayiela.html

[D03] 在指定位置插入元素
来源：http://dali.sweek.top/Article/details/gtdyecoxmf.html

Py:   arr.insert(0, 0)
来源：http://dali.daria6918.cn/Article/details/gtrzdyaunv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yueranfly.top/Article/details/gtldheumzl.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cashguo.top/Article/details/gtjfuuceuw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jiagoushi.top/Article/details/gtiesppiqo.html

Java: list.add(0, 0);
来源：http://dali.vqdsnc.cn/Article/details/gtqbqfcydk.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.dashuyun.cn/Article/details/gtxkgjknbc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xuetiantiany.cn/Article/details/gtsagcvjmr.html

C#:   list.Insert(0, 0);
来源：http://dali.pycfn.com/Article/details/gtbzpqkrfk.html

[D04] 删除元素
来源：http://dali.wangdashe.top/Article/details/gtwliyacbc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jianghu66.top/Article/details/gtwwrbimnh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yuanzhike.top/Article/details/gthwyowiql.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hnxiangtu.top/Article/details/gtszbpnaoe.html

TS:   arr.splice(0, 1);
来源：http://dali.wangdashe.top/Article/details/gturszxpjp.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.wangdashe.top/Article/details/gtinxmiaoi.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ppjwa.cn/Article/details/gtytpcnuwl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.bjfxy.top/Article/details/gtpxrdimci.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.nanxuanxn.top/Article/details/gtzyhikviy.html

[D05] 访问与修改元素
来源：http://dali.zdqjudy.top/Article/details/gtisklckyr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangshuangyany.cn/Article/details/gtyxvzhqou.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.smart0.xyz/Article/details/gtafaswajh.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.tanke756.top/Article/details/gtykqaawct.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.wangshuangyany.cn/Article/details/gtsjhlwqlf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ydzc1.top/Article/details/gtmpgeftei.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoqporkhd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxinkj.top/Article/details/gtjbwepkvp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.svipenyu.cn/Article/details/gtgxmifemm.html

[D06] 数组长度
来源：http://dali.hywenlv.cn/Article/details/gtoatujvef.html

Py:   len(arr)
来源：http://dali.ehwqpu.com/Article/details/gtctxwuxxp.html

PHP:  count($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtgxsbbugm.html

JS:   arr.length
来源：http://dali.nanxinkj.top/Article/details/gtwqndnkqq.html

TS:   arr.length
来源：http://dali.sufxvd.cn/Article/details/gtkchocnxb.html

Java: list.size();
来源：http://dali.yj20258.top/Article/details/gtkbkzyfdr.html

Go:   len(arr)
来源：http://dali.gotoacloud.top/Article/details/gtcfwjimzz.html

Ruby: arr.length; arr.size
来源：http://dali.xziqi.cn/Article/details/gthhdxihed.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gtxzhtzfmu.html

[D07] 切片 / 取子数组
来源：http://dali.316326.xyz/Article/details/gtvnsvrkre.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhixingplan.top/Article/details/gtyqurimvx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhengqikj.top/Article/details/gttwjagvql.html

JS:   arr.slice(1, 4);
来源：http://dali.daria6918.cn/Article/details/gtjfoseelg.html

TS:   arr.slice(1, 4);
来源：http://dali.vqdsnc.cn/Article/details/gtlhwcsvwx.html

Java: list.subList(1, 4);
来源：http://dali.tanke756.top/Article/details/gthtweshfk.html

Go:   arr[1:4]
来源：http://dali.pengpengdd.cyou/Article/details/gtneigubsq.html

Ruby: arr[1, 3]
来源：http://dali.jqgufenzy.top/Article/details/gtcbequoyt.html

C#:   list.GetRange(1, 3);
来源：http://dali.ppjwa.cn/Article/details/gtmbubxpni.html

[D08] 合并两个数组
来源：http://dali.zhoulong.xyz/Article/details/gtrbbepbad.html

Py:   a + b;  a.extend(b)
来源：http://dali.shuidangran.top/Article/details/gtwzilakun.html

PHP:  array_merge($a, $b);
来源：http://dali.yueranfly.top/Article/details/gtiqfdxcqo.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.aizwys.cn/Article/details/gtiywuovsd.html

TS:   [...a, ...b];
来源：http://dali.pycfn.com/Article/details/gtkrfkthde.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwdhqoklk.html

Go:   append(a, b...)
来源：http://dali.hywenlv.cn/Article/details/gtfgclcven.html

Ruby: a + b;  a.concat(b)
来源：http://dali.haohaochexian.top/Article/details/gtfgzvhplr.html

C#:   a.Concat(b).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtfaehirsi.html

[D09] 排序（升序）
来源：http://dali.gzhubu.top/Article/details/gtdbjpkuaq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shangyingyoupin.top/Article/details/gtkibtkmbk.html

PHP:  sort($arr);
来源：http://dali.jiagoushi.top/Article/details/gtmnwknwqg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xuetiantiany.cn/Article/details/gtajnqbyvs.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.pengpengdd.cyou/Article/details/gtbkehnpjz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shangyingyoupin.top/Article/details/gtcozkapvl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.316326.xyz/Article/details/gtomlkyarh.html

Ruby: arr.sort
来源：http://dali.jinghuilouyu.cn/Article/details/gtlhkaafqn.html

C#:   list.Sort();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwfazfupk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.chenlongwang.top/Article/details/gtejkmhqqc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cucudq.cn/Article/details/gtmluhrwed.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ydzc1.top/Article/details/gttjxjseth.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cashguo.top/Article/details/gtgtndvxby.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.snrcjt.cn/Article/details/gttcfzvqou.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xuetiantiany.cn/Article/details/gtayjdjzog.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwmfooecy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.daria6918.cn/Article/details/gtmpsrxjmw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.0kj1m.cn/Article/details/gtxihcqdhe.html

[D11] 反转数组
来源：http://dali.guannengcc.top/Article/details/gtffveimqq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zycfv.cn/Article/details/gtwmhqgrle.html

PHP:  array_reverse($arr);
来源：http://dali.ppjwa.cn/Article/details/gtrauvujdm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.bjfxy.top/Article/details/gtgbqhhtsa.html

TS:   [...arr].reverse();
来源：http://dali.jqgfzy.top/Article/details/gtcgttbcpm.html

Java: Collections.reverse(list);
来源：http://dali.shuidangran.top/Article/details/gtlpxbwred.html

Go:   slices.Reverse(arr)
来源：http://dali.cdnleiting.top/Article/details/gtcvorvscy.html

Ruby: arr.reverse
来源：http://dali.zhoulong.xyz/Article/details/gtouagyfkg.html

C#:   list.Reverse();
来源：http://dali.yanxiufei.cn/Article/details/gtjlqmcupc.html

[D12] 查找元素下标
来源：http://dali.shzxlz.cn/Article/details/gtnunbuhhw.html

Py:   arr.index(x);  x in arr
来源：http://dali.gaohongyu789.top/Article/details/gtgptnkxrx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xylfe.cn/Article/details/gtusbvulio.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgfzy.top/Article/details/gtyoawkwsg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gtflxztmuw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gogol.net.cn/Article/details/gtqnfinqhz.html

Go:   slices.Index(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtdzerljga.html

Ruby: arr.index(x)
来源：http://dali.pycfn.com/Article/details/gtqeywceue.html

C#:   list.IndexOf(x);
来源：http://dali.zhixingplan.top/Article/details/gtacrehjhb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hnqzz.top/Article/details/gtbemchhdi.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.pycfn.com/Article/details/gtkzflmgxi.html


<!-- 参考信息 -->