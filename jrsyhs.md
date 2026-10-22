代发 wailian999

PHP:  range(0, 10, 2);
来源：http://dali.andypj.xyz/Article/details/gthhqawrgc.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.snrcjt.cn/Article/details/gtonpftmtm.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.meibo888.top/Article/details/gtwmayexek.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.nwbrower.top/Article/details/gtugbnpgdh.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.dashuyun.cn/Article/details/gtyqcgerax.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jiagoushi.top/Article/details/gtucrbaqtl.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yongpay.top/Article/details/gtsvqeetiq.html

[B12] 跳出多层循环
来源：http://dali.yanxiufei.cn/Article/details/gtwysumrzq.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.iojbl.cn/Article/details/gtqlugqenm.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cucudq.cn/Article/details/gtizjzkrum.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcdsmaevi.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hammf.cn/Article/details/gttxfgakrk.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.9152youxi.cn/Article/details/gtyvlcvlgm.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jiagoushi.top/Article/details/gtkapadrqb.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.wangdashe.top/Article/details/gtnxbbazem.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.guannengcc.top/Article/details/gtcqomvhfs.html

[B13] 判断是否为数字
来源：http://dali.yj20258888.top/Article/details/gtdnxpgyuy.html

Py:   isinstance(x, (int, float))
来源：http://dali.xylfe.cn/Article/details/gtfofkwpiu.html

PHP:  is_numeric($x)
来源：http://dali.hongshengwenyu.top/Article/details/gtbvzcyewi.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jiagoushi.top/Article/details/gtvpiwmruc.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtxgvqpmgr.html

Java: x instanceof Number
来源：http://dali.zhixingplan.top/Article/details/gtiauymaqn.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.dashuyun.cn/Article/details/gteqhfdovj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hnqzz.top/Article/details/gtjlyelnso.html

C#:   x is int or double or decimal
来源：http://dali.chenlongwang.top/Article/details/gtorzdjpff.html

[B14] 判断值是否在集合内
来源：http://dali.yuxming.cn/Article/details/gtkgwfekal.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yvedp.cn/Article/details/gtegumszqm.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.chenjidiqi.icu/Article/details/gtnucfycjh.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jqgfzy.top/Article/details/gtbxeptwmy.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gttwnpfrfa.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.meibo888.top/Article/details/gtartxbzaf.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.wangdashe.top/Article/details/gtwwnyrflg.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yuanzhike.top/Article/details/gtvuqohalb.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yonumen.top/Article/details/gtsmqvadwj.html

[B15] 布尔运算与取反
来源：http://dali.yj20258.top/Article/details/gttpwjujfe.html

Py:   a and b or not c
来源：http://dali.cucudq.cn/Article/details/gtvfoemztw.html

PHP:  $a && $b || !$c
来源：http://dali.guowangkeji.top/Article/details/gtdqiavfjw.html

JS:   a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gtkfkpqbsh.html

TS:   a && b || !c
来源：http://dali.9152youxi.cn/Article/details/gtaczxzksg.html

Java: a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gtecmeobxk.html

Go:   a && b || !c
来源：http://dali.xinyue.icu/Article/details/gtvnyvfhjy.html

Ruby: a && b || !c
来源：http://dali.redwolf501.top/Article/details/gtkdahvqhf.html

C#:   a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gtzarnzcku.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yuxming.cn/Article/details/gtnhnlbpij.html

Py:   if not data: return
来源：http://dali.zhengqikj.top/Article/details/gtvcqkuxdf.html

PHP:  if (!$data) { return; }
来源：http://dali.jiagoushi.top/Article/details/gtyoiwzueu.html

JS:   if (!data) return;
来源：http://dali.yvedp.cn/Article/details/gteuxyvkik.html

TS:   if (!data) return;
来源：http://dali.cqqwz.cn/Article/details/gtpgzhctqo.html

Java: if (data == null) return;
来源：http://dali.dashuyun.cn/Article/details/gtygxmepaq.html

Go:   if data == nil { return }
来源：http://dali.ydzc1.top/Article/details/gtlkjleepq.html

Ruby: return if data.nil?
来源：http://dali.chenjidiqi.icu/Article/details/gtivbnyvds.html

C#:   if (data == null) return;
来源：http://dali.0kj1m.cn/Article/details/gthawjyaql.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtyeoqnwja.html

C. 函数与作用域
来源：http://dali.hammf.cn/Article/details/gtpgkgnqkh.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtxdxxgzte.html

[C01] 定义函数
来源：http://dali.pycfn.com/Article/details/gtovqjqgbt.html

Py:   def add(a, b): return a + b
来源：http://dali.gotoacloud.top/Article/details/gtbtroqodc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aibaodan.cn/Article/details/gtrueoqgjm.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gtlaqlwgmp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gtoayirvsm.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtvlhqzvje.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yvedp.cn/Article/details/gtavdulsjx.html

Ruby: def add(a, b); a + b; end
来源：http://dali.haohaochexian.top/Article/details/gtdhmzsvjy.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gtsuieibok.html

[C02] 默认参数
来源：http://dali.c1oappe.top/Article/details/gtwvojvvvh.html

Py:   def greet(name="World"): return name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbrpcnjiq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hysaishi.cn/Article/details/gtaacbufbg.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtxdkltabv.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtdloasota.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.wangdashe.top/Article/details/gtdepykxcw.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hfpthk.cn/Article/details/gthbrihntf.html

Ruby: def greet(name = "World") = name
来源：http://dali.xinyue.icu/Article/details/gtnfyolbnv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.smart0.xyz/Article/details/gtsqkjcrtj.html

[C03] 可变参数
来源：http://dali.cqqwz.cn/Article/details/gtiekmrkyr.html

Py:   def total(*args): return sum(args)
来源：http://dali.guowangkeji.top/Article/details/gtihoxgddy.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hfpthk.cn/Article/details/gtksbfcahc.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xziqi.cn/Article/details/gtnnhtyuwf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.feifeiyinyue.top/Article/details/gtqnjgskvk.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.dashuyun.cn/Article/details/gtcwgylald.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.shangyingyoupin.top/Article/details/gtkpqcrnkl.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.quarkkingdee.top/Article/details/gtvhyqieqn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jinqigfzy.top/Article/details/gtvpuifzpi.html

[C04] 命名参数 / 关键字参数
来源：http://dali.0kj1m.cn/Article/details/gtnjnqbuns.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.feifeiyinyue.top/Article/details/gtkzloogje.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hywenlv.cn/Article/details/gtjjfutxxw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhoulong.xyz/Article/details/gtbtfwdmnx.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cheryme.top/Article/details/gtkznxjklm.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhengqikj.top/Article/details/gtwtmbfjeq.html

Go:   // 无：用配置结构体参数
来源：http://dali.tian-w.cn/Article/details/gtmaorulup.html

Ruby: f(a: 1, b: 2)
来源：http://dali.guowangkeji.top/Article/details/gtlpgxkkec.html

C#:   f(a: 1, b: 2)
来源：http://dali.mhx1999.top/Article/details/gtfpiurapv.html

[C05] 返回多个值
来源：http://dali.wangdashe.top/Article/details/gtxrzpxqfy.html

Py:   return a, b
来源：http://dali.daria6918.cn/Article/details/gthbrbryyq.html

PHP:  return [$a, $b];
来源：http://dali.zhiwuduotai.top/Article/details/gtjngmpvqj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shangyingyoupin.top/Article/details/gtdlejmfqg.html

TS:   return { a, b };
来源：http://dali.9152youxi.cn/Article/details/gtbsidfpwj.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.meibo888.top/Article/details/gthljjesbr.html

Go:   return a, b
来源：http://dali.tian-w.cn/Article/details/gttfvotulk.html

Ruby: return a, b
来源：http://dali.yueranfly.top/Article/details/gtnlzuahoj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.kuanghao11.cn/Article/details/gtwfffumhg.html

[C06] 匿名函数 / lambda
来源：http://dali.shangyingyoupin.top/Article/details/gttopuqatv.html

Py:   square = lambda x: x * x
来源：http://dali.shangyingyoupin.top/Article/details/gthpllmwtd.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.daria6918.cn/Article/details/gtuwxoeyxf.html

JS:   const square = x => x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gtlasgrczd.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jyoumei.cn/Article/details/gtfsrzgewf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xinyue.icu/Article/details/gtwdtarxzb.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.gogol.net.cn/Article/details/gtovrihawg.html

Ruby: square = ->(x) { x * x }
来源：http://dali.9152youxi.cn/Article/details/gtxpqdxeji.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.kuanghao11.cn/Article/details/gtgtxjrhqs.html

[C07] 把函数作为参数传入
来源：http://dali.guannengcc.top/Article/details/gtactaglcp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.gzhubu.top/Article/details/gtusyfatcs.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtfpbhhwja.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.daxiang520.top/Article/details/gtvenccckp.html

TS:   arr.map(String)
来源：http://dali.nanxinkj.top/Article/details/gtvnjhadwn.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtshujnayg.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ehwqpu.com/Article/details/gtasspqyve.html

Ruby: arr.map(&:upcase)
来源：http://dali.snrcjt.cn/Article/details/gtfntlobjp.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.sxryk.cn/Article/details/gtwdidivzm.html

[C08] 闭包
来源：http://dali.ppjwa.cn/Article/details/gteqzbvahm.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.havefunace.top/Article/details/gttsqhjvcn.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttplktlzm.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.dianchejie.cn/Article/details/gtaiwxveuq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.tianlin.xyz/Article/details/gtghhhsqiv.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.bjfxy.top/Article/details/gtriziwixe.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.mhx1999.top/Article/details/gttuilpsxx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yj20258.top/Article/details/gtwprerfqc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jinqigufen.top/Article/details/gtbjrfqfbm.html

[C09] 递归
来源：http://dali.birdmap.top/Article/details/gtjkikimkx.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yuanzhike.top/Article/details/gtaqvaoddo.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ybcxt.top/Article/details/gtipmrgoeg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.fengsongda.top/Article/details/gtgbbyupfv.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cdnleiting.top/Article/details/gtgydsgxvs.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.bjfxy.top/Article/details/gttpzcqnnu.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhiwuduotai.top/Article/details/gtrkoaumuw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ppjwa.cn/Article/details/gtogxqesoi.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xylfe.cn/Article/details/gtfoerdjue.html

[C10] 变量作用域
来源：http://dali.sweek.top/Article/details/gtcrtrxfgn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.shzxlz.cn/Article/details/gtgujepzxe.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.gzhubu.top/Article/details/gtfgjidyvh.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.nanxinkj.top/Article/details/gtueyygykl.html

TS:   同 JS
来源：http://dali.mhx1999.top/Article/details/gtytwwpbtp.html

Java: 方法内为块级作用域
来源：http://dali.yanxiufei.cn/Article/details/gtaaggmbgf.html

Go:   花括号块级作用域
来源：http://dali.yvedp.cn/Article/details/gtkjgdoovw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shangyingyoupin.top/Article/details/gtesunodzo.html

C#:   块级作用域
来源：http://dali.tanke756.top/Article/details/gtskakiulb.html

[C11] 模块导入与导出
来源：http://dali.pycfn.com/Article/details/gtzxwznkhp.html

Py:   from module import func
来源：http://dali.sysykeji.top/Article/details/gtxwsbjstp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xylfe.cn/Article/details/gtciqsvvlh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.quarkkingdee.top/Article/details/gtxfejnkmz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jqgufenzy.top/Article/details/gterpiuryk.html

Java: import java.util.List;
来源：http://dali.yonumen.top/Article/details/gtmobtzyyq.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinyuanbaomall.cn/Article/details/gtemqyamgq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ppjwa.cn/Article/details/gtqrjznoup.html

C#:   using System.Text;
来源：http://dali.xuetiantiany.cn/Article/details/gtlanwaryi.html

[C12] 立即执行函数 IIFE
来源：http://dali.yj202588.top/Article/details/gtqtcmjdww.html

Py:   (lambda: print("run"))()
来源：http://dali.sysykeji.top/Article/details/gtmkdhdmam.html

PHP:  (function () { echo "run"; })();
来源：http://dali.sufxvd.cn/Article/details/gtbpctfzmu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.quarkkingdee.top/Article/details/gtzudskzkd.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hysaishi.cn/Article/details/gtiijfocgv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinqigfzy.top/Article/details/gtvdluhecg.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.havefunace.top/Article/details/gtuxqwlqnk.html

Ruby: -> { puts "run" }.call
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvwfdvcqp.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.chenlongwang.top/Article/details/gtipirkzcj.html

[C13] 类型声明 / 类型注解
来源：http://dali.chenlongwang.top/Article/details/gtpwihiqem.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jinyuanbaomall.cn/Article/details/gthnoxyssv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dashuyun.cn/Article/details/gtyrwwilhx.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zdqjudy.top/Article/details/gtivjdwhnh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gttjwdosce.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtddfcswrk.html

Go:   func add(a, b int) int
来源：http://dali.guowangkeji.top/Article/details/gtovdbfzwk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cheryme.top/Article/details/gtplxagtdw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.daria6918.cn/Article/details/gtmemwpppx.html

[C14] 泛型函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzhqgvqkk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.tianlin.xyz/Article/details/gtoyjzgtop.html

PHP:  // 无泛型
来源：http://dali.guowangkeji.top/Article/details/gtrtjwkshu.html

JS:   // 无泛型
来源：http://dali.nanxuanxn.top/Article/details/gtarapmgjv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hysaishi.cn/Article/details/gtleowjfrj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.fengsongda.top/Article/details/gtjztmbqrl.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrfnwqvqv.html

Ruby: # 无泛型
来源：http://dali.xinyue.icu/Article/details/gtedehrnwa.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjwjpdugr.html

[C15] 解构 / 展开参数
来源：http://dali.redwolf501.top/Article/details/gtzujjiuvm.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ybcxt.top/Article/details/gtxhaoakvb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xinyue.icu/Article/details/gtfrfnhqwv.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhoulong.xyz/Article/details/gtcrabakid.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.fzhhl.top/Article/details/gthjralpxs.html

Java: // 无解构
来源：http://dali.sysykeji.top/Article/details/gtlrtdwelp.html

Go:   // 无解构
来源：http://dali.hongshengwenyu.top/Article/details/gtrmlwdwud.html

Ruby: a, b = pair
来源：http://dali.tanke756.top/Article/details/gtlnghdenh.html

C#:   var (a, b) = pair;
来源：http://dali.nanxinkj.top/Article/details/gtrelnxuln.html

[C16] 函数 / 方法重载
来源：http://dali.zycfv.cn/Article/details/gthnavcyts.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.daxiang520.top/Article/details/gtxjbaxhen.html

PHP:  // 无重载
来源：http://dali.jiagoushi.top/Article/details/gtiyohcdjd.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.haohaochexian.top/Article/details/gtopmdmdyu.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gzhubu.top/Article/details/gtprjeviap.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgisqlnou.html

Go:   // 无重载：用不同函数名
来源：http://dali.yj202588.top/Article/details/gtbrhjshay.html

Ruby: # 无重载：靠动态参数
来源：http://dali.chenzaomai.com/Article/details/gtxanpwuqz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtgufokvxd.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtcrrjetfo.html

D. 数组 / 列表 / 集合
来源：http://dali.feifeiyinyue.top/Article/details/gtzmjxhewp.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtpscygofb.html

[D01] 创建数组 / 列表
来源：http://dali.shzxlz.cn/Article/details/gtyhsngypb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hysaishi.cn/Article/details/gtxwbirmma.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.havefunace.top/Article/details/gtlstpkrhk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.smart0.xyz/Article/details/gtjaxhpayd.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.svipenyu.cn/Article/details/gtvjxruppu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.sweek.top/Article/details/gtgkrevxdt.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.vqdsnc.cn/Article/details/gtnnbovutv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hysaishi.cn/Article/details/gtycwtxqhy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.pycfn.com/Article/details/gtgfdzaflv.html

[D02] 追加元素到末尾
来源：http://dali.fzhhl.top/Article/details/gtxbywkdhi.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.chenjidiqi.icu/Article/details/gtzytaxwas.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhiwuduotai.top/Article/details/gtziojivll.html

JS:   arr.push(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtobezzrgs.html

TS:   arr.push(4);
来源：http://dali.ppjwa.cn/Article/details/gtlualgdln.html

Java: list.add(4);
来源：http://dali.wangshuangyany.cn/Article/details/gtqllvftli.html

Go:   arr = append(arr, 4)
来源：http://dali.daxiang520.top/Article/details/gtjgblgkcb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqowqpmuq.html

C#:   list.Add(4);
来源：http://dali.zhixingplan.top/Article/details/gtwtvgomyh.html

[D03] 在指定位置插入元素
来源：http://dali.shzxlz.cn/Article/details/gtpjzahrup.html

Py:   arr.insert(0, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtqfqklabv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.chenjidiqi.icu/Article/details/gtqrlrfphj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.svipenyu.cn/Article/details/gtqidvdmen.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.nanxinkj.top/Article/details/gtkwbtyisv.html

Java: list.add(0, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdpqklkxw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.bjfxy.top/Article/details/gtkcumgyzz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtptyrvpol.html

C#:   list.Insert(0, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtzebyafst.html

[D04] 删除元素
来源：http://dali.ydzc1.top/Article/details/gtivkjrrab.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.dianchejie.cn/Article/details/gtdmmbepfh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yj202588.top/Article/details/gtutbqcqdh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xziqi.cn/Article/details/gtypnlhvle.html

TS:   arr.splice(0, 1);
来源：http://dali.nwbrower.top/Article/details/gtmhjnyuhb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.chenlongwang.top/Article/details/gtdgabdibs.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gtrgbuoddr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hnqzz.top/Article/details/gttpacotxb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.9152youxi.cn/Article/details/gtjspbnlqz.html

[D05] 访问与修改元素
来源：http://dali.zdqjudy.top/Article/details/gtfloioufo.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhixingplan.top/Article/details/gtveqedqli.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cheryme.top/Article/details/gtrqdwsewy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yanxiufei.cn/Article/details/gtowsvwjij.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ybcxt.top/Article/details/gtufcmvhsz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.daxiang520.top/Article/details/gtfotfdwyv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ydzc1.top/Article/details/gtfzueojcj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.dashuyun.cn/Article/details/gtozzqjtuv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yj202588.top/Article/details/gtvwzxbgxs.html

[D06] 数组长度
来源：http://dali.mhx1999.top/Article/details/gtcklihqrp.html

Py:   len(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtzpafukxs.html

PHP:  count($arr);
来源：http://dali.jiagoushi.top/Article/details/gtyuixsijz.html

JS:   arr.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpjneraxs.html

TS:   arr.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwquumnpd.html

Java: list.size();
来源：http://dali.birdmap.top/Article/details/gtbawrrgcw.html

Go:   len(arr)
来源：http://dali.yj202588.top/Article/details/gtswfetahp.html

Ruby: arr.length; arr.size
来源：http://dali.hnqzz.top/Article/details/gtygozjesk.html

C#:   list.Count;
来源：http://dali.tian-w.cn/Article/details/gtuvaexrrf.html

[D07] 切片 / 取子数组
来源：http://dali.dianchejie.cn/Article/details/gtkphkmhfz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.havefunace.top/Article/details/gthnrbagte.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yonumen.top/Article/details/gtjyqajqef.html

JS:   arr.slice(1, 4);
来源：http://dali.hywenlv.cn/Article/details/gtlsrrfghe.html

TS:   arr.slice(1, 4);
来源：http://dali.iojbl.cn/Article/details/gtzfisofwi.html

Java: list.subList(1, 4);
来源：http://dali.fzhhl.top/Article/details/gtmxecfekl.html

Go:   arr[1:4]
来源：http://dali.nwbrower.top/Article/details/gtpqtokwud.html

Ruby: arr[1, 3]
来源：http://dali.shanyushiyangtech.top/Article/details/gteondarrl.html

C#:   list.GetRange(1, 3);
来源：http://dali.iojbl.cn/Article/details/gtyfeilteb.html

[D08] 合并两个数组
来源：http://dali.guannengcc.top/Article/details/gtqaqvfops.html

Py:   a + b;  a.extend(b)
来源：http://dali.tian-w.cn/Article/details/gtbuedacyp.html

PHP:  array_merge($a, $b);
来源：http://dali.smart0.xyz/Article/details/gtcmezmyih.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shangyingyoupin.top/Article/details/gtcgapdmjf.html

TS:   [...a, ...b];
来源：http://dali.daxiang520.top/Article/details/gtbdrsbdui.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.tianlin.xyz/Article/details/gtouobyqjc.html

Go:   append(a, b...)
来源：http://dali.hammf.cn/Article/details/gtqnykcgdd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.pengpengdd.cyou/Article/details/gtsgjljhfq.html

C#:   a.Concat(b).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtfbnubapa.html

[D09] 排序（升序）
来源：http://dali.vqdsnc.cn/Article/details/gtyudlfvxq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ehwqpu.com/Article/details/gteixrtgno.html

PHP:  sort($arr);
来源：http://dali.jyoumei.cn/Article/details/gtnjsbjjni.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhaomingkeji.xyz/Article/details/gttbdfajzw.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ydzc1.top/Article/details/gthsitpkwf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gogol.net.cn/Article/details/gtwiebrmfd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkzyigrku.html

Ruby: arr.sort
来源：http://dali.guowangkeji.top/Article/details/gtfjmzctxz.html

C#:   list.Sort();
来源：http://dali.yongpay.top/Article/details/gtdnnjgkfw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cheryme.top/Article/details/gtfzevyygs.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xinyue.icu/Article/details/gttmtyifhz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.quarkkingdee.top/Article/details/gttacqafbj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fzhhl.top/Article/details/gtpalsuaxq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.mhx1999.top/Article/details/gtyqmfexgj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jqgfzy.top/Article/details/gtcbxvljwk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.meibo888.top/Article/details/gtrprxtbyo.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhiwuduotai.top/Article/details/gtesblfdcp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxmqfiqpo.html

[D11] 反转数组
来源：http://dali.hnqzz.top/Article/details/gtzkjqczfr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.gotoacloud.top/Article/details/gtsujsifhn.html

PHP:  array_reverse($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtjbchroel.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yj20258888.top/Article/details/gtantuspgo.html

TS:   [...arr].reverse();
来源：http://dali.havefunace.top/Article/details/gtzvdiggeo.html

Java: Collections.reverse(list);
来源：http://dali.svipenyu.cn/Article/details/gtfdczuout.html

Go:   slices.Reverse(arr)
来源：http://dali.cucudq.cn/Article/details/gtclnvhqoy.html

Ruby: arr.reverse
来源：http://dali.yueranfly.top/Article/details/gtauztvzjl.html


<!-- 参考信息 -->