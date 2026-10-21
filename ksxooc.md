代发 wailian999

PHP:  range(0, 10, 2);
来源：http://dali.0kj1m.cn/Article/details/gtbbuggfdt.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yanxiufei.cn/Article/details/gtsxutcrac.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jlsjyb.cn/Article/details/gtbhfresjp.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.vqdsnc.cn/Article/details/gthequkjsa.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhengqikj.top/Article/details/gtywziflfp.html

Ruby: (0...10).step(2).to_a
来源：http://dali.shangyingyoupin.top/Article/details/gtpxnbivfj.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shuidangran.top/Article/details/gtwmmerler.html

[B12] 跳出多层循环
来源：http://dali.pengpengdd.cyou/Article/details/gtjvjrzjai.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xinyue.icu/Article/details/gtyluiwjlz.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdpgwvrbs.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jlsjyb.cn/Article/details/gtuyoglmsf.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenzaomai.com/Article/details/gtlykzbkua.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.tian-w.cn/Article/details/gtxvtgpolr.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yueranfly.top/Article/details/gtphxjqail.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.nwbrower.top/Article/details/gtrugqgapf.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.chenlongwang.top/Article/details/gtywmpzvga.html

[B13] 判断是否为数字
来源：http://dali.shuidangran.top/Article/details/gtkgcpzgay.html

Py:   isinstance(x, (int, float))
来源：http://dali.smart0.xyz/Article/details/gtwlyvlyfv.html

PHP:  is_numeric($x)
来源：http://dali.316326.xyz/Article/details/gtzbnpvxtu.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zycfv.cn/Article/details/gtirbxrwki.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqposspyh.html

Java: x instanceof Number
来源：http://dali.zhoulong.xyz/Article/details/gtudulvtqy.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cashguo.top/Article/details/gttvuhlvuc.html

Ruby: x.is_a?(Numeric)
来源：http://dali.cqqwz.cn/Article/details/gtxrinlonf.html

C#:   x is int or double or decimal
来源：http://dali.0kj1m.cn/Article/details/gtnswcmwcl.html

[B14] 判断值是否在集合内
来源：http://dali.cheryme.top/Article/details/gtnlqypodq.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.vqdsnc.cn/Article/details/gtdttldjui.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.tianlin.xyz/Article/details/gthwxfuhkl.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.svipenyu.cn/Article/details/gtumufvjnt.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hywenlv.cn/Article/details/gtkkyouprs.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhiwuduotai.top/Article/details/gthcwtoalh.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.daxiang520.top/Article/details/gtnevkzbwb.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.haohaochexian.top/Article/details/gthwboynzo.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xinyue.icu/Article/details/gtqygtsctn.html

[B15] 布尔运算与取反
来源：http://dali.jinqigfzy.top/Article/details/gtqlnsiuuy.html

Py:   a and b or not c
来源：http://dali.0kj1m.cn/Article/details/gteniputmn.html

PHP:  $a && $b || !$c
来源：http://dali.cucudq.cn/Article/details/gtgaimcyev.html

JS:   a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gtmnrnyzrj.html

TS:   a && b || !c
来源：http://dali.redwolf501.top/Article/details/gtlcdkjcxj.html

Java: a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gtnofshtoi.html

Go:   a && b || !c
来源：http://dali.xziqi.cn/Article/details/gtxwpiozcy.html

Ruby: a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gtumfjoims.html

C#:   a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gtcpnytupt.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hongshengwenyu.top/Article/details/gtglgmumcq.html

Py:   if not data: return
来源：http://dali.yj20258888.top/Article/details/gtxgxjnqfu.html

PHP:  if (!$data) { return; }
来源：http://dali.fengsongda.top/Article/details/gthbanxpmh.html

JS:   if (!data) return;
来源：http://dali.zhongyouzk.top/Article/details/gtglzaylqw.html

TS:   if (!data) return;
来源：http://dali.dashuyun.cn/Article/details/gtwjanqlnr.html

Java: if (data == null) return;
来源：http://dali.aizwys.cn/Article/details/gtotdhizkw.html

Go:   if data == nil { return }
来源：http://dali.cheryme.top/Article/details/gtfastspsi.html

Ruby: return if data.nil?
来源：http://dali.yongpay.top/Article/details/gtirzfqnwt.html

C#:   if (data == null) return;
来源：http://dali.hongshengwenyu.top/Article/details/gtkzlissno.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtwmriizou.html

C. 函数与作用域
来源：http://dali.xuetiantiany.cn/Article/details/gtxebcjayy.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtlbjowbzg.html

[C01] 定义函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvpvrblqf.html

Py:   def add(a, b): return a + b
来源：http://dali.ybcxt.top/Article/details/gtevcvusfa.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xinyue.icu/Article/details/gtqebrgutf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthgslffdh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtrpusznnd.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkapxitpl.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jqgufenzy.top/Article/details/gtgotcxwok.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jianghu66.top/Article/details/gteaaxgomg.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gtpmkatals.html

[C02] 默认参数
来源：http://dali.yuxming.cn/Article/details/gtprobkqks.html

Py:   def greet(name="World"): return name
来源：http://dali.wangdashe.top/Article/details/gtheksizry.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xuanzx.com/Article/details/gtpsmwcjsi.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.guannengcc.top/Article/details/gtheqsicev.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gtxvaciceu.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yuxming.cn/Article/details/gtjftzgqci.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.kuanghao11.cn/Article/details/gtvxhbpyjh.html

Ruby: def greet(name = "World") = name
来源：http://dali.aibaodan.cn/Article/details/gtkpgforys.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.nwbrower.top/Article/details/gtcgxnqxtr.html

[C03] 可变参数
来源：http://dali.jianghu66.top/Article/details/gtaochdgwn.html

Py:   def total(*args): return sum(args)
来源：http://dali.yangfankeji.com/Article/details/gtqypxpver.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.redwolf501.top/Article/details/gtkkdjzxbx.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.kuanghao11.cn/Article/details/gtavwglofj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.iojbl.cn/Article/details/gtnyxrsogi.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.guowangkeji.top/Article/details/gtzjowgkya.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.bjfxy.top/Article/details/gtrsuqsmdh.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xinyue.icu/Article/details/gtyimypfzo.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shuidangran.top/Article/details/gtpfreints.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hnqzz.top/Article/details/gtudtozzxf.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jyoumei.cn/Article/details/gtjspunfqo.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.daxiang520.top/Article/details/gtgptfslnu.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.gotoacloud.top/Article/details/gtffbipiui.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.316326.xyz/Article/details/gtlkdkjkoc.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shangyingyoupin.top/Article/details/gthtpzqeog.html

Go:   // 无：用配置结构体参数
来源：http://dali.daria6918.cn/Article/details/gtvoyktmhg.html

Ruby: f(a: 1, b: 2)
来源：http://dali.nanxuanxn.top/Article/details/gtykzdfohw.html

C#:   f(a: 1, b: 2)
来源：http://dali.jinqigufen.top/Article/details/gtmsfwiwmv.html

[C05] 返回多个值
来源：http://dali.nwbrower.top/Article/details/gthljfkzje.html

Py:   return a, b
来源：http://dali.wangshuangyany.cn/Article/details/gtxpqtyyfb.html

PHP:  return [$a, $b];
来源：http://dali.nanxuanxn.top/Article/details/gtuxkaxvdu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cdnleiting.top/Article/details/gtswtoliso.html

TS:   return { a, b };
来源：http://dali.ivvv.top/Article/details/gtmlxbohlo.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.9152youxi.cn/Article/details/gttgcrvvue.html

Go:   return a, b
来源：http://dali.havefunace.top/Article/details/gtpiiifbqz.html

Ruby: return a, b
来源：http://dali.iojbl.cn/Article/details/gtpdbssocy.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbqgqldag.html

[C06] 匿名函数 / lambda
来源：http://dali.ydzc1.top/Article/details/gthtqcwhwj.html

Py:   square = lambda x: x * x
来源：http://dali.svipenyu.cn/Article/details/gtuaxvxsoc.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.birdmap.top/Article/details/gtaoknyvqn.html

JS:   const square = x => x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gtvkzwpkrm.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shzxlz.cn/Article/details/gtczcuygrs.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.cdnleiting.top/Article/details/gtrcasljov.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ivvv.top/Article/details/gtylnlzdca.html

Ruby: square = ->(x) { x * x }
来源：http://dali.nwbrower.top/Article/details/gtcmncgkmq.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ehwqpu.com/Article/details/gtdelgtdxv.html

[C07] 把函数作为参数传入
来源：http://dali.cdnleiting.top/Article/details/gtvsqssfvd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthdqqctfb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sxryk.cn/Article/details/gtcytcezvi.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jianghu66.top/Article/details/gthaheyruk.html

TS:   arr.map(String)
来源：http://dali.iojbl.cn/Article/details/gtvpjnjbhr.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhengqikj.top/Article/details/gtatiuacpc.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.snrcjt.cn/Article/details/gtutirivsg.html

Ruby: arr.map(&:upcase)
来源：http://dali.jqgfzy.top/Article/details/gtympetdnr.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwtlhstdk.html

[C08] 闭包
来源：http://dali.daxiang520.top/Article/details/gtnfouqrer.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yonumen.top/Article/details/gtrplkivdb.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yj20258.top/Article/details/gtreumpufv.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.gzhubu.top/Article/details/gtmiazzobn.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.shzxlz.cn/Article/details/gtmvvixypb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.bjfxy.top/Article/details/gtiutrnwtq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yangfankeji.com/Article/details/gtznreenru.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zycfv.cn/Article/details/gtiibbjlfp.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhengqikj.top/Article/details/gtwbcncxva.html

[C09] 递归
来源：http://dali.chenzaomai.com/Article/details/gtbbbovwvf.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.meibo888.top/Article/details/gtryvofzct.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.meibo888.top/Article/details/gtnrqhtjve.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.aizwys.cn/Article/details/gtawczteee.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hfpthk.cn/Article/details/gtvysbpgwg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yuxming.cn/Article/details/gtoudpgpef.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.fzhhl.top/Article/details/gtvkletjyd.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yueranfly.top/Article/details/gttlqknmqs.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.chenzaomai.com/Article/details/gtybsjcwfh.html

[C10] 变量作用域
来源：http://dali.sweek.top/Article/details/gtpppmscbn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhoulong.xyz/Article/details/gtnnxtrbgv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shanyushiyangtech.top/Article/details/gtxkcaafkf.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcvnyxryo.html

TS:   同 JS
来源：http://dali.cheryme.top/Article/details/gtcllgfpel.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gtzyxkzyrt.html

Go:   花括号块级作用域
来源：http://dali.shuidangran.top/Article/details/gtyeclnrcj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.gaohongyu789.top/Article/details/gtmojtvmqw.html

C#:   块级作用域
来源：http://dali.jianghu66.top/Article/details/gtdgtwmkmb.html

[C11] 模块导入与导出
来源：http://dali.guowangkeji.top/Article/details/gtoctkycck.html

Py:   from module import func
来源：http://dali.bjfxy.top/Article/details/gtvyixqgry.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.snrcjt.cn/Article/details/gtzsrhnsek.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.quarkkingdee.top/Article/details/gtdldgnmoi.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhiwuduotai.top/Article/details/gtqnhjbzbd.html

Java: import java.util.List;
来源：http://dali.chenlongwang.top/Article/details/gtoavinwhr.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtptewixuv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.bjfxy.top/Article/details/gtboudevrh.html

C#:   using System.Text;
来源：http://dali.yongpay.top/Article/details/gtuiklzgpz.html

[C12] 立即执行函数 IIFE
来源：http://dali.chenjidiqi.icu/Article/details/gtmaoqvawi.html

Py:   (lambda: print("run"))()
来源：http://dali.jqgufenzy.top/Article/details/gtsnsirlvt.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xylfe.cn/Article/details/gthzjnxsey.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ydzc1.top/Article/details/gtsxddltrt.html

TS:   (() => { console.log("run"); })();
来源：http://dali.9152youxi.cn/Article/details/gtoiijhkio.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.pycfn.com/Article/details/gtcqagyggh.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zdqjudy.top/Article/details/gtnxdpkaka.html

Ruby: -> { puts "run" }.call
来源：http://dali.yanxiufei.cn/Article/details/gtqtgwlxty.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jinqigfzy.top/Article/details/gtsmlsckhr.html

[C13] 类型声明 / 类型注解
来源：http://dali.hysaishi.cn/Article/details/gtnxfaayzp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sufxvd.cn/Article/details/gttdlegsjn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gtiuthpvlt.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtexlyrxvs.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gtijthvzbu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtwoduqzre.html

Go:   func add(a, b int) int
来源：http://dali.shangyingyoupin.top/Article/details/gtknlutibo.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.wangdashe.top/Article/details/gtsrnvvpaf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.pycfn.com/Article/details/gtpjphufum.html

[C14] 泛型函数
来源：http://dali.zhoulong.xyz/Article/details/gttmksppyr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.tian-w.cn/Article/details/gtwfhjborq.html

PHP:  // 无泛型
来源：http://dali.haohaochexian.top/Article/details/gtkwsssfja.html

JS:   // 无泛型
来源：http://dali.tanke756.top/Article/details/gtvmqclzrv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhoulong.xyz/Article/details/gtwezaidrq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.aibaodan.cn/Article/details/gtsrllpids.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hnqzz.top/Article/details/gtqsclqguh.html

Ruby: # 无泛型
来源：http://dali.jianghu66.top/Article/details/gtdbzlwyyq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.fzhhl.top/Article/details/gtvxremyam.html

[C15] 解构 / 展开参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsebhvwkh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ivvv.top/Article/details/gtvjkfzhff.html

PHP:  [$a, $b] = $pair;
来源：http://dali.tanke756.top/Article/details/gtbudkjtpp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sxryk.cn/Article/details/gtjlksyetk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.dashuyun.cn/Article/details/gtkazejjuo.html

Java: // 无解构
来源：http://dali.iojbl.cn/Article/details/gtbbstkcfh.html

Go:   // 无解构
来源：http://dali.jlsjyb.cn/Article/details/gtksmdusbr.html

Ruby: a, b = pair
来源：http://dali.nanxinkj.top/Article/details/gtjcragzjt.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gtvbmvrxam.html

[C16] 函数 / 方法重载
来源：http://dali.wangdashe.top/Article/details/gttukbvzrh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yonumen.top/Article/details/gtuglfaebc.html

PHP:  // 无重载
来源：http://dali.kuanghao11.cn/Article/details/gtngerfwff.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.redwolf501.top/Article/details/gtbrahgnnh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.nanxuanxn.top/Article/details/gthuonlyii.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yanxiufei.cn/Article/details/gtbuayvbba.html

Go:   // 无重载：用不同函数名
来源：http://dali.ehwqpu.com/Article/details/gtjwbzhled.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shangyingyoupin.top/Article/details/gtwgdzukuh.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhengqikj.top/Article/details/gtdvydbvhr.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtpbddqnya.html

D. 数组 / 列表 / 集合
来源：http://dali.xylfe.cn/Article/details/gtsexycpkd.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gttaeggyil.html

[D01] 创建数组 / 列表
来源：http://dali.ydzc1.top/Article/details/gtdsqzbjbk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.svipenyu.cn/Article/details/gtuwgxqgsy.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.redwolf501.top/Article/details/gtqucghyfv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sufxvd.cn/Article/details/gtuufsbqhd.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.tian-w.cn/Article/details/gtsanochbi.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yonumen.top/Article/details/gtpysykdgn.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.nanxuanxn.top/Article/details/gtilznnrvw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.dashuyun.cn/Article/details/gtwgirotdr.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.chenlongwang.top/Article/details/gtmpzfgbqh.html

[D02] 追加元素到末尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsptciwir.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hnxiangtu.top/Article/details/gtdonizwoa.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hfpthk.cn/Article/details/gtptpnuppm.html

JS:   arr.push(4);
来源：http://dali.gaohongyu789.top/Article/details/gtrzdjaanr.html

TS:   arr.push(4);
来源：http://dali.nanxinkj.top/Article/details/gteikimxmy.html

Java: list.add(4);
来源：http://dali.gaohongyu789.top/Article/details/gtezclqazk.html

Go:   arr = append(arr, 4)
来源：http://dali.bjfxy.top/Article/details/gtfjingspf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xziqi.cn/Article/details/gthjdscnwq.html

C#:   list.Add(4);
来源：http://dali.xylfe.cn/Article/details/gtvxswjzac.html

[D03] 在指定位置插入元素
来源：http://dali.hammf.cn/Article/details/gtwelkgfjk.html

Py:   arr.insert(0, 0)
来源：http://dali.ivvv.top/Article/details/gtpizfdtdz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yuxming.cn/Article/details/gtvqciugfn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.wangdashe.top/Article/details/gtnrwoafki.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.havefunace.top/Article/details/gtypkuzyyw.html

Java: list.add(0, 0);
来源：http://dali.cdnleiting.top/Article/details/gtdplnvzwx.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.pycfn.com/Article/details/gtjwoiokhl.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hywenlv.cn/Article/details/gtepabyxtj.html

C#:   list.Insert(0, 0);
来源：http://dali.sxryk.cn/Article/details/gtkacfivdi.html

[D04] 删除元素
来源：http://dali.cheryme.top/Article/details/gttdvqwwja.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.nanxinkj.top/Article/details/gtttwksafs.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.andypj.xyz/Article/details/gttsvjsujr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.guannengcc.top/Article/details/gtydjrqaih.html

TS:   arr.splice(0, 1);
来源：http://dali.yuxming.cn/Article/details/gthaofynnh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.smart0.xyz/Article/details/gtlguwcozj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yj20258.top/Article/details/gtivugrkqi.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hnqzz.top/Article/details/gtottykjls.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.0kj1m.cn/Article/details/gtlapudaoe.html

[D05] 访问与修改元素
来源：http://dali.cashguo.top/Article/details/gtdipxycjr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gtrfdpblap.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yj202588.top/Article/details/gtpvtqtyts.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.dashuyun.cn/Article/details/gtbnsiraek.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.daria6918.cn/Article/details/gtnkdienki.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cucudq.cn/Article/details/gtxonpcknq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xinyue.icu/Article/details/gtjphewjdy.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hongshengwenyu.top/Article/details/gtkkhkvunb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqrwigflx.html

[D06] 数组长度
来源：http://dali.jyoumei.cn/Article/details/gtbnfeznob.html

Py:   len(arr)
来源：http://dali.ppjwa.cn/Article/details/gtdsrnloba.html

PHP:  count($arr);
来源：http://dali.smart0.xyz/Article/details/gtcaclkfzx.html

JS:   arr.length
来源：http://dali.316326.xyz/Article/details/gtvthijjjh.html

TS:   arr.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtwxqlqpfu.html

Java: list.size();
来源：http://dali.hnqzz.top/Article/details/gtszviyjav.html

Go:   len(arr)
来源：http://dali.ppjwa.cn/Article/details/gthfnkzixh.html

Ruby: arr.length; arr.size
来源：http://dali.yvedp.cn/Article/details/gtgyhpknge.html

C#:   list.Count;
来源：http://dali.zhengqikj.top/Article/details/gtkidaiuyq.html

[D07] 切片 / 取子数组
来源：http://dali.c1oappe.top/Article/details/gtwzwcczzy.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.fengsongda.top/Article/details/gtxzbmuhvs.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yongpay.top/Article/details/gtwavvnhex.html

JS:   arr.slice(1, 4);
来源：http://dali.xinyue.icu/Article/details/gthmtmltxv.html

TS:   arr.slice(1, 4);
来源：http://dali.xuanzx.com/Article/details/gtfimiowgq.html

Java: list.subList(1, 4);
来源：http://dali.yj20258888.top/Article/details/gtnyjbmppg.html

Go:   arr[1:4]
来源：http://dali.xuanzx.com/Article/details/gtsbnvgqeb.html

Ruby: arr[1, 3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gthgodopxz.html

C#:   list.GetRange(1, 3);
来源：http://dali.yuxming.cn/Article/details/gtzfejmvex.html

[D08] 合并两个数组
来源：http://dali.c1oappe.top/Article/details/gtwfvmggju.html

Py:   a + b;  a.extend(b)
来源：http://dali.zycfv.cn/Article/details/gtkqydpmji.html

PHP:  array_merge($a, $b);
来源：http://dali.snrcjt.cn/Article/details/gttmnjoggs.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ybcxt.top/Article/details/gtefnyjndv.html

TS:   [...a, ...b];
来源：http://dali.shanyushiyangtech.top/Article/details/gtkrarerjm.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.dianchejie.cn/Article/details/gtltugwsde.html

Go:   append(a, b...)
来源：http://dali.yonumen.top/Article/details/gtnulffhav.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cdnleiting.top/Article/details/gtgyatdure.html

C#:   a.Concat(b).ToList()
来源：http://dali.hfpthk.cn/Article/details/gtglzpbshj.html

[D09] 排序（升序）
来源：http://dali.svipenyu.cn/Article/details/gtgccogawd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ivvv.top/Article/details/gtfkbubypf.html

PHP:  sort($arr);
来源：http://dali.iojbl.cn/Article/details/gtsztmqjpm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.daria6918.cn/Article/details/gtqnxwiiun.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yonumen.top/Article/details/gtozhmumrb.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.pycfn.com/Article/details/gtrxvmftnu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.aizwys.cn/Article/details/gtlznexahv.html

Ruby: arr.sort
来源：http://dali.gotoacloud.top/Article/details/gtqtnammai.html

C#:   list.Sort();
来源：http://dali.nanxuanxn.top/Article/details/gtayacehje.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sweek.top/Article/details/gtffzvwkvk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hnqzz.top/Article/details/gtyqvwfmmo.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hywenlv.cn/Article/details/gttqavvapo.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xinyue.icu/Article/details/gtzgqygprg.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jyoumei.cn/Article/details/gtwwwrxwmr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.pengpengdd.cyou/Article/details/gtoegqxsua.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shangyingyoupin.top/Article/details/gtyxzqcvfn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ehwqpu.com/Article/details/gttdlplnur.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gogol.net.cn/Article/details/gthvqwhbry.html

[D11] 反转数组
来源：http://dali.sxryk.cn/Article/details/gtvzytylkm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jinqigfzy.top/Article/details/gtpahhulic.html

PHP:  array_reverse($arr);
来源：http://dali.cheryme.top/Article/details/gtffscyewd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yuanzhike.top/Article/details/gtekiyqtxt.html

TS:   [...arr].reverse();
来源：http://dali.yangfankeji.com/Article/details/gtdsdlcupl.html

Java: Collections.reverse(list);
来源：http://dali.cdnleiting.top/Article/details/gtsqxuptsl.html

Go:   slices.Reverse(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtubxnunxd.html

Ruby: arr.reverse
来源：http://dali.aibaodan.cn/Article/details/gtbxmhzduz.html


<!-- 参考信息 -->