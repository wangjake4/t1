代发 wailian999

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yj202588.top/Article/details/gtiksfekpd.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.xuanzx.com/Article/details/gtdjfpjrle.html

[B11] 生成数字序列 / 区间
来源：http://dali.yuxming.cn/Article/details/gtxrzczosg.html

Py:   list(range(0, 10, 2))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkuktvczb.html

PHP:  range(0, 10, 2);
来源：http://dali.gotoacloud.top/Article/details/gtpwyhaowq.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jlsjyb.cn/Article/details/gtbxmyiqlo.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.aizwys.cn/Article/details/gtpwbmzarm.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.dianchejie.cn/Article/details/gtxjlhsgch.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.quarkkingdee.top/Article/details/gtjitydiag.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzilrpfdr.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.gogol.net.cn/Article/details/gtgkthbzhy.html

[B12] 跳出多层循环
来源：http://dali.shuidangran.top/Article/details/gtvotfklox.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jyoumei.cn/Article/details/gtxvlnojix.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yuanzhike.top/Article/details/gtizcipaoj.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gogol.net.cn/Article/details/gtnyhctqxa.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.birdmap.top/Article/details/gtsqmjiwmh.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hongshengwenyu.top/Article/details/gtvaketjtq.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.nanxuanxn.top/Article/details/gtzplunwcf.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.chenjidiqi.icu/Article/details/gtwrnpgswb.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yangfankeji.com/Article/details/gtlgnzecsr.html

[B13] 判断是否为数字
来源：http://dali.hysaishi.cn/Article/details/gtmelzjcig.html

Py:   isinstance(x, (int, float))
来源：http://dali.meibo888.top/Article/details/gtsuxxobgw.html

PHP:  is_numeric($x)
来源：http://dali.wangshuangyany.cn/Article/details/gtzzviegdc.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daxiang520.top/Article/details/gtmnpxjndc.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yvedp.cn/Article/details/gtxwfqymoh.html

Java: x instanceof Number
来源：http://dali.xuetiantiany.cn/Article/details/gtdjvlkjmw.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.gaohongyu789.top/Article/details/gthbtdlcox.html

Ruby: x.is_a?(Numeric)
来源：http://dali.c1oappe.top/Article/details/gtjjhshyfk.html

C#:   x is int or double or decimal
来源：http://dali.cqqwz.cn/Article/details/gtglrkorxc.html

[B14] 判断值是否在集合内
来源：http://dali.gogol.net.cn/Article/details/gtvuzxllvq.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.tianlin.xyz/Article/details/gthfwchkms.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.tanke756.top/Article/details/gtmwxhusfm.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.smart0.xyz/Article/details/gtxiuajajm.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.smart0.xyz/Article/details/gtpldosghr.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtbcrgpkil.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.bjfxy.top/Article/details/gtngeuqnjw.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.tanke756.top/Article/details/gtbqsdkqiq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yuxming.cn/Article/details/gtmbyxrbjc.html

[B15] 布尔运算与取反
来源：http://dali.ivvv.top/Article/details/gtimtvvtdy.html

Py:   a and b or not c
来源：http://dali.jinqigufen.top/Article/details/gtzrsrtcrl.html

PHP:  $a && $b || !$c
来源：http://dali.9152youxi.cn/Article/details/gtrolclrdw.html

JS:   a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gtxyvbtpbt.html

TS:   a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gtobhmkijb.html

Java: a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gtzflzmixw.html

Go:   a && b || !c
来源：http://dali.andypj.xyz/Article/details/gtnobvvmpq.html

Ruby: a && b || !c
来源：http://dali.yuxming.cn/Article/details/gttinvdgiy.html

C#:   a && b || !c
来源：http://dali.cucudq.cn/Article/details/gtibugpmto.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cdnleiting.top/Article/details/gtqnuglhos.html

Py:   if not data: return
来源：http://dali.cucudq.cn/Article/details/gttetwkhej.html

PHP:  if (!$data) { return; }
来源：http://dali.guannengcc.top/Article/details/gtdqzsgsay.html

JS:   if (!data) return;
来源：http://dali.jinqigufen.top/Article/details/gtevmuawhv.html

TS:   if (!data) return;
来源：http://dali.smart0.xyz/Article/details/gtmqdmbths.html

Java: if (data == null) return;
来源：http://dali.zdqjudy.top/Article/details/gtuoujrlhc.html

Go:   if data == nil { return }
来源：http://dali.zhiwuduotai.top/Article/details/gtcgboxppy.html

Ruby: return if data.nil?
来源：http://dali.redwolf501.top/Article/details/gtycdynovj.html

C#:   if (data == null) return;
来源：http://dali.c1oappe.top/Article/details/gtlijelclj.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtplazxcki.html

C. 函数与作用域
来源：http://dali.iojbl.cn/Article/details/gtyzngrjxs.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtknzcviek.html

[C01] 定义函数
来源：http://dali.feifeiyinyue.top/Article/details/gthyxouikt.html

Py:   def add(a, b): return a + b
来源：http://dali.zhiwuduotai.top/Article/details/gtpnwjthzb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gturwwdqvh.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gtodjnpfcr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gtntgmuirr.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gtcrezhqxp.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.aibaodan.cn/Article/details/gtqiaodimi.html

Ruby: def add(a, b); a + b; end
来源：http://dali.svipenyu.cn/Article/details/gtndtitgyj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gtozxfooxb.html

[C02] 默认参数
来源：http://dali.jqgfzy.top/Article/details/gtklzpvzhv.html

Py:   def greet(name="World"): return name
来源：http://dali.cashguo.top/Article/details/gtedcnsgoa.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.0kj1m.cn/Article/details/gtdgeitekq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtzbyfdzgz.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.shuidangran.top/Article/details/gtqnrezxyl.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hnqzz.top/Article/details/gticxugppp.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.9152youxi.cn/Article/details/gtdpmjsedg.html

Ruby: def greet(name = "World") = name
来源：http://dali.yj20258.top/Article/details/gtsexuzxwq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yj20258.top/Article/details/gtlrpkvvqm.html

[C03] 可变参数
来源：http://dali.yueranfly.top/Article/details/gtmwiefnrc.html

Py:   def total(*args): return sum(args)
来源：http://dali.nanxinkj.top/Article/details/gtvhdvqhmp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hongshengwenyu.top/Article/details/gtbaxxbypl.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.wangdashe.top/Article/details/gtxhrttjth.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.vqdsnc.cn/Article/details/gtjhletptq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.smart0.xyz/Article/details/gtmwfgymon.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hfpthk.cn/Article/details/gtnhmicfkl.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.svipenyu.cn/Article/details/gtbtsvlpvz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xuanzx.com/Article/details/gtgbzoejeg.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zycfv.cn/Article/details/gtdttitwfe.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hammf.cn/Article/details/gtxgjjngxj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwmbanqqb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.gaohongyu789.top/Article/details/gtewliamnu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ydzc1.top/Article/details/gtpbdwvlnw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shzxlz.cn/Article/details/gtqikcozfw.html

Go:   // 无：用配置结构体参数
来源：http://dali.ybcxt.top/Article/details/gttirzrkmk.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hammf.cn/Article/details/gtwbtpawsk.html

C#:   f(a: 1, b: 2)
来源：http://dali.nwbrower.top/Article/details/gtvyojeqfg.html

[C05] 返回多个值
来源：http://dali.xziqi.cn/Article/details/gtkmsarkht.html

Py:   return a, b
来源：http://dali.yonumen.top/Article/details/gtjqxwyrgd.html

PHP:  return [$a, $b];
来源：http://dali.pycfn.com/Article/details/gtksclcmvk.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.nanxuanxn.top/Article/details/gtxfephxod.html

TS:   return { a, b };
来源：http://dali.cdnleiting.top/Article/details/gtnblwdvka.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yangfankeji.com/Article/details/gtbadtcwuv.html

Go:   return a, b
来源：http://dali.bjfxy.top/Article/details/gtdtphyyeg.html

Ruby: return a, b
来源：http://dali.zhixingplan.top/Article/details/gtallgonjd.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.nanxuanxn.top/Article/details/gtwkqqujjg.html

[C06] 匿名函数 / lambda
来源：http://dali.jinqigfzy.top/Article/details/gtyxwfdghf.html

Py:   square = lambda x: x * x
来源：http://dali.xuetiantiany.cn/Article/details/gtcolfufpc.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.nanxinkj.top/Article/details/gtnqqowaij.html

JS:   const square = x => x * x;
来源：http://dali.xylfe.cn/Article/details/gtdlhgmakx.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cheryme.top/Article/details/gthdsrhbia.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.mhx1999.top/Article/details/gtlunbhzls.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sweek.top/Article/details/gtsuxfsolf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.smart0.xyz/Article/details/gtttppwsdo.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.svipenyu.cn/Article/details/gtofubqrvc.html

[C07] 把函数作为参数传入
来源：http://dali.meibo888.top/Article/details/gtgreepmqd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ivvv.top/Article/details/gtcnmugutp.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.ehwqpu.com/Article/details/gtffsfkqto.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.guannengcc.top/Article/details/gthhtgjrhg.html

TS:   arr.map(String)
来源：http://dali.ivvv.top/Article/details/gtzsepfbgk.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hnxiangtu.top/Article/details/gtdoduadhg.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.9152youxi.cn/Article/details/gtqbxbifcj.html

Ruby: arr.map(&:upcase)
来源：http://dali.xziqi.cn/Article/details/gtlcoftylw.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.redwolf501.top/Article/details/gtgpslzbyk.html

[C08] 闭包
来源：http://dali.yanxiufei.cn/Article/details/gtopchvkjp.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yuxming.cn/Article/details/gtgajtylpz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.haohaochexian.top/Article/details/gtwhzmsrpx.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.fzhhl.top/Article/details/gtsessgtsf.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jyoumei.cn/Article/details/gtinwjmgmf.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jlsjyb.cn/Article/details/gtkbglopcg.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cdnleiting.top/Article/details/gtayngwhmj.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.aibaodan.cn/Article/details/gtyqsfozcy.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jlsjyb.cn/Article/details/gtbzzjrkrk.html

[C09] 递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxrjiyrfo.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.shuidangran.top/Article/details/gtirhsgjpg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.dashuyun.cn/Article/details/gtuhtosusb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jlsjyb.cn/Article/details/gtinxlmtja.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hongshengwenyu.top/Article/details/gttwgmgdlg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zdqjudy.top/Article/details/gtvrpqfmpy.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.9152youxi.cn/Article/details/gtldyugoow.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ehwqpu.com/Article/details/gtxbqygmoh.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhongyouzk.top/Article/details/gtyqmrezbw.html

[C10] 变量作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gthqqvzwhn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jlsjyb.cn/Article/details/gtjqtfkrhg.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.quarkkingdee.top/Article/details/gtnbklxntr.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.sysykeji.top/Article/details/gtnzlivyuf.html

TS:   同 JS
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqvqegwrm.html

Java: 方法内为块级作用域
来源：http://dali.xziqi.cn/Article/details/gtacwqltmo.html

Go:   花括号块级作用域
来源：http://dali.haohaochexian.top/Article/details/gtlebvlqnu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.gaohongyu789.top/Article/details/gtbdjafrin.html

C#:   块级作用域
来源：http://dali.shzxlz.cn/Article/details/gtwrtcpxbr.html

[C11] 模块导入与导出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbzfluzeo.html

Py:   from module import func
来源：http://dali.jqgfzy.top/Article/details/gtoyixzede.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yongpay.top/Article/details/gtlbbodoou.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zycfv.cn/Article/details/gtxkclkbne.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhoulong.xyz/Article/details/gtrggszqxa.html

Java: import java.util.List;
来源：http://dali.zhengqikj.top/Article/details/gtzdxxvdro.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ybcxt.top/Article/details/gtjwtcgybl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hongshengwenyu.top/Article/details/gtqynlfjwj.html

C#:   using System.Text;
来源：http://dali.jyoumei.cn/Article/details/gttvddsjhy.html

[C12] 立即执行函数 IIFE
来源：http://dali.shuidangran.top/Article/details/gtitojzbxm.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gtlianlybb.html

PHP:  (function () { echo "run"; })();
来源：http://dali.quarkkingdee.top/Article/details/gtwfajmvdr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.aizwys.cn/Article/details/gtbnkvbcpt.html

TS:   (() => { console.log("run"); })();
来源：http://dali.andypj.xyz/Article/details/gtksrahpwc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.tianlin.xyz/Article/details/gthgbwhzev.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.quarkkingdee.top/Article/details/gtnohwtgka.html

Ruby: -> { puts "run" }.call
来源：http://dali.sufxvd.cn/Article/details/gtfmmlbmgp.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.pycfn.com/Article/details/gtatvxrqzc.html

[C13] 类型声明 / 类型注解
来源：http://dali.xinyue.icu/Article/details/gtuwgponpl.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.guannengcc.top/Article/details/gtikshsiqv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aibaodan.cn/Article/details/gtasxywrbw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.birdmap.top/Article/details/gtmeixzayc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gtdpihadnj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gtddoeuxvq.html

Go:   func add(a, b int) int
来源：http://dali.guannengcc.top/Article/details/gtqjejaxdg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xinyue.icu/Article/details/gthjntybcq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yongpay.top/Article/details/gtebqybcde.html

[C14] 泛型函数
来源：http://dali.ivvv.top/Article/details/gtvlowjxot.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.fengsongda.top/Article/details/gtknmueczt.html

PHP:  // 无泛型
来源：http://dali.havefunace.top/Article/details/gtppnxkpjd.html

JS:   // 无泛型
来源：http://dali.hywenlv.cn/Article/details/gtmdcfikmm.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.fengsongda.top/Article/details/gttzgseylj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.316326.xyz/Article/details/gtducnjxkg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuyturxdo.html

Ruby: # 无泛型
来源：http://dali.zhengqikj.top/Article/details/gtnbiccpuo.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.sufxvd.cn/Article/details/gtkieyjwfv.html

[C15] 解构 / 展开参数
来源：http://dali.zdqjudy.top/Article/details/gtudxznoin.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.chenlongwang.top/Article/details/gtgjhodsdj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtofusfgme.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jyoumei.cn/Article/details/gthxswslrl.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoxkizhcr.html

Java: // 无解构
来源：http://dali.sxryk.cn/Article/details/gthrfptcmf.html

Go:   // 无解构
来源：http://dali.vqdsnc.cn/Article/details/gtyklhfxsu.html

Ruby: a, b = pair
来源：http://dali.shanyushiyangtech.top/Article/details/gtzikiqalk.html

C#:   var (a, b) = pair;
来源：http://dali.cheryme.top/Article/details/gtqwfpdenj.html

[C16] 函数 / 方法重载
来源：http://dali.ehwqpu.com/Article/details/gtzddnctjb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.chenzaomai.com/Article/details/gtvaipvhrm.html

PHP:  // 无重载
来源：http://dali.dianchejie.cn/Article/details/gtkakzdhwn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hongshengwenyu.top/Article/details/gtjoettyif.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.chenlongwang.top/Article/details/gtonitjaye.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.bjfxy.top/Article/details/gtrzisyaci.html

Go:   // 无重载：用不同函数名
来源：http://dali.sysykeji.top/Article/details/gtulnbztxo.html

Ruby: # 无重载：靠动态参数
来源：http://dali.316326.xyz/Article/details/gtzhvnxahu.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.daria6918.cn/Article/details/gtyvficawr.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtdqjxnmjq.html

D. 数组 / 列表 / 集合
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvhfreslr.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtutcxvidw.html

[D01] 创建数组 / 列表
来源：http://dali.tanke756.top/Article/details/gtqxkgwwkb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnhoyhvxm.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hnxiangtu.top/Article/details/gtsafoqjpu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.quarkkingdee.top/Article/details/gtofnpwxym.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.tian-w.cn/Article/details/gtlkezxoxk.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.nwbrower.top/Article/details/gtkhpasbzl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.snrcjt.cn/Article/details/gtczwffwnr.html

Ruby: arr = [1, 2, 3]
来源：http://dali.fzhhl.top/Article/details/gtdopmblul.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.dianchejie.cn/Article/details/gtukpoxunl.html

[D02] 追加元素到末尾
来源：http://dali.kuanghao11.cn/Article/details/gtlazldspo.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.wangshuangyany.cn/Article/details/gtugapbrta.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yuanzhike.top/Article/details/gtiyqkppuy.html

JS:   arr.push(4);
来源：http://dali.yj20258.top/Article/details/gtoxqkeurn.html

TS:   arr.push(4);
来源：http://dali.zhoulong.xyz/Article/details/gtjivyvuhj.html

Java: list.add(4);
来源：http://dali.zhongyouzk.top/Article/details/gtxaylghyv.html

Go:   arr = append(arr, 4)
来源：http://dali.c1oappe.top/Article/details/gtiywlcqwb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhengqikj.top/Article/details/gtpaaynfim.html

C#:   list.Add(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmdlpjiyv.html

[D03] 在指定位置插入元素
来源：http://dali.cdnleiting.top/Article/details/gtrmemvlvl.html

Py:   arr.insert(0, 0)
来源：http://dali.guannengcc.top/Article/details/gtxvaqizpc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.kuanghao11.cn/Article/details/gtxksatabg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hammf.cn/Article/details/gtolzpwksz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtukeeznxg.html

Java: list.add(0, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtuxrsugdw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hysaishi.cn/Article/details/gtueqgycgf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jlsjyb.cn/Article/details/gtjwveakgn.html

C#:   list.Insert(0, 0);
来源：http://dali.vqdsnc.cn/Article/details/gtnmxnakhq.html

[D04] 删除元素
来源：http://dali.snrcjt.cn/Article/details/gtbhotburs.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.tianlin.xyz/Article/details/gtvcbzzolo.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sufxvd.cn/Article/details/gtitczygdu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.chenjidiqi.icu/Article/details/gttsvkfouo.html

TS:   arr.splice(0, 1);
来源：http://dali.pycfn.com/Article/details/gtgmgrgnwv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.iojbl.cn/Article/details/gtbclcdphh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.sufxvd.cn/Article/details/gtgyvojpvu.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.chenlongwang.top/Article/details/gtslngyotg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yongpay.top/Article/details/gtapuqjtpj.html

[D05] 访问与修改元素
来源：http://dali.nanxuanxn.top/Article/details/gtqahgbkew.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tianlin.xyz/Article/details/gtmismqrzz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gtvgmfuyna.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinqigufen.top/Article/details/gtarxdoiim.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.tianlin.xyz/Article/details/gtsvazwsgy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.guowangkeji.top/Article/details/gtimwfvfbc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gaohongyu789.top/Article/details/gticzskgad.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shzxlz.cn/Article/details/gtcoozxxrk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.guannengcc.top/Article/details/gtvdddegjp.html

[D06] 数组长度
来源：http://dali.sweek.top/Article/details/gtfdsfndhy.html

Py:   len(arr)
来源：http://dali.yueranfly.top/Article/details/gtbrpuiqmm.html

PHP:  count($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtpsemxrre.html

JS:   arr.length
来源：http://dali.iojbl.cn/Article/details/gtuhserftq.html

TS:   arr.length
来源：http://dali.mhx1999.top/Article/details/gtepahwoez.html

Java: list.size();
来源：http://dali.gotoacloud.top/Article/details/gtroxbhdsa.html

Go:   len(arr)
来源：http://dali.svipenyu.cn/Article/details/gttkcmaqyp.html

Ruby: arr.length; arr.size
来源：http://dali.shuidangran.top/Article/details/gtybtnzyai.html

C#:   list.Count;
来源：http://dali.nanxinkj.top/Article/details/gtqxsgdswc.html

[D07] 切片 / 取子数组
来源：http://dali.andypj.xyz/Article/details/gtjnozccgx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.aizwys.cn/Article/details/gtcmgrnhak.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.guowangkeji.top/Article/details/gtbhddpmsl.html

JS:   arr.slice(1, 4);
来源：http://dali.vqdsnc.cn/Article/details/gtygymeyua.html

TS:   arr.slice(1, 4);
来源：http://dali.feifeiyinyue.top/Article/details/gtepwxkkgt.html

Java: list.subList(1, 4);
来源：http://dali.hnqzz.top/Article/details/gtfvsjgctg.html

Go:   arr[1:4]
来源：http://dali.guowangkeji.top/Article/details/gtphjgimxb.html

Ruby: arr[1, 3]
来源：http://dali.sufxvd.cn/Article/details/gtmlawsspp.html

C#:   list.GetRange(1, 3);
来源：http://dali.hnxiangtu.top/Article/details/gtverfsvtu.html

[D08] 合并两个数组
来源：http://dali.hammf.cn/Article/details/gtuweuriuo.html

Py:   a + b;  a.extend(b)
来源：http://dali.daxiang520.top/Article/details/gtncnaidsa.html

PHP:  array_merge($a, $b);
来源：http://dali.cdnleiting.top/Article/details/gtplxclsts.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.daxiang520.top/Article/details/gtwyttqcdc.html

TS:   [...a, ...b];
来源：http://dali.yangfankeji.com/Article/details/gtbpihvqnb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.chenzaomai.com/Article/details/gtcgwujwjk.html

Go:   append(a, b...)
来源：http://dali.dashuyun.cn/Article/details/gtlzocnngl.html

Ruby: a + b;  a.concat(b)
来源：http://dali.nwbrower.top/Article/details/gtpmwyyeiv.html

C#:   a.Concat(b).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtoxaulkvw.html

[D09] 排序（升序）
来源：http://dali.dianchejie.cn/Article/details/gtrgodpssr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cheryme.top/Article/details/gtkjiwpqkz.html

PHP:  sort($arr);
来源：http://dali.xuanzx.com/Article/details/gtmtfnsmxw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.smart0.xyz/Article/details/gtoqihtfwu.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xylfe.cn/Article/details/gtricgfkfl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.dashuyun.cn/Article/details/gtfpeaqcve.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gturmcmawx.html

Ruby: arr.sort
来源：http://dali.jqgufenzy.top/Article/details/gtxslhxgdd.html

C#:   list.Sort();
来源：http://dali.guannengcc.top/Article/details/gthjbwqxoh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.tanke756.top/Article/details/gtmubyqkjb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jianghu66.top/Article/details/gtqukawhti.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xuetiantiany.cn/Article/details/gtwngwnclc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.birdmap.top/Article/details/gtaxwspblc.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gaohongyu789.top/Article/details/gtjsfmzbbb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.fengsongda.top/Article/details/gtmcqnvlzu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.chenlongwang.top/Article/details/gtwswmhazj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxwprhvvg.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hywenlv.cn/Article/details/gtvbnamycw.html

[D11] 反转数组
来源：http://dali.fzhhl.top/Article/details/gtpprfytrf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.snrcjt.cn/Article/details/gtcboalhnp.html

PHP:  array_reverse($arr);
来源：http://dali.tanke756.top/Article/details/gtnstroqhb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sxryk.cn/Article/details/gtcesmcnne.html


<!-- 参考信息 -->