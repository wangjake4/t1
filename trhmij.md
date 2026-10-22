代发 wailian999

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.haohaochexian.top/Article/details/gtxoxxengi.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jyoumei.cn/Article/details/gtjozttifk.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.gzhubu.top/Article/details/gtiivsqyki.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hywenlv.cn/Article/details/gtovtzmtip.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.xylfe.cn/Article/details/gtvxtdusoe.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.svipenyu.cn/Article/details/gteiiyviqa.html

[B11] 生成数字序列 / 区间
来源：http://dali.jiagoushi.top/Article/details/gtvmezpwsc.html

Py:   list(range(0, 10, 2))
来源：http://dali.yuanzhike.top/Article/details/gtpqkjbgna.html

PHP:  range(0, 10, 2);
来源：http://dali.jinqigufen.top/Article/details/gtsrtqtooc.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yonumen.top/Article/details/gtacyoclpw.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gotoacloud.top/Article/details/gtsvgwpqsf.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.tianlin.xyz/Article/details/gtunassebk.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hnxiangtu.top/Article/details/gtddugoocy.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ydzc1.top/Article/details/gtbeixzxpm.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.dianchejie.cn/Article/details/gtqtsialqv.html

[B12] 跳出多层循环
来源：http://dali.jqgufenzy.top/Article/details/gtjrtszaby.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xziqi.cn/Article/details/gtxinuxymg.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.fengsongda.top/Article/details/gtrrafwrpt.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.aizwys.cn/Article/details/gtlzrsujrj.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.svipenyu.cn/Article/details/gtbvsymqeu.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zdqjudy.top/Article/details/gtyvoducsl.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvicicbcx.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hfpthk.cn/Article/details/gtgzeqezuo.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hysaishi.cn/Article/details/gtcpfexdjq.html

[B13] 判断是否为数字
来源：http://dali.zhengqikj.top/Article/details/gthvbswniv.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhixingplan.top/Article/details/gtaqnsswct.html

PHP:  is_numeric($x)
来源：http://dali.feifeiyinyue.top/Article/details/gthhoinngx.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtwiawxaaf.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenzaomai.com/Article/details/gtfaudowfz.html

Java: x instanceof Number
来源：http://dali.zhaomingkeji.xyz/Article/details/gtymuophyg.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhengqikj.top/Article/details/gtmtdokrfv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ivvv.top/Article/details/gtttkuiwhz.html

C#:   x is int or double or decimal
来源：http://dali.zhengqikj.top/Article/details/gtfabrjdqa.html

[B14] 判断值是否在集合内
来源：http://dali.xuanzx.com/Article/details/gtsbedifvt.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhengqikj.top/Article/details/gtsyppzvwa.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hammf.cn/Article/details/gthvktihys.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yonumen.top/Article/details/gtbebfvxne.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ydzc1.top/Article/details/gtaguziewf.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.cheryme.top/Article/details/gtzgomahnp.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.andypj.xyz/Article/details/gttthwzzgs.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtptukcpup.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.nwbrower.top/Article/details/gtixgqyker.html

[B15] 布尔运算与取反
来源：http://dali.chenjidiqi.icu/Article/details/gtvzoliqqe.html

Py:   a and b or not c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqctpflzo.html

PHP:  $a && $b || !$c
来源：http://dali.zhongyouzk.top/Article/details/gtcxbvoqyt.html

JS:   a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gtmwirhbwe.html

TS:   a && b || !c
来源：http://dali.9152youxi.cn/Article/details/gtyqyijslz.html

Java: a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gtcvugmuer.html

Go:   a && b || !c
来源：http://dali.tanke756.top/Article/details/gtvforqwtn.html

Ruby: a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzlmqimcj.html

C#:   a && b || !c
来源：http://dali.yuxming.cn/Article/details/gtkwblgave.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cheryme.top/Article/details/gtrrsezyzj.html

Py:   if not data: return
来源：http://dali.yangfankeji.com/Article/details/gtruhczzuz.html

PHP:  if (!$data) { return; }
来源：http://dali.ydzc1.top/Article/details/gtjspkatpo.html

JS:   if (!data) return;
来源：http://dali.mhx1999.top/Article/details/gtmfndyltd.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gtgtqoynpr.html

Java: if (data == null) return;
来源：http://dali.cashguo.top/Article/details/gtjunxltkn.html

Go:   if data == nil { return }
来源：http://dali.zhengqikj.top/Article/details/gtjcgzfyzb.html

Ruby: return if data.nil?
来源：http://dali.meibo888.top/Article/details/gtuigwexmb.html

C#:   if (data == null) return;
来源：http://dali.mhx1999.top/Article/details/gthsbunmpu.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gttjvudlcr.html

C. 函数与作用域
来源：http://dali.ehwqpu.com/Article/details/gtlcsjvgnv.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gthajonaak.html

[C01] 定义函数
来源：http://dali.haohaochexian.top/Article/details/gtsiqbnbnr.html

Py:   def add(a, b): return a + b
来源：http://dali.ehwqpu.com/Article/details/gtucakixdl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sweek.top/Article/details/gtuwkbehva.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjqupmwov.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gttxbyyjcs.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpohexndm.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.cashguo.top/Article/details/gtsssavkjp.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jyoumei.cn/Article/details/gtkqxxrdus.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gtmkdkidgy.html

[C02] 默认参数
来源：http://dali.svipenyu.cn/Article/details/gtrngelrvy.html

Py:   def greet(name="World"): return name
来源：http://dali.jqgfzy.top/Article/details/gtieueqgvm.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yuxming.cn/Article/details/gtuinnisan.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jyoumei.cn/Article/details/gtuyfyusqq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xinyue.icu/Article/details/gtacvhfjqn.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yueranfly.top/Article/details/gtkgnyfequ.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.nanxuanxn.top/Article/details/gtkzgwunmj.html

Ruby: def greet(name = "World") = name
来源：http://dali.pycfn.com/Article/details/gtzeqssfrj.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.birdmap.top/Article/details/gtdurypbeq.html

[C03] 可变参数
来源：http://dali.cashguo.top/Article/details/gtwsbvspda.html

Py:   def total(*args): return sum(args)
来源：http://dali.yueranfly.top/Article/details/gtmplnafub.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.316326.xyz/Article/details/gtbvurqnne.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.snrcjt.cn/Article/details/gtppzvkqpj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hammf.cn/Article/details/gtnjyensqd.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.daxiang520.top/Article/details/gtpxhlztoi.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzpchhxxb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yonumen.top/Article/details/gthfwiejkd.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.bjfxy.top/Article/details/gtnkwucbna.html

[C04] 命名参数 / 关键字参数
来源：http://dali.nwbrower.top/Article/details/gtxdcfjuei.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cdnleiting.top/Article/details/gtbjrodemb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.vqdsnc.cn/Article/details/gtogjqirxl.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.gaohongyu789.top/Article/details/gtlgdtgucs.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.snrcjt.cn/Article/details/gtrbdlyncn.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.316326.xyz/Article/details/gtivykphci.html

Go:   // 无：用配置结构体参数
来源：http://dali.ppjwa.cn/Article/details/gtqxwcnxqi.html

Ruby: f(a: 1, b: 2)
来源：http://dali.c1oappe.top/Article/details/gtpjfvxkac.html

C#:   f(a: 1, b: 2)
来源：http://dali.redwolf501.top/Article/details/gtsptfksjd.html

[C05] 返回多个值
来源：http://dali.hysaishi.cn/Article/details/gtkrsnhxol.html

Py:   return a, b
来源：http://dali.ybcxt.top/Article/details/gtwidaljog.html

PHP:  return [$a, $b];
来源：http://dali.ybcxt.top/Article/details/gtitvlqcnn.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sxryk.cn/Article/details/gtzvgxbtwg.html

TS:   return { a, b };
来源：http://dali.kuanghao11.cn/Article/details/gtmbkqquum.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhongyouzk.top/Article/details/gtkalvaino.html

Go:   return a, b
来源：http://dali.yanxiufei.cn/Article/details/gtwynontcp.html

Ruby: return a, b
来源：http://dali.xuanzx.com/Article/details/gtspyfdsqy.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.gzhubu.top/Article/details/gtblydxapb.html

[C06] 匿名函数 / lambda
来源：http://dali.ivvv.top/Article/details/gtlsvhgfio.html

Py:   square = lambda x: x * x
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsxuezmtr.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jinghuilouyu.cn/Article/details/gtoxuubgjl.html

JS:   const square = x => x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gtlekoagzc.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gtpusjnypd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.vqdsnc.cn/Article/details/gtquglgfoc.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yangfankeji.com/Article/details/gtlrhblvpq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hammf.cn/Article/details/gtwvmelmos.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtikzopixc.html

[C07] 把函数作为参数传入
来源：http://dali.iojbl.cn/Article/details/gtbmlcopnf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xuanzx.com/Article/details/gtxgqfkvps.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jiagoushi.top/Article/details/gtogxpvatu.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xziqi.cn/Article/details/gtoncusjgz.html

TS:   arr.map(String)
来源：http://dali.hywenlv.cn/Article/details/gtvyimyfjs.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ehwqpu.com/Article/details/gtuyrumilo.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cheryme.top/Article/details/gttxjqlxhl.html

Ruby: arr.map(&:upcase)
来源：http://dali.316326.xyz/Article/details/gtmkhrsdyd.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhongyouzk.top/Article/details/gtcvkfhrrr.html

[C08] 闭包
来源：http://dali.sysykeji.top/Article/details/gtxhbituqi.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.quarkkingdee.top/Article/details/gtjuiqfqbl.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.quarkkingdee.top/Article/details/gtpbzqvkot.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.c1oappe.top/Article/details/gtesvqieba.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cashguo.top/Article/details/gtlmsfetzq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gzhubu.top/Article/details/gtxudxgrrt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.tianlin.xyz/Article/details/gtpdurgrrn.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hfpthk.cn/Article/details/gttflsjijb.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hnqzz.top/Article/details/gtjgrlwjvf.html

[C09] 递归
来源：http://dali.nanxinkj.top/Article/details/gtqmtgjeoc.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.0kj1m.cn/Article/details/gtwoaqlylm.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xinyue.icu/Article/details/gtsgaywjgu.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgufenzy.top/Article/details/gtvnzmekxv.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhoulong.xyz/Article/details/gtedezphyj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.sxryk.cn/Article/details/gtsbdsjfty.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvydobvfg.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xziqi.cn/Article/details/gtwzpngxqz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hammf.cn/Article/details/gtwienopjy.html

[C10] 变量作用域
来源：http://dali.jqgufenzy.top/Article/details/gternwctlp.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.sxryk.cn/Article/details/gtvgqiejmx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.quarkkingdee.top/Article/details/gtftgfeviv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.snrcjt.cn/Article/details/gtmxcoqayn.html

TS:   同 JS
来源：http://dali.zhixingplan.top/Article/details/gtwwuomckc.html

Java: 方法内为块级作用域
来源：http://dali.havefunace.top/Article/details/gtsupnbqaz.html

Go:   花括号块级作用域
来源：http://dali.pycfn.com/Article/details/gtclgmbluz.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hongshengwenyu.top/Article/details/gtzjqajvev.html

C#:   块级作用域
来源：http://dali.zycfv.cn/Article/details/gtgwbhgygg.html

[C11] 模块导入与导出
来源：http://dali.dashuyun.cn/Article/details/gtlfvqsbhi.html

Py:   from module import func
来源：http://dali.jianghu66.top/Article/details/gtvwymzoph.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hammf.cn/Article/details/gteqeehdhq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.svipenyu.cn/Article/details/gtfwgfkypc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hammf.cn/Article/details/gtccvsiroa.html

Java: import java.util.List;
来源：http://dali.ybcxt.top/Article/details/gtpwvvluyp.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhiwuduotai.top/Article/details/gttvjlhudg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yonumen.top/Article/details/gtaqzfclbf.html

C#:   using System.Text;
来源：http://dali.yueranfly.top/Article/details/gtrsppbaon.html

[C12] 立即执行函数 IIFE
来源：http://dali.jinqigufen.top/Article/details/gtuuqlyeav.html

Py:   (lambda: print("run"))()
来源：http://dali.aibaodan.cn/Article/details/gtyblshett.html

PHP:  (function () { echo "run"; })();
来源：http://dali.chenjidiqi.icu/Article/details/gtovlcvbhs.html

JS:   (() => { console.log("run"); })();
来源：http://dali.guannengcc.top/Article/details/gtlsavpwjj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.iojbl.cn/Article/details/gtcynanxrv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cqqwz.cn/Article/details/gthuzdqndm.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinqigufen.top/Article/details/gtmqylqmqk.html

Ruby: -> { puts "run" }.call
来源：http://dali.shanyushiyangtech.top/Article/details/gtmnolgbxm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.wangdashe.top/Article/details/gtwddegjus.html

[C13] 类型声明 / 类型注解
来源：http://dali.yvedp.cn/Article/details/gtfalvwmtf.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.quarkkingdee.top/Article/details/gtqjgwrhye.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtluqslfan.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yanxiufei.cn/Article/details/gtdfsjdeam.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gtrjevliqq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtwafgdzgh.html

Go:   func add(a, b int) int
来源：http://dali.jqgfzy.top/Article/details/gtgrwaajwz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhengqikj.top/Article/details/gtqvmwhcyg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.9152youxi.cn/Article/details/gtlhuvfmab.html

[C14] 泛型函数
来源：http://dali.andypj.xyz/Article/details/gtaxqasfny.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.guannengcc.top/Article/details/gthhwgmihv.html

PHP:  // 无泛型
来源：http://dali.zhoulong.xyz/Article/details/gtkzlwbjfd.html

JS:   // 无泛型
来源：http://dali.vqdsnc.cn/Article/details/gtpqfobgjy.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yonumen.top/Article/details/gtaifwlzmu.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gtjsixnofn.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.pycfn.com/Article/details/gtejobwsqa.html

Ruby: # 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjkmosskj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.sxryk.cn/Article/details/gtythbhtrj.html

[C15] 解构 / 展开参数
来源：http://dali.jianghu66.top/Article/details/gtjdhgtofm.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sysykeji.top/Article/details/gtpdepjblw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinqigufen.top/Article/details/gtvyxhewon.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.nwbrower.top/Article/details/gtowbqicmi.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtbnzpvjjd.html

Java: // 无解构
来源：http://dali.yanxiufei.cn/Article/details/gtffqmhupi.html

Go:   // 无解构
来源：http://dali.sweek.top/Article/details/gtsrqjixcm.html

Ruby: a, b = pair
来源：http://dali.aibaodan.cn/Article/details/gteuoygucu.html

C#:   var (a, b) = pair;
来源：http://dali.zhongyouzk.top/Article/details/gtdtmiavyz.html

[C16] 函数 / 方法重载
来源：http://dali.quarkkingdee.top/Article/details/gtbvsumfdi.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jianghu66.top/Article/details/gtmvscdaet.html

PHP:  // 无重载
来源：http://dali.cucudq.cn/Article/details/gtnmgaqbvo.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhixingplan.top/Article/details/gtxhgjrkzh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zycfv.cn/Article/details/gtsyldybkz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sysykeji.top/Article/details/gtqrxuhvmw.html

Go:   // 无重载：用不同函数名
来源：http://dali.yueranfly.top/Article/details/gtjaiajzle.html

Ruby: # 无重载：靠动态参数
来源：http://dali.daxiang520.top/Article/details/gtpyxxeymn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.chenlongwang.top/Article/details/gteojroowu.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtrlubdahe.html

D. 数组 / 列表 / 集合
来源：http://dali.jinqigufen.top/Article/details/gtqmhhempt.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtoqvsfdnc.html

[D01] 创建数组 / 列表
来源：http://dali.ivvv.top/Article/details/gttccujgly.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.vqdsnc.cn/Article/details/gtnnqmmovm.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.guowangkeji.top/Article/details/gtkhmmclms.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.aizwys.cn/Article/details/gtmflzuets.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ehwqpu.com/Article/details/gtxpmotagm.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.9152youxi.cn/Article/details/gtoaclethr.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.snrcjt.cn/Article/details/gtqhybgaan.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sysykeji.top/Article/details/gttabxspna.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.guannengcc.top/Article/details/gttiiqwqaw.html

[D02] 追加元素到末尾
来源：http://dali.chenzaomai.com/Article/details/gtxycxdypk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hysaishi.cn/Article/details/gtxywawmca.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gotoacloud.top/Article/details/gtkxgpmtlt.html

JS:   arr.push(4);
来源：http://dali.gzhubu.top/Article/details/gtgxyxkbwt.html

TS:   arr.push(4);
来源：http://dali.zhoulong.xyz/Article/details/gtwmswesaz.html

Java: list.add(4);
来源：http://dali.svipenyu.cn/Article/details/gtgirodxoc.html

Go:   arr = append(arr, 4)
来源：http://dali.ppjwa.cn/Article/details/gtnzyahtfz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfahlcxwh.html

C#:   list.Add(4);
来源：http://dali.ydzc1.top/Article/details/gtumceqvpp.html

[D03] 在指定位置插入元素
来源：http://dali.yonumen.top/Article/details/gtxytiyysl.html

Py:   arr.insert(0, 0)
来源：http://dali.bjfxy.top/Article/details/gtcxdqahlr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.meibo888.top/Article/details/gtasejimtz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yj20258888.top/Article/details/gtvodppslj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtcgmremso.html

Java: list.add(0, 0);
来源：http://dali.aibaodan.cn/Article/details/gtbagtsuqf.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.nwbrower.top/Article/details/gtzsmdbsyo.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hywenlv.cn/Article/details/gtqrijnjbl.html

C#:   list.Insert(0, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtymtfikle.html

[D04] 删除元素
来源：http://dali.cqqwz.cn/Article/details/gteawuxrhl.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.snrcjt.cn/Article/details/gtztwqvgqu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtvnjxketa.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yanxiufei.cn/Article/details/gtdxwkksgb.html

TS:   arr.splice(0, 1);
来源：http://dali.ppjwa.cn/Article/details/gtzeodbkhm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gaohongyu789.top/Article/details/gtdgqokcjx.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.aibaodan.cn/Article/details/gtmdizeybt.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yuanzhike.top/Article/details/gtuifmeddv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hnqzz.top/Article/details/gtrkjorksz.html

[D05] 访问与修改元素
来源：http://dali.zdqjudy.top/Article/details/gtzbfrukij.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shuidangran.top/Article/details/gtqckkdrdv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.meibo888.top/Article/details/gtsqzamfpt.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.quarkkingdee.top/Article/details/gtmilkkcxa.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.chenjidiqi.icu/Article/details/gtmylnwdjf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinqigufen.top/Article/details/gtrpntjfgp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yongpay.top/Article/details/gtlwmshdgq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aizwys.cn/Article/details/gtmarquwmz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gogol.net.cn/Article/details/gtwbsnnedz.html

[D06] 数组长度
来源：http://dali.quarkkingdee.top/Article/details/gtaejcqoxk.html

Py:   len(arr)
来源：http://dali.yuanzhike.top/Article/details/gtuecxlfek.html

PHP:  count($arr);
来源：http://dali.guannengcc.top/Article/details/gtaimjxxre.html

JS:   arr.length
来源：http://dali.ivvv.top/Article/details/gtjpzqjryr.html

TS:   arr.length
来源：http://dali.hnqzz.top/Article/details/gtfoywaarb.html

Java: list.size();
来源：http://dali.havefunace.top/Article/details/gtuhqqutgd.html

Go:   len(arr)
来源：http://dali.aizwys.cn/Article/details/gtgaekkeyp.html

Ruby: arr.length; arr.size
来源：http://dali.zycfv.cn/Article/details/gtjqiuetto.html

C#:   list.Count;
来源：http://dali.zhiwuduotai.top/Article/details/gtywdmqkcg.html

[D07] 切片 / 取子数组
来源：http://dali.zdqjudy.top/Article/details/gtmfgrldje.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xinyue.icu/Article/details/gtlafxvzsd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hnxiangtu.top/Article/details/gtetrppvqq.html

JS:   arr.slice(1, 4);
来源：http://dali.yj20258888.top/Article/details/gtigjlxgmp.html

TS:   arr.slice(1, 4);
来源：http://dali.chenlongwang.top/Article/details/gthhhalycz.html

Java: list.subList(1, 4);
来源：http://dali.smart0.xyz/Article/details/gtqgmkpqme.html

Go:   arr[1:4]
来源：http://dali.yonumen.top/Article/details/gtiroxpbpv.html

Ruby: arr[1, 3]
来源：http://dali.nanxuanxn.top/Article/details/gtqnemfcnq.html

C#:   list.GetRange(1, 3);
来源：http://dali.nwbrower.top/Article/details/gtxmsaacvp.html

[D08] 合并两个数组
来源：http://dali.vqdsnc.cn/Article/details/gtryipnyem.html

Py:   a + b;  a.extend(b)
来源：http://dali.ivvv.top/Article/details/gtgbzpgccj.html

PHP:  array_merge($a, $b);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuobdpcei.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinghuilouyu.cn/Article/details/gtyzjeftct.html

TS:   [...a, ...b];
来源：http://dali.snrcjt.cn/Article/details/gtdivbdghv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.mhx1999.top/Article/details/gtdzaoyaet.html

Go:   append(a, b...)
来源：http://dali.vqdsnc.cn/Article/details/gtcruhxfgf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yuxming.cn/Article/details/gtrkzmucdo.html

C#:   a.Concat(b).ToList()
来源：http://dali.gotoacloud.top/Article/details/gtfyeovipt.html

[D09] 排序（升序）
来源：http://dali.vqdsnc.cn/Article/details/gtdzkuiena.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuanzhike.top/Article/details/gtkcijiudj.html

PHP:  sort($arr);
来源：http://dali.yuanzhike.top/Article/details/gtrmgqegrd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.nanxuanxn.top/Article/details/gtqidxazog.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhongyouzk.top/Article/details/gtmljqrpvo.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hfpthk.cn/Article/details/gtypgzlifu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.fengsongda.top/Article/details/gtmphmitqx.html

Ruby: arr.sort
来源：http://dali.hysaishi.cn/Article/details/gtobwpludp.html

C#:   list.Sort();
来源：http://dali.pycfn.com/Article/details/gttnmpigwp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.nanxuanxn.top/Article/details/gtntphzkoh.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtdyvdlfqv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.wangdashe.top/Article/details/gtnprqylny.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xylfe.cn/Article/details/gthgwhgkcw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ppjwa.cn/Article/details/gtqbuywenq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shzxlz.cn/Article/details/gtmkdxxypb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ybcxt.top/Article/details/gtauarchwq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sxryk.cn/Article/details/gtpebvmdmq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.svipenyu.cn/Article/details/gtlugsretv.html


<!-- 参考信息 -->