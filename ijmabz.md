代发 wailian999

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258888.top/Article/details/gtgwoarqob.html

[B10] 遍历同时拿索引
来源：http://dali.shangyingyoupin.top/Article/details/gtzgklrgtu.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.cucudq.cn/Article/details/gthrasmlzi.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.sxryk.cn/Article/details/gtlmglcpgd.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.aibaodan.cn/Article/details/gtyrnmwnvv.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhengqikj.top/Article/details/gtdxtmobrl.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.316326.xyz/Article/details/gtlnxukoik.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yonumen.top/Article/details/gtqdqxdoic.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.shzxlz.cn/Article/details/gtcxgakzvp.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.nanxinkj.top/Article/details/gtjcljhtvj.html

[B11] 生成数字序列 / 区间
来源：http://dali.yvedp.cn/Article/details/gtrfukiwvu.html

Py:   list(range(0, 10, 2))
来源：http://dali.gotoacloud.top/Article/details/gtgxhtewsg.html

PHP:  range(0, 10, 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtxyyyyosx.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtioyfplqk.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xziqi.cn/Article/details/gtgczmucyo.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.ydzc1.top/Article/details/gtmhbudokx.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.wangdashe.top/Article/details/gtougiotoa.html

Ruby: (0...10).step(2).to_a
来源：http://dali.guowangkeji.top/Article/details/gtolynvmbk.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.gotoacloud.top/Article/details/gtumvufnnl.html

[B12] 跳出多层循环
来源：http://dali.cdnleiting.top/Article/details/gttdgpiscy.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xinyue.icu/Article/details/gtrqnntmiq.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.daxiang520.top/Article/details/gtjoqrifcx.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.redwolf501.top/Article/details/gtueyzcniv.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yueranfly.top/Article/details/gtvotyulev.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.redwolf501.top/Article/details/gtagevmfch.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.cqqwz.cn/Article/details/gtezgvmjgc.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.gzhubu.top/Article/details/gtwyurjaxh.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yueranfly.top/Article/details/gtaylfrlec.html

[B13] 判断是否为数字
来源：http://dali.hywenlv.cn/Article/details/gttxgptrxx.html

Py:   isinstance(x, (int, float))
来源：http://dali.jqgfzy.top/Article/details/gtiqrpnkon.html

PHP:  is_numeric($x)
来源：http://dali.sweek.top/Article/details/gtwedcjgxz.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhongyouzk.top/Article/details/gtmgeunuvh.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.aibaodan.cn/Article/details/gtvovgfkba.html

Java: x instanceof Number
来源：http://dali.nanxuanxn.top/Article/details/gttcphixbi.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.birdmap.top/Article/details/gtrxbvpikq.html

Ruby: x.is_a?(Numeric)
来源：http://dali.tanke756.top/Article/details/gtchqbzoze.html

C#:   x is int or double or decimal
来源：http://dali.hywenlv.cn/Article/details/gtvixuoilo.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gtmxbolltt.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shuidangran.top/Article/details/gtukplatdl.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hywenlv.cn/Article/details/gtjnswawzb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.0kj1m.cn/Article/details/gtbddqpsoh.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.shuidangran.top/Article/details/gtolfbinou.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.fzhhl.top/Article/details/gthtijmftp.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.c1oappe.top/Article/details/gtxzgkbgtp.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtklduyxhq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gtzxemlxlb.html

[B15] 布尔运算与取反
来源：http://dali.zhoulong.xyz/Article/details/gtrrmqihpa.html

Py:   a and b or not c
来源：http://dali.havefunace.top/Article/details/gtmwgrrfql.html

PHP:  $a && $b || !$c
来源：http://dali.zycfv.cn/Article/details/gthzjtdmsy.html

JS:   a && b || !c
来源：http://dali.ivvv.top/Article/details/gtwuabgmhs.html

TS:   a && b || !c
来源：http://dali.fengsongda.top/Article/details/gtdlizsyjo.html

Java: a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gthneqxnjr.html

Go:   a && b || !c
来源：http://dali.shanyushiyangkeji.top/Article/details/gtakqamnez.html

Ruby: a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gtubaibkzy.html

C#:   a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gthdsodyec.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.pengpengdd.cyou/Article/details/gtsysozmor.html

Py:   if not data: return
来源：http://dali.hfpthk.cn/Article/details/gtoqndzboa.html

PHP:  if (!$data) { return; }
来源：http://dali.cheryme.top/Article/details/gtukreeacx.html

JS:   if (!data) return;
来源：http://dali.svipenyu.cn/Article/details/gtezsfqvgy.html

TS:   if (!data) return;
来源：http://dali.cashguo.top/Article/details/gtydanstgp.html

Java: if (data == null) return;
来源：http://dali.hammf.cn/Article/details/gtcdvlaobb.html

Go:   if data == nil { return }
来源：http://dali.xuanzx.com/Article/details/gtehrjkdod.html

Ruby: return if data.nil?
来源：http://dali.shangyingyoupin.top/Article/details/gtoxuxlwnx.html

C#:   if (data == null) return;
来源：http://dali.yueranfly.top/Article/details/gtymdotigh.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtrytdigiv.html

C. 函数与作用域
来源：http://dali.aibaodan.cn/Article/details/gtutadxdzz.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtaaukodyv.html

[C01] 定义函数
来源：http://dali.zhixingplan.top/Article/details/gtvrxqamet.html

Py:   def add(a, b): return a + b
来源：http://dali.tanke756.top/Article/details/gtkdwhsybd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yangfankeji.com/Article/details/gtlotiukmd.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gtbkxjptoi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtqlkouhni.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gtjbrbmffg.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.snrcjt.cn/Article/details/gtmssjyhee.html

Ruby: def add(a, b); a + b; end
来源：http://dali.iojbl.cn/Article/details/gtgqyugers.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gtqangxiih.html

[C02] 默认参数
来源：http://dali.xinyue.icu/Article/details/gtzcxctign.html

Py:   def greet(name="World"): return name
来源：http://dali.xziqi.cn/Article/details/gtxedcoowc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.fengsongda.top/Article/details/gtlwootkfw.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gtiejcvycf.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpaanfrny.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.havefunace.top/Article/details/gtubdplmzm.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hnqzz.top/Article/details/gtdvwcrjhl.html

Ruby: def greet(name = "World") = name
来源：http://dali.birdmap.top/Article/details/gtlytfcdcw.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yvedp.cn/Article/details/gtrqyyfjdz.html

[C03] 可变参数
来源：http://dali.hnxiangtu.top/Article/details/gtpjxxdmjq.html

Py:   def total(*args): return sum(args)
来源：http://dali.pycfn.com/Article/details/gtidastwga.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yongpay.top/Article/details/gtgwdmuuzz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hywenlv.cn/Article/details/gtnlivlrvh.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ivvv.top/Article/details/gtstyplkdj.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hywenlv.cn/Article/details/gtcaaatclp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yangfankeji.com/Article/details/gtpsssdzpb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zycfv.cn/Article/details/gtfxywvowk.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.feifeiyinyue.top/Article/details/gtodhlqevn.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhoulong.xyz/Article/details/gtzazvjipx.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yangfankeji.com/Article/details/gtmmdwdoay.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yvedp.cn/Article/details/gteqndgkbc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.havefunace.top/Article/details/gtownvsvlm.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.meibo888.top/Article/details/gtvxvimzuf.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.svipenyu.cn/Article/details/gteeghzkmu.html

Go:   // 无：用配置结构体参数
来源：http://dali.9152youxi.cn/Article/details/gtjbtccruc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.gaohongyu789.top/Article/details/gtoapadoky.html

C#:   f(a: 1, b: 2)
来源：http://dali.hnqzz.top/Article/details/gtmwshcumk.html

[C05] 返回多个值
来源：http://dali.zhixingplan.top/Article/details/gtekhlwysy.html

Py:   return a, b
来源：http://dali.shzxlz.cn/Article/details/gthpedhkry.html

PHP:  return [$a, $b];
来源：http://dali.aizwys.cn/Article/details/gtiiuwmuft.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbjvmherj.html

TS:   return { a, b };
来源：http://dali.birdmap.top/Article/details/gtewfqrgzn.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.snrcjt.cn/Article/details/gtxdhwvdnx.html

Go:   return a, b
来源：http://dali.aizwys.cn/Article/details/gtsimkxpcl.html

Ruby: return a, b
来源：http://dali.xuanzx.com/Article/details/gtgxeaxiie.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.sysykeji.top/Article/details/gtqiymzihw.html

[C06] 匿名函数 / lambda
来源：http://dali.zhiwuduotai.top/Article/details/gtwkiahwzm.html

Py:   square = lambda x: x * x
来源：http://dali.iojbl.cn/Article/details/gtznefhjif.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gtnuebtlvj.html

JS:   const square = x => x * x;
来源：http://dali.gaohongyu789.top/Article/details/gtsxqqffdq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xuetiantiany.cn/Article/details/gtxtxibdmm.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.andypj.xyz/Article/details/gtcmrmwyez.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmbadmsii.html

Ruby: square = ->(x) { x * x }
来源：http://dali.dashuyun.cn/Article/details/gtifrnuwbw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.gogol.net.cn/Article/details/gtrfppuskz.html

[C07] 把函数作为参数传入
来源：http://dali.zhiwuduotai.top/Article/details/gttbyavpaz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.mhx1999.top/Article/details/gtqsdznmzh.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zycfv.cn/Article/details/gteaoblxlt.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.pengpengdd.cyou/Article/details/gtxzktgeex.html

TS:   arr.map(String)
来源：http://dali.zycfv.cn/Article/details/gtpulbtzty.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xinyue.icu/Article/details/gtpqkkazkd.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ydzc1.top/Article/details/gtpxlgowtp.html

Ruby: arr.map(&:upcase)
来源：http://dali.hfpthk.cn/Article/details/gtjyyhoubn.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.gotoacloud.top/Article/details/gtijgfukbs.html

[C08] 闭包
来源：http://dali.cucudq.cn/Article/details/gtihpmnjuy.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xinyue.icu/Article/details/gtafvkduat.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.0kj1m.cn/Article/details/gtrsgivejf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.havefunace.top/Article/details/gtfyahxvlr.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.aibaodan.cn/Article/details/gtdwogpwce.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jinqigfzy.top/Article/details/gtsafumiyz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.snrcjt.cn/Article/details/gtznnyyzyu.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.iojbl.cn/Article/details/gtyabtadrk.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yuxming.cn/Article/details/gtnbenkwjs.html

[C09] 递归
来源：http://dali.quarkkingdee.top/Article/details/gtofqzhhjd.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.quarkkingdee.top/Article/details/gtfagfbdqx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jianghu66.top/Article/details/gtgcrnszns.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgufenzy.top/Article/details/gtimycehvu.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.quarkkingdee.top/Article/details/gtlyclkits.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhengqikj.top/Article/details/gtufstyenv.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwitxihsj.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjvpwjume.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.tianlin.xyz/Article/details/gtgsavjcge.html

[C10] 变量作用域
来源：http://dali.vqdsnc.cn/Article/details/gtqpfjrgwh.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.quarkkingdee.top/Article/details/gtuugkibwb.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.fengsongda.top/Article/details/gtbymjnqcv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.chenlongwang.top/Article/details/gtsczoymda.html

TS:   同 JS
来源：http://dali.andypj.xyz/Article/details/gtwbmmpvaf.html

Java: 方法内为块级作用域
来源：http://dali.haohaochexian.top/Article/details/gtysjbqpzg.html

Go:   花括号块级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuyugoftm.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.aibaodan.cn/Article/details/gtfbysispm.html

C#:   块级作用域
来源：http://dali.wangshuangyany.cn/Article/details/gtfdcqsfya.html

[C11] 模块导入与导出
来源：http://dali.zhiwuduotai.top/Article/details/gtfyfkngpt.html

Py:   from module import func
来源：http://dali.kuanghao11.cn/Article/details/gtefojirad.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhengqikj.top/Article/details/gttpgucwnb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.pengpengdd.cyou/Article/details/gtdtnzbrdr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yuanzhike.top/Article/details/gtwkuqzdvt.html

Java: import java.util.List;
来源：http://dali.quarkkingdee.top/Article/details/gteascsjej.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.dashuyun.cn/Article/details/gtfcmwlqau.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.tanke756.top/Article/details/gtjhkjlhvx.html

C#:   using System.Text;
来源：http://dali.jinqigfzy.top/Article/details/gttmoocjwe.html

[C12] 立即执行函数 IIFE
来源：http://dali.shangyingyoupin.top/Article/details/gtidjntmxz.html

Py:   (lambda: print("run"))()
来源：http://dali.jinghuilouyu.cn/Article/details/gtayduljkw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ehwqpu.com/Article/details/gtztcrdheg.html

JS:   (() => { console.log("run"); })();
来源：http://dali.aibaodan.cn/Article/details/gtzwdvbizp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.sxryk.cn/Article/details/gtodpigsqv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xinyue.icu/Article/details/gtkszkaasl.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hysaishi.cn/Article/details/gtwjefmssl.html

Ruby: -> { puts "run" }.call
来源：http://dali.sufxvd.cn/Article/details/gtdtgylbtl.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hfpthk.cn/Article/details/gtgrctauit.html

[C13] 类型声明 / 类型注解
来源：http://dali.tian-w.cn/Article/details/gtkwqaxboh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.c1oappe.top/Article/details/gtlcxagkgt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxuanxn.top/Article/details/gtaimmdwzc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jianghu66.top/Article/details/gtyzeubrje.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gtjhitoywf.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtoeksncup.html

Go:   func add(a, b int) int
来源：http://dali.zhongyouzk.top/Article/details/gtifeznbpg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shzxlz.cn/Article/details/gtzcazfgzv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xylfe.cn/Article/details/gtcpxaprxc.html

[C14] 泛型函数
来源：http://dali.cheryme.top/Article/details/gtudxqoijx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cucudq.cn/Article/details/gtkfpaxrfn.html

PHP:  // 无泛型
来源：http://dali.hongshengwenyu.top/Article/details/gtikahllfc.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gtcdgzvtmx.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.fengsongda.top/Article/details/gtcgdruuhn.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.andypj.xyz/Article/details/gtyzbhstun.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sysykeji.top/Article/details/gtfogceusg.html

Ruby: # 无泛型
来源：http://dali.zhoulong.xyz/Article/details/gtzewknaya.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.meibo888.top/Article/details/gtygzsfsen.html

[C15] 解构 / 展开参数
来源：http://dali.sxryk.cn/Article/details/gtrcreanhy.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.redwolf501.top/Article/details/gtnxxtispp.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shuidangran.top/Article/details/gtpfiwemhm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtabnfesvm.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cdnleiting.top/Article/details/gtkefasqmo.html

Java: // 无解构
来源：http://dali.chenzaomai.com/Article/details/gtfyplfydn.html

Go:   // 无解构
来源：http://dali.zycfv.cn/Article/details/gtybntapca.html

Ruby: a, b = pair
来源：http://dali.yj202588.top/Article/details/gtbdllvduj.html

C#:   var (a, b) = pair;
来源：http://dali.9152youxi.cn/Article/details/gtjhimgezk.html

[C16] 函数 / 方法重载
来源：http://dali.jiagoushi.top/Article/details/gtkuufjwbq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.iojbl.cn/Article/details/gtyfsyydaz.html

PHP:  // 无重载
来源：http://dali.shanyushiyangkeji.top/Article/details/gttgpgdnjf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.chenzaomai.com/Article/details/gtlzvomhrj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhengqikj.top/Article/details/gtpjzjkqyw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cqqwz.cn/Article/details/gtricbalyp.html

Go:   // 无重载：用不同函数名
来源：http://dali.jiagoushi.top/Article/details/gttzpaaeqn.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhengqikj.top/Article/details/gtidcpyrqv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqihvirzg.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtkgqaqiae.html

D. 数组 / 列表 / 集合
来源：http://dali.jianghu66.top/Article/details/gtoathbwxh.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtmatmvxoh.html

[D01] 创建数组 / 列表
来源：http://dali.yvedp.cn/Article/details/gtdrknqwhg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zdqjudy.top/Article/details/gtsbsgqvzj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.wangdashe.top/Article/details/gtatkpcnij.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yonumen.top/Article/details/gthtfenwqx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hnqzz.top/Article/details/gtmeokcyhb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.kuanghao11.cn/Article/details/gtajwfwvgx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yj202588.top/Article/details/gtaxwdbumh.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhixingplan.top/Article/details/gtgtkjftlm.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gogol.net.cn/Article/details/gtraoojnvk.html

[D02] 追加元素到末尾
来源：http://dali.316326.xyz/Article/details/gtyicsvyng.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.pycfn.com/Article/details/gtgdchvpjd.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yj20258888.top/Article/details/gtxbnuypxk.html

JS:   arr.push(4);
来源：http://dali.sxryk.cn/Article/details/gtowaucane.html

TS:   arr.push(4);
来源：http://dali.chenlongwang.top/Article/details/gtmruwbbyg.html

Java: list.add(4);
来源：http://dali.mhx1999.top/Article/details/gtfogdbrrn.html

Go:   arr = append(arr, 4)
来源：http://dali.316326.xyz/Article/details/gtaponqxqn.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jinqigfzy.top/Article/details/gtndevsvng.html

C#:   list.Add(4);
来源：http://dali.9152youxi.cn/Article/details/gtvqkxsyom.html

[D03] 在指定位置插入元素
来源：http://dali.svipenyu.cn/Article/details/gtpelqapmu.html

Py:   arr.insert(0, 0)
来源：http://dali.tian-w.cn/Article/details/gtryzdgktz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.chenzaomai.com/Article/details/gtdvbwatch.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.tian-w.cn/Article/details/gtiqnwmyll.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.nanxuanxn.top/Article/details/gtmcljmqqr.html

Java: list.add(0, 0);
来源：http://dali.zhixingplan.top/Article/details/gtffokbovw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shangyingyoupin.top/Article/details/gtkunmnuty.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.9152youxi.cn/Article/details/gtrfuusdjo.html

C#:   list.Insert(0, 0);
来源：http://dali.ppjwa.cn/Article/details/gtzwmhzryl.html

[D04] 删除元素
来源：http://dali.cashguo.top/Article/details/gtlnnvzles.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yongpay.top/Article/details/gtdtxuqhfz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xylfe.cn/Article/details/gtemvdwqtt.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.pengpengdd.cyou/Article/details/gtkjsxyrqe.html

TS:   arr.splice(0, 1);
来源：http://dali.nwbrower.top/Article/details/gtystqotja.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtdpgeysrz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.tanke756.top/Article/details/gtplajqqop.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.dashuyun.cn/Article/details/gtddwaopty.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.mhx1999.top/Article/details/gtopmklshu.html

[D05] 访问与修改元素
来源：http://dali.dashuyun.cn/Article/details/gtuirxfujg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ivvv.top/Article/details/gtvwjkvife.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.mhx1999.top/Article/details/gtdkhnbrxz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yongpay.top/Article/details/gtbqxjzfkx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.daxiang520.top/Article/details/gtkrjlosre.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cdnleiting.top/Article/details/gtcohwcsvw.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfqukixkm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.feifeiyinyue.top/Article/details/gtftfwpxla.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yj202588.top/Article/details/gthpjyczdk.html

[D06] 数组长度
来源：http://dali.quarkkingdee.top/Article/details/gtjhxnrzff.html

Py:   len(arr)
来源：http://dali.ehwqpu.com/Article/details/gtbwceyiij.html

PHP:  count($arr);
来源：http://dali.meibo888.top/Article/details/gtbqfkavww.html

JS:   arr.length
来源：http://dali.fengsongda.top/Article/details/gtmlcqeoal.html

TS:   arr.length
来源：http://dali.dashuyun.cn/Article/details/gtesqkjnzy.html

Java: list.size();
来源：http://dali.zdqjudy.top/Article/details/gtfaykhxhx.html

Go:   len(arr)
来源：http://dali.svipenyu.cn/Article/details/gtgyhdpzwz.html

Ruby: arr.length; arr.size
来源：http://dali.dianchejie.cn/Article/details/gtgmkvjfie.html

C#:   list.Count;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlrqqgrku.html

[D07] 切片 / 取子数组
来源：http://dali.daria6918.cn/Article/details/gthuaqbftd.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jlsjyb.cn/Article/details/gtgydnmpgo.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.fzhhl.top/Article/details/gtaifxbbxf.html

JS:   arr.slice(1, 4);
来源：http://dali.vqdsnc.cn/Article/details/gtbkuaapmf.html

TS:   arr.slice(1, 4);
来源：http://dali.yvedp.cn/Article/details/gtskddsuvm.html

Java: list.subList(1, 4);
来源：http://dali.zhongyouzk.top/Article/details/gtzatmorhi.html

Go:   arr[1:4]
来源：http://dali.aizwys.cn/Article/details/gtdbojgmci.html

Ruby: arr[1, 3]
来源：http://dali.gzhubu.top/Article/details/gtzaxqbzrj.html

C#:   list.GetRange(1, 3);
来源：http://dali.ppjwa.cn/Article/details/gtgixmpykz.html

[D08] 合并两个数组
来源：http://dali.tian-w.cn/Article/details/gtinfqktng.html

Py:   a + b;  a.extend(b)
来源：http://dali.ehwqpu.com/Article/details/gtwoaqjfgr.html

PHP:  array_merge($a, $b);
来源：http://dali.c1oappe.top/Article/details/gtdkimvfvn.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.fengsongda.top/Article/details/gtvkbnotut.html

TS:   [...a, ...b];
来源：http://dali.yj20258888.top/Article/details/gtwghngnfh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yj202588.top/Article/details/gtipzauzml.html

Go:   append(a, b...)
来源：http://dali.tian-w.cn/Article/details/gtfjxitxie.html

Ruby: a + b;  a.concat(b)
来源：http://dali.9152youxi.cn/Article/details/gtwkdsypig.html

C#:   a.Concat(b).ToList()
来源：http://dali.0kj1m.cn/Article/details/gthstqhxhd.html

[D09] 排序（升序）
来源：http://dali.cheryme.top/Article/details/gtrphbcjcd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tian-w.cn/Article/details/gtqbdzmlqo.html

PHP:  sort($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtrhnqhmop.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.9152youxi.cn/Article/details/gtxracfazu.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.nanxinkj.top/Article/details/gtbdqxttuz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cdnleiting.top/Article/details/gtzvlzumix.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinqigufen.top/Article/details/gtnejdzfno.html

Ruby: arr.sort
来源：http://dali.yj20258888.top/Article/details/gthxalmwcm.html

C#:   list.Sort();
来源：http://dali.aizwys.cn/Article/details/gtfvuapvxm.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.tian-w.cn/Article/details/gttizqesms.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.bjfxy.top/Article/details/gtcvrqvgks.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cdnleiting.top/Article/details/gtnpljsehw.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinqigufen.top/Article/details/gtbqhdnjyg.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dianchejie.cn/Article/details/gtrwyvljro.html


<!-- 参考信息 -->