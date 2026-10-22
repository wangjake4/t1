代发 wailian999

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.cqqwz.cn/Article/details/gturutrzzy.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.chenlongwang.top/Article/details/gtmdyofhfo.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.cqqwz.cn/Article/details/gtiztoikpv.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.kuanghao11.cn/Article/details/gtkqubmeud.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yuxming.cn/Article/details/gtlscbqqpm.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shuidangran.top/Article/details/gtkqlnsgna.html

[B11] 生成数字序列 / 区间
来源：http://dali.nanxinkj.top/Article/details/gtjawwftcw.html

Py:   list(range(0, 10, 2))
来源：http://dali.smart0.xyz/Article/details/gtubvdcpda.html

PHP:  range(0, 10, 2);
来源：http://dali.cdnleiting.top/Article/details/gtbndwdlik.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yuanzhike.top/Article/details/gtfflhdpho.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zycfv.cn/Article/details/gtokautkxp.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hysaishi.cn/Article/details/gttcnwipov.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hfpthk.cn/Article/details/gtemkcyjuo.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yongpay.top/Article/details/gtkklpjkux.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hnxiangtu.top/Article/details/gtfurhgcde.html

[B12] 跳出多层循环
来源：http://dali.daxiang520.top/Article/details/gtccifnquj.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.shanyushiyangtech.top/Article/details/gtqbhimkwz.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.shzxlz.cn/Article/details/gtghuvythk.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nwbrower.top/Article/details/gtiawjjlll.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgylukdcv.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.redwolf501.top/Article/details/gtnlbqaxqt.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jinqigfzy.top/Article/details/gtzrecjkvb.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hnxiangtu.top/Article/details/gtpkarqblq.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yj20258888.top/Article/details/gtkpkhuoho.html

[B13] 判断是否为数字
来源：http://dali.zhoulong.xyz/Article/details/gttcllczhc.html

Py:   isinstance(x, (int, float))
来源：http://dali.zycfv.cn/Article/details/gtqranqmvw.html

PHP:  is_numeric($x)
来源：http://dali.hnqzz.top/Article/details/gttvrsmxqx.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.mhx1999.top/Article/details/gtpmmraogo.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jyoumei.cn/Article/details/gtuspwrdvq.html

Java: x instanceof Number
来源：http://dali.yj20258888.top/Article/details/gtonguafur.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hammf.cn/Article/details/gtosamipxq.html

Ruby: x.is_a?(Numeric)
来源：http://dali.meibo888.top/Article/details/gtfrtqkyfw.html

C#:   x is int or double or decimal
来源：http://dali.pycfn.com/Article/details/gtkzlilnab.html

[B14] 判断值是否在集合内
来源：http://dali.9152youxi.cn/Article/details/gtvugyiaml.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jinqigufen.top/Article/details/gtfagzllmp.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yueranfly.top/Article/details/gtcygnnfjb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cdnleiting.top/Article/details/gtfmkoqjkh.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jyoumei.cn/Article/details/gtgkrhzzhg.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ydzc1.top/Article/details/gtpahmokzw.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ppjwa.cn/Article/details/gtehbhstks.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xinyue.icu/Article/details/gtwhpmortm.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hywenlv.cn/Article/details/gtqquwprql.html

[B15] 布尔运算与取反
来源：http://dali.quarkkingdee.top/Article/details/gtltjgijmx.html

Py:   a and b or not c
来源：http://dali.pengpengdd.cyou/Article/details/gtvgbvdmfm.html

PHP:  $a && $b || !$c
来源：http://dali.chenzaomai.com/Article/details/gtilhiuxoq.html

JS:   a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gtjmraokbp.html

TS:   a && b || !c
来源：http://dali.jianghu66.top/Article/details/gtfofzlaxu.html

Java: a && b || !c
来源：http://dali.aizwys.cn/Article/details/gtudomttwa.html

Go:   a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gtqyiegalx.html

Ruby: a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmfazczoa.html

C#:   a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gttyijzlkb.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.tian-w.cn/Article/details/gtynntvkds.html

Py:   if not data: return
来源：http://dali.shanyushiyangtech.top/Article/details/gtmvpfjnuf.html

PHP:  if (!$data) { return; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtiwrgdgen.html

JS:   if (!data) return;
来源：http://dali.jinqigufen.top/Article/details/gtsjwrssks.html

TS:   if (!data) return;
来源：http://dali.feifeiyinyue.top/Article/details/gtggtqmvlb.html

Java: if (data == null) return;
来源：http://dali.yangfankeji.com/Article/details/gtxqjdzfip.html

Go:   if data == nil { return }
来源：http://dali.jqgfzy.top/Article/details/gtdvuqkfvy.html

Ruby: return if data.nil?
来源：http://dali.xylfe.cn/Article/details/gttaipxsol.html

C#:   if (data == null) return;
来源：http://dali.jlsjyb.cn/Article/details/gtulvgqlkv.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvmxbbupc.html

C. 函数与作用域
来源：http://dali.gogol.net.cn/Article/details/gtxprstufh.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtquwflcew.html

[C01] 定义函数
来源：http://dali.ppjwa.cn/Article/details/gtrdzsplvi.html

Py:   def add(a, b): return a + b
来源：http://dali.zhiwuduotai.top/Article/details/gtdsumdijq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gtifoyspzx.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gtolxvnqye.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gtcxakbpgf.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.birdmap.top/Article/details/gtrfmcrsgx.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.dashuyun.cn/Article/details/gtnujbqfno.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xuanzx.com/Article/details/gtlkxuoszu.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gtgevmaqkd.html

[C02] 默认参数
来源：http://dali.jyoumei.cn/Article/details/gtcevytisf.html

Py:   def greet(name="World"): return name
来源：http://dali.jlsjyb.cn/Article/details/gthetjngcr.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.havefunace.top/Article/details/gtipikkpgu.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zycfv.cn/Article/details/gtdktpigup.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yangfankeji.com/Article/details/gtqxluqaoy.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.tianlin.xyz/Article/details/gtlgdufdez.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhixingplan.top/Article/details/gtpumvhelf.html

Ruby: def greet(name = "World") = name
来源：http://dali.sxryk.cn/Article/details/gtkeaqvucc.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkgopynhx.html

[C03] 可变参数
来源：http://dali.cucudq.cn/Article/details/gtxhzcdwlr.html

Py:   def total(*args): return sum(args)
来源：http://dali.meibo888.top/Article/details/gturpesqbp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhoulong.xyz/Article/details/gtvhrnzqex.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cashguo.top/Article/details/gtqpnguojp.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbbkruffx.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sweek.top/Article/details/gtymmbrtzb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.fengsongda.top/Article/details/gttmzzuytb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.9152youxi.cn/Article/details/gtfcwjtfex.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.fzhhl.top/Article/details/gtetaltbuo.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yanxiufei.cn/Article/details/gtpprodtzh.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ivvv.top/Article/details/gtazoqgmrk.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhixingplan.top/Article/details/gtvtnovcit.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xuanzx.com/Article/details/gtduacvjbo.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhiwuduotai.top/Article/details/gtsfrhlxqh.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.wangdashe.top/Article/details/gtouswpotr.html

Go:   // 无：用配置结构体参数
来源：http://dali.cqqwz.cn/Article/details/gtjupqdqny.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yangfankeji.com/Article/details/gtuaojlelh.html

C#:   f(a: 1, b: 2)
来源：http://dali.shuidangran.top/Article/details/gtqtvtpqcn.html

[C05] 返回多个值
来源：http://dali.0kj1m.cn/Article/details/gtczsxsdxd.html

Py:   return a, b
来源：http://dali.meibo888.top/Article/details/gtokciisae.html

PHP:  return [$a, $b];
来源：http://dali.zhixingplan.top/Article/details/gtocdcvjfv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jqgufenzy.top/Article/details/gtuuudtkxm.html

TS:   return { a, b };
来源：http://dali.xuetiantiany.cn/Article/details/gtegvxnkfq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yangfankeji.com/Article/details/gtfgvadxmo.html

Go:   return a, b
来源：http://dali.smart0.xyz/Article/details/gtujefottg.html

Ruby: return a, b
来源：http://dali.yueranfly.top/Article/details/gtcmtbtmek.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shuidangran.top/Article/details/gthbhkbypn.html

[C06] 匿名函数 / lambda
来源：http://dali.jyoumei.cn/Article/details/gtbimaaoxz.html

Py:   square = lambda x: x * x
来源：http://dali.pengpengdd.cyou/Article/details/gtokgaopor.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jqgufenzy.top/Article/details/gttxspkbog.html

JS:   const square = x => x * x;
来源：http://dali.guowangkeji.top/Article/details/gtbsnxucjn.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gtamdahysy.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gteodjpcle.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.daxiang520.top/Article/details/gtupqlxwcz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.9152youxi.cn/Article/details/gtwwmhsvew.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yj202588.top/Article/details/gtpgpqkvfa.html

[C07] 把函数作为参数传入
来源：http://dali.bjfxy.top/Article/details/gthlrjnkfw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhixingplan.top/Article/details/gtlbyopran.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtsjdlzvcy.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yangfankeji.com/Article/details/gtbqsppwme.html

TS:   arr.map(String)
来源：http://dali.yongpay.top/Article/details/gtvibggbup.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.wangdashe.top/Article/details/gtnkmggtbw.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hongshengwenyu.top/Article/details/gtonztajmv.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gtlbcvoieq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.wangshuangyany.cn/Article/details/gtoazxomeg.html

[C08] 闭包
来源：http://dali.jyoumei.cn/Article/details/gtiltdtuas.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.tanke756.top/Article/details/gtamumyvmb.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yongpay.top/Article/details/gtbvjkgkwr.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.iojbl.cn/Article/details/gtioqovlar.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ydzc1.top/Article/details/gtghvwbfba.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.redwolf501.top/Article/details/gtzbzeyptn.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yj202588.top/Article/details/gtepxovvzt.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gzhubu.top/Article/details/gtngaxtsyv.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yuxming.cn/Article/details/gtcxqbxhtj.html

[C09] 递归
来源：http://dali.mhx1999.top/Article/details/gtngeqcccf.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteohonkwt.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.birdmap.top/Article/details/gtvptehugc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gogol.net.cn/Article/details/gtmooqpbfz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.snrcjt.cn/Article/details/gtlxuppzpi.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.havefunace.top/Article/details/gtqgkmwjaq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xylfe.cn/Article/details/gtvinecyez.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ehwqpu.com/Article/details/gtnvxvoaca.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.feifeiyinyue.top/Article/details/gtmxwdiphc.html

[C10] 变量作用域
来源：http://dali.guannengcc.top/Article/details/gtrwszwxda.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gzhubu.top/Article/details/gtgacqhjzi.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.aizwys.cn/Article/details/gtnwiffgaf.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.sysykeji.top/Article/details/gtmwmtspaz.html

TS:   同 JS
来源：http://dali.sufxvd.cn/Article/details/gtgowokdjr.html

Java: 方法内为块级作用域
来源：http://dali.ehwqpu.com/Article/details/gtzimbpkos.html

Go:   花括号块级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzrhsfoju.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jinqigufen.top/Article/details/gtrpgdxjdq.html

C#:   块级作用域
来源：http://dali.zhengqikj.top/Article/details/gttqieipou.html

[C11] 模块导入与导出
来源：http://dali.c1oappe.top/Article/details/gtizliurnj.html

Py:   from module import func
来源：http://dali.pengpengdd.cyou/Article/details/gtiuszlpfh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.quarkkingdee.top/Article/details/gtmtixoirh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.daria6918.cn/Article/details/gtxhwyoplg.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hammf.cn/Article/details/gtdejugkdq.html

Java: import java.util.List;
来源：http://dali.pengpengdd.cyou/Article/details/gtrysyypfj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ehwqpu.com/Article/details/gtvapbogmk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ybcxt.top/Article/details/gttylhczal.html

C#:   using System.Text;
来源：http://dali.pycfn.com/Article/details/gtpqkdxojc.html

[C12] 立即执行函数 IIFE
来源：http://dali.cqqwz.cn/Article/details/gtwiqcisdf.html

Py:   (lambda: print("run"))()
来源：http://dali.wangdashe.top/Article/details/gtvfwkhqbw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jinqigufen.top/Article/details/gtrdlynxgv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.9152youxi.cn/Article/details/gtzwckypcc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.316326.xyz/Article/details/gtaiiukqdv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yuxming.cn/Article/details/gtglgnqqrj.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gogol.net.cn/Article/details/gtavvyvzgc.html

Ruby: -> { puts "run" }.call
来源：http://dali.jiagoushi.top/Article/details/gtqhqwivfd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hywenlv.cn/Article/details/gtkjdgaftm.html

[C13] 类型声明 / 类型注解
来源：http://dali.hnqzz.top/Article/details/gtivnfzdml.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.meibo888.top/Article/details/gthzegtoco.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvqwznazt.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gotoacloud.top/Article/details/gtfiwtfxgb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gtalgyufhr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gttmmyhuaa.html

Go:   func add(a, b int) int
来源：http://dali.tian-w.cn/Article/details/gtqdapyebu.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.feifeiyinyue.top/Article/details/gtsbyzrvta.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.quarkkingdee.top/Article/details/gtbvywkeca.html

[C14] 泛型函数
来源：http://dali.gzhubu.top/Article/details/gtakztauva.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.quarkkingdee.top/Article/details/gtoodhfbqt.html

PHP:  // 无泛型
来源：http://dali.aibaodan.cn/Article/details/gtuszyqxsz.html

JS:   // 无泛型
来源：http://dali.yvedp.cn/Article/details/gtzlxgjegl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.smart0.xyz/Article/details/gtrqoyzfbs.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsodqcmke.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ivvv.top/Article/details/gtvmntmknj.html

Ruby: # 无泛型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxdukmfjt.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xinyue.icu/Article/details/gtrjntzvqx.html

[C15] 解构 / 展开参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtacxsyxnx.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hywenlv.cn/Article/details/gtteitpuhd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jlsjyb.cn/Article/details/gtvznujymm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.9152youxi.cn/Article/details/gtvwzrgkjt.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sweek.top/Article/details/gtqlldwffv.html

Java: // 无解构
来源：http://dali.yuanzhike.top/Article/details/gtwkucbqkn.html

Go:   // 无解构
来源：http://dali.gaohongyu789.top/Article/details/gtegpiwzvg.html

Ruby: a, b = pair
来源：http://dali.yangfankeji.com/Article/details/gtgkhqlixz.html

C#:   var (a, b) = pair;
来源：http://dali.chenzaomai.com/Article/details/gtwlqsxtdn.html

[C16] 函数 / 方法重载
来源：http://dali.xuanzx.com/Article/details/gtwwhxjqvp.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shzxlz.cn/Article/details/gtoivxpmft.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gtzfasfdrq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.andypj.xyz/Article/details/gtruvftivz.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hnxiangtu.top/Article/details/gtqpkytems.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.aizwys.cn/Article/details/gtuxeeqxgw.html

Go:   // 无重载：用不同函数名
来源：http://dali.hywenlv.cn/Article/details/gtsvghbako.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ydzc1.top/Article/details/gtckkoujcs.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.birdmap.top/Article/details/gtlapmncav.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtoprphtxy.html

D. 数组 / 列表 / 集合
来源：http://dali.hywenlv.cn/Article/details/gtvtcpcabn.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtxyhhfhak.html

[D01] 创建数组 / 列表
来源：http://dali.zhengqikj.top/Article/details/gtbwrgwona.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shzxlz.cn/Article/details/gtvgwbmvbr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jyoumei.cn/Article/details/gtfqklhhsq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zycfv.cn/Article/details/gtvytghydm.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jinghuilouyu.cn/Article/details/gtottfadgu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cdnleiting.top/Article/details/gtyrhonong.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.fengsongda.top/Article/details/gtngyrcqxw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hywenlv.cn/Article/details/gtqojwaukx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhaomingkeji.xyz/Article/details/gterckdcef.html

[D02] 追加元素到末尾
来源：http://dali.aibaodan.cn/Article/details/gtwhvukyhw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shanyushiyangtech.top/Article/details/gtdubevdrz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yj20258888.top/Article/details/gtcqozvmow.html

JS:   arr.push(4);
来源：http://dali.xziqi.cn/Article/details/gtgbsgsowq.html

TS:   arr.push(4);
来源：http://dali.gaohongyu789.top/Article/details/gtbempqzjx.html

Java: list.add(4);
来源：http://dali.sufxvd.cn/Article/details/gtshgkwnlu.html

Go:   arr = append(arr, 4)
来源：http://dali.jyoumei.cn/Article/details/gtukorvsul.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.0kj1m.cn/Article/details/gtpgafsvpw.html

C#:   list.Add(4);
来源：http://dali.9152youxi.cn/Article/details/gtrvqttnvf.html

[D03] 在指定位置插入元素
来源：http://dali.zhoulong.xyz/Article/details/gtegnaqllf.html

Py:   arr.insert(0, 0)
来源：http://dali.sysykeji.top/Article/details/gtkcfabnvx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zdqjudy.top/Article/details/gttznexmyd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ehwqpu.com/Article/details/gthhharlxm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.aibaodan.cn/Article/details/gtgnbzwhub.html

Java: list.add(0, 0);
来源：http://dali.316326.xyz/Article/details/gtmurculzo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jqgfzy.top/Article/details/gteodaykeu.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ppjwa.cn/Article/details/gtbcdkwqbm.html

C#:   list.Insert(0, 0);
来源：http://dali.sweek.top/Article/details/gtnedviuvd.html

[D04] 删除元素
来源：http://dali.yj20258888.top/Article/details/gtufuavawp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.quarkkingdee.top/Article/details/gtulcpmoln.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yangfankeji.com/Article/details/gtqjpfpxic.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xuanzx.com/Article/details/gtqayclaog.html

TS:   arr.splice(0, 1);
来源：http://dali.sxryk.cn/Article/details/gtvpjelmxe.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yongpay.top/Article/details/gtjqfjvzty.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.svipenyu.cn/Article/details/gtyloznnqi.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsayghiir.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xziqi.cn/Article/details/gtmgnctysu.html

[D05] 访问与修改元素
来源：http://dali.xziqi.cn/Article/details/gtedkdxrdy.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tian-w.cn/Article/details/gtinjcczow.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jyoumei.cn/Article/details/gtusxgutbd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hysaishi.cn/Article/details/gtmtnpnftg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthhhfbses.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yongpay.top/Article/details/gtpssybaie.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cdnleiting.top/Article/details/gtbirslyju.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jiagoushi.top/Article/details/gtknwnudhi.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jyoumei.cn/Article/details/gtvuhzzkwi.html

[D06] 数组长度
来源：http://dali.iojbl.cn/Article/details/gthktrdjoy.html

Py:   len(arr)
来源：http://dali.tian-w.cn/Article/details/gtlyebypiz.html

PHP:  count($arr);
来源：http://dali.yj20258.top/Article/details/gtfqdjwpdc.html

JS:   arr.length
来源：http://dali.chenzaomai.com/Article/details/gttpajzqds.html

TS:   arr.length
来源：http://dali.shuidangran.top/Article/details/gtvtiugllm.html

Java: list.size();
来源：http://dali.cashguo.top/Article/details/gtjpfozjut.html

Go:   len(arr)
来源：http://dali.snrcjt.cn/Article/details/gtbsevsxrr.html

Ruby: arr.length; arr.size
来源：http://dali.sweek.top/Article/details/gtwqrtdctr.html

C#:   list.Count;
来源：http://dali.pycfn.com/Article/details/gtvmmmfmbm.html

[D07] 切片 / 取子数组
来源：http://dali.zhoulong.xyz/Article/details/gtmqyenobo.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinghuilouyu.cn/Article/details/gtnmtghkqc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yj202588.top/Article/details/gtgcgzqjmb.html

JS:   arr.slice(1, 4);
来源：http://dali.sxryk.cn/Article/details/gtrbamezzs.html

TS:   arr.slice(1, 4);
来源：http://dali.zhengqikj.top/Article/details/gtzuoguewr.html

Java: list.subList(1, 4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtppemhezd.html

Go:   arr[1:4]
来源：http://dali.yj20258888.top/Article/details/gtzbcaonip.html

Ruby: arr[1, 3]
来源：http://dali.sufxvd.cn/Article/details/gtwvhfwwcf.html

C#:   list.GetRange(1, 3);
来源：http://dali.hysaishi.cn/Article/details/gtgerfnpqh.html

[D08] 合并两个数组
来源：http://dali.zdqjudy.top/Article/details/gtygoctjya.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinqigufen.top/Article/details/gtknnefhos.html

PHP:  array_merge($a, $b);
来源：http://dali.smart0.xyz/Article/details/gtqrqsvyjx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.mhx1999.top/Article/details/gtengljfzb.html

TS:   [...a, ...b];
来源：http://dali.yongpay.top/Article/details/gtngqazsjn.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.fengsongda.top/Article/details/gtyxskdirh.html

Go:   append(a, b...)
来源：http://dali.guowangkeji.top/Article/details/gttdpvwxeo.html

Ruby: a + b;  a.concat(b)
来源：http://dali.smart0.xyz/Article/details/gtxeasxcrx.html

C#:   a.Concat(b).ToList()
来源：http://dali.xuanzx.com/Article/details/gtsjzzkkdt.html

[D09] 排序（升序）
来源：http://dali.pengpengdd.cyou/Article/details/gtyijcfdsb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuanzhike.top/Article/details/gtbalbxghf.html

PHP:  sort($arr);
来源：http://dali.sysykeji.top/Article/details/gtnicnorpr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.nwbrower.top/Article/details/gtvcxakqee.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cheryme.top/Article/details/gtkolwfevg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhiwuduotai.top/Article/details/gtngjsfzby.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hammf.cn/Article/details/gtumiithwk.html

Ruby: arr.sort
来源：http://dali.cheryme.top/Article/details/gtsspkrjqf.html

C#:   list.Sort();
来源：http://dali.zycfv.cn/Article/details/gtavensdsq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xuetiantiany.cn/Article/details/gtaqxapbpa.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yvedp.cn/Article/details/gtumshnrzd.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nanxuanxn.top/Article/details/gtmrnbjsrj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.smart0.xyz/Article/details/gtrdrsbpqj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cashguo.top/Article/details/gthoijbtxk.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.havefunace.top/Article/details/gtqbgnyucw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yvedp.cn/Article/details/gtyrcalxwe.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jiagoushi.top/Article/details/gtwemkrpfr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yonumen.top/Article/details/gtfvqxbclq.html


<!-- 参考信息 -->