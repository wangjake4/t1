代发 wailian999

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.xuetiantiany.cn/Article/details/gtkspfajwo.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.pycfn.com/Article/details/gthkllsueh.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yonumen.top/Article/details/gtfrjkpuxs.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ybcxt.top/Article/details/gtkchtioqc.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jianghu66.top/Article/details/gtrpwuvwts.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.guannengcc.top/Article/details/gtltfymamy.html

[B11] 生成数字序列 / 区间
来源：http://dali.jinqigfzy.top/Article/details/gtajkfoirb.html

Py:   list(range(0, 10, 2))
来源：http://dali.havefunace.top/Article/details/gtnfkdowhx.html

PHP:  range(0, 10, 2);
来源：http://dali.xziqi.cn/Article/details/gtxiqbphqj.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.havefunace.top/Article/details/gtgycotxnp.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cashguo.top/Article/details/gtbcrwsofn.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jinqigfzy.top/Article/details/gtynsopfzx.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhixingplan.top/Article/details/gtumcwoajh.html

Ruby: (0...10).step(2).to_a
来源：http://dali.meibo888.top/Article/details/gtlvyoxjtc.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.cqqwz.cn/Article/details/gthoakqhyp.html

[B12] 跳出多层循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtnuhlnjxv.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.gzhubu.top/Article/details/gtudglwlkw.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yangfankeji.com/Article/details/gtxlqgpvkh.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shzxlz.cn/Article/details/gtiwmioylo.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfrftvbty.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.aizwys.cn/Article/details/gtoyaxgwpf.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.wangshuangyany.cn/Article/details/gtdspvkagg.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jinghuilouyu.cn/Article/details/gtwybkfmpd.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hammf.cn/Article/details/gtptmaeygr.html

[B13] 判断是否为数字
来源：http://dali.shanyushiyangkeji.top/Article/details/gtajalohjo.html

Py:   isinstance(x, (int, float))
来源：http://dali.gogol.net.cn/Article/details/gtacfmzmuu.html

PHP:  is_numeric($x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnfvydfes.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ydzc1.top/Article/details/gtmqblizfm.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhiwuduotai.top/Article/details/gthktrsjmi.html

Java: x instanceof Number
来源：http://dali.kuanghao11.cn/Article/details/gtkaljrdnl.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.quarkkingdee.top/Article/details/gtovzhcijk.html

Ruby: x.is_a?(Numeric)
来源：http://dali.c1oappe.top/Article/details/gtwspfvwou.html

C#:   x is int or double or decimal
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlaousyif.html

[B14] 判断值是否在集合内
来源：http://dali.zhiwuduotai.top/Article/details/gtjxeikiqn.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.nanxuanxn.top/Article/details/gtjwgaczyr.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.meibo888.top/Article/details/gtzxekaoes.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtltdyhxle.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jyoumei.cn/Article/details/gtoohzjnrw.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yj20258888.top/Article/details/gtwjdsaudu.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfixqlmsf.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ivvv.top/Article/details/gtsxsplnge.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yj202588.top/Article/details/gtrjbxahlz.html

[B15] 布尔运算与取反
来源：http://dali.yangfankeji.com/Article/details/gtrkpmomst.html

Py:   a and b or not c
来源：http://dali.tian-w.cn/Article/details/gtyebortle.html

PHP:  $a && $b || !$c
来源：http://dali.tianlin.xyz/Article/details/gthfpirykq.html

JS:   a && b || !c
来源：http://dali.zycfv.cn/Article/details/gtslwovixt.html

TS:   a && b || !c
来源：http://dali.birdmap.top/Article/details/gtwavyjrac.html

Java: a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqkhemqyn.html

Go:   a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxffcjxcl.html

Ruby: a && b || !c
来源：http://dali.zycfv.cn/Article/details/gtphfqfgki.html

C#:   a && b || !c
来源：http://dali.havefunace.top/Article/details/gtpqsouubm.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hywenlv.cn/Article/details/gtmimmsrym.html

Py:   if not data: return
来源：http://dali.daxiang520.top/Article/details/gtvkitdhjh.html

PHP:  if (!$data) { return; }
来源：http://dali.zhoulong.xyz/Article/details/gtowswjhbq.html

JS:   if (!data) return;
来源：http://dali.ehwqpu.com/Article/details/gtpetmohoc.html

TS:   if (!data) return;
来源：http://dali.birdmap.top/Article/details/gtjczpgfrh.html

Java: if (data == null) return;
来源：http://dali.wangdashe.top/Article/details/gtepjzjmvw.html

Go:   if data == nil { return }
来源：http://dali.tanke756.top/Article/details/gtmlltyxwl.html

Ruby: return if data.nil?
来源：http://dali.chenlongwang.top/Article/details/gtnmpbgqej.html

C#:   if (data == null) return;
来源：http://dali.gotoacloud.top/Article/details/gtbinnmjdp.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtujbndfxs.html

C. 函数与作用域
来源：http://dali.yj202588.top/Article/details/gtbptzwvjp.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfuiwtfuw.html

[C01] 定义函数
来源：http://dali.wangdashe.top/Article/details/gtfjncnipk.html

Py:   def add(a, b): return a + b
来源：http://dali.bjfxy.top/Article/details/gtksjmskxd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gtevabxblg.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtruheedul.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gtsymedalu.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gtudfhhxto.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yuanzhike.top/Article/details/gtveyptajz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.gzhubu.top/Article/details/gtvwwbrvrj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtucjrucfd.html

[C02] 默认参数
来源：http://dali.sufxvd.cn/Article/details/gteasidsgm.html

Py:   def greet(name="World"): return name
来源：http://dali.cqqwz.cn/Article/details/gtjqgobzxs.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtfoffujbl.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.dianchejie.cn/Article/details/gthbxjkadz.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.fzhhl.top/Article/details/gtiiqpslcb.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yanxiufei.cn/Article/details/gtzjimjixw.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hysaishi.cn/Article/details/gtwaspiqvm.html

Ruby: def greet(name = "World") = name
来源：http://dali.fzhhl.top/Article/details/gtbksrimqk.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.wangdashe.top/Article/details/gtnpyaejlr.html

[C03] 可变参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsmceqkkz.html

Py:   def total(*args): return sum(args)
来源：http://dali.sufxvd.cn/Article/details/gttgnqgwox.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.daxiang520.top/Article/details/gtdhgknvwp.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tanke756.top/Article/details/gtpxasnlbq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258.top/Article/details/gtxhgbyroy.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jlsjyb.cn/Article/details/gthtlnbtlv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.vqdsnc.cn/Article/details/gtkltwtdcy.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.mhx1999.top/Article/details/gtxwcdhmdo.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.daria6918.cn/Article/details/gthedneoyq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkpyxsibh.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.quarkkingdee.top/Article/details/gtddoffbxx.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xinyue.icu/Article/details/gtoptsdasd.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.sweek.top/Article/details/gtlcsdwixc.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hnxiangtu.top/Article/details/gtytucqtck.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hnqzz.top/Article/details/gtvytpdybc.html

Go:   // 无：用配置结构体参数
来源：http://dali.wangdashe.top/Article/details/gtyodejbbs.html

Ruby: f(a: 1, b: 2)
来源：http://dali.nwbrower.top/Article/details/gtyokksbkw.html

C#:   f(a: 1, b: 2)
来源：http://dali.yj202588.top/Article/details/gtbchwtvip.html

[C05] 返回多个值
来源：http://dali.zhengqikj.top/Article/details/gtzgaubdod.html

Py:   return a, b
来源：http://dali.yongpay.top/Article/details/gtqyrcvgkh.html

PHP:  return [$a, $b];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwgrbgifi.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhiwuduotai.top/Article/details/gtcxxmfmnz.html

TS:   return { a, b };
来源：http://dali.yongpay.top/Article/details/gtrlkjksgg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sweek.top/Article/details/gtuiqthtou.html

Go:   return a, b
来源：http://dali.sufxvd.cn/Article/details/gtaogiwwdv.html

Ruby: return a, b
来源：http://dali.smart0.xyz/Article/details/gtgfqnhysa.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shangyingyoupin.top/Article/details/gtveeboftw.html

[C06] 匿名函数 / lambda
来源：http://dali.fengsongda.top/Article/details/gtgermxgvu.html

Py:   square = lambda x: x * x
来源：http://dali.hnxiangtu.top/Article/details/gtidywegza.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hongshengwenyu.top/Article/details/gtpyamimbg.html

JS:   const square = x => x * x;
来源：http://dali.shanyushiyangtech.top/Article/details/gtlqkunvml.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.kuanghao11.cn/Article/details/gtrdnnzwjo.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.dashuyun.cn/Article/details/gtetyythyo.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yuanzhike.top/Article/details/gtytqktsts.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yongpay.top/Article/details/gtjcharrfk.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hfpthk.cn/Article/details/gtfqlkbijq.html

[C07] 把函数作为参数传入
来源：http://dali.gzhubu.top/Article/details/gtgxivbxna.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cdnleiting.top/Article/details/gtozqjeawo.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sysykeji.top/Article/details/gtizmrrnzc.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.sxryk.cn/Article/details/gtgywhokyi.html

TS:   arr.map(String)
来源：http://dali.sysykeji.top/Article/details/gtgdkquavz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtykqxmnlc.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cashguo.top/Article/details/gtkmqxlkbw.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinqigfzy.top/Article/details/gtfstvqtnn.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xziqi.cn/Article/details/gteconjovm.html

[C08] 闭包
来源：http://dali.aizwys.cn/Article/details/gtkyyutdmo.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cqqwz.cn/Article/details/gtnswmlrlh.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hongshengwenyu.top/Article/details/gtdwhakyca.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shzxlz.cn/Article/details/gtzcbenmau.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jqgfzy.top/Article/details/gtndkkesfo.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.feifeiyinyue.top/Article/details/gtpbcdxckc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.smart0.xyz/Article/details/gtqnaqiyxq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.vqdsnc.cn/Article/details/gtqbkbjmhi.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zdqjudy.top/Article/details/gtrgcijuuj.html

[C09] 递归
来源：http://dali.yongpay.top/Article/details/gtxghxpfmb.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhongyouzk.top/Article/details/gtzvewngwa.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.wangdashe.top/Article/details/gtrxvcmqti.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.pycfn.com/Article/details/gtymkrtqlw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.wangshuangyany.cn/Article/details/gtkdqofejv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhongyouzk.top/Article/details/gtpyvdscwx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhengqikj.top/Article/details/gtibujpfqr.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jinqigfzy.top/Article/details/gtxpoloesc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xziqi.cn/Article/details/gtxrrdkibs.html

[C10] 变量作用域
来源：http://dali.hongshengwenyu.top/Article/details/gtxlsreoej.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yanxiufei.cn/Article/details/gtzjqdvhmf.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhengqikj.top/Article/details/gtjzztdaxv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.chenlongwang.top/Article/details/gtvkiitdwb.html

TS:   同 JS
来源：http://dali.zhengqikj.top/Article/details/gtcubynowh.html

Java: 方法内为块级作用域
来源：http://dali.shangyingyoupin.top/Article/details/gttoobinzm.html

Go:   花括号块级作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbqonhcks.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.svipenyu.cn/Article/details/gtfpycevqp.html

C#:   块级作用域
来源：http://dali.mhx1999.top/Article/details/gtiwduqtnh.html

[C11] 模块导入与导出
来源：http://dali.vqdsnc.cn/Article/details/gthetlhejs.html

Py:   from module import func
来源：http://dali.redwolf501.top/Article/details/gtwuteyeij.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hnxiangtu.top/Article/details/gtvnhhikao.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xinyue.icu/Article/details/gtlawoqnul.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jianghu66.top/Article/details/gtedhameli.html

Java: import java.util.List;
来源：http://dali.hongshengwenyu.top/Article/details/gtqufcfwcx.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xuanzx.com/Article/details/gtuwyvrufq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cqqwz.cn/Article/details/gtuwsnvbfe.html

C#:   using System.Text;
来源：http://dali.yuxming.cn/Article/details/gtbahcqzsl.html

[C12] 立即执行函数 IIFE
来源：http://dali.zdqjudy.top/Article/details/gtocuzlfvh.html

Py:   (lambda: print("run"))()
来源：http://dali.hywenlv.cn/Article/details/gtsqjfzvqn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.gaohongyu789.top/Article/details/gtzifklkve.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shzxlz.cn/Article/details/gtoftkkiia.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hywenlv.cn/Article/details/gtgdaryeia.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cheryme.top/Article/details/gtvcdbmewx.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.fzhhl.top/Article/details/gtbpoenwjt.html

Ruby: -> { puts "run" }.call
来源：http://dali.yj202588.top/Article/details/gtbfgnlafk.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hongshengwenyu.top/Article/details/gtyoltdppc.html

[C13] 类型声明 / 类型注解
来源：http://dali.fengsongda.top/Article/details/gtspwfwmpw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sufxvd.cn/Article/details/gtaxnbpank.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jlsjyb.cn/Article/details/gtgzuebgdr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sufxvd.cn/Article/details/gtcwtmxvnt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gthykbzuog.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtjremfrwh.html

Go:   func add(a, b int) int
来源：http://dali.shuidangran.top/Article/details/gtfpyklwzs.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zycfv.cn/Article/details/gtzqqkxpui.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yueranfly.top/Article/details/gtpgjinfnq.html

[C14] 泛型函数
来源：http://dali.hammf.cn/Article/details/gtghyrzbsc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.gzhubu.top/Article/details/gtpuxqrcax.html

PHP:  // 无泛型
来源：http://dali.jqgfzy.top/Article/details/gtahbieunw.html

JS:   // 无泛型
来源：http://dali.zhiwuduotai.top/Article/details/gtnwtkuctw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gthsoqrgio.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.haohaochexian.top/Article/details/gtpcwoaoau.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hnxiangtu.top/Article/details/gttmhnxaye.html

Ruby: # 无泛型
来源：http://dali.ehwqpu.com/Article/details/gtlxpqvivz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hfpthk.cn/Article/details/gtgmdqnuuv.html

[C15] 解构 / 展开参数
来源：http://dali.xuetiantiany.cn/Article/details/gtcihzwwck.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hongshengwenyu.top/Article/details/gtxrersaux.html

PHP:  [$a, $b] = $pair;
来源：http://dali.iojbl.cn/Article/details/gtnkzjpiuw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gzhubu.top/Article/details/gtoarpmvma.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.snrcjt.cn/Article/details/gtuwvhspcw.html

Java: // 无解构
来源：http://dali.ppjwa.cn/Article/details/gtcpqlztoj.html

Go:   // 无解构
来源：http://dali.yuxming.cn/Article/details/gtirxukelv.html

Ruby: a, b = pair
来源：http://dali.jianghu66.top/Article/details/gtbpvodjxb.html

C#:   var (a, b) = pair;
来源：http://dali.sysykeji.top/Article/details/gtuhxkpaau.html

[C16] 函数 / 方法重载
来源：http://dali.sufxvd.cn/Article/details/gtwlgqulcl.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.vqdsnc.cn/Article/details/gtpptswojs.html

PHP:  // 无重载
来源：http://dali.daxiang520.top/Article/details/gtxjxcixya.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.sysykeji.top/Article/details/gtmtvtutvh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yj20258.top/Article/details/gtobuhfhim.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.nanxinkj.top/Article/details/gtojljjhuu.html

Go:   // 无重载：用不同函数名
来源：http://dali.cdnleiting.top/Article/details/gtfbkrcrnl.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xuanzx.com/Article/details/gtmrizrfmq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.sxryk.cn/Article/details/gtawdzgjrx.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtqyfdqwxr.html

D. 数组 / 列表 / 集合
来源：http://dali.316326.xyz/Article/details/gtdwckbzia.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtnwnbjqcg.html

[D01] 创建数组 / 列表
来源：http://dali.pycfn.com/Article/details/gtaglawrkd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.tian-w.cn/Article/details/gtyoxmqtpp.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ybcxt.top/Article/details/gtsoxjmwwo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hnqzz.top/Article/details/gtlxwuwdid.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xinyue.icu/Article/details/gtgpftikiq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ydzc1.top/Article/details/gtxddqqrdf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gzhubu.top/Article/details/gttubabqvr.html

Ruby: arr = [1, 2, 3]
来源：http://dali.chenzaomai.com/Article/details/gtwdclqznh.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhiwuduotai.top/Article/details/gthuyrfctd.html

[D02] 追加元素到末尾
来源：http://dali.pycfn.com/Article/details/gtkolkaipq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jianghu66.top/Article/details/gtbovuhyts.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hnxiangtu.top/Article/details/gtuaodagic.html

JS:   arr.push(4);
来源：http://dali.wangshuangyany.cn/Article/details/gtqbfcaqpq.html

TS:   arr.push(4);
来源：http://dali.meibo888.top/Article/details/gtybsnsnjv.html

Java: list.add(4);
来源：http://dali.zdqjudy.top/Article/details/gthpzqrdsl.html

Go:   arr = append(arr, 4)
来源：http://dali.guowangkeji.top/Article/details/gttrqpfioc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sxryk.cn/Article/details/gthkoknnym.html

C#:   list.Add(4);
来源：http://dali.nanxinkj.top/Article/details/gttpaysfuf.html

[D03] 在指定位置插入元素
来源：http://dali.yuxming.cn/Article/details/gtllbhmddh.html

Py:   arr.insert(0, 0)
来源：http://dali.bjfxy.top/Article/details/gtitheofrw.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.chenzaomai.com/Article/details/gtdfszifmr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yj20258888.top/Article/details/gtayxtpdoc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.gzhubu.top/Article/details/gtlvvwibwi.html

Java: list.add(0, 0);
来源：http://dali.gzhubu.top/Article/details/gtwvdohnoy.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yongpay.top/Article/details/gtsfzxvzmj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgvaeenbs.html

C#:   list.Insert(0, 0);
来源：http://dali.zhongyouzk.top/Article/details/gtzeopllog.html

[D04] 删除元素
来源：http://dali.jinqigufen.top/Article/details/gtdedviddi.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.tanke756.top/Article/details/gtfooyyfrk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yueranfly.top/Article/details/gtkscyzqlz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cucudq.cn/Article/details/gtohlztcld.html

TS:   arr.splice(0, 1);
来源：http://dali.aibaodan.cn/Article/details/gtztrthcsd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shuidangran.top/Article/details/gtgkmqhseb.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.meibo888.top/Article/details/gtotxwivox.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xinyue.icu/Article/details/gtsxbfghwt.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.chenjidiqi.icu/Article/details/gttngootoo.html

[D05] 访问与修改元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtrhnrkcli.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yuxming.cn/Article/details/gtccdeovtw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hywenlv.cn/Article/details/gtyjgshlot.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.gotoacloud.top/Article/details/gtbgnjppge.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.chenlongwang.top/Article/details/gtgcqaqrbi.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.tianlin.xyz/Article/details/gtiaqhucsx.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.chenlongwang.top/Article/details/gtexjnszsa.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pycfn.com/Article/details/gttfubvhvo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbagknugt.html

[D06] 数组长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtloenmvto.html

Py:   len(arr)
来源：http://dali.smart0.xyz/Article/details/gtmddbjhse.html

PHP:  count($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtbjoammkl.html

JS:   arr.length
来源：http://dali.ppjwa.cn/Article/details/gtfqvttzhc.html

TS:   arr.length
来源：http://dali.yueranfly.top/Article/details/gtpghtgfus.html

Java: list.size();
来源：http://dali.smart0.xyz/Article/details/gtmkbdfflm.html

Go:   len(arr)
来源：http://dali.smart0.xyz/Article/details/gtpqgjuakk.html

Ruby: arr.length; arr.size
来源：http://dali.hammf.cn/Article/details/gtfzkxvnaj.html

C#:   list.Count;
来源：http://dali.meibo888.top/Article/details/gtzpwomwfx.html

[D07] 切片 / 取子数组
来源：http://dali.mhx1999.top/Article/details/gtomjwwuou.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hammf.cn/Article/details/gttsoajcdp.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.andypj.xyz/Article/details/gtordmwarv.html

JS:   arr.slice(1, 4);
来源：http://dali.chenlongwang.top/Article/details/gtrcqyxgdq.html

TS:   arr.slice(1, 4);
来源：http://dali.feifeiyinyue.top/Article/details/gtoznzmaci.html

Java: list.subList(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gtiluzbbxk.html

Go:   arr[1:4]
来源：http://dali.yangfankeji.com/Article/details/gtlljpmjjj.html

Ruby: arr[1, 3]
来源：http://dali.dianchejie.cn/Article/details/gtecmkwizw.html

C#:   list.GetRange(1, 3);
来源：http://dali.jqgfzy.top/Article/details/gtdgvuhuey.html

[D08] 合并两个数组
来源：http://dali.wangdashe.top/Article/details/gtdrekpezn.html

Py:   a + b;  a.extend(b)
来源：http://dali.ppjwa.cn/Article/details/gtixroiciv.html

PHP:  array_merge($a, $b);
来源：http://dali.gogol.net.cn/Article/details/gtizpjozuc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.pengpengdd.cyou/Article/details/gtuxyxhamv.html

TS:   [...a, ...b];
来源：http://dali.mhx1999.top/Article/details/gtwrrpnrio.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtsihkplgg.html

Go:   append(a, b...)
来源：http://dali.xuanzx.com/Article/details/gtdjlmqlfy.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jyoumei.cn/Article/details/gtdbbifihs.html

C#:   a.Concat(b).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtvniaiyba.html

[D09] 排序（升序）
来源：http://dali.chenlongwang.top/Article/details/gtcdzwnuho.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.iojbl.cn/Article/details/gtrbwgujqj.html

PHP:  sort($arr);
来源：http://dali.nwbrower.top/Article/details/gttphporzu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.chenjidiqi.icu/Article/details/gtgrzlcugt.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.nanxinkj.top/Article/details/gtsbhidphl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yuanzhike.top/Article/details/gtehhgabyl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.nwbrower.top/Article/details/gttwvzpyzs.html

Ruby: arr.sort
来源：http://dali.gotoacloud.top/Article/details/gtsseoniyn.html

C#:   list.Sort();
来源：http://dali.yongpay.top/Article/details/gtglnttkik.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cucudq.cn/Article/details/gtbjjemzbn.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hysaishi.cn/Article/details/gtwoykfxhw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtujabyzkd.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuanzhike.top/Article/details/gtmokksvrz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sweek.top/Article/details/gtrcvzaqts.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinghuilouyu.cn/Article/details/gtpfcbeisr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yj202588.top/Article/details/gtlwxlehhm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xuanzx.com/Article/details/gtgatzqsro.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xuanzx.com/Article/details/gtqvwsssgj.html


<!-- 参考信息 -->