代发 wailian999

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ydzc1.top/Article/details/gtzieoamil.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.nwbrower.top/Article/details/gtwvhzepnf.html

[B11] 生成数字序列 / 区间
来源：http://dali.quarkkingdee.top/Article/details/gtdfgrhott.html

Py:   list(range(0, 10, 2))
来源：http://dali.tanke756.top/Article/details/gtnlewtvkw.html

PHP:  range(0, 10, 2);
来源：http://dali.hnxiangtu.top/Article/details/gtudrexjge.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtsppybmdz.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.andypj.xyz/Article/details/gtbpybfewm.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yj20258.top/Article/details/gtsonvvoly.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.dianchejie.cn/Article/details/gtmuqlyfor.html

Ruby: (0...10).step(2).to_a
来源：http://dali.gogol.net.cn/Article/details/gtheuestyg.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtybwdycsr.html

[B12] 跳出多层循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyqfvwjsm.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.andypj.xyz/Article/details/gtutgfojoz.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.pycfn.com/Article/details/gtrajymuwz.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gotoacloud.top/Article/details/gtwxmtqkpj.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.daria6918.cn/Article/details/gtarozmpac.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.kuanghao11.cn/Article/details/gtssytotgn.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.dianchejie.cn/Article/details/gtgmxgrytn.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.wangdashe.top/Article/details/gtdujevfmb.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yueranfly.top/Article/details/gtlbzokfnc.html

[B13] 判断是否为数字
来源：http://dali.jinqigfzy.top/Article/details/gtvuttcpls.html

Py:   isinstance(x, (int, float))
来源：http://dali.shanyushiyangtech.top/Article/details/gtbnaposes.html

PHP:  is_numeric($x)
来源：http://dali.nwbrower.top/Article/details/gtmnpyegrh.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtjvvetxic.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj20258.top/Article/details/gttxztlmya.html

Java: x instanceof Number
来源：http://dali.yonumen.top/Article/details/gtllhmyslg.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.snrcjt.cn/Article/details/gtjdzyelfg.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhixingplan.top/Article/details/gttroctspv.html

C#:   x is int or double or decimal
来源：http://dali.yongpay.top/Article/details/gttajzzymp.html

[B14] 判断值是否在集合内
来源：http://dali.hnxiangtu.top/Article/details/gtoujpgrzi.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jqgfzy.top/Article/details/gtqtifoexw.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jyoumei.cn/Article/details/gtthyirdti.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gttjmhpulf.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.haohaochexian.top/Article/details/gtjyvmluna.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.cqqwz.cn/Article/details/gtoozgpklv.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yuanzhike.top/Article/details/gtxljpmsqs.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtozhzdajy.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.birdmap.top/Article/details/gtigtdqnec.html

[B15] 布尔运算与取反
来源：http://dali.kuanghao11.cn/Article/details/gtwpvvbnry.html

Py:   a and b or not c
来源：http://dali.gotoacloud.top/Article/details/gtmxhgagew.html

PHP:  $a && $b || !$c
来源：http://dali.andypj.xyz/Article/details/gtpfqfbtlr.html

JS:   a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gtafygirch.html

TS:   a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtybjrujxt.html

Java: a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gtotlrevti.html

Go:   a && b || !c
来源：http://dali.sysykeji.top/Article/details/gttpalnbxh.html

Ruby: a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gtbswmalsy.html

C#:   a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gthggrwwnz.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.havefunace.top/Article/details/gtelnbbrnr.html

Py:   if not data: return
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyegyeuuk.html

PHP:  if (!$data) { return; }
来源：http://dali.guowangkeji.top/Article/details/gtsphmyoyi.html

JS:   if (!data) return;
来源：http://dali.pengpengdd.cyou/Article/details/gtwazfeiql.html

TS:   if (!data) return;
来源：http://dali.yueranfly.top/Article/details/gtcppilbqi.html

Java: if (data == null) return;
来源：http://dali.xuetiantiany.cn/Article/details/gtuwygyeqx.html

Go:   if data == nil { return }
来源：http://dali.cheryme.top/Article/details/gtseqongtl.html

Ruby: return if data.nil?
来源：http://dali.quarkkingdee.top/Article/details/gtftkdgned.html

C#:   if (data == null) return;
来源：http://dali.redwolf501.top/Article/details/gtovrtqinn.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtzlodhrcq.html

C. 函数与作用域
来源：http://dali.cashguo.top/Article/details/gtbcqwreaj.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtsbqcubch.html

[C01] 定义函数
来源：http://dali.dashuyun.cn/Article/details/gtgpladpng.html

Py:   def add(a, b): return a + b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpktjixau.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cqqwz.cn/Article/details/gtyntojzoi.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gtxdgojgnz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gtxnkqbssn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gtcaixfoxo.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.pengpengdd.cyou/Article/details/gtpanxmxhk.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jinqigfzy.top/Article/details/gtpqwicsbz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gtuukwpzzw.html

[C02] 默认参数
来源：http://dali.chenlongwang.top/Article/details/gtxmlygfyt.html

Py:   def greet(name="World"): return name
来源：http://dali.xuanzx.com/Article/details/gtsnkmkuok.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jqgfzy.top/Article/details/gtpooyjisu.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrqnglcwb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvowlwjje.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jlsjyb.cn/Article/details/gtimxbvfjr.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.daria6918.cn/Article/details/gtquekfcvo.html

Ruby: def greet(name = "World") = name
来源：http://dali.9152youxi.cn/Article/details/gtxcyjaspi.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yj20258.top/Article/details/gtccbfoztx.html

[C03] 可变参数
来源：http://dali.fengsongda.top/Article/details/gtpclontjq.html

Py:   def total(*args): return sum(args)
来源：http://dali.snrcjt.cn/Article/details/gtsqlnaygd.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.aizwys.cn/Article/details/gtgidnsgie.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tian-w.cn/Article/details/gtmafvetzu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zdqjudy.top/Article/details/gtztrisibz.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhixingplan.top/Article/details/gtkdwmvtal.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cheryme.top/Article/details/gtxclyftgi.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnwcylgww.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shuidangran.top/Article/details/gthwmfccag.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gogol.net.cn/Article/details/gtyryhyiap.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinqigufen.top/Article/details/gtmqxfcroc.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.bjfxy.top/Article/details/gtpnxhytrm.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.daxiang520.top/Article/details/gtkitsvdmm.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yangfankeji.com/Article/details/gtdvdfvucy.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.guannengcc.top/Article/details/gtwokmejbl.html

Go:   // 无：用配置结构体参数
来源：http://dali.quarkkingdee.top/Article/details/gtrhtvjoce.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yj20258.top/Article/details/gtvmssntcm.html

C#:   f(a: 1, b: 2)
来源：http://dali.gaohongyu789.top/Article/details/gtabpkyntr.html

[C05] 返回多个值
来源：http://dali.iojbl.cn/Article/details/gtzzsukyby.html

Py:   return a, b
来源：http://dali.gotoacloud.top/Article/details/gtetjnerfi.html

PHP:  return [$a, $b];
来源：http://dali.nwbrower.top/Article/details/gtnbhxujel.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhixingplan.top/Article/details/gtvlpfkwax.html

TS:   return { a, b };
来源：http://dali.fengsongda.top/Article/details/gthhwznqru.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yvedp.cn/Article/details/gtbrxdlemz.html

Go:   return a, b
来源：http://dali.haohaochexian.top/Article/details/gtrfsacxnj.html

Ruby: return a, b
来源：http://dali.xuetiantiany.cn/Article/details/gtqiaabljv.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.aibaodan.cn/Article/details/gtwaptctwh.html

[C06] 匿名函数 / lambda
来源：http://dali.svipenyu.cn/Article/details/gtlgkmhqlu.html

Py:   square = lambda x: x * x
来源：http://dali.gaohongyu789.top/Article/details/gtsqzqxbkz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.sysykeji.top/Article/details/gthelxjmzz.html

JS:   const square = x => x * x;
来源：http://dali.haohaochexian.top/Article/details/gtwzyhiovb.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.pengpengdd.cyou/Article/details/gtzzbqfnbd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.guannengcc.top/Article/details/gtrwfnlfmj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.9152youxi.cn/Article/details/gtunnojapz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.feifeiyinyue.top/Article/details/gtfhfpuvvs.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xuetiantiany.cn/Article/details/gtyrbddccw.html

[C07] 把函数作为参数传入
来源：http://dali.ppjwa.cn/Article/details/gtdnzopxze.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cheryme.top/Article/details/gthkmcbglj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.haohaochexian.top/Article/details/gtsmwwfcks.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.dashuyun.cn/Article/details/gtoihyqsah.html

TS:   arr.map(String)
来源：http://dali.meibo888.top/Article/details/gtdeojmfne.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gogol.net.cn/Article/details/gtvjydckol.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.sufxvd.cn/Article/details/gtfhfchfkc.html

Ruby: arr.map(&:upcase)
来源：http://dali.bjfxy.top/Article/details/gtzzxelxmp.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yongpay.top/Article/details/gtyodgvxpe.html

[C08] 闭包
来源：http://dali.aibaodan.cn/Article/details/gtseoyricb.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhengqikj.top/Article/details/gtgsfhpdrg.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.iojbl.cn/Article/details/gtoxpexpwi.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yj20258888.top/Article/details/gtmwynaolg.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.316326.xyz/Article/details/gtqhirppnw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.tian-w.cn/Article/details/gtkpktisiq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.iojbl.cn/Article/details/gtzrghusib.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ehwqpu.com/Article/details/gtjhqsfolu.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yuxming.cn/Article/details/gtmyidocry.html

[C09] 递归
来源：http://dali.guannengcc.top/Article/details/gtrdaroxhl.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xylfe.cn/Article/details/gtkzdrsvrb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.vqdsnc.cn/Article/details/gtvlwjqxxg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jiagoushi.top/Article/details/gtoorajcss.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.wangshuangyany.cn/Article/details/gtcosjjhkt.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cheryme.top/Article/details/gtpejhyaal.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.feifeiyinyue.top/Article/details/gtjyyervro.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.redwolf501.top/Article/details/gtpmwvmong.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.svipenyu.cn/Article/details/gtypuparhm.html

[C10] 变量作用域
来源：http://dali.ivvv.top/Article/details/gtnkjuxufy.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hfpthk.cn/Article/details/gtlvqnhmio.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqzmtspmc.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zdqjudy.top/Article/details/gtdusotxrc.html

TS:   同 JS
来源：http://dali.jyoumei.cn/Article/details/gtzsyrbhja.html

Java: 方法内为块级作用域
来源：http://dali.yonumen.top/Article/details/gtohvnvtxe.html

Go:   花括号块级作用域
来源：http://dali.yj202588.top/Article/details/gtjlmklroo.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xinyue.icu/Article/details/gtremvpgfh.html

C#:   块级作用域
来源：http://dali.snrcjt.cn/Article/details/gtpxtimhfg.html

[C11] 模块导入与导出
来源：http://dali.tianlin.xyz/Article/details/gtyfkkmjty.html

Py:   from module import func
来源：http://dali.zycfv.cn/Article/details/gtfkcqfpxl.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.tian-w.cn/Article/details/gtmhdfqyqh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zycfv.cn/Article/details/gtwqoetofd.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtavtwucxn.html

Java: import java.util.List;
来源：http://dali.xuetiantiany.cn/Article/details/gtsoxekaqv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinqigfzy.top/Article/details/gtgfqdbqmg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.dianchejie.cn/Article/details/gtusdydstc.html

C#:   using System.Text;
来源：http://dali.yangfankeji.com/Article/details/gtyirjzzjv.html

[C12] 立即执行函数 IIFE
来源：http://dali.cashguo.top/Article/details/gtwnsbsrkz.html

Py:   (lambda: print("run"))()
来源：http://dali.cdnleiting.top/Article/details/gtebytckko.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jqgufenzy.top/Article/details/gtcuvuokbn.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zycfv.cn/Article/details/gtthuxpuyy.html

TS:   (() => { console.log("run"); })();
来源：http://dali.chenjidiqi.icu/Article/details/gtzdanpdnr.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.tian-w.cn/Article/details/gtczliyjka.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhixingplan.top/Article/details/gtclwevtsc.html

Ruby: -> { puts "run" }.call
来源：http://dali.shuidangran.top/Article/details/gtelsyneei.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.mhx1999.top/Article/details/gtpzylgyzb.html

[C13] 类型声明 / 类型注解
来源：http://dali.quarkkingdee.top/Article/details/gtscyujuuz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.daxiang520.top/Article/details/gtsfgkrcfq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hammf.cn/Article/details/gtnykvnqwe.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.feifeiyinyue.top/Article/details/gtfrtdzync.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gtcekgrwty.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzanryclq.html

Go:   func add(a, b int) int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqbhkbhaa.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zycfv.cn/Article/details/gthskusncb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yuanzhike.top/Article/details/gtiydrwofa.html

[C14] 泛型函数
来源：http://dali.vqdsnc.cn/Article/details/gtmikomqjz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.feifeiyinyue.top/Article/details/gtglbxytlo.html

PHP:  // 无泛型
来源：http://dali.shanyushiyangtech.top/Article/details/gtpejyuhke.html

JS:   // 无泛型
来源：http://dali.jiagoushi.top/Article/details/gtskmyfakf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shangyingyoupin.top/Article/details/gtjhljlokz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hongshengwenyu.top/Article/details/gtfjtvtnsa.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cashguo.top/Article/details/gthjryjqdv.html

Ruby: # 无泛型
来源：http://dali.shangyingyoupin.top/Article/details/gtrupxirsd.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.fzhhl.top/Article/details/gtivccjwao.html

[C15] 解构 / 展开参数
来源：http://dali.jiagoushi.top/Article/details/gtxkkrncdl.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hfpthk.cn/Article/details/gtqfuskfob.html

PHP:  [$a, $b] = $pair;
来源：http://dali.smart0.xyz/Article/details/gtsgnpvutb.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jyoumei.cn/Article/details/gtjqydagtd.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cashguo.top/Article/details/gtbezxzlbt.html

Java: // 无解构
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxzuymnqm.html

Go:   // 无解构
来源：http://dali.gzhubu.top/Article/details/gtvfhynqwy.html

Ruby: a, b = pair
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcecnsvxx.html

C#:   var (a, b) = pair;
来源：http://dali.c1oappe.top/Article/details/gtalgtujmz.html

[C16] 函数 / 方法重载
来源：http://dali.yueranfly.top/Article/details/gtctlsqfwg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhoulong.xyz/Article/details/gtbxlfsgrw.html

PHP:  // 无重载
来源：http://dali.birdmap.top/Article/details/gtgzmzwenj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jyoumei.cn/Article/details/gtnvflddsf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.pycfn.com/Article/details/gtpisdrbeo.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gogol.net.cn/Article/details/gtgrucpnop.html

Go:   // 无重载：用不同函数名
来源：http://dali.meibo888.top/Article/details/gtcbcqdpbo.html

Ruby: # 无重载：靠动态参数
来源：http://dali.svipenyu.cn/Article/details/gtrzaclbpt.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yonumen.top/Article/details/gtexseredg.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtymksxaha.html

D. 数组 / 列表 / 集合
来源：http://dali.mhx1999.top/Article/details/gtbkllzsng.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtpwwjjkgb.html

[D01] 创建数组 / 列表
来源：http://dali.snrcjt.cn/Article/details/gttajdzdgt.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj20258.top/Article/details/gttfrixfpm.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.nanxinkj.top/Article/details/gtyxhertpr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cashguo.top/Article/details/gtrgtdxdbd.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yueranfly.top/Article/details/gtrfuiqwmx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.316326.xyz/Article/details/gtgwqqtxwc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hongshengwenyu.top/Article/details/gtdfcmdxcl.html

Ruby: arr = [1, 2, 3]
来源：http://dali.tianlin.xyz/Article/details/gthsmzukly.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yonumen.top/Article/details/gtjfeaugkc.html

[D02] 追加元素到末尾
来源：http://dali.yuxming.cn/Article/details/gtvfhdcdjp.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hysaishi.cn/Article/details/gtubqxyfze.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jqgufenzy.top/Article/details/gtjltehjnb.html

JS:   arr.push(4);
来源：http://dali.aizwys.cn/Article/details/gtexintdpe.html

TS:   arr.push(4);
来源：http://dali.dashuyun.cn/Article/details/gtbybxymke.html

Java: list.add(4);
来源：http://dali.sysykeji.top/Article/details/gtnbizxtmm.html

Go:   arr = append(arr, 4)
来源：http://dali.svipenyu.cn/Article/details/gtojncubee.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jqgufenzy.top/Article/details/gtuexcosgt.html

C#:   list.Add(4);
来源：http://dali.dianchejie.cn/Article/details/gtvnyxiauk.html

[D03] 在指定位置插入元素
来源：http://dali.hnqzz.top/Article/details/gtntgeinmg.html

Py:   arr.insert(0, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtmikkslxy.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yuxming.cn/Article/details/gtltmzrlru.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cheryme.top/Article/details/gtymhrdbxp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jqgfzy.top/Article/details/gtsbfxxeub.html

Java: list.add(0, 0);
来源：http://dali.wangdashe.top/Article/details/gtgieupjlo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.dashuyun.cn/Article/details/gtlohvmzro.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.guowangkeji.top/Article/details/gtytrjtctn.html

C#:   list.Insert(0, 0);
来源：http://dali.kuanghao11.cn/Article/details/gtcjyappgt.html

[D04] 删除元素
来源：http://dali.ppjwa.cn/Article/details/gteenxknbj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yanxiufei.cn/Article/details/gtzrqeiqtk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shuidangran.top/Article/details/gtttfamyrg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinghuilouyu.cn/Article/details/gtksptwupq.html

TS:   arr.splice(0, 1);
来源：http://dali.yuxming.cn/Article/details/gtabghsoga.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cashguo.top/Article/details/gtgbwjhnpk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.chenlongwang.top/Article/details/gtbyrmiozy.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zycfv.cn/Article/details/gthlgdvrfh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ivvv.top/Article/details/gtncrevtlb.html

[D05] 访问与修改元素
来源：http://dali.hywenlv.cn/Article/details/gtctqaftnz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenjidiqi.icu/Article/details/gtvzlzwouq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.tianlin.xyz/Article/details/gtrbczfhuq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.dianchejie.cn/Article/details/gtqsrtovxx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.aibaodan.cn/Article/details/gtuwtulrcn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cqqwz.cn/Article/details/gtwghzwjby.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gtqezaxkxu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.9152youxi.cn/Article/details/gtbtztjkwv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.birdmap.top/Article/details/gtrdlfhkpo.html

[D06] 数组长度
来源：http://dali.hammf.cn/Article/details/gtokjfjbit.html

Py:   len(arr)
来源：http://dali.yj20258.top/Article/details/gthllmduwc.html

PHP:  count($arr);
来源：http://dali.jinqigufen.top/Article/details/gtdljsvaby.html

JS:   arr.length
来源：http://dali.jqgufenzy.top/Article/details/gtbqwgxtru.html

TS:   arr.length
来源：http://dali.shuidangran.top/Article/details/gtfnwlaerz.html

Java: list.size();
来源：http://dali.pycfn.com/Article/details/gtcvdlfryy.html

Go:   len(arr)
来源：http://dali.tianlin.xyz/Article/details/gttcuodzjr.html

Ruby: arr.length; arr.size
来源：http://dali.yangfankeji.com/Article/details/gtmsalggsk.html

C#:   list.Count;
来源：http://dali.xylfe.cn/Article/details/gtoxaqzxmt.html

[D07] 切片 / 取子数组
来源：http://dali.ydzc1.top/Article/details/gtnscxeagr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ybcxt.top/Article/details/gthshalqut.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cucudq.cn/Article/details/gttiewmkrn.html

JS:   arr.slice(1, 4);
来源：http://dali.yj20258.top/Article/details/gtomdyralj.html

TS:   arr.slice(1, 4);
来源：http://dali.haohaochexian.top/Article/details/gtfvrzttwb.html

Java: list.subList(1, 4);
来源：http://dali.yvedp.cn/Article/details/gtioasvsug.html

Go:   arr[1:4]
来源：http://dali.xylfe.cn/Article/details/gtjxwywykt.html

Ruby: arr[1, 3]
来源：http://dali.vqdsnc.cn/Article/details/gtqxiszrxw.html

C#:   list.GetRange(1, 3);
来源：http://dali.sxryk.cn/Article/details/gtswnfexpx.html

[D08] 合并两个数组
来源：http://dali.pycfn.com/Article/details/gtivutplsy.html

Py:   a + b;  a.extend(b)
来源：http://dali.hnqzz.top/Article/details/gtpwywjeii.html

PHP:  array_merge($a, $b);
来源：http://dali.zhongyouzk.top/Article/details/gtdtaynqee.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yj20258888.top/Article/details/gtzqrgmwjy.html

TS:   [...a, ...b];
来源：http://dali.redwolf501.top/Article/details/gtpaigmhou.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hywenlv.cn/Article/details/gtucjbcvyb.html

Go:   append(a, b...)
来源：http://dali.chenjidiqi.icu/Article/details/gtzcfycogs.html

Ruby: a + b;  a.concat(b)
来源：http://dali.fengsongda.top/Article/details/gtzntghail.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhengqikj.top/Article/details/gtakxltomu.html

[D09] 排序（升序）
来源：http://dali.tian-w.cn/Article/details/gtkyqettlg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gtwrrbtzwi.html

PHP:  sort($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtshjrppvv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jqgfzy.top/Article/details/gtjeorlmvg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gogol.net.cn/Article/details/gtxyjctepf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.nwbrower.top/Article/details/gtmwsrlrbp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtwvpbnzde.html

Ruby: arr.sort
来源：http://dali.zycfv.cn/Article/details/gtaojarypw.html

C#:   list.Sort();
来源：http://dali.chenzaomai.com/Article/details/gtsgtfxkyh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.quarkkingdee.top/Article/details/gtcqtomfcd.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yangfankeji.com/Article/details/gtucqifxlu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258.top/Article/details/gtmvpmfqlg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gzhubu.top/Article/details/gtvpuskjpr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.bjfxy.top/Article/details/gtsdycyajj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yuanzhike.top/Article/details/gtvkpagzkl.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.quarkkingdee.top/Article/details/gtpkzgqxpi.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.guowangkeji.top/Article/details/gtpihkpxsl.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shzxlz.cn/Article/details/gtqdqvnxsc.html

[D11] 反转数组
来源：http://dali.feifeiyinyue.top/Article/details/gtizqyvhuy.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.pycfn.com/Article/details/gtdboyhsbm.html

PHP:  array_reverse($arr);
来源：http://dali.xylfe.cn/Article/details/gtfgpofrzi.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.nanxuanxn.top/Article/details/gtdmhdmcuw.html


<!-- 参考信息 -->