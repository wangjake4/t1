代发 wailian999

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gaohongyu789.top/Article/details/gt2ntbnukps.html

[B10] 遍历同时拿索引
来源：http://dali.yvedp.cn/Article/details/gt2lcwcxjzc.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jianghu66.top/Article/details/gt2xoaivhaz.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yuanzhike.top/Article/details/gt2wfwgbnxv.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yj202588.top/Article/details/gt2ciooterg.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.316326.xyz/Article/details/gt2roaxpzbx.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yanxiufei.cn/Article/details/gt2grdgzxsu.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.pengpengdd.cyou/Article/details/gt2hbijfvit.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhengqikj.top/Article/details/gt2dzkpshsd.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.c1oappe.top/Article/details/gt2waodyyer.html

[B11] 生成数字序列 / 区间
来源：http://dali.quarkkingdee.top/Article/details/gt2rapieixe.html

Py:   list(range(0, 10, 2))
来源：http://dali.sysykeji.top/Article/details/gt2xfhjcipd.html

PHP:  range(0, 10, 2);
来源：http://dali.tianlin.xyz/Article/details/gt2kkbfuxuz.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.pengpengdd.cyou/Article/details/gt2rwsiekud.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj202588.top/Article/details/gt2mvrulefr.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.aibaodan.cn/Article/details/gt2rizeknsb.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zdqjudy.top/Article/details/gt2ixpjuxxg.html

Ruby: (0...10).step(2).to_a
来源：http://dali.9152youxi.cn/Article/details/gt2vvpqsjlz.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yj20258.top/Article/details/gt2snnpvkhi.html

[B12] 跳出多层循环
来源：http://dali.dashuyun.cn/Article/details/gt2rtlciyxa.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cashguo.top/Article/details/gt2teqoipzk.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fkovumxd.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhixingplan.top/Article/details/gt2wqzwjlhs.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgfzy.top/Article/details/gt2xqjekerg.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhiwuduotai.top/Article/details/gt2bfdwlmas.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.gogol.net.cn/Article/details/gt2osingauk.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.shzxlz.cn/Article/details/gt2wmktuywp.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xuetiantiany.cn/Article/details/gt2lfqbrumw.html

[B13] 判断是否为数字
来源：http://dali.birdmap.top/Article/details/gt2xkvlbxmr.html

Py:   isinstance(x, (int, float))
来源：http://dali.xuetiantiany.cn/Article/details/gt2ntxnpslh.html

PHP:  is_numeric($x)
来源：http://dali.cucudq.cn/Article/details/gt2oerxsvtw.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xuanzx.com/Article/details/gt2ogomxqkr.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kvorksym.html

Java: x instanceof Number
来源：http://dali.yuxming.cn/Article/details/gt2uohddlkk.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.aizwys.cn/Article/details/gt2uzteaypr.html

Ruby: x.is_a?(Numeric)
来源：http://dali.daria6918.cn/Article/details/gt2qtvyipqb.html

C#:   x is int or double or decimal
来源：http://dali.nanxuanxn.top/Article/details/gt2jfcfesly.html

[B14] 判断值是否在集合内
来源：http://dali.yvedp.cn/Article/details/gt2fwtihidi.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yj20258888.top/Article/details/gt2mlreudnd.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.sweek.top/Article/details/gt2yskggoyh.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.iojbl.cn/Article/details/gt2bwfuatos.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.tanke756.top/Article/details/gt2ldmblhhe.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ybcxt.top/Article/details/gt2mabrquox.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.daria6918.cn/Article/details/gt2umjniytv.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhixingplan.top/Article/details/gt2uvwaheoy.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.daxiang520.top/Article/details/gt2ussvncym.html

[B15] 布尔运算与取反
来源：http://dali.jyoumei.cn/Article/details/gt2fyryigym.html

Py:   a and b or not c
来源：http://dali.zhongyouzk.top/Article/details/gt2gavqtbdd.html

PHP:  $a && $b || !$c
来源：http://dali.chenlongwang.top/Article/details/gt2smczrvkr.html

JS:   a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gt2qmayyhbi.html

TS:   a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gt2txsscdbw.html

Java: a && b || !c
来源：http://dali.yj20258888.top/Article/details/gt2tgcmkdma.html

Go:   a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hrisftah.html

Ruby: a && b || !c
来源：http://dali.xuanzx.com/Article/details/gt2vbyiaahb.html

C#:   a && b || !c
来源：http://dali.wangdashe.top/Article/details/gt2ifdceulm.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.redwolf501.top/Article/details/gt2bnqlvxpe.html

Py:   if not data: return
来源：http://dali.yueranfly.top/Article/details/gt2wbslnvlt.html

PHP:  if (!$data) { return; }
来源：http://dali.chenzaomai.com/Article/details/gt2kenlndec.html

JS:   if (!data) return;
来源：http://dali.yongpay.top/Article/details/gt2offlmbui.html

TS:   if (!data) return;
来源：http://dali.fzhhl.top/Article/details/gt2qywvstlu.html

Java: if (data == null) return;
来源：http://dali.feifeiyinyue.top/Article/details/gt2kelkaays.html

Go:   if data == nil { return }
来源：http://dali.sufxvd.cn/Article/details/gt2bltoqztl.html

Ruby: return if data.nil?
来源：http://dali.ivvv.top/Article/details/gt2fttfehlu.html

C#:   if (data == null) return;
来源：http://dali.chenlongwang.top/Article/details/gt2krhxxtwg.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2ietnhtxi.html

C. 函数与作用域
来源：http://dali.zycfv.cn/Article/details/gt2xprywbuh.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2mwqnlbzj.html

[C01] 定义函数
来源：http://dali.aibaodan.cn/Article/details/gt2gaogoapb.html

Py:   def add(a, b): return a + b
来源：http://dali.shuidangran.top/Article/details/gt2skemwdkj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.iojbl.cn/Article/details/gt2izromqwx.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gt2hljzbpko.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gt2daamjlwm.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gt2zayjuxti.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bhovqekl.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ydzc1.top/Article/details/gt2vxjwbmhd.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gt2geopgumv.html

[C02] 默认参数
来源：http://dali.bjfxy.top/Article/details/gt2hlrvwwte.html

Py:   def greet(name="World"): return name
来源：http://dali.jianghu66.top/Article/details/gt2kfrvlwjx.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zycfv.cn/Article/details/gt2acmbwyvq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aggjknwx.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2bgupaleq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.0kj1m.cn/Article/details/gt2dcrbubhd.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yangfankeji.com/Article/details/gt2tuepooyh.html

Ruby: def greet(name = "World") = name
来源：http://dali.iojbl.cn/Article/details/gt2cyvegkgh.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gogol.net.cn/Article/details/gt2kdluywnx.html

[C03] 可变参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2tsaqhiyp.html

Py:   def total(*args): return sum(args)
来源：http://dali.ydzc1.top/Article/details/gt2qreqmelk.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hnqzz.top/Article/details/gt2whwyvtqa.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gzhubu.top/Article/details/gt2aorqmzme.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hysaishi.cn/Article/details/gt2gebyytcf.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.gotoacloud.top/Article/details/gt2vrhcaixa.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.haohaochexian.top/Article/details/gt2uqkjhqzf.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yuanzhike.top/Article/details/gt2vynqhfgp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hywenlv.cn/Article/details/gt2tvcjuasj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.chenzaomai.com/Article/details/gt2neyicwcz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhixingplan.top/Article/details/gt2ahjiyoyo.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jyoumei.cn/Article/details/gt2iaritdgd.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.wangdashe.top/Article/details/gt2znclkxir.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.havefunace.top/Article/details/gt2lkpmpmxj.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xylfe.cn/Article/details/gt2lavfbdhi.html

Go:   // 无：用配置结构体参数
来源：http://dali.meibo888.top/Article/details/gt2xdlzbtyl.html

Ruby: f(a: 1, b: 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2aeuaypbf.html

C#:   f(a: 1, b: 2)
来源：http://dali.sysykeji.top/Article/details/gt2ayvuqxkh.html

[C05] 返回多个值
来源：http://dali.jianghu66.top/Article/details/gt2joiesbyf.html

Py:   return a, b
来源：http://dali.hammf.cn/Article/details/gt2ludedfye.html

PHP:  return [$a, $b];
来源：http://dali.cqqwz.cn/Article/details/gt2qlsbbdgn.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.fzhhl.top/Article/details/gt2ltgxltnv.html

TS:   return { a, b };
来源：http://dali.ppjwa.cn/Article/details/gt2ugqhefhd.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shanyushiyangtech.top/Article/details/gt2essfingz.html

Go:   return a, b
来源：http://dali.daria6918.cn/Article/details/gt2advkkkpv.html

Ruby: return a, b
来源：http://dali.yonumen.top/Article/details/gt2jbmdceln.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yonumen.top/Article/details/gt2intwxtnd.html

[C06] 匿名函数 / lambda
来源：http://dali.ydzc1.top/Article/details/gt2trvjiafh.html

Py:   square = lambda x: x * x
来源：http://dali.wangshuangyany.cn/Article/details/gt2fikfsabs.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.dashuyun.cn/Article/details/gt2ziqymajm.html

JS:   const square = x => x * x;
来源：http://dali.jianghu66.top/Article/details/gt2wkxkeebv.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hnxiangtu.top/Article/details/gt2hdvrourg.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.aizwys.cn/Article/details/gt2sgyrsppa.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ylfnheki.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hfpthk.cn/Article/details/gt2gdlmnalw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shuidangran.top/Article/details/gt2lkoddnys.html

[C07] 把函数作为参数传入
来源：http://dali.jiagoushi.top/Article/details/gt2bnrsagvi.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.tianlin.xyz/Article/details/gt2yhwrygff.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hnqzz.top/Article/details/gt2yvphubgo.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hfpthk.cn/Article/details/gt2xadlllsi.html

TS:   arr.map(String)
来源：http://dali.xziqi.cn/Article/details/gt2gcfucxtf.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xylfe.cn/Article/details/gt2ycjwiwls.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yuanzhike.top/Article/details/gt2mmggsgsx.html

Ruby: arr.map(&:upcase)
来源：http://dali.jqgfzy.top/Article/details/gt2aarozgrz.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cashguo.top/Article/details/gt2bxosjlir.html

[C08] 闭包
来源：http://dali.feifeiyinyue.top/Article/details/gt2uuzomvkp.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cdnleiting.top/Article/details/gt2kabjbife.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2iewfxall.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.daxiang520.top/Article/details/gt2ngfoqeon.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hambulfg.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xinyue.icu/Article/details/gt2zodlmrmg.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.snrcjt.cn/Article/details/gt2fwymnoij.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cdnleiting.top/Article/details/gt2twqpuoev.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.mhx1999.top/Article/details/gt2htflkxbb.html

[C09] 递归
来源：http://dali.yj20258.top/Article/details/gt2fzcbebpq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.pycfn.com/Article/details/gt2udzumqdm.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.havefunace.top/Article/details/gt2ypygljac.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.svipenyu.cn/Article/details/gt2vwbafipc.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mtdcmjke.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yangfankeji.com/Article/details/gt2rgmddeuj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hnqzz.top/Article/details/gt2movxtkbs.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.nanxinkj.top/Article/details/gt2udmqgwfe.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ybcxt.top/Article/details/gt2twwknmhi.html

[C10] 变量作用域
来源：http://dali.yongpay.top/Article/details/gt2rnqqkifs.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hfpthk.cn/Article/details/gt2hnujfwri.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.tanke756.top/Article/details/gt2dtocdmzp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.sysykeji.top/Article/details/gt2aeuvwvhg.html

TS:   同 JS
来源：http://dali.nwbrower.top/Article/details/gt2euwkdtxh.html

Java: 方法内为块级作用域
来源：http://dali.zhixingplan.top/Article/details/gt2iecwwrbo.html

Go:   花括号块级作用域
来源：http://dali.vqdsnc.cn/Article/details/gt2gnrlrlhl.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yongpay.top/Article/details/gt2hxxzsayy.html

C#:   块级作用域
来源：http://dali.jyoumei.cn/Article/details/gt2cwujomrt.html

[C11] 模块导入与导出
来源：http://dali.zhengqikj.top/Article/details/gt2zwsrkvyc.html

Py:   from module import func
来源：http://dali.xinyue.icu/Article/details/gt2hathslzy.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.chenlongwang.top/Article/details/gt2rrkpbwom.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shzxlz.cn/Article/details/gt2wbukhsbq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ppjwa.cn/Article/details/gt2nychppmv.html

Java: import java.util.List;
来源：http://dali.bjfxy.top/Article/details/gt2qawnoqhc.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinqigfzy.top/Article/details/gt2wajeggpx.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jqgfzy.top/Article/details/gt2naeatnco.html

C#:   using System.Text;
来源：http://dali.tianlin.xyz/Article/details/gt2izxeotko.html

[C12] 立即执行函数 IIFE
来源：http://dali.nanxinkj.top/Article/details/gt2akujsmtb.html

Py:   (lambda: print("run"))()
来源：http://dali.jqgfzy.top/Article/details/gt2xkuiaxrn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yongpay.top/Article/details/gt2jdvwxkpp.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hfpthk.cn/Article/details/gt2clzpvfvb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hnqzz.top/Article/details/gt2nbeqlamz.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.bjfxy.top/Article/details/gt2kusaqhnw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2blhosczc.html

Ruby: -> { puts "run" }.call
来源：http://dali.svipenyu.cn/Article/details/gt2dsbdnckc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ivvv.top/Article/details/gt2qncmkjnj.html

[C13] 类型声明 / 类型注解
来源：http://dali.jyoumei.cn/Article/details/gt2vfkcehun.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cheryme.top/Article/details/gt2lkciwsbl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.quarkkingdee.top/Article/details/gt2gvpamlmt.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.316326.xyz/Article/details/gt2zyhoxqev.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2monusqjc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gt2gfuyeucr.html

Go:   func add(a, b int) int
来源：http://dali.birdmap.top/Article/details/gt2evimopjk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sufxvd.cn/Article/details/gt2xytsdjbx.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ebtvizvy.html

[C14] 泛型函数
来源：http://dali.guannengcc.top/Article/details/gt2nuizqbpg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yueranfly.top/Article/details/gt2ybhkmfjk.html

PHP:  // 无泛型
来源：http://dali.yuxming.cn/Article/details/gt2nktokwfd.html

JS:   // 无泛型
来源：http://dali.chenzaomai.com/Article/details/gt2kxgzzfhc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.tian-w.cn/Article/details/gt2cjpbgqek.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.dashuyun.cn/Article/details/gt2cbdkswmh.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rkazbgql.html

Ruby: # 无泛型
来源：http://dali.xinyue.icu/Article/details/gt2aahvjdnx.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.pycfn.com/Article/details/gt2nbcwtdgs.html

[C15] 解构 / 展开参数
来源：http://dali.guowangkeji.top/Article/details/gt2nqlhfgfj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jqgufenzy.top/Article/details/gt2jgwuhqdr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhoulong.xyz/Article/details/gt2ureefvbp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jiagoushi.top/Article/details/gt2vtwpnbfq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.snrcjt.cn/Article/details/gt2tvjttowh.html

Java: // 无解构
来源：http://dali.hongshengwenyu.top/Article/details/gt2xjhspcqb.html

Go:   // 无解构
来源：http://dali.316326.xyz/Article/details/gt2bjzuqqfs.html

Ruby: a, b = pair
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hueicngv.html

C#:   var (a, b) = pair;
来源：http://dali.shuidangran.top/Article/details/gt2hqtkmbtr.html

[C16] 函数 / 方法重载
来源：http://dali.redwolf501.top/Article/details/gt2mddanunk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.pengpengdd.cyou/Article/details/gt2ckstmmii.html

PHP:  // 无重载
来源：http://dali.shuidangran.top/Article/details/gt2ksyijyht.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhixingplan.top/Article/details/gt2bbxlxdmc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zmyxlutb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.fzhhl.top/Article/details/gt2kvawiflj.html

Go:   // 无重载：用不同函数名
来源：http://dali.hongshengwenyu.top/Article/details/gt2yuapwxbq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ehwqpu.com/Article/details/gt2svahcpxa.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jinqigufen.top/Article/details/gt2basuatan.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2nnrdsbum.html

D. 数组 / 列表 / 集合
来源：http://dali.chenlongwang.top/Article/details/gt2hispitmq.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2jnymxxya.html

[D01] 创建数组 / 列表
来源：http://dali.nwbrower.top/Article/details/gt2xijcxudw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cdnleiting.top/Article/details/gt2boaghmnt.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.sweek.top/Article/details/gt2nyhehdhv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iuuljyef.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xuetiantiany.cn/Article/details/gt2cbimurbg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhixingplan.top/Article/details/gt2uzhnvjwa.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.9152youxi.cn/Article/details/gt2xsxwbfqx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yongpay.top/Article/details/gt2vcpiessa.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.iojbl.cn/Article/details/gt2itxkytjx.html

[D02] 追加元素到末尾
来源：http://dali.cdnleiting.top/Article/details/gt2kpkcphjh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.svipenyu.cn/Article/details/gt2elamzvqk.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.birdmap.top/Article/details/gt2vflxmusq.html

JS:   arr.push(4);
来源：http://dali.dashuyun.cn/Article/details/gt2fymsfkqp.html

TS:   arr.push(4);
来源：http://dali.aibaodan.cn/Article/details/gt2wtixtkfp.html

Java: list.add(4);
来源：http://dali.meibo888.top/Article/details/gt2rlxmnucl.html

Go:   arr = append(arr, 4)
来源：http://dali.dashuyun.cn/Article/details/gt2ocfiinsa.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xuetiantiany.cn/Article/details/gt2gvgqnlfs.html

C#:   list.Add(4);
来源：http://dali.andypj.xyz/Article/details/gt2jisatrao.html

[D03] 在指定位置插入元素
来源：http://dali.ydzc1.top/Article/details/gt2cvoklvux.html

Py:   arr.insert(0, 0)
来源：http://dali.jqgfzy.top/Article/details/gt2praqrsbh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.smart0.xyz/Article/details/gt2okvdqeff.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.dianchejie.cn/Article/details/gt2psdqulep.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shzxlz.cn/Article/details/gt2qjtxeajs.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcekazer.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.daxiang520.top/Article/details/gt2trtcpjgh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.fzhhl.top/Article/details/gt2pgbxlddz.html

C#:   list.Insert(0, 0);
来源：http://dali.gzhubu.top/Article/details/gt2njikuujc.html

[D04] 删除元素
来源：http://dali.yuanzhike.top/Article/details/gt2uwpwngsn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hywenlv.cn/Article/details/gt2gijrczle.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.svipenyu.cn/Article/details/gt2wmjcqvmj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.meibo888.top/Article/details/gt2wmcqjboy.html

TS:   arr.splice(0, 1);
来源：http://dali.hnqzz.top/Article/details/gt2ucujcdib.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ehwqpu.com/Article/details/gt2appbvcjj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhixingplan.top/Article/details/gt2uvhvfqce.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.9152youxi.cn/Article/details/gt2owxkgxzc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.guannengcc.top/Article/details/gt2ocodszkm.html

[D05] 访问与修改元素
来源：http://dali.sxryk.cn/Article/details/gt2tosnxuup.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sufxvd.cn/Article/details/gt2ukdqytjp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.tanke756.top/Article/details/gt2pfhegmik.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.wangdashe.top/Article/details/gt2luadmkhz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nlfxpybz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hysaishi.cn/Article/details/gt2tunlmeqs.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ppjwa.cn/Article/details/gt2lefuapjh.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.meibo888.top/Article/details/gt2myhkvwna.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jiagoushi.top/Article/details/gt2fdiiisfh.html

[D06] 数组长度
来源：http://dali.vqdsnc.cn/Article/details/gt2gorfnhcf.html

Py:   len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2jebkabzk.html

PHP:  count($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vfzqqvhb.html

JS:   arr.length
来源：http://dali.hnqzz.top/Article/details/gt2libgrvpy.html

TS:   arr.length
来源：http://dali.zhengqikj.top/Article/details/gt2qwjoqdsj.html

Java: list.size();
来源：http://dali.xuetiantiany.cn/Article/details/gt2dsxvmzpk.html

Go:   len(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eaxswrek.html

Ruby: arr.length; arr.size
来源：http://dali.wangshuangyany.cn/Article/details/gt2tmycatgs.html

C#:   list.Count;
来源：http://dali.hysaishi.cn/Article/details/gt2hahfbdfu.html

[D07] 切片 / 取子数组
来源：http://dali.wangdashe.top/Article/details/gt2rwkafkgx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.chenlongwang.top/Article/details/gt2mowtslor.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xinyue.icu/Article/details/gt2gexfiqxc.html

JS:   arr.slice(1, 4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tbxtruek.html

TS:   arr.slice(1, 4);
来源：http://dali.svipenyu.cn/Article/details/gt2gqdgxudf.html

Java: list.subList(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gt2vpdzcdhd.html

Go:   arr[1:4]
来源：http://dali.pycfn.com/Article/details/gt2ygybptel.html

Ruby: arr[1, 3]
来源：http://dali.yj20258888.top/Article/details/gt2ksmncmwt.html

C#:   list.GetRange(1, 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2urvnzjuv.html

[D08] 合并两个数组
来源：http://dali.svipenyu.cn/Article/details/gt2kquuxkha.html

Py:   a + b;  a.extend(b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bgbboyta.html

PHP:  array_merge($a, $b);
来源：http://dali.vqdsnc.cn/Article/details/gt2jgixsxfq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yuanzhike.top/Article/details/gt2tdavmebk.html

TS:   [...a, ...b];
来源：http://dali.birdmap.top/Article/details/gt2hxgmpunx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.meibo888.top/Article/details/gt2oohuvspt.html

Go:   append(a, b...)
来源：http://dali.snrcjt.cn/Article/details/gt2fwelwruu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yj202588.top/Article/details/gt2suxukclh.html

C#:   a.Concat(b).ToList()
来源：http://dali.yj20258888.top/Article/details/gt2giuglqdu.html

[D09] 排序（升序）
来源：http://dali.jyoumei.cn/Article/details/gt2nivriqfh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gvpgjjcs.html

PHP:  sort($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2tuckncmw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.havefunace.top/Article/details/gt2wifyitmx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jiagoushi.top/Article/details/gt2ccxmvpes.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.fzhhl.top/Article/details/gt2aomyxatx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2jicvbmps.html

Ruby: arr.sort
来源：http://dali.redwolf501.top/Article/details/gt2zsizedee.html

C#:   list.Sort();
来源：http://dali.zhoulong.xyz/Article/details/gt2qgubhgrv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ehwqpu.com/Article/details/gt2mkxfxsxy.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.kuanghao11.cn/Article/details/gt2tpbqycav.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wudvvwac.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenzaomai.com/Article/details/gt2ldwpgqth.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zdqjudy.top/Article/details/gt2jgdgqjwj.html


<!-- 参考信息 -->