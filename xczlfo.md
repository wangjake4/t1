代发 wailian999

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenjidiqi.icu/Article/details/gtvgcsdthr.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gtfqfcgfkw.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrdbcsycd.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.daria6918.cn/Article/details/gtfaoystdi.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtnjqzmiuk.html

[B10] 遍历同时拿索引
来源：http://dali.sxryk.cn/Article/details/gtdkuojone.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.snrcjt.cn/Article/details/gtdcormwvu.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.guannengcc.top/Article/details/gtfxpxssnw.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.sufxvd.cn/Article/details/gtgdptotvs.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.havefunace.top/Article/details/gtgwnroylp.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhengqikj.top/Article/details/gtkyzxlksp.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.andypj.xyz/Article/details/gtygvdiwem.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.iojbl.cn/Article/details/gtolehigom.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.birdmap.top/Article/details/gtzhhdagog.html

[B11] 生成数字序列 / 区间
来源：http://dali.sxryk.cn/Article/details/gtmlrwqkoz.html

Py:   list(range(0, 10, 2))
来源：http://dali.yongpay.top/Article/details/gturzmfqnl.html

PHP:  range(0, 10, 2);
来源：http://dali.tanke756.top/Article/details/gtqirsyeos.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.guowangkeji.top/Article/details/gticaiqrou.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.daria6918.cn/Article/details/gtibxlayhd.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.gotoacloud.top/Article/details/gtgbrpllah.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yuanzhike.top/Article/details/gtjhawjczy.html

Ruby: (0...10).step(2).to_a
来源：http://dali.haohaochexian.top/Article/details/gtkozvucre.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbaijxgel.html

[B12] 跳出多层循环
来源：http://dali.nwbrower.top/Article/details/gttwflhjgm.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jinqigufen.top/Article/details/gtaotmnbnb.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.nanxuanxn.top/Article/details/gtjwoigcir.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yvedp.cn/Article/details/gtaiddlfdp.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gotoacloud.top/Article/details/gttydbnxac.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hfpthk.cn/Article/details/gtkpevilve.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.pengpengdd.cyou/Article/details/gtrvalhkfs.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.316326.xyz/Article/details/gtfwhduafg.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hammf.cn/Article/details/gtostmgbbf.html

[B13] 判断是否为数字
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttxqciftd.html

Py:   isinstance(x, (int, float))
来源：http://dali.iojbl.cn/Article/details/gtdiyziher.html

PHP:  is_numeric($x)
来源：http://dali.shuidangran.top/Article/details/gtbgiuibnz.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.vqdsnc.cn/Article/details/gtyxoddyfd.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtlsvlswrj.html

Java: x instanceof Number
来源：http://dali.cashguo.top/Article/details/gtpigdltsx.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yangfankeji.com/Article/details/gtietzmdxa.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlkqrxqpf.html

C#:   x is int or double or decimal
来源：http://dali.fzhhl.top/Article/details/gtzknrsdgh.html

[B14] 判断值是否在集合内
来源：http://dali.aibaodan.cn/Article/details/gtuwtsumke.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.wangdashe.top/Article/details/gtdlbjnqbr.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.gaohongyu789.top/Article/details/gtxggcmdom.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.dianchejie.cn/Article/details/gtebdgxmvy.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.svipenyu.cn/Article/details/gttbqwdksq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhengqikj.top/Article/details/gtouoxkdmp.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yj202588.top/Article/details/gtvpfipkex.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.kuanghao11.cn/Article/details/gtguijxbsj.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhixingplan.top/Article/details/gtntmbtchb.html

[B15] 布尔运算与取反
来源：http://dali.shuidangran.top/Article/details/gttbssyvax.html

Py:   a and b or not c
来源：http://dali.yj20258888.top/Article/details/gtblfarnoy.html

PHP:  $a && $b || !$c
来源：http://dali.jinqigufen.top/Article/details/gtvelbxiki.html

JS:   a && b || !c
来源：http://dali.gzhubu.top/Article/details/gtcutltdrc.html

TS:   a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gtoazlymtt.html

Java: a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtjmsecwfj.html

Go:   a && b || !c
来源：http://dali.yueranfly.top/Article/details/gtsvoclvwf.html

Ruby: a && b || !c
来源：http://dali.xuanzx.com/Article/details/gtqrbyrwax.html

C#:   a && b || !c
来源：http://dali.birdmap.top/Article/details/gtatxvetky.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.feifeiyinyue.top/Article/details/gtxbutmvil.html

Py:   if not data: return
来源：http://dali.ppjwa.cn/Article/details/gtgyhdutxd.html

PHP:  if (!$data) { return; }
来源：http://dali.zhixingplan.top/Article/details/gtnxsacubv.html

JS:   if (!data) return;
来源：http://dali.ivvv.top/Article/details/gtrfnapdzj.html

TS:   if (!data) return;
来源：http://dali.feifeiyinyue.top/Article/details/gttueohjzl.html

Java: if (data == null) return;
来源：http://dali.xuanzx.com/Article/details/gtbztvjvdo.html

Go:   if data == nil { return }
来源：http://dali.fengsongda.top/Article/details/gtjgtvuldk.html

Ruby: return if data.nil?
来源：http://dali.smart0.xyz/Article/details/gtuesytzow.html

C#:   if (data == null) return;
来源：http://dali.yuanzhike.top/Article/details/gtkkiwksoi.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtmgcujmeh.html

C. 函数与作用域
来源：http://dali.dianchejie.cn/Article/details/gtszijdeft.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtixxkzoxx.html

[C01] 定义函数
来源：http://dali.chenzaomai.com/Article/details/gtbfiipvnf.html

Py:   def add(a, b): return a + b
来源：http://dali.nanxuanxn.top/Article/details/gtghiijegv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gtrzhxjnox.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gtgshyxpmz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gtqmmbjova.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtxmyqtdff.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.shangyingyoupin.top/Article/details/gtibnqcyzl.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gttoskoahr.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gtpgxgjrei.html

[C02] 默认参数
来源：http://dali.tanke756.top/Article/details/gtcpvguykd.html

Py:   def greet(name="World"): return name
来源：http://dali.shuidangran.top/Article/details/gtrqurwveu.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.chenzaomai.com/Article/details/gthxcherve.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yj20258.top/Article/details/gtzsavmuka.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtfnzvvbqz.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hysaishi.cn/Article/details/gtkpuuafxv.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhixingplan.top/Article/details/gtwzgwdbjl.html

Ruby: def greet(name = "World") = name
来源：http://dali.9152youxi.cn/Article/details/gtwkheujjd.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.daxiang520.top/Article/details/gtymsenhhb.html

[C03] 可变参数
来源：http://dali.c1oappe.top/Article/details/gtfwqdzdym.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gtdtwqmvqg.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.chenlongwang.top/Article/details/gthpkfxfdi.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yuxming.cn/Article/details/gthklwtofb.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hywenlv.cn/Article/details/gtenddubkk.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtgynrmynu.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.andypj.xyz/Article/details/gtinbjqmwv.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.fzhhl.top/Article/details/gtnbidwtlf.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ppjwa.cn/Article/details/gtuknfwzzy.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hnxiangtu.top/Article/details/gtcibvjdgb.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.wangshuangyany.cn/Article/details/gtfkmbglqs.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xziqi.cn/Article/details/gtpcviincr.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.kuanghao11.cn/Article/details/gtuymptthz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yj20258.top/Article/details/gtipnenzqd.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hnxiangtu.top/Article/details/gtwipowqrf.html

Go:   // 无：用配置结构体参数
来源：http://dali.nanxuanxn.top/Article/details/gtzfexalsp.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yj20258.top/Article/details/gtiscpxbnw.html

C#:   f(a: 1, b: 2)
来源：http://dali.0kj1m.cn/Article/details/gtklshiuuc.html

[C05] 返回多个值
来源：http://dali.gaohongyu789.top/Article/details/gtupfmkrgx.html

Py:   return a, b
来源：http://dali.chenlongwang.top/Article/details/gtnzwzyuex.html

PHP:  return [$a, $b];
来源：http://dali.iojbl.cn/Article/details/gtuegnrhmy.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.quarkkingdee.top/Article/details/gtkqmauqrj.html

TS:   return { a, b };
来源：http://dali.yj20258.top/Article/details/gtcsvrzjud.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhongyouzk.top/Article/details/gtbqwhisrj.html

Go:   return a, b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjzxlorrd.html

Ruby: return a, b
来源：http://dali.aibaodan.cn/Article/details/gtnjsgcjri.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.mhx1999.top/Article/details/gtbtadznea.html

[C06] 匿名函数 / lambda
来源：http://dali.cqqwz.cn/Article/details/gtbesvygjx.html

Py:   square = lambda x: x * x
来源：http://dali.jianghu66.top/Article/details/gteuxfunbv.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.daxiang520.top/Article/details/gtfijojhgh.html

JS:   const square = x => x * x;
来源：http://dali.sysykeji.top/Article/details/gthxodyujk.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gtbwxrmhpv.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhengqikj.top/Article/details/gtnfkpylzk.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.tian-w.cn/Article/details/gtuawyvkqy.html

Ruby: square = ->(x) { x * x }
来源：http://dali.guannengcc.top/Article/details/gtpezjyjtn.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hywenlv.cn/Article/details/gtgapkjohs.html

[C07] 把函数作为参数传入
来源：http://dali.jinghuilouyu.cn/Article/details/gtkywcttle.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cucudq.cn/Article/details/gtjebqfuuf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.0kj1m.cn/Article/details/gtfaidhveb.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hfpthk.cn/Article/details/gtuzhtbfmf.html

TS:   arr.map(String)
来源：http://dali.ivvv.top/Article/details/gteckpcwnx.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gotoacloud.top/Article/details/gtabqfibnn.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jqgufenzy.top/Article/details/gtxipendmc.html

Ruby: arr.map(&:upcase)
来源：http://dali.shangyingyoupin.top/Article/details/gtyhsnhofj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.mhx1999.top/Article/details/gtjgxcazbp.html

[C08] 闭包
来源：http://dali.birdmap.top/Article/details/gthzzizrcr.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hywenlv.cn/Article/details/gtkpdildgy.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yj202588.top/Article/details/gtvaaaxqsj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.aibaodan.cn/Article/details/gtgoqldspn.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xylfe.cn/Article/details/gtekcvycgf.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yongpay.top/Article/details/gtvtyagbkk.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgsvkzfmh.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cucudq.cn/Article/details/gtiuhwdhbv.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jiagoushi.top/Article/details/gtefomkaff.html

[C09] 递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtfrsamzbk.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.fengsongda.top/Article/details/gtqgientcb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.wangdashe.top/Article/details/gtoxfsgzvf.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.iojbl.cn/Article/details/gtaunwruuf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenlongwang.top/Article/details/gturkilwum.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shuidangran.top/Article/details/gtocluxcei.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yonumen.top/Article/details/gtvmwmcrnw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shzxlz.cn/Article/details/gtcxppewtv.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhiwuduotai.top/Article/details/gtagxfixso.html

[C10] 变量作用域
来源：http://dali.jqgufenzy.top/Article/details/gtytvfdtkp.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xylfe.cn/Article/details/gtynowsoea.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.nwbrower.top/Article/details/gtoohdsphu.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.9152youxi.cn/Article/details/gtcleedxdj.html

TS:   同 JS
来源：http://dali.jinqigfzy.top/Article/details/gtaknzfxzu.html

Java: 方法内为块级作用域
来源：http://dali.sufxvd.cn/Article/details/gtyzkjntpq.html

Go:   花括号块级作用域
来源：http://dali.dashuyun.cn/Article/details/gtwrctkjpv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.guannengcc.top/Article/details/gtzxpgbvjc.html

C#:   块级作用域
来源：http://dali.guowangkeji.top/Article/details/gtalqkwrwl.html

[C11] 模块导入与导出
来源：http://dali.hnxiangtu.top/Article/details/gtwhncobzk.html

Py:   from module import func
来源：http://dali.hnxiangtu.top/Article/details/gtcldnzayl.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.gzhubu.top/Article/details/gtiogdniql.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.snrcjt.cn/Article/details/gthmiicxch.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xuetiantiany.cn/Article/details/gtgxohyyht.html

Java: import java.util.List;
来源：http://dali.nanxuanxn.top/Article/details/gtmpqrvvmq.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.feifeiyinyue.top/Article/details/gtpihdmcrv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.havefunace.top/Article/details/gtmjhffjwp.html

C#:   using System.Text;
来源：http://dali.tanke756.top/Article/details/gtohcgmaoa.html

[C12] 立即执行函数 IIFE
来源：http://dali.cheryme.top/Article/details/gtdytfkarv.html

Py:   (lambda: print("run"))()
来源：http://dali.vqdsnc.cn/Article/details/gtqnxausmv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.sysykeji.top/Article/details/gtwhjseunp.html

JS:   (() => { console.log("run"); })();
来源：http://dali.mhx1999.top/Article/details/gtpnfbbont.html

TS:   (() => { console.log("run"); })();
来源：http://dali.sufxvd.cn/Article/details/gtjanzhlmn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.pengpengdd.cyou/Article/details/gtndgtbcxb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.kuanghao11.cn/Article/details/gtpdmehdjn.html

Ruby: -> { puts "run" }.call
来源：http://dali.0kj1m.cn/Article/details/gtrawchdjo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ehwqpu.com/Article/details/gthjcsjnqn.html

[C13] 类型声明 / 类型注解
来源：http://dali.mhx1999.top/Article/details/gtrxckmbod.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zycfv.cn/Article/details/gtrzghzdja.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhengqikj.top/Article/details/gtkclgunjk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cashguo.top/Article/details/gtkqgfxanr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gtbbjnlhxt.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.birdmap.top/Article/details/gtgmbsjtga.html

Go:   func add(a, b int) int
来源：http://dali.ppjwa.cn/Article/details/gtumynhesk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.iojbl.cn/Article/details/gtznpqovah.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.pycfn.com/Article/details/gtdeqtppcx.html

[C14] 泛型函数
来源：http://dali.cashguo.top/Article/details/gticjkyaab.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ydzc1.top/Article/details/gtzgfbclzp.html

PHP:  // 无泛型
来源：http://dali.gogol.net.cn/Article/details/gtsfszxkjs.html

JS:   // 无泛型
来源：http://dali.yj20258888.top/Article/details/gthjhnkefk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jlsjyb.cn/Article/details/gtjjwmjeny.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ehwqpu.com/Article/details/gtgkuszjsk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.dianchejie.cn/Article/details/gtnzekwhwp.html

Ruby: # 无泛型
来源：http://dali.gzhubu.top/Article/details/gtxzmvlhhi.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yvedp.cn/Article/details/gtprxyxjai.html

[C15] 解构 / 展开参数
来源：http://dali.haohaochexian.top/Article/details/gtbntgkbft.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.chenlongwang.top/Article/details/gtuyldmcya.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gaohongyu789.top/Article/details/gtmatlzqel.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtedwcnqqx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.redwolf501.top/Article/details/gtsadpxfip.html

Java: // 无解构
来源：http://dali.yueranfly.top/Article/details/gtqqabmqrf.html

Go:   // 无解构
来源：http://dali.vqdsnc.cn/Article/details/gtmrpwndlg.html

Ruby: a, b = pair
来源：http://dali.tianlin.xyz/Article/details/gthagljbhp.html

C#:   var (a, b) = pair;
来源：http://dali.yonumen.top/Article/details/gtlktvzayv.html

[C16] 函数 / 方法重载
来源：http://dali.vqdsnc.cn/Article/details/gtfmamucrv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.bjfxy.top/Article/details/gtwncsuvdl.html

PHP:  // 无重载
来源：http://dali.gogol.net.cn/Article/details/gtsiedcytj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yangfankeji.com/Article/details/gttifyguba.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sweek.top/Article/details/gthgkhfjir.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jianghu66.top/Article/details/gtqdymowic.html

Go:   // 无重载：用不同函数名
来源：http://dali.birdmap.top/Article/details/gteccrgbyw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ivvv.top/Article/details/gtohgjaicf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zdqjudy.top/Article/details/gtclhztefa.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gttptjhbqv.html

D. 数组 / 列表 / 集合
来源：http://dali.cdnleiting.top/Article/details/gtfkzurgmt.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtsltdllne.html

[D01] 创建数组 / 列表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtleviiuvg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.redwolf501.top/Article/details/gtffpivhsx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xziqi.cn/Article/details/gtmvxasnsq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.mhx1999.top/Article/details/gtkqipxhzj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jinqigufen.top/Article/details/gtcnkkexcs.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.svipenyu.cn/Article/details/gtjydsjcli.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shuidangran.top/Article/details/gthdlnkqnd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.smart0.xyz/Article/details/gtctukkoxo.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hnxiangtu.top/Article/details/gtufmozesg.html

[D02] 追加元素到末尾
来源：http://dali.mhx1999.top/Article/details/gtddxiyzei.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhengqikj.top/Article/details/gtyxpjgyyw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jlsjyb.cn/Article/details/gtdhcejapg.html

JS:   arr.push(4);
来源：http://dali.andypj.xyz/Article/details/gtkzubwbrw.html

TS:   arr.push(4);
来源：http://dali.andypj.xyz/Article/details/gtupszltrq.html

Java: list.add(4);
来源：http://dali.316326.xyz/Article/details/gtunphagqz.html

Go:   arr = append(arr, 4)
来源：http://dali.quarkkingdee.top/Article/details/gtgkjvlwpz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hongshengwenyu.top/Article/details/gtzhxadumw.html

C#:   list.Add(4);
来源：http://dali.yuanzhike.top/Article/details/gtvnjsdifo.html

[D03] 在指定位置插入元素
来源：http://dali.feifeiyinyue.top/Article/details/gtlzcylape.html

Py:   arr.insert(0, 0)
来源：http://dali.daria6918.cn/Article/details/gtrjvzptid.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.0kj1m.cn/Article/details/gthufumgjf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shanyushiyangtech.top/Article/details/gtezqqcfop.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.gaohongyu789.top/Article/details/gtupurifxu.html

Java: list.add(0, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdzwraxmj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.daxiang520.top/Article/details/gthntiqzug.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cqqwz.cn/Article/details/gtivaisajd.html

C#:   list.Insert(0, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwahoanou.html

[D04] 删除元素
来源：http://dali.jianghu66.top/Article/details/gtnarawcjr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ehwqpu.com/Article/details/gtvudttaku.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sxryk.cn/Article/details/gtfwvyfqlb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.9152youxi.cn/Article/details/gtxahpbixk.html

TS:   arr.splice(0, 1);
来源：http://dali.nanxinkj.top/Article/details/gtztrxktoy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmhxfgtzh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hysaishi.cn/Article/details/gtcvgxdkrj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gtefxnpjpr.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.nwbrower.top/Article/details/gtoobzyglq.html

[D05] 访问与修改元素
来源：http://dali.feifeiyinyue.top/Article/details/gtzuhqmznz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jlsjyb.cn/Article/details/gtzplhkoos.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.316326.xyz/Article/details/gtcdniaftj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hfpthk.cn/Article/details/gtqydnncuz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.tianlin.xyz/Article/details/gturwmrrja.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.fzhhl.top/Article/details/gtmtmnzlqb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.aibaodan.cn/Article/details/gtomlamopm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yuxming.cn/Article/details/gtbwchnzpj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.kuanghao11.cn/Article/details/gtwtgevshs.html

[D06] 数组长度
来源：http://dali.svipenyu.cn/Article/details/gtxbgylidw.html

Py:   len(arr)
来源：http://dali.andypj.xyz/Article/details/gtgqkoondw.html

PHP:  count($arr);
来源：http://dali.ivvv.top/Article/details/gtlobfazol.html

JS:   arr.length
来源：http://dali.yuanzhike.top/Article/details/gtscatbdyu.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gtxzeclehy.html

Java: list.size();
来源：http://dali.pengpengdd.cyou/Article/details/gtktlxwqxt.html

Go:   len(arr)
来源：http://dali.tian-w.cn/Article/details/gtaypqyejl.html

Ruby: arr.length; arr.size
来源：http://dali.ivvv.top/Article/details/gtpffybljj.html

C#:   list.Count;
来源：http://dali.ehwqpu.com/Article/details/gttiuxezpo.html

[D07] 切片 / 取子数组
来源：http://dali.jiagoushi.top/Article/details/gtkbnfsuie.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.daxiang520.top/Article/details/gtcezmjmlg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhixingplan.top/Article/details/gtvepjpbko.html

JS:   arr.slice(1, 4);
来源：http://dali.sysykeji.top/Article/details/gtmlccyaeg.html

TS:   arr.slice(1, 4);
来源：http://dali.zhiwuduotai.top/Article/details/gtzhxckdiu.html

Java: list.subList(1, 4);
来源：http://dali.andypj.xyz/Article/details/gthzkdvjit.html

Go:   arr[1:4]
来源：http://dali.yj20258.top/Article/details/gtgtdmvgct.html

Ruby: arr[1, 3]
来源：http://dali.sweek.top/Article/details/gtlgqgwbyf.html

C#:   list.GetRange(1, 3);
来源：http://dali.cdnleiting.top/Article/details/gtnkqijhmx.html

[D08] 合并两个数组
来源：http://dali.yongpay.top/Article/details/gtlwslchxn.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhoulong.xyz/Article/details/gtlxvhdapn.html

PHP:  array_merge($a, $b);
来源：http://dali.sysykeji.top/Article/details/gteoqmqmyi.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jlsjyb.cn/Article/details/gtpskanhoo.html

TS:   [...a, ...b];
来源：http://dali.guowangkeji.top/Article/details/gtfqzexnoz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sweek.top/Article/details/gtorobjyrg.html

Go:   append(a, b...)
来源：http://dali.daria6918.cn/Article/details/gtguxcgnty.html

Ruby: a + b;  a.concat(b)
来源：http://dali.haohaochexian.top/Article/details/gtbaqzdowq.html

C#:   a.Concat(b).ToList()
来源：http://dali.ehwqpu.com/Article/details/gtxteoissw.html

[D09] 排序（升序）
来源：http://dali.jinqigfzy.top/Article/details/gthfsffrew.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hfpthk.cn/Article/details/gtpwszurwm.html

PHP:  sort($arr);
来源：http://dali.ppjwa.cn/Article/details/gtvftxfhmn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jyoumei.cn/Article/details/gtchnetocu.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnhxkaxqm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhoulong.xyz/Article/details/gtwurnzisy.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.dashuyun.cn/Article/details/gtztyxbrem.html

Ruby: arr.sort
来源：http://dali.aizwys.cn/Article/details/gtfncqbbuq.html

C#:   list.Sort();
来源：http://dali.aibaodan.cn/Article/details/gtxpxnfyli.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.pengpengdd.cyou/Article/details/gtcqsonavv.html


<!-- 参考信息 -->