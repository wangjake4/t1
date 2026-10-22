代发 wailian999

PHP:  range(0, 10, 2);
来源：http://dali.gotoacloud.top/Article/details/gt2dosjmxzk.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jyoumei.cn/Article/details/gt2tcqccieg.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xinyue.icu/Article/details/gt2wrmrhxhf.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hammf.cn/Article/details/gt2okvsfkug.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.xylfe.cn/Article/details/gt2nbeyshzn.html

Ruby: (0...10).step(2).to_a
来源：http://dali.quarkkingdee.top/Article/details/gt2oknxxrjb.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.smart0.xyz/Article/details/gt2pbvzezpc.html

[B12] 跳出多层循环
来源：http://dali.xylfe.cn/Article/details/gt2tznrbgcl.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hammf.cn/Article/details/gt2pbcryikb.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.sufxvd.cn/Article/details/gt2nlawvbiq.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zycfv.cn/Article/details/gt2ivbcvjkl.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ivvv.top/Article/details/gt2rkfpgwhm.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenzaomai.com/Article/details/gt2udwqaoiz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.aizwys.cn/Article/details/gt2hjwekmnp.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.guowangkeji.top/Article/details/gt2nutxqmcl.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xinyue.icu/Article/details/gt2yfnsevbv.html

[B13] 判断是否为数字
来源：http://dali.xinyue.icu/Article/details/gt2cfvwcvda.html

Py:   isinstance(x, (int, float))
来源：http://dali.yanxiufei.cn/Article/details/gt2gguagdom.html

PHP:  is_numeric($x)
来源：http://dali.gaohongyu789.top/Article/details/gt2lzlxlnvf.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.haohaochexian.top/Article/details/gt2pjttqbbk.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hfpthk.cn/Article/details/gt2sqbpjddj.html

Java: x instanceof Number
来源：http://dali.yj20258.top/Article/details/gt2tnzxkrmw.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ydzc1.top/Article/details/gt2eylkjnyb.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jyoumei.cn/Article/details/gt2giixrpbu.html

C#:   x is int or double or decimal
来源：http://dali.cdnleiting.top/Article/details/gt2xevfdlsf.html

[B14] 判断值是否在集合内
来源：http://dali.pengpengdd.cyou/Article/details/gt2mqdbxzjk.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.andypj.xyz/Article/details/gt2tiwokell.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jinqigfzy.top/Article/details/gt2ffyyvcoq.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.chenzaomai.com/Article/details/gt2jggqmyxe.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.tian-w.cn/Article/details/gt2mcwiaemc.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yuxming.cn/Article/details/gt2igmpyiex.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.andypj.xyz/Article/details/gt2oplsoexp.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zdqjudy.top/Article/details/gt2nkzfckdm.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hysaishi.cn/Article/details/gt2csygwtft.html

[B15] 布尔运算与取反
来源：http://dali.sysykeji.top/Article/details/gt2phkxcuek.html

Py:   a and b or not c
来源：http://dali.gaohongyu789.top/Article/details/gt2gtniqjgm.html

PHP:  $a && $b || !$c
来源：http://dali.hnxiangtu.top/Article/details/gt2skkmqlhs.html

JS:   a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nifnfjez.html

TS:   a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gt2zpklnlxr.html

Java: a && b || !c
来源：http://dali.pycfn.com/Article/details/gt2ehvfcyfc.html

Go:   a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gt2ctzaxxlx.html

Ruby: a && b || !c
来源：http://dali.fzhhl.top/Article/details/gt2qeohzzzq.html

C#:   a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gt2umgnggts.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.tianlin.xyz/Article/details/gt2fyanomrs.html

Py:   if not data: return
来源：http://dali.birdmap.top/Article/details/gt2mtzfrdqf.html

PHP:  if (!$data) { return; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vqbmldqj.html

JS:   if (!data) return;
来源：http://dali.shzxlz.cn/Article/details/gt2yvuedsjc.html

TS:   if (!data) return;
来源：http://dali.zhiwuduotai.top/Article/details/gt2zdjywugf.html

Java: if (data == null) return;
来源：http://dali.sxryk.cn/Article/details/gt2txwxibci.html

Go:   if data == nil { return }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wrdteqqq.html

Ruby: return if data.nil?
来源：http://dali.shangyingyoupin.top/Article/details/gt2rjihqyep.html

C#:   if (data == null) return;
来源：http://dali.vqdsnc.cn/Article/details/gt2hskocqjw.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2ucnmvdel.html

C. 函数与作用域
来源：http://dali.ybcxt.top/Article/details/gt2ddqkustk.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2tzlktnya.html

[C01] 定义函数
来源：http://dali.yanxiufei.cn/Article/details/gt2rchjnttc.html

Py:   def add(a, b): return a + b
来源：http://dali.dashuyun.cn/Article/details/gt2lxtargvy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2mnytvofc.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2sdsbyceg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gt2txurrihc.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gt2oirfaksn.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yj20258888.top/Article/details/gt2alfuxgkn.html

Ruby: def add(a, b); a + b; end
来源：http://dali.316326.xyz/Article/details/gt2voqasdwr.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gt2yobdtvat.html

[C02] 默认参数
来源：http://dali.9152youxi.cn/Article/details/gt2qccoyqyo.html

Py:   def greet(name="World"): return name
来源：http://dali.redwolf501.top/Article/details/gt2glawdsbc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2pnascuqa.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yongpay.top/Article/details/gt2vyjvgbng.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mrcengvg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.aibaodan.cn/Article/details/gt2jxlyohnc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.9152youxi.cn/Article/details/gt2brnxjoec.html

Ruby: def greet(name = "World") = name
来源：http://dali.gaohongyu789.top/Article/details/gt2hsxfukdp.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.chenjidiqi.icu/Article/details/gt2ufurgqdb.html

[C03] 可变参数
来源：http://dali.zhengqikj.top/Article/details/gt2wvnkktvq.html

Py:   def total(*args): return sum(args)
来源：http://dali.jqgfzy.top/Article/details/gt2xvqzwzzq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.mhx1999.top/Article/details/gt2lsloivcm.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cashguo.top/Article/details/gt2rhtibpvj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cashguo.top/Article/details/gt2lehihgsl.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hammf.cn/Article/details/gt2fzazfocz.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ybcxt.top/Article/details/gt2ioecxead.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.cdnleiting.top/Article/details/gt2iookkndc.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shzxlz.cn/Article/details/gt2fewektjv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ybbkvawp.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jyoumei.cn/Article/details/gt2ijpkfbhu.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hywenlv.cn/Article/details/gt2njsqkvio.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.guannengcc.top/Article/details/gt2sgaynzhg.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cqqwz.cn/Article/details/gt2jzzmzvwo.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yuxming.cn/Article/details/gt2ncvzfmvs.html

Go:   // 无：用配置结构体参数
来源：http://dali.quarkkingdee.top/Article/details/gt2boteufwk.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ppjwa.cn/Article/details/gt2aqjnbnvb.html

C#:   f(a: 1, b: 2)
来源：http://dali.cheryme.top/Article/details/gt2tahlants.html

[C05] 返回多个值
来源：http://dali.kuanghao11.cn/Article/details/gt2rpvfrjxy.html

Py:   return a, b
来源：http://dali.smart0.xyz/Article/details/gt2mhcwysbj.html

PHP:  return [$a, $b];
来源：http://dali.shuidangran.top/Article/details/gt2csweqtps.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.chenzaomai.com/Article/details/gt2xzdrjtte.html

TS:   return { a, b };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xhofkgdr.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jiagoushi.top/Article/details/gt2oakaehbm.html

Go:   return a, b
来源：http://dali.hysaishi.cn/Article/details/gt2ainupwaq.html

Ruby: return a, b
来源：http://dali.ybcxt.top/Article/details/gt2tdpzufqt.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.wangdashe.top/Article/details/gt2jfhijnju.html

[C06] 匿名函数 / lambda
来源：http://dali.jinqigfzy.top/Article/details/gt2oyvxhdwp.html

Py:   square = lambda x: x * x
来源：http://dali.jinqigufen.top/Article/details/gt2tanarplm.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.snrcjt.cn/Article/details/gt2xprjxbqe.html

JS:   const square = x => x * x;
来源：http://dali.jqgfzy.top/Article/details/gt2gcsmukfz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.snrcjt.cn/Article/details/gt2uydhpkuu.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhiwuduotai.top/Article/details/gt2zgdmkivf.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.guannengcc.top/Article/details/gt2shwtonvh.html

Ruby: square = ->(x) { x * x }
来源：http://dali.mhx1999.top/Article/details/gt2afdgoncp.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ivvv.top/Article/details/gt2pmoibbwz.html

[C07] 把函数作为参数传入
来源：http://dali.0kj1m.cn/Article/details/gt2kcammqqf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhoulong.xyz/Article/details/gt2qvpyuyer.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.snrcjt.cn/Article/details/gt2hwurjejd.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hysaishi.cn/Article/details/gt2yiptzfjk.html

TS:   arr.map(String)
来源：http://dali.jqgufenzy.top/Article/details/gt2lkgqkgcp.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.nwbrower.top/Article/details/gt2nepddreo.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.haohaochexian.top/Article/details/gt2wfonazvx.html

Ruby: arr.map(&:upcase)
来源：http://dali.316326.xyz/Article/details/gt2qmbqmkcu.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhoulong.xyz/Article/details/gt2vbdsrkoc.html

[C08] 闭包
来源：http://dali.guowangkeji.top/Article/details/gt2gipqzbfq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yanxiufei.cn/Article/details/gt2zmygnjui.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.aibaodan.cn/Article/details/gt2iiihcxwn.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.9152youxi.cn/Article/details/gt2vkpziyof.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.tianlin.xyz/Article/details/gt2vrdavkqt.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zdqjudy.top/Article/details/gt2poktbehh.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.iojbl.cn/Article/details/gt2ztgpnsns.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shuidangran.top/Article/details/gt2bihkepmx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ypzwnyto.html

[C09] 递归
来源：http://dali.xziqi.cn/Article/details/gt2exsirevy.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2btzxehwx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.sysykeji.top/Article/details/gt2rnnvmlqq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tanke756.top/Article/details/gt2drioivdu.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ppjwa.cn/Article/details/gt2fkrztsau.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jqgfzy.top/Article/details/gt2ytmnykep.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nvujfxsw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cheryme.top/Article/details/gt2nxojzlen.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hnxiangtu.top/Article/details/gt2vojwgcke.html

[C10] 变量作用域
来源：http://dali.sufxvd.cn/Article/details/gt2pgampyul.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xylfe.cn/Article/details/gt2tvuenfpt.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.havefunace.top/Article/details/gt2yjqbhsrq.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jianghu66.top/Article/details/gt2efbtsodf.html

TS:   同 JS
来源：http://dali.jiagoushi.top/Article/details/gt2skdjespi.html

Java: 方法内为块级作用域
来源：http://dali.xuanzx.com/Article/details/gt2ejkogjcb.html

Go:   花括号块级作用域
来源：http://dali.tian-w.cn/Article/details/gt2ukjbgtam.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yongpay.top/Article/details/gt2pqmjekmi.html

C#:   块级作用域
来源：http://dali.jqgufenzy.top/Article/details/gt2embufofw.html

[C11] 模块导入与导出
来源：http://dali.wangdashe.top/Article/details/gt2qgntrvgx.html

Py:   from module import func
来源：http://dali.jqgufenzy.top/Article/details/gt2orsdcacm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.tianlin.xyz/Article/details/gt2usldyion.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yueranfly.top/Article/details/gt2czdvlilm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.gzhubu.top/Article/details/gt2rlckqkai.html

Java: import java.util.List;
来源：http://dali.aibaodan.cn/Article/details/gt2xxsfnkjz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jianghu66.top/Article/details/gt2ghbjmrga.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.vqdsnc.cn/Article/details/gt2evvcskbq.html

C#:   using System.Text;
来源：http://dali.aizwys.cn/Article/details/gt2ptcmgqig.html

[C12] 立即执行函数 IIFE
来源：http://dali.daria6918.cn/Article/details/gt2twzanmzg.html

Py:   (lambda: print("run"))()
来源：http://dali.hammf.cn/Article/details/gt2bydrrldf.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hnqzz.top/Article/details/gt2myrfhrdj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.dianchejie.cn/Article/details/gt2uiophduv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.nwbrower.top/Article/details/gt2bvltqoyu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.chenzaomai.com/Article/details/gt2wmssqsdt.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hnxiangtu.top/Article/details/gt2zniqdjcd.html

Ruby: -> { puts "run" }.call
来源：http://dali.jqgufenzy.top/Article/details/gt2nsaxkxtk.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.guowangkeji.top/Article/details/gt2vmcssjrc.html

[C13] 类型声明 / 类型注解
来源：http://dali.cashguo.top/Article/details/gt2gwvuqhxx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.0kj1m.cn/Article/details/gt2ttqjaeqe.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gt2mbjsleiv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yvedp.cn/Article/details/gt2lkgbfabt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gt2roldupte.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gt2rnbqevjn.html

Go:   func add(a, b int) int
来源：http://dali.cdnleiting.top/Article/details/gt2ynbofpfv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.redwolf501.top/Article/details/gt2ptppmebk.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinqigufen.top/Article/details/gt2ijhrubdk.html

[C14] 泛型函数
来源：http://dali.birdmap.top/Article/details/gt2gmnpjrvo.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cqqwz.cn/Article/details/gt2skbbbpki.html

PHP:  // 无泛型
来源：http://dali.316326.xyz/Article/details/gt2uvfezhoi.html

JS:   // 无泛型
来源：http://dali.smart0.xyz/Article/details/gt2nbxmvapu.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhixingplan.top/Article/details/gt2xflrqnhe.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.fengsongda.top/Article/details/gt2jbfkfwtw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.nanxuanxn.top/Article/details/gt2fjynlcqk.html

Ruby: # 无泛型
来源：http://dali.tianlin.xyz/Article/details/gt2dqfhmyvp.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hrjfqmmi.html

[C15] 解构 / 展开参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tgcmfwhr.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yj20258888.top/Article/details/gt2ksibwbot.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhongyouzk.top/Article/details/gt2dannjoym.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jiagoushi.top/Article/details/gt2dfwweiky.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.c1oappe.top/Article/details/gt2olsinamc.html

Java: // 无解构
来源：http://dali.xziqi.cn/Article/details/gt2fgwpbwuz.html

Go:   // 无解构
来源：http://dali.wangdashe.top/Article/details/gt2sugbyrti.html

Ruby: a, b = pair
来源：http://dali.jinqigufen.top/Article/details/gt2pdrbkuwh.html

C#:   var (a, b) = pair;
来源：http://dali.andypj.xyz/Article/details/gt2arehnxlj.html

[C16] 函数 / 方法重载
来源：http://dali.nanxinkj.top/Article/details/gt2zuizlfso.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ivvv.top/Article/details/gt2gspzsvyq.html

PHP:  // 无重载
来源：http://dali.chenlongwang.top/Article/details/gt2msksqnmq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.gotoacloud.top/Article/details/gt2kpyeceqc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.nanxinkj.top/Article/details/gt2lxhhuzqn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ivvv.top/Article/details/gt2mrwypzed.html

Go:   // 无重载：用不同函数名
来源：http://dali.yvedp.cn/Article/details/gt2nwzeweaw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ppjwa.cn/Article/details/gt2hmcryrvr.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2iqnjjjov.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2iwzvefns.html

D. 数组 / 列表 / 集合
来源：http://dali.dianchejie.cn/Article/details/gt2qxlqgymj.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2hiwamdhu.html

[D01] 创建数组 / 列表
来源：http://dali.guannengcc.top/Article/details/gt2tiwggqcz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.wangdashe.top/Article/details/gt2gpswwmuz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2evcifccr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gotoacloud.top/Article/details/gt2pjwqdtvj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hammf.cn/Article/details/gt2lfiusdqv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.redwolf501.top/Article/details/gt2qbwxskox.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.wangdashe.top/Article/details/gt2wferogof.html

Ruby: arr = [1, 2, 3]
来源：http://dali.nwbrower.top/Article/details/gt2djychlvp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cashguo.top/Article/details/gt2kaitqmbm.html

[D02] 追加元素到末尾
来源：http://dali.yj202588.top/Article/details/gt2tflfzywy.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shuidangran.top/Article/details/gt2jqalodda.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhiwuduotai.top/Article/details/gt2websbvld.html

JS:   arr.push(4);
来源：http://dali.chenjidiqi.icu/Article/details/gt2bhmaimgv.html

TS:   arr.push(4);
来源：http://dali.gzhubu.top/Article/details/gt2fymcbogf.html

Java: list.add(4);
来源：http://dali.zhixingplan.top/Article/details/gt2maondmwi.html

Go:   arr = append(arr, 4)
来源：http://dali.dashuyun.cn/Article/details/gt2tmzlfzmf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qiwyyotk.html

C#:   list.Add(4);
来源：http://dali.zhengqikj.top/Article/details/gt2amyopkls.html

[D03] 在指定位置插入元素
来源：http://dali.cqqwz.cn/Article/details/gt2sndqxbzq.html

Py:   arr.insert(0, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2uhyzvpkz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.gogol.net.cn/Article/details/gt2smmdfqkr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cqqwz.cn/Article/details/gt2ptqfcrzh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.aizwys.cn/Article/details/gt2lhdfsjms.html

Java: list.add(0, 0);
来源：http://dali.birdmap.top/Article/details/gt2qiinduhd.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.mhx1999.top/Article/details/gt2qzhjxrby.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ybcxt.top/Article/details/gt2ltixiggi.html

C#:   list.Insert(0, 0);
来源：http://dali.gotoacloud.top/Article/details/gt2ntyxvctb.html

[D04] 删除元素
来源：http://dali.yuxming.cn/Article/details/gt2dlljxkqn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qzvtdwnx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ybcxt.top/Article/details/gt2qkypjjos.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.guannengcc.top/Article/details/gt2gdsthevb.html

TS:   arr.splice(0, 1);
来源：http://dali.sweek.top/Article/details/gt2wffzkity.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ydzc1.top/Article/details/gt2lptgcvls.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.wangshuangyany.cn/Article/details/gt2scuojguw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xuanzx.com/Article/details/gt2fwtvnmgn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.aizwys.cn/Article/details/gt2bhqriwal.html

[D05] 访问与修改元素
来源：http://dali.gzhubu.top/Article/details/gt2gbfjficf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jyoumei.cn/Article/details/gt2mfzpfdnd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yongpay.top/Article/details/gt2vrgukkpq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.snrcjt.cn/Article/details/gt2mazxqftv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ubziawkd.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cheryme.top/Article/details/gt2qbfqdjdw.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xziqi.cn/Article/details/gt2qfhbsdqt.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhiwuduotai.top/Article/details/gt2giyzfluu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ivvv.top/Article/details/gt2gjkrgrym.html

[D06] 数组长度
来源：http://dali.dianchejie.cn/Article/details/gt2xsarnisr.html

Py:   len(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dfjuuxwr.html

PHP:  count($arr);
来源：http://dali.daxiang520.top/Article/details/gt2onfliczo.html

JS:   arr.length
来源：http://dali.zhoulong.xyz/Article/details/gt2hccejgdt.html

TS:   arr.length
来源：http://dali.chenzaomai.com/Article/details/gt2poxprkcl.html

Java: list.size();
来源：http://dali.xylfe.cn/Article/details/gt2vicastcs.html

Go:   len(arr)
来源：http://dali.xuanzx.com/Article/details/gt2pnxjmvio.html

Ruby: arr.length; arr.size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yhshqwxj.html

C#:   list.Count;
来源：http://dali.iojbl.cn/Article/details/gt2ncfefszw.html

[D07] 切片 / 取子数组
来源：http://dali.hfpthk.cn/Article/details/gt2cdcxduxg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.daxiang520.top/Article/details/gt2rfhbhkkq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinqigufen.top/Article/details/gt2egfvwttt.html

JS:   arr.slice(1, 4);
来源：http://dali.jianghu66.top/Article/details/gt2lfotiqzk.html

TS:   arr.slice(1, 4);
来源：http://dali.xziqi.cn/Article/details/gt2xmylufwf.html

Java: list.subList(1, 4);
来源：http://dali.hnxiangtu.top/Article/details/gt2uybrnuuy.html

Go:   arr[1:4]
来源：http://dali.kuanghao11.cn/Article/details/gt2jzsgjyuc.html

Ruby: arr[1, 3]
来源：http://dali.jqgufenzy.top/Article/details/gt2zepwxuwh.html

C#:   list.GetRange(1, 3);
来源：http://dali.hfpthk.cn/Article/details/gt2fnnfqyfb.html

[D08] 合并两个数组
来源：http://dali.hongshengwenyu.top/Article/details/gt2ubnnuqdd.html

Py:   a + b;  a.extend(b)
来源：http://dali.cdnleiting.top/Article/details/gt2aelccomh.html

PHP:  array_merge($a, $b);
来源：http://dali.chenzaomai.com/Article/details/gt2bvciyahd.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.0kj1m.cn/Article/details/gt2iibjgqco.html

TS:   [...a, ...b];
来源：http://dali.jinqigfzy.top/Article/details/gt2ocktxqxx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.bjfxy.top/Article/details/gt2jneozqfp.html

Go:   append(a, b...)
来源：http://dali.shzxlz.cn/Article/details/gt2scxhvdgn.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hywenlv.cn/Article/details/gt2yezjphhf.html

C#:   a.Concat(b).ToList()
来源：http://dali.bjfxy.top/Article/details/gt2jzzxzwmt.html

[D09] 排序（升序）
来源：http://dali.nwbrower.top/Article/details/gt2mcalddba.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xinyue.icu/Article/details/gt2xuodjypr.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsalobfp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.mhx1999.top/Article/details/gt2mmmaflcv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yj202588.top/Article/details/gt2buwoetaf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sweek.top/Article/details/gt2rftkgajt.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yvedp.cn/Article/details/gt2mcxjiqkc.html

Ruby: arr.sort
来源：http://dali.cdnleiting.top/Article/details/gt2thprgted.html

C#:   list.Sort();
来源：http://dali.cqqwz.cn/Article/details/gt2rfqfgjli.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.tanke756.top/Article/details/gt2dxxnqzxy.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yvedp.cn/Article/details/gt2fhwtafli.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ydzc1.top/Article/details/gt2qpbejujg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.c1oappe.top/Article/details/gt2ukckzglg.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guannengcc.top/Article/details/gt2ecwcyvja.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.chenlongwang.top/Article/details/gt2byyhyzgn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.daria6918.cn/Article/details/gt2ubjnrbow.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xuanzx.com/Article/details/gt2wqqpxcnv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.9152youxi.cn/Article/details/gt2cdrykwae.html

[D11] 反转数组
来源：http://dali.tanke756.top/Article/details/gt2rvydwgls.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hammf.cn/Article/details/gt2vupqkarf.html

PHP:  array_reverse($arr);
来源：http://dali.hammf.cn/Article/details/gt2vjgyyeey.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.snrcjt.cn/Article/details/gt2bdbjbhhy.html

TS:   [...arr].reverse();
来源：http://dali.chenlongwang.top/Article/details/gt2oeycgfab.html

Java: Collections.reverse(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jfpjsbwh.html

Go:   slices.Reverse(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2qijyvcqd.html

Ruby: arr.reverse
来源：http://dali.yvedp.cn/Article/details/gt2jytnllpm.html


<!-- 参考信息 -->