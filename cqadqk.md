代发 wailian999

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zycfv.cn/Article/details/gtyibvtgfw.html

[B10] 遍历同时拿索引
来源：http://dali.wangshuangyany.cn/Article/details/gtbjslxoqt.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ivvv.top/Article/details/gtvcwihxnv.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zycfv.cn/Article/details/gtzhdomlyp.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jianghu66.top/Article/details/gtravrepsc.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.dianchejie.cn/Article/details/gtvdxlfhtc.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hysaishi.cn/Article/details/gtzhcyuolo.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.nanxuanxn.top/Article/details/gthpfdzflz.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.gotoacloud.top/Article/details/gtkzdghmtx.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yvedp.cn/Article/details/gtjuqvpcup.html

[B11] 生成数字序列 / 区间
来源：http://dali.xziqi.cn/Article/details/gtzfcochbm.html

Py:   list(range(0, 10, 2))
来源：http://dali.chenjidiqi.icu/Article/details/gtoxkelwki.html

PHP:  range(0, 10, 2);
来源：http://dali.cqqwz.cn/Article/details/gtuwohbvuu.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yuxming.cn/Article/details/gtdsegzolu.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.birdmap.top/Article/details/gteqztrddb.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.chenzaomai.com/Article/details/gtsjqgbgjv.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hammf.cn/Article/details/gtuaexjccs.html

Ruby: (0...10).step(2).to_a
来源：http://dali.kuanghao11.cn/Article/details/gthukbywms.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.guannengcc.top/Article/details/gtabjyeeze.html

[B12] 跳出多层循环
来源：http://dali.svipenyu.cn/Article/details/gtvaergpgb.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.fengsongda.top/Article/details/gtbrudfuqe.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhengqikj.top/Article/details/gtxjrzmpfl.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgufenzy.top/Article/details/gtbefgyzmh.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zycfv.cn/Article/details/gtvscbuooy.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.pengpengdd.cyou/Article/details/gtmsjrtpjl.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ppjwa.cn/Article/details/gtxitxwvek.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.wangshuangyany.cn/Article/details/gtknywbqhw.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.redwolf501.top/Article/details/gtljtzbijs.html

[B13] 判断是否为数字
来源：http://dali.zhengqikj.top/Article/details/gteqsddgjp.html

Py:   isinstance(x, (int, float))
来源：http://dali.cheryme.top/Article/details/gtezjuvcum.html

PHP:  is_numeric($x)
来源：http://dali.haohaochexian.top/Article/details/gtfslgvvqf.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hfpthk.cn/Article/details/gtgeemdbck.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yonumen.top/Article/details/gtztgniwjn.html

Java: x instanceof Number
来源：http://dali.mhx1999.top/Article/details/gtzngpxudy.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhengqikj.top/Article/details/gtpadwsvut.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shuidangran.top/Article/details/gthfxbkjcj.html

C#:   x is int or double or decimal
来源：http://dali.yuxming.cn/Article/details/gticcrknoe.html

[B14] 判断值是否在集合内
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtljnamtbm.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.fengsongda.top/Article/details/gtknlokptw.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbnovqzls.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.mhx1999.top/Article/details/gtprdbanof.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhoulong.xyz/Article/details/gtmvmfhhsj.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.xylfe.cn/Article/details/gtmpdyfbox.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.aizwys.cn/Article/details/gtmcvzvlag.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.cheryme.top/Article/details/gtukxvfrpb.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.andypj.xyz/Article/details/gtiqvyqggj.html

[B15] 布尔运算与取反
来源：http://dali.wangshuangyany.cn/Article/details/gtihazsped.html

Py:   a and b or not c
来源：http://dali.tanke756.top/Article/details/gtttpfgalf.html

PHP:  $a && $b || !$c
来源：http://dali.nanxinkj.top/Article/details/gtxagcegis.html

JS:   a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gtfxchzmsa.html

TS:   a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gtnaeshnwq.html

Java: a && b || !c
来源：http://dali.cucudq.cn/Article/details/gtxzzylnir.html

Go:   a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gtgseczwsc.html

Ruby: a && b || !c
来源：http://dali.yongpay.top/Article/details/gtvafvqvzb.html

C#:   a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gtsogdvpie.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.gotoacloud.top/Article/details/gtyvgvkfou.html

Py:   if not data: return
来源：http://dali.daria6918.cn/Article/details/gtrmdhfqmn.html

PHP:  if (!$data) { return; }
来源：http://dali.jyoumei.cn/Article/details/gteajopsfo.html

JS:   if (!data) return;
来源：http://dali.ehwqpu.com/Article/details/gtkuoeycez.html

TS:   if (!data) return;
来源：http://dali.ydzc1.top/Article/details/gtgucfoohp.html

Java: if (data == null) return;
来源：http://dali.tian-w.cn/Article/details/gtrtcpytdp.html

Go:   if data == nil { return }
来源：http://dali.316326.xyz/Article/details/gtlozfdyjh.html

Ruby: return if data.nil?
来源：http://dali.hywenlv.cn/Article/details/gthiprcymx.html

C#:   if (data == null) return;
来源：http://dali.pycfn.com/Article/details/gtmmavnesp.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtwbvlxooy.html

C. 函数与作用域
来源：http://dali.sweek.top/Article/details/gtxqkziwob.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtzpgqtdsu.html

[C01] 定义函数
来源：http://dali.kuanghao11.cn/Article/details/gtjdgwjyka.html

Py:   def add(a, b): return a + b
来源：http://dali.shanyushiyangtech.top/Article/details/gtfinvouii.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gtciyorlhi.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gteoigonei.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gtschoihps.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gtqboxqail.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yanxiufei.cn/Article/details/gtllxyfhjw.html

Ruby: def add(a, b); a + b; end
来源：http://dali.0kj1m.cn/Article/details/gterztopvd.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gtocuxaxvs.html

[C02] 默认参数
来源：http://dali.snrcjt.cn/Article/details/gtetpiigrt.html

Py:   def greet(name="World"): return name
来源：http://dali.jinqigfzy.top/Article/details/gtdadaalse.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jyoumei.cn/Article/details/gthqcpnfqt.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yj20258888.top/Article/details/gtzjglgijk.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.shuidangran.top/Article/details/gtcjqkpgsi.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.dianchejie.cn/Article/details/gtzyxydhei.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.smart0.xyz/Article/details/gtofzfftac.html

Ruby: def greet(name = "World") = name
来源：http://dali.feifeiyinyue.top/Article/details/gttyyyfsni.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.sxryk.cn/Article/details/gtlyucrvhx.html

[C03] 可变参数
来源：http://dali.yongpay.top/Article/details/gtpaaeuwfd.html

Py:   def total(*args): return sum(args)
来源：http://dali.meibo888.top/Article/details/gtbwgirrfz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hnxiangtu.top/Article/details/gtvhxmqfdk.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.smart0.xyz/Article/details/gtfpqpkxww.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.quarkkingdee.top/Article/details/gtiovnhdfa.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jqgfzy.top/Article/details/gtphzkyurs.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.shangyingyoupin.top/Article/details/gtrrjympjp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.svipenyu.cn/Article/details/gtelzwuifp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jyoumei.cn/Article/details/gtyohhnxen.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shzxlz.cn/Article/details/gteflqhlgf.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhoulong.xyz/Article/details/gtwvjwcavi.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.tian-w.cn/Article/details/gtzodssior.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cdnleiting.top/Article/details/gtcvrrokqh.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.nanxuanxn.top/Article/details/gturwjklna.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiqkukixt.html

Go:   // 无：用配置结构体参数
来源：http://dali.guannengcc.top/Article/details/gtrhvwyshq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.redwolf501.top/Article/details/gttouflndb.html

C#:   f(a: 1, b: 2)
来源：http://dali.dianchejie.cn/Article/details/gtukzfszfk.html

[C05] 返回多个值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtznzkcvfp.html

Py:   return a, b
来源：http://dali.yangfankeji.com/Article/details/gtknmpwguw.html

PHP:  return [$a, $b];
来源：http://dali.yongpay.top/Article/details/gtbfaqhkti.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.fzhhl.top/Article/details/gtmygbvwdt.html

TS:   return { a, b };
来源：http://dali.zycfv.cn/Article/details/gtcvsbhicc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.svipenyu.cn/Article/details/gtyjedkgwy.html

Go:   return a, b
来源：http://dali.jinyuanbaomall.cn/Article/details/gttvfvpnqq.html

Ruby: return a, b
来源：http://dali.pycfn.com/Article/details/gtizhfpftf.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cdnleiting.top/Article/details/gtucrpgvng.html

[C06] 匿名函数 / lambda
来源：http://dali.jiagoushi.top/Article/details/gtaliujlqe.html

Py:   square = lambda x: x * x
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdfbkvrdw.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zdqjudy.top/Article/details/gtiicoteyl.html

JS:   const square = x => x * x;
来源：http://dali.feifeiyinyue.top/Article/details/gtgoddrjiw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yvedp.cn/Article/details/gtkgakftgr.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlznboyvc.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.wangdashe.top/Article/details/gtmiuwjksg.html

Ruby: square = ->(x) { x * x }
来源：http://dali.gogol.net.cn/Article/details/gtyulphpsk.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ivvv.top/Article/details/gthowfaiao.html

[C07] 把函数作为参数传入
来源：http://dali.gotoacloud.top/Article/details/gtpbwkylhu.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yangfankeji.com/Article/details/gtggklpxse.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtikfotflx.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.nanxuanxn.top/Article/details/gtzrvzogpd.html

TS:   arr.map(String)
来源：http://dali.yangfankeji.com/Article/details/gtqizfbmbn.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jyoumei.cn/Article/details/gtzxbyavlv.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvconbfeb.html

Ruby: arr.map(&:upcase)
来源：http://dali.aibaodan.cn/Article/details/gtsxdeymil.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.tianlin.xyz/Article/details/gtpyazuhtx.html

[C08] 闭包
来源：http://dali.dashuyun.cn/Article/details/gtacthhfkz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cheryme.top/Article/details/gtolvgnkzw.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.daria6918.cn/Article/details/gtjytejhlv.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jinqigfzy.top/Article/details/gtnkhxovsr.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yuxming.cn/Article/details/gtkyfzfsao.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjjmjhepp.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cashguo.top/Article/details/gtaipdvojv.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.aibaodan.cn/Article/details/gtjhxsmjgg.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xinyue.icu/Article/details/gtineqwdzq.html

[C09] 递归
来源：http://dali.jinqigufen.top/Article/details/gtoxnllkfe.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtstcgbbqf.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.meibo888.top/Article/details/gtkgiizsnf.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sysykeji.top/Article/details/gtqeklofpr.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gogol.net.cn/Article/details/gtrdabegoe.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yongpay.top/Article/details/gtkstmmtzt.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jyoumei.cn/Article/details/gtiukfgnfc.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.smart0.xyz/Article/details/gtzinwojsn.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiziarapz.html

[C10] 变量作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbcklutww.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.iojbl.cn/Article/details/gtxxycqwfe.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cashguo.top/Article/details/gtbuouopin.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.fzhhl.top/Article/details/gtwphxxhdu.html

TS:   同 JS
来源：http://dali.chenzaomai.com/Article/details/gtvniubqrl.html

Java: 方法内为块级作用域
来源：http://dali.ydzc1.top/Article/details/gtpmfhoriw.html

Go:   花括号块级作用域
来源：http://dali.birdmap.top/Article/details/gtwlptnhkz.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zycfv.cn/Article/details/gttbubcjtu.html

C#:   块级作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmbgkqupx.html

[C11] 模块导入与导出
来源：http://dali.yuanzhike.top/Article/details/gtyhraxmpl.html

Py:   from module import func
来源：http://dali.zhixingplan.top/Article/details/gtclfhhayx.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.vqdsnc.cn/Article/details/gtyeahbqup.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.guannengcc.top/Article/details/gtkxpxzsjm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.fzhhl.top/Article/details/gtbaaifrwu.html

Java: import java.util.List;
来源：http://dali.mhx1999.top/Article/details/gtdtmwkgzo.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.vqdsnc.cn/Article/details/gtrfjbnetq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cucudq.cn/Article/details/gttznondno.html

C#:   using System.Text;
来源：http://dali.sweek.top/Article/details/gtzmumvfge.html

[C12] 立即执行函数 IIFE
来源：http://dali.tian-w.cn/Article/details/gtsftrzucp.html

Py:   (lambda: print("run"))()
来源：http://dali.xuanzx.com/Article/details/gtyayiwcch.html

PHP:  (function () { echo "run"; })();
来源：http://dali.chenzaomai.com/Article/details/gtqwmkpclz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.chenjidiqi.icu/Article/details/gtyyzozfyl.html

TS:   (() => { console.log("run"); })();
来源：http://dali.nanxinkj.top/Article/details/gtvbxgsmck.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jlsjyb.cn/Article/details/gtiumsadsy.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.snrcjt.cn/Article/details/gtojhifree.html

Ruby: -> { puts "run" }.call
来源：http://dali.hysaishi.cn/Article/details/gtzbvpdqnj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ydzc1.top/Article/details/gtzntkdpoi.html

[C13] 类型声明 / 类型注解
来源：http://dali.dashuyun.cn/Article/details/gtwhocwdxn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhongyouzk.top/Article/details/gtjnbgqhuf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yueranfly.top/Article/details/gtmmwuughj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtijooiccc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtchdnsbyl.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gttycynpcx.html

Go:   func add(a, b int) int
来源：http://dali.jinqigfzy.top/Article/details/gtoezxbnbh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvtumqpgl.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.redwolf501.top/Article/details/gtsnjaxrbq.html

[C14] 泛型函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdfecxvuu.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhiwuduotai.top/Article/details/gtjjuxgazt.html

PHP:  // 无泛型
来源：http://dali.mhx1999.top/Article/details/gtwqlnaelf.html

JS:   // 无泛型
来源：http://dali.nanxinkj.top/Article/details/gtnmembdlx.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xziqi.cn/Article/details/gtqptnqnwf.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgxytabqp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yongpay.top/Article/details/gtgtgpkvnc.html

Ruby: # 无泛型
来源：http://dali.cqqwz.cn/Article/details/gtzofnyzzh.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cqqwz.cn/Article/details/gtssxtdxde.html

[C15] 解构 / 展开参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtysuvuyqh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jqgufenzy.top/Article/details/gtjnctnwhm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.0kj1m.cn/Article/details/gtjlaxfxhw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.pycfn.com/Article/details/gtulylhgxx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhixingplan.top/Article/details/gtzoidpuku.html

Java: // 无解构
来源：http://dali.316326.xyz/Article/details/gtrqawevel.html

Go:   // 无解构
来源：http://dali.316326.xyz/Article/details/gtknkzosym.html

Ruby: a, b = pair
来源：http://dali.yj20258888.top/Article/details/gthjmpnsrr.html

C#:   var (a, b) = pair;
来源：http://dali.zhoulong.xyz/Article/details/gtbkpyqrrs.html

[C16] 函数 / 方法重载
来源：http://dali.tanke756.top/Article/details/gtqyzorsgk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hnqzz.top/Article/details/gtlurprgbi.html

PHP:  // 无重载
来源：http://dali.chenjidiqi.icu/Article/details/gtxepgungh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.pengpengdd.cyou/Article/details/gtbdtcawlh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhoulong.xyz/Article/details/gtmrzeiczh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.birdmap.top/Article/details/gtmxptjlct.html

Go:   // 无重载：用不同函数名
来源：http://dali.jqgufenzy.top/Article/details/gtvietuqxd.html

Ruby: # 无重载：靠动态参数
来源：http://dali.feifeiyinyue.top/Article/details/gtsqsozasg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xuanzx.com/Article/details/gtpgbulmvo.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtxxtvnduo.html

D. 数组 / 列表 / 集合
来源：http://dali.xuanzx.com/Article/details/gtzzdmntvh.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtieihqxbm.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gtdiwhszcm.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnigfldup.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shzxlz.cn/Article/details/gtiltxaovg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.guowangkeji.top/Article/details/gtfurooasp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yuxming.cn/Article/details/gtundcsdxd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.bjfxy.top/Article/details/gttuekffjj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.nanxuanxn.top/Article/details/gtprvynewe.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jlsjyb.cn/Article/details/gtbbhyrpjj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.kuanghao11.cn/Article/details/gtvhqmwlxx.html

[D02] 追加元素到末尾
来源：http://dali.tanke756.top/Article/details/gtayvgegvk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xuanzx.com/Article/details/gteesbskab.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yvedp.cn/Article/details/gtlocuikvp.html

JS:   arr.push(4);
来源：http://dali.aizwys.cn/Article/details/gtgjfnymcq.html

TS:   arr.push(4);
来源：http://dali.cheryme.top/Article/details/gtykdamfsk.html

Java: list.add(4);
来源：http://dali.jyoumei.cn/Article/details/gtgywquppw.html

Go:   arr = append(arr, 4)
来源：http://dali.hywenlv.cn/Article/details/gtnqrgtwvr.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.redwolf501.top/Article/details/gtlafsygbi.html

C#:   list.Add(4);
来源：http://dali.xuetiantiany.cn/Article/details/gtviapawdo.html

[D03] 在指定位置插入元素
来源：http://dali.quarkkingdee.top/Article/details/gtrdpmggdr.html

Py:   arr.insert(0, 0)
来源：http://dali.aibaodan.cn/Article/details/gtgmqsxedw.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hnqzz.top/Article/details/gtllmoermw.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.iojbl.cn/Article/details/gtyhnzxfcx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.sufxvd.cn/Article/details/gtlwmxjxnn.html

Java: list.add(0, 0);
来源：http://dali.yj20258.top/Article/details/gtcuoacrgf.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.kuanghao11.cn/Article/details/gtpxsxssxm.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.feifeiyinyue.top/Article/details/gtnxgzaozd.html

C#:   list.Insert(0, 0);
来源：http://dali.sysykeji.top/Article/details/gtqvabwuis.html

[D04] 删除元素
来源：http://dali.ivvv.top/Article/details/gthxyxuwoz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yuanzhike.top/Article/details/gtverzpqra.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jianghu66.top/Article/details/gtwuxjiukr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sufxvd.cn/Article/details/gtxhahmyyp.html

TS:   arr.splice(0, 1);
来源：http://dali.yueranfly.top/Article/details/gtmxpghnby.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhoulong.xyz/Article/details/gtivnmlxaf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ehwqpu.com/Article/details/gtumstfdff.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.fengsongda.top/Article/details/gtzvwodems.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jlsjyb.cn/Article/details/gtdgwjndyc.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gtjkdekoju.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258888.top/Article/details/gtgsrnqtyz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhixingplan.top/Article/details/gtdadiynoz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.fzhhl.top/Article/details/gtwiifhgzv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhoulong.xyz/Article/details/gtnjebiouw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.316326.xyz/Article/details/gtnyohiujr.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yuanzhike.top/Article/details/gtxaeyekon.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnxiangtu.top/Article/details/gtjlhfqmph.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xuetiantiany.cn/Article/details/gtcvzbtozr.html

[D06] 数组长度
来源：http://dali.chenjidiqi.icu/Article/details/gtbtqooybx.html

Py:   len(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtettfpymf.html

PHP:  count($arr);
来源：http://dali.jinqigufen.top/Article/details/gtriqmrole.html

JS:   arr.length
来源：http://dali.zycfv.cn/Article/details/gtkumyvomi.html

TS:   arr.length
来源：http://dali.daxiang520.top/Article/details/gtzxqbrgya.html

Java: list.size();
来源：http://dali.fengsongda.top/Article/details/gtspesqmfs.html

Go:   len(arr)
来源：http://dali.sufxvd.cn/Article/details/gtjqhxvzoa.html

Ruby: arr.length; arr.size
来源：http://dali.hysaishi.cn/Article/details/gtpsixysfo.html

C#:   list.Count;
来源：http://dali.9152youxi.cn/Article/details/gtmyayajou.html

[D07] 切片 / 取子数组
来源：http://dali.pengpengdd.cyou/Article/details/gtipybnxvu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shzxlz.cn/Article/details/gtwdqonvhf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cdnleiting.top/Article/details/gtidmxjcic.html

JS:   arr.slice(1, 4);
来源：http://dali.daxiang520.top/Article/details/gthwcamzpz.html

TS:   arr.slice(1, 4);
来源：http://dali.haohaochexian.top/Article/details/gteceteamp.html

Java: list.subList(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gtkyhxduql.html

Go:   arr[1:4]
来源：http://dali.nwbrower.top/Article/details/gthiedlngi.html

Ruby: arr[1, 3]
来源：http://dali.chenlongwang.top/Article/details/gtrvfqyntz.html

C#:   list.GetRange(1, 3);
来源：http://dali.guowangkeji.top/Article/details/gtkflpjgoz.html

[D08] 合并两个数组
来源：http://dali.jianghu66.top/Article/details/gtbhkhneqm.html

Py:   a + b;  a.extend(b)
来源：http://dali.zycfv.cn/Article/details/gtvzilnivk.html

PHP:  array_merge($a, $b);
来源：http://dali.hfpthk.cn/Article/details/gtafetihng.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hnqzz.top/Article/details/gtaaccrvle.html

TS:   [...a, ...b];
来源：http://dali.shzxlz.cn/Article/details/gtflktqnbz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.dashuyun.cn/Article/details/gtnnnooqta.html

Go:   append(a, b...)
来源：http://dali.chenzaomai.com/Article/details/gtkiorpxhz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhoulong.xyz/Article/details/gtswthxprp.html

C#:   a.Concat(b).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtjrktazxe.html

[D09] 排序（升序）
来源：http://dali.hongshengwenyu.top/Article/details/gtsulupzso.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtznfothgq.html

PHP:  sort($arr);
来源：http://dali.fzhhl.top/Article/details/gtfutjrcuk.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.0kj1m.cn/Article/details/gttredbfnk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cqqwz.cn/Article/details/gtykoslxmn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ppjwa.cn/Article/details/gtvgheyylu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.wangdashe.top/Article/details/gtqonizovs.html

Ruby: arr.sort
来源：http://dali.tianlin.xyz/Article/details/gtlrxcakoo.html

C#:   list.Sort();
来源：http://dali.aizwys.cn/Article/details/gtphsuandw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.c1oappe.top/Article/details/gtcbfwomnm.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.redwolf501.top/Article/details/gtryzrfyum.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthehglwbm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tianlin.xyz/Article/details/gtktoeymqy.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ppjwa.cn/Article/details/gtplzvsrwi.html


<!-- 参考信息 -->