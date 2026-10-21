代发 wailian999

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.quarkkingdee.top/Article/details/gtnkrwojgr.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jinqigfzy.top/Article/details/gtvutxnoua.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhoulong.xyz/Article/details/gtoiupxkua.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.cheryme.top/Article/details/gtvicpowjm.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.xziqi.cn/Article/details/gtetykfouh.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yanxiufei.cn/Article/details/gtewdbuayd.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhixingplan.top/Article/details/gtsbutahta.html

Py:   list(range(0, 10, 2))
来源：http://dali.hfpthk.cn/Article/details/gthaghachl.html

PHP:  range(0, 10, 2);
来源：http://dali.svipenyu.cn/Article/details/gtwnjxzuhz.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nwbrower.top/Article/details/gtsqktziwy.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xylfe.cn/Article/details/gtpmgubfmq.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtwxmcebwp.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.cheryme.top/Article/details/gthxlvnshm.html

Ruby: (0...10).step(2).to_a
来源：http://dali.dianchejie.cn/Article/details/gtvgtzrzox.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yangfankeji.com/Article/details/gtfergsjzv.html

[B12] 跳出多层循环
来源：http://dali.svipenyu.cn/Article/details/gtyrmtrcmm.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yonumen.top/Article/details/gtqdlzhmjk.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xylfe.cn/Article/details/gtcqjatvwl.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shzxlz.cn/Article/details/gteydmtlkm.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxinkj.top/Article/details/gtntzjaqfm.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.andypj.xyz/Article/details/gtznilphld.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zycfv.cn/Article/details/gtugmtvzqb.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xylfe.cn/Article/details/gtpnolabed.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xuanzx.com/Article/details/gtknpfpcqz.html

[B13] 判断是否为数字
来源：http://dali.ybcxt.top/Article/details/gthmnshmmm.html

Py:   isinstance(x, (int, float))
来源：http://dali.havefunace.top/Article/details/gtooqihayt.html

PHP:  is_numeric($x)
来源：http://dali.dashuyun.cn/Article/details/gtpxzewrhp.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.bjfxy.top/Article/details/gtfyblrezx.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhongyouzk.top/Article/details/gtrqvndkhi.html

Java: x instanceof Number
来源：http://dali.nwbrower.top/Article/details/gtekabyeku.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdcnruwxe.html

Ruby: x.is_a?(Numeric)
来源：http://dali.haohaochexian.top/Article/details/gtmnzkzusa.html

C#:   x is int or double or decimal
来源：http://dali.feifeiyinyue.top/Article/details/gtncdehjxb.html

[B14] 判断值是否在集合内
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjsspasil.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.haohaochexian.top/Article/details/gtowgxblyv.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.daria6918.cn/Article/details/gtspqsaigt.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.pycfn.com/Article/details/gtvrzpetxa.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jinqigufen.top/Article/details/gthgfzfrem.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.fzhhl.top/Article/details/gtecooypfd.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.birdmap.top/Article/details/gtxrficpdb.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtohmarywm.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ivvv.top/Article/details/gtyyqcnoza.html

[B15] 布尔运算与取反
来源：http://dali.shzxlz.cn/Article/details/gtcwgtjjtx.html

Py:   a and b or not c
来源：http://dali.chenjidiqi.icu/Article/details/gtykiptwks.html

PHP:  $a && $b || !$c
来源：http://dali.c1oappe.top/Article/details/gtfymwrtqc.html

JS:   a && b || !c
来源：http://dali.smart0.xyz/Article/details/gtbgqdyhud.html

TS:   a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gtvpwsdssz.html

Java: a && b || !c
来源：http://dali.yuxming.cn/Article/details/gtzvkavfbc.html

Go:   a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gtxyzgpuoi.html

Ruby: a && b || !c
来源：http://dali.tanke756.top/Article/details/gtkcaofbmx.html

C#:   a && b || !c
来源：http://dali.bjfxy.top/Article/details/gtgkuwntcd.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.pycfn.com/Article/details/gtkobszpkv.html

Py:   if not data: return
来源：http://dali.nanxinkj.top/Article/details/gtumbvfpkj.html

PHP:  if (!$data) { return; }
来源：http://dali.hysaishi.cn/Article/details/gtfzzlgrku.html

JS:   if (!data) return;
来源：http://dali.wangshuangyany.cn/Article/details/gtclpgcnyq.html

TS:   if (!data) return;
来源：http://dali.vqdsnc.cn/Article/details/gtjbboylvk.html

Java: if (data == null) return;
来源：http://dali.ydzc1.top/Article/details/gthqdkzrox.html

Go:   if data == nil { return }
来源：http://dali.daxiang520.top/Article/details/gtkqkurphx.html

Ruby: return if data.nil?
来源：http://dali.chenlongwang.top/Article/details/gtlwtkklxb.html

C#:   if (data == null) return;
来源：http://dali.sweek.top/Article/details/gtqgorspdt.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtdlwgejxj.html

C. 函数与作用域
来源：http://dali.yj20258888.top/Article/details/gtuubawijm.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtumfatzzy.html

[C01] 定义函数
来源：http://dali.zycfv.cn/Article/details/gtqllyvfvt.html

Py:   def add(a, b): return a + b
来源：http://dali.hywenlv.cn/Article/details/gtvfhgqvgx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ppjwa.cn/Article/details/gtfiivqaps.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hammf.cn/Article/details/gtmqeepafj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gtynxjnvlu.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gtimarchpd.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtizagyqgg.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zdqjudy.top/Article/details/gtxbnwrzxz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gtljnjbeqp.html

[C02] 默认参数
来源：http://dali.jianghu66.top/Article/details/gtjnwmdkyp.html

Py:   def greet(name="World"): return name
来源：http://dali.jinqigufen.top/Article/details/gtpqygtbdc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cqqwz.cn/Article/details/gturwvnzmq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ydzc1.top/Article/details/gtuxeaupxl.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhengqikj.top/Article/details/gtiguukhds.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.fzhhl.top/Article/details/gtwennouyd.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.chenjidiqi.icu/Article/details/gtvzwfvhgx.html

Ruby: def greet(name = "World") = name
来源：http://dali.c1oappe.top/Article/details/gtbzuttdsi.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.wangdashe.top/Article/details/gtwgsqdvcm.html

[C03] 可变参数
来源：http://dali.gzhubu.top/Article/details/gtsmstunip.html

Py:   def total(*args): return sum(args)
来源：http://dali.birdmap.top/Article/details/gtbsequweb.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yueranfly.top/Article/details/gtaolvkmsa.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258888.top/Article/details/gterjmazry.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xinyue.icu/Article/details/gtstrusrqh.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yj202588.top/Article/details/gtpzxnklyd.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yongpay.top/Article/details/gtidwxhvmj.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.wangshuangyany.cn/Article/details/gtibtlhtin.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.sufxvd.cn/Article/details/gtbjdojocm.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yonumen.top/Article/details/gtndlfqtmu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.guowangkeji.top/Article/details/gtehimnodo.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yongpay.top/Article/details/gtptfdxzgj.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.nanxuanxn.top/Article/details/gtwargxzld.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.chenlongwang.top/Article/details/gttcoxcnkv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cashguo.top/Article/details/gtgqyaxldb.html

Go:   // 无：用配置结构体参数
来源：http://dali.yongpay.top/Article/details/gtpefwlukl.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shangyingyoupin.top/Article/details/gttcdrasgz.html

C#:   f(a: 1, b: 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcdlkjqit.html

[C05] 返回多个值
来源：http://dali.316326.xyz/Article/details/gtnzgkcrrp.html

Py:   return a, b
来源：http://dali.xziqi.cn/Article/details/gtswbschgz.html

PHP:  return [$a, $b];
来源：http://dali.tian-w.cn/Article/details/gtpzfhfqcv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.fzhhl.top/Article/details/gtojykpuaf.html

TS:   return { a, b };
来源：http://dali.mhx1999.top/Article/details/gtflikxiks.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.nanxinkj.top/Article/details/gtsnzurqwp.html

Go:   return a, b
来源：http://dali.nanxinkj.top/Article/details/gtnmurxsnh.html

Ruby: return a, b
来源：http://dali.yueranfly.top/Article/details/gtqhhmsygy.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.c1oappe.top/Article/details/gtumqnopck.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gtktyuxwbi.html

Py:   square = lambda x: x * x
来源：http://dali.hfpthk.cn/Article/details/gtegowdlgp.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.aizwys.cn/Article/details/gtkamxkhqc.html

JS:   const square = x => x * x;
来源：http://dali.cqqwz.cn/Article/details/gttebtwifq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jianghu66.top/Article/details/gtsyqyqhno.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.nanxinkj.top/Article/details/gtyjmyhuca.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ivvv.top/Article/details/gtzfwyscmo.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ybcxt.top/Article/details/gtbgyivegi.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ivvv.top/Article/details/gtqwlntxva.html

[C07] 把函数作为参数传入
来源：http://dali.nanxuanxn.top/Article/details/gttxjuhbue.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shangyingyoupin.top/Article/details/gtjdxjacoh.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.tian-w.cn/Article/details/gtjahhiduv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hammf.cn/Article/details/gtqeqvnwcr.html

TS:   arr.map(String)
来源：http://dali.pengpengdd.cyou/Article/details/gtymtrtloh.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.tianlin.xyz/Article/details/gtmtaqunsd.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.tian-w.cn/Article/details/gtlvyhihrs.html

Ruby: arr.map(&:upcase)
来源：http://dali.yuxming.cn/Article/details/gtojpwelxd.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.wangdashe.top/Article/details/gtougeypms.html

[C08] 闭包
来源：http://dali.wangdashe.top/Article/details/gtotkspdse.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cucudq.cn/Article/details/gtdlkrcxda.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yueranfly.top/Article/details/gtmnezsviv.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ivvv.top/Article/details/gtchbsvbry.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.fzhhl.top/Article/details/gtjtqrnvyz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.nanxuanxn.top/Article/details/gtbawdvlhb.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.svipenyu.cn/Article/details/gtvuwieays.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yanxiufei.cn/Article/details/gtbwuppfqk.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yueranfly.top/Article/details/gtptlenzch.html

[C09] 递归
来源：http://dali.0kj1m.cn/Article/details/gtwqmtgnkg.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yj202588.top/Article/details/gtsonwwvqg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yuanzhike.top/Article/details/gtxwhorbpj.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hnxiangtu.top/Article/details/gtfetpssyw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtectrbyrw.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.sweek.top/Article/details/gthnacmgxl.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.nwbrower.top/Article/details/gtwfbrseka.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.9152youxi.cn/Article/details/gtudrttlnz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.iojbl.cn/Article/details/gtpxjvsdrn.html

[C10] 变量作用域
来源：http://dali.andypj.xyz/Article/details/gtspnjgtqv.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cdnleiting.top/Article/details/gtokubdkpl.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.svipenyu.cn/Article/details/gtuwfhgraw.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xylfe.cn/Article/details/gtbkvmdras.html

TS:   同 JS
来源：http://dali.xuanzx.com/Article/details/gtmcbsqmbc.html

Java: 方法内为块级作用域
来源：http://dali.ybcxt.top/Article/details/gtxtrwklln.html

Go:   花括号块级作用域
来源：http://dali.yanxiufei.cn/Article/details/gtbmbmorbc.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cdnleiting.top/Article/details/gtgmlqrcev.html

C#:   块级作用域
来源：http://dali.hywenlv.cn/Article/details/gtovurnqqt.html

[C11] 模块导入与导出
来源：http://dali.yvedp.cn/Article/details/gtogagfxvh.html

Py:   from module import func
来源：http://dali.ehwqpu.com/Article/details/gtlqbmukkl.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinghuilouyu.cn/Article/details/gtoofpmzmc.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cqqwz.cn/Article/details/gtozmlebjh.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jinqigfzy.top/Article/details/gttlelisrh.html

Java: import java.util.List;
来源：http://dali.gotoacloud.top/Article/details/gtfcgyzmja.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.bjfxy.top/Article/details/gtwcxfusmg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.daria6918.cn/Article/details/gtdpedchru.html

C#:   using System.Text;
来源：http://dali.cashguo.top/Article/details/gtxzjdmujd.html

[C12] 立即执行函数 IIFE
来源：http://dali.chenlongwang.top/Article/details/gtwfqrnumv.html

Py:   (lambda: print("run"))()
来源：http://dali.sysykeji.top/Article/details/gtxqvlxbvr.html

PHP:  (function () { echo "run"; })();
来源：http://dali.wangdashe.top/Article/details/gtcblaeced.html

JS:   (() => { console.log("run"); })();
来源：http://dali.gogol.net.cn/Article/details/gthkusnkfc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.mhx1999.top/Article/details/gtshilqiuq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.tian-w.cn/Article/details/gtayblealz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gzhubu.top/Article/details/gtfoysjfhk.html

Ruby: -> { puts "run" }.call
来源：http://dali.gogol.net.cn/Article/details/gtrxftmphv.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.chenzaomai.com/Article/details/gtlqshtpbo.html

[C13] 类型声明 / 类型注解
来源：http://dali.andypj.xyz/Article/details/gtwdbfyeqc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.gogol.net.cn/Article/details/gtgbouowmf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gtbktziipv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shanyushiyangtech.top/Article/details/gthezvvzfx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtralnmfxe.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfkpjljcg.html

Go:   func add(a, b int) int
来源：http://dali.tianlin.xyz/Article/details/gtsfcljqnc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmugsrcyg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gogol.net.cn/Article/details/gtxncqjmqp.html

[C14] 泛型函数
来源：http://dali.cucudq.cn/Article/details/gtemqdnlhn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hywenlv.cn/Article/details/gtqbkxiebw.html

PHP:  // 无泛型
来源：http://dali.zycfv.cn/Article/details/gtjseurrqh.html

JS:   // 无泛型
来源：http://dali.aibaodan.cn/Article/details/gtgoolyrhv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sufxvd.cn/Article/details/gtwrqacfzf.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gtadnliete.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.aizwys.cn/Article/details/gtykwbpmlx.html

Ruby: # 无泛型
来源：http://dali.0kj1m.cn/Article/details/gttvwhlacl.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.dashuyun.cn/Article/details/gthqeujkzp.html

[C15] 解构 / 展开参数
来源：http://dali.ydzc1.top/Article/details/gtefczrqjx.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zdqjudy.top/Article/details/gtjpjcekqw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.nanxinkj.top/Article/details/gttdniecpt.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.316326.xyz/Article/details/gtpjczjrvb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhengqikj.top/Article/details/gtfynmgeup.html

Java: // 无解构
来源：http://dali.guowangkeji.top/Article/details/gtdpuqxffe.html

Go:   // 无解构
来源：http://dali.daxiang520.top/Article/details/gtocjkcobk.html

Ruby: a, b = pair
来源：http://dali.yvedp.cn/Article/details/gteizgkiyq.html

C#:   var (a, b) = pair;
来源：http://dali.yj202588.top/Article/details/gthblctpkc.html

[C16] 函数 / 方法重载
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrzjmrgdh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvrjyacxd.html

PHP:  // 无重载
来源：http://dali.svipenyu.cn/Article/details/gttzgopqsr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.aibaodan.cn/Article/details/gtmlacioyh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xziqi.cn/Article/details/gtxvrxycvc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.quarkkingdee.top/Article/details/gtgsnbdcuc.html

Go:   // 无重载：用不同函数名
来源：http://dali.0kj1m.cn/Article/details/gtqpmvvpue.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhixingplan.top/Article/details/gtwkewhcbd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hfpthk.cn/Article/details/gtidhuaedo.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtzicgrald.html

D. 数组 / 列表 / 集合
来源：http://dali.aizwys.cn/Article/details/gthoywjsoh.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtxrzxdwbd.html

[D01] 创建数组 / 列表
来源：http://dali.fzhhl.top/Article/details/gtmzzwltfc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.chenjidiqi.icu/Article/details/gtfzcdhklz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ydzc1.top/Article/details/gthsogxplo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.snrcjt.cn/Article/details/gtkcbsokya.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yj20258888.top/Article/details/gtjwlriifu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xziqi.cn/Article/details/gtckcxkzwg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhengqikj.top/Article/details/gthedxgcxj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hnxiangtu.top/Article/details/gtmmaynngr.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.pycfn.com/Article/details/gtlesfcdfe.html

[D02] 追加元素到末尾
来源：http://dali.shanyushiyangtech.top/Article/details/gtdhdxubhe.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ybcxt.top/Article/details/gtyphjjvok.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.tian-w.cn/Article/details/gtudbmqqlc.html

JS:   arr.push(4);
来源：http://dali.yuxming.cn/Article/details/gtxvxnxnga.html

TS:   arr.push(4);
来源：http://dali.xylfe.cn/Article/details/gtjagcgumr.html

Java: list.add(4);
来源：http://dali.meibo888.top/Article/details/gtcheesnyn.html

Go:   arr = append(arr, 4)
来源：http://dali.guowangkeji.top/Article/details/gteejtxiut.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gaohongyu789.top/Article/details/gtpckdnujd.html

C#:   list.Add(4);
来源：http://dali.havefunace.top/Article/details/gtiijurdtj.html

[D03] 在指定位置插入元素
来源：http://dali.jyoumei.cn/Article/details/gtrduyxuyi.html

Py:   arr.insert(0, 0)
来源：http://dali.wangdashe.top/Article/details/gtlrdciebv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shangyingyoupin.top/Article/details/gtfytjncyi.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.fengsongda.top/Article/details/gtmctcpqyx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.chenzaomai.com/Article/details/gttudwcoaf.html

Java: list.add(0, 0);
来源：http://dali.dianchejie.cn/Article/details/gtmxtzffbz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hfpthk.cn/Article/details/gtvyngdyyy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.mhx1999.top/Article/details/gtckcqpmnn.html

C#:   list.Insert(0, 0);
来源：http://dali.daria6918.cn/Article/details/gtwixxklmq.html

[D04] 删除元素
来源：http://dali.jqgufenzy.top/Article/details/gtsunpdohz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.birdmap.top/Article/details/gtdjudyfgm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtkaxekwbh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinqigfzy.top/Article/details/gtrexgjuht.html

TS:   arr.splice(0, 1);
来源：http://dali.xziqi.cn/Article/details/gtvzjrxoiy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.iojbl.cn/Article/details/gtdnrznjqs.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jlsjyb.cn/Article/details/gtgmgkrvrn.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ydzc1.top/Article/details/gtysddyttm.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.daria6918.cn/Article/details/gtwdhvdnpw.html

[D05] 访问与修改元素
来源：http://dali.hywenlv.cn/Article/details/gtdejbxaab.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pengpengdd.cyou/Article/details/gtfgtxnhor.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.vqdsnc.cn/Article/details/gtiszuzztn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.vqdsnc.cn/Article/details/gtopubgcvq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.wangshuangyany.cn/Article/details/gteaqjmfwg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.pycfn.com/Article/details/gtpnbuahhq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhixingplan.top/Article/details/gtmxmphsdd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.c1oappe.top/Article/details/gtvsvkeutv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jqgufenzy.top/Article/details/gtvbbxgkeo.html

[D06] 数组长度
来源：http://dali.kuanghao11.cn/Article/details/gtthfhhuel.html

Py:   len(arr)
来源：http://dali.aizwys.cn/Article/details/gturcqqisr.html

PHP:  count($arr);
来源：http://dali.iojbl.cn/Article/details/gtgyjntpqt.html

JS:   arr.length
来源：http://dali.tian-w.cn/Article/details/gtilyvqhuy.html

TS:   arr.length
来源：http://dali.tian-w.cn/Article/details/gtovrwzbhc.html

Java: list.size();
来源：http://dali.yangfankeji.com/Article/details/gtdvybglgo.html

Go:   len(arr)
来源：http://dali.vqdsnc.cn/Article/details/gthsjllrtu.html

Ruby: arr.length; arr.size
来源：http://dali.jinqigufen.top/Article/details/gtfyvcxwtl.html

C#:   list.Count;
来源：http://dali.aibaodan.cn/Article/details/gtrusfbnke.html

[D07] 切片 / 取子数组
来源：http://dali.tian-w.cn/Article/details/gtesaznqhv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jyoumei.cn/Article/details/gtcsmvlblo.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ybcxt.top/Article/details/gtsjcedmfd.html

JS:   arr.slice(1, 4);
来源：http://dali.yuxming.cn/Article/details/gtebwmxrta.html

TS:   arr.slice(1, 4);
来源：http://dali.yj20258888.top/Article/details/gtwuxgtvmb.html

Java: list.subList(1, 4);
来源：http://dali.chenlongwang.top/Article/details/gtfrbimgyq.html

Go:   arr[1:4]
来源：http://dali.cucudq.cn/Article/details/gtpeaxtgzz.html

Ruby: arr[1, 3]
来源：http://dali.birdmap.top/Article/details/gtwrtyazgz.html

C#:   list.GetRange(1, 3);
来源：http://dali.0kj1m.cn/Article/details/gtjtzrpbpt.html

[D08] 合并两个数组
来源：http://dali.gaohongyu789.top/Article/details/gthzgpijzd.html

Py:   a + b;  a.extend(b)
来源：http://dali.jyoumei.cn/Article/details/gtaeotzbvy.html

PHP:  array_merge($a, $b);
来源：http://dali.ydzc1.top/Article/details/gtcscfuibn.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jyoumei.cn/Article/details/gtrimqrzus.html

TS:   [...a, ...b];
来源：http://dali.gzhubu.top/Article/details/gtfckfdihy.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shzxlz.cn/Article/details/gtpfpyepjz.html

Go:   append(a, b...)
来源：http://dali.mhx1999.top/Article/details/gtftgjuiqz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfpdnllyv.html

C#:   a.Concat(b).ToList()
来源：http://dali.316326.xyz/Article/details/gtdpazsayk.html

[D09] 排序（升序）
来源：http://dali.havefunace.top/Article/details/gtmppjckuf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenlongwang.top/Article/details/gtinbjxblv.html

PHP:  sort($arr);
来源：http://dali.guowangkeji.top/Article/details/gtthskxuuw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhiwuduotai.top/Article/details/gthylhqkdv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cucudq.cn/Article/details/gtvmhkliar.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.9152youxi.cn/Article/details/gtuadhhkly.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.nwbrower.top/Article/details/gtlneradeu.html

Ruby: arr.sort
来源：http://dali.xylfe.cn/Article/details/gtmfikqeez.html

C#:   list.Sort();
来源：http://dali.jiagoushi.top/Article/details/gttvgukowf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.fengsongda.top/Article/details/gtpkwnoewj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.daria6918.cn/Article/details/gtyvavrgom.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zycfv.cn/Article/details/gtlzuahngy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shangyingyoupin.top/Article/details/gtsmnlpwik.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sysykeji.top/Article/details/gtjwnerzxd.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.daria6918.cn/Article/details/gtlsywxfkz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.guowangkeji.top/Article/details/gtuyxqsdni.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.guowangkeji.top/Article/details/gtnhelgcit.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hysaishi.cn/Article/details/gtpjwhzjqu.html


<!-- 参考信息 -->