代发 wailian999

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.sxryk.cn/Article/details/gtdizdrcce.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.bjfxy.top/Article/details/gtjioehsar.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.tian-w.cn/Article/details/gtnwramcnq.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jinqigfzy.top/Article/details/gtogskzoco.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zycfv.cn/Article/details/gtwhordtfw.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.aizwys.cn/Article/details/gtbjshcjgb.html

[B11] 生成数字序列 / 区间
来源：http://dali.yuxming.cn/Article/details/gtfdnqpukf.html

Py:   list(range(0, 10, 2))
来源：http://dali.316326.xyz/Article/details/gtlzvylxdn.html

PHP:  range(0, 10, 2);
来源：http://dali.tian-w.cn/Article/details/gtsjzycazv.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xinyue.icu/Article/details/gthebwouff.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xinyue.icu/Article/details/gtjtyhfqps.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.sufxvd.cn/Article/details/gtngeazfdf.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.c1oappe.top/Article/details/gtpqxlwpvr.html

Ruby: (0...10).step(2).to_a
来源：http://dali.cdnleiting.top/Article/details/gtwnidciyr.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.sweek.top/Article/details/gtzplembgn.html

[B12] 跳出多层循环
来源：http://dali.jinqigufen.top/Article/details/gteemingmw.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.wangdashe.top/Article/details/gtkjgkbcjo.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.gogol.net.cn/Article/details/gtzoiuubte.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jiagoushi.top/Article/details/gtrvosnzyp.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnxiangtu.top/Article/details/gtoqyhiiol.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigfzy.top/Article/details/gtzvrfdhbw.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.smart0.xyz/Article/details/gtrvyygulu.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.aizwys.cn/Article/details/gtqjldzere.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.gzhubu.top/Article/details/gtqsktnysq.html

[B13] 判断是否为数字
来源：http://dali.shuidangran.top/Article/details/gtawvhmgij.html

Py:   isinstance(x, (int, float))
来源：http://dali.redwolf501.top/Article/details/gtbmuvbmoy.html

PHP:  is_numeric($x)
来源：http://dali.cheryme.top/Article/details/gtsiuodijl.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ydzc1.top/Article/details/gtgmfbtkcm.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtijmusgnj.html

Java: x instanceof Number
来源：http://dali.quarkkingdee.top/Article/details/gthpwwpnky.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.birdmap.top/Article/details/gtkxzxsouv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.nanxinkj.top/Article/details/gtliphpkic.html

C#:   x is int or double or decimal
来源：http://dali.andypj.xyz/Article/details/gtdergbjqo.html

[B14] 判断值是否在集合内
来源：http://dali.zdqjudy.top/Article/details/gtdmfwvlxd.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.fengsongda.top/Article/details/gtreicwuis.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hnqzz.top/Article/details/gtebejgepq.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.mhx1999.top/Article/details/gtyhuftgeg.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.cqqwz.cn/Article/details/gthhhkumgn.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.haohaochexian.top/Article/details/gtehgjuzhh.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yanxiufei.cn/Article/details/gtpgmnxdkp.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.svipenyu.cn/Article/details/gtkuovpwpi.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.sysykeji.top/Article/details/gtoqmkxvzp.html

[B15] 布尔运算与取反
来源：http://dali.yj20258888.top/Article/details/gteoebjvlr.html

Py:   a and b or not c
来源：http://dali.tanke756.top/Article/details/gtwbxfopru.html

PHP:  $a && $b || !$c
来源：http://dali.ehwqpu.com/Article/details/gtdyzlevgn.html

JS:   a && b || !c
来源：http://dali.birdmap.top/Article/details/gtkkmfpgxr.html

TS:   a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttchmwalh.html

Java: a && b || !c
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmuobqmdk.html

Go:   a && b || !c
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqjnawqib.html

Ruby: a && b || !c
来源：http://dali.yvedp.cn/Article/details/gtwtwwxvdn.html

C#:   a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gtfgdsstzi.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.kuanghao11.cn/Article/details/gtdxovabhk.html

Py:   if not data: return
来源：http://dali.jlsjyb.cn/Article/details/gtpjldkhif.html

PHP:  if (!$data) { return; }
来源：http://dali.birdmap.top/Article/details/gtftvczjhr.html

JS:   if (!data) return;
来源：http://dali.pycfn.com/Article/details/gtuprgfffh.html

TS:   if (!data) return;
来源：http://dali.0kj1m.cn/Article/details/gtljcloqza.html

Java: if (data == null) return;
来源：http://dali.pengpengdd.cyou/Article/details/gtaubikirj.html

Go:   if data == nil { return }
来源：http://dali.hongshengwenyu.top/Article/details/gttxeqrpog.html

Ruby: return if data.nil?
来源：http://dali.jiagoushi.top/Article/details/gtbbincjwc.html

C#:   if (data == null) return;
来源：http://dali.haohaochexian.top/Article/details/gtnjrvzpxg.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtpuzdaqzi.html

C. 函数与作用域
来源：http://dali.pengpengdd.cyou/Article/details/gtewcofdxv.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrruawwdp.html

[C01] 定义函数
来源：http://dali.zhixingplan.top/Article/details/gtbhavhfkg.html

Py:   def add(a, b): return a + b
来源：http://dali.jiagoushi.top/Article/details/gtyukdlpga.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daria6918.cn/Article/details/gtwvlskxcf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gtshdlkrjy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gtszejahxc.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gtdrdrsnxi.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xuetiantiany.cn/Article/details/gtxdrlsycv.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cqqwz.cn/Article/details/gtnvhwbzsw.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gtbjqlvacu.html

[C02] 默认参数
来源：http://dali.ybcxt.top/Article/details/gtipsdjmyo.html

Py:   def greet(name="World"): return name
来源：http://dali.chenzaomai.com/Article/details/gttbnezvle.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ydzc1.top/Article/details/gtfljujwuz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yueranfly.top/Article/details/gtsvmoerkl.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.smart0.xyz/Article/details/gtclgfdnmm.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.guowangkeji.top/Article/details/gtvuprikts.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xinyue.icu/Article/details/gtrpzjwzxy.html

Ruby: def greet(name = "World") = name
来源：http://dali.gogol.net.cn/Article/details/gtnteeihxj.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.guannengcc.top/Article/details/gtfypvtobt.html

[C03] 可变参数
来源：http://dali.bjfxy.top/Article/details/gtcvchtofx.html

Py:   def total(*args): return sum(args)
来源：http://dali.nwbrower.top/Article/details/gtlbnsvntw.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhoulong.xyz/Article/details/gtdsjzbczv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ivvv.top/Article/details/gtufbsrqtl.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.daria6918.cn/Article/details/gtwozjuswb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.birdmap.top/Article/details/gtvkcuamfq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.andypj.xyz/Article/details/gtcmytfgsl.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yj202588.top/Article/details/gtxzejzvun.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtecqnsimc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jqgfzy.top/Article/details/gtshhzilcc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yuanzhike.top/Article/details/gtkfyktgah.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.wangshuangyany.cn/Article/details/gtdijdnhoh.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xuanzx.com/Article/details/gtaqkrepns.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.nanxinkj.top/Article/details/gtposyjmll.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.tianlin.xyz/Article/details/gtvpaviqos.html

Go:   // 无：用配置结构体参数
来源：http://dali.guannengcc.top/Article/details/gtubvuobog.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtdjmurfub.html

C#:   f(a: 1, b: 2)
来源：http://dali.dianchejie.cn/Article/details/gtogxundav.html

[C05] 返回多个值
来源：http://dali.xuanzx.com/Article/details/gtmrkqlrbs.html

Py:   return a, b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwdzhncsy.html

PHP:  return [$a, $b];
来源：http://dali.nanxuanxn.top/Article/details/gtecoooucz.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jinqigfzy.top/Article/details/gtpxptwxyx.html

TS:   return { a, b };
来源：http://dali.svipenyu.cn/Article/details/gttlzemenu.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.nanxuanxn.top/Article/details/gtrmpponck.html

Go:   return a, b
来源：http://dali.sufxvd.cn/Article/details/gtrgtrleae.html

Ruby: return a, b
来源：http://dali.hysaishi.cn/Article/details/gtsmlclfhs.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinqigufen.top/Article/details/gtrmnoimqi.html

[C06] 匿名函数 / lambda
来源：http://dali.wangdashe.top/Article/details/gtkqcnunir.html

Py:   square = lambda x: x * x
来源：http://dali.yueranfly.top/Article/details/gtqhqvdttf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.pengpengdd.cyou/Article/details/gtbnekfqil.html

JS:   const square = x => x * x;
来源：http://dali.yanxiufei.cn/Article/details/gtpworeyrl.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ivvv.top/Article/details/gtsubrtfub.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.cdnleiting.top/Article/details/gtajizghic.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.nanxinkj.top/Article/details/gtzerwcvqp.html

Ruby: square = ->(x) { x * x }
来源：http://dali.316326.xyz/Article/details/gthopqxxtv.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.0kj1m.cn/Article/details/gtgcfgzbqi.html

[C07] 把函数作为参数传入
来源：http://dali.gaohongyu789.top/Article/details/gtwdpmxfwj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yuxming.cn/Article/details/gthtqnkzco.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.tanke756.top/Article/details/gtftplvwgg.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.snrcjt.cn/Article/details/gtpmrjqzwm.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gtmmkmwoui.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jianghu66.top/Article/details/gtvejxglhm.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hnqzz.top/Article/details/gtihiegyte.html

Ruby: arr.map(&:upcase)
来源：http://dali.hnqzz.top/Article/details/gtsgebyzyg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.aibaodan.cn/Article/details/gtlpzuuxrq.html

[C08] 闭包
来源：http://dali.pengpengdd.cyou/Article/details/gtmhnbbicg.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.sysykeji.top/Article/details/gtuiylzrqx.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.dianchejie.cn/Article/details/gtednhxxsf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.quarkkingdee.top/Article/details/gttbgjljte.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xinyue.icu/Article/details/gtlnvldgqx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.snrcjt.cn/Article/details/gtckijzjnr.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.iojbl.cn/Article/details/gtlyqggjwe.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cucudq.cn/Article/details/gtczldlspv.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.chenjidiqi.icu/Article/details/gtmtwgrigw.html

[C09] 递归
来源：http://dali.dashuyun.cn/Article/details/gtrxiyzlru.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.kuanghao11.cn/Article/details/gtermbvaor.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gaohongyu789.top/Article/details/gtsbjavuox.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.smart0.xyz/Article/details/gtituafzxh.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sysykeji.top/Article/details/gtfpuvyntb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfyevqozc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hfpthk.cn/Article/details/gtcwlzifgc.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtonhslmzg.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jinqigufen.top/Article/details/gtgryjvhei.html

[C10] 变量作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqawuvepg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cqqwz.cn/Article/details/gtkowdxzww.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ybcxt.top/Article/details/gthirkidbl.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.aizwys.cn/Article/details/gtlxrhhdou.html

TS:   同 JS
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvodhxhvm.html

Java: 方法内为块级作用域
来源：http://dali.ybcxt.top/Article/details/gtsowzritc.html

Go:   花括号块级作用域
来源：http://dali.redwolf501.top/Article/details/gtjswjlywf.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jiagoushi.top/Article/details/gtpwfxurxo.html

C#:   块级作用域
来源：http://dali.redwolf501.top/Article/details/gtzftvaveu.html

[C11] 模块导入与导出
来源：http://dali.tanke756.top/Article/details/gtmrmkrmax.html

Py:   from module import func
来源：http://dali.sysykeji.top/Article/details/gtpqtdyjle.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ehwqpu.com/Article/details/gtjgampkak.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.meibo888.top/Article/details/gtbrxxadan.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtodomsdce.html

Java: import java.util.List;
来源：http://dali.nanxuanxn.top/Article/details/gtawwhojve.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sweek.top/Article/details/gtexrmqtbr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shzxlz.cn/Article/details/gtccoycqzr.html

C#:   using System.Text;
来源：http://dali.bjfxy.top/Article/details/gtakqpoexs.html

[C12] 立即执行函数 IIFE
来源：http://dali.yueranfly.top/Article/details/gtiawlawql.html

Py:   (lambda: print("run"))()
来源：http://dali.yangfankeji.com/Article/details/gtcoeaojtw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhoulong.xyz/Article/details/gtdepimwem.html

JS:   (() => { console.log("run"); })();
来源：http://dali.meibo888.top/Article/details/gtphuiajzo.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yangfankeji.com/Article/details/gtebxtweus.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrkruaumn.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shanyushiyangtech.top/Article/details/gtwledfaht.html

Ruby: -> { puts "run" }.call
来源：http://dali.shangyingyoupin.top/Article/details/gtdowhfcvt.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yuxming.cn/Article/details/gtbgriyrib.html

[C13] 类型声明 / 类型注解
来源：http://dali.chenzaomai.com/Article/details/gtliysejbk.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hfpthk.cn/Article/details/gttjgblkkm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gotoacloud.top/Article/details/gtmefyvijw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cdnleiting.top/Article/details/gtajcfrrio.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sweek.top/Article/details/gtcycnjclf.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtvxnzyxxw.html

Go:   func add(a, b int) int
来源：http://dali.0kj1m.cn/Article/details/gtsfveaykw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hysaishi.cn/Article/details/gtbtsaqiap.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.dianchejie.cn/Article/details/gtcvngmebv.html

[C14] 泛型函数
来源：http://dali.gogol.net.cn/Article/details/gttvojcdmp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.svipenyu.cn/Article/details/gtisjkqqjr.html

PHP:  // 无泛型
来源：http://dali.fengsongda.top/Article/details/gtskoxxjxk.html

JS:   // 无泛型
来源：http://dali.zhengqikj.top/Article/details/gtxsthdail.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.gaohongyu789.top/Article/details/gtpxvrdhfm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.daria6918.cn/Article/details/gtjppmjwtf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.dashuyun.cn/Article/details/gtxldhfope.html

Ruby: # 无泛型
来源：http://dali.daxiang520.top/Article/details/gttmpljwrp.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.andypj.xyz/Article/details/gtgpkspeqw.html

[C15] 解构 / 展开参数
来源：http://dali.sweek.top/Article/details/gttcyublsd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.haohaochexian.top/Article/details/gtdfjkolgs.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmrbsdmcq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.pycfn.com/Article/details/gtmvsbywev.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.birdmap.top/Article/details/gtknhundxz.html

Java: // 无解构
来源：http://dali.316326.xyz/Article/details/gtgsxbsace.html

Go:   // 无解构
来源：http://dali.cashguo.top/Article/details/gtagcuzinb.html

Ruby: a, b = pair
来源：http://dali.jinqigfzy.top/Article/details/gtxpwwdtxe.html

C#:   var (a, b) = pair;
来源：http://dali.tianlin.xyz/Article/details/gtdmoopssr.html

[C16] 函数 / 方法重载
来源：http://dali.cucudq.cn/Article/details/gtcwpddkkw.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.feifeiyinyue.top/Article/details/gtrixsprxf.html

PHP:  // 无重载
来源：http://dali.pengpengdd.cyou/Article/details/gtrneafbzi.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.meibo888.top/Article/details/gtmpkoepmr.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqgrxngty.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.316326.xyz/Article/details/gtlaaokgos.html

Go:   // 无重载：用不同函数名
来源：http://dali.yangfankeji.com/Article/details/gtyobeksqs.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gaohongyu789.top/Article/details/gtihiwfbva.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hnxiangtu.top/Article/details/gttsbatkjn.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtpvuzrsil.html

D. 数组 / 列表 / 集合
来源：http://dali.fengsongda.top/Article/details/gtrvcubpxu.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtiajxqmpf.html

[D01] 创建数组 / 列表
来源：http://dali.meibo888.top/Article/details/gtgfcfibhg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hnxiangtu.top/Article/details/gtxyuxghix.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ehwqpu.com/Article/details/gtiljiesvu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.chenzaomai.com/Article/details/gtwtexrygh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yj202588.top/Article/details/gtckqwknul.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cheryme.top/Article/details/gtttwvjjzv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yj202588.top/Article/details/gtmsgmubng.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cucudq.cn/Article/details/gtkmxpvbtf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.c1oappe.top/Article/details/gtdkzixjzy.html

[D02] 追加元素到末尾
来源：http://dali.yanxiufei.cn/Article/details/gtalcagawm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hnqzz.top/Article/details/gtejdqemxn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jinghuilouyu.cn/Article/details/gtumqhchvb.html

JS:   arr.push(4);
来源：http://dali.aizwys.cn/Article/details/gttavxspcb.html

TS:   arr.push(4);
来源：http://dali.daria6918.cn/Article/details/gtmvcwdeba.html

Java: list.add(4);
来源：http://dali.pycfn.com/Article/details/gtpejsgdni.html

Go:   arr = append(arr, 4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwtfrlqqs.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.pengpengdd.cyou/Article/details/gtelnkytqw.html

C#:   list.Add(4);
来源：http://dali.chenjidiqi.icu/Article/details/gtzkhgkdlu.html

[D03] 在指定位置插入元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtczfurhdk.html

Py:   arr.insert(0, 0)
来源：http://dali.zhixingplan.top/Article/details/gtpnfcpoxh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.chenjidiqi.icu/Article/details/gttlztaooz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jinqigfzy.top/Article/details/gtgatnqtxy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shzxlz.cn/Article/details/gtaqfrpbgs.html

Java: list.add(0, 0);
来源：http://dali.316326.xyz/Article/details/gtcrfcgghe.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shangyingyoupin.top/Article/details/gtiebiqzyl.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuutgqvpf.html

C#:   list.Insert(0, 0);
来源：http://dali.andypj.xyz/Article/details/gtayvdrzgc.html

[D04] 删除元素
来源：http://dali.yonumen.top/Article/details/gtohyueysa.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.tanke756.top/Article/details/gtizvikyni.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.smart0.xyz/Article/details/gtagtzzhvz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.vqdsnc.cn/Article/details/gtnawmfobo.html

TS:   arr.splice(0, 1);
来源：http://dali.shzxlz.cn/Article/details/gteopgsvlw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ydzc1.top/Article/details/gthirtlows.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shuidangran.top/Article/details/gtfljdrnwm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.tanke756.top/Article/details/gtswhpwtsb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.316326.xyz/Article/details/gtmqenxqfu.html

[D05] 访问与修改元素
来源：http://dali.sxryk.cn/Article/details/gtavmkrmvi.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj202588.top/Article/details/gtsgqkxiib.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hongshengwenyu.top/Article/details/gtsosmufll.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.birdmap.top/Article/details/gtdfvaqlvl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xuetiantiany.cn/Article/details/gtfkvzghou.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.chenzaomai.com/Article/details/gtptbzqrfk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinqigfzy.top/Article/details/gtzmxyufxs.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.snrcjt.cn/Article/details/gthzoomyne.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.quarkkingdee.top/Article/details/gtlsnrlxyr.html

[D06] 数组长度
来源：http://dali.aizwys.cn/Article/details/gtcwgtnldi.html

Py:   len(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtpunsefco.html

PHP:  count($arr);
来源：http://dali.wangdashe.top/Article/details/gtiyqyuadg.html

JS:   arr.length
来源：http://dali.mhx1999.top/Article/details/gtchqltnqa.html

TS:   arr.length
来源：http://dali.guowangkeji.top/Article/details/gtilkdgkpq.html

Java: list.size();
来源：http://dali.ybcxt.top/Article/details/gtosvozczc.html

Go:   len(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtzrjrwlpw.html

Ruby: arr.length; arr.size
来源：http://dali.yuxming.cn/Article/details/gtqqhjqwmg.html

C#:   list.Count;
来源：http://dali.sysykeji.top/Article/details/gtbgbyfnkj.html

[D07] 切片 / 取子数组
来源：http://dali.xinyue.icu/Article/details/gtvwyxjxfv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jyoumei.cn/Article/details/gtwkdllpxu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.9152youxi.cn/Article/details/gtinhihbeq.html

JS:   arr.slice(1, 4);
来源：http://dali.chenjidiqi.icu/Article/details/gtvsxmjlvw.html

TS:   arr.slice(1, 4);
来源：http://dali.birdmap.top/Article/details/gtsoditiox.html

Java: list.subList(1, 4);
来源：http://dali.sweek.top/Article/details/gtnuzbynsn.html

Go:   arr[1:4]
来源：http://dali.mhx1999.top/Article/details/gthfvugtnp.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gtinkqryby.html

C#:   list.GetRange(1, 3);
来源：http://dali.jlsjyb.cn/Article/details/gtyqvbkeil.html

[D08] 合并两个数组
来源：http://dali.jyoumei.cn/Article/details/gtzbkdmuix.html

Py:   a + b;  a.extend(b)
来源：http://dali.haohaochexian.top/Article/details/gtiusvhhgg.html

PHP:  array_merge($a, $b);
来源：http://dali.ybcxt.top/Article/details/gtkzztfspe.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.feifeiyinyue.top/Article/details/gtqvyxtefw.html

TS:   [...a, ...b];
来源：http://dali.shzxlz.cn/Article/details/gtfycagabq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.gotoacloud.top/Article/details/gtydeuvuhw.html

Go:   append(a, b...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxupzyybp.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jqgufenzy.top/Article/details/gtdsvsherp.html

C#:   a.Concat(b).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtaifpowxe.html

[D09] 排序（升序）
来源：http://dali.kuanghao11.cn/Article/details/gtqkymtrae.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xziqi.cn/Article/details/gtpfzytwoa.html

PHP:  sort($arr);
来源：http://dali.meibo888.top/Article/details/gtekrnqmtu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xinyue.icu/Article/details/gtzfyswfsa.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xuanzx.com/Article/details/gtxdgfoxks.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jqgfzy.top/Article/details/gtsrkymcef.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ydzc1.top/Article/details/gtugvkkmkk.html

Ruby: arr.sort
来源：http://dali.chenjidiqi.icu/Article/details/gtbzdgasid.html

C#:   list.Sort();
来源：http://dali.ehwqpu.com/Article/details/gtfcirufmj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.andypj.xyz/Article/details/gtcsapjhbk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jiagoushi.top/Article/details/gtgxzcmclt.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sufxvd.cn/Article/details/gttikxzzxt.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuanzx.com/Article/details/gtiwjlanmk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jiagoushi.top/Article/details/gtbzvhpapx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yj20258.top/Article/details/gttopjgppn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhongyouzk.top/Article/details/gtsgxmkfbl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinqigufen.top/Article/details/gthgejedxc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.tianlin.xyz/Article/details/gtvwofshjy.html


<!-- 参考信息 -->