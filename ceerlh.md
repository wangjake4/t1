代发 wailian999

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.gzhubu.top/Article/details/gtqrliielz.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jinqigufen.top/Article/details/gtaxbsfeiv.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.birdmap.top/Article/details/gtviieldvt.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.chenlongwang.top/Article/details/gtbuoxmmgv.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.dashuyun.cn/Article/details/gtcelmxabi.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.smart0.xyz/Article/details/gtjuhmyvnt.html

[B11] 生成数字序列 / 区间
来源：http://dali.andypj.xyz/Article/details/gtyjmpjirg.html

Py:   list(range(0, 10, 2))
来源：http://dali.jiagoushi.top/Article/details/gturvbwzfu.html

PHP:  range(0, 10, 2);
来源：http://dali.smart0.xyz/Article/details/gtmschenmv.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.mhx1999.top/Article/details/gthiubfxcv.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yanxiufei.cn/Article/details/gtbzodenon.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.316326.xyz/Article/details/gtqgbczscz.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yonumen.top/Article/details/gtxtaibtnp.html

Ruby: (0...10).step(2).to_a
来源：http://dali.tianlin.xyz/Article/details/gtivzhvgog.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zycfv.cn/Article/details/gtbxpfmzmq.html

[B12] 跳出多层循环
来源：http://dali.jianghu66.top/Article/details/gtphgpjvut.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.iojbl.cn/Article/details/gtmutvnbec.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.nanxuanxn.top/Article/details/gtogcllnhl.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbomqehkz.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ydzc1.top/Article/details/gtfwpvlyvt.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.shuidangran.top/Article/details/gtaxxhihrj.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.meibo888.top/Article/details/gtbkgyilhm.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yangfankeji.com/Article/details/gtdskuqzop.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.smart0.xyz/Article/details/gtecpzorlo.html

[B13] 判断是否为数字
来源：http://dali.sxryk.cn/Article/details/gtabmnzdyd.html

Py:   isinstance(x, (int, float))
来源：http://dali.cashguo.top/Article/details/gtlqeovesu.html

PHP:  is_numeric($x)
来源：http://dali.guowangkeji.top/Article/details/gtzeykfnzz.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhoulong.xyz/Article/details/gtygeygyyy.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.fzhhl.top/Article/details/gtmrxqffpf.html

Java: x instanceof Number
来源：http://dali.jlsjyb.cn/Article/details/gtnfsvdueq.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgfwncame.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtygxpesqa.html

C#:   x is int or double or decimal
来源：http://dali.shangyingyoupin.top/Article/details/gtrlwcsxkg.html

[B14] 判断值是否在集合内
来源：http://dali.yj20258888.top/Article/details/gthdrsaovt.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ehwqpu.com/Article/details/gtoecqfqib.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.smart0.xyz/Article/details/gtdlabjnxn.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xinyue.icu/Article/details/gtvugibdit.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.smart0.xyz/Article/details/gtfoxubytb.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.sweek.top/Article/details/gtqbvlwrwa.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.cheryme.top/Article/details/gtbkrgxihi.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jqgufenzy.top/Article/details/gtcshownqh.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.redwolf501.top/Article/details/gtvqygbmbs.html

[B15] 布尔运算与取反
来源：http://dali.sxryk.cn/Article/details/gtpkrawbkw.html

Py:   a and b or not c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuhnshzkq.html

PHP:  $a && $b || !$c
来源：http://dali.cdnleiting.top/Article/details/gtlnbpslvh.html

JS:   a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gtoddpozkk.html

TS:   a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gtrzpdappj.html

Java: a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gtsnpotpbq.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gtjjdyumzx.html

Ruby: a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gtiqadphvc.html

C#:   a && b || !c
来源：http://dali.yvedp.cn/Article/details/gtkzjwddia.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.guowangkeji.top/Article/details/gtdnvneuoz.html

Py:   if not data: return
来源：http://dali.0kj1m.cn/Article/details/gtbvttbiii.html

PHP:  if (!$data) { return; }
来源：http://dali.redwolf501.top/Article/details/gtlyrsktac.html

JS:   if (!data) return;
来源：http://dali.vqdsnc.cn/Article/details/gtarflnsmj.html

TS:   if (!data) return;
来源：http://dali.xziqi.cn/Article/details/gtckgaepsm.html

Java: if (data == null) return;
来源：http://dali.gotoacloud.top/Article/details/gtjpfhzqya.html

Go:   if data == nil { return }
来源：http://dali.jinyuanbaomall.cn/Article/details/gteizrtnpw.html

Ruby: return if data.nil?
来源：http://dali.sxryk.cn/Article/details/gtxgwdjyqm.html

C#:   if (data == null) return;
来源：http://dali.chenjidiqi.icu/Article/details/gtrpruahbf.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtagmaakyp.html

C. 函数与作用域
来源：http://dali.chenjidiqi.icu/Article/details/gtgkglcyym.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtpxnmwzjy.html

[C01] 定义函数
来源：http://dali.hfpthk.cn/Article/details/gtzdrapnxg.html

Py:   def add(a, b): return a + b
来源：http://dali.yangfankeji.com/Article/details/gtqbibdwyt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtllyuxqsk.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtzszimtnd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gtftdtcxkj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gtapgkbnws.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yueranfly.top/Article/details/gtzcgiggnz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.wangshuangyany.cn/Article/details/gtuecmzwli.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gtvklrdagc.html

[C02] 默认参数
来源：http://dali.xylfe.cn/Article/details/gtkbnuspkz.html

Py:   def greet(name="World"): return name
来源：http://dali.ppjwa.cn/Article/details/gtpcxadlac.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shzxlz.cn/Article/details/gtcebsealc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.bjfxy.top/Article/details/gtdgclmcxc.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cheryme.top/Article/details/gthljrxwmd.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.sweek.top/Article/details/gtbbnzckip.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.dianchejie.cn/Article/details/gtspgumgap.html

Ruby: def greet(name = "World") = name
来源：http://dali.jqgfzy.top/Article/details/gtbgvdilml.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yj20258.top/Article/details/gtcbqswzrp.html

[C03] 可变参数
来源：http://dali.havefunace.top/Article/details/gtyurokbbr.html

Py:   def total(*args): return sum(args)
来源：http://dali.yj202588.top/Article/details/gtvtihnuas.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jlsjyb.cn/Article/details/gtqwsvhryv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.iojbl.cn/Article/details/gtwxeozsgk.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gogol.net.cn/Article/details/gttllrypcm.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.tian-w.cn/Article/details/gtfpnpvncr.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.0kj1m.cn/Article/details/gtmvoqvnjm.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jlsjyb.cn/Article/details/gtsqgakyxz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtprbwfxtj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.fzhhl.top/Article/details/gtqevzwjro.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cashguo.top/Article/details/gtilafqjdc.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shuidangran.top/Article/details/gtikcycrjh.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jqgufenzy.top/Article/details/gthxkqebdk.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ydzc1.top/Article/details/gtpodhzwgq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jiagoushi.top/Article/details/gtwbcpbujs.html

Go:   // 无：用配置结构体参数
来源：http://dali.chenjidiqi.icu/Article/details/gtlzuwtpnt.html

Ruby: f(a: 1, b: 2)
来源：http://dali.c1oappe.top/Article/details/gtdrivfphb.html

C#:   f(a: 1, b: 2)
来源：http://dali.yj20258888.top/Article/details/gtspufplqf.html

[C05] 返回多个值
来源：http://dali.nanxuanxn.top/Article/details/gtqleyromc.html

Py:   return a, b
来源：http://dali.cqqwz.cn/Article/details/gtktorffad.html

PHP:  return [$a, $b];
来源：http://dali.gogol.net.cn/Article/details/gtzkyxesjb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yongpay.top/Article/details/gtnnruufjt.html

TS:   return { a, b };
来源：http://dali.redwolf501.top/Article/details/gtzeoewbrs.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xylfe.cn/Article/details/gtqetisfgp.html

Go:   return a, b
来源：http://dali.gaohongyu789.top/Article/details/gtacxjrpgf.html

Ruby: return a, b
来源：http://dali.jianghu66.top/Article/details/gtqwkorduq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.andypj.xyz/Article/details/gtwahqfxui.html

[C06] 匿名函数 / lambda
来源：http://dali.shuidangran.top/Article/details/gtvuusulfa.html

Py:   square = lambda x: x * x
来源：http://dali.yonumen.top/Article/details/gtmucsbuxv.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xinyue.icu/Article/details/gtucbxvnkk.html

JS:   const square = x => x * x;
来源：http://dali.zhongyouzk.top/Article/details/gtbjvofzjs.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gthivfnjdo.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhoulong.xyz/Article/details/gtzbydashe.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.dianchejie.cn/Article/details/gtgoyjmede.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shzxlz.cn/Article/details/gtomimotsu.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hysaishi.cn/Article/details/gteuksvmec.html

[C07] 把函数作为参数传入
来源：http://dali.daria6918.cn/Article/details/gtctyrhbgh.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.wangshuangyany.cn/Article/details/gtpexvkjzn.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.daria6918.cn/Article/details/gtahpttztm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yueranfly.top/Article/details/gtlvgejabd.html

TS:   arr.map(String)
来源：http://dali.pengpengdd.cyou/Article/details/gtchqdsqqx.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gogol.net.cn/Article/details/gtgzjzjbel.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.nwbrower.top/Article/details/gtenircejh.html

Ruby: arr.map(&:upcase)
来源：http://dali.guowangkeji.top/Article/details/gtrhjoanzt.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ehwqpu.com/Article/details/gtqhrvkhzx.html

[C08] 闭包
来源：http://dali.yueranfly.top/Article/details/gtsbdmexre.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.feifeiyinyue.top/Article/details/gtodhxmeik.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xylfe.cn/Article/details/gtxyjlzzao.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.svipenyu.cn/Article/details/gtivbswysi.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.guowangkeji.top/Article/details/gtsgnkzypz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hnxiangtu.top/Article/details/gtgzjruqtc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.feifeiyinyue.top/Article/details/gtnkegddtu.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.dianchejie.cn/Article/details/gtohlemhjl.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.birdmap.top/Article/details/gtzqydntov.html

[C09] 递归
来源：http://dali.dashuyun.cn/Article/details/gtppslfium.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.fengsongda.top/Article/details/gtihzfjsnb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yangfankeji.com/Article/details/gtmeewrmkq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sxryk.cn/Article/details/gtjwghjxzf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.quarkkingdee.top/Article/details/gthnxdeynw.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.tianlin.xyz/Article/details/gteifmmhiw.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xylfe.cn/Article/details/gtzbojgvqg.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.mhx1999.top/Article/details/gtsqmeyjth.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yj202588.top/Article/details/gtwsfimdpa.html

[C10] 变量作用域
来源：http://dali.snrcjt.cn/Article/details/gtibcygaax.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinqigfzy.top/Article/details/gtadfhyrqm.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ehwqpu.com/Article/details/gteutxcheq.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jiagoushi.top/Article/details/gtzogjhenn.html

TS:   同 JS
来源：http://dali.yvedp.cn/Article/details/gtexwfztxy.html

Java: 方法内为块级作用域
来源：http://dali.birdmap.top/Article/details/gtlifnhatq.html

Go:   花括号块级作用域
来源：http://dali.zhongyouzk.top/Article/details/gtaabcyivf.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhixingplan.top/Article/details/gtkylyadas.html

C#:   块级作用域
来源：http://dali.jyoumei.cn/Article/details/gtlqjuqmft.html

[C11] 模块导入与导出
来源：http://dali.tianlin.xyz/Article/details/gtjdfeauvj.html

Py:   from module import func
来源：http://dali.smart0.xyz/Article/details/gtlubxiqcf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.chenlongwang.top/Article/details/gtffwhnvzw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.svipenyu.cn/Article/details/gtnckuhzeh.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yuxming.cn/Article/details/gtlkhnqmsk.html

Java: import java.util.List;
来源：http://dali.zhoulong.xyz/Article/details/gteybhejbu.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.tanke756.top/Article/details/gtwoeqlpsf.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jlsjyb.cn/Article/details/gtwtzpttsu.html

C#:   using System.Text;
来源：http://dali.nwbrower.top/Article/details/gtfrimxvnm.html

[C12] 立即执行函数 IIFE
来源：http://dali.yuxming.cn/Article/details/gtknkqrqah.html

Py:   (lambda: print("run"))()
来源：http://dali.chenlongwang.top/Article/details/gtjrrruqcf.html

PHP:  (function () { echo "run"; })();
来源：http://dali.redwolf501.top/Article/details/gtedywuwue.html

JS:   (() => { console.log("run"); })();
来源：http://dali.guannengcc.top/Article/details/gthjdsrhjy.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hongshengwenyu.top/Article/details/gtbvaozblb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.smart0.xyz/Article/details/gtbmfnbgtr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xinyue.icu/Article/details/gtyvnpgaxs.html

Ruby: -> { puts "run" }.call
来源：http://dali.wangshuangyany.cn/Article/details/gtdrwddsip.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.daria6918.cn/Article/details/gtaeqwbhiw.html

[C13] 类型声明 / 类型注解
来源：http://dali.smart0.xyz/Article/details/gtttgofqur.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhixingplan.top/Article/details/gtuohpxnjn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cdnleiting.top/Article/details/gtypuzdrro.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.aibaodan.cn/Article/details/gtvipefhnk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gtdkmtyhif.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtqsykcqhm.html

Go:   func add(a, b int) int
来源：http://dali.xylfe.cn/Article/details/gtbxqimuwp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.snrcjt.cn/Article/details/gtdvuttxxk.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.sxryk.cn/Article/details/gtqejfinvf.html

[C14] 泛型函数
来源：http://dali.nwbrower.top/Article/details/gtoamrysly.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yongpay.top/Article/details/gtifdhsqhg.html

PHP:  // 无泛型
来源：http://dali.hammf.cn/Article/details/gtslpjnikp.html

JS:   // 无泛型
来源：http://dali.birdmap.top/Article/details/gtuyrejaeh.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hfpthk.cn/Article/details/gtehketzge.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.kuanghao11.cn/Article/details/gtthiysqpg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yuxming.cn/Article/details/gtytkiwfqm.html

Ruby: # 无泛型
来源：http://dali.meibo888.top/Article/details/gtsjntpiel.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbozqivxc.html

[C15] 解构 / 展开参数
来源：http://dali.yonumen.top/Article/details/gtsvsbkvir.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ehwqpu.com/Article/details/gtjlsidjwq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.daria6918.cn/Article/details/gtirfckwxl.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.svipenyu.cn/Article/details/gtsatokaab.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jianghu66.top/Article/details/gtehqfxaqx.html

Java: // 无解构
来源：http://dali.sweek.top/Article/details/gthykmgmjj.html

Go:   // 无解构
来源：http://dali.jianghu66.top/Article/details/gtaispwxkn.html

Ruby: a, b = pair
来源：http://dali.fzhhl.top/Article/details/gtugdqarsk.html

C#:   var (a, b) = pair;
来源：http://dali.yj202588.top/Article/details/gtvrjlmedn.html

[C16] 函数 / 方法重载
来源：http://dali.cashguo.top/Article/details/gtckrxwtmv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.fzhhl.top/Article/details/gtvkngcdkl.html

PHP:  // 无重载
来源：http://dali.tian-w.cn/Article/details/gtwmwwmjtr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ivvv.top/Article/details/gtskibkndl.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hfpthk.cn/Article/details/gtioqrgryp.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.svipenyu.cn/Article/details/gtkaxitnxl.html

Go:   // 无重载：用不同函数名
来源：http://dali.ydzc1.top/Article/details/gtorqljwit.html

Ruby: # 无重载：靠动态参数
来源：http://dali.fzhhl.top/Article/details/gtzzgbelxd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.sxryk.cn/Article/details/gtqpmfxoyb.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtiictbsih.html

D. 数组 / 列表 / 集合
来源：http://dali.9152youxi.cn/Article/details/gtuapwzmsr.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtdlyvwpov.html

[D01] 创建数组 / 列表
来源：http://dali.xuanzx.com/Article/details/gtpaorleaz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinghuilouyu.cn/Article/details/gtnimgiywe.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zycfv.cn/Article/details/gtwtweirzs.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yongpay.top/Article/details/gtaunqspjy.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jqgufenzy.top/Article/details/gtvopbsudu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.redwolf501.top/Article/details/gtvtmccwso.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yuxming.cn/Article/details/gtgwghvqyr.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sysykeji.top/Article/details/gtawjplpqf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yanxiufei.cn/Article/details/gtppjozhej.html

[D02] 追加元素到末尾
来源：http://dali.jinghuilouyu.cn/Article/details/gtunrsutej.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinqigfzy.top/Article/details/gtbtuuenkz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.tianlin.xyz/Article/details/gtqzjiascu.html

JS:   arr.push(4);
来源：http://dali.yuxming.cn/Article/details/gtrtullavj.html

TS:   arr.push(4);
来源：http://dali.tianlin.xyz/Article/details/gthkhksfjy.html

Java: list.add(4);
来源：http://dali.yj20258.top/Article/details/gtalivvrvk.html

Go:   arr = append(arr, 4)
来源：http://dali.yangfankeji.com/Article/details/gtlqnbmtuy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jinqigfzy.top/Article/details/gtyshdcvlw.html

C#:   list.Add(4);
来源：http://dali.feifeiyinyue.top/Article/details/gtmqcgsnda.html

[D03] 在指定位置插入元素
来源：http://dali.sxryk.cn/Article/details/gtnfrnzwos.html

Py:   arr.insert(0, 0)
来源：http://dali.daria6918.cn/Article/details/gtbjtswmqy.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shangyingyoupin.top/Article/details/gtqobegekv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.chenzaomai.com/Article/details/gtqywrtjyv.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhixingplan.top/Article/details/gtompcgbem.html

Java: list.add(0, 0);
来源：http://dali.zhengqikj.top/Article/details/gtqghrjble.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.kuanghao11.cn/Article/details/gtkfotrioy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yj20258.top/Article/details/gtbenfgzlz.html

C#:   list.Insert(0, 0);
来源：http://dali.xziqi.cn/Article/details/gtoojygptm.html

[D04] 删除元素
来源：http://dali.wangshuangyany.cn/Article/details/gtxdfawuoc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.havefunace.top/Article/details/gtxjkmcvql.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cashguo.top/Article/details/gtbpothroy.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinqigufen.top/Article/details/gtohdsaeec.html

TS:   arr.splice(0, 1);
来源：http://dali.xuanzx.com/Article/details/gtvnjsmlql.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cashguo.top/Article/details/gtverfqeap.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.nanxuanxn.top/Article/details/gtiqecmilc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.tanke756.top/Article/details/gtaaicroek.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlwpptdju.html

[D05] 访问与修改元素
来源：http://dali.hammf.cn/Article/details/gthegpbldy.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.bjfxy.top/Article/details/gtcdejhjde.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xylfe.cn/Article/details/gttuzktagp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cdnleiting.top/Article/details/gttwfqmack.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jinqigufen.top/Article/details/gtwtgclnql.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yongpay.top/Article/details/gtvagvugpl.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgbtfeunl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tianlin.xyz/Article/details/gtrbjewwwi.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhoulong.xyz/Article/details/gtiqhdyazu.html

[D06] 数组长度
来源：http://dali.iojbl.cn/Article/details/gttpgbcova.html

Py:   len(arr)
来源：http://dali.hnqzz.top/Article/details/gthvdckjuv.html

PHP:  count($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtusunakhv.html

JS:   arr.length
来源：http://dali.hnxiangtu.top/Article/details/gtpndfhnze.html

TS:   arr.length
来源：http://dali.yonumen.top/Article/details/gtkrhukczb.html

Java: list.size();
来源：http://dali.xylfe.cn/Article/details/gtzjyubwul.html

Go:   len(arr)
来源：http://dali.c1oappe.top/Article/details/gtnpflinin.html

Ruby: arr.length; arr.size
来源：http://dali.0kj1m.cn/Article/details/gtsanxhnsz.html

C#:   list.Count;
来源：http://dali.0kj1m.cn/Article/details/gtkdbjdcco.html

[D07] 切片 / 取子数组
来源：http://dali.zdqjudy.top/Article/details/gtdklpuyau.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.c1oappe.top/Article/details/gtxkljjvbx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hammf.cn/Article/details/gthqqatich.html

JS:   arr.slice(1, 4);
来源：http://dali.hnxiangtu.top/Article/details/gtkysakvwd.html

TS:   arr.slice(1, 4);
来源：http://dali.dianchejie.cn/Article/details/gtaytzforr.html

Java: list.subList(1, 4);
来源：http://dali.316326.xyz/Article/details/gtcgcqguzb.html

Go:   arr[1:4]
来源：http://dali.xuanzx.com/Article/details/gtfufkhwnu.html

Ruby: arr[1, 3]
来源：http://dali.andypj.xyz/Article/details/gtoxwtxeym.html

C#:   list.GetRange(1, 3);
来源：http://dali.jqgfzy.top/Article/details/gtfzbckkzo.html

[D08] 合并两个数组
来源：http://dali.shuidangran.top/Article/details/gtrrixnhxs.html

Py:   a + b;  a.extend(b)
来源：http://dali.yvedp.cn/Article/details/gtznyyoocd.html

PHP:  array_merge($a, $b);
来源：http://dali.tian-w.cn/Article/details/gtzvzpcfro.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jqgfzy.top/Article/details/gtksexltjl.html

TS:   [...a, ...b];
来源：http://dali.cashguo.top/Article/details/gtwaaogurl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.kuanghao11.cn/Article/details/gtakrpfwpg.html

Go:   append(a, b...)
来源：http://dali.shanyushiyangtech.top/Article/details/gthzyufhux.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ppjwa.cn/Article/details/gtszjndyxf.html

C#:   a.Concat(b).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtxwfonyhm.html

[D09] 排序（升序）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnnnffess.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnxiangtu.top/Article/details/gtcdvmczck.html

PHP:  sort($arr);
来源：http://dali.pycfn.com/Article/details/gtkjxqrmhx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.tanke756.top/Article/details/gtajjhxpyn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ivvv.top/Article/details/gtvekzlqag.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cqqwz.cn/Article/details/gtoymtlryv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtfgmgvrsk.html

Ruby: arr.sort
来源：http://dali.jianghu66.top/Article/details/gtriucyrxp.html

C#:   list.Sort();
来源：http://dali.jinqigufen.top/Article/details/gtdtdldelf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhiwuduotai.top/Article/details/gtzappvqqq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.feifeiyinyue.top/Article/details/gtbcheqpoy.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tanke756.top/Article/details/gttnfhsnqf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnqzz.top/Article/details/gtykrgcyej.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenzaomai.com/Article/details/gtiqmzoxuf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xylfe.cn/Article/details/gtdxznuijh.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.sweek.top/Article/details/gtxwcpwhbs.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhongyouzk.top/Article/details/gtvimdpntf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhiwuduotai.top/Article/details/gtvzddpfmg.html


<!-- 参考信息 -->