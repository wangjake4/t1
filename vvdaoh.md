代发 wailian999

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.vqdsnc.cn/Article/details/gttbbttwaq.html

[B10] 遍历同时拿索引
来源：http://dali.chenjidiqi.icu/Article/details/gtojmrhhzd.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.meibo888.top/Article/details/gtlvjjldxq.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.tanke756.top/Article/details/gtjoziqbgx.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hnxiangtu.top/Article/details/gtnvwcgvpb.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.aizwys.cn/Article/details/gtfpzlgtnq.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yongpay.top/Article/details/gtokzaohbm.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yj20258.top/Article/details/gtveumslme.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zdqjudy.top/Article/details/gtcadzclqm.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.sufxvd.cn/Article/details/gthoobpwht.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuhsvygix.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhoulong.xyz/Article/details/gtntoznqtm.html

PHP:  range(0, 10, 2);
来源：http://dali.xinyue.icu/Article/details/gtoszmqbqm.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ydzc1.top/Article/details/gtovfrmndi.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ydzc1.top/Article/details/gtauczqsrm.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.dianchejie.cn/Article/details/gtxxztbgvj.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yj20258888.top/Article/details/gtzrgyjfom.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ppjwa.cn/Article/details/gtmjdvxbli.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.daxiang520.top/Article/details/gthknjnecd.html

[B12] 跳出多层循环
来源：http://dali.wangdashe.top/Article/details/gtkewzicyl.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yj202588.top/Article/details/gtxevdojhq.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zycfv.cn/Article/details/gtjxdofkkq.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.guannengcc.top/Article/details/gtgcmouyfy.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.andypj.xyz/Article/details/gtqpktgnmx.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.tian-w.cn/Article/details/gtmacpumrj.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xylfe.cn/Article/details/gtlqahazck.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.gzhubu.top/Article/details/gttoxmsoft.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jlsjyb.cn/Article/details/gtscvwvqmz.html

[B13] 判断是否为数字
来源：http://dali.havefunace.top/Article/details/gttghzxxxz.html

Py:   isinstance(x, (int, float))
来源：http://dali.cucudq.cn/Article/details/gtoevcgzfa.html

PHP:  is_numeric($x)
来源：http://dali.hongshengwenyu.top/Article/details/gteurpmjrs.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtpzkrgebt.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tianlin.xyz/Article/details/gtncuxnmjs.html

Java: x instanceof Number
来源：http://dali.ehwqpu.com/Article/details/gtsylbtypz.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.feifeiyinyue.top/Article/details/gtzenpemyy.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yuxming.cn/Article/details/gtkpioydlz.html

C#:   x is int or double or decimal
来源：http://dali.zhoulong.xyz/Article/details/gttfedurjc.html

[B14] 判断值是否在集合内
来源：http://dali.gzhubu.top/Article/details/gtdrtnhlzz.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.9152youxi.cn/Article/details/gtggdklgab.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hnxiangtu.top/Article/details/gtovrltzcf.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zycfv.cn/Article/details/gtdpvwpctr.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.aibaodan.cn/Article/details/gtirwotqcc.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.gotoacloud.top/Article/details/gtvdaokdqx.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yonumen.top/Article/details/gtfifreidj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkskbrezc.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.dashuyun.cn/Article/details/gtadyxvkvu.html

[B15] 布尔运算与取反
来源：http://dali.tianlin.xyz/Article/details/gtpiyioceg.html

Py:   a and b or not c
来源：http://dali.cqqwz.cn/Article/details/gtmktcpbwf.html

PHP:  $a && $b || !$c
来源：http://dali.xziqi.cn/Article/details/gtnieqtqda.html

JS:   a && b || !c
来源：http://dali.redwolf501.top/Article/details/gtujameeep.html

TS:   a && b || !c
来源：http://dali.fengsongda.top/Article/details/gtsqemqrwy.html

Java: a && b || !c
来源：http://dali.aizwys.cn/Article/details/gtshvxvzej.html

Go:   a && b || !c
来源：http://dali.tianlin.xyz/Article/details/gtdhhhugmy.html

Ruby: a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrbbaqdkc.html

C#:   a && b || !c
来源：http://dali.sysykeji.top/Article/details/gtaqxwsers.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ehwqpu.com/Article/details/gtitdnshue.html

Py:   if not data: return
来源：http://dali.snrcjt.cn/Article/details/gtumsydjou.html

PHP:  if (!$data) { return; }
来源：http://dali.birdmap.top/Article/details/gtqqkqaahm.html

JS:   if (!data) return;
来源：http://dali.nwbrower.top/Article/details/gtqmcohwvb.html

TS:   if (!data) return;
来源：http://dali.jlsjyb.cn/Article/details/gtgebwfjyc.html

Java: if (data == null) return;
来源：http://dali.nanxinkj.top/Article/details/gtprcsgnfe.html

Go:   if data == nil { return }
来源：http://dali.jqgufenzy.top/Article/details/gtbklpuixs.html

Ruby: return if data.nil?
来源：http://dali.ehwqpu.com/Article/details/gtmszentqo.html

C#:   if (data == null) return;
来源：http://dali.ppjwa.cn/Article/details/gtevslpsqu.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtxsrdcfhd.html

C. 函数与作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gtwjygiqac.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtieoqzfni.html

[C01] 定义函数
来源：http://dali.9152youxi.cn/Article/details/gtzjodutvf.html

Py:   def add(a, b): return a + b
来源：http://dali.yongpay.top/Article/details/gtzkdspzjr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.fzhhl.top/Article/details/gtqpfpjjjx.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gtedxuxpgj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtdhvmwqof.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gtvtekclum.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hongshengwenyu.top/Article/details/gtknpdttvh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.kuanghao11.cn/Article/details/gtbqoaisxs.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gtofmzqpvn.html

[C02] 默认参数
来源：http://dali.bjfxy.top/Article/details/gtjtsrzmsd.html

Py:   def greet(name="World"): return name
来源：http://dali.ehwqpu.com/Article/details/gtvwauqefr.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yonumen.top/Article/details/gtdjiorsxy.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpzpvuqfl.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkxocwmyj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.wangshuangyany.cn/Article/details/gtuxthpkgp.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.nwbrower.top/Article/details/gtsnenqxps.html

Ruby: def greet(name = "World") = name
来源：http://dali.wangshuangyany.cn/Article/details/gtfirkrjhi.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cashguo.top/Article/details/gtskqnnrjf.html

[C03] 可变参数
来源：http://dali.cdnleiting.top/Article/details/gtlkeziosl.html

Py:   def total(*args): return sum(args)
来源：http://dali.wangdashe.top/Article/details/gteschkpmd.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhoulong.xyz/Article/details/gtghmhtpho.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tianlin.xyz/Article/details/gtoiubsnbb.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gteokuzzxv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jlsjyb.cn/Article/details/gtgeoeists.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jlsjyb.cn/Article/details/gtrthciodl.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.gotoacloud.top/Article/details/gtfvfflkta.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yj20258.top/Article/details/gtwignehqh.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jyoumei.cn/Article/details/gtknpwjvjd.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hysaishi.cn/Article/details/gtlcucdbdk.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtrdhszggp.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.chenzaomai.com/Article/details/gtzdolqoiu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.9152youxi.cn/Article/details/gthqqdnefa.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.svipenyu.cn/Article/details/gttzqudzlf.html

Go:   // 无：用配置结构体参数
来源：http://dali.sysykeji.top/Article/details/gtmmthquma.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ivvv.top/Article/details/gtgmskiejb.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhixingplan.top/Article/details/gtmubrsdks.html

[C05] 返回多个值
来源：http://dali.gotoacloud.top/Article/details/gtirjklofw.html

Py:   return a, b
来源：http://dali.yj20258888.top/Article/details/gtplvpbudj.html

PHP:  return [$a, $b];
来源：http://dali.daxiang520.top/Article/details/gtljrjnymb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.0kj1m.cn/Article/details/gtldqpaxwv.html

TS:   return { a, b };
来源：http://dali.0kj1m.cn/Article/details/gtarbhrheb.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ivvv.top/Article/details/gtbilqfhnk.html

Go:   return a, b
来源：http://dali.xylfe.cn/Article/details/gtziyqwlci.html

Ruby: return a, b
来源：http://dali.ydzc1.top/Article/details/gtqaouvhmo.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.vqdsnc.cn/Article/details/gthppxzgou.html

[C06] 匿名函数 / lambda
来源：http://dali.nwbrower.top/Article/details/gtthvgyrhk.html

Py:   square = lambda x: x * x
来源：http://dali.havefunace.top/Article/details/gtigzlrjsk.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.0kj1m.cn/Article/details/gtnppvsegl.html

JS:   const square = x => x * x;
来源：http://dali.chenlongwang.top/Article/details/gtbzeoivoo.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgxqrvqon.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.chenjidiqi.icu/Article/details/gtxetmntse.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.meibo888.top/Article/details/gtfdtempib.html

Ruby: square = ->(x) { x * x }
来源：http://dali.gotoacloud.top/Article/details/gtwufnjpxv.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yueranfly.top/Article/details/gtlyidjqhv.html

[C07] 把函数作为参数传入
来源：http://dali.pycfn.com/Article/details/gtmffwinag.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hnxiangtu.top/Article/details/gtcjzktprv.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtmkfwykdx.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.sxryk.cn/Article/details/gtmpkqqxta.html

TS:   arr.map(String)
来源：http://dali.cashguo.top/Article/details/gtjmzkmpnb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ehwqpu.com/Article/details/gtryjjhtav.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hnxiangtu.top/Article/details/gttgdrzdzt.html

Ruby: arr.map(&:upcase)
来源：http://dali.sweek.top/Article/details/gtxjvavbbp.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.kuanghao11.cn/Article/details/gtokkgzjhb.html

[C08] 闭包
来源：http://dali.yvedp.cn/Article/details/gtbqlzqkzj.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.pengpengdd.cyou/Article/details/gtpnowpvut.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.chenlongwang.top/Article/details/gtartzfyfu.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ehwqpu.com/Article/details/gtwwzvyjgh.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yonumen.top/Article/details/gtcluorpvd.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.quarkkingdee.top/Article/details/gtnrpdkqvo.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.aibaodan.cn/Article/details/gtkugfwwxr.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.daria6918.cn/Article/details/gthycpehgm.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.dianchejie.cn/Article/details/gtaxkppksh.html

[C09] 递归
来源：http://dali.daria6918.cn/Article/details/gtddihmjvg.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hysaishi.cn/Article/details/gtkeymzjnz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.iojbl.cn/Article/details/gtunfyhfoj.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenlongwang.top/Article/details/gtkrlzniup.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hysaishi.cn/Article/details/gtiiuwmrut.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.mhx1999.top/Article/details/gtaoplhucw.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yj20258888.top/Article/details/gtyazgjnik.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.316326.xyz/Article/details/gttbinxeah.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.nanxuanxn.top/Article/details/gtmjtzgqmo.html

[C10] 变量作用域
来源：http://dali.smart0.xyz/Article/details/gtgrugzfnu.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.guowangkeji.top/Article/details/gtdgbzxded.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ppjwa.cn/Article/details/gtgnenrkea.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xinyue.icu/Article/details/gttgritfsr.html

TS:   同 JS
来源：http://dali.sxryk.cn/Article/details/gttbkmuwfc.html

Java: 方法内为块级作用域
来源：http://dali.chenjidiqi.icu/Article/details/gtwzrsgirz.html

Go:   花括号块级作用域
来源：http://dali.cheryme.top/Article/details/gtykccsohb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shuidangran.top/Article/details/gtlhaqclqj.html

C#:   块级作用域
来源：http://dali.gogol.net.cn/Article/details/gtuxhcljio.html

[C11] 模块导入与导出
来源：http://dali.9152youxi.cn/Article/details/gthrncykyk.html

Py:   from module import func
来源：http://dali.jyoumei.cn/Article/details/gtujodilsv.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzwidwsqf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.chenlongwang.top/Article/details/gtqnamtrtv.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.quarkkingdee.top/Article/details/gtyxfiuoig.html

Java: import java.util.List;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtklvkgoet.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hysaishi.cn/Article/details/gtzmymcdoq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zdqjudy.top/Article/details/gtdfahshtc.html

C#:   using System.Text;
来源：http://dali.gogol.net.cn/Article/details/gtypnlviwe.html

[C12] 立即执行函数 IIFE
来源：http://dali.havefunace.top/Article/details/gtrmgmzoke.html

Py:   (lambda: print("run"))()
来源：http://dali.ppjwa.cn/Article/details/gtpnovhykw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hnxiangtu.top/Article/details/gtdtbgpagi.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shzxlz.cn/Article/details/gtcwtruani.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ybcxt.top/Article/details/gtbofpjawn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.0kj1m.cn/Article/details/gtdsreymjl.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.dianchejie.cn/Article/details/gtdcnayefi.html

Ruby: -> { puts "run" }.call
来源：http://dali.jqgfzy.top/Article/details/gtjcbkrfhq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.meibo888.top/Article/details/gtygivyzox.html

[C13] 类型声明 / 类型注解
来源：http://dali.xinyue.icu/Article/details/gtmbkgcbvy.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtowtyctvc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dianchejie.cn/Article/details/gtsblexaga.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ydzc1.top/Article/details/gtehlwopre.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtzqqvmxiw.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgvfwpcbj.html

Go:   func add(a, b int) int
来源：http://dali.vqdsnc.cn/Article/details/gtznsvdwhq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ehwqpu.com/Article/details/gtkzovoytu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.mhx1999.top/Article/details/gtkntrtzku.html

[C14] 泛型函数
来源：http://dali.hnxiangtu.top/Article/details/gthslzqxcz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zycfv.cn/Article/details/gteagqxbzc.html

PHP:  // 无泛型
来源：http://dali.andypj.xyz/Article/details/gtejryfmko.html

JS:   // 无泛型
来源：http://dali.jianghu66.top/Article/details/gtfuvmmlxz.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.nanxinkj.top/Article/details/gtvrpzybcv.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqmnufcpy.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.aizwys.cn/Article/details/gtkvdhpwov.html

Ruby: # 无泛型
来源：http://dali.yj20258888.top/Article/details/gtdlrjbwsf.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhoulong.xyz/Article/details/gtpeuvdnqj.html

[C15] 解构 / 展开参数
来源：http://dali.shangyingyoupin.top/Article/details/gtgmcbtmal.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.tian-w.cn/Article/details/gtruqounjt.html

PHP:  [$a, $b] = $pair;
来源：http://dali.sufxvd.cn/Article/details/gttbxgdidy.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xuanzx.com/Article/details/gthecziipo.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sweek.top/Article/details/gtncyyejoo.html

Java: // 无解构
来源：http://dali.tian-w.cn/Article/details/gtsumdojdw.html

Go:   // 无解构
来源：http://dali.guannengcc.top/Article/details/gtxistabqb.html

Ruby: a, b = pair
来源：http://dali.jinqigfzy.top/Article/details/gtkodojqxe.html

C#:   var (a, b) = pair;
来源：http://dali.9152youxi.cn/Article/details/gtznbwkyhc.html

[C16] 函数 / 方法重载
来源：http://dali.havefunace.top/Article/details/gtbbqmikwd.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.316326.xyz/Article/details/gtbykegero.html

PHP:  // 无重载
来源：http://dali.vqdsnc.cn/Article/details/gtuwowifpu.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.316326.xyz/Article/details/gtuzgwwpcw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jiagoushi.top/Article/details/gtyhxfhwfs.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xylfe.cn/Article/details/gtupmwbsfj.html

Go:   // 无重载：用不同函数名
来源：http://dali.jqgfzy.top/Article/details/gthnsmtvjb.html

Ruby: # 无重载：靠动态参数
来源：http://dali.guowangkeji.top/Article/details/gtwvoexxok.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.wangdashe.top/Article/details/gtqiqjfbxi.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtwsnmjahp.html

D. 数组 / 列表 / 集合
来源：http://dali.snrcjt.cn/Article/details/gtscntszoz.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtpmjclaav.html

[D01] 创建数组 / 列表
来源：http://dali.xylfe.cn/Article/details/gtngrnvlxi.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.aizwys.cn/Article/details/gtpuqoxtnl.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.meibo888.top/Article/details/gtlwfiymed.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yvedp.cn/Article/details/gtcodusdhm.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.tanke756.top/Article/details/gtcfjtdnlx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhengqikj.top/Article/details/gtbkzecfrl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ehwqpu.com/Article/details/gtuclhjlfo.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yangfankeji.com/Article/details/gtklusnqto.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sweek.top/Article/details/gtuffpnkea.html

[D02] 追加元素到末尾
来源：http://dali.ybcxt.top/Article/details/gtqldjcsvo.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jlsjyb.cn/Article/details/gtcsjietne.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shuidangran.top/Article/details/gtmbbsgbna.html

JS:   arr.push(4);
来源：http://dali.xziqi.cn/Article/details/gtfcvfxsmu.html

TS:   arr.push(4);
来源：http://dali.tianlin.xyz/Article/details/gttdcewpjb.html

Java: list.add(4);
来源：http://dali.vqdsnc.cn/Article/details/gtzvcmpzow.html

Go:   arr = append(arr, 4)
来源：http://dali.ivvv.top/Article/details/gtydhaoqpz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hnqzz.top/Article/details/gtlfbebbcl.html

C#:   list.Add(4);
来源：http://dali.tianlin.xyz/Article/details/gtzddmtwqc.html

[D03] 在指定位置插入元素
来源：http://dali.ybcxt.top/Article/details/gtaumzdhrw.html

Py:   arr.insert(0, 0)
来源：http://dali.cdnleiting.top/Article/details/gtrpilkhtq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yuxming.cn/Article/details/gtbouelrvw.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzqiblqvd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yj20258.top/Article/details/gtrwqtvhrd.html

Java: list.add(0, 0);
来源：http://dali.sweek.top/Article/details/gtyjsaqtpb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ivvv.top/Article/details/gtunsguoii.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gogol.net.cn/Article/details/gtisnmprgz.html

C#:   list.Insert(0, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaatsrmlb.html

[D04] 删除元素
来源：http://dali.kuanghao11.cn/Article/details/gtepvrwyjc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtgyuyrebw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ppjwa.cn/Article/details/gteeonvual.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.daxiang520.top/Article/details/gtooyhauui.html

TS:   arr.splice(0, 1);
来源：http://dali.yangfankeji.com/Article/details/gtvnbnwqpa.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ydzc1.top/Article/details/gthfowoedq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ybcxt.top/Article/details/gtmgiavmbj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.bjfxy.top/Article/details/gthtzqwatv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.birdmap.top/Article/details/gtnsifmjcr.html

[D05] 访问与修改元素
来源：http://dali.pengpengdd.cyou/Article/details/gtxiynrvrw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.meibo888.top/Article/details/gtwjtsbscs.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yueranfly.top/Article/details/gtbwedwlna.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shanyushiyangtech.top/Article/details/gteedcvwan.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jqgufenzy.top/Article/details/gtbnfdfqjn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xylfe.cn/Article/details/gtzirklwqd.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yonumen.top/Article/details/gtcfrsgbun.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xinyue.icu/Article/details/gtlesmumzy.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhengqikj.top/Article/details/gtnzrgrsaf.html

[D06] 数组长度
来源：http://dali.nanxuanxn.top/Article/details/gtqlaikvvb.html

Py:   len(arr)
来源：http://dali.dianchejie.cn/Article/details/gtkzrjnzrl.html

PHP:  count($arr);
来源：http://dali.yj20258.top/Article/details/gtkdxefayb.html

JS:   arr.length
来源：http://dali.shangyingyoupin.top/Article/details/gtjknfeobn.html

TS:   arr.length
来源：http://dali.vqdsnc.cn/Article/details/gtlzwnpooh.html

Java: list.size();
来源：http://dali.zhixingplan.top/Article/details/gtvkfgcjdt.html

Go:   len(arr)
来源：http://dali.birdmap.top/Article/details/gtlrvrrwij.html

Ruby: arr.length; arr.size
来源：http://dali.daxiang520.top/Article/details/gtjgiyccch.html

C#:   list.Count;
来源：http://dali.svipenyu.cn/Article/details/gtsrpsabvm.html

[D07] 切片 / 取子数组
来源：http://dali.316326.xyz/Article/details/gtjgszycne.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.gotoacloud.top/Article/details/gthtdoyjhp.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cashguo.top/Article/details/gtpbchqtqo.html

JS:   arr.slice(1, 4);
来源：http://dali.feifeiyinyue.top/Article/details/gteyvaspeg.html

TS:   arr.slice(1, 4);
来源：http://dali.yueranfly.top/Article/details/gtglrzrkqq.html

Java: list.subList(1, 4);
来源：http://dali.jinqigufen.top/Article/details/gtpcghaugd.html

Go:   arr[1:4]
来源：http://dali.ivvv.top/Article/details/gtafybfpul.html

Ruby: arr[1, 3]
来源：http://dali.xuetiantiany.cn/Article/details/gtrhwdjhay.html

C#:   list.GetRange(1, 3);
来源：http://dali.hfpthk.cn/Article/details/gthoylmhrd.html

[D08] 合并两个数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbgypgyii.html

Py:   a + b;  a.extend(b)
来源：http://dali.fengsongda.top/Article/details/gtghuwsbzm.html

PHP:  array_merge($a, $b);
来源：http://dali.ydzc1.top/Article/details/gtopmzaige.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttctuqqwq.html

TS:   [...a, ...b];
来源：http://dali.fzhhl.top/Article/details/gtdqpqkpdo.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hammf.cn/Article/details/gtryoxfbuf.html

Go:   append(a, b...)
来源：http://dali.vqdsnc.cn/Article/details/gtmawzfpxl.html

Ruby: a + b;  a.concat(b)
来源：http://dali.bjfxy.top/Article/details/gtrzlpraub.html

C#:   a.Concat(b).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtsnqxsvrh.html

[D09] 排序（升序）
来源：http://dali.yangfankeji.com/Article/details/gtacdnthku.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yueranfly.top/Article/details/gtvnrxxfmf.html

PHP:  sort($arr);
来源：http://dali.yj20258888.top/Article/details/gtznozusty.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cdnleiting.top/Article/details/gtiihhexgf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jqgfzy.top/Article/details/gtmbakyili.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.tianlin.xyz/Article/details/gtgbnicppd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yj20258888.top/Article/details/gtmtyaicgt.html

Ruby: arr.sort
来源：http://dali.hongshengwenyu.top/Article/details/gtwtysrlaw.html

C#:   list.Sort();
来源：http://dali.dashuyun.cn/Article/details/gtpmnxvahl.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jyoumei.cn/Article/details/gtkgvcryxg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.daria6918.cn/Article/details/gtwtsnxefz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj202588.top/Article/details/gtvswcxwjo.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gogol.net.cn/Article/details/gtlfzqubpj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nanxinkj.top/Article/details/gtwhsdzkto.html


<!-- 参考信息 -->