代发 wailian999

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.xuanzx.com/Article/details/gtngofkutk.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.daxiang520.top/Article/details/gtgiyvrgjd.html

[B11] 生成数字序列 / 区间
来源：http://dali.sweek.top/Article/details/gtwptvbnta.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhoulong.xyz/Article/details/gtfzluhxrn.html

PHP:  range(0, 10, 2);
来源：http://dali.haohaochexian.top/Article/details/gtnwhovtea.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.316326.xyz/Article/details/gtoustfyxj.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tian-w.cn/Article/details/gtidorxrwe.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.gaohongyu789.top/Article/details/gtsnqlmziy.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.bjfxy.top/Article/details/gtcoyatafb.html

Ruby: (0...10).step(2).to_a
来源：http://dali.cashguo.top/Article/details/gtidpulyey.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yangfankeji.com/Article/details/gtojnllmsv.html

[B12] 跳出多层循环
来源：http://dali.pycfn.com/Article/details/gtowaedaja.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.haohaochexian.top/Article/details/gtaemecyyl.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hfpthk.cn/Article/details/gtyveflmmi.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgufenzy.top/Article/details/gthvhdgasl.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cashguo.top/Article/details/gtwzsckwwq.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.bjfxy.top/Article/details/gtokwvhvfo.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xuanzx.com/Article/details/gtlffikqzw.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jinyuanbaomall.cn/Article/details/gthdduuqsn.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.andypj.xyz/Article/details/gtxxfcmrld.html

[B13] 判断是否为数字
来源：http://dali.xuanzx.com/Article/details/gtzhjmzgez.html

Py:   isinstance(x, (int, float))
来源：http://dali.yanxiufei.cn/Article/details/gtakumqxdu.html

PHP:  is_numeric($x)
来源：http://dali.jiagoushi.top/Article/details/gtcgwbzzoj.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvnentmfi.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yongpay.top/Article/details/gtllmelnpo.html

Java: x instanceof Number
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzxiilujr.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.vqdsnc.cn/Article/details/gtvebocokh.html

Ruby: x.is_a?(Numeric)
来源：http://dali.tian-w.cn/Article/details/gtxiimzbdn.html

C#:   x is int or double or decimal
来源：http://dali.tian-w.cn/Article/details/gtngmzxcoj.html

[B14] 判断值是否在集合内
来源：http://dali.guannengcc.top/Article/details/gtmambkhuq.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.pycfn.com/Article/details/gtwbokswjw.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.cashguo.top/Article/details/gttxfcsmaf.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.svipenyu.cn/Article/details/gtqtbmohts.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.mhx1999.top/Article/details/gtehaavjsy.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.aibaodan.cn/Article/details/gtobjprafv.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.cheryme.top/Article/details/gtgttlamum.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.chenzaomai.com/Article/details/gttdtwijmd.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.havefunace.top/Article/details/gtcjbnnbyj.html

[B15] 布尔运算与取反
来源：http://dali.xuetiantiany.cn/Article/details/gtvipuukrk.html

Py:   a and b or not c
来源：http://dali.zhongyouzk.top/Article/details/gtytakusts.html

PHP:  $a && $b || !$c
来源：http://dali.zhengqikj.top/Article/details/gtmvtdbgxs.html

JS:   a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gtrlpbhuwo.html

TS:   a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gtnpyaxlva.html

Java: a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gtgvlurzun.html

Go:   a && b || !c
来源：http://dali.316326.xyz/Article/details/gtzudupaai.html

Ruby: a && b || !c
来源：http://dali.xinyue.icu/Article/details/gtdeenhnwn.html

C#:   a && b || !c
来源：http://dali.sxryk.cn/Article/details/gtlrhdwsfw.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.guowangkeji.top/Article/details/gtqglrnnxm.html

Py:   if not data: return
来源：http://dali.zdqjudy.top/Article/details/gtztwhywet.html

PHP:  if (!$data) { return; }
来源：http://dali.ybcxt.top/Article/details/gtmxbjhyjj.html

JS:   if (!data) return;
来源：http://dali.quarkkingdee.top/Article/details/gtsucktqpv.html

TS:   if (!data) return;
来源：http://dali.yonumen.top/Article/details/gtcfsxsqgq.html

Java: if (data == null) return;
来源：http://dali.shanyushiyangtech.top/Article/details/gtqjuccayn.html

Go:   if data == nil { return }
来源：http://dali.dashuyun.cn/Article/details/gtbsgyquzm.html

Ruby: return if data.nil?
来源：http://dali.tian-w.cn/Article/details/gtgnzlnbsf.html

C#:   if (data == null) return;
来源：http://dali.jinghuilouyu.cn/Article/details/gtkjjgiiun.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtjhgwzfcc.html

C. 函数与作用域
来源：http://dali.havefunace.top/Article/details/gtqqhksiex.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gthwokdojr.html

[C01] 定义函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtcuksuhzz.html

Py:   def add(a, b): return a + b
来源：http://dali.jinghuilouyu.cn/Article/details/gtafklwhjk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiyuvqhji.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gtntnuskvj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gtjevirbkb.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gtslikdzcc.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyoqpssti.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yj20258888.top/Article/details/gtdwrcpjdw.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gtstlzvmpy.html

[C02] 默认参数
来源：http://dali.zhoulong.xyz/Article/details/gtgkntejtw.html

Py:   def greet(name="World"): return name
来源：http://dali.zhixingplan.top/Article/details/gtmrhswwyb.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.pycfn.com/Article/details/gtyrxjdevo.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gtfgketxts.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hammf.cn/Article/details/gtoohjwghi.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xuetiantiany.cn/Article/details/gtgczdzdsh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhixingplan.top/Article/details/gtcgxzpxzp.html

Ruby: def greet(name = "World") = name
来源：http://dali.9152youxi.cn/Article/details/gtdeldifyj.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtntlmtsmk.html

[C03] 可变参数
来源：http://dali.hywenlv.cn/Article/details/gtjwxiypbm.html

Py:   def total(*args): return sum(args)
来源：http://dali.haohaochexian.top/Article/details/gthketqsgj.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.daxiang520.top/Article/details/gtxginohfq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.pengpengdd.cyou/Article/details/gttsomsuum.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sufxvd.cn/Article/details/gtsicvncfx.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.nanxuanxn.top/Article/details/gtsxztcmqf.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yj20258.top/Article/details/gtceyydvws.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zycfv.cn/Article/details/gtnpymyocu.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.tian-w.cn/Article/details/gtmqbdbdyi.html

[C04] 命名参数 / 关键字参数
来源：http://dali.pycfn.com/Article/details/gttbjjsuro.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhongyouzk.top/Article/details/gthwqhhpfs.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.gogol.net.cn/Article/details/gtdhplemcu.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.sweek.top/Article/details/gtdkbdpvbw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shanyushiyangtech.top/Article/details/gtjvxcdlkj.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shuidangran.top/Article/details/gtsorqeear.html

Go:   // 无：用配置结构体参数
来源：http://dali.tianlin.xyz/Article/details/gtshrexliw.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yueranfly.top/Article/details/gtzotzlmdx.html

C#:   f(a: 1, b: 2)
来源：http://dali.gotoacloud.top/Article/details/gtdkruxqkq.html

[C05] 返回多个值
来源：http://dali.quarkkingdee.top/Article/details/gtatwmzexz.html

Py:   return a, b
来源：http://dali.nwbrower.top/Article/details/gtckyaavkd.html

PHP:  return [$a, $b];
来源：http://dali.dianchejie.cn/Article/details/gtsxlyhivh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xuetiantiany.cn/Article/details/gtbwclxsgc.html

TS:   return { a, b };
来源：http://dali.redwolf501.top/Article/details/gtnriqexog.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.guannengcc.top/Article/details/gtmgdcaots.html

Go:   return a, b
来源：http://dali.hysaishi.cn/Article/details/gtdustrrej.html

Ruby: return a, b
来源：http://dali.tianlin.xyz/Article/details/gtbpqbrujf.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.tian-w.cn/Article/details/gtmyebfulg.html

[C06] 匿名函数 / lambda
来源：http://dali.meibo888.top/Article/details/gtgqsprsvn.html

Py:   square = lambda x: x * x
来源：http://dali.jinqigfzy.top/Article/details/gtarvgneya.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhengqikj.top/Article/details/gtyjrlwcft.html

JS:   const square = x => x * x;
来源：http://dali.316326.xyz/Article/details/gtviolhdts.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtracdgllh.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.cheryme.top/Article/details/gtqivejmpy.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.cucudq.cn/Article/details/gtqfyhjgjw.html

Ruby: square = ->(x) { x * x }
来源：http://dali.meibo888.top/Article/details/gtkgacflzr.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.smart0.xyz/Article/details/gtcdhlaksy.html

[C07] 把函数作为参数传入
来源：http://dali.xylfe.cn/Article/details/gtmseynsxg.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaglrxflj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.gaohongyu789.top/Article/details/gtsujcgqyk.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.aizwys.cn/Article/details/gtcuiorttx.html

TS:   arr.map(String)
来源：http://dali.guannengcc.top/Article/details/gtsoiyqrtu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xinyue.icu/Article/details/gtcqktnlfl.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xuetiantiany.cn/Article/details/gtdusfvwyy.html

Ruby: arr.map(&:upcase)
来源：http://dali.tian-w.cn/Article/details/gtazogyuuc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.tianlin.xyz/Article/details/gthijgzihj.html

[C08] 闭包
来源：http://dali.9152youxi.cn/Article/details/gtdqcaambk.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.tanke756.top/Article/details/gteufidqbg.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.0kj1m.cn/Article/details/gtbhcjoqex.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.316326.xyz/Article/details/gtyuqwcsgk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cashguo.top/Article/details/gtqmeemnsc.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhiwuduotai.top/Article/details/gtphhhpyuz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.gogol.net.cn/Article/details/gtgdbvdbtg.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.aibaodan.cn/Article/details/gtsuyowhex.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ehwqpu.com/Article/details/gtkkjkqigu.html

[C09] 递归
来源：http://dali.jlsjyb.cn/Article/details/gtngfsrhoe.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jinqigufen.top/Article/details/gtwxtnpjgr.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.tian-w.cn/Article/details/gtxibxhmvv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shzxlz.cn/Article/details/gtwkuaunaa.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gotoacloud.top/Article/details/gthzxemfbc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.316326.xyz/Article/details/gthzbthhtc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhengqikj.top/Article/details/gtxptnabhn.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.haohaochexian.top/Article/details/gtcdpbonqj.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.nwbrower.top/Article/details/gtxpzmtlby.html

[C10] 变量作用域
来源：http://dali.gotoacloud.top/Article/details/gttynpihxy.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.feifeiyinyue.top/Article/details/gtiaphqfgz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zdqjudy.top/Article/details/gtbwnakoyt.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gotoacloud.top/Article/details/gtsrflsvbz.html

TS:   同 JS
来源：http://dali.snrcjt.cn/Article/details/gtjvayqymz.html

Java: 方法内为块级作用域
来源：http://dali.ydzc1.top/Article/details/gtajyjlmpm.html

Go:   花括号块级作用域
来源：http://dali.nwbrower.top/Article/details/gtxbiikdpy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrtyezogd.html

C#:   块级作用域
来源：http://dali.cdnleiting.top/Article/details/gtsnwnglpt.html

[C11] 模块导入与导出
来源：http://dali.sysykeji.top/Article/details/gtvjznnlet.html

Py:   from module import func
来源：http://dali.zdqjudy.top/Article/details/gtwnecppwh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfdnziiou.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zycfv.cn/Article/details/gtdqlgtehb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cdnleiting.top/Article/details/gtxjqbezbw.html

Java: import java.util.List;
来源：http://dali.aizwys.cn/Article/details/gttjwuxgve.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ydzc1.top/Article/details/gtggvhzyyw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.smart0.xyz/Article/details/gthmttrdea.html

C#:   using System.Text;
来源：http://dali.zhixingplan.top/Article/details/gtomhgwyww.html

[C12] 立即执行函数 IIFE
来源：http://dali.iojbl.cn/Article/details/gtlhtrolhd.html

Py:   (lambda: print("run"))()
来源：http://dali.hnxiangtu.top/Article/details/gtcdtgakzn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yangfankeji.com/Article/details/gtycocoopf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinqigfzy.top/Article/details/gtkcouvycy.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shuidangran.top/Article/details/gtihknedef.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.andypj.xyz/Article/details/gtzznvaafq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shzxlz.cn/Article/details/gtzitgwgut.html

Ruby: -> { puts "run" }.call
来源：http://dali.wangdashe.top/Article/details/gtpttljnkq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gthexwmvmw.html

[C13] 类型声明 / 类型注解
来源：http://dali.hongshengwenyu.top/Article/details/gtpdzftmze.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.smart0.xyz/Article/details/gtflsdprgj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xinyue.icu/Article/details/gtjkpoemwk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsfahobeu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtofbstkml.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gttipacfou.html

Go:   func add(a, b int) int
来源：http://dali.meibo888.top/Article/details/gthwapiqvi.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shzxlz.cn/Article/details/gtoxduegdd.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.fengsongda.top/Article/details/gtprvqfzwa.html

[C14] 泛型函数
来源：http://dali.cheryme.top/Article/details/gtcldcfwgc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.316326.xyz/Article/details/gtzkjdffte.html

PHP:  // 无泛型
来源：http://dali.fzhhl.top/Article/details/gtpzofpvfr.html

JS:   // 无泛型
来源：http://dali.chenlongwang.top/Article/details/gthwnmdutx.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.wangshuangyany.cn/Article/details/gtilbnfbne.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.pengpengdd.cyou/Article/details/gtsjmvengz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.c1oappe.top/Article/details/gtvcbqxehp.html

Ruby: # 无泛型
来源：http://dali.xinyue.icu/Article/details/gtmwfyoshq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jlsjyb.cn/Article/details/gtgrbyjlkt.html

[C15] 解构 / 展开参数
来源：http://dali.sysykeji.top/Article/details/gtjsrltkik.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xuetiantiany.cn/Article/details/gtxpnnryzm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hnqzz.top/Article/details/gtwoeklhla.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jqgufenzy.top/Article/details/gtxalugsfr.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfgdnyswr.html

Java: // 无解构
来源：http://dali.316326.xyz/Article/details/gtmizxvvyl.html

Go:   // 无解构
来源：http://dali.hnqzz.top/Article/details/gtdyqvpevu.html

Ruby: a, b = pair
来源：http://dali.aizwys.cn/Article/details/gtupnkhjpm.html

C#:   var (a, b) = pair;
来源：http://dali.hfpthk.cn/Article/details/gtfxdsfzch.html

[C16] 函数 / 方法重载
来源：http://dali.jqgfzy.top/Article/details/gthfkokhuq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hongshengwenyu.top/Article/details/gtcuaaosfm.html

PHP:  // 无重载
来源：http://dali.xuetiantiany.cn/Article/details/gtneaolfwv.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cheryme.top/Article/details/gtcancalpj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xylfe.cn/Article/details/gtrsgveqbz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yuxming.cn/Article/details/gtuqiikhgx.html

Go:   // 无重载：用不同函数名
来源：http://dali.aizwys.cn/Article/details/gtommmhgjc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ehwqpu.com/Article/details/gtqqbnvpxe.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hnqzz.top/Article/details/gtaejmkgbg.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtthvyqfvl.html

D. 数组 / 列表 / 集合
来源：http://dali.zhongyouzk.top/Article/details/gtvyqkeuap.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtyatuboip.html

[D01] 创建数组 / 列表
来源：http://dali.zhoulong.xyz/Article/details/gtbwaegwju.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.chenzaomai.com/Article/details/gtnwhsprql.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfdzprrdb.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhengqikj.top/Article/details/gtoznahrac.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.iojbl.cn/Article/details/gtfdafuvbp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hywenlv.cn/Article/details/gtyftyyvuh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.wangdashe.top/Article/details/gtiajlnlqm.html

Ruby: arr = [1, 2, 3]
来源：http://dali.chenlongwang.top/Article/details/gtljxawipx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.havefunace.top/Article/details/gtvasqmpoj.html

[D02] 追加元素到末尾
来源：http://dali.chenzaomai.com/Article/details/gtdczkcbau.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yongpay.top/Article/details/gtoyacbsry.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jinghuilouyu.cn/Article/details/gtgxwuduwn.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gtperqbkvv.html

TS:   arr.push(4);
来源：http://dali.zhongyouzk.top/Article/details/gtijsmbcke.html

Java: list.add(4);
来源：http://dali.zhongyouzk.top/Article/details/gtbxufqwjv.html

Go:   arr = append(arr, 4)
来源：http://dali.andypj.xyz/Article/details/gtucxstmcf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.quarkkingdee.top/Article/details/gthvxjpdhf.html

C#:   list.Add(4);
来源：http://dali.hnqzz.top/Article/details/gteiybwgxi.html

[D03] 在指定位置插入元素
来源：http://dali.cashguo.top/Article/details/gtqmiimuld.html

Py:   arr.insert(0, 0)
来源：http://dali.pycfn.com/Article/details/gtqdmxvrsf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jlsjyb.cn/Article/details/gtzdpjesqx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.pycfn.com/Article/details/gtyyjeireu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hnxiangtu.top/Article/details/gtnvyeegzd.html

Java: list.add(0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gturjiasyi.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.wangshuangyany.cn/Article/details/gtlpsmliri.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yuanzhike.top/Article/details/gtiyjnqrtp.html

C#:   list.Insert(0, 0);
来源：http://dali.ivvv.top/Article/details/gtsslbwcgf.html

[D04] 删除元素
来源：http://dali.jinqigufen.top/Article/details/gtoyaayimy.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hysaishi.cn/Article/details/gthsepwnlh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtnhdkygiz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cucudq.cn/Article/details/gtfprfhmcg.html

TS:   arr.splice(0, 1);
来源：http://dali.9152youxi.cn/Article/details/gtbrctexmz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtpehfkkdj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jlsjyb.cn/Article/details/gtsrvtuuow.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.tianlin.xyz/Article/details/gtqhnhawrg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ybcxt.top/Article/details/gtbebbjkav.html

[D05] 访问与修改元素
来源：http://dali.zdqjudy.top/Article/details/gtxmxmtdyq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sysykeji.top/Article/details/gtkqpezeml.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hnqzz.top/Article/details/gtvresgppq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.fengsongda.top/Article/details/gtntorrvrq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.kuanghao11.cn/Article/details/gtgeefwdcs.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.pycfn.com/Article/details/gtymprdzkp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.fengsongda.top/Article/details/gtbpgccqcb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gtxmslifve.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gzhubu.top/Article/details/gtugcjnrfx.html

[D06] 数组长度
来源：http://dali.yj20258.top/Article/details/gtftfzytcg.html

Py:   len(arr)
来源：http://dali.9152youxi.cn/Article/details/gtmfpknpqc.html

PHP:  count($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtvcomugyu.html

JS:   arr.length
来源：http://dali.zhixingplan.top/Article/details/gtskpxtgcl.html

TS:   arr.length
来源：http://dali.xinyue.icu/Article/details/gtctfrfgmw.html

Java: list.size();
来源：http://dali.jiagoushi.top/Article/details/gttvfucbko.html

Go:   len(arr)
来源：http://dali.chenlongwang.top/Article/details/gtarvtisrp.html

Ruby: arr.length; arr.size
来源：http://dali.hysaishi.cn/Article/details/gtdsaravty.html

C#:   list.Count;
来源：http://dali.shzxlz.cn/Article/details/gtbweyrdrz.html

[D07] 切片 / 取子数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfvozzwua.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shuidangran.top/Article/details/gtrhvreplx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtiwkqbklq.html

JS:   arr.slice(1, 4);
来源：http://dali.jiagoushi.top/Article/details/gtgsujznxj.html

TS:   arr.slice(1, 4);
来源：http://dali.sysykeji.top/Article/details/gtucedmlsz.html

Java: list.subList(1, 4);
来源：http://dali.guowangkeji.top/Article/details/gtosypvpzi.html

Go:   arr[1:4]
来源：http://dali.zhengqikj.top/Article/details/gtfgirxfsw.html

Ruby: arr[1, 3]
来源：http://dali.gotoacloud.top/Article/details/gtvulpzjov.html

C#:   list.GetRange(1, 3);
来源：http://dali.daxiang520.top/Article/details/gtrjziqewe.html

[D08] 合并两个数组
来源：http://dali.sufxvd.cn/Article/details/gtdmvodnpz.html

Py:   a + b;  a.extend(b)
来源：http://dali.daxiang520.top/Article/details/gtbhgssjwp.html

PHP:  array_merge($a, $b);
来源：http://dali.hongshengwenyu.top/Article/details/gttyhkwehn.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sxryk.cn/Article/details/gtebsktepn.html

TS:   [...a, ...b];
来源：http://dali.jqgfzy.top/Article/details/gtjpaaezkq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.fzhhl.top/Article/details/gtlrzuggup.html

Go:   append(a, b...)
来源：http://dali.316326.xyz/Article/details/gtlhazjxgu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yj20258888.top/Article/details/gtpchymrww.html

C#:   a.Concat(b).ToList()
来源：http://dali.jinqigufen.top/Article/details/gtphlrbcyb.html

[D09] 排序（升序）
来源：http://dali.gotoacloud.top/Article/details/gtehhyvymw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuanzhike.top/Article/details/gthuzxaqrt.html

PHP:  sort($arr);
来源：http://dali.chenlongwang.top/Article/details/gtszkplela.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.daria6918.cn/Article/details/gtywfjlpwv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.0kj1m.cn/Article/details/gtioxvscil.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.wangshuangyany.cn/Article/details/gtnxetshdo.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhixingplan.top/Article/details/gtcavrjqtj.html

Ruby: arr.sort
来源：http://dali.birdmap.top/Article/details/gtqbssiezt.html

C#:   list.Sort();
来源：http://dali.ybcxt.top/Article/details/gtfgsraqno.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.chenzaomai.com/Article/details/gtuihoszvh.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zdqjudy.top/Article/details/gtzvqphint.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj202588.top/Article/details/gtftvztujb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.havefunace.top/Article/details/gtwkktgowo.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthvcdnhuu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.nanxuanxn.top/Article/details/gtshbfdoag.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yj20258888.top/Article/details/gtrjmjaqei.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhongyouzk.top/Article/details/gtfqynrxws.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.wangshuangyany.cn/Article/details/gtddujyrmc.html

[D11] 反转数组
来源：http://dali.fengsongda.top/Article/details/gtnlkdxmtn.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ivvv.top/Article/details/gttovyxqdc.html

PHP:  array_reverse($arr);
来源：http://dali.xuanzx.com/Article/details/gtjspxdubf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yvedp.cn/Article/details/gtnhtsybxp.html


<!-- 参考信息 -->