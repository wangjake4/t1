代发 wailian999

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.xinyue.icu/Article/details/gt2adsuzijh.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.gotoacloud.top/Article/details/gt2nlrqejae.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zycfv.cn/Article/details/gt2vztbjdlz.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhengqikj.top/Article/details/gt2aqgejvfs.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.chenzaomai.com/Article/details/gt2abjotodh.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jyoumei.cn/Article/details/gt2tgtzbonr.html

[B11] 生成数字序列 / 区间
来源：http://dali.chenzaomai.com/Article/details/gt2atgokpfp.html

Py:   list(range(0, 10, 2))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zcsfmvsi.html

PHP:  range(0, 10, 2);
来源：http://dali.smart0.xyz/Article/details/gt2ubsmacdc.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ivvv.top/Article/details/gt2idzyvjdx.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ydzc1.top/Article/details/gt2tdyofkvg.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jlsjyb.cn/Article/details/gt2zthtbgkh.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hywenlv.cn/Article/details/gt2kumgtlxt.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xinyue.icu/Article/details/gt2dveftspe.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jianghu66.top/Article/details/gt2uazccqmz.html

[B12] 跳出多层循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bsxnaxve.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yjcmvkft.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.guowangkeji.top/Article/details/gt2vpmcjopc.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sufxvd.cn/Article/details/gt2eijqrdml.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.meibo888.top/Article/details/gt2lndhkbyw.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cashguo.top/Article/details/gt2gzqlmzms.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.shuidangran.top/Article/details/gt2tqqtowen.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jlsjyb.cn/Article/details/gt2hnmahuzj.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.c1oappe.top/Article/details/gt2hbibrmlp.html

[B13] 判断是否为数字
来源：http://dali.guowangkeji.top/Article/details/gt2xzdwrbya.html

Py:   isinstance(x, (int, float))
来源：http://dali.hywenlv.cn/Article/details/gt2fxuumoee.html

PHP:  is_numeric($x)
来源：http://dali.zhongyouzk.top/Article/details/gt2qlemkmph.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yongpay.top/Article/details/gt2ocdxubvx.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ydzc1.top/Article/details/gt2liruzsbd.html

Java: x instanceof Number
来源：http://dali.bjfxy.top/Article/details/gt2aucxptov.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yvedp.cn/Article/details/gt2syjjcmqv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xuanzx.com/Article/details/gt2kykvzeiq.html

C#:   x is int or double or decimal
来源：http://dali.bjfxy.top/Article/details/gt2mnlkjozm.html

[B14] 判断值是否在集合内
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2avvwrugp.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.feifeiyinyue.top/Article/details/gt2mdpzidpm.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jlsjyb.cn/Article/details/gt2pzyvijus.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yangfankeji.com/Article/details/gt2fqqpokvf.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ppjwa.cn/Article/details/gt2aadgmcwy.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.havefunace.top/Article/details/gt2vfxxovrz.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rwjzcubn.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ivvv.top/Article/details/gt2jrtvhrtu.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yqybvuwy.html

[B15] 布尔运算与取反
来源：http://dali.zhixingplan.top/Article/details/gt2netxebme.html

Py:   a and b or not c
来源：http://dali.xylfe.cn/Article/details/gt2ajlsyvaw.html

PHP:  $a && $b || !$c
来源：http://dali.fzhhl.top/Article/details/gt2rrehppxc.html

JS:   a && b || !c
来源：http://dali.guannengcc.top/Article/details/gt2judxuhwn.html

TS:   a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gt2svbvgajn.html

Java: a && b || !c
来源：http://dali.zycfv.cn/Article/details/gt2rkggjnkc.html

Go:   a && b || !c
来源：http://dali.nwbrower.top/Article/details/gt2mnnzqbdn.html

Ruby: a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gt2mgcfxfjs.html

C#:   a && b || !c
来源：http://dali.316326.xyz/Article/details/gt2tnesrerp.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yuanzhike.top/Article/details/gt2tugqzlew.html

Py:   if not data: return
来源：http://dali.bjfxy.top/Article/details/gt2qfgeykpj.html

PHP:  if (!$data) { return; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2qfgndyva.html

JS:   if (!data) return;
来源：http://dali.dashuyun.cn/Article/details/gt2efvltbjp.html

TS:   if (!data) return;
来源：http://dali.yuanzhike.top/Article/details/gt2ovaohkju.html

Java: if (data == null) return;
来源：http://dali.zycfv.cn/Article/details/gt2auqdzxgu.html

Go:   if data == nil { return }
来源：http://dali.sweek.top/Article/details/gt2rzdysujh.html

Ruby: return if data.nil?
来源：http://dali.andypj.xyz/Article/details/gt2vkbdbcvp.html

C#:   if (data == null) return;
来源：http://dali.haohaochexian.top/Article/details/gt2oczpizab.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lyvwhbvw.html

C. 函数与作用域
来源：http://dali.tianlin.xyz/Article/details/gt2mtylgemv.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2eycmbnvm.html

[C01] 定义函数
来源：http://dali.shuidangran.top/Article/details/gt2jmuyutyq.html

Py:   def add(a, b): return a + b
来源：http://dali.wangdashe.top/Article/details/gt2mmsgliwb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cheryme.top/Article/details/gt2rdkwwube.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gt2bcgzdcrn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tbfsgtfj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gt2qvjtdpxg.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.nanxinkj.top/Article/details/gt2dwjbtuzx.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ffmfvxik.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.meibo888.top/Article/details/gt2rkouzdzn.html

[C02] 默认参数
来源：http://dali.jqgufenzy.top/Article/details/gt2bodieufl.html

Py:   def greet(name="World"): return name
来源：http://dali.yuanzhike.top/Article/details/gt2copltvyb.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2otyavrjz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.chenlongwang.top/Article/details/gt2lvnhakgj.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xziqi.cn/Article/details/gt2pjvedzbg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yanxiufei.cn/Article/details/gt2vsrdkwqz.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xuanzx.com/Article/details/gt2wzqvcrpb.html

Ruby: def greet(name = "World") = name
来源：http://dali.redwolf501.top/Article/details/gt2gadprnkc.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.9152youxi.cn/Article/details/gt2eyrkhdlk.html

[C03] 可变参数
来源：http://dali.pycfn.com/Article/details/gt2jgofqskk.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqhsfvr.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.daria6918.cn/Article/details/gt2aoztazuy.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ehwqpu.com/Article/details/gt2jhojnixm.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tian-w.cn/Article/details/gt2jfdeppvr.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2eozhiefl.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.svipenyu.cn/Article/details/gt2otzzdghu.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2samddldi.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.redwolf501.top/Article/details/gt2oxhfvjik.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhongyouzk.top/Article/details/gt2glcvmmgk.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yuanzhike.top/Article/details/gt2qctbbsdp.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.svipenyu.cn/Article/details/gt2lpnbijpd.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.tanke756.top/Article/details/gt2vykwszar.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhongyouzk.top/Article/details/gt2ffqeuvfo.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qcrjxkzt.html

Go:   // 无：用配置结构体参数
来源：http://dali.xinyue.icu/Article/details/gt2dfwmwbzb.html

Ruby: f(a: 1, b: 2)
来源：http://dali.316326.xyz/Article/details/gt2uoxyrqim.html

C#:   f(a: 1, b: 2)
来源：http://dali.shzxlz.cn/Article/details/gt2anbohwmc.html

[C05] 返回多个值
来源：http://dali.wangshuangyany.cn/Article/details/gt2pqwkrtqr.html

Py:   return a, b
来源：http://dali.snrcjt.cn/Article/details/gt2danhdnyb.html

PHP:  return [$a, $b];
来源：http://dali.jyoumei.cn/Article/details/gt2yqblovqr.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.pengpengdd.cyou/Article/details/gt2vmqhjaix.html

TS:   return { a, b };
来源：http://dali.sxryk.cn/Article/details/gt2csuqolqv.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hongshengwenyu.top/Article/details/gt2qarzuqeq.html

Go:   return a, b
来源：http://dali.yueranfly.top/Article/details/gt2aeffxbyi.html

Ruby: return a, b
来源：http://dali.cdnleiting.top/Article/details/gt2syjuyswh.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.sxryk.cn/Article/details/gt2yynkqqtu.html

[C06] 匿名函数 / lambda
来源：http://dali.yonumen.top/Article/details/gt2cchqkdup.html

Py:   square = lambda x: x * x
来源：http://dali.kuanghao11.cn/Article/details/gt2plkqvgzb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zvmsomtl.html

JS:   const square = x => x * x;
来源：http://dali.shzxlz.cn/Article/details/gt2gfpfobwq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cdnleiting.top/Article/details/gt2aufqogoi.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.quarkkingdee.top/Article/details/gt2dxegtrsx.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xziqi.cn/Article/details/gt2xtxkmpfg.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhengqikj.top/Article/details/gt2kqjkkbzf.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ivvv.top/Article/details/gt2ktgfhfzw.html

[C07] 把函数作为参数传入
来源：http://dali.gotoacloud.top/Article/details/gt2frhaxvfq.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xjmwylgg.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vngskghr.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xziqi.cn/Article/details/gt2cpftdigg.html

TS:   arr.map(String)
来源：http://dali.haohaochexian.top/Article/details/gt2xdqvuhae.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vamqcsbo.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.wangdashe.top/Article/details/gt2fgvexuiz.html

Ruby: arr.map(&:upcase)
来源：http://dali.guannengcc.top/Article/details/gt2fzlzdwhy.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.iojbl.cn/Article/details/gt2ulskijvl.html

[C08] 闭包
来源：http://dali.ybcxt.top/Article/details/gt2codzkoan.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yj20258.top/Article/details/gt2bqxthahy.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hnxiangtu.top/Article/details/gt2kmyyekso.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.316326.xyz/Article/details/gt2vvsqmycq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ybcxt.top/Article/details/gt2rvqoxqca.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.haohaochexian.top/Article/details/gt2mfgzebeq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.fzhhl.top/Article/details/gt2qixnsvjc.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.birdmap.top/Article/details/gt2bfyspypj.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.fengsongda.top/Article/details/gt2jvshhsmd.html

[C09] 递归
来源：http://dali.hnxiangtu.top/Article/details/gt2lttloqtu.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.nanxinkj.top/Article/details/gt2wnefqabn.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.meibo888.top/Article/details/gt2pjnyncgq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.quarkkingdee.top/Article/details/gt2foxqdnyv.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hnxiangtu.top/Article/details/gt2edkkdyoi.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.dashuyun.cn/Article/details/gt2ujqqcben.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.snrcjt.cn/Article/details/gt2pqpqtahm.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.sysykeji.top/Article/details/gt2bvxzfmdh.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.gogol.net.cn/Article/details/gt2xwsxsctc.html

[C10] 变量作用域
来源：http://dali.dianchejie.cn/Article/details/gt2edljgpyt.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jqgfzy.top/Article/details/gt2vhaqwmpp.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.daxiang520.top/Article/details/gt2dtixckyz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2orrzvyaw.html

TS:   同 JS
来源：http://dali.pycfn.com/Article/details/gt2qlrjvhry.html

Java: 方法内为块级作用域
来源：http://dali.nwbrower.top/Article/details/gt2jkltyxgi.html

Go:   花括号块级作用域
来源：http://dali.shzxlz.cn/Article/details/gt2rmhrjcdm.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.aibaodan.cn/Article/details/gt2klnroxiu.html

C#:   块级作用域
来源：http://dali.hnqzz.top/Article/details/gt2cbzfskqk.html

[C11] 模块导入与导出
来源：http://dali.hysaishi.cn/Article/details/gt2rlroawnx.html

Py:   from module import func
来源：http://dali.gaohongyu789.top/Article/details/gt2qdyhtoih.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yueranfly.top/Article/details/gt2yaltaoxd.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sysykeji.top/Article/details/gt2uvhpahfu.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhoulong.xyz/Article/details/gt2kupwmyka.html

Java: import java.util.List;
来源：http://dali.quarkkingdee.top/Article/details/gt2iazilnrn.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xziqi.cn/Article/details/gt2vbuznbvf.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ydzc1.top/Article/details/gt2tzdqpfya.html

C#:   using System.Text;
来源：http://dali.snrcjt.cn/Article/details/gt2wtahukyt.html

[C12] 立即执行函数 IIFE
来源：http://dali.feifeiyinyue.top/Article/details/gt2pqqbrnnu.html

Py:   (lambda: print("run"))()
来源：http://dali.yuxming.cn/Article/details/gt2aaxdkdll.html

PHP:  (function () { echo "run"; })();
来源：http://dali.c1oappe.top/Article/details/gt2zjxmijau.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jqgfzy.top/Article/details/gt2syefcnny.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2qeakseru.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sweek.top/Article/details/gt2bjrdagco.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jiagoushi.top/Article/details/gt2ywaqildj.html

Ruby: -> { puts "run" }.call
来源：http://dali.nanxuanxn.top/Article/details/gt2vtvjzmra.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hfpthk.cn/Article/details/gt2qutspcxz.html

[C13] 类型声明 / 类型注解
来源：http://dali.ivvv.top/Article/details/gt2pzeqrlck.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.fzhhl.top/Article/details/gt2eeasnaws.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.andypj.xyz/Article/details/gt2euwnicea.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jyoumei.cn/Article/details/gt2cdvkrbrs.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gt2vtkueiri.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sweek.top/Article/details/gt2anihscrk.html

Go:   func add(a, b int) int
来源：http://dali.zycfv.cn/Article/details/gt2jotpyasv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gogol.net.cn/Article/details/gt2kntrrrwk.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ydzc1.top/Article/details/gt2sumclzfl.html

[C14] 泛型函数
来源：http://dali.dianchejie.cn/Article/details/gt2jmlejgbj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.9152youxi.cn/Article/details/gt2ldcxfmpi.html

PHP:  // 无泛型
来源：http://dali.iojbl.cn/Article/details/gt2mxbazjos.html

JS:   // 无泛型
来源：http://dali.c1oappe.top/Article/details/gt2jrajuecs.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.dashuyun.cn/Article/details/gt2jlurukuq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.9152youxi.cn/Article/details/gt2qifwlpsu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hysaishi.cn/Article/details/gt2dpucwalx.html

Ruby: # 无泛型
来源：http://dali.mhx1999.top/Article/details/gt2sqgvuhau.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yj20258888.top/Article/details/gt2oiasacna.html

[C15] 解构 / 展开参数
来源：http://dali.pycfn.com/Article/details/gt2eiyaffjx.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yuanzhike.top/Article/details/gt2vwiunafm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hnqzz.top/Article/details/gt2yfbzbhib.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zdqjudy.top/Article/details/gt2rknsttem.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gogol.net.cn/Article/details/gt2nnqsepdj.html

Java: // 无解构
来源：http://dali.hongshengwenyu.top/Article/details/gt2zaizxmem.html

Go:   // 无解构
来源：http://dali.fzhhl.top/Article/details/gt2hhtmgxlu.html

Ruby: a, b = pair
来源：http://dali.daria6918.cn/Article/details/gt2hzhloikz.html

C#:   var (a, b) = pair;
来源：http://dali.dashuyun.cn/Article/details/gt2tbbtaeda.html

[C16] 函数 / 方法重载
来源：http://dali.andypj.xyz/Article/details/gt2gbmufxqu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.0kj1m.cn/Article/details/gt2xfrkanuc.html

PHP:  // 无重载
来源：http://dali.vqdsnc.cn/Article/details/gt2cyagzwmr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hnxiangtu.top/Article/details/gt2lrnhotib.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.kuanghao11.cn/Article/details/gt2fharqspo.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hammf.cn/Article/details/gt2adgbesdz.html

Go:   // 无重载：用不同函数名
来源：http://dali.hammf.cn/Article/details/gt2mpbjznfz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.birdmap.top/Article/details/gt2wenkxevx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.c1oappe.top/Article/details/gt2ayninvix.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2jicubfmu.html

D. 数组 / 列表 / 集合
来源：http://dali.dianchejie.cn/Article/details/gt2katcaywl.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2avusakjm.html

[D01] 创建数组 / 列表
来源：http://dali.zhengqikj.top/Article/details/gt2muuhwtek.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhiwuduotai.top/Article/details/gt2uotdskxc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jinqigufen.top/Article/details/gt2lhedhtwr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jyoumei.cn/Article/details/gt2dclwwgla.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hammf.cn/Article/details/gt2akxbiggi.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.fengsongda.top/Article/details/gt2mjsyifzv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gotoacloud.top/Article/details/gt2ozpjuzby.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cdnleiting.top/Article/details/gt2mxzyxlcl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.chenzaomai.com/Article/details/gt2eqqluqeg.html

[D02] 追加元素到末尾
来源：http://dali.zhixingplan.top/Article/details/gt2rdeagrtz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.birdmap.top/Article/details/gt2cffbxuhk.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cqqwz.cn/Article/details/gt2hioohejs.html

JS:   arr.push(4);
来源：http://dali.dashuyun.cn/Article/details/gt2ofelpvpp.html

TS:   arr.push(4);
来源：http://dali.vqdsnc.cn/Article/details/gt2vkkssysq.html

Java: list.add(4);
来源：http://dali.ybcxt.top/Article/details/gt2uzovdjps.html

Go:   arr = append(arr, 4)
来源：http://dali.hysaishi.cn/Article/details/gt2exrkctjs.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vmledjbs.html

C#:   list.Add(4);
来源：http://dali.sysykeji.top/Article/details/gt2cxdbkjfj.html

[D03] 在指定位置插入元素
来源：http://dali.yanxiufei.cn/Article/details/gt2hqjvmnsa.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxybjoqo.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yanxiufei.cn/Article/details/gt2fmrfaaej.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mehhsrow.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.c1oappe.top/Article/details/gt2yzmqlfof.html

Java: list.add(0, 0);
来源：http://dali.yj20258.top/Article/details/gt2csidclxr.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.haohaochexian.top/Article/details/gt2xccftkke.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ybcxt.top/Article/details/gt2ypzlhtul.html

C#:   list.Insert(0, 0);
来源：http://dali.jqgufenzy.top/Article/details/gt2uhldwqxb.html

[D04] 删除元素
来源：http://dali.nanxuanxn.top/Article/details/gt2gmyhvmmi.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ehwqpu.com/Article/details/gt2agdjhmti.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sufxvd.cn/Article/details/gt2ncfrhkbg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yangfankeji.com/Article/details/gt2koevbopf.html

TS:   arr.splice(0, 1);
来源：http://dali.nanxinkj.top/Article/details/gt2ehaqnlqi.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jinqigufen.top/Article/details/gt2iyyaolua.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.vqdsnc.cn/Article/details/gt2xipjxcoz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cheryme.top/Article/details/gt2hmzkhnjv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhengqikj.top/Article/details/gt2wtjuxnrp.html

[D05] 访问与修改元素
来源：http://dali.cashguo.top/Article/details/gt2qdxiamxt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxuanxn.top/Article/details/gt2fujxeldg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gt2oeolyles.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cucudq.cn/Article/details/gt2ltocyhky.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xinyue.icu/Article/details/gt2teadvavk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhengqikj.top/Article/details/gt2nunwuovs.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hjsmfozn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.feifeiyinyue.top/Article/details/gt2voyoftgt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yj202588.top/Article/details/gt2kspzpmlz.html

[D06] 数组长度
来源：http://dali.hfpthk.cn/Article/details/gt2lamvyfpa.html

Py:   len(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2brfarzjw.html

PHP:  count($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2ckpvauwl.html

JS:   arr.length
来源：http://dali.gzhubu.top/Article/details/gt2wfzotddx.html

TS:   arr.length
来源：http://dali.xuetiantiany.cn/Article/details/gt2vtwsonpu.html

Java: list.size();
来源：http://dali.jyoumei.cn/Article/details/gt2wmisvrxy.html

Go:   len(arr)
来源：http://dali.cucudq.cn/Article/details/gt2faowajuf.html

Ruby: arr.length; arr.size
来源：http://dali.gogol.net.cn/Article/details/gt2imuzsbzp.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzxybik.html

[D07] 切片 / 取子数组
来源：http://dali.gzhubu.top/Article/details/gt2vhutsdcl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.nwbrower.top/Article/details/gt2geyapisx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.guannengcc.top/Article/details/gt2lekahjcy.html

JS:   arr.slice(1, 4);
来源：http://dali.hfpthk.cn/Article/details/gt2pqewydmq.html

TS:   arr.slice(1, 4);
来源：http://dali.aizwys.cn/Article/details/gt2hycimhdf.html

Java: list.subList(1, 4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2imnpckln.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2dckvrots.html

Ruby: arr[1, 3]
来源：http://dali.gzhubu.top/Article/details/gt2lzscupwp.html

C#:   list.GetRange(1, 3);
来源：http://dali.zdqjudy.top/Article/details/gt2daxwfpsw.html

[D08] 合并两个数组
来源：http://dali.yueranfly.top/Article/details/gt2fdcklfwf.html

Py:   a + b;  a.extend(b)
来源：http://dali.snrcjt.cn/Article/details/gt2gnrwuuie.html

PHP:  array_merge($a, $b);
来源：http://dali.jiagoushi.top/Article/details/gt2zegdyxol.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.9152youxi.cn/Article/details/gt2qxirlrcu.html

TS:   [...a, ...b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nbggtjng.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.smart0.xyz/Article/details/gt2kpoytxzc.html

Go:   append(a, b...)
来源：http://dali.hammf.cn/Article/details/gt2esapabvw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ziuatncs.html

C#:   a.Concat(b).ToList()
来源：http://dali.hammf.cn/Article/details/gt2xzuvyeod.html

[D09] 排序（升序）
来源：http://dali.shzxlz.cn/Article/details/gt2njosybma.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.guannengcc.top/Article/details/gt2ostadofn.html

PHP:  sort($arr);
来源：http://dali.bjfxy.top/Article/details/gt2iepxmuvo.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinqigfzy.top/Article/details/gt2jvjowdyl.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ppjwa.cn/Article/details/gt2tjfzqgfg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.meibo888.top/Article/details/gt2obrpmrbo.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2xkjyhqlp.html

Ruby: arr.sort
来源：http://dali.9152youxi.cn/Article/details/gt2icoeutcy.html

C#:   list.Sort();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ytbznvlh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.tian-w.cn/Article/details/gt2whmmxtcp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yuanzhike.top/Article/details/gt2nftfraef.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sxryk.cn/Article/details/gt2kphhxonl.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shangyingyoupin.top/Article/details/gt2chjiqxvp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daxiang520.top/Article/details/gt2evxgdcgj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.tian-w.cn/Article/details/gt2hbxstgzt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.snrcjt.cn/Article/details/gt2cflxuzsk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhongyouzk.top/Article/details/gt2tizznbmz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zjgiwptd.html


<!-- 参考信息 -->