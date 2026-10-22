代发 wailian999

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cashguo.top/Article/details/gt2fvsrzxlw.html

[B10] 遍历同时拿索引
来源：http://dali.chenzaomai.com/Article/details/gt2knvtvvvo.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.chenzaomai.com/Article/details/gt2yjtspbpz.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.tian-w.cn/Article/details/gt2yzwlmxzq.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.bjfxy.top/Article/details/gt2ehyjynea.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gvoozsjs.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.nanxuanxn.top/Article/details/gt2eftfgnny.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jqgfzy.top/Article/details/gt2nofyxgkw.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.shzxlz.cn/Article/details/gt2zbnmcohq.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jqgufenzy.top/Article/details/gt2xvfdqlpb.html

[B11] 生成数字序列 / 区间
来源：http://dali.hnxiangtu.top/Article/details/gt2xdqantcz.html

Py:   list(range(0, 10, 2))
来源：http://dali.guowangkeji.top/Article/details/gt2wismoozn.html

PHP:  range(0, 10, 2);
来源：http://dali.zdqjudy.top/Article/details/gt2emluahjx.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.daxiang520.top/Article/details/gt2kryhjqit.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yueranfly.top/Article/details/gt2slfyxjuo.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hnxiangtu.top/Article/details/gt2vlvbgtnl.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.ydzc1.top/Article/details/gt2hugkyjfb.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ehwqpu.com/Article/details/gt2vtnwbwib.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.kuanghao11.cn/Article/details/gt2lakicayf.html

[B12] 跳出多层循环
来源：http://dali.cqqwz.cn/Article/details/gt2ffknatcz.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.guannengcc.top/Article/details/gt2ycehqbfc.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bxuztyuw.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xzkxguss.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgfzy.top/Article/details/gt2qazatycs.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cheryme.top/Article/details/gt2lrtdgkzx.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ydzc1.top/Article/details/gt2qasvlyuk.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zycfv.cn/Article/details/gt2vtrwdtts.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.svipenyu.cn/Article/details/gt2wkjjucxz.html

[B13] 判断是否为数字
来源：http://dali.chenjidiqi.icu/Article/details/gt2sfknjddz.html

Py:   isinstance(x, (int, float))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hmvkucpn.html

PHP:  is_numeric($x)
来源：http://dali.yangfankeji.com/Article/details/gt2rvesulpt.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yonumen.top/Article/details/gt2soscjnfn.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.birdmap.top/Article/details/gt2xlfjxkxi.html

Java: x instanceof Number
来源：http://dali.feifeiyinyue.top/Article/details/gt2tcdnbwvv.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cucudq.cn/Article/details/gt2pwexvhsk.html

Ruby: x.is_a?(Numeric)
来源：http://dali.nanxinkj.top/Article/details/gt2fczskjjc.html

C#:   x is int or double or decimal
来源：http://dali.yanxiufei.cn/Article/details/gt2tcjtwyby.html

[B14] 判断值是否在集合内
来源：http://dali.ivvv.top/Article/details/gt2rdpttzuu.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hnxiangtu.top/Article/details/gt2qclqpian.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.tian-w.cn/Article/details/gt2nlehxwjk.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ickfkwkz.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.chenlongwang.top/Article/details/gt2mbanznvi.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.cdnleiting.top/Article/details/gt2iqctpqfp.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2aciywzgo.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.wangdashe.top/Article/details/gt2sejduanl.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.shuidangran.top/Article/details/gt2kxxqybav.html

[B15] 布尔运算与取反
来源：http://dali.316326.xyz/Article/details/gt2aefngwun.html

Py:   a and b or not c
来源：http://dali.andypj.xyz/Article/details/gt2tpqjgrcq.html

PHP:  $a && $b || !$c
来源：http://dali.xuanzx.com/Article/details/gt2wbpxvkaz.html

JS:   a && b || !c
来源：http://dali.sysykeji.top/Article/details/gt2odcxvsim.html

TS:   a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gt2zalwiirw.html

Java: a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gt2ygnqfcbd.html

Go:   a && b || !c
来源：http://dali.cucudq.cn/Article/details/gt2uizktdyc.html

Ruby: a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gt2ofzathph.html

C#:   a && b || !c
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vsswhwxc.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jlsjyb.cn/Article/details/gt2xjpzvrqa.html

Py:   if not data: return
来源：http://dali.daria6918.cn/Article/details/gt2ezcmvucg.html

PHP:  if (!$data) { return; }
来源：http://dali.sweek.top/Article/details/gt2wosyuwnh.html

JS:   if (!data) return;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vnuswoqf.html

TS:   if (!data) return;
来源：http://dali.dianchejie.cn/Article/details/gt2aqpezanv.html

Java: if (data == null) return;
来源：http://dali.yuxming.cn/Article/details/gt2rqqrkiac.html

Go:   if data == nil { return }
来源：http://dali.jiagoushi.top/Article/details/gt2jyfokviu.html

Ruby: return if data.nil?
来源：http://dali.iojbl.cn/Article/details/gt2rfwawhbw.html

C#:   if (data == null) return;
来源：http://dali.nanxuanxn.top/Article/details/gt2sgfxpvhc.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2aytaxwxm.html

C. 函数与作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eddtemip.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2nlzxasiy.html

[C01] 定义函数
来源：http://dali.gotoacloud.top/Article/details/gt2gtcqpsbu.html

Py:   def add(a, b): return a + b
来源：http://dali.tanke756.top/Article/details/gt2muakrkcn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.svipenyu.cn/Article/details/gt2hkzjpqzf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gt2gryhtwqx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gt2pcxgniun.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gt2ertujduu.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.0kj1m.cn/Article/details/gt2fceheljf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.havefunace.top/Article/details/gt2iuwhatwf.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2lhnokost.html

[C02] 默认参数
来源：http://dali.jqgfzy.top/Article/details/gt2feajvhgo.html

Py:   def greet(name="World"): return name
来源：http://dali.yongpay.top/Article/details/gt2srcxhveq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cucudq.cn/Article/details/gt2wjvvpukc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.iojbl.cn/Article/details/gt2ytwrgcwf.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.chenzaomai.com/Article/details/gt2gwmisiun.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhiwuduotai.top/Article/details/gt2embbtpvv.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jiagoushi.top/Article/details/gt2psotolfh.html

Ruby: def greet(name = "World") = name
来源：http://dali.havefunace.top/Article/details/gt2mxoxqelb.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cucudq.cn/Article/details/gt2xpkduztn.html

[C03] 可变参数
来源：http://dali.jinqigufen.top/Article/details/gt2fgkvznol.html

Py:   def total(*args): return sum(args)
来源：http://dali.fzhhl.top/Article/details/gt2nwtdrafe.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.meibo888.top/Article/details/gt2lbjdddnc.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.pycfn.com/Article/details/gt2crrblrlz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rccwdlxt.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.0kj1m.cn/Article/details/gt2uxltsvbo.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.fzhhl.top/Article/details/gt2nzhfolyl.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinqigufen.top/Article/details/gt2cqjcysex.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ydzc1.top/Article/details/gt2qlkwwjyp.html

[C04] 命名参数 / 关键字参数
来源：http://dali.c1oappe.top/Article/details/gt2knnjefys.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yangfankeji.com/Article/details/gt2typutqcd.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hammf.cn/Article/details/gt2htmpcaeq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2twlpiriy.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.wangshuangyany.cn/Article/details/gt2dxsvsisp.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xuetiantiany.cn/Article/details/gt2pnzlchxr.html

Go:   // 无：用配置结构体参数
来源：http://dali.ydzc1.top/Article/details/gt2ctjuqowi.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhixingplan.top/Article/details/gt2ymbdjaff.html

C#:   f(a: 1, b: 2)
来源：http://dali.yongpay.top/Article/details/gt2ofubanyv.html

[C05] 返回多个值
来源：http://dali.jiagoushi.top/Article/details/gt2abyzduij.html

Py:   return a, b
来源：http://dali.andypj.xyz/Article/details/gt2yjdigkla.html

PHP:  return [$a, $b];
来源：http://dali.ehwqpu.com/Article/details/gt2gsshuejj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.iojbl.cn/Article/details/gt2qbbtflcu.html

TS:   return { a, b };
来源：http://dali.daxiang520.top/Article/details/gt2hnpdkctg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ppjwa.cn/Article/details/gt2naltchiz.html

Go:   return a, b
来源：http://dali.nanxuanxn.top/Article/details/gt2kuuwnpot.html

Ruby: return a, b
来源：http://dali.zhongyouzk.top/Article/details/gt2tmmythgs.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hywenlv.cn/Article/details/gt2rgebpmly.html

[C06] 匿名函数 / lambda
来源：http://dali.hysaishi.cn/Article/details/gt2awxhvhkp.html

Py:   square = lambda x: x * x
来源：http://dali.hammf.cn/Article/details/gt2alkxsajb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jinqigufen.top/Article/details/gt2cyiaicpu.html

JS:   const square = x => x * x;
来源：http://dali.tanke756.top/Article/details/gt2nqatfnch.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.gaohongyu789.top/Article/details/gt2zsoajorb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yj20258888.top/Article/details/gt2wrgwnvbt.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hysaishi.cn/Article/details/gt2ssuobiph.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yuanzhike.top/Article/details/gt2bhhjcqjc.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhongyouzk.top/Article/details/gt2ndczwriy.html

[C07] 把函数作为参数传入
来源：http://dali.ivvv.top/Article/details/gt2vjgkzkac.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cheryme.top/Article/details/gt2vjenaeuk.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2swhxmnxt.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.9152youxi.cn/Article/details/gt2kqbpepce.html

TS:   arr.map(String)
来源：http://dali.redwolf501.top/Article/details/gt2iekmnxhf.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xziqi.cn/Article/details/gt2gujtkvra.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yongpay.top/Article/details/gt2uahqodel.html

Ruby: arr.map(&:upcase)
来源：http://dali.yj20258888.top/Article/details/gt2ntfwccnx.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.feifeiyinyue.top/Article/details/gt2pwbcwzvz.html

[C08] 闭包
来源：http://dali.316326.xyz/Article/details/gt2gcodqgun.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cucudq.cn/Article/details/gt2dwcpulxp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xinyue.icu/Article/details/gt2wudriepq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.sxryk.cn/Article/details/gt2akuxsxso.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhongyouzk.top/Article/details/gt2aelbcwwe.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.haohaochexian.top/Article/details/gt2scavpicv.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.redwolf501.top/Article/details/gt2apvfzrgi.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rpyvoprk.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ydzc1.top/Article/details/gt2ifvanylb.html

[C09] 递归
来源：http://dali.feifeiyinyue.top/Article/details/gt2vedzxstw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2zwommvfx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhixingplan.top/Article/details/gt2ehcxfhfd.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.quarkkingdee.top/Article/details/gt2jninzgrz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yonumen.top/Article/details/gt2wgoztxye.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.nwbrower.top/Article/details/gt2lkmmyvni.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hnxiangtu.top/Article/details/gt2uifetpca.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cqqwz.cn/Article/details/gt2isnvcvgi.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.nanxuanxn.top/Article/details/gt2kamkuqnt.html

[C10] 变量作用域
来源：http://dali.ydzc1.top/Article/details/gt2bgiwcesf.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gogol.net.cn/Article/details/gt2cjpwgkkp.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.chenjidiqi.icu/Article/details/gt2mkeexrrz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhoulong.xyz/Article/details/gt2yxivroug.html

TS:   同 JS
来源：http://dali.wangshuangyany.cn/Article/details/gt2bvjnbjoe.html

Java: 方法内为块级作用域
来源：http://dali.ppjwa.cn/Article/details/gt2zwyvzarw.html

Go:   花括号块级作用域
来源：http://dali.jlsjyb.cn/Article/details/gt2swekehfp.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.svipenyu.cn/Article/details/gt2jemkwcvm.html

C#:   块级作用域
来源：http://dali.jlsjyb.cn/Article/details/gt2hwfqrdwp.html

[C11] 模块导入与导出
来源：http://dali.guowangkeji.top/Article/details/gt2bmaqqyqw.html

Py:   from module import func
来源：http://dali.ehwqpu.com/Article/details/gt2najioeyx.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.pengpengdd.cyou/Article/details/gt2mrfnxpim.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xxzhmqzx.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.snrcjt.cn/Article/details/gt2vajuzvjr.html

Java: import java.util.List;
来源：http://dali.316326.xyz/Article/details/gt2pfsaizum.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.dashuyun.cn/Article/details/gt2tkkesewx.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2khtsedzl.html

C#:   using System.Text;
来源：http://dali.chenjidiqi.icu/Article/details/gt2xgfgngyq.html

[C12] 立即执行函数 IIFE
来源：http://dali.mhx1999.top/Article/details/gt2ipahbnvk.html

Py:   (lambda: print("run"))()
来源：http://dali.yuxming.cn/Article/details/gt2dgesuamn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.9152youxi.cn/Article/details/gt2hafhnbyn.html

JS:   (() => { console.log("run"); })();
来源：http://dali.dianchejie.cn/Article/details/gt2txnhkdmc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2letkogpp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.chenjidiqi.icu/Article/details/gt2phjzcqie.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.vqdsnc.cn/Article/details/gt2rtqorabk.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2qdmqffkh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.9152youxi.cn/Article/details/gt2xtcinwtp.html

[C13] 类型声明 / 类型注解
来源：http://dali.tianlin.xyz/Article/details/gt2tqvuvvvu.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hywenlv.cn/Article/details/gt2iypnitns.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2lijgblmu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gzhubu.top/Article/details/gt2khhrauna.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2acsgrmgy.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2xpywleuz.html

Go:   func add(a, b int) int
来源：http://dali.daria6918.cn/Article/details/gt2ogwkkfnd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.smart0.xyz/Article/details/gt2gygwhchv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.meibo888.top/Article/details/gt2lhkstmqa.html

[C14] 泛型函数
来源：http://dali.jinqigfzy.top/Article/details/gt2cwqemclt.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.pycfn.com/Article/details/gt2kwpxjkcw.html

PHP:  // 无泛型
来源：http://dali.hnxiangtu.top/Article/details/gt2ruzlmgws.html

JS:   // 无泛型
来源：http://dali.zhiwuduotai.top/Article/details/gt2jejribep.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.svipenyu.cn/Article/details/gt2ywczrunf.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.c1oappe.top/Article/details/gt2ejhvnhro.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.guowangkeji.top/Article/details/gt2ahazzykb.html

Ruby: # 无泛型
来源：http://dali.yongpay.top/Article/details/gt2jsdwyesy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.tianlin.xyz/Article/details/gt2vfcxjztz.html

[C15] 解构 / 展开参数
来源：http://dali.sweek.top/Article/details/gt2yspaopvm.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ddzmruif.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cashguo.top/Article/details/gt2iztnmsyi.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2keemzkbn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.andypj.xyz/Article/details/gt2wfdilvnb.html

Java: // 无解构
来源：http://dali.nanxuanxn.top/Article/details/gt2eanjfdaf.html

Go:   // 无解构
来源：http://dali.dianchejie.cn/Article/details/gt2oahjprpk.html

Ruby: a, b = pair
来源：http://dali.tian-w.cn/Article/details/gt2dayxjqqo.html

C#:   var (a, b) = pair;
来源：http://dali.hnqzz.top/Article/details/gt2ajjhhjji.html

[C16] 函数 / 方法重载
来源：http://dali.vqdsnc.cn/Article/details/gt2eaaamkzw.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hongshengwenyu.top/Article/details/gt2bqfgrmca.html

PHP:  // 无重载
来源：http://dali.snrcjt.cn/Article/details/gt2lxzxndwq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.bjfxy.top/Article/details/gt2qcbwothq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.havefunace.top/Article/details/gt2jfqerwtr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gogol.net.cn/Article/details/gt2supqstzq.html

Go:   // 无重载：用不同函数名
来源：http://dali.9152youxi.cn/Article/details/gt2hbuogdbv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yueranfly.top/Article/details/gt2yxjeyupz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.tian-w.cn/Article/details/gt2vzwpowbx.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2oxmgnujh.html

D. 数组 / 列表 / 集合
来源：http://dali.nanxinkj.top/Article/details/gt2frhaxxed.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2ndwruvbq.html

[D01] 创建数组 / 列表
来源：http://dali.yj20258888.top/Article/details/gt2nlloqvoq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shzxlz.cn/Article/details/gt2rajfkjny.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ybcxt.top/Article/details/gt2mjuxptwm.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sxryk.cn/Article/details/gt2lhhupkof.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.sufxvd.cn/Article/details/gt2dqtiyphm.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yonumen.top/Article/details/gt2ujgyloiz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.nanxinkj.top/Article/details/gt2adryryfz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.c1oappe.top/Article/details/gt2wncanwig.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yuanzhike.top/Article/details/gt2icjiyrrd.html

[D02] 追加元素到末尾
来源：http://dali.ehwqpu.com/Article/details/gt2voupxjgl.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jiagoushi.top/Article/details/gt2irfbqtdk.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gogol.net.cn/Article/details/gt2yalycabp.html

JS:   arr.push(4);
来源：http://dali.guowangkeji.top/Article/details/gt2fbrqsgox.html

TS:   arr.push(4);
来源：http://dali.sxryk.cn/Article/details/gt2ytyoplip.html

Java: list.add(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pdqcjofy.html

Go:   arr = append(arr, 4)
来源：http://dali.ppjwa.cn/Article/details/gt2ihhduhpq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gaohongyu789.top/Article/details/gt2kdbxasor.html

C#:   list.Add(4);
来源：http://dali.jinqigufen.top/Article/details/gt2bpqvhbim.html

[D03] 在指定位置插入元素
来源：http://dali.gotoacloud.top/Article/details/gt2cqldbqmq.html

Py:   arr.insert(0, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2uhsjbbkj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cheryme.top/Article/details/gt2elnvnnky.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.fengsongda.top/Article/details/gt2eaanwlhw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jlsjyb.cn/Article/details/gt2anhljiab.html

Java: list.add(0, 0);
来源：http://dali.hnqzz.top/Article/details/gt2zivounxh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cashguo.top/Article/details/gt2kodervlx.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.nanxinkj.top/Article/details/gt2gzsspkqq.html

C#:   list.Insert(0, 0);
来源：http://dali.daria6918.cn/Article/details/gt2uwzvcmjt.html

[D04] 删除元素
来源：http://dali.pengpengdd.cyou/Article/details/gt2rdwtvngb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jsbqhmuh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2tkpuhevg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.nanxinkj.top/Article/details/gt2rvhgfwed.html

TS:   arr.splice(0, 1);
来源：http://dali.jianghu66.top/Article/details/gt2ktcqqhzk.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.kuanghao11.cn/Article/details/gt2yfyfuslk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.tian-w.cn/Article/details/gt2cvvjijvl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.smart0.xyz/Article/details/gt2mtjdrcfl.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zdqjudy.top/Article/details/gt2fdpmjmsm.html

[D05] 访问与修改元素
来源：http://dali.hfpthk.cn/Article/details/gt2wdprgsal.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pycfn.com/Article/details/gt2lsxfbmnp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinqigfzy.top/Article/details/gt2vqfoflhk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shangyingyoupin.top/Article/details/gt2wqvxclak.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.feifeiyinyue.top/Article/details/gt2qrstkvsu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jyoumei.cn/Article/details/gt2cjyqoaqq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yuanzhike.top/Article/details/gt2tcjdugge.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangdashe.top/Article/details/gt2abelbsaz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gzhubu.top/Article/details/gt2nqhriutf.html

[D06] 数组长度
来源：http://dali.jiagoushi.top/Article/details/gt2wcmltdyq.html

Py:   len(arr)
来源：http://dali.yonumen.top/Article/details/gt2aprfqxhi.html

PHP:  count($arr);
来源：http://dali.sysykeji.top/Article/details/gt2esfovkjq.html

JS:   arr.length
来源：http://dali.wangshuangyany.cn/Article/details/gt2ypgmzqbj.html

TS:   arr.length
来源：http://dali.ybcxt.top/Article/details/gt2mccoxegg.html

Java: list.size();
来源：http://dali.smart0.xyz/Article/details/gt2yxrokmyn.html

Go:   len(arr)
来源：http://dali.9152youxi.cn/Article/details/gt2igbxebji.html

Ruby: arr.length; arr.size
来源：http://dali.jiagoushi.top/Article/details/gt2xehgmpeo.html

C#:   list.Count;
来源：http://dali.sysykeji.top/Article/details/gt2bvokomps.html

[D07] 切片 / 取子数组
来源：http://dali.ybcxt.top/Article/details/gt2xcvswjon.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2edkvsrqm.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jqgufenzy.top/Article/details/gt2ermovavq.html

JS:   arr.slice(1, 4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hfbklgbt.html

TS:   arr.slice(1, 4);
来源：http://dali.jinqigfzy.top/Article/details/gt2hfghmfbn.html

Java: list.subList(1, 4);
来源：http://dali.cucudq.cn/Article/details/gt2vzmqlgmp.html

Go:   arr[1:4]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hvmdwtis.html

Ruby: arr[1, 3]
来源：http://dali.chenlongwang.top/Article/details/gt2uxivvfgt.html

C#:   list.GetRange(1, 3);
来源：http://dali.iojbl.cn/Article/details/gt2kekvebjj.html

[D08] 合并两个数组
来源：http://dali.vqdsnc.cn/Article/details/gt2tgmewqhw.html

Py:   a + b;  a.extend(b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pavhljnk.html

PHP:  array_merge($a, $b);
来源：http://dali.yj20258888.top/Article/details/gt2jgyqvdeh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xuanzx.com/Article/details/gt2cmulomrv.html

TS:   [...a, ...b];
来源：http://dali.jlsjyb.cn/Article/details/gt2hqllqzaj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ppjwa.cn/Article/details/gt2yezkrdru.html

Go:   append(a, b...)
来源：http://dali.gaohongyu789.top/Article/details/gt2wydqrfil.html

Ruby: a + b;  a.concat(b)
来源：http://dali.nwbrower.top/Article/details/gt2gfwpfgtf.html

C#:   a.Concat(b).ToList()
来源：http://dali.zycfv.cn/Article/details/gt2kqacjsdo.html

[D09] 排序（升序）
来源：http://dali.yuxming.cn/Article/details/gt2gakdckix.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zdqjudy.top/Article/details/gt2mxljmzax.html

PHP:  sort($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2rccuwzan.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yj202588.top/Article/details/gt2ccyqrsgw.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.nanxinkj.top/Article/details/gt2odsedooa.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yuxming.cn/Article/details/gt2fykcksmx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vlyuldvc.html

Ruby: arr.sort
来源：http://dali.cashguo.top/Article/details/gt2jqncvwve.html

C#:   list.Sort();
来源：http://dali.cdnleiting.top/Article/details/gt2whnslvkg.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.guowangkeji.top/Article/details/gt2yqkgsykn.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.dianchejie.cn/Article/details/gt2kemmawsv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cheryme.top/Article/details/gt2odzuacoq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuetiantiany.cn/Article/details/gt2niayautv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gaohongyu789.top/Article/details/gt2izbhfkol.html


<!-- 参考信息 -->