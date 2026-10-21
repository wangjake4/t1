代发 wailian999

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.gogol.net.cn/Article/details/gtgzhedwzl.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.gogol.net.cn/Article/details/gtheaywpgf.html

[B11] 生成数字序列 / 区间
来源：http://dali.ybcxt.top/Article/details/gtvmuqiamy.html

Py:   list(range(0, 10, 2))
来源：http://dali.hysaishi.cn/Article/details/gttahbvene.html

PHP:  range(0, 10, 2);
来源：http://dali.yj202588.top/Article/details/gtexuuivpd.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fzhhl.top/Article/details/gtgtwiqmbz.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.daxiang520.top/Article/details/gtezsrdawx.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.daxiang520.top/Article/details/gtqvfkoenz.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jinghuilouyu.cn/Article/details/gtgeapxswe.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoygpppdv.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhongyouzk.top/Article/details/gtstfdkodw.html

[B12] 跳出多层循环
来源：http://dali.dashuyun.cn/Article/details/gtjrsjinvd.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xuetiantiany.cn/Article/details/gtdsbudshl.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.gzhubu.top/Article/details/gthrcorsup.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yueranfly.top/Article/details/gtnxxifdrx.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.birdmap.top/Article/details/gtdkcqozto.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yanxiufei.cn/Article/details/gtyropjfao.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hywenlv.cn/Article/details/gtrpihwnpl.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xziqi.cn/Article/details/gtrzoaiunh.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.shangyingyoupin.top/Article/details/gtopexrwre.html

[B13] 判断是否为数字
来源：http://dali.chenjidiqi.icu/Article/details/gtbvjbdjxw.html

Py:   isinstance(x, (int, float))
来源：http://dali.tian-w.cn/Article/details/gtinozaofn.html

PHP:  is_numeric($x)
来源：http://dali.wangshuangyany.cn/Article/details/gtlqnlklzp.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenzaomai.com/Article/details/gthquaboen.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ybcxt.top/Article/details/gtxjzlwjlm.html

Java: x instanceof Number
来源：http://dali.daria6918.cn/Article/details/gtxcnhgcxn.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.snrcjt.cn/Article/details/gtiklszutk.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hammf.cn/Article/details/gtsobcboym.html

C#:   x is int or double or decimal
来源：http://dali.dashuyun.cn/Article/details/gttgzsnwva.html

[B14] 判断值是否在集合内
来源：http://dali.yonumen.top/Article/details/gtlqtlhjoq.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yj202588.top/Article/details/gtkwjdrntc.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.chenjidiqi.icu/Article/details/gtqjeqmtmc.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhengqikj.top/Article/details/gttwtcigaa.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.aizwys.cn/Article/details/gtgkntmfdu.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfelipapl.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsxdbcavr.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jinqigfzy.top/Article/details/gthbccidie.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.shuidangran.top/Article/details/gtzljyovpq.html

[B15] 布尔运算与取反
来源：http://dali.nwbrower.top/Article/details/gtvksjejev.html

Py:   a and b or not c
来源：http://dali.yueranfly.top/Article/details/gtzeuycrym.html

PHP:  $a && $b || !$c
来源：http://dali.hfpthk.cn/Article/details/gtsixuktog.html

JS:   a && b || !c
来源：http://dali.yonumen.top/Article/details/gthmpdkogl.html

TS:   a && b || !c
来源：http://dali.zycfv.cn/Article/details/gtwstiwgwn.html

Java: a && b || !c
来源：http://dali.fzhhl.top/Article/details/gtjzkdyels.html

Go:   a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gtmwbfcfdw.html

Ruby: a && b || !c
来源：http://dali.yonumen.top/Article/details/gtwvbcylqi.html

C#:   a && b || !c
来源：http://dali.xuanzx.com/Article/details/gtkrtzmssb.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.sxryk.cn/Article/details/gthprpmtkx.html

Py:   if not data: return
来源：http://dali.xuetiantiany.cn/Article/details/gtsucscndm.html

PHP:  if (!$data) { return; }
来源：http://dali.nanxinkj.top/Article/details/gtaynrdyti.html

JS:   if (!data) return;
来源：http://dali.guowangkeji.top/Article/details/gtjcoibmmx.html

TS:   if (!data) return;
来源：http://dali.dashuyun.cn/Article/details/gtnrzzqpyv.html

Java: if (data == null) return;
来源：http://dali.hnqzz.top/Article/details/gtiseanrgg.html

Go:   if data == nil { return }
来源：http://dali.meibo888.top/Article/details/gtnvhlrmmk.html

Ruby: return if data.nil?
来源：http://dali.yuxming.cn/Article/details/gtqrgagjre.html

C#:   if (data == null) return;
来源：http://dali.jiagoushi.top/Article/details/gtkhpogcbq.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtfxpfryqm.html

C. 函数与作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxthblhvc.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtyfpdacbh.html

[C01] 定义函数
来源：http://dali.cheryme.top/Article/details/gtaasdqicy.html

Py:   def add(a, b): return a + b
来源：http://dali.9152youxi.cn/Article/details/gtrpgdyanz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gtygbkyzps.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gtrfnafksc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcftragph.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtizlncecn.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtentfdonk.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhixingplan.top/Article/details/gtuoybylru.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gtmfglhrme.html

[C02] 默认参数
来源：http://dali.nwbrower.top/Article/details/gtutyzlktd.html

Py:   def greet(name="World"): return name
来源：http://dali.yangfankeji.com/Article/details/gtodeqwsjw.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gteeoihwvc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yangfankeji.com/Article/details/gtyxswzpqt.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtkkwmpyme.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cheryme.top/Article/details/gtizwnvpjt.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.sxryk.cn/Article/details/gtyjgeqpbw.html

Ruby: def greet(name = "World") = name
来源：http://dali.yongpay.top/Article/details/gtmjkzuulc.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.guannengcc.top/Article/details/gtchqfeymq.html

[C03] 可变参数
来源：http://dali.xinyue.icu/Article/details/gtqfoalaed.html

Py:   def total(*args): return sum(args)
来源：http://dali.tanke756.top/Article/details/gtgjvntfxb.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hysaishi.cn/Article/details/gtvstyxwea.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yuxming.cn/Article/details/gtgbdtmast.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.nanxinkj.top/Article/details/gtpoegoqyx.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrsbkqgdb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yuanzhike.top/Article/details/gtoeiubdpc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.tanke756.top/Article/details/gtzdhrroav.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ydzc1.top/Article/details/gtkbfcfwmc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxlnnsqta.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.vqdsnc.cn/Article/details/gtlyrpqqws.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.iojbl.cn/Article/details/gtidecxfgm.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yj202588.top/Article/details/gtzzqnvfbn.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hnqzz.top/Article/details/gthiavqcif.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhixingplan.top/Article/details/gtedizupqa.html

Go:   // 无：用配置结构体参数
来源：http://dali.redwolf501.top/Article/details/gtxxvowtdh.html

Ruby: f(a: 1, b: 2)
来源：http://dali.sxryk.cn/Article/details/gtgmarthha.html

C#:   f(a: 1, b: 2)
来源：http://dali.hfpthk.cn/Article/details/gtxeuvilzy.html

[C05] 返回多个值
来源：http://dali.shangyingyoupin.top/Article/details/gtplemtfji.html

Py:   return a, b
来源：http://dali.sweek.top/Article/details/gtkmjgnpvl.html

PHP:  return [$a, $b];
来源：http://dali.dashuyun.cn/Article/details/gtiegkfpig.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.redwolf501.top/Article/details/gtjnkwmxdm.html

TS:   return { a, b };
来源：http://dali.pycfn.com/Article/details/gtipshhkop.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zycfv.cn/Article/details/gtwdizviwa.html

Go:   return a, b
来源：http://dali.sysykeji.top/Article/details/gthqeequqb.html

Ruby: return a, b
来源：http://dali.ivvv.top/Article/details/gtfgxgxkfq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.aizwys.cn/Article/details/gtkmokjxzf.html

[C06] 匿名函数 / lambda
来源：http://dali.jlsjyb.cn/Article/details/gtmpteodpu.html

Py:   square = lambda x: x * x
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyojnfmbg.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.aizwys.cn/Article/details/gtprbegdla.html

JS:   const square = x => x * x;
来源：http://dali.zhiwuduotai.top/Article/details/gtuqkmiaux.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jyoumei.cn/Article/details/gtjqysmmwn.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.gogol.net.cn/Article/details/gtgiehyfvt.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.redwolf501.top/Article/details/gttrqfinsh.html

Ruby: square = ->(x) { x * x }
来源：http://dali.vqdsnc.cn/Article/details/gtstlzpmkr.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuujpmczy.html

[C07] 把函数作为参数传入
来源：http://dali.jqgfzy.top/Article/details/gtvarlvnsx.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jinqigfzy.top/Article/details/gtofwnldrp.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.tian-w.cn/Article/details/gtfekexzvt.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hywenlv.cn/Article/details/gtnkpimphg.html

TS:   arr.map(String)
来源：http://dali.xuetiantiany.cn/Article/details/gtojoovtnc.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.redwolf501.top/Article/details/gtpovjwcwz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yvedp.cn/Article/details/gtxrktbkil.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhiwuduotai.top/Article/details/gtrwvulrcn.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yonumen.top/Article/details/gtomzwtczc.html

[C08] 闭包
来源：http://dali.jqgufenzy.top/Article/details/gtwkkxbnfj.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.redwolf501.top/Article/details/gtteaekoyq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqutfpzjy.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.birdmap.top/Article/details/gtkmakqtnc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.gaohongyu789.top/Article/details/gttdftmpel.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.iojbl.cn/Article/details/gtewljxbue.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xuetiantiany.cn/Article/details/gtkafoxctz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.andypj.xyz/Article/details/gtkhrxqhxg.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.havefunace.top/Article/details/gtmlopxlar.html

[C09] 递归
来源：http://dali.yj20258.top/Article/details/gtkthusoed.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.smart0.xyz/Article/details/gtvdnftqyh.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jiagoushi.top/Article/details/gtoepmupuk.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.guowangkeji.top/Article/details/gtjnsxammv.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.smart0.xyz/Article/details/gtnlgrggqw.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xylfe.cn/Article/details/gtgazlwvki.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gtowyvdbvt.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xuanzx.com/Article/details/gtwizwleqg.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.gotoacloud.top/Article/details/gttqvfpfyu.html

[C10] 变量作用域
来源：http://dali.hongshengwenyu.top/Article/details/gtfyktcpky.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yj202588.top/Article/details/gteuacxwkm.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.fzhhl.top/Article/details/gtytzcnuta.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yuanzhike.top/Article/details/gtclqfddvt.html

TS:   同 JS
来源：http://dali.yueranfly.top/Article/details/gtzvqanclr.html

Java: 方法内为块级作用域
来源：http://dali.smart0.xyz/Article/details/gtmsgcovhj.html

Go:   花括号块级作用域
来源：http://dali.chenjidiqi.icu/Article/details/gtbtnyddfv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.guannengcc.top/Article/details/gtghxqakjv.html

C#:   块级作用域
来源：http://dali.havefunace.top/Article/details/gttmmnqcuf.html

[C11] 模块导入与导出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtotewgmhr.html

Py:   from module import func
来源：http://dali.xinyue.icu/Article/details/gtaezivdsr.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cdnleiting.top/Article/details/gtrvsjihnd.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xuanzx.com/Article/details/gteyvitnum.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yongpay.top/Article/details/gtxikrihmu.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gtcrujljjz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hfpthk.cn/Article/details/gtwkksmetu.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yongpay.top/Article/details/gtfzsodiab.html

C#:   using System.Text;
来源：http://dali.smart0.xyz/Article/details/gtvsfmkcox.html

[C12] 立即执行函数 IIFE
来源：http://dali.hysaishi.cn/Article/details/gtulswbpzq.html

Py:   (lambda: print("run"))()
来源：http://dali.fengsongda.top/Article/details/gtdvyuhbdr.html

PHP:  (function () { echo "run"; })();
来源：http://dali.chenlongwang.top/Article/details/gtbbfqisos.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yj20258888.top/Article/details/gthxpekjnd.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hongshengwenyu.top/Article/details/gtluoiwlrn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yuanzhike.top/Article/details/gtefnyqilu.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.haohaochexian.top/Article/details/gtrvjsqflo.html

Ruby: -> { puts "run" }.call
来源：http://dali.ehwqpu.com/Article/details/gtigqbyivv.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhoulong.xyz/Article/details/gtqjndpfmv.html

[C13] 类型声明 / 类型注解
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqkuzcfux.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.redwolf501.top/Article/details/gtglkjnvjl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttdzxmztc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cashguo.top/Article/details/gtypglchvr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gteyonytxc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gtopqrbltj.html

Go:   func add(a, b int) int
来源：http://dali.hammf.cn/Article/details/gtwuujzsxp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hysaishi.cn/Article/details/gtkxvjovdj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.chenjidiqi.icu/Article/details/gtgjgqdavo.html

[C14] 泛型函数
来源：http://dali.yongpay.top/Article/details/gtlaoixikl.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hongshengwenyu.top/Article/details/gtogrkugjk.html

PHP:  // 无泛型
来源：http://dali.yj202588.top/Article/details/gttlrpjmoj.html

JS:   // 无泛型
来源：http://dali.yueranfly.top/Article/details/gtnkewnbgx.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.redwolf501.top/Article/details/gtrieetkpu.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.smart0.xyz/Article/details/gthpxyfjdt.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ybcxt.top/Article/details/gtlhhbewfd.html

Ruby: # 无泛型
来源：http://dali.yonumen.top/Article/details/gtowixbift.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.iojbl.cn/Article/details/gtfwonipum.html

[C15] 解构 / 展开参数
来源：http://dali.nanxinkj.top/Article/details/gtwsvevopa.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gotoacloud.top/Article/details/gtlqocjxsy.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gtfxgpoozm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shzxlz.cn/Article/details/gtxoffsoma.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xuanzx.com/Article/details/gtlxrcdysd.html

Java: // 无解构
来源：http://dali.nwbrower.top/Article/details/gtiolqzpjh.html

Go:   // 无解构
来源：http://dali.guowangkeji.top/Article/details/gtiqzikjwv.html

Ruby: a, b = pair
来源：http://dali.ehwqpu.com/Article/details/gtokjdujdv.html

C#:   var (a, b) = pair;
来源：http://dali.cheryme.top/Article/details/gttnccfutk.html

[C16] 函数 / 方法重载
来源：http://dali.yj20258.top/Article/details/gtdkzgmcbq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xuetiantiany.cn/Article/details/gtmreqkrzk.html

PHP:  // 无重载
来源：http://dali.jqgfzy.top/Article/details/gtxgwgznyt.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.aibaodan.cn/Article/details/gtrtrmkgtc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.bjfxy.top/Article/details/gtedqloris.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.kuanghao11.cn/Article/details/gtajuzkuve.html

Go:   // 无重载：用不同函数名
来源：http://dali.yuxming.cn/Article/details/gtzujygjxg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttjpwlumw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gaohongyu789.top/Article/details/gtwmcuhaan.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtplafhcmx.html

D. 数组 / 列表 / 集合
来源：http://dali.guannengcc.top/Article/details/gtxaqdnkgw.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtigpkxakw.html

[D01] 创建数组 / 列表
来源：http://dali.jyoumei.cn/Article/details/gtyaltbesx.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.redwolf501.top/Article/details/gtebbzmahb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.nanxuanxn.top/Article/details/gtqvyplmfn.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cashguo.top/Article/details/gthinyrdnv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhiwuduotai.top/Article/details/gtchrtmlab.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cashguo.top/Article/details/gtvdwaqqlm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yuanzhike.top/Article/details/gtakcwlztl.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbqzxryey.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.haohaochexian.top/Article/details/gtdeskhnis.html

[D02] 追加元素到末尾
来源：http://dali.sweek.top/Article/details/gtdyzwdtlh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.daxiang520.top/Article/details/gteggttiug.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cdnleiting.top/Article/details/gtwozbclom.html

JS:   arr.push(4);
来源：http://dali.chenjidiqi.icu/Article/details/gtbqciybug.html

TS:   arr.push(4);
来源：http://dali.zdqjudy.top/Article/details/gtrufbqkxu.html

Java: list.add(4);
来源：http://dali.jyoumei.cn/Article/details/gtenxevnhh.html

Go:   arr = append(arr, 4)
来源：http://dali.ivvv.top/Article/details/gtatsojnlf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxtkyvoen.html

C#:   list.Add(4);
来源：http://dali.zdqjudy.top/Article/details/gtneydtyvn.html

[D03] 在指定位置插入元素
来源：http://dali.xziqi.cn/Article/details/gtwpntyyls.html

Py:   arr.insert(0, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkryionve.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hnqzz.top/Article/details/gtobawcmbc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.fzhhl.top/Article/details/gtxvxjdgai.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.tianlin.xyz/Article/details/gtkgaraljk.html

Java: list.add(0, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzvjddysp.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yj20258.top/Article/details/gtimnfkdsp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yj20258.top/Article/details/gtbvsjfagc.html

C#:   list.Insert(0, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvxzvpoul.html

[D04] 删除元素
来源：http://dali.zhongyouzk.top/Article/details/gtxsglalzw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hysaishi.cn/Article/details/gtkbhawitq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhengqikj.top/Article/details/gtcrjalibs.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.chenlongwang.top/Article/details/gthjbyqolb.html

TS:   arr.splice(0, 1);
来源：http://dali.hongshengwenyu.top/Article/details/gtfhsisppw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jiagoushi.top/Article/details/gtkxyflfio.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhengqikj.top/Article/details/gtiyfpfjbh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtwntrgumv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.redwolf501.top/Article/details/gtfceqbedi.html

[D05] 访问与修改元素
来源：http://dali.chenlongwang.top/Article/details/gtaplfdvpw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gtvylvxboj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jqgufenzy.top/Article/details/gteownaacz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.mhx1999.top/Article/details/gtkpskyrmc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yonumen.top/Article/details/gtsvuppwfk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yuanzhike.top/Article/details/gtgrisrhir.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.tanke756.top/Article/details/gtsmkoypmq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sufxvd.cn/Article/details/gtougqqown.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gtadznvxcw.html

[D06] 数组长度
来源：http://dali.ybcxt.top/Article/details/gtckztixge.html

Py:   len(arr)
来源：http://dali.ydzc1.top/Article/details/gtdrectrcs.html

PHP:  count($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtmukcfqgy.html

JS:   arr.length
来源：http://dali.daria6918.cn/Article/details/gtryosboft.html

TS:   arr.length
来源：http://dali.redwolf501.top/Article/details/gturzyasxh.html

Java: list.size();
来源：http://dali.zdqjudy.top/Article/details/gtkgeepphx.html

Go:   len(arr)
来源：http://dali.shzxlz.cn/Article/details/gttidmxhov.html

Ruby: arr.length; arr.size
来源：http://dali.mhx1999.top/Article/details/gtstfigkup.html

C#:   list.Count;
来源：http://dali.hysaishi.cn/Article/details/gtqraweeel.html

[D07] 切片 / 取子数组
来源：http://dali.tanke756.top/Article/details/gtkeanusmk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jqgufenzy.top/Article/details/gtvtvdsxjm.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzrahvuvv.html

JS:   arr.slice(1, 4);
来源：http://dali.pengpengdd.cyou/Article/details/gthpgqduig.html

TS:   arr.slice(1, 4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdqlxmwyl.html

Java: list.subList(1, 4);
来源：http://dali.tian-w.cn/Article/details/gtgixoqauk.html

Go:   arr[1:4]
来源：http://dali.redwolf501.top/Article/details/gtunqamhld.html

Ruby: arr[1, 3]
来源：http://dali.aibaodan.cn/Article/details/gtffrllvop.html

C#:   list.GetRange(1, 3);
来源：http://dali.havefunace.top/Article/details/gtyqdkhcte.html

[D08] 合并两个数组
来源：http://dali.sxryk.cn/Article/details/gtnvemnsay.html

Py:   a + b;  a.extend(b)
来源：http://dali.iojbl.cn/Article/details/gtvuecxszh.html

PHP:  array_merge($a, $b);
来源：http://dali.nwbrower.top/Article/details/gtxztbfxgj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.smart0.xyz/Article/details/gtxnpuwylt.html

TS:   [...a, ...b];
来源：http://dali.mhx1999.top/Article/details/gtloehdmvc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.smart0.xyz/Article/details/gtyiqwppxu.html

Go:   append(a, b...)
来源：http://dali.iojbl.cn/Article/details/gtxpkujwii.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpuzoqvzd.html

C#:   a.Concat(b).ToList()
来源：http://dali.yongpay.top/Article/details/gthfbbyroc.html

[D09] 排序（升序）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtltdplzte.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zycfv.cn/Article/details/gttupuwpzt.html

PHP:  sort($arr);
来源：http://dali.guowangkeji.top/Article/details/gtrxnhfrqe.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.316326.xyz/Article/details/gtdgotcici.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.nanxinkj.top/Article/details/gthjottqtf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hysaishi.cn/Article/details/gtoadjmlcv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsrpwyvza.html

Ruby: arr.sort
来源：http://dali.0kj1m.cn/Article/details/gtwkymjuez.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gtyphpvmln.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cheryme.top/Article/details/gtplvhivap.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shuidangran.top/Article/details/gtyjltxxcc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xziqi.cn/Article/details/gtreonpvjh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuanzx.com/Article/details/gtzansxqby.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fzhhl.top/Article/details/gtlxxlrbul.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ehwqpu.com/Article/details/gtkkeiryza.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.aibaodan.cn/Article/details/gtslhsjokz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nanxuanxn.top/Article/details/gtnmjmjvom.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhoulong.xyz/Article/details/gttcbjvgdo.html

[D11] 反转数组
来源：http://dali.gotoacloud.top/Article/details/gtaskinidc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.vqdsnc.cn/Article/details/gtixqtxere.html

PHP:  array_reverse($arr);
来源：http://dali.zhixingplan.top/Article/details/gtdqeqbxlu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.redwolf501.top/Article/details/gtwylwonqx.html


<!-- 参考信息 -->