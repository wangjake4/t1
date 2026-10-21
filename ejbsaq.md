代发 wailian999

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.pengpengdd.cyou/Article/details/gtriewwuks.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.nanxinkj.top/Article/details/gtxrxvsxlv.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.iojbl.cn/Article/details/gtmuyjipaw.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shuidangran.top/Article/details/gtajjtlxkm.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hnxiangtu.top/Article/details/gtzyxrxgxn.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.9152youxi.cn/Article/details/gtuhkewbme.html

[B11] 生成数字序列 / 区间
来源：http://dali.redwolf501.top/Article/details/gthpsureoa.html

Py:   list(range(0, 10, 2))
来源：http://dali.pycfn.com/Article/details/gttxowxnub.html

PHP:  range(0, 10, 2);
来源：http://dali.nanxinkj.top/Article/details/gtyosrlcyc.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj20258888.top/Article/details/gtisjjqhjn.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yanxiufei.cn/Article/details/gtqvvthref.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.nwbrower.top/Article/details/gtcrbghewn.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yuanzhike.top/Article/details/gtfegeerca.html

Ruby: (0...10).step(2).to_a
来源：http://dali.wangdashe.top/Article/details/gtjchkymfc.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.daxiang520.top/Article/details/gtcgmejrnm.html

[B12] 跳出多层循环
来源：http://dali.chenzaomai.com/Article/details/gtgzegqyhc.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cucudq.cn/Article/details/gtjddajrjb.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jyoumei.cn/Article/details/gtcfofrdvz.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yanxiufei.cn/Article/details/gtttgvejgt.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gogol.net.cn/Article/details/gtinmihrdq.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.sweek.top/Article/details/gtstgtfkof.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.tanke756.top/Article/details/gtevrxknmh.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xuanzx.com/Article/details/gtaqaaasli.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.haohaochexian.top/Article/details/gtymsaqljr.html

[B13] 判断是否为数字
来源：http://dali.ehwqpu.com/Article/details/gtjafzxsyn.html

Py:   isinstance(x, (int, float))
来源：http://dali.ehwqpu.com/Article/details/gteijiaxep.html

PHP:  is_numeric($x)
来源：http://dali.ybcxt.top/Article/details/gtdnvjkebj.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtpgkuetul.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlihqyqif.html

Java: x instanceof Number
来源：http://dali.jinqigfzy.top/Article/details/gtjkuasesx.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hammf.cn/Article/details/gtnhaqvezu.html

Ruby: x.is_a?(Numeric)
来源：http://dali.svipenyu.cn/Article/details/gttgcjiswd.html

C#:   x is int or double or decimal
来源：http://dali.vqdsnc.cn/Article/details/gtsqrzjodc.html

[B14] 判断值是否在集合内
来源：http://dali.havefunace.top/Article/details/gtarvukzlu.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shangyingyoupin.top/Article/details/gteapkoinc.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.ybcxt.top/Article/details/gtsmkktieo.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.9152youxi.cn/Article/details/gtxapbihkj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhoulong.xyz/Article/details/gtyqejyhsl.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.kuanghao11.cn/Article/details/gtjkglayfn.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.fengsongda.top/Article/details/gtjlikikxh.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.fzhhl.top/Article/details/gtstmcqqtx.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hywenlv.cn/Article/details/gtpqxsmshm.html

[B15] 布尔运算与取反
来源：http://dali.xuetiantiany.cn/Article/details/gtdjqqsnsz.html

Py:   a and b or not c
来源：http://dali.jiagoushi.top/Article/details/gtasbtkykf.html

PHP:  $a && $b || !$c
来源：http://dali.yanxiufei.cn/Article/details/gtvkevnboy.html

JS:   a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gtzpulninb.html

TS:   a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gtpvldpohj.html

Java: a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gtrsujbvgk.html

Go:   a && b || !c
来源：http://dali.sysykeji.top/Article/details/gtkxwmamul.html

Ruby: a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gtrjhvfpqf.html

C#:   a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gtznhvbfhj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jianghu66.top/Article/details/gtpktvghqv.html

Py:   if not data: return
来源：http://dali.mhx1999.top/Article/details/gtqoabzhof.html

PHP:  if (!$data) { return; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbvkafnuj.html

JS:   if (!data) return;
来源：http://dali.hfpthk.cn/Article/details/gtuuusuksd.html

TS:   if (!data) return;
来源：http://dali.nanxinkj.top/Article/details/gtmtnszaxe.html

Java: if (data == null) return;
来源：http://dali.havefunace.top/Article/details/gtegoqkusn.html

Go:   if data == nil { return }
来源：http://dali.sweek.top/Article/details/gtdnwhiney.html

Ruby: return if data.nil?
来源：http://dali.xuanzx.com/Article/details/gtaqsapksq.html

C#:   if (data == null) return;
来源：http://dali.cucudq.cn/Article/details/gtmwlakyqq.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtmftblksa.html

C. 函数与作用域
来源：http://dali.tanke756.top/Article/details/gtegsfuktx.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtenuaaqsq.html

[C01] 定义函数
来源：http://dali.smart0.xyz/Article/details/gtqwvpxlwf.html

Py:   def add(a, b): return a + b
来源：http://dali.daxiang520.top/Article/details/gtluxftjne.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.316326.xyz/Article/details/gtsqxsqjpy.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gtoszvvhzj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gthpmjflme.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtwsywnkdh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.chenzaomai.com/Article/details/gtltpundqi.html

Ruby: def add(a, b); a + b; end
来源：http://dali.sufxvd.cn/Article/details/gtonsyheav.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gtdzpykafj.html

[C02] 默认参数
来源：http://dali.xylfe.cn/Article/details/gtuaoxubrf.html

Py:   def greet(name="World"): return name
来源：http://dali.jinqigfzy.top/Article/details/gtcggrwuol.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.dashuyun.cn/Article/details/gthdddhqgh.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.dashuyun.cn/Article/details/gtictpzsne.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.aibaodan.cn/Article/details/gtulowdnqu.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.tanke756.top/Article/details/gtfjvkzcbj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.feifeiyinyue.top/Article/details/gtjzmnynlx.html

Ruby: def greet(name = "World") = name
来源：http://dali.birdmap.top/Article/details/gtupefsnde.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.fengsongda.top/Article/details/gtaqdqzkgb.html

[C03] 可变参数
来源：http://dali.birdmap.top/Article/details/gtybufsttt.html

Py:   def total(*args): return sum(args)
来源：http://dali.hywenlv.cn/Article/details/gtzltdbupn.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.sweek.top/Article/details/gtfnelyqie.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xuanzx.com/Article/details/gtnstyodgu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.pengpengdd.cyou/Article/details/gtopzcglse.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jqgfzy.top/Article/details/gtzvapvuel.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ivvv.top/Article/details/gtlvoqipbw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.tanke756.top/Article/details/gtszwerqhf.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhiwuduotai.top/Article/details/gtqffkhxkn.html

[C04] 命名参数 / 关键字参数
来源：http://dali.chenlongwang.top/Article/details/gtcgkafzpe.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yvedp.cn/Article/details/gtsuyxoxsf.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yj202588.top/Article/details/gthfgmtxnx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlbhpiwxt.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.nanxuanxn.top/Article/details/gtttvxifgl.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hywenlv.cn/Article/details/gtihlagdmf.html

Go:   // 无：用配置结构体参数
来源：http://dali.hnqzz.top/Article/details/gtnzokmlqk.html

Ruby: f(a: 1, b: 2)
来源：http://dali.tanke756.top/Article/details/gtookqbegu.html

C#:   f(a: 1, b: 2)
来源：http://dali.hammf.cn/Article/details/gtdkogfoyj.html

[C05] 返回多个值
来源：http://dali.snrcjt.cn/Article/details/gttwrpjzbk.html

Py:   return a, b
来源：http://dali.yuanzhike.top/Article/details/gteflomkyw.html

PHP:  return [$a, $b];
来源：http://dali.hammf.cn/Article/details/gtrjigyiid.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.vqdsnc.cn/Article/details/gtqymliijj.html

TS:   return { a, b };
来源：http://dali.guowangkeji.top/Article/details/gtaifmqqou.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.tian-w.cn/Article/details/gtbwnwobdp.html

Go:   return a, b
来源：http://dali.daria6918.cn/Article/details/gtuhvijisy.html

Ruby: return a, b
来源：http://dali.jiagoushi.top/Article/details/gtebfdpitm.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.gotoacloud.top/Article/details/gtgxjfyksb.html

[C06] 匿名函数 / lambda
来源：http://dali.bjfxy.top/Article/details/gtejtvmuch.html

Py:   square = lambda x: x * x
来源：http://dali.bjfxy.top/Article/details/gtfdszvlfh.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xuanzx.com/Article/details/gtspoqujkx.html

JS:   const square = x => x * x;
来源：http://dali.jlsjyb.cn/Article/details/gtptseppku.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.daria6918.cn/Article/details/gtucnumnjp.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.sweek.top/Article/details/gtjxznmrbg.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sxryk.cn/Article/details/gtvenrbmpd.html

Ruby: square = ->(x) { x * x }
来源：http://dali.gogol.net.cn/Article/details/gtbmkenkhz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.pengpengdd.cyou/Article/details/gtylkvcrfo.html

[C07] 把函数作为参数传入
来源：http://dali.yvedp.cn/Article/details/gthfrpphio.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hysaishi.cn/Article/details/gtmxbecrww.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.tanke756.top/Article/details/gtzuqhkxef.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.quarkkingdee.top/Article/details/gtpdcfqujv.html

TS:   arr.map(String)
来源：http://dali.c1oappe.top/Article/details/gtirbmmbba.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtfyfwojdn.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.aizwys.cn/Article/details/gtrpmgwluu.html

Ruby: arr.map(&:upcase)
来源：http://dali.316326.xyz/Article/details/gtsgqpkpqd.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.quarkkingdee.top/Article/details/gtecphdlge.html

[C08] 闭包
来源：http://dali.redwolf501.top/Article/details/gtjrcjpuce.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.gotoacloud.top/Article/details/gtkfefdbnd.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yvedp.cn/Article/details/gtqquoujky.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jiagoushi.top/Article/details/gtlatdpyho.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cdnleiting.top/Article/details/gtvsxwzjdf.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.vqdsnc.cn/Article/details/gtvpgxlieh.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.dashuyun.cn/Article/details/gtfqpavuww.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cashguo.top/Article/details/gtlfqgdrcp.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.chenlongwang.top/Article/details/gtvrnsmmgx.html

[C09] 递归
来源：http://dali.jiagoushi.top/Article/details/gtvhgcnmms.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.havefunace.top/Article/details/gttyogyqsg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.sweek.top/Article/details/gtcupcyqrs.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yonumen.top/Article/details/gtznbxcjwc.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.snrcjt.cn/Article/details/gtcecueiyc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xuetiantiany.cn/Article/details/gtlyfrcvpx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.daxiang520.top/Article/details/gthvxetpxc.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jqgufenzy.top/Article/details/gtvebghbal.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ivvv.top/Article/details/gtryanpqna.html

[C10] 变量作用域
来源：http://dali.jiagoushi.top/Article/details/gttkddhfgx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.fengsongda.top/Article/details/gtdcnfxwbm.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.haohaochexian.top/Article/details/gtgswnffis.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.tian-w.cn/Article/details/gtpqawwefv.html

TS:   同 JS
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoaldzfqx.html

Java: 方法内为块级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwksnxukx.html

Go:   花括号块级作用域
来源：http://dali.yongpay.top/Article/details/gtrtfmezak.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.sxryk.cn/Article/details/gttwbhcuch.html

C#:   块级作用域
来源：http://dali.yangfankeji.com/Article/details/gtrtyysvlq.html

[C11] 模块导入与导出
来源：http://dali.daxiang520.top/Article/details/gtylbohbeu.html

Py:   from module import func
来源：http://dali.ydzc1.top/Article/details/gtaeyagbdm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.feifeiyinyue.top/Article/details/gtsacrfgia.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhoulong.xyz/Article/details/gtwezajjos.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.dashuyun.cn/Article/details/gttamsdsrn.html

Java: import java.util.List;
来源：http://dali.sxryk.cn/Article/details/gtstxjdrsl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jqgufenzy.top/Article/details/gtiptianbt.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.nwbrower.top/Article/details/gtxgrercvg.html

C#:   using System.Text;
来源：http://dali.fzhhl.top/Article/details/gteejgvkmo.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfqjyeinj.html

Py:   (lambda: print("run"))()
来源：http://dali.c1oappe.top/Article/details/gtqghedxmo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.aibaodan.cn/Article/details/gtbpekqktz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.dashuyun.cn/Article/details/gtyrzotojb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yj20258.top/Article/details/gtzooyqqjo.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.redwolf501.top/Article/details/gtsotkkbco.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yuxming.cn/Article/details/gtvpjsyvqp.html

Ruby: -> { puts "run" }.call
来源：http://dali.daxiang520.top/Article/details/gtjvronopo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.mhx1999.top/Article/details/gtakhsgrqt.html

[C13] 类型声明 / 类型注解
来源：http://dali.yonumen.top/Article/details/gtnrsbokgc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.quarkkingdee.top/Article/details/gtntksgqgz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.kuanghao11.cn/Article/details/gtjymmjlgd.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhongyouzk.top/Article/details/gtvtpnswlb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gtaepuqncm.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gtzeljiufg.html

Go:   func add(a, b int) int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlhvlrmsp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhengqikj.top/Article/details/gtjbknxnws.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hnqzz.top/Article/details/gtpqueydfk.html

[C14] 泛型函数
来源：http://dali.hammf.cn/Article/details/gtxbzhpemu.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.guowangkeji.top/Article/details/gtjiqeloxc.html

PHP:  // 无泛型
来源：http://dali.yj20258888.top/Article/details/gtvoksccmz.html

JS:   // 无泛型
来源：http://dali.shzxlz.cn/Article/details/gtwputczqq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtwzxtwoxi.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gzhubu.top/Article/details/gthajawcgg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzjsbcnqq.html

Ruby: # 无泛型
来源：http://dali.yj20258888.top/Article/details/gtqrlccnpj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.sweek.top/Article/details/gtemncclge.html

[C15] 解构 / 展开参数
来源：http://dali.jianghu66.top/Article/details/gtbxyjciuz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yanxiufei.cn/Article/details/gtkqrjtioi.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jianghu66.top/Article/details/gtrpcgdmse.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gotoacloud.top/Article/details/gtexkvfaxr.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.tianlin.xyz/Article/details/gtkyclidif.html

Java: // 无解构
来源：http://dali.gzhubu.top/Article/details/gtwnudzqsl.html

Go:   // 无解构
来源：http://dali.9152youxi.cn/Article/details/gtvfnozrsa.html

Ruby: a, b = pair
来源：http://dali.fengsongda.top/Article/details/gtonxuxcxk.html

C#:   var (a, b) = pair;
来源：http://dali.zhoulong.xyz/Article/details/gtsqwvwkua.html

[C16] 函数 / 方法重载
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxwxuhkml.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shangyingyoupin.top/Article/details/gtmpnlkeuw.html

PHP:  // 无重载
来源：http://dali.haohaochexian.top/Article/details/gtwjiuwiid.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.sysykeji.top/Article/details/gtnzpujeny.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.daxiang520.top/Article/details/gtcggeqvkn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ppjwa.cn/Article/details/gtqppvzqwv.html

Go:   // 无重载：用不同函数名
来源：http://dali.yangfankeji.com/Article/details/gtdxdscxkj.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhengqikj.top/Article/details/gtttyjksqi.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yuxming.cn/Article/details/gtaajqwkmm.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtwuzhlgzh.html

D. 数组 / 列表 / 集合
来源：http://dali.jinqigfzy.top/Article/details/gtfecdofcc.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtveziodqj.html

[D01] 创建数组 / 列表
来源：http://dali.cqqwz.cn/Article/details/gtocseebxe.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sufxvd.cn/Article/details/gtjazvmpzh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yangfankeji.com/Article/details/gtgdnknlon.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hywenlv.cn/Article/details/gtagljvlrm.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yueranfly.top/Article/details/gtsyqwgvis.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.redwolf501.top/Article/details/gtjqbqalmz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.svipenyu.cn/Article/details/gtpugihtic.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zdqjudy.top/Article/details/gtvnthvbul.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yanxiufei.cn/Article/details/gtvhqxaxtb.html

[D02] 追加元素到末尾
来源：http://dali.guannengcc.top/Article/details/gtihpcyemq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zdqjudy.top/Article/details/gtzspefvnu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.nanxinkj.top/Article/details/gtrfyvemtk.html

JS:   arr.push(4);
来源：http://dali.jlsjyb.cn/Article/details/gtxdgszkzj.html

TS:   arr.push(4);
来源：http://dali.vqdsnc.cn/Article/details/gtakfrsskg.html

Java: list.add(4);
来源：http://dali.ybcxt.top/Article/details/gtazdqprkh.html

Go:   arr = append(arr, 4)
来源：http://dali.fengsongda.top/Article/details/gtkgjfadiu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.tianlin.xyz/Article/details/gtbkzemkne.html

C#:   list.Add(4);
来源：http://dali.gzhubu.top/Article/details/gtzrievupv.html

[D03] 在指定位置插入元素
来源：http://dali.sweek.top/Article/details/gtuxdgfvpi.html

Py:   arr.insert(0, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtrpjsoqqm.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.nwbrower.top/Article/details/gtxnfnonfv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.pycfn.com/Article/details/gtzeuhylbn.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gtgftsvtqp.html

Java: list.add(0, 0);
来源：http://dali.gzhubu.top/Article/details/gtpyxumrsp.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.smart0.xyz/Article/details/gtlgeublrv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenlongwang.top/Article/details/gtjmfwaxhj.html

C#:   list.Insert(0, 0);
来源：http://dali.hysaishi.cn/Article/details/gtllcjgxfc.html

[D04] 删除元素
来源：http://dali.jqgfzy.top/Article/details/gtiaeltqva.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhengqikj.top/Article/details/gtgpilksmk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcutwfxnv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xylfe.cn/Article/details/gtigbbdhsg.html

TS:   arr.splice(0, 1);
来源：http://dali.zhongyouzk.top/Article/details/gthkrqcxmd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.316326.xyz/Article/details/gtmbdkmudj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtujycetta.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinqigfzy.top/Article/details/gtgkwyrwsv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.guannengcc.top/Article/details/gtwihsziua.html

[D05] 访问与修改元素
来源：http://dali.tian-w.cn/Article/details/gtvnfrspbb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.fzhhl.top/Article/details/gtziaimukd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.dashuyun.cn/Article/details/gtbnrkrrcc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhoulong.xyz/Article/details/gtmascwnhq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cashguo.top/Article/details/gtzuldlfmc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.wangdashe.top/Article/details/gtoddynmfq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shuidangran.top/Article/details/gtiumkfqpd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258.top/Article/details/gtmugukxrf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gtjewaxcbf.html

[D06] 数组长度
来源：http://dali.dashuyun.cn/Article/details/gtpfzubntx.html

Py:   len(arr)
来源：http://dali.xuanzx.com/Article/details/gtwuwhitpf.html

PHP:  count($arr);
来源：http://dali.yuxming.cn/Article/details/gtjoklfeou.html

JS:   arr.length
来源：http://dali.hongshengwenyu.top/Article/details/gtpyidofip.html

TS:   arr.length
来源：http://dali.cashguo.top/Article/details/gtpqkqhrgo.html

Java: list.size();
来源：http://dali.redwolf501.top/Article/details/gtsajdunit.html

Go:   len(arr)
来源：http://dali.nanxinkj.top/Article/details/gtsvzwwyfu.html

Ruby: arr.length; arr.size
来源：http://dali.dianchejie.cn/Article/details/gtuqgbvwwp.html

C#:   list.Count;
来源：http://dali.aibaodan.cn/Article/details/gtftudxxxt.html

[D07] 切片 / 取子数组
来源：http://dali.havefunace.top/Article/details/gtbwtrrvxi.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.aizwys.cn/Article/details/gtyjrefivl.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhoulong.xyz/Article/details/gthxuofoag.html

JS:   arr.slice(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gttsrwtjkf.html

TS:   arr.slice(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gtzespidjn.html

Java: list.subList(1, 4);
来源：http://dali.tanke756.top/Article/details/gtxqviztnk.html

Go:   arr[1:4]
来源：http://dali.jinqigfzy.top/Article/details/gtaumftsdy.html

Ruby: arr[1, 3]
来源：http://dali.andypj.xyz/Article/details/gtkibpbign.html

C#:   list.GetRange(1, 3);
来源：http://dali.dashuyun.cn/Article/details/gtdfzrnqxq.html

[D08] 合并两个数组
来源：http://dali.cucudq.cn/Article/details/gtgsaahsxw.html

Py:   a + b;  a.extend(b)
来源：http://dali.snrcjt.cn/Article/details/gtivtarjeb.html

PHP:  array_merge($a, $b);
来源：http://dali.fengsongda.top/Article/details/gtfrhtabfc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.fzhhl.top/Article/details/gtclodrxnw.html

TS:   [...a, ...b];
来源：http://dali.yuxming.cn/Article/details/gtkixpobfb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.pycfn.com/Article/details/gtwopbasgl.html

Go:   append(a, b...)
来源：http://dali.zhiwuduotai.top/Article/details/gtluwfiyqi.html

Ruby: a + b;  a.concat(b)
来源：http://dali.havefunace.top/Article/details/gtinrfiktp.html

C#:   a.Concat(b).ToList()
来源：http://dali.chenlongwang.top/Article/details/gtddmwvjpb.html

[D09] 排序（升序）
来源：http://dali.yj20258888.top/Article/details/gtstpjadsy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.havefunace.top/Article/details/gtcmbxhbwq.html

PHP:  sort($arr);
来源：http://dali.chenlongwang.top/Article/details/gtduiykjkb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.guowangkeji.top/Article/details/gtvcyrfnfv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yj20258.top/Article/details/gtgdnlflij.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.tanke756.top/Article/details/gtfzxrwvgn.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.iojbl.cn/Article/details/gturptbvck.html

Ruby: arr.sort
来源：http://dali.guannengcc.top/Article/details/gtjqnmyldn.html

C#:   list.Sort();
来源：http://dali.ehwqpu.com/Article/details/gtkfneplwh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jqgfzy.top/Article/details/gtdfiqoyac.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jyoumei.cn/Article/details/gtrcipkoyf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.meibo888.top/Article/details/gtudfalejk.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnxiangtu.top/Article/details/gttuwjbubx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.quarkkingdee.top/Article/details/gtxadrcxvf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jiagoushi.top/Article/details/gtygmhjtyv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.guannengcc.top/Article/details/gtvtakeedc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.316326.xyz/Article/details/gtzogdglqa.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.bjfxy.top/Article/details/gtgyshhyxo.html


<!-- 参考信息 -->