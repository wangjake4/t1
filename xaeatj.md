代发 wailian999

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tianlin.xyz/Article/details/gtvgpmtpck.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.snrcjt.cn/Article/details/gtjozkcdwf.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.gaohongyu789.top/Article/details/gtwsdsnhfw.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.daxiang520.top/Article/details/gtfdpqyerl.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.redwolf501.top/Article/details/gtmzmsjohe.html

[B10] 遍历同时拿索引
来源：http://dali.sweek.top/Article/details/gtgaeybuda.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.cheryme.top/Article/details/gtxpmthhhk.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jiagoushi.top/Article/details/gteshumxip.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yongpay.top/Article/details/gtqgrvammi.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.pengpengdd.cyou/Article/details/gtyycgagmh.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.gotoacloud.top/Article/details/gtubvedncn.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvkynskwa.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.dianchejie.cn/Article/details/gtfmhkmtez.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.tanke756.top/Article/details/gtqfflqlap.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhaomingkeji.xyz/Article/details/gtboshjhhl.html

Py:   list(range(0, 10, 2))
来源：http://dali.andypj.xyz/Article/details/gtpbaycrhr.html

PHP:  range(0, 10, 2);
来源：http://dali.cdnleiting.top/Article/details/gttdzknyji.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cqqwz.cn/Article/details/gtuthvklai.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtqxcrbbdz.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cdnleiting.top/Article/details/gtsxfqqicf.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.smart0.xyz/Article/details/gtumedgiuf.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ehwqpu.com/Article/details/gtvldpuhcy.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yonumen.top/Article/details/gtdrsxpahs.html

[B12] 跳出多层循环
来源：http://dali.xinyue.icu/Article/details/gtubjdkzvo.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.iojbl.cn/Article/details/gtuhvrkcyr.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hnxiangtu.top/Article/details/gtalgtbxsu.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hysaishi.cn/Article/details/gtzajweetn.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.dashuyun.cn/Article/details/gtbvgwpjkf.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jiagoushi.top/Article/details/gttvbqdjgy.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhongyouzk.top/Article/details/gtioxxrnjb.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yuxming.cn/Article/details/gtyjemflhe.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xuanzx.com/Article/details/gtajssujqi.html

[B13] 判断是否为数字
来源：http://dali.yueranfly.top/Article/details/gttynbmjth.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhixingplan.top/Article/details/gtnmqsaikq.html

PHP:  is_numeric($x)
来源：http://dali.zhengqikj.top/Article/details/gtnwqopwzr.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.andypj.xyz/Article/details/gtodqlcdlu.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ehwqpu.com/Article/details/gtactjvqoc.html

Java: x instanceof Number
来源：http://dali.andypj.xyz/Article/details/gtgkajzrkq.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ydzc1.top/Article/details/gtrovxkhig.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xinyue.icu/Article/details/gtnsmpjuwe.html

C#:   x is int or double or decimal
来源：http://dali.haohaochexian.top/Article/details/gtotuoqpti.html

[B14] 判断值是否在集合内
来源：http://dali.nanxinkj.top/Article/details/gtzdlxkpnu.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.bjfxy.top/Article/details/gthovqoymh.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yuxming.cn/Article/details/gtqtmjznkh.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.andypj.xyz/Article/details/gtakpcyewh.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgpeutkoy.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.9152youxi.cn/Article/details/gtgzimfnje.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.cashguo.top/Article/details/gtybrnrzvo.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.tianlin.xyz/Article/details/gtyhisetaz.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yueranfly.top/Article/details/gtbwrlcoye.html

[B15] 布尔运算与取反
来源：http://dali.gaohongyu789.top/Article/details/gtilrblngg.html

Py:   a and b or not c
来源：http://dali.jyoumei.cn/Article/details/gtbnhcwnyz.html

PHP:  $a && $b || !$c
来源：http://dali.jlsjyb.cn/Article/details/gtiyamqefn.html

JS:   a && b || !c
来源：http://dali.wangdashe.top/Article/details/gtbkxbshby.html

TS:   a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gtdheetzpc.html

Java: a && b || !c
来源：http://dali.shuidangran.top/Article/details/gttvwjcpaf.html

Go:   a && b || !c
来源：http://dali.tianlin.xyz/Article/details/gtivckqtuw.html

Ruby: a && b || !c
来源：http://dali.xylfe.cn/Article/details/gtuvvwukan.html

C#:   a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtqyyjgplx.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yuanzhike.top/Article/details/gtgwycjeop.html

Py:   if not data: return
来源：http://dali.yongpay.top/Article/details/gtpzxkogoi.html

PHP:  if (!$data) { return; }
来源：http://dali.gotoacloud.top/Article/details/gtyxxruyye.html

JS:   if (!data) return;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyepgcvoc.html

TS:   if (!data) return;
来源：http://dali.gaohongyu789.top/Article/details/gtfpxdlvjr.html

Java: if (data == null) return;
来源：http://dali.svipenyu.cn/Article/details/gtbxqpiyyb.html

Go:   if data == nil { return }
来源：http://dali.yj202588.top/Article/details/gtcvjpuned.html

Ruby: return if data.nil?
来源：http://dali.316326.xyz/Article/details/gturwxjdeb.html

C#:   if (data == null) return;
来源：http://dali.nwbrower.top/Article/details/gtqyjnawrf.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gthzrctaau.html

C. 函数与作用域
来源：http://dali.gogol.net.cn/Article/details/gtmkxsscni.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtzvhunfdz.html

[C01] 定义函数
来源：http://dali.guowangkeji.top/Article/details/gtptpsogfs.html

Py:   def add(a, b): return a + b
来源：http://dali.chenzaomai.com/Article/details/gtszybaics.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gtflszsqpx.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gtlrqmfpbo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ivvv.top/Article/details/gtwidusqis.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gtfuzfaxfu.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yj20258.top/Article/details/gtoosswyfd.html

Ruby: def add(a, b); a + b; end
来源：http://dali.wangdashe.top/Article/details/gtrbsdahfo.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gtqdiiuiuz.html

[C02] 默认参数
来源：http://dali.yonumen.top/Article/details/gtgdfmfqrg.html

Py:   def greet(name="World"): return name
来源：http://dali.ivvv.top/Article/details/gtfyyvmudv.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.iojbl.cn/Article/details/gtbhyczlzs.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hammf.cn/Article/details/gttquqxtba.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.gogol.net.cn/Article/details/gtuzjgfjxc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.tanke756.top/Article/details/gtqhafrdyd.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zycfv.cn/Article/details/gtahqptxam.html

Ruby: def greet(name = "World") = name
来源：http://dali.aizwys.cn/Article/details/gtmjvqkjtb.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xinyue.icu/Article/details/gtxdimnfjg.html

[C03] 可变参数
来源：http://dali.yuxming.cn/Article/details/gtvbizdqqm.html

Py:   def total(*args): return sum(args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpxoohbvy.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hywenlv.cn/Article/details/gtupbukdwb.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sufxvd.cn/Article/details/gtbbkeoqxt.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hnxiangtu.top/Article/details/gtddizvysh.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhixingplan.top/Article/details/gtewdfgbit.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhongyouzk.top/Article/details/gtiavngcuk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.snrcjt.cn/Article/details/gtnozbywmr.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yonumen.top/Article/details/gtamqgwabb.html

[C04] 命名参数 / 关键字参数
来源：http://dali.tanke756.top/Article/details/gtpjopaxhu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.guannengcc.top/Article/details/gtvoubmssa.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zdqjudy.top/Article/details/gtbhfvvfmi.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yangfankeji.com/Article/details/gtxdupzhhn.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ivvv.top/Article/details/gtszwgatsy.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jinqigufen.top/Article/details/gtdaejlzms.html

Go:   // 无：用配置结构体参数
来源：http://dali.xziqi.cn/Article/details/gtljcztzhc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hywenlv.cn/Article/details/gtybcbylbc.html

C#:   f(a: 1, b: 2)
来源：http://dali.yueranfly.top/Article/details/gtajtirfqq.html

[C05] 返回多个值
来源：http://dali.jlsjyb.cn/Article/details/gtbubqtdmc.html

Py:   return a, b
来源：http://dali.havefunace.top/Article/details/gtxtzqrrni.html

PHP:  return [$a, $b];
来源：http://dali.tanke756.top/Article/details/gtngiffxng.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hfpthk.cn/Article/details/gtcdwqezau.html

TS:   return { a, b };
来源：http://dali.cdnleiting.top/Article/details/gttjsstmva.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.guowangkeji.top/Article/details/gtnulmishe.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gthsgvyrkh.html

Ruby: return a, b
来源：http://dali.andypj.xyz/Article/details/gtcerueeql.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhengqikj.top/Article/details/gtcgigxkhp.html

[C06] 匿名函数 / lambda
来源：http://dali.xziqi.cn/Article/details/gtrcxvnqbw.html

Py:   square = lambda x: x * x
来源：http://dali.yueranfly.top/Article/details/gtovsiafcq.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhengqikj.top/Article/details/gtzxnyjemg.html

JS:   const square = x => x * x;
来源：http://dali.havefunace.top/Article/details/gtiwkpfftz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jqgfzy.top/Article/details/gtzuynvbot.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ydzc1.top/Article/details/gtqvgfjork.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.aizwys.cn/Article/details/gtwssscdxm.html

Ruby: square = ->(x) { x * x }
来源：http://dali.tanke756.top/Article/details/gtvvvvaydp.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shuidangran.top/Article/details/gtdygqctoi.html

[C07] 把函数作为参数传入
来源：http://dali.chenlongwang.top/Article/details/gtipcugoxe.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.redwolf501.top/Article/details/gtfntgkbuq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.haohaochexian.top/Article/details/gtnnbeueew.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.sweek.top/Article/details/gtbmudoerm.html

TS:   arr.map(String)
来源：http://dali.ehwqpu.com/Article/details/gtxilxvpqq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.nanxinkj.top/Article/details/gtetwruzlj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ybcxt.top/Article/details/gtcwqoigjp.html

Ruby: arr.map(&:upcase)
来源：http://dali.yj20258.top/Article/details/gtgwtiymtp.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yj202588.top/Article/details/gttdkfkbnc.html

[C08] 闭包
来源：http://dali.wangdashe.top/Article/details/gtfdfmggbu.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shanyushiyangtech.top/Article/details/gtdvmenlga.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xziqi.cn/Article/details/gtwkitlpju.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hysaishi.cn/Article/details/gtrylnznpv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xylfe.cn/Article/details/gtvmekquas.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hnxiangtu.top/Article/details/gtuhbnjuro.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jlsjyb.cn/Article/details/gtxxiplhxe.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jqgfzy.top/Article/details/gtmiulxneu.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.aibaodan.cn/Article/details/gtniqnqmgc.html

[C09] 递归
来源：http://dali.jinqigufen.top/Article/details/gtlrhdrzsl.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yanxiufei.cn/Article/details/gtsdvgnyzs.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.birdmap.top/Article/details/gtxztfeeeb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zycfv.cn/Article/details/gtobvvqzar.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zycfv.cn/Article/details/gtedpbukez.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.bjfxy.top/Article/details/gtxdrehwga.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ybcxt.top/Article/details/gtbhdtaakm.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhoulong.xyz/Article/details/gtnihxnzjh.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsnnkimvz.html

[C10] 变量作用域
来源：http://dali.gzhubu.top/Article/details/gtkgzzidys.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.c1oappe.top/Article/details/gtpjbixneq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hfpthk.cn/Article/details/gtyfwsngzc.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.wangshuangyany.cn/Article/details/gtfzlgdcit.html

TS:   同 JS
来源：http://dali.zhengqikj.top/Article/details/gtjvorfunu.html

Java: 方法内为块级作用域
来源：http://dali.cucudq.cn/Article/details/gtswftwdvm.html

Go:   花括号块级作用域
来源：http://dali.dianchejie.cn/Article/details/gtcooarvny.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.guowangkeji.top/Article/details/gtuvlyrkgp.html

C#:   块级作用域
来源：http://dali.jlsjyb.cn/Article/details/gthhkwafvr.html

[C11] 模块导入与导出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbgjcxctq.html

Py:   from module import func
来源：http://dali.aibaodan.cn/Article/details/gtzswwggim.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.vqdsnc.cn/Article/details/gtpgictkob.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cdnleiting.top/Article/details/gtolmpirai.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.iojbl.cn/Article/details/gtfinafczx.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gtivlcoton.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cheryme.top/Article/details/gtyhcgxrhx.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.redwolf501.top/Article/details/gtliaipyid.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gtoldnsfvo.html

[C12] 立即执行函数 IIFE
来源：http://dali.hywenlv.cn/Article/details/gtqjliakui.html

Py:   (lambda: print("run"))()
来源：http://dali.yuxming.cn/Article/details/gtrapifdds.html

PHP:  (function () { echo "run"; })();
来源：http://dali.dashuyun.cn/Article/details/gtvqbkdoop.html

JS:   (() => { console.log("run"); })();
来源：http://dali.redwolf501.top/Article/details/gtueyexiun.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqybqdgct.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhoulong.xyz/Article/details/gtsourfciu.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.aizwys.cn/Article/details/gtbqrvjgbb.html

Ruby: -> { puts "run" }.call
来源：http://dali.xuetiantiany.cn/Article/details/gtlzhqxhmd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.birdmap.top/Article/details/gtpbotpoal.html

[C13] 类型声明 / 类型注解
来源：http://dali.yj20258.top/Article/details/gtnrjxlrtn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ehwqpu.com/Article/details/gtaugvsysv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gtodyugoxw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.chenjidiqi.icu/Article/details/gtzkshkmwx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gtdyswzyzy.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtcjaxshwo.html

Go:   func add(a, b int) int
来源：http://dali.tianlin.xyz/Article/details/gtmmjchgwb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yvedp.cn/Article/details/gtexeqoona.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yj20258.top/Article/details/gtajjbueoy.html

[C14] 泛型函数
来源：http://dali.hywenlv.cn/Article/details/gtwfdpagyu.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ivvv.top/Article/details/gtzmpjobar.html

PHP:  // 无泛型
来源：http://dali.chenlongwang.top/Article/details/gtjndyxule.html

JS:   // 无泛型
来源：http://dali.chenzaomai.com/Article/details/gthcidocxl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.guowangkeji.top/Article/details/gtxmgjvbti.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jyoumei.cn/Article/details/gtxdbkcphh.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.aibaodan.cn/Article/details/gtlnpadjei.html

Ruby: # 无泛型
来源：http://dali.yj20258888.top/Article/details/gtelacevcp.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.dianchejie.cn/Article/details/gtzrecxpkr.html

[C15] 解构 / 展开参数
来源：http://dali.wangdashe.top/Article/details/gtablujxqp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xylfe.cn/Article/details/gthnwtzjqf.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yvedp.cn/Article/details/gthzcwxiog.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jinqigfzy.top/Article/details/gtmdqsrrmv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hywenlv.cn/Article/details/gtltjlhelg.html

Java: // 无解构
来源：http://dali.yongpay.top/Article/details/gtvbayduij.html

Go:   // 无解构
来源：http://dali.shangyingyoupin.top/Article/details/gtjunfnhbk.html

Ruby: a, b = pair
来源：http://dali.zhoulong.xyz/Article/details/gtwbvydibm.html

C#:   var (a, b) = pair;
来源：http://dali.hongshengwenyu.top/Article/details/gtadtybaec.html

[C16] 函数 / 方法重载
来源：http://dali.cdnleiting.top/Article/details/gtzdcripja.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.tanke756.top/Article/details/gtpdwmwzma.html

PHP:  // 无重载
来源：http://dali.tianlin.xyz/Article/details/gtiympzmdy.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.haohaochexian.top/Article/details/gthdxwcncd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xziqi.cn/Article/details/gtxtmmfkbk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gaohongyu789.top/Article/details/gtaemfkccg.html

Go:   // 无重载：用不同函数名
来源：http://dali.shuidangran.top/Article/details/gtzupzncsz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlqrvohvz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.birdmap.top/Article/details/gtsztgizmv.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtlyenlvud.html

D. 数组 / 列表 / 集合
来源：http://dali.zhoulong.xyz/Article/details/gtczawpmrr.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtpesbvzvt.html

[D01] 创建数组 / 列表
来源：http://dali.shanyushiyangtech.top/Article/details/gtncrntrym.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.chenlongwang.top/Article/details/gtyjbesyay.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.nanxuanxn.top/Article/details/gtpckyvwgj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shuidangran.top/Article/details/gtoswbvqpr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.gotoacloud.top/Article/details/gtwevjiviu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gtbrxxnrwu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinqigufen.top/Article/details/gtezglxkrd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.tian-w.cn/Article/details/gtmhfzrizj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.kuanghao11.cn/Article/details/gtropxuzef.html

[D02] 追加元素到末尾
来源：http://dali.nanxinkj.top/Article/details/gtetgfnppv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtshpliitu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.daria6918.cn/Article/details/gtpdpnfowt.html

JS:   arr.push(4);
来源：http://dali.hnqzz.top/Article/details/gtpfaiusaj.html

TS:   arr.push(4);
来源：http://dali.0kj1m.cn/Article/details/gtlayoooqx.html

Java: list.add(4);
来源：http://dali.cucudq.cn/Article/details/gtvudabuky.html

Go:   arr = append(arr, 4)
来源：http://dali.aibaodan.cn/Article/details/gtiregdits.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.mhx1999.top/Article/details/gtgtocyotr.html

C#:   list.Add(4);
来源：http://dali.chenlongwang.top/Article/details/gtzvsuyhlw.html

[D03] 在指定位置插入元素
来源：http://dali.vqdsnc.cn/Article/details/gtgmaagyez.html

Py:   arr.insert(0, 0)
来源：http://dali.jinqigufen.top/Article/details/gtxrdarzfg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.nanxuanxn.top/Article/details/gtgkuhnpig.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.wangshuangyany.cn/Article/details/gthuhrnalw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yj20258.top/Article/details/gtfswlhuvy.html

Java: list.add(0, 0);
来源：http://dali.jinqigufen.top/Article/details/gtsvwznfxy.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.iojbl.cn/Article/details/gtvjanoirr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yonumen.top/Article/details/gtlcnyougn.html

C#:   list.Insert(0, 0);
来源：http://dali.ivvv.top/Article/details/gtiwvgylsa.html

[D04] 删除元素
来源：http://dali.zhongyouzk.top/Article/details/gtnihakffz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xinyue.icu/Article/details/gtbxqfscba.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xinyue.icu/Article/details/gtemvcupzn.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtadkwtgbb.html

TS:   arr.splice(0, 1);
来源：http://dali.hongshengwenyu.top/Article/details/gtndqmlbuo.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.chenzaomai.com/Article/details/gtvatohpsx.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.smart0.xyz/Article/details/gttodjwbpt.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xinyue.icu/Article/details/gtbwsgkmui.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gtlzqdbwva.html

[D05] 访问与修改元素
来源：http://dali.gogol.net.cn/Article/details/gtywqstnva.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zdqjudy.top/Article/details/gtgxkfphqm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.meibo888.top/Article/details/gtnsyoyjzj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cheryme.top/Article/details/gtpngvblqv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cdnleiting.top/Article/details/gtvjipuaab.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcqzhaqui.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hfpthk.cn/Article/details/gtcrcocjrr.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cucudq.cn/Article/details/gtwizizvzv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jlsjyb.cn/Article/details/gtdzbxayah.html

[D06] 数组长度
来源：http://dali.chenzaomai.com/Article/details/gtoaacexey.html

Py:   len(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtnxkmsycq.html

PHP:  count($arr);
来源：http://dali.yuxming.cn/Article/details/gtvjvzepkd.html

JS:   arr.length
来源：http://dali.yuanzhike.top/Article/details/gtwnnuymrx.html

TS:   arr.length
来源：http://dali.yangfankeji.com/Article/details/gttyyvoefa.html

Java: list.size();
来源：http://dali.ehwqpu.com/Article/details/gtjijzdexv.html

Go:   len(arr)
来源：http://dali.gogol.net.cn/Article/details/gtlddrqozm.html

Ruby: arr.length; arr.size
来源：http://dali.xuanzx.com/Article/details/gtqossmycq.html

C#:   list.Count;
来源：http://dali.jyoumei.cn/Article/details/gtsjjslyct.html

[D07] 切片 / 取子数组
来源：http://dali.shuidangran.top/Article/details/gtszusqofq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbdlfvqgt.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinqigufen.top/Article/details/gtdopybwos.html

JS:   arr.slice(1, 4);
来源：http://dali.svipenyu.cn/Article/details/gtmfniszbj.html

TS:   arr.slice(1, 4);
来源：http://dali.yanxiufei.cn/Article/details/gtzjhhlven.html

Java: list.subList(1, 4);
来源：http://dali.gzhubu.top/Article/details/gtruganutu.html

Go:   arr[1:4]
来源：http://dali.bjfxy.top/Article/details/gtmfjumqsb.html

Ruby: arr[1, 3]
来源：http://dali.birdmap.top/Article/details/gtsqbhnkrz.html

C#:   list.GetRange(1, 3);
来源：http://dali.kuanghao11.cn/Article/details/gtvulhhreg.html

[D08] 合并两个数组
来源：http://dali.yvedp.cn/Article/details/gtztfhqwqa.html

Py:   a + b;  a.extend(b)
来源：http://dali.ehwqpu.com/Article/details/gtrhzakitp.html

PHP:  array_merge($a, $b);
来源：http://dali.316326.xyz/Article/details/gtmgjqsykr.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xinyue.icu/Article/details/gtfutmatps.html

TS:   [...a, ...b];
来源：http://dali.zdqjudy.top/Article/details/gtcyqokpze.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yj202588.top/Article/details/gtfvclnbsi.html

Go:   append(a, b...)
来源：http://dali.kuanghao11.cn/Article/details/gtcvhpazqn.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbrgrcddr.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtavkrbdid.html

[D09] 排序（升序）
来源：http://dali.zhixingplan.top/Article/details/gtjcavghrp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258888.top/Article/details/gtnegnzisa.html

PHP:  sort($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtekdwtrtw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jiagoushi.top/Article/details/gtogsxlkei.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yuanzhike.top/Article/details/gtrcvudlhe.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zdqjudy.top/Article/details/gtswuhbrma.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtochrdkji.html

Ruby: arr.sort
来源：http://dali.snrcjt.cn/Article/details/gtuprnphvv.html

C#:   list.Sort();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtifrpbnun.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhengqikj.top/Article/details/gtayczhrgh.html


<!-- 参考信息 -->