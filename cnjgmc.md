代发 wailian999

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnqzz.top/Article/details/gtdnqgyjbi.html

[B10] 遍历同时拿索引
来源：http://dali.sufxvd.cn/Article/details/gtyocdoctm.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.kuanghao11.cn/Article/details/gtrzfvzeqy.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yonumen.top/Article/details/gtsajzyuaw.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.ppjwa.cn/Article/details/gtmjozcbyi.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shuidangran.top/Article/details/gtzuhsxfll.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hnqzz.top/Article/details/gtcibzxvgx.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.cdnleiting.top/Article/details/gtosrgbiky.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jlsjyb.cn/Article/details/gtwapoavpk.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.daxiang520.top/Article/details/gtcuylbslk.html

[B11] 生成数字序列 / 区间
来源：http://dali.cqqwz.cn/Article/details/gtgeqexhfz.html

Py:   list(range(0, 10, 2))
来源：http://dali.vqdsnc.cn/Article/details/gtjpkxvfhr.html

PHP:  range(0, 10, 2);
来源：http://dali.guannengcc.top/Article/details/gtxlkuican.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ydzc1.top/Article/details/gteauggant.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cdnleiting.top/Article/details/gtjaldmhrr.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jinqigufen.top/Article/details/gtgcileqwg.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwkwbphhk.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zdqjudy.top/Article/details/gtfovwfhxy.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jqgfzy.top/Article/details/gtubjhzypf.html

[B12] 跳出多层循环
来源：http://dali.quarkkingdee.top/Article/details/gtajblbpat.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.pengpengdd.cyou/Article/details/gttsbuyims.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.guowangkeji.top/Article/details/gtrmrpwsxb.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cashguo.top/Article/details/gtddjlcvhj.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangshuangyany.cn/Article/details/gtcrrmnpcr.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.smart0.xyz/Article/details/gtyqfhqxxt.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.havefunace.top/Article/details/gtpohbrdli.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xinyue.icu/Article/details/gtdurzonru.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yueranfly.top/Article/details/gtezlnoubl.html

[B13] 判断是否为数字
来源：http://dali.birdmap.top/Article/details/gtqjetmiye.html

Py:   isinstance(x, (int, float))
来源：http://dali.316326.xyz/Article/details/gtagsmfobd.html

PHP:  is_numeric($x)
来源：http://dali.quarkkingdee.top/Article/details/gtnubmjfcz.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtcxpdclly.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrauuxidl.html

Java: x instanceof Number
来源：http://dali.zhixingplan.top/Article/details/gtpimekelu.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.pengpengdd.cyou/Article/details/gtoorbqqat.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xylfe.cn/Article/details/gthyoonsei.html

C#:   x is int or double or decimal
来源：http://dali.smart0.xyz/Article/details/gtebeiqqhk.html

[B14] 判断值是否在集合内
来源：http://dali.daxiang520.top/Article/details/gtyvmkwtqc.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.havefunace.top/Article/details/gtebixuowb.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.sufxvd.cn/Article/details/gtalksbdhi.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.fengsongda.top/Article/details/gtwpsplqus.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtqnpglorf.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.xziqi.cn/Article/details/gtttzisatm.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.daria6918.cn/Article/details/gtsxyxpeon.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jyoumei.cn/Article/details/gtkkjbgxde.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxjnhtgab.html

[B15] 布尔运算与取反
来源：http://dali.pengpengdd.cyou/Article/details/gtgdhebdpv.html

Py:   a and b or not c
来源：http://dali.svipenyu.cn/Article/details/gtpmyzywho.html

PHP:  $a && $b || !$c
来源：http://dali.c1oappe.top/Article/details/gtrrkgjlvh.html

JS:   a && b || !c
来源：http://dali.gzhubu.top/Article/details/gtpugxnhnd.html

TS:   a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gtinvpqfue.html

Java: a && b || !c
来源：http://dali.havefunace.top/Article/details/gtthbqfedy.html

Go:   a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gtrajgtfpr.html

Ruby: a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gtrgcluddp.html

C#:   a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gtlfurviio.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jiagoushi.top/Article/details/gtnqaxzzzw.html

Py:   if not data: return
来源：http://dali.gotoacloud.top/Article/details/gthhsermqq.html

PHP:  if (!$data) { return; }
来源：http://dali.yonumen.top/Article/details/gtgedzkrna.html

JS:   if (!data) return;
来源：http://dali.xuetiantiany.cn/Article/details/gtbukllqic.html

TS:   if (!data) return;
来源：http://dali.sufxvd.cn/Article/details/gtrecrfuja.html

Java: if (data == null) return;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtereubkoe.html

Go:   if data == nil { return }
来源：http://dali.tianlin.xyz/Article/details/gtfuergdhg.html

Ruby: return if data.nil?
来源：http://dali.daxiang520.top/Article/details/gtftqwoxsa.html

C#:   if (data == null) return;
来源：http://dali.pengpengdd.cyou/Article/details/gtpiszjxsi.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtixkcyrhu.html

C. 函数与作用域
来源：http://dali.gogol.net.cn/Article/details/gtnteqnsaw.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtcwugizug.html

[C01] 定义函数
来源：http://dali.yj20258888.top/Article/details/gtrqkjjcic.html

Py:   def add(a, b): return a + b
来源：http://dali.xuetiantiany.cn/Article/details/gtfuvidkhj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xylfe.cn/Article/details/gtqxlynncl.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gtltlmmadt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gtxadggnmw.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtbptvdqqm.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxupbblfs.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ydzc1.top/Article/details/gtdxhpqaxy.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gtjnshbbhi.html

[C02] 默认参数
来源：http://dali.yongpay.top/Article/details/gtaewbsjtc.html

Py:   def greet(name="World"): return name
来源：http://dali.c1oappe.top/Article/details/gtnlocvors.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yuxming.cn/Article/details/gtzbddmldo.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shuidangran.top/Article/details/gtaxiyoxaf.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hammf.cn/Article/details/gtcgsoypfz.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jqgfzy.top/Article/details/gtlqfcadmi.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.fengsongda.top/Article/details/gtxydcfhxi.html

Ruby: def greet(name = "World") = name
来源：http://dali.xziqi.cn/Article/details/gtdwvvnjxe.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.9152youxi.cn/Article/details/gtuhhjinvt.html

[C03] 可变参数
来源：http://dali.wangdashe.top/Article/details/gtsndlnxzv.html

Py:   def total(*args): return sum(args)
来源：http://dali.9152youxi.cn/Article/details/gthbelovvt.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.sysykeji.top/Article/details/gtyecjdeet.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.wangshuangyany.cn/Article/details/gtomgnplru.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttvpksygq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.fengsongda.top/Article/details/gtjngajweu.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jiagoushi.top/Article/details/gtfpxusmfm.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.bjfxy.top/Article/details/gthvnztsop.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.gzhubu.top/Article/details/gtyoxyzdur.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxqftdpsb.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hywenlv.cn/Article/details/gtiowarhtz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yj202588.top/Article/details/gtmxtsgiqc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.snrcjt.cn/Article/details/gtfxtjxtmf.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhongyouzk.top/Article/details/gtwdojchdd.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.kuanghao11.cn/Article/details/gthdyyryev.html

Go:   // 无：用配置结构体参数
来源：http://dali.ehwqpu.com/Article/details/gtbjtssyaa.html

Ruby: f(a: 1, b: 2)
来源：http://dali.quarkkingdee.top/Article/details/gtyepykyqe.html

C#:   f(a: 1, b: 2)
来源：http://dali.birdmap.top/Article/details/gtasnucqjp.html

[C05] 返回多个值
来源：http://dali.smart0.xyz/Article/details/gtmisossnz.html

Py:   return a, b
来源：http://dali.ivvv.top/Article/details/gtczaxprah.html

PHP:  return [$a, $b];
来源：http://dali.zhiwuduotai.top/Article/details/gtymlogfbx.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.0kj1m.cn/Article/details/gtqdactaqk.html

TS:   return { a, b };
来源：http://dali.birdmap.top/Article/details/gtrxcgvrbn.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sweek.top/Article/details/gtlflcmkuv.html

Go:   return a, b
来源：http://dali.yongpay.top/Article/details/gtvxleytub.html

Ruby: return a, b
来源：http://dali.wangshuangyany.cn/Article/details/gtkdhyixun.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.smart0.xyz/Article/details/gtfaflrsjk.html

[C06] 匿名函数 / lambda
来源：http://dali.hongshengwenyu.top/Article/details/gtdpqeoxar.html

Py:   square = lambda x: x * x
来源：http://dali.xziqi.cn/Article/details/gtcbpakjxm.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jqgufenzy.top/Article/details/gtvjbhddqk.html

JS:   const square = x => x * x;
来源：http://dali.zdqjudy.top/Article/details/gtdekapeet.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.aibaodan.cn/Article/details/gtrtqxeisw.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jqgfzy.top/Article/details/gtoqeyzewn.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hnqzz.top/Article/details/gtdmztrhhs.html

Ruby: square = ->(x) { x * x }
来源：http://dali.bjfxy.top/Article/details/gtukwcaone.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.meibo888.top/Article/details/gtmpvmcbxv.html

[C07] 把函数作为参数传入
来源：http://dali.zhiwuduotai.top/Article/details/gtuclbjhnh.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jqgufenzy.top/Article/details/gtkmhplugm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.smart0.xyz/Article/details/gtppeejfsg.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.gzhubu.top/Article/details/gtelaghjeb.html

TS:   arr.map(String)
来源：http://dali.hnqzz.top/Article/details/gtyzrjatgp.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.tianlin.xyz/Article/details/gtwumwgnpe.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.wangdashe.top/Article/details/gtpxquopps.html

Ruby: arr.map(&:upcase)
来源：http://dali.gzhubu.top/Article/details/gtqxeafivq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.guannengcc.top/Article/details/gtgbzuwhmv.html

[C08] 闭包
来源：http://dali.yongpay.top/Article/details/gtpkweitrb.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.daria6918.cn/Article/details/gtxyrbxaah.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.pycfn.com/Article/details/gtjsnxdhxr.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yongpay.top/Article/details/gtgphjkcog.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.shuidangran.top/Article/details/gtpulhyflf.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shanyushiyangkeji.top/Article/details/gtypicophe.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwegpqhip.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yueranfly.top/Article/details/gtrpthweny.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.c1oappe.top/Article/details/gtdppmlgrl.html

[C09] 递归
来源：http://dali.andypj.xyz/Article/details/gtlaxfuohq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtagpjbudv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.smart0.xyz/Article/details/gtssakysgc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cucudq.cn/Article/details/gtukzaxugk.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.quarkkingdee.top/Article/details/gthobrildh.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.0kj1m.cn/Article/details/gtsvaenykp.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jinqigufen.top/Article/details/gtupwxcphv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jqgufenzy.top/Article/details/gtxwztzfgb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.redwolf501.top/Article/details/gtsisqslbw.html

[C10] 变量作用域
来源：http://dali.sweek.top/Article/details/gtupuobwfx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.chenlongwang.top/Article/details/gtnqkhymhn.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhoulong.xyz/Article/details/gtsypojrsc.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.snrcjt.cn/Article/details/gtjkwdduop.html

TS:   同 JS
来源：http://dali.tianlin.xyz/Article/details/gtytonfioy.html

Java: 方法内为块级作用域
来源：http://dali.yongpay.top/Article/details/gtnfqtmiav.html

Go:   花括号块级作用域
来源：http://dali.mhx1999.top/Article/details/gtlebzugbu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.mhx1999.top/Article/details/gtatuexyxd.html

C#:   块级作用域
来源：http://dali.chenlongwang.top/Article/details/gtgiliuiaj.html

[C11] 模块导入与导出
来源：http://dali.shuidangran.top/Article/details/gtdmjdpbkk.html

Py:   from module import func
来源：http://dali.fengsongda.top/Article/details/gtbwwjfcmk.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttuswvbba.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sxryk.cn/Article/details/gttygqyjfn.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.vqdsnc.cn/Article/details/gtywcefvld.html

Java: import java.util.List;
来源：http://dali.hfpthk.cn/Article/details/gtmnykhehi.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.dashuyun.cn/Article/details/gtmumuizrx.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.wangdashe.top/Article/details/gtfdlgtzze.html

C#:   using System.Text;
来源：http://dali.tianlin.xyz/Article/details/gtfydmfqdr.html

[C12] 立即执行函数 IIFE
来源：http://dali.xuanzx.com/Article/details/gtyavoxlci.html

Py:   (lambda: print("run"))()
来源：http://dali.nanxinkj.top/Article/details/gtrlzenaew.html

PHP:  (function () { echo "run"; })();
来源：http://dali.wangdashe.top/Article/details/gtvxzwizri.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinqigfzy.top/Article/details/gtnchvyrwy.html

TS:   (() => { console.log("run"); })();
来源：http://dali.gotoacloud.top/Article/details/gtrrhvyhcd.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.meibo888.top/Article/details/gtcpbwnncd.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrdsoscec.html

Ruby: -> { puts "run" }.call
来源：http://dali.yangfankeji.com/Article/details/gtvgqazoir.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yuanzhike.top/Article/details/gtasxponba.html

[C13] 类型声明 / 类型注解
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsdhisoqx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.dianchejie.cn/Article/details/gtmqfgzefd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtxjbpeaob.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.aizwys.cn/Article/details/gtwnymqdlh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gtaqmzvgms.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gtjaovckuz.html

Go:   func add(a, b int) int
来源：http://dali.zhoulong.xyz/Article/details/gtilpahpfi.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxnhizmbj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.havefunace.top/Article/details/gtdmxugejx.html

[C14] 泛型函数
来源：http://dali.yj20258888.top/Article/details/gtdlwthnoh.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.c1oappe.top/Article/details/gtwjxtmutx.html

PHP:  // 无泛型
来源：http://dali.zhoulong.xyz/Article/details/gtrdidxqvu.html

JS:   // 无泛型
来源：http://dali.hfpthk.cn/Article/details/gtlfecwepm.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.vqdsnc.cn/Article/details/gtybcbrlfp.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xylfe.cn/Article/details/gtnpairgnn.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.aibaodan.cn/Article/details/gtgzsycuia.html

Ruby: # 无泛型
来源：http://dali.xinyue.icu/Article/details/gtkkljzapn.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yj20258.top/Article/details/gtbyxazxvh.html

[C15] 解构 / 展开参数
来源：http://dali.jinqigfzy.top/Article/details/gtsglunjbp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.bjfxy.top/Article/details/gtyodsygqi.html

PHP:  [$a, $b] = $pair;
来源：http://dali.nwbrower.top/Article/details/gtkmttbfoc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.chenlongwang.top/Article/details/gtidmahbwy.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtywnqmvbm.html

Java: // 无解构
来源：http://dali.316326.xyz/Article/details/gtbhsouwhz.html

Go:   // 无解构
来源：http://dali.yvedp.cn/Article/details/gtpppfkcyr.html

Ruby: a, b = pair
来源：http://dali.yuxming.cn/Article/details/gtlsxxpwub.html

C#:   var (a, b) = pair;
来源：http://dali.hnxiangtu.top/Article/details/gtvwdiuqcb.html

[C16] 函数 / 方法重载
来源：http://dali.cdnleiting.top/Article/details/gtuqkhmjzd.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yuxming.cn/Article/details/gtozeeugrw.html

PHP:  // 无重载
来源：http://dali.xuetiantiany.cn/Article/details/gteszpuqkv.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hywenlv.cn/Article/details/gtwtqebbgw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jiagoushi.top/Article/details/gtmmidvsnq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtikqvlkng.html

Go:   // 无重载：用不同函数名
来源：http://dali.c1oappe.top/Article/details/gtxtejmjlq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.smart0.xyz/Article/details/gtgfalrsaq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hnxiangtu.top/Article/details/gtzqtrlcik.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtmmgiepyg.html

D. 数组 / 列表 / 集合
来源：http://dali.hnqzz.top/Article/details/gtaunuzqed.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtqinrfbns.html

[D01] 创建数组 / 列表
来源：http://dali.ybcxt.top/Article/details/gtrgfvyqtk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gotoacloud.top/Article/details/gtplaimorf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdybiauzj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.andypj.xyz/Article/details/gtjakhgqnu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.guannengcc.top/Article/details/gteblzzydt.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhongyouzk.top/Article/details/gtmtfiklga.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xuanzx.com/Article/details/gtxmggyvwd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yonumen.top/Article/details/gtaoegolls.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jyoumei.cn/Article/details/gtqakumcgs.html

[D02] 追加元素到末尾
来源：http://dali.cheryme.top/Article/details/gtsjqksuxt.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxhfsphcq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xinyue.icu/Article/details/gtoajifgkt.html

JS:   arr.push(4);
来源：http://dali.daria6918.cn/Article/details/gtoyitbpxi.html

TS:   arr.push(4);
来源：http://dali.pengpengdd.cyou/Article/details/gtkckemhtq.html

Java: list.add(4);
来源：http://dali.daria6918.cn/Article/details/gtbtnircnm.html

Go:   arr = append(arr, 4)
来源：http://dali.fzhhl.top/Article/details/gtjjswzrxd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.pengpengdd.cyou/Article/details/gtogblkehp.html

C#:   list.Add(4);
来源：http://dali.nanxuanxn.top/Article/details/gtjommssje.html

[D03] 在指定位置插入元素
来源：http://dali.ybcxt.top/Article/details/gtgwqecivw.html

Py:   arr.insert(0, 0)
来源：http://dali.bjfxy.top/Article/details/gtzobrdufe.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhengqikj.top/Article/details/gtckyzjrxf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.wangshuangyany.cn/Article/details/gtldgxxsug.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.bjfxy.top/Article/details/gtmuwhiptx.html

Java: list.add(0, 0);
来源：http://dali.sweek.top/Article/details/gtuanogjzo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.haohaochexian.top/Article/details/gtobaxgmyy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinqigfzy.top/Article/details/gtuywjiouf.html

C#:   list.Insert(0, 0);
来源：http://dali.zhixingplan.top/Article/details/gtgvfsylxj.html

[D04] 删除元素
来源：http://dali.aibaodan.cn/Article/details/gtytgiilun.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.tanke756.top/Article/details/gtmiscsqch.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtqnybnfly.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.fzhhl.top/Article/details/gtzlrqqvfg.html

TS:   arr.splice(0, 1);
来源：http://dali.0kj1m.cn/Article/details/gtbpcqwpvk.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hammf.cn/Article/details/gtakxvpfbt.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.c1oappe.top/Article/details/gtiqttddwg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtqlaafsgs.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hfpthk.cn/Article/details/gtepwneepo.html

[D05] 访问与修改元素
来源：http://dali.andypj.xyz/Article/details/gtsrxljxsg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gotoacloud.top/Article/details/gthhwhmhsl.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jqgufenzy.top/Article/details/gtjgfssubz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.dashuyun.cn/Article/details/gttokxsmat.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xuetiantiany.cn/Article/details/gtvrsvqdml.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zdqjudy.top/Article/details/gtnyyqoxch.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gotoacloud.top/Article/details/gtvxxqcglj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.haohaochexian.top/Article/details/gtiwmcoiid.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gotoacloud.top/Article/details/gtkgcrpqoc.html

[D06] 数组长度
来源：http://dali.fengsongda.top/Article/details/gtdaxcxdun.html

Py:   len(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtehrdszuu.html

PHP:  count($arr);
来源：http://dali.cheryme.top/Article/details/gtvbbdpekg.html

JS:   arr.length
来源：http://dali.jlsjyb.cn/Article/details/gtygwfommz.html

TS:   arr.length
来源：http://dali.dashuyun.cn/Article/details/gtaeufbhgm.html

Java: list.size();
来源：http://dali.chenzaomai.com/Article/details/gtanyhppvv.html

Go:   len(arr)
来源：http://dali.daria6918.cn/Article/details/gtzuotqwmh.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gtnurduope.html

C#:   list.Count;
来源：http://dali.jqgfzy.top/Article/details/gtmgsvkdet.html

[D07] 切片 / 取子数组
来源：http://dali.9152youxi.cn/Article/details/gtniohiqgu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xziqi.cn/Article/details/gtrokfdlsp.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ybcxt.top/Article/details/gtxbohtbef.html

JS:   arr.slice(1, 4);
来源：http://dali.jyoumei.cn/Article/details/gtouhasjzs.html

TS:   arr.slice(1, 4);
来源：http://dali.daria6918.cn/Article/details/gtdrnllszf.html

Java: list.subList(1, 4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcrbbuung.html

Go:   arr[1:4]
来源：http://dali.hongshengwenyu.top/Article/details/gtemrllccs.html

Ruby: arr[1, 3]
来源：http://dali.xinyue.icu/Article/details/gtabxrnvef.html

C#:   list.GetRange(1, 3);
来源：http://dali.pycfn.com/Article/details/gtzpymqdxs.html

[D08] 合并两个数组
来源：http://dali.jqgfzy.top/Article/details/gthiipgavb.html

Py:   a + b;  a.extend(b)
来源：http://dali.aibaodan.cn/Article/details/gtvvgyvxry.html

PHP:  array_merge($a, $b);
来源：http://dali.yueranfly.top/Article/details/gtnerbvpuq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.tian-w.cn/Article/details/gtdntbbmzc.html

TS:   [...a, ...b];
来源：http://dali.redwolf501.top/Article/details/gtksfzxzhx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhoulong.xyz/Article/details/gtdxjkopiw.html

Go:   append(a, b...)
来源：http://dali.zhixingplan.top/Article/details/gtnakhnest.html

Ruby: a + b;  a.concat(b)
来源：http://dali.nanxuanxn.top/Article/details/gtqspvucxm.html

C#:   a.Concat(b).ToList()
来源：http://dali.yonumen.top/Article/details/gtavzrsawo.html

[D09] 排序（升序）
来源：http://dali.zhongyouzk.top/Article/details/gthkgkgmgl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yangfankeji.com/Article/details/gtnticnrpe.html

PHP:  sort($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtmsmrqdsc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.sxryk.cn/Article/details/gtfjkzxwlz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cqqwz.cn/Article/details/gtxekoppuk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hongshengwenyu.top/Article/details/gtvidzmzev.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtxsitqisx.html

Ruby: arr.sort
来源：http://dali.dashuyun.cn/Article/details/gtrxgebwta.html

C#:   list.Sort();
来源：http://dali.yueranfly.top/Article/details/gtjkytkgjr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcusxxicg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.havefunace.top/Article/details/gtzebsgpzu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shangyingyoupin.top/Article/details/gtdkofkbzb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gogol.net.cn/Article/details/gtwwahawfm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hongshengwenyu.top/Article/details/gtbcqktwny.html


<!-- 参考信息 -->