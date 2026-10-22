代发 wailian999

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzavjnpus.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhoulong.xyz/Article/details/gtlpphrnvl.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.nwbrower.top/Article/details/gtynbjnexx.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hnqzz.top/Article/details/gthhmxaxci.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yvedp.cn/Article/details/gtqownjppa.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtulhkngab.html

[B11] 生成数字序列 / 区间
来源：http://dali.gzhubu.top/Article/details/gtcunzhtoe.html

Py:   list(range(0, 10, 2))
来源：http://dali.nanxinkj.top/Article/details/gtxxocgikr.html

PHP:  range(0, 10, 2);
来源：http://dali.yangfankeji.com/Article/details/gtudxumluq.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gotoacloud.top/Article/details/gtnwypbyas.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yanxiufei.cn/Article/details/gtbxmmmljh.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zdqjudy.top/Article/details/gtofwmnkqo.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.haohaochexian.top/Article/details/gtszysayze.html

Ruby: (0...10).step(2).to_a
来源：http://dali.haohaochexian.top/Article/details/gtnhxkzhzb.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.meibo888.top/Article/details/gtsszexlbk.html

[B12] 跳出多层循环
来源：http://dali.gogol.net.cn/Article/details/gttzbpbvht.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.chenzaomai.com/Article/details/gtjmnzwsxq.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gthimdyxyr.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhengqikj.top/Article/details/gtnzwnqwvw.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenlongwang.top/Article/details/gtupbeaddx.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258.top/Article/details/gtzhvqmoio.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.andypj.xyz/Article/details/gtezudddbh.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jqgfzy.top/Article/details/gtgolsrdeh.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yangfankeji.com/Article/details/gthsuocano.html

[B13] 判断是否为数字
来源：http://dali.xuetiantiany.cn/Article/details/gtdvmpeqkj.html

Py:   isinstance(x, (int, float))
来源：http://dali.yj20258888.top/Article/details/gtopctetqa.html

PHP:  is_numeric($x)
来源：http://dali.gaohongyu789.top/Article/details/gtqanmsbxj.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jqgufenzy.top/Article/details/gtvjsnmwsy.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.fzhhl.top/Article/details/gtjikfpgxn.html

Java: x instanceof Number
来源：http://dali.dianchejie.cn/Article/details/gttxeruuyr.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.sweek.top/Article/details/gtrqnevzck.html

Ruby: x.is_a?(Numeric)
来源：http://dali.svipenyu.cn/Article/details/gttxkliqew.html

C#:   x is int or double or decimal
来源：http://dali.hnqzz.top/Article/details/gtljwioywe.html

[B14] 判断值是否在集合内
来源：http://dali.chenjidiqi.icu/Article/details/gteiitxpve.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shanyushiyangtech.top/Article/details/gtooxflngt.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.sysykeji.top/Article/details/gtqkluctft.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.nanxinkj.top/Article/details/gtvgoaibgh.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.bjfxy.top/Article/details/gtueondgry.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.snrcjt.cn/Article/details/gtplhugvxm.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.daxiang520.top/Article/details/gtipuxxxms.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hysaishi.cn/Article/details/gtczqnjlho.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hywenlv.cn/Article/details/gtlkbpegrv.html

[B15] 布尔运算与取反
来源：http://dali.jqgufenzy.top/Article/details/gtiewevpbq.html

Py:   a and b or not c
来源：http://dali.kuanghao11.cn/Article/details/gtaxybbttl.html

PHP:  $a && $b || !$c
来源：http://dali.jinghuilouyu.cn/Article/details/gtnbabjjba.html

JS:   a && b || !c
来源：http://dali.svipenyu.cn/Article/details/gtdlcqfezx.html

TS:   a && b || !c
来源：http://dali.fzhhl.top/Article/details/gtbaiccgly.html

Java: a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gtsnlzyxgt.html

Go:   a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gttzodxgvd.html

Ruby: a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gtwaobofia.html

C#:   a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gtjafhvymj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jlsjyb.cn/Article/details/gttxxiajec.html

Py:   if not data: return
来源：http://dali.smart0.xyz/Article/details/gtbczxptrb.html

PHP:  if (!$data) { return; }
来源：http://dali.zhengqikj.top/Article/details/gtrmwzkqtz.html

JS:   if (!data) return;
来源：http://dali.yanxiufei.cn/Article/details/gtokvorqyh.html

TS:   if (!data) return;
来源：http://dali.xuetiantiany.cn/Article/details/gtbqvjvmbt.html

Java: if (data == null) return;
来源：http://dali.yuxming.cn/Article/details/gtsuhycysb.html

Go:   if data == nil { return }
来源：http://dali.sxryk.cn/Article/details/gtjqeonnmy.html

Ruby: return if data.nil?
来源：http://dali.mhx1999.top/Article/details/gtjdqcmjpl.html

C#:   if (data == null) return;
来源：http://dali.ivvv.top/Article/details/gtqgqboyua.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtiycqmdfl.html

C. 函数与作用域
来源：http://dali.sweek.top/Article/details/gtfdlidaij.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtyehbixjx.html

[C01] 定义函数
来源：http://dali.ydzc1.top/Article/details/gtimpsvnuv.html

Py:   def add(a, b): return a + b
来源：http://dali.nwbrower.top/Article/details/gthafmqcyh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.9152youxi.cn/Article/details/gtznoevyxa.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtulqkrxnk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gtrmmxllka.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yonumen.top/Article/details/gtucykjvfh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xinyue.icu/Article/details/gttbkjxkid.html

Ruby: def add(a, b); a + b; end
来源：http://dali.chenzaomai.com/Article/details/gtmtquojms.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gtqxfreytd.html

[C02] 默认参数
来源：http://dali.shzxlz.cn/Article/details/gtqidfyhqn.html

Py:   def greet(name="World"): return name
来源：http://dali.dianchejie.cn/Article/details/gtuksmlrbe.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gtwvrwnhhx.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jyoumei.cn/Article/details/gtnxpvjaii.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.snrcjt.cn/Article/details/gtoiuvvbxl.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.redwolf501.top/Article/details/gtxkrtznhv.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.birdmap.top/Article/details/gtnligoqqm.html

Ruby: def greet(name = "World") = name
来源：http://dali.mhx1999.top/Article/details/gtblnfcwdf.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yongpay.top/Article/details/gtycsluyto.html

[C03] 可变参数
来源：http://dali.shuidangran.top/Article/details/gtpumkxvux.html

Py:   def total(*args): return sum(args)
来源：http://dali.dashuyun.cn/Article/details/gtgdkykhmj.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.dashuyun.cn/Article/details/gtfaemdema.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinqigfzy.top/Article/details/gtjzxjffli.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jyoumei.cn/Article/details/gtvozgitmc.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.guowangkeji.top/Article/details/gtoznokjcd.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhongyouzk.top/Article/details/gtivfgqpfc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.9152youxi.cn/Article/details/gtngmnsnph.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shanyushiyangkeji.top/Article/details/gttbopzpkt.html

[C04] 命名参数 / 关键字参数
来源：http://dali.guannengcc.top/Article/details/gtkzlnwlxt.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.pycfn.com/Article/details/gtdjgodsys.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cheryme.top/Article/details/gtfztputbm.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jianghu66.top/Article/details/gtflhrerjq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.9152youxi.cn/Article/details/gtncmdotzd.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yueranfly.top/Article/details/gthgdoycpa.html

Go:   // 无：用配置结构体参数
来源：http://dali.hongshengwenyu.top/Article/details/gtzvdxjjnx.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hnqzz.top/Article/details/gtyikedjon.html

C#:   f(a: 1, b: 2)
来源：http://dali.yvedp.cn/Article/details/gttfotruuo.html

[C05] 返回多个值
来源：http://dali.pengpengdd.cyou/Article/details/gtjsgwmhzf.html

Py:   return a, b
来源：http://dali.nanxuanxn.top/Article/details/gtlliymqyo.html

PHP:  return [$a, $b];
来源：http://dali.cashguo.top/Article/details/gtjgiklhyt.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cqqwz.cn/Article/details/gtkivrcemu.html

TS:   return { a, b };
来源：http://dali.havefunace.top/Article/details/gtsjcogrlk.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sweek.top/Article/details/gtrimayzad.html

Go:   return a, b
来源：http://dali.daria6918.cn/Article/details/gtjovmoxwc.html

Ruby: return a, b
来源：http://dali.yj20258.top/Article/details/gtldgijktn.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ybcxt.top/Article/details/gtsxouctxa.html

[C06] 匿名函数 / lambda
来源：http://dali.yonumen.top/Article/details/gttiujcjva.html

Py:   square = lambda x: x * x
来源：http://dali.shangyingyoupin.top/Article/details/gtequmnfws.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gotoacloud.top/Article/details/gtxkvutzaq.html

JS:   const square = x => x * x;
来源：http://dali.zdqjudy.top/Article/details/gtrxyhtlyf.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.vqdsnc.cn/Article/details/gtkowmizmz.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.feifeiyinyue.top/Article/details/gtvkdqxguc.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.meibo888.top/Article/details/gthfshnflt.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jqgufenzy.top/Article/details/gtqnrfxouc.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hfpthk.cn/Article/details/gtuijggdwr.html

[C07] 把函数作为参数传入
来源：http://dali.dashuyun.cn/Article/details/gtaswtlyvr.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.svipenyu.cn/Article/details/gtrzjarjbt.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.vqdsnc.cn/Article/details/gthoecznnw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yueranfly.top/Article/details/gtsjfqfuif.html

TS:   arr.map(String)
来源：http://dali.zhengqikj.top/Article/details/gtuthwyfgg.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.chenzaomai.com/Article/details/gtxsieqthq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.nanxuanxn.top/Article/details/gtafrdflgn.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhixingplan.top/Article/details/gtpvngocro.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jinqigfzy.top/Article/details/gtchgeqhfs.html

[C08] 闭包
来源：http://dali.nwbrower.top/Article/details/gtqgwqjbvj.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.pengpengdd.cyou/Article/details/gtcdzgyvrw.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.aibaodan.cn/Article/details/gtfvayndcg.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jyoumei.cn/Article/details/gtyhzehywl.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jyoumei.cn/Article/details/gtskflhdhf.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.c1oappe.top/Article/details/gtmrcinznn.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.dianchejie.cn/Article/details/gtnssvxnsq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.fengsongda.top/Article/details/gtbsdkbssf.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.tianlin.xyz/Article/details/gtzmrjomng.html

[C09] 递归
来源：http://dali.jqgfzy.top/Article/details/gtjerwqlau.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jqgufenzy.top/Article/details/gtslmtoxka.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.chenzaomai.com/Article/details/gtrsrdkxgt.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gzhubu.top/Article/details/gtyqcjxggm.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yuxming.cn/Article/details/gtrmbtyicb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhixingplan.top/Article/details/gtdlswumkz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzwpvlemx.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtcklcxpvk.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zycfv.cn/Article/details/gtmsrydlgf.html

[C10] 变量作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfvxmxues.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinqigufen.top/Article/details/gtgynmzisi.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hongshengwenyu.top/Article/details/gtsrdgkhmv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gogol.net.cn/Article/details/gtxmzpusam.html

TS:   同 JS
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyunecmet.html

Java: 方法内为块级作用域
来源：http://dali.snrcjt.cn/Article/details/gtdfsdozaz.html

Go:   花括号块级作用域
来源：http://dali.xziqi.cn/Article/details/gtrquebjhh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.guowangkeji.top/Article/details/gtcmfxazlj.html

C#:   块级作用域
来源：http://dali.gaohongyu789.top/Article/details/gtdmgcbxdj.html

[C11] 模块导入与导出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfbcjnxqj.html

Py:   from module import func
来源：http://dali.ydzc1.top/Article/details/gtcxfwfwkc.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.snrcjt.cn/Article/details/gtiulhiuif.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ivvv.top/Article/details/gtbzfrfghy.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.kuanghao11.cn/Article/details/gtakrzmghi.html

Java: import java.util.List;
来源：http://dali.pycfn.com/Article/details/gtnxwoftkc.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhixingplan.top/Article/details/gtpkguuxzs.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.tian-w.cn/Article/details/gtdvhokpfs.html

C#:   using System.Text;
来源：http://dali.gzhubu.top/Article/details/gtsobhepjw.html

[C12] 立即执行函数 IIFE
来源：http://dali.jinqigfzy.top/Article/details/gtxhfyesmn.html

Py:   (lambda: print("run"))()
来源：http://dali.zycfv.cn/Article/details/gtcxabitic.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhengqikj.top/Article/details/gtoqaejeeh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinqigufen.top/Article/details/gtbxygazvs.html

TS:   (() => { console.log("run"); })();
来源：http://dali.redwolf501.top/Article/details/gtxmcolodm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sysykeji.top/Article/details/gtrqexwdgq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jlsjyb.cn/Article/details/gtedxckzao.html

Ruby: -> { puts "run" }.call
来源：http://dali.shanyushiyangtech.top/Article/details/gtztvedcfq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xylfe.cn/Article/details/gtggtqzxkj.html

[C13] 类型声明 / 类型注解
来源：http://dali.bjfxy.top/Article/details/gtppxhpcgd.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sysykeji.top/Article/details/gtrzemwdeu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.snrcjt.cn/Article/details/gtofeyqyvo.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xylfe.cn/Article/details/gtpjnzbmmz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gtkylgcigm.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gtluylxjty.html

Go:   func add(a, b int) int
来源：http://dali.316326.xyz/Article/details/gtheuptxxz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.pengpengdd.cyou/Article/details/gtlxoywohc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.nanxuanxn.top/Article/details/gtwdcfbeck.html

[C14] 泛型函数
来源：http://dali.gotoacloud.top/Article/details/gtngbzpnco.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinghuilouyu.cn/Article/details/gtjxxmcmtp.html

PHP:  // 无泛型
来源：http://dali.gzhubu.top/Article/details/gtuoqwfzti.html

JS:   // 无泛型
来源：http://dali.vqdsnc.cn/Article/details/gthivvkeui.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.daxiang520.top/Article/details/gtsyjfipbx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiukthjrx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sxryk.cn/Article/details/gtzreewdun.html

Ruby: # 无泛型
来源：http://dali.kuanghao11.cn/Article/details/gtfighgkol.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yuxming.cn/Article/details/gthztmsmqd.html

[C15] 解构 / 展开参数
来源：http://dali.pengpengdd.cyou/Article/details/gtjhjnamyd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.bjfxy.top/Article/details/gtbpedlnft.html

PHP:  [$a, $b] = $pair;
来源：http://dali.pengpengdd.cyou/Article/details/gtpfjzoeik.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.nwbrower.top/Article/details/gtmamctjov.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.nanxuanxn.top/Article/details/gtlbvlenyb.html

Java: // 无解构
来源：http://dali.mhx1999.top/Article/details/gtkdwwpgvc.html

Go:   // 无解构
来源：http://dali.chenzaomai.com/Article/details/gtzdfviojm.html

Ruby: a, b = pair
来源：http://dali.nanxinkj.top/Article/details/gtncavkqji.html

C#:   var (a, b) = pair;
来源：http://dali.ppjwa.cn/Article/details/gtgbhdvrye.html

[C16] 函数 / 方法重载
来源：http://dali.hfpthk.cn/Article/details/gtlhdphfqz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhoulong.xyz/Article/details/gtdrfvypii.html

PHP:  // 无重载
来源：http://dali.nanxinkj.top/Article/details/gtxovwanug.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xuanzx.com/Article/details/gtdmgdjedn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zdqjudy.top/Article/details/gtenxqimet.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ydzc1.top/Article/details/gtksafxlli.html

Go:   // 无重载：用不同函数名
来源：http://dali.vqdsnc.cn/Article/details/gtjuwtuhcz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gzhubu.top/Article/details/gtzojhaohz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.sufxvd.cn/Article/details/gtwvppkonb.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtsvcvwmao.html

D. 数组 / 列表 / 集合
来源：http://dali.nanxuanxn.top/Article/details/gtiviqhlmq.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtohopvlke.html

[D01] 创建数组 / 列表
来源：http://dali.jinqigfzy.top/Article/details/gtgatbjgmz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.daxiang520.top/Article/details/gtxyrxriyw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hnqzz.top/Article/details/gtjdeajsch.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yvedp.cn/Article/details/gtnksuroek.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cqqwz.cn/Article/details/gttzpxhukx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.316326.xyz/Article/details/gthvcuwukh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gaohongyu789.top/Article/details/gtnfevjzzj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yueranfly.top/Article/details/gtjpeclwzk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jqgfzy.top/Article/details/gtupsmqxkv.html

[D02] 追加元素到末尾
来源：http://dali.316326.xyz/Article/details/gtwsefvvut.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhengqikj.top/Article/details/gtawzwuzuj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.nanxuanxn.top/Article/details/gtxvjkpvqh.html

JS:   arr.push(4);
来源：http://dali.tian-w.cn/Article/details/gtbfscgaqk.html

TS:   arr.push(4);
来源：http://dali.yuanzhike.top/Article/details/gtkgeauhjf.html

Java: list.add(4);
来源：http://dali.meibo888.top/Article/details/gtysejeunm.html

Go:   arr = append(arr, 4)
来源：http://dali.iojbl.cn/Article/details/gtshllkdiv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.c1oappe.top/Article/details/gtucjjocgy.html

C#:   list.Add(4);
来源：http://dali.hywenlv.cn/Article/details/gtjqvecxej.html

[D03] 在指定位置插入元素
来源：http://dali.aibaodan.cn/Article/details/gtdbpqoyki.html

Py:   arr.insert(0, 0)
来源：http://dali.jianghu66.top/Article/details/gtvtzquvbq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.wangshuangyany.cn/Article/details/gtknsxufgb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.sufxvd.cn/Article/details/gtmwdmjteh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cashguo.top/Article/details/gtxjcszpuv.html

Java: list.add(0, 0);
来源：http://dali.xylfe.cn/Article/details/gtafisekkx.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sxryk.cn/Article/details/gtwjmqmxyc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenlongwang.top/Article/details/gtotwmrlas.html

C#:   list.Insert(0, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtthlliabq.html

[D04] 删除元素
来源：http://dali.jlsjyb.cn/Article/details/gtqrotzspl.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.dashuyun.cn/Article/details/gtzfzoxlnn.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sufxvd.cn/Article/details/gtaovlxulp.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhongyouzk.top/Article/details/gtrdafwlve.html

TS:   arr.splice(0, 1);
来源：http://dali.feifeiyinyue.top/Article/details/gtrnrbtces.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sufxvd.cn/Article/details/gtelrrguxd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.mhx1999.top/Article/details/gtdgjgemjj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtywjbeoas.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxvqrkpkj.html

[D05] 访问与修改元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmgwfvdlj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shuidangran.top/Article/details/gttebwmgqu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.smart0.xyz/Article/details/gtjtckrvlg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hongshengwenyu.top/Article/details/gtychlyqfg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtezwylhip.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gogol.net.cn/Article/details/gtujequxpi.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.aizwys.cn/Article/details/gtobbvqwzm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.9152youxi.cn/Article/details/gtpcadyupa.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.dashuyun.cn/Article/details/gtfxdkjxfi.html

[D06] 数组长度
来源：http://dali.0kj1m.cn/Article/details/gtjykcofbb.html

Py:   len(arr)
来源：http://dali.yonumen.top/Article/details/gtxuhlzswh.html

PHP:  count($arr);
来源：http://dali.jqgufenzy.top/Article/details/gttfhaiddu.html

JS:   arr.length
来源：http://dali.pycfn.com/Article/details/gtpajkvpdv.html

TS:   arr.length
来源：http://dali.dashuyun.cn/Article/details/gtottnekvf.html

Java: list.size();
来源：http://dali.wangshuangyany.cn/Article/details/gtgpidyrws.html

Go:   len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtcxtfjndl.html

Ruby: arr.length; arr.size
来源：http://dali.zhiwuduotai.top/Article/details/gticfmaojz.html

C#:   list.Count;
来源：http://dali.yuanzhike.top/Article/details/gtljbvfmdd.html

[D07] 切片 / 取子数组
来源：http://dali.bjfxy.top/Article/details/gtjphrcffl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.snrcjt.cn/Article/details/gtxjxevhyo.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtybqlblgf.html

JS:   arr.slice(1, 4);
来源：http://dali.haohaochexian.top/Article/details/gtxqkbqify.html

TS:   arr.slice(1, 4);
来源：http://dali.yonumen.top/Article/details/gtcglqpzmf.html

Java: list.subList(1, 4);
来源：http://dali.dashuyun.cn/Article/details/gtkaumuhpw.html

Go:   arr[1:4]
来源：http://dali.hammf.cn/Article/details/gtgqebbusx.html

Ruby: arr[1, 3]
来源：http://dali.9152youxi.cn/Article/details/gtfsbpotwp.html

C#:   list.GetRange(1, 3);
来源：http://dali.nanxuanxn.top/Article/details/gthlspqhbh.html

[D08] 合并两个数组
来源：http://dali.shzxlz.cn/Article/details/gtzxvrvekz.html

Py:   a + b;  a.extend(b)
来源：http://dali.birdmap.top/Article/details/gtufkryeet.html

PHP:  array_merge($a, $b);
来源：http://dali.nanxuanxn.top/Article/details/gtmobrifbb.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shangyingyoupin.top/Article/details/gtgarxngak.html

TS:   [...a, ...b];
来源：http://dali.yj20258888.top/Article/details/gthmfkbrwd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.kuanghao11.cn/Article/details/gtsbeqpzrv.html

Go:   append(a, b...)
来源：http://dali.quarkkingdee.top/Article/details/gtvrzrrujc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.wangdashe.top/Article/details/gtxsxwzgat.html

C#:   a.Concat(b).ToList()
来源：http://dali.cqqwz.cn/Article/details/gtnpbuwxei.html

[D09] 排序（升序）
来源：http://dali.yj20258.top/Article/details/gtzgydhudp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ybcxt.top/Article/details/gtswmtriui.html

PHP:  sort($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gttdrnwdkz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jiagoushi.top/Article/details/gtyubolrrq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gzhubu.top/Article/details/gtbkgbdlfu.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yj202588.top/Article/details/gtyyzectwx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.snrcjt.cn/Article/details/gtjuaegwcx.html

Ruby: arr.sort
来源：http://dali.jlsjyb.cn/Article/details/gtwqevette.html

C#:   list.Sort();
来源：http://dali.sufxvd.cn/Article/details/gtsubkcagk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yangfankeji.com/Article/details/gtmbcfplbb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.chenzaomai.com/Article/details/gtbvehaxeu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xylfe.cn/Article/details/gtzofyjtyc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenlongwang.top/Article/details/gtlsdddczz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pycfn.com/Article/details/gtayqzsgbb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jiagoushi.top/Article/details/gtkaxaelrw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.chenjidiqi.icu/Article/details/gtecgvqfzc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shuidangran.top/Article/details/gtxqupvsrd.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.0kj1m.cn/Article/details/gtzoggsedn.html


<!-- 参考信息 -->