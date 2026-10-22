代发 wailian999

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfrzgkfwy.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hywenlv.cn/Article/details/gtsrfozrwt.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zycfv.cn/Article/details/gtxhbueqck.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.hnqzz.top/Article/details/gtltcjsgnb.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yanxiufei.cn/Article/details/gtjjgdkxir.html

[B10] 遍历同时拿索引
来源：http://dali.jinqigufen.top/Article/details/gtmjdwdlsd.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhijiandao.cn/Article/details/gtkgkzikkj.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.shzxlz.cn/Article/details/gtgmbyktjb.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.ivvv.top/Article/details/gtvvmbzsxx.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shuidangran.top/Article/details/gtrldzzmed.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.nanxuanxn.top/Article/details/gthqxcaohr.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtibhlehjv.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hfpthk.cn/Article/details/gtyqiunfic.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.fzhhl.top/Article/details/gtcsstntax.html

[B11] 生成数字序列 / 区间
来源：http://dali.yvedp.cn/Article/details/gtqfjtbgmy.html

Py:   list(range(0, 10, 2))
来源：http://dali.dashuyun.cn/Article/details/gtzpbfhqou.html

PHP:  range(0, 10, 2);
来源：http://dali.ydzc1.top/Article/details/gtfvgmxdvn.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tanke756.top/Article/details/gtskuxrzbr.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yanxiufei.cn/Article/details/gtrdibptor.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yvedp.cn/Article/details/gtgykdsymx.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.cdnleiting.top/Article/details/gtmixjzgki.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinghuilouyu.cn/Article/details/gtcqxhfseu.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jqgufenzy.top/Article/details/gtcauxmgiw.html

[B12] 跳出多层循环
来源：http://dali.c1oappe.top/Article/details/gtnnvuqyhd.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.meibo888.top/Article/details/gthzehzisw.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.9152youxi.cn/Article/details/gtnmqmmrgy.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.c1oappe.top/Article/details/gtgprezeth.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hongshengwenyu.top/Article/details/gtadgyvwnf.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.birdmap.top/Article/details/gtwgzccvbl.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hywenlv.cn/Article/details/gtlwvdvcnu.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jinghuilouyu.cn/Article/details/gtqlxseicj.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.redwolf501.top/Article/details/gtsoauaywp.html

[B13] 判断是否为数字
来源：http://dali.shanyushiyangtech.top/Article/details/gtudkzrzni.html

Py:   isinstance(x, (int, float))
来源：http://dali.ehwqpu.com/Article/details/gtoacrjvht.html

PHP:  is_numeric($x)
来源：http://dali.zhoulong.xyz/Article/details/gtapcauhfs.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jiagoushi.top/Article/details/gtennwebhw.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yuxming.cn/Article/details/gtqfsqrtki.html

Java: x instanceof Number
来源：http://dali.svipenyu.cn/Article/details/gtwrpshtgt.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jinghuilouyu.cn/Article/details/gtsjksqhqr.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yongpay.top/Article/details/gtsojiztlv.html

C#:   x is int or double or decimal
来源：http://dali.yuxming.cn/Article/details/gthrjaxxgt.html

[B14] 判断值是否在集合内
来源：http://dali.yj202588.top/Article/details/gtsokovcej.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cqqwz.cn/Article/details/gthnbnkcym.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.c1oappe.top/Article/details/gtaaubnncj.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.pycfn.com/Article/details/gtvtyitxru.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.c1oappe.top/Article/details/gtztyexdql.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jqgfzy.top/Article/details/gtzbljkekw.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.mhx1999.top/Article/details/gtngtbvefc.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.tanke756.top/Article/details/gtfgcqnppj.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.tian-w.cn/Article/details/gtnccqlxfa.html

[B15] 布尔运算与取反
来源：http://dali.xuetiantiany.cn/Article/details/gtlkpbnuiq.html

Py:   a and b or not c
来源：http://dali.cqqwz.cn/Article/details/gtfbwnxiuu.html

PHP:  $a && $b || !$c
来源：http://dali.shzxlz.cn/Article/details/gtsaqgpkhd.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gtdcpsnqqe.html

TS:   a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gtucdsltxv.html

Java: a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gtalppwupt.html

Go:   a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gtjucpqphi.html

Ruby: a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gthiujxeoi.html

C#:   a && b || !c
来源：http://dali.xylfe.cn/Article/details/gtsqtsbqxp.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.guannengcc.top/Article/details/gtywjcevfi.html

Py:   if not data: return
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnylcvzsq.html

PHP:  if (!$data) { return; }
来源：http://dali.jinqigufen.top/Article/details/gtactcptgv.html

JS:   if (!data) return;
来源：http://dali.chenzaomai.com/Article/details/gtulnerbie.html

TS:   if (!data) return;
来源：http://dali.cucudq.cn/Article/details/gtwqwzbcya.html

Java: if (data == null) return;
来源：http://dali.hongshengwenyu.top/Article/details/gtuoowyash.html

Go:   if data == nil { return }
来源：http://dali.andypj.xyz/Article/details/gtpqsqguup.html

Ruby: return if data.nil?
来源：http://dali.gotoacloud.top/Article/details/gtbuggqiuz.html

C#:   if (data == null) return;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtydymttol.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gttwwbkbcq.html

C. 函数与作用域
来源：http://dali.yj20258.top/Article/details/gthttisdku.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtqbsjukzi.html

[C01] 定义函数
来源：http://dali.hfpthk.cn/Article/details/gtpnbnffpv.html

Py:   def add(a, b): return a + b
来源：http://dali.yueranfly.top/Article/details/gtwddexboe.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenzaomai.com/Article/details/gtnaurkrlu.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gtyszksbyw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpryxfzii.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtywpkpnzb.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.dashuyun.cn/Article/details/gtsbogusab.html

Ruby: def add(a, b); a + b; end
来源：http://dali.aibaodan.cn/Article/details/gtdkyxtylv.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gtzgntldep.html

[C02] 默认参数
来源：http://dali.meibo888.top/Article/details/gtqcliqsqe.html

Py:   def greet(name="World"): return name
来源：http://dali.zhiwuduotai.top/Article/details/gticddxvei.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yuanzhike.top/Article/details/gtzkrhqgew.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtzskctvin.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gtuhytvawg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yuxming.cn/Article/details/gtnlsfvosz.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.0kj1m.cn/Article/details/gtfeibhctf.html

Ruby: def greet(name = "World") = name
来源：http://dali.hfpthk.cn/Article/details/gtwocnizlh.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xuetiantiany.cn/Article/details/gtxbxylell.html

[C03] 可变参数
来源：http://dali.chenjidiqi.icu/Article/details/gtorbrapll.html

Py:   def total(*args): return sum(args)
来源：http://dali.nanxuanxn.top/Article/details/gtbqocxdvd.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xuetiantiany.cn/Article/details/gtrainblfv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.daxiang520.top/Article/details/gthwitxawu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj202588.top/Article/details/gtykaaerao.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gtvyvsbjsv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.bjfxy.top/Article/details/gthokmzvwl.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hnxiangtu.top/Article/details/gtfstxlvru.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.vqdsnc.cn/Article/details/gtnlmfrian.html

[C04] 命名参数 / 关键字参数
来源：http://dali.daxiang520.top/Article/details/gtuefrbvqa.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsmdxltmq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.fengsongda.top/Article/details/gttpjmjzvw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xinyue.icu/Article/details/gtdmggoczj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.guannengcc.top/Article/details/gttcifsidw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.9152youxi.cn/Article/details/gttqcrccnn.html

Go:   // 无：用配置结构体参数
来源：http://dali.vqdsnc.cn/Article/details/gtesccqrhe.html

Ruby: f(a: 1, b: 2)
来源：http://dali.dashuyun.cn/Article/details/gttwvxniev.html

C#:   f(a: 1, b: 2)
来源：http://dali.tianlin.xyz/Article/details/gtzshjuwkg.html

[C05] 返回多个值
来源：http://dali.zhengqikj.top/Article/details/gtjeacodkv.html

Py:   return a, b
来源：http://dali.shuidangran.top/Article/details/gtmkbkfijh.html

PHP:  return [$a, $b];
来源：http://dali.wangshuangyany.cn/Article/details/gthyphhqrg.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqexlfffd.html

TS:   return { a, b };
来源：http://dali.hysaishi.cn/Article/details/gtwlczkqbb.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.redwolf501.top/Article/details/gteyeyahhz.html

Go:   return a, b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnvqzakbc.html

Ruby: return a, b
来源：http://dali.kuanghao11.cn/Article/details/gtocwgycip.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shzxlz.cn/Article/details/gtrqgdxmax.html

[C06] 匿名函数 / lambda
来源：http://dali.kuanghao11.cn/Article/details/gtigwzazvy.html

Py:   square = lambda x: x * x
来源：http://dali.daria6918.cn/Article/details/gtsajuxyfl.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.mhx1999.top/Article/details/gtcylzhsbm.html

JS:   const square = x => x * x;
来源：http://dali.snrcjt.cn/Article/details/gtqhfpmjkw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.kuanghao11.cn/Article/details/gtowmseotd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ybcxt.top/Article/details/gtqrevhvtm.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yuanzhike.top/Article/details/gtghagvwpt.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jinqigfzy.top/Article/details/gtmezamybt.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jqgufenzy.top/Article/details/gtdxaxnyfn.html

[C07] 把函数作为参数传入
来源：http://dali.fzhhl.top/Article/details/gtikeokbif.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.chenlongwang.top/Article/details/gtpzuqsgoa.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zdqjudy.top/Article/details/gtvllptkgc.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yueranfly.top/Article/details/gtchcfgfgc.html

TS:   arr.map(String)
来源：http://dali.tian-w.cn/Article/details/gtomzcjdhz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.meibo888.top/Article/details/gtsglyfmyd.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.0kj1m.cn/Article/details/gtgjhtxbzr.html

Ruby: arr.map(&:upcase)
来源：http://dali.mhx1999.top/Article/details/gttjjmxwnt.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhixingplan.top/Article/details/gtfldjdluc.html

[C08] 闭包
来源：http://dali.andypj.xyz/Article/details/gtnwvwdnxh.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.nanxuanxn.top/Article/details/gtkumxjjvn.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xuanzx.com/Article/details/gtxlvgsawn.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhongyouzk.top/Article/details/gtwidbzhws.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.kuanghao11.cn/Article/details/gtoivbijvr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.chenzaomai.com/Article/details/gtcvzlefuy.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.daria6918.cn/Article/details/gtxjazxurl.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.aibaodan.cn/Article/details/gtupdveket.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.fengsongda.top/Article/details/gttbxlpgys.html

[C09] 递归
来源：http://dali.zhengqikj.top/Article/details/gtqklyqiib.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hnxiangtu.top/Article/details/gtizlwftej.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hammf.cn/Article/details/gtgfcvlgnj.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigufen.top/Article/details/gtcravgkdy.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shanyushiyangtech.top/Article/details/gtluioeqly.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.sysykeji.top/Article/details/gtyurezdkp.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sweek.top/Article/details/gtlibnjzpv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jqgufenzy.top/Article/details/gtdiwanefo.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jqgufenzy.top/Article/details/gtceuqbjss.html

[C10] 变量作用域
来源：http://dali.feifeiyinyue.top/Article/details/gtuvoxzwlb.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.shangyingyoupin.top/Article/details/gtdeqyjfee.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jianghu66.top/Article/details/gtwmnmmwzd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.kuanghao11.cn/Article/details/gthesdpocn.html

TS:   同 JS
来源：http://dali.yonumen.top/Article/details/gtqjcvbawz.html

Java: 方法内为块级作用域
来源：http://dali.chenzaomai.com/Article/details/gtabllpssf.html

Go:   花括号块级作用域
来源：http://dali.mhx1999.top/Article/details/gtdprzycjk.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jinqigufen.top/Article/details/gtbcnclzqa.html

C#:   块级作用域
来源：http://dali.aibaodan.cn/Article/details/gtholvgcog.html

[C11] 模块导入与导出
来源：http://dali.nwbrower.top/Article/details/gteejwxtvm.html

Py:   from module import func
来源：http://dali.dashuyun.cn/Article/details/gtdwmuqneo.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zycfv.cn/Article/details/gteihzirvk.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.fengsongda.top/Article/details/gteunhqcli.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.gzhubu.top/Article/details/gtwijeazel.html

Java: import java.util.List;
来源：http://dali.sxryk.cn/Article/details/gttkcbefck.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cucudq.cn/Article/details/gtcxsbvbru.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xinyue.icu/Article/details/gtbentsndx.html

C#:   using System.Text;
来源：http://dali.wangdashe.top/Article/details/gtdzvmywgd.html

[C12] 立即执行函数 IIFE
来源：http://dali.jiagoushi.top/Article/details/gtvjgzjvoc.html

Py:   (lambda: print("run"))()
来源：http://dali.cqqwz.cn/Article/details/gtnjuzqnfw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hysaishi.cn/Article/details/gtzsratxbs.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ppjwa.cn/Article/details/gtwjiwdzvv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfepogtip.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hfpthk.cn/Article/details/gtlojkhblw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.kuanghao11.cn/Article/details/gtoyujpzgr.html

Ruby: -> { puts "run" }.call
来源：http://dali.zdqjudy.top/Article/details/gtreowyrsc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hywenlv.cn/Article/details/gtpotczrwv.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhoulong.xyz/Article/details/gtvddgybbj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.aizwys.cn/Article/details/gtulweaoyj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sufxvd.cn/Article/details/gtomwxljmw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.pycfn.com/Article/details/gtussplmmv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gtgdplrdyq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gtibmanenz.html

Go:   func add(a, b int) int
来源：http://dali.xuanzx.com/Article/details/gtzcoqcquy.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.svipenyu.cn/Article/details/gtknxnngmj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.pengpengdd.cyou/Article/details/gtjwdgmrui.html

[C14] 泛型函数
来源：http://dali.iojbl.cn/Article/details/gtliixvgrp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.nwbrower.top/Article/details/gtsmcxqlwe.html

PHP:  // 无泛型
来源：http://dali.jinqigufen.top/Article/details/gtmngalenm.html

JS:   // 无泛型
来源：http://dali.yuanzhike.top/Article/details/gtxznkucxo.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.guowangkeji.top/Article/details/gtsvhbzapi.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.c1oappe.top/Article/details/gthlaawzzg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoelozuxn.html

Ruby: # 无泛型
来源：http://dali.hongshengwenyu.top/Article/details/gtdqovnhwn.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.tianlin.xyz/Article/details/gtxelsbmax.html

[C15] 解构 / 展开参数
来源：http://dali.ehwqpu.com/Article/details/gtzilfelch.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shangyingyoupin.top/Article/details/gthudixgpu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.feifeiyinyue.top/Article/details/gtzwnccmvu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ehwqpu.com/Article/details/gtojaknsds.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinqigufen.top/Article/details/gtdhhcwfxx.html

Java: // 无解构
来源：http://dali.yj202588.top/Article/details/gtyozcjwdr.html

Go:   // 无解构
来源：http://dali.havefunace.top/Article/details/gtbqnfxihf.html

Ruby: a, b = pair
来源：http://dali.redwolf501.top/Article/details/gtqeicfdpm.html

C#:   var (a, b) = pair;
来源：http://dali.zdqjudy.top/Article/details/gtpuntfanv.html

[C16] 函数 / 方法重载
来源：http://dali.kuanghao11.cn/Article/details/gtuzvcgbyo.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hammf.cn/Article/details/gtybtuakiy.html

PHP:  // 无重载
来源：http://dali.daxiang520.top/Article/details/gttwswkpmy.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cdnleiting.top/Article/details/gttjaqhfsy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hnqzz.top/Article/details/gtnihiyzde.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.wangdashe.top/Article/details/gtiacrcnxz.html

Go:   // 无重载：用不同函数名
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcybgnsvq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.guowangkeji.top/Article/details/gtxvmglpyd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.quarkkingdee.top/Article/details/gtdlneqoiv.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtzttqinnn.html

D. 数组 / 列表 / 集合
来源：http://dali.yueranfly.top/Article/details/gttuusacqo.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtrstmvsxm.html

[D01] 创建数组 / 列表
来源：http://dali.hnxiangtu.top/Article/details/gtyddxmana.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.meibo888.top/Article/details/gtgwluaszm.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhengqikj.top/Article/details/gtvjtqrcah.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.birdmap.top/Article/details/gtwceilsfx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.birdmap.top/Article/details/gtykqznqbp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xuetiantiany.cn/Article/details/gtxictpwqw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gaohongyu789.top/Article/details/gtnnlzmaul.html

Ruby: arr = [1, 2, 3]
来源：http://dali.fzhhl.top/Article/details/gtbodcbaiz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jiagoushi.top/Article/details/gtfmallfms.html

[D02] 追加元素到末尾
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxagkxeh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shzxlz.cn/Article/details/gtmrugqlra.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zdqjudy.top/Article/details/gtkuoqpdxr.html

JS:   arr.push(4);
来源：http://dali.yj20258888.top/Article/details/gtqwqaryij.html

TS:   arr.push(4);
来源：http://dali.cheryme.top/Article/details/gtwjnngpib.html

Java: list.add(4);
来源：http://dali.nanxuanxn.top/Article/details/gtmsiiehgw.html

Go:   arr = append(arr, 4)
来源：http://dali.hongshengwenyu.top/Article/details/gtaxxfhcss.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.chenlongwang.top/Article/details/gtjnylecwm.html

C#:   list.Add(4);
来源：http://dali.guannengcc.top/Article/details/gtxqoouzfk.html

[D03] 在指定位置插入元素
来源：http://dali.redwolf501.top/Article/details/gttkcgswkg.html

Py:   arr.insert(0, 0)
来源：http://dali.sxryk.cn/Article/details/gtoyvnnvvu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jqgfzy.top/Article/details/gtcegntgvl.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yj20258.top/Article/details/gtkzqlwjzz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthsyyfxai.html

Java: list.add(0, 0);
来源：http://dali.andypj.xyz/Article/details/gtxcqzzxoq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sxryk.cn/Article/details/gtgqjotpsy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.sufxvd.cn/Article/details/gtlqwdwiwm.html

C#:   list.Insert(0, 0);
来源：http://dali.gotoacloud.top/Article/details/gtrdgyqfes.html

[D04] 删除元素
来源：http://dali.zhoulong.xyz/Article/details/gtckzhpzwx.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hysaishi.cn/Article/details/gtfgoeicfi.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.fzhhl.top/Article/details/gthmpceblx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shangyingyoupin.top/Article/details/gtpmoixjba.html

TS:   arr.splice(0, 1);
来源：http://dali.0kj1m.cn/Article/details/gtmuhnpwtt.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhixingplan.top/Article/details/gtcbmgxhkr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yongpay.top/Article/details/gtamrtutya.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.sufxvd.cn/Article/details/gtostkldcz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.redwolf501.top/Article/details/gtxzahgcxj.html

[D05] 访问与修改元素
来源：http://dali.chenjidiqi.icu/Article/details/gtbaincyeo.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.guannengcc.top/Article/details/gtisalblwz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yanxiufei.cn/Article/details/gtziypxdtq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.feifeiyinyue.top/Article/details/gthuoorupy.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.c1oappe.top/Article/details/gtiqnehtay.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.pengpengdd.cyou/Article/details/gtxmlgarei.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.redwolf501.top/Article/details/gtblgoykaj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.feifeiyinyue.top/Article/details/gtoeghxjpq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.snrcjt.cn/Article/details/gtzndrsnsi.html

[D06] 数组长度
来源：http://dali.yanxiufei.cn/Article/details/gtetkitorv.html

Py:   len(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtrbwroqhp.html

PHP:  count($arr);
来源：http://dali.ivvv.top/Article/details/gtvmmuakiw.html

JS:   arr.length
来源：http://dali.chenjidiqi.icu/Article/details/gtamyezjbm.html

TS:   arr.length
来源：http://dali.dashuyun.cn/Article/details/gtthiorqii.html

Java: list.size();
来源：http://dali.pycfn.com/Article/details/gtctsefujl.html

Go:   len(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtphpivfvx.html

Ruby: arr.length; arr.size
来源：http://dali.jianghu66.top/Article/details/gthrsjdbzn.html

C#:   list.Count;
来源：http://dali.sxryk.cn/Article/details/gtriaklole.html

[D07] 切片 / 取子数组
来源：http://dali.c1oappe.top/Article/details/gtsvnsdiza.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yueranfly.top/Article/details/gtdfcxuysn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sweek.top/Article/details/gtxkzkoezo.html

JS:   arr.slice(1, 4);
来源：http://dali.quarkkingdee.top/Article/details/gtfalxbbkt.html

TS:   arr.slice(1, 4);
来源：http://dali.haohaochexian.top/Article/details/gtasalummm.html

Java: list.subList(1, 4);
来源：http://dali.zhiwuduotai.top/Article/details/gtiflqhbup.html

Go:   arr[1:4]
来源：http://dali.sufxvd.cn/Article/details/gtbcdaxqdk.html

Ruby: arr[1, 3]
来源：http://dali.yanxiufei.cn/Article/details/gtwndzhigx.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinqigufen.top/Article/details/gteyfwrlgd.html

[D08] 合并两个数组
来源：http://dali.jyoumei.cn/Article/details/gtvjfxggbm.html

Py:   a + b;  a.extend(b)
来源：http://dali.cdnleiting.top/Article/details/gtmgbtakgc.html

PHP:  array_merge($a, $b);
来源：http://dali.meibo888.top/Article/details/gtjlkjsuls.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.gzhubu.top/Article/details/gtjhkbdbpx.html

TS:   [...a, ...b];
来源：http://dali.zhoulong.xyz/Article/details/gtyedlkvgb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yanxiufei.cn/Article/details/gtogpqcpfq.html

Go:   append(a, b...)
来源：http://dali.hysaishi.cn/Article/details/gtrttjgebl.html

Ruby: a + b;  a.concat(b)
来源：http://dali.aibaodan.cn/Article/details/gtyqbutzex.html

C#:   a.Concat(b).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtbnjhaorm.html

[D09] 排序（升序）
来源：http://dali.andypj.xyz/Article/details/gtedsudtjr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.snrcjt.cn/Article/details/gtfolwltei.html

PHP:  sort($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtwgreilsn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hnxiangtu.top/Article/details/gttvrcqcqp.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xinyue.icu/Article/details/gtbhbdhaii.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.bjfxy.top/Article/details/gtwhbcvymf.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.9152youxi.cn/Article/details/gtzctunutz.html

Ruby: arr.sort
来源：http://dali.yonumen.top/Article/details/gtcgwnqecu.html

C#:   list.Sort();
来源：http://dali.sweek.top/Article/details/gtdxxpleaw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.tanke756.top/Article/details/gtwmadhfig.html


<!-- 参考信息 -->