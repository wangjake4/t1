代发 wailian999

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.aizwys.cn/Article/details/gt2xlrwfdos.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zycfv.cn/Article/details/gt2rburndiq.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yuanzhike.top/Article/details/gt2lgkqzhzm.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yuanzhike.top/Article/details/gt2dhfsfuzo.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.daxiang520.top/Article/details/gt2ewjrltgb.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2plykijvg.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhoulong.xyz/Article/details/gt2kueenkng.html

Py:   list(range(0, 10, 2))
来源：http://dali.jlsjyb.cn/Article/details/gt2pofacclz.html

PHP:  range(0, 10, 2);
来源：http://dali.gzhubu.top/Article/details/gt2fgpqwamp.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cdnleiting.top/Article/details/gt2pxyghaex.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nanxinkj.top/Article/details/gt2uwiywivc.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.316326.xyz/Article/details/gt2wfclnkun.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.ppjwa.cn/Article/details/gt2pbzyeuxl.html

Ruby: (0...10).step(2).to_a
来源：http://dali.cheryme.top/Article/details/gt2jbqtuhzd.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.kuanghao11.cn/Article/details/gt2qmwmsipl.html

[B12] 跳出多层循环
来源：http://dali.zhongyouzk.top/Article/details/gt2ihrbkmui.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xuanzx.com/Article/details/gt2kkgvltth.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cucudq.cn/Article/details/gt2nkskcsdj.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.guannengcc.top/Article/details/gt2ousydpdt.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.snrcjt.cn/Article/details/gt2lubhjwgy.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ydzc1.top/Article/details/gt2ipdvwvge.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.iojbl.cn/Article/details/gt2dnvibbor.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yuxming.cn/Article/details/gt2orlvqzai.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.mhx1999.top/Article/details/gt2yhmylrka.html

[B13] 判断是否为数字
来源：http://dali.chenjidiqi.icu/Article/details/gt2fgmqrpqg.html

Py:   isinstance(x, (int, float))
来源：http://dali.sweek.top/Article/details/gt2mpmxouex.html

PHP:  is_numeric($x)
来源：http://dali.aibaodan.cn/Article/details/gt2svuyqujq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jyoumei.cn/Article/details/gt2comdimpn.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxinkj.top/Article/details/gt2bpfsofkn.html

Java: x instanceof Number
来源：http://dali.0kj1m.cn/Article/details/gt2eaifgygd.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xylfe.cn/Article/details/gt2dhltzqoc.html

Ruby: x.is_a?(Numeric)
来源：http://dali.sysykeji.top/Article/details/gt2jrveiaae.html

C#:   x is int or double or decimal
来源：http://dali.mhx1999.top/Article/details/gt2kyibkiie.html

[B14] 判断值是否在集合内
来源：http://dali.yj20258888.top/Article/details/gt2puoanmry.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.pycfn.com/Article/details/gt2lusbfukk.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.tianlin.xyz/Article/details/gt2xbzlguls.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.snrcjt.cn/Article/details/gt2zlnwsqyy.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.gzhubu.top/Article/details/gt2jcsyhguj.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.pycfn.com/Article/details/gt2thbvjcdi.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.pycfn.com/Article/details/gt2qeifutln.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.havefunace.top/Article/details/gt2kywgmvbs.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bjcdjqpl.html

[B15] 布尔运算与取反
来源：http://dali.zhongyouzk.top/Article/details/gt2ikbjdnfo.html

Py:   a and b or not c
来源：http://dali.guannengcc.top/Article/details/gt2zsovykco.html

PHP:  $a && $b || !$c
来源：http://dali.xziqi.cn/Article/details/gt2cmulymqs.html

JS:   a && b || !c
来源：http://dali.zycfv.cn/Article/details/gt2jnefwhwd.html

TS:   a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gt2gozdclpu.html

Java: a && b || !c
来源：http://dali.daxiang520.top/Article/details/gt2turskadx.html

Go:   a && b || !c
来源：http://dali.tanke756.top/Article/details/gt2zvidyeci.html

Ruby: a && b || !c
来源：http://dali.hammf.cn/Article/details/gt2ddfmeuvq.html

C#:   a && b || !c
来源：http://dali.redwolf501.top/Article/details/gt2dfvqxnuc.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zdqjudy.top/Article/details/gt2puauaofc.html

Py:   if not data: return
来源：http://dali.0kj1m.cn/Article/details/gt2whymtfcd.html

PHP:  if (!$data) { return; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rrmfiunf.html

JS:   if (!data) return;
来源：http://dali.nwbrower.top/Article/details/gt2mtvgiatl.html

TS:   if (!data) return;
来源：http://dali.jqgufenzy.top/Article/details/gt2unsmlabj.html

Java: if (data == null) return;
来源：http://dali.zycfv.cn/Article/details/gt2ggdkxvul.html

Go:   if data == nil { return }
来源：http://dali.fzhhl.top/Article/details/gt2lfgbvogp.html

Ruby: return if data.nil?
来源：http://dali.jinqigfzy.top/Article/details/gt2nfkgyqrz.html

C#:   if (data == null) return;
来源：http://dali.kuanghao11.cn/Article/details/gt2tbhjexuk.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2htoraaln.html

C. 函数与作用域
来源：http://dali.hammf.cn/Article/details/gt2bthztfxd.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2ttrjherc.html

[C01] 定义函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2pkvhebna.html

Py:   def add(a, b): return a + b
来源：http://dali.guannengcc.top/Article/details/gt2flglvede.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnxiangtu.top/Article/details/gt2aywlnmdf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gt2ipiiliek.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gt2yiacvtim.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.sweek.top/Article/details/gt2ppvleayj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xuanzx.com/Article/details/gt2ccbyykte.html

Ruby: def add(a, b); a + b; end
来源：http://dali.316326.xyz/Article/details/gt2nfxvqeat.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gt2odhhknlu.html

[C02] 默认参数
来源：http://dali.jianghu66.top/Article/details/gt2sxuvacpa.html

Py:   def greet(name="World"): return name
来源：http://dali.xuanzx.com/Article/details/gt2brhvhuui.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xziqi.cn/Article/details/gt2zfoyhivn.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.wangdashe.top/Article/details/gt2vacnpqey.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.wangdashe.top/Article/details/gt2sbvghptm.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jcxplhvz.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2whdvcyww.html

Ruby: def greet(name = "World") = name
来源：http://dali.redwolf501.top/Article/details/gt2yleomuyi.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.nanxuanxn.top/Article/details/gt2ayuapjfx.html

[C03] 可变参数
来源：http://dali.hfpthk.cn/Article/details/gt2kdpzcbpa.html

Py:   def total(*args): return sum(args)
来源：http://dali.xylfe.cn/Article/details/gt2bjyusckr.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.fzhhl.top/Article/details/gt2iavdjtya.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.316326.xyz/Article/details/gt2reegxdif.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhongyouzk.top/Article/details/gt2krzzqimg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lxuvnlwu.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.aizwys.cn/Article/details/gt2orkvlbdk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.chenzaomai.com/Article/details/gt2uyzdcvrm.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yueranfly.top/Article/details/gt2wdnquqtj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.sxryk.cn/Article/details/gt2srqlnpuz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.haohaochexian.top/Article/details/gt2wqwxjjlo.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hthtvyte.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2upnnlzpb.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.gaohongyu789.top/Article/details/gt2tewzraeq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yonumen.top/Article/details/gt2jolcyltq.html

Go:   // 无：用配置结构体参数
来源：http://dali.gaohongyu789.top/Article/details/gt2xxliscpl.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yj20258888.top/Article/details/gt2uqwnojpe.html

C#:   f(a: 1, b: 2)
来源：http://dali.ivvv.top/Article/details/gt2rcjdbomj.html

[C05] 返回多个值
来源：http://dali.jqgfzy.top/Article/details/gt2ammjgqzv.html

Py:   return a, b
来源：http://dali.kuanghao11.cn/Article/details/gt2tzjaqoxw.html

PHP:  return [$a, $b];
来源：http://dali.kuanghao11.cn/Article/details/gt2cnmrtgwn.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.andypj.xyz/Article/details/gt2luaaajma.html

TS:   return { a, b };
来源：http://dali.guowangkeji.top/Article/details/gt2xrswnhyu.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.smart0.xyz/Article/details/gt2ldvwcvdx.html

Go:   return a, b
来源：http://dali.dianchejie.cn/Article/details/gt2udxdtmkp.html

Ruby: return a, b
来源：http://dali.yangfankeji.com/Article/details/gt2ozwkragx.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shuidangran.top/Article/details/gt2njpxruva.html

[C06] 匿名函数 / lambda
来源：http://dali.yvedp.cn/Article/details/gt2itmzbuwj.html

Py:   square = lambda x: x * x
来源：http://dali.ehwqpu.com/Article/details/gt2yzduevwt.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yuxming.cn/Article/details/gt2zpygeffu.html

JS:   const square = x => x * x;
来源：http://dali.zhengqikj.top/Article/details/gt2sikmfxll.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hfpthk.cn/Article/details/gt2sriqbugd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.cashguo.top/Article/details/gt2yrdcxrip.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.redwolf501.top/Article/details/gt2luyqapmw.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hammf.cn/Article/details/gt2zxbfjalw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mdwwqick.html

[C07] 把函数作为参数传入
来源：http://dali.cheryme.top/Article/details/gt2phlytvfm.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.mhx1999.top/Article/details/gt2zwmltkgt.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hysaishi.cn/Article/details/gt2rwvcytuu.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shangyingyoupin.top/Article/details/gt2csyfpdqs.html

TS:   arr.map(String)
来源：http://dali.andypj.xyz/Article/details/gt2yumpbeny.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hfpthk.cn/Article/details/gt2yflnpuwf.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.316326.xyz/Article/details/gt2djffgyok.html

Ruby: arr.map(&:upcase)
来源：http://dali.0kj1m.cn/Article/details/gt2xpazedoa.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.vqdsnc.cn/Article/details/gt2rswkxkuw.html

[C08] 闭包
来源：http://dali.yj202588.top/Article/details/gt2ssitpcmn.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ybcxt.top/Article/details/gt2pckkzvyu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jqgufenzy.top/Article/details/gt2ckxchfqg.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cucudq.cn/Article/details/gt2mlzvdmva.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zkysrmuy.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xinyue.icu/Article/details/gt2iaxsjgry.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhiwuduotai.top/Article/details/gt2znpwbheb.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.birdmap.top/Article/details/gt2uvmtnueq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.chenlongwang.top/Article/details/gt2ljvkocyq.html

[C09] 递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ybeghfma.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.shuidangran.top/Article/details/gt2ileevhrm.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jqgufenzy.top/Article/details/gt2axvkaddc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ybcxt.top/Article/details/gt2rolebteg.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.daxiang520.top/Article/details/gt2kjatoyhx.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shzxlz.cn/Article/details/gt2ikxefztz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.dashuyun.cn/Article/details/gt2ljsphawr.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shzxlz.cn/Article/details/gt2iytjvioy.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jinqigfzy.top/Article/details/gt2odfrocnm.html

[C10] 变量作用域
来源：http://dali.fzhhl.top/Article/details/gt2qwjrydok.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uchdddya.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jqgufenzy.top/Article/details/gt2weogpfcx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hongshengwenyu.top/Article/details/gt2olqwmzdj.html

TS:   同 JS
来源：http://dali.xinyue.icu/Article/details/gt2jlfowcyt.html

Java: 方法内为块级作用域
来源：http://dali.hammf.cn/Article/details/gt2fycllvuy.html

Go:   花括号块级作用域
来源：http://dali.yj20258.top/Article/details/gt2ahencuve.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.chenjidiqi.icu/Article/details/gt2mymgpaex.html

C#:   块级作用域
来源：http://dali.havefunace.top/Article/details/gt2erwzgxcw.html

[C11] 模块导入与导出
来源：http://dali.cucudq.cn/Article/details/gt2izwrqklf.html

Py:   from module import func
来源：http://dali.shzxlz.cn/Article/details/gt2sjrcbmit.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aygbbpyo.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.daxiang520.top/Article/details/gt2jxxojdvm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yonumen.top/Article/details/gt2hlpnhqpq.html

Java: import java.util.List;
来源：http://dali.aizwys.cn/Article/details/gt2nycpxgwp.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ehwqpu.com/Article/details/gt2lqkqrjtk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.meibo888.top/Article/details/gt2elbgscsz.html

C#:   using System.Text;
来源：http://dali.vqdsnc.cn/Article/details/gt2ciqckjrc.html

[C12] 立即执行函数 IIFE
来源：http://dali.cqqwz.cn/Article/details/gt2zdtpyogd.html

Py:   (lambda: print("run"))()
来源：http://dali.ybcxt.top/Article/details/gt2tavurdxe.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhiwuduotai.top/Article/details/gt2ghefniql.html

JS:   (() => { console.log("run"); })();
来源：http://dali.quarkkingdee.top/Article/details/gt2inctiqbm.html

TS:   (() => { console.log("run"); })();
来源：http://dali.c1oappe.top/Article/details/gt2tnypmmha.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.9152youxi.cn/Article/details/gt2yfdibpcb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cdnleiting.top/Article/details/gt2ylksioqr.html

Ruby: -> { puts "run" }.call
来源：http://dali.xinyue.icu/Article/details/gt2jhzogpay.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2xalainlq.html

[C13] 类型声明 / 类型注解
来源：http://dali.pycfn.com/Article/details/gt2cjozbqrp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhiwuduotai.top/Article/details/gt2pddfdaft.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tianlin.xyz/Article/details/gt2cmrcdinm.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2svftmacp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gt2zxkskocy.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gt2tjgmmefy.html

Go:   func add(a, b int) int
来源：http://dali.hnxiangtu.top/Article/details/gt2bojuklnm.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yuanzhike.top/Article/details/gt2lcmftsxg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.daxiang520.top/Article/details/gt2pigsjevu.html

[C14] 泛型函数
来源：http://dali.fengsongda.top/Article/details/gt2xlueqspl.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.daxiang520.top/Article/details/gt2asyfcppb.html

PHP:  // 无泛型
来源：http://dali.yj20258.top/Article/details/gt2whylbkcd.html

JS:   // 无泛型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mjfincmu.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.tianlin.xyz/Article/details/gt2kdehnmzq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jqgfzy.top/Article/details/gt2rhlhmfac.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kpujvcha.html

Ruby: # 无泛型
来源：http://dali.guowangkeji.top/Article/details/gt2ucdolryi.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yj20258.top/Article/details/gt2nrlmxvmo.html

[C15] 解构 / 展开参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bquedubd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.daxiang520.top/Article/details/gt2knkqdmtb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zycfv.cn/Article/details/gt2faotckin.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.bjfxy.top/Article/details/gt2vzzvtook.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xuanzx.com/Article/details/gt2gfzzbkcb.html

Java: // 无解构
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hmpskspp.html

Go:   // 无解构
来源：http://dali.shzxlz.cn/Article/details/gt2wclqfgaa.html

Ruby: a, b = pair
来源：http://dali.bjfxy.top/Article/details/gt2seqgarvk.html

C#:   var (a, b) = pair;
来源：http://dali.svipenyu.cn/Article/details/gt2polnihqm.html

[C16] 函数 / 方法重载
来源：http://dali.jlsjyb.cn/Article/details/gt2ejzambjf.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.smart0.xyz/Article/details/gt2xkrlrxca.html

PHP:  // 无重载
来源：http://dali.ehwqpu.com/Article/details/gt2oqocttyg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.guowangkeji.top/Article/details/gt2ggihuflt.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.pycfn.com/Article/details/gt2tppequen.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2tqwghkbu.html

Go:   // 无重载：用不同函数名
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yxgncjsx.html

Ruby: # 无重载：靠动态参数
来源：http://dali.redwolf501.top/Article/details/gt2wobvyoen.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gotoacloud.top/Article/details/gt2peaagpsa.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2ooyvysqu.html

D. 数组 / 列表 / 集合
来源：http://dali.hnxiangtu.top/Article/details/gt2hoojbtjb.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2qyjypgrv.html

[D01] 创建数组 / 列表
来源：http://dali.gogol.net.cn/Article/details/gt2dmsmituf.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jiagoushi.top/Article/details/gt2qzjordnh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jinqigufen.top/Article/details/gt2aqlqomoi.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ebkkeqvb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.chenzaomai.com/Article/details/gt2ssewrtfl.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.0kj1m.cn/Article/details/gt2pyukyocb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.birdmap.top/Article/details/gt2kipanoqs.html

Ruby: arr = [1, 2, 3]
来源：http://dali.redwolf501.top/Article/details/gt2wmnbnrzt.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ybcxt.top/Article/details/gt2yqmbywfn.html

[D02] 追加元素到末尾
来源：http://dali.c1oappe.top/Article/details/gt2yytyxbzt.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.daria6918.cn/Article/details/gt2jtqbpogv.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jlsjyb.cn/Article/details/gt2pjnnssei.html

JS:   arr.push(4);
来源：http://dali.redwolf501.top/Article/details/gt2fbdbfquk.html

TS:   arr.push(4);
来源：http://dali.ydzc1.top/Article/details/gt2khhedtmz.html

Java: list.add(4);
来源：http://dali.aibaodan.cn/Article/details/gt2jaexvjan.html

Go:   arr = append(arr, 4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rbxfvfca.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sufxvd.cn/Article/details/gt2huankwvq.html

C#:   list.Add(4);
来源：http://dali.ppjwa.cn/Article/details/gt2hhlvhmbq.html

[D03] 在指定位置插入元素
来源：http://dali.yongpay.top/Article/details/gt2khlgvtuq.html

Py:   arr.insert(0, 0)
来源：http://dali.fzhhl.top/Article/details/gt2uauopxsl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2inreolqq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.aizwys.cn/Article/details/gt2nzpsqqtm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hnqzz.top/Article/details/gt2kmychfhz.html

Java: list.add(0, 0);
来源：http://dali.yueranfly.top/Article/details/gt2fwmftpjh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.chenjidiqi.icu/Article/details/gt2pghdvruc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yongpay.top/Article/details/gt2icnhmvuw.html

C#:   list.Insert(0, 0);
来源：http://dali.xinyue.icu/Article/details/gt2tdpqqhzw.html

[D04] 删除元素
来源：http://dali.ydzc1.top/Article/details/gt2csplqgvc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.daxiang520.top/Article/details/gt2ojadjvbp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ybcxt.top/Article/details/gt2wtscmklg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.aibaodan.cn/Article/details/gt2hbvyqfsa.html

TS:   arr.splice(0, 1);
来源：http://dali.pengpengdd.cyou/Article/details/gt2axvunbfg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jianghu66.top/Article/details/gt2hhrbswdj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.daxiang520.top/Article/details/gt2aipdbhro.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.meibo888.top/Article/details/gt2izomtcac.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.9152youxi.cn/Article/details/gt2ksblppqv.html

[D05] 访问与修改元素
来源：http://dali.daria6918.cn/Article/details/gt2efdskcjc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.fengsongda.top/Article/details/gt2qfujmvut.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hywenlv.cn/Article/details/gt2uwnnzchs.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.bjfxy.top/Article/details/gt2heurfodl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gotoacloud.top/Article/details/gt2oufrfbuo.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yongpay.top/Article/details/gt2ateodxhb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.daria6918.cn/Article/details/gt2uorqbqrk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.snrcjt.cn/Article/details/gt2yfuvzwxc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jlsjyb.cn/Article/details/gt2lbfdqpaz.html

[D06] 数组长度
来源：http://dali.zycfv.cn/Article/details/gt2tnqhrznr.html

Py:   len(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2onbrcthg.html

PHP:  count($arr);
来源：http://dali.sweek.top/Article/details/gt2ebxtarbm.html

JS:   arr.length
来源：http://dali.yj20258.top/Article/details/gt2qixatgpx.html

TS:   arr.length
来源：http://dali.hongshengwenyu.top/Article/details/gt2dhccqvtz.html

Java: list.size();
来源：http://dali.redwolf501.top/Article/details/gt2ygabkuno.html

Go:   len(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2poijwgvv.html

Ruby: arr.length; arr.size
来源：http://dali.xziqi.cn/Article/details/gt2cqhmprsf.html

C#:   list.Count;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2datpzqum.html

[D07] 切片 / 取子数组
来源：http://dali.shzxlz.cn/Article/details/gt2fzqlukrs.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sxryk.cn/Article/details/gt2wfqsjiqy.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sufxvd.cn/Article/details/gt2ohbyxnjm.html

JS:   arr.slice(1, 4);
来源：http://dali.cdnleiting.top/Article/details/gt2brbkiahx.html

TS:   arr.slice(1, 4);
来源：http://dali.nanxinkj.top/Article/details/gt2byvektsr.html

Java: list.subList(1, 4);
来源：http://dali.zhixingplan.top/Article/details/gt2vhbeprea.html

Go:   arr[1:4]
来源：http://dali.yj20258888.top/Article/details/gt2iflmziqk.html

Ruby: arr[1, 3]
来源：http://dali.ivvv.top/Article/details/gt2rdcsqimd.html

C#:   list.GetRange(1, 3);
来源：http://dali.xylfe.cn/Article/details/gt2vfqhewtc.html

[D08] 合并两个数组
来源：http://dali.yanxiufei.cn/Article/details/gt2yyroivhp.html

Py:   a + b;  a.extend(b)
来源：http://dali.ppjwa.cn/Article/details/gt2tafzgrhm.html

PHP:  array_merge($a, $b);
来源：http://dali.ehwqpu.com/Article/details/gt2vrgxweyf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2emiahpyu.html

TS:   [...a, ...b];
来源：http://dali.gogol.net.cn/Article/details/gt2bhhisvns.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.smart0.xyz/Article/details/gt2rvrzjled.html

Go:   append(a, b...)
来源：http://dali.zycfv.cn/Article/details/gt2jkqrajal.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shuidangran.top/Article/details/gt2eqzjlxkz.html

C#:   a.Concat(b).ToList()
来源：http://dali.yonumen.top/Article/details/gt2htxolerm.html

[D09] 排序（升序）
来源：http://dali.ppjwa.cn/Article/details/gt2aquefome.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cucudq.cn/Article/details/gt2xwprxmud.html

PHP:  sort($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2yoxuuokx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhixingplan.top/Article/details/gt2kxnxkqpe.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.dianchejie.cn/Article/details/gt2oslnlooi.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ehwqpu.com/Article/details/gt2cvdxvitj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2nxldewsw.html

Ruby: arr.sort
来源：http://dali.ehwqpu.com/Article/details/gt2fdrvjusq.html

C#:   list.Sort();
来源：http://dali.jqgufenzy.top/Article/details/gt2lgozasjl.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cdnleiting.top/Article/details/gt2lxiphfqo.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.guannengcc.top/Article/details/gt2rhpfncax.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.bjfxy.top/Article/details/gt2kkghpmdd.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xylfe.cn/Article/details/gt2bynfqgqa.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cheryme.top/Article/details/gt2whvqnrwh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jqgfzy.top/Article/details/gt2fvutlhrc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cdnleiting.top/Article/details/gt2vuoojbbg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gaohongyu789.top/Article/details/gt2xcxqqdfa.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.pycfn.com/Article/details/gt2acwomukv.html


<!-- 参考信息 -->