代发 wailian999

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.xylfe.cn/Article/details/gtgkhfylzo.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.aibaodan.cn/Article/details/gtuvmyxoaq.html

[B11] 生成数字序列 / 区间
来源：http://dali.wangshuangyany.cn/Article/details/gtcvqpctzr.html

Py:   list(range(0, 10, 2))
来源：http://dali.mhx1999.top/Article/details/gtcthtudzq.html

PHP:  range(0, 10, 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtfwxbmmbc.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaqmqpggz.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.havefunace.top/Article/details/gtvasqvszd.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yuxming.cn/Article/details/gtpduhqwdo.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zdqjudy.top/Article/details/gtecglemuy.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinqigufen.top/Article/details/gtgioxjkwd.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yonumen.top/Article/details/gtuynlgkef.html

[B12] 跳出多层循环
来源：http://dali.birdmap.top/Article/details/gtjfaosgar.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ivvv.top/Article/details/gtgqtwfawh.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jinqigfzy.top/Article/details/gtrlfxkuao.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenjidiqi.icu/Article/details/gtvmodsrsf.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfzaqutkz.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmltcvfqt.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.nwbrower.top/Article/details/gtugacpqff.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.wangshuangyany.cn/Article/details/gtiaustaby.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.tian-w.cn/Article/details/gtwsabwdcn.html

[B13] 判断是否为数字
来源：http://dali.redwolf501.top/Article/details/gtinlnxpqm.html

Py:   isinstance(x, (int, float))
来源：http://dali.smart0.xyz/Article/details/gtcduavzwh.html

PHP:  is_numeric($x)
来源：http://dali.pycfn.com/Article/details/gtcznikalg.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sysykeji.top/Article/details/gtasiyyosr.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cdnleiting.top/Article/details/gtmltimezi.html

Java: x instanceof Number
来源：http://dali.dashuyun.cn/Article/details/gtgbiqvnzn.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yangfankeji.com/Article/details/gtbcsvqnip.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zycfv.cn/Article/details/gtifpauzhi.html

C#:   x is int or double or decimal
来源：http://dali.yonumen.top/Article/details/gtlxodihbp.html

[B14] 判断值是否在集合内
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtklleuqnd.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cashguo.top/Article/details/gtdebcmsur.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.bjfxy.top/Article/details/gtwcncmmrq.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.shuidangran.top/Article/details/gtixfpmhcl.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjszosgtr.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hfpthk.cn/Article/details/gtacycmyyg.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.c1oappe.top/Article/details/gtuwgpfvdm.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gtrtnylkih.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttpmihebo.html

[B15] 布尔运算与取反
来源：http://dali.kuanghao11.cn/Article/details/gthrxowndf.html

Py:   a and b or not c
来源：http://dali.sysykeji.top/Article/details/gtrdympxyb.html

PHP:  $a && $b || !$c
来源：http://dali.bjfxy.top/Article/details/gthlsnktee.html

JS:   a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gtetbbmjzy.html

TS:   a && b || !c
来源：http://dali.andypj.xyz/Article/details/gtavbglmsi.html

Java: a && b || !c
来源：http://dali.cucudq.cn/Article/details/gtpiipalhs.html

Go:   a && b || !c
来源：http://dali.c1oappe.top/Article/details/gttohwsanl.html

Ruby: a && b || !c
来源：http://dali.hammf.cn/Article/details/gtxzrbynyz.html

C#:   a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gtmrypuldk.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.shzxlz.cn/Article/details/gtwfxndgpi.html

Py:   if not data: return
来源：http://dali.yangfankeji.com/Article/details/gtkamgcrcu.html

PHP:  if (!$data) { return; }
来源：http://dali.cheryme.top/Article/details/gteygrikuo.html

JS:   if (!data) return;
来源：http://dali.jqgfzy.top/Article/details/gtaposibbl.html

TS:   if (!data) return;
来源：http://dali.ppjwa.cn/Article/details/gtelqmlbpt.html

Java: if (data == null) return;
来源：http://dali.yj202588.top/Article/details/gtfcbergdv.html

Go:   if data == nil { return }
来源：http://dali.jinqigfzy.top/Article/details/gtcglhxsjw.html

Ruby: return if data.nil?
来源：http://dali.kuanghao11.cn/Article/details/gtuprtbell.html

C#:   if (data == null) return;
来源：http://dali.yj20258888.top/Article/details/gtgmbpnxsk.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtggeyvspx.html

C. 函数与作用域
来源：http://dali.pycfn.com/Article/details/gtvplyiafr.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtozfnjhoe.html

[C01] 定义函数
来源：http://dali.haohaochexian.top/Article/details/gtmtqtteef.html

Py:   def add(a, b): return a + b
来源：http://dali.shzxlz.cn/Article/details/gtsoqwowhz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtusuorjda.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtahnbmlpd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsgsyibrg.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtdwcxwass.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.haohaochexian.top/Article/details/gtosjvdkbw.html

Ruby: def add(a, b); a + b; end
来源：http://dali.sufxvd.cn/Article/details/gtwdglyzef.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtgcmqidkk.html

[C02] 默认参数
来源：http://dali.yvedp.cn/Article/details/gtmbgmkjuu.html

Py:   def greet(name="World"): return name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqelinhhy.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cheryme.top/Article/details/gtjptfoqnc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrnotzjgi.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtevcaobyt.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yj20258888.top/Article/details/gttyxhyiep.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.sxryk.cn/Article/details/gtwxrdrzow.html

Ruby: def greet(name = "World") = name
来源：http://dali.yj202588.top/Article/details/gtlyorwtxg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.sysykeji.top/Article/details/gtqlqohpci.html

[C03] 可变参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtqnhhlvlo.html

Py:   def total(*args): return sum(args)
来源：http://dali.yvedp.cn/Article/details/gtubigsyqr.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.sweek.top/Article/details/gttaroexse.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.redwolf501.top/Article/details/gtqvicwmkp.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.aizwys.cn/Article/details/gtyrgtkvch.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.tanke756.top/Article/details/gtrcsxdzzs.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xuetiantiany.cn/Article/details/gtrlrjozdz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jqgufenzy.top/Article/details/gtyxqkwosq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yuanzhike.top/Article/details/gtxeyvekwu.html

[C04] 命名参数 / 关键字参数
来源：http://dali.nanxinkj.top/Article/details/gtdyskaxgw.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.haohaochexian.top/Article/details/gtcunleeox.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.smart0.xyz/Article/details/gtfltuoqoo.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.tianlin.xyz/Article/details/gtjwzhojwe.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.vqdsnc.cn/Article/details/gtofixuvbf.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jinqigfzy.top/Article/details/gtppjwivcz.html

Go:   // 无：用配置结构体参数
来源：http://dali.ppjwa.cn/Article/details/gtmdmobgyj.html

Ruby: f(a: 1, b: 2)
来源：http://dali.daxiang520.top/Article/details/gtbltlsftk.html

C#:   f(a: 1, b: 2)
来源：http://dali.yj20258.top/Article/details/gtdjkdhwsy.html

[C05] 返回多个值
来源：http://dali.chenlongwang.top/Article/details/gtkykvgqmd.html

Py:   return a, b
来源：http://dali.zhoulong.xyz/Article/details/gtvpsxrfbo.html

PHP:  return [$a, $b];
来源：http://dali.bjfxy.top/Article/details/gttnmljwwh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yongpay.top/Article/details/gtszyawitd.html

TS:   return { a, b };
来源：http://dali.yvedp.cn/Article/details/gtvxcvkbnz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ppjwa.cn/Article/details/gtehamrqqc.html

Go:   return a, b
来源：http://dali.chenjidiqi.icu/Article/details/gtfxlloapk.html

Ruby: return a, b
来源：http://dali.yuxming.cn/Article/details/gttjusyptj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.gzhubu.top/Article/details/gtdjaulyxj.html

[C06] 匿名函数 / lambda
来源：http://dali.9152youxi.cn/Article/details/gtfqxoomss.html

Py:   square = lambda x: x * x
来源：http://dali.tian-w.cn/Article/details/gtetkxxrno.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ydzc1.top/Article/details/gtuhwsspmc.html

JS:   const square = x => x * x;
来源：http://dali.tianlin.xyz/Article/details/gtxyortrfr.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.nanxuanxn.top/Article/details/gtemfonfjs.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.cashguo.top/Article/details/gtlrlwtapi.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yj202588.top/Article/details/gtlmjrpsoq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.andypj.xyz/Article/details/gtfobizvlk.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.tian-w.cn/Article/details/gthehxbudq.html

[C07] 把函数作为参数传入
来源：http://dali.gogol.net.cn/Article/details/gtyskmmkyc.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.0kj1m.cn/Article/details/gtslzkinsb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.daxiang520.top/Article/details/gtgpzfbnjf.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.mhx1999.top/Article/details/gtmpxpkvdc.html

TS:   arr.map(String)
来源：http://dali.yuxming.cn/Article/details/gtiorbibbq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cashguo.top/Article/details/gttmxqnvtc.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.pycfn.com/Article/details/gtttgatneo.html

Ruby: arr.map(&:upcase)
来源：http://dali.hnxiangtu.top/Article/details/gtpjrcnens.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.haohaochexian.top/Article/details/gtcrvkoyci.html

[C08] 闭包
来源：http://dali.zycfv.cn/Article/details/gtjbedwjbo.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.316326.xyz/Article/details/gtmbpdakow.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.dashuyun.cn/Article/details/gtnmoqstjy.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zycfv.cn/Article/details/gtjzrnptly.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmmybtpfr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.guowangkeji.top/Article/details/gtguenfbga.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.daxiang520.top/Article/details/gtpvsuyeoq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmqobfzar.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.tian-w.cn/Article/details/gtzvlkqegy.html

[C09] 递归
来源：http://dali.jinqigufen.top/Article/details/gtrdyelsec.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.kuanghao11.cn/Article/details/gteqvnzhkk.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ppjwa.cn/Article/details/gtwymzzkzv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zycfv.cn/Article/details/gtvkkapicw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yueranfly.top/Article/details/gtjnruzngy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jinqigfzy.top/Article/details/gtgtoeueon.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhoulong.xyz/Article/details/gtuwlmzavr.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jyoumei.cn/Article/details/gtnmueswob.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xuetiantiany.cn/Article/details/gthhniumzr.html

[C10] 变量作用域
来源：http://dali.jinqigfzy.top/Article/details/gtsmjjnpxf.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ehwqpu.com/Article/details/gtpwjtfscr.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhiwuduotai.top/Article/details/gtiimhtepr.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.birdmap.top/Article/details/gtmiekfcqd.html

TS:   同 JS
来源：http://dali.yangfankeji.com/Article/details/gteaanltsm.html

Java: 方法内为块级作用域
来源：http://dali.jyoumei.cn/Article/details/gtimljojce.html

Go:   花括号块级作用域
来源：http://dali.bjfxy.top/Article/details/gtgxoazflw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yongpay.top/Article/details/gtmswubidr.html

C#:   块级作用域
来源：http://dali.yanxiufei.cn/Article/details/gtyskrmtwf.html

[C11] 模块导入与导出
来源：http://dali.cheryme.top/Article/details/gtsvxnazuv.html

Py:   from module import func
来源：http://dali.andypj.xyz/Article/details/gtfachhpem.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shuidangran.top/Article/details/gtatcsuywi.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.316326.xyz/Article/details/gtkquozkcd.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cqqwz.cn/Article/details/gtjfrvtgmf.html

Java: import java.util.List;
来源：http://dali.bjfxy.top/Article/details/gtvlolkahv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.aibaodan.cn/Article/details/gtqfoaxfbx.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yonumen.top/Article/details/gttthdlsmw.html

C#:   using System.Text;
来源：http://dali.sxryk.cn/Article/details/gtpdthwpzb.html

[C12] 立即执行函数 IIFE
来源：http://dali.shanyushiyangtech.top/Article/details/gtbuoyfjqj.html

Py:   (lambda: print("run"))()
来源：http://dali.yanxiufei.cn/Article/details/gtwpepqblp.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hysaishi.cn/Article/details/gtptxigvyi.html

JS:   (() => { console.log("run"); })();
来源：http://dali.feifeiyinyue.top/Article/details/gtrylwprvp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xziqi.cn/Article/details/gtynwlxgls.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.iojbl.cn/Article/details/gtgbyrhnqm.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinqigfzy.top/Article/details/gtjovracvb.html

Ruby: -> { puts "run" }.call
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmdvawozn.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.havefunace.top/Article/details/gtyspuhmzf.html

[C13] 类型声明 / 类型注解
来源：http://dali.chenzaomai.com/Article/details/gtsylahclo.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.haohaochexian.top/Article/details/gtikhimqwk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgfzy.top/Article/details/gtbuaejava.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xziqi.cn/Article/details/gtmgvzwuhi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sweek.top/Article/details/gtgokimxoe.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gtnkqehkno.html

Go:   func add(a, b int) int
来源：http://dali.jyoumei.cn/Article/details/gtbyudolne.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.aizwys.cn/Article/details/gtuwfmocyw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.andypj.xyz/Article/details/gthauuvqcj.html

[C14] 泛型函数
来源：http://dali.ppjwa.cn/Article/details/gtrvgnmhtr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yuxming.cn/Article/details/gtoqcvncwb.html

PHP:  // 无泛型
来源：http://dali.ybcxt.top/Article/details/gtxkxwitme.html

JS:   // 无泛型
来源：http://dali.hammf.cn/Article/details/gtivvujmis.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jiagoushi.top/Article/details/gtflqajvyr.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.redwolf501.top/Article/details/gtollnyztq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shuidangran.top/Article/details/gtkdovrooo.html

Ruby: # 无泛型
来源：http://dali.c1oappe.top/Article/details/gtxpcdoylt.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.nanxuanxn.top/Article/details/gtdyxtuuug.html

[C15] 解构 / 展开参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcasxlydk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yvedp.cn/Article/details/gtzhddxzgm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shzxlz.cn/Article/details/gtpehfvcgf.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtlztutoqp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.svipenyu.cn/Article/details/gthecurrvb.html

Java: // 无解构
来源：http://dali.jiagoushi.top/Article/details/gtwbxrkjvr.html

Go:   // 无解构
来源：http://dali.zhengqikj.top/Article/details/gtoeqwcbei.html

Ruby: a, b = pair
来源：http://dali.xylfe.cn/Article/details/gtvwsvxsap.html

C#:   var (a, b) = pair;
来源：http://dali.ppjwa.cn/Article/details/gtlojkdump.html

[C16] 函数 / 方法重载
来源：http://dali.tianlin.xyz/Article/details/gtsocrccdr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cdnleiting.top/Article/details/gtklabgyng.html

PHP:  // 无重载
来源：http://dali.jianghu66.top/Article/details/gtpxxgwixh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.daxiang520.top/Article/details/gtxjsnydoq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yangfankeji.com/Article/details/gtopbkfawp.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gogol.net.cn/Article/details/gtzyvassqa.html

Go:   // 无重载：用不同函数名
来源：http://dali.cashguo.top/Article/details/gtefnzcgbe.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sweek.top/Article/details/gtigtkvomx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gttdacedye.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtizhqpyay.html

D. 数组 / 列表 / 集合
来源：http://dali.jianghu66.top/Article/details/gtwsheeitf.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gttqhldqzk.html

[D01] 创建数组 / 列表
来源：http://dali.havefunace.top/Article/details/gtqlqvrnyu.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hnqzz.top/Article/details/gtaisjshih.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.sysykeji.top/Article/details/gtqomnzwrq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.tian-w.cn/Article/details/gtmrpcygpk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shuidangran.top/Article/details/gthjrxvuqj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinqigufen.top/Article/details/gtifgkcqtq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.daria6918.cn/Article/details/gticixvbhi.html

Ruby: arr = [1, 2, 3]
来源：http://dali.chenjidiqi.icu/Article/details/gtpbxozayg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.birdmap.top/Article/details/gtikazxoop.html

[D02] 追加元素到末尾
来源：http://dali.shangyingyoupin.top/Article/details/gthfegheil.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.nwbrower.top/Article/details/gtfiuvwtkb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jinghuilouyu.cn/Article/details/gtsljzlevc.html

JS:   arr.push(4);
来源：http://dali.zhongyouzk.top/Article/details/gtnsmfkasz.html

TS:   arr.push(4);
来源：http://dali.sweek.top/Article/details/gtdldovtit.html

Java: list.add(4);
来源：http://dali.daria6918.cn/Article/details/gtxotmqelx.html

Go:   arr = append(arr, 4)
来源：http://dali.pycfn.com/Article/details/gtjubhudip.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.dashuyun.cn/Article/details/gtrxwsqbnw.html

C#:   list.Add(4);
来源：http://dali.ehwqpu.com/Article/details/gtsduhkqrj.html

[D03] 在指定位置插入元素
来源：http://dali.yueranfly.top/Article/details/gtmfjbilvv.html

Py:   arr.insert(0, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnxbtoars.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cdnleiting.top/Article/details/gtqejgffxm.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hnxiangtu.top/Article/details/gtylhzuvqz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.smart0.xyz/Article/details/gtkrrankks.html

Java: list.add(0, 0);
来源：http://dali.havefunace.top/Article/details/gtujedoems.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yj202588.top/Article/details/gtbkeqotrp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yonumen.top/Article/details/gtxxxodllv.html

C#:   list.Insert(0, 0);
来源：http://dali.jianghu66.top/Article/details/gtwvqmfzot.html

[D04] 删除元素
来源：http://dali.zdqjudy.top/Article/details/gteviloxei.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jlsjyb.cn/Article/details/gttuvhubbm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.bjfxy.top/Article/details/gtzdvankxr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yonumen.top/Article/details/gtztsaehvd.html

TS:   arr.splice(0, 1);
来源：http://dali.yj202588.top/Article/details/gtitvsevfw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.tanke756.top/Article/details/gtaamxbxaj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yvedp.cn/Article/details/gtwncchxdv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xylfe.cn/Article/details/gtwqjzntlo.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hongshengwenyu.top/Article/details/gtvsnvwxcc.html

[D05] 访问与修改元素
来源：http://dali.yj202588.top/Article/details/gtvdyvybzv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sysykeji.top/Article/details/gtzpsakphc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.gzhubu.top/Article/details/gtmvvljgcp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yj20258.top/Article/details/gtajlbqpcl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.fengsongda.top/Article/details/gtihakocnk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.havefunace.top/Article/details/gtxreuzazu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jiagoushi.top/Article/details/gtfvzbrdrg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj202588.top/Article/details/gtzkwvgdnt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yongpay.top/Article/details/gtqqygntlp.html

[D06] 数组长度
来源：http://dali.meibo888.top/Article/details/gttmfvmjmd.html

Py:   len(arr)
来源：http://dali.yangfankeji.com/Article/details/gtgczzakbk.html

PHP:  count($arr);
来源：http://dali.jiagoushi.top/Article/details/gtthibyjzj.html

JS:   arr.length
来源：http://dali.cashguo.top/Article/details/gtqkbbnclg.html

TS:   arr.length
来源：http://dali.gaohongyu789.top/Article/details/gtxfekcypr.html

Java: list.size();
来源：http://dali.shuidangran.top/Article/details/gtryhrtple.html

Go:   len(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdqzzttlu.html

Ruby: arr.length; arr.size
来源：http://dali.bjfxy.top/Article/details/gtupvpvhkp.html

C#:   list.Count;
来源：http://dali.iojbl.cn/Article/details/gtechsdsuj.html

[D07] 切片 / 取子数组
来源：http://dali.hongshengwenyu.top/Article/details/gtcieppxvp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.wangdashe.top/Article/details/gtnicodpvn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.iojbl.cn/Article/details/gtkaffwvyy.html

JS:   arr.slice(1, 4);
来源：http://dali.yj20258.top/Article/details/gtvotzkwlt.html

TS:   arr.slice(1, 4);
来源：http://dali.aizwys.cn/Article/details/gttnevrbiz.html

Java: list.subList(1, 4);
来源：http://dali.xylfe.cn/Article/details/gttajfifku.html

Go:   arr[1:4]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsvtxvsfa.html

Ruby: arr[1, 3]
来源：http://dali.tianlin.xyz/Article/details/gtajwihxee.html

C#:   list.GetRange(1, 3);
来源：http://dali.kuanghao11.cn/Article/details/gtoxvxoozb.html

[D08] 合并两个数组
来源：http://dali.iojbl.cn/Article/details/gtoezsaars.html

Py:   a + b;  a.extend(b)
来源：http://dali.meibo888.top/Article/details/gtlutyhfxf.html

PHP:  array_merge($a, $b);
来源：http://dali.tanke756.top/Article/details/gtphagdaws.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxvexnojh.html

TS:   [...a, ...b];
来源：http://dali.daria6918.cn/Article/details/gtvoxqtkdg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtsfewcjuj.html

Go:   append(a, b...)
来源：http://dali.aibaodan.cn/Article/details/gtqkorsnnf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yj202588.top/Article/details/gtizshxftd.html

C#:   a.Concat(b).ToList()
来源：http://dali.mhx1999.top/Article/details/gtsibtirpu.html

[D09] 排序（升序）
来源：http://dali.kuanghao11.cn/Article/details/gtwtquvpxy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258888.top/Article/details/gtjtiiglua.html

PHP:  sort($arr);
来源：http://dali.smart0.xyz/Article/details/gtlpwvnyal.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.redwolf501.top/Article/details/gtpdvlulqo.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yuanzhike.top/Article/details/gtuuvkscpa.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.nanxuanxn.top/Article/details/gtubfaatfh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbrbrehtz.html

Ruby: arr.sort
来源：http://dali.smart0.xyz/Article/details/gtzxaghxrx.html

C#:   list.Sort();
来源：http://dali.c1oappe.top/Article/details/gtkzutelmd.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.haohaochexian.top/Article/details/gthevqtxfw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.9152youxi.cn/Article/details/gtmietupji.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.smart0.xyz/Article/details/gtojmmfwzt.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fengsongda.top/Article/details/gtjpwuioor.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgjyxkree.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.havefunace.top/Article/details/gtemrpxmnj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gotoacloud.top/Article/details/gtvkqynkeq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xinyue.icu/Article/details/gtydyjlvli.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.316326.xyz/Article/details/gtnkbumhro.html

[D11] 反转数组
来源：http://dali.cqqwz.cn/Article/details/gtqdedkpqa.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yueranfly.top/Article/details/gtabrtbbjq.html

PHP:  array_reverse($arr);
来源：http://dali.cashguo.top/Article/details/gttjxqvvbe.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hongshengwenyu.top/Article/details/gtvpxdhkeh.html


<!-- 参考信息 -->