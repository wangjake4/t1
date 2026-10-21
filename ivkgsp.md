代发 wailian999

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxuanxn.top/Article/details/gtyiumppme.html

[B10] 遍历同时拿索引
来源：http://dali.jqgfzy.top/Article/details/gtywapfzoa.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.shzxlz.cn/Article/details/gtxwqapnrj.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ppjwa.cn/Article/details/gtqxtlqavc.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zdqjudy.top/Article/details/gtcpnykosi.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.andypj.xyz/Article/details/gtlliaffkw.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthgeriogt.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.c1oappe.top/Article/details/gtyiyhcslq.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yj202588.top/Article/details/gtjmjermyg.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shangyingyoupin.top/Article/details/gtrxhfsrxt.html

[B11] 生成数字序列 / 区间
来源：http://dali.cucudq.cn/Article/details/gtssyrorlv.html

Py:   list(range(0, 10, 2))
来源：http://dali.cheryme.top/Article/details/gtzkqaesis.html

PHP:  range(0, 10, 2);
来源：http://dali.gzhubu.top/Article/details/gtfibledhy.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hysaishi.cn/Article/details/gtvkzefapf.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gogol.net.cn/Article/details/gtgexdacel.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.sysykeji.top/Article/details/gttqsjygcs.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.chenlongwang.top/Article/details/gtiwcnwayf.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhiwuduotai.top/Article/details/gtfjaizvkc.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.sufxvd.cn/Article/details/gtozaahppf.html

[B12] 跳出多层循环
来源：http://dali.kuanghao11.cn/Article/details/gtghrhrgyn.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jinyuanbaomall.cn/Article/details/gthosshrnz.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gtilhukkwb.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hammf.cn/Article/details/gtqpxghfrv.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ehwqpu.com/Article/details/gtcemggknp.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbiudpccz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hammf.cn/Article/details/gtmumlyhxg.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.c1oappe.top/Article/details/gtjkiilvmv.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ydzc1.top/Article/details/gtlrbdqzbd.html

[B13] 判断是否为数字
来源：http://dali.zhoulong.xyz/Article/details/gthhoqjiep.html

Py:   isinstance(x, (int, float))
来源：http://dali.nanxuanxn.top/Article/details/gtvgjwpvxb.html

PHP:  is_numeric($x)
来源：http://dali.zhongyouzk.top/Article/details/gtpjtifrcs.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ydzc1.top/Article/details/gtxnftbmzg.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthkatnfop.html

Java: x instanceof Number
来源：http://dali.cucudq.cn/Article/details/gtmjppgmfr.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ppjwa.cn/Article/details/gteubmipcv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.daria6918.cn/Article/details/gtrhkvtxzi.html

C#:   x is int or double or decimal
来源：http://dali.wangdashe.top/Article/details/gtftzxiwjr.html

[B14] 判断值是否在集合内
来源：http://dali.fzhhl.top/Article/details/gtqqzgojvr.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.chenzaomai.com/Article/details/gtumdbdbdm.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjveuyzo.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.gzhubu.top/Article/details/gtrjrwquls.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.nwbrower.top/Article/details/gtlpuglrcg.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.sxryk.cn/Article/details/gtlmwykiye.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtawayngmw.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yangfankeji.com/Article/details/gtvlsadyqz.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.snrcjt.cn/Article/details/gtbkcbjnnk.html

[B15] 布尔运算与取反
来源：http://dali.hfpthk.cn/Article/details/gtxonfagmn.html

Py:   a and b or not c
来源：http://dali.smart0.xyz/Article/details/gtttumednu.html

PHP:  $a && $b || !$c
来源：http://dali.9152youxi.cn/Article/details/gtzsrqzjgc.html

JS:   a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gtbwvdzjmr.html

TS:   a && b || !c
来源：http://dali.bjfxy.top/Article/details/gteiuelcsh.html

Java: a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gtexpiycdq.html

Go:   a && b || !c
来源：http://dali.hammf.cn/Article/details/gtxnqlfspr.html

Ruby: a && b || !c
来源：http://dali.cucudq.cn/Article/details/gtmzyshaet.html

C#:   a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gtljhgnzsa.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.havefunace.top/Article/details/gtwyzeoeej.html

Py:   if not data: return
来源：http://dali.jyoumei.cn/Article/details/gtxwkvycyh.html

PHP:  if (!$data) { return; }
来源：http://dali.zhixingplan.top/Article/details/gtnaxzbuiw.html

JS:   if (!data) return;
来源：http://dali.jqgfzy.top/Article/details/gtklolhrer.html

TS:   if (!data) return;
来源：http://dali.yuxming.cn/Article/details/gthafdkwxg.html

Java: if (data == null) return;
来源：http://dali.havefunace.top/Article/details/gtqjrcflnn.html

Go:   if data == nil { return }
来源：http://dali.sweek.top/Article/details/gtuqyamojl.html

Ruby: return if data.nil?
来源：http://dali.guannengcc.top/Article/details/gtxvymafmj.html

C#:   if (data == null) return;
来源：http://dali.jianghu66.top/Article/details/gtdbjmqeii.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtfmhizbyb.html

C. 函数与作用域
来源：http://dali.9152youxi.cn/Article/details/gtbjpvvsnc.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtflvwhenk.html

[C01] 定义函数
来源：http://dali.ehwqpu.com/Article/details/gtipeqepvl.html

Py:   def add(a, b): return a + b
来源：http://dali.xinyue.icu/Article/details/gtyekvgajn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.vqdsnc.cn/Article/details/gtwecionbn.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gtzsiadmlg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtouunokoo.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqfdknetk.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.guannengcc.top/Article/details/gtruxozcwk.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yuxming.cn/Article/details/gtfwbusexf.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtynzaawmw.html

[C02] 默认参数
来源：http://dali.shuidangran.top/Article/details/gtyktbcpfz.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gtmtuhrkbq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ppjwa.cn/Article/details/gtyfyzrrfc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.sweek.top/Article/details/gtogwcsxhk.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xuanzx.com/Article/details/gttrvygike.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.chenlongwang.top/Article/details/gtpqfxlqzs.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jinqigufen.top/Article/details/gtbslmjcsi.html

Ruby: def greet(name = "World") = name
来源：http://dali.ybcxt.top/Article/details/gtogbclqcj.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.vqdsnc.cn/Article/details/gtzojwdtmo.html

[C03] 可变参数
来源：http://dali.jinqigfzy.top/Article/details/gtazgcgsjc.html

Py:   def total(*args): return sum(args)
来源：http://dali.sweek.top/Article/details/gtqhkudlbb.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xuanzx.com/Article/details/gtxusiixxy.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhengqikj.top/Article/details/gtackqzmvi.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xuetiantiany.cn/Article/details/gtltumlulp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.fengsongda.top/Article/details/gtydxutiec.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.chenzaomai.com/Article/details/gtmksgpmal.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sxryk.cn/Article/details/gtbduyepwm.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdgemrutx.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cashguo.top/Article/details/gtffvuvphd.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.9152youxi.cn/Article/details/gtusfqcred.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.chenzaomai.com/Article/details/gtfwpfsfqk.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.vqdsnc.cn/Article/details/gtwrwxgbdq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jqgufenzy.top/Article/details/gtceeacvei.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shzxlz.cn/Article/details/gtstgpszts.html

Go:   // 无：用配置结构体参数
来源：http://dali.sweek.top/Article/details/gtorltisbs.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shuidangran.top/Article/details/gtgswlkomg.html

C#:   f(a: 1, b: 2)
来源：http://dali.yvedp.cn/Article/details/gtcwydzzes.html

[C05] 返回多个值
来源：http://dali.ybcxt.top/Article/details/gtnbwktqsp.html

Py:   return a, b
来源：http://dali.vqdsnc.cn/Article/details/gtoyqrtaqk.html

PHP:  return [$a, $b];
来源：http://dali.nwbrower.top/Article/details/gtnzsyavms.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zdqjudy.top/Article/details/gtewfhugtu.html

TS:   return { a, b };
来源：http://dali.yangfankeji.com/Article/details/gtfbpebdgr.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xziqi.cn/Article/details/gtyddrrnnn.html

Go:   return a, b
来源：http://dali.aibaodan.cn/Article/details/gthwhzzlzl.html

Ruby: return a, b
来源：http://dali.guowangkeji.top/Article/details/gtohhuzkuw.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hywenlv.cn/Article/details/gtobwpdofa.html

[C06] 匿名函数 / lambda
来源：http://dali.tianlin.xyz/Article/details/gtmqtsrudm.html

Py:   square = lambda x: x * x
来源：http://dali.gogol.net.cn/Article/details/gthdbjczra.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.daria6918.cn/Article/details/gtsetwsbpi.html

JS:   const square = x => x * x;
来源：http://dali.ivvv.top/Article/details/gtyxhtdpqh.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.daxiang520.top/Article/details/gtuuufgrro.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.mhx1999.top/Article/details/gtutuszuhj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ybcxt.top/Article/details/gtucfmvloy.html

Ruby: square = ->(x) { x * x }
来源：http://dali.pengpengdd.cyou/Article/details/gtevenqatv.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.aizwys.cn/Article/details/gttzfdzmfg.html

[C07] 把函数作为参数传入
来源：http://dali.chenzaomai.com/Article/details/gtfbrbnyaz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shanyushiyangtech.top/Article/details/gtomutohbk.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.haohaochexian.top/Article/details/gtsxhsmcpa.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hysaishi.cn/Article/details/gtlddxvwjs.html

TS:   arr.map(String)
来源：http://dali.birdmap.top/Article/details/gtvxjroobs.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.chenzaomai.com/Article/details/gtkkqupysc.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.tian-w.cn/Article/details/gtecqjqfdx.html

Ruby: arr.map(&:upcase)
来源：http://dali.yvedp.cn/Article/details/gtidcukgsn.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jinqigfzy.top/Article/details/gtkxrzxgne.html

[C08] 闭包
来源：http://dali.zhiwuduotai.top/Article/details/gtwswyhioa.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yonumen.top/Article/details/gtibaitzdr.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hnqzz.top/Article/details/gtkmwpdofe.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hnqzz.top/Article/details/gtuieliqyq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yuxming.cn/Article/details/gtomkrysaz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cqqwz.cn/Article/details/gtosituntn.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.c1oappe.top/Article/details/gtiuzivnej.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yj20258888.top/Article/details/gtgfqgwpjy.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zycfv.cn/Article/details/gtcmvtzuns.html

[C09] 递归
来源：http://dali.havefunace.top/Article/details/gtwrjqsxuy.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.guannengcc.top/Article/details/gtaialjejt.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.sweek.top/Article/details/gtquuoxazz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenjidiqi.icu/Article/details/gtjjpziqyt.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hywenlv.cn/Article/details/gtnocjzvwz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.meibo888.top/Article/details/gtpjdnsssc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.bjfxy.top/Article/details/gtncgjqrhm.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yangfankeji.com/Article/details/gtpetjtigz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hywenlv.cn/Article/details/gtnipincdc.html

[C10] 变量作用域
来源：http://dali.jqgfzy.top/Article/details/gtavlgluom.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jlsjyb.cn/Article/details/gtydnlpfof.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hnxiangtu.top/Article/details/gtnbruhipm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.9152youxi.cn/Article/details/gtgzkshncm.html

TS:   同 JS
来源：http://dali.cashguo.top/Article/details/gtvqdbvtmd.html

Java: 方法内为块级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgfldliym.html

Go:   花括号块级作用域
来源：http://dali.svipenyu.cn/Article/details/gtnyefuanq.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.fzhhl.top/Article/details/gtgdaeckps.html

C#:   块级作用域
来源：http://dali.aibaodan.cn/Article/details/gttihfrdfb.html

[C11] 模块导入与导出
来源：http://dali.jinghuilouyu.cn/Article/details/gtjrxqcqaa.html

Py:   from module import func
来源：http://dali.nwbrower.top/Article/details/gtddiqmwkj.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cucudq.cn/Article/details/gtnhngcnuq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jianghu66.top/Article/details/gteqjoljhb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jqgufenzy.top/Article/details/gtcwpxjwfa.html

Java: import java.util.List;
来源：http://dali.daria6918.cn/Article/details/gtqaefpila.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.andypj.xyz/Article/details/gtnrmyagft.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ybcxt.top/Article/details/gtclzdsiih.html

C#:   using System.Text;
来源：http://dali.cqqwz.cn/Article/details/gtqvscnmup.html

[C12] 立即执行函数 IIFE
来源：http://dali.xylfe.cn/Article/details/gteuqiilru.html

Py:   (lambda: print("run"))()
来源：http://dali.316326.xyz/Article/details/gtsiyxbpeg.html

PHP:  (function () { echo "run"; })();
来源：http://dali.tian-w.cn/Article/details/gtzhzmdfzc.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cucudq.cn/Article/details/gthaenmutr.html

TS:   (() => { console.log("run"); })();
来源：http://dali.pycfn.com/Article/details/gtbdhhdfda.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.redwolf501.top/Article/details/gtaangbgex.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yuxming.cn/Article/details/gtutvhizpx.html

Ruby: -> { puts "run" }.call
来源：http://dali.snrcjt.cn/Article/details/gtdcjoviqy.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.nanxuanxn.top/Article/details/gtwpttlzxe.html

[C13] 类型声明 / 类型注解
来源：http://dali.jinghuilouyu.cn/Article/details/gtmwmkzcqr.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.fengsongda.top/Article/details/gtqiebldli.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.mhx1999.top/Article/details/gtxoutrtkc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.kuanghao11.cn/Article/details/gtwmllfptj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hammf.cn/Article/details/gtzsepvbzo.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gtjyccralz.html

Go:   func add(a, b int) int
来源：http://dali.yanxiufei.cn/Article/details/gtxciuiezu.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cheryme.top/Article/details/gtdbrmavog.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jyoumei.cn/Article/details/gtfioivafx.html

[C14] 泛型函数
来源：http://dali.shangyingyoupin.top/Article/details/gtgnjmhhgi.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hammf.cn/Article/details/gthkjbzyms.html

PHP:  // 无泛型
来源：http://dali.mhx1999.top/Article/details/gtnqczpkrf.html

JS:   // 无泛型
来源：http://dali.jlsjyb.cn/Article/details/gtqxjexzmd.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.bjfxy.top/Article/details/gtdrslyoxh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.0kj1m.cn/Article/details/gtmgzyufrp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ppjwa.cn/Article/details/gtxxorlwuh.html

Ruby: # 无泛型
来源：http://dali.zhongyouzk.top/Article/details/gtoebbleen.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtodykieki.html

[C15] 解构 / 展开参数
来源：http://dali.zhiwuduotai.top/Article/details/gtnyvynwbk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhengqikj.top/Article/details/gtrrmhhpir.html

PHP:  [$a, $b] = $pair;
来源：http://dali.tanke756.top/Article/details/gtgefxqcpc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtajfvgswq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jyoumei.cn/Article/details/gtgkzdzdmd.html

Java: // 无解构
来源：http://dali.gogol.net.cn/Article/details/gttajrweal.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gtpwpitnkw.html

Ruby: a, b = pair
来源：http://dali.zhongyouzk.top/Article/details/gtlyfczhrm.html

C#:   var (a, b) = pair;
来源：http://dali.yj20258.top/Article/details/gtuvdyalzv.html

[C16] 函数 / 方法重载
来源：http://dali.pycfn.com/Article/details/gtbxrgxnrb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shuidangran.top/Article/details/gtqntxlvsg.html

PHP:  // 无重载
来源：http://dali.yj20258888.top/Article/details/gthlueppyr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.aizwys.cn/Article/details/gtgierrivt.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jiagoushi.top/Article/details/gtflddhzph.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ehwqpu.com/Article/details/gtxtuqwsqk.html

Go:   // 无重载：用不同函数名
来源：http://dali.yj20258.top/Article/details/gtpfzvtegt.html

Ruby: # 无重载：靠动态参数
来源：http://dali.chenjidiqi.icu/Article/details/gtkfftemou.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtwphuxdqm.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtxmwxllce.html

D. 数组 / 列表 / 集合
来源：http://dali.nwbrower.top/Article/details/gtasyqecoi.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtgbdxlcmh.html

[D01] 创建数组 / 列表
来源：http://dali.hammf.cn/Article/details/gtkpmjmupl.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.nwbrower.top/Article/details/gtemncihth.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hywenlv.cn/Article/details/gtqnkbqktc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpblsnmah.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.9152youxi.cn/Article/details/gtppzzrgjc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.vqdsnc.cn/Article/details/gtsanetkwm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.c1oappe.top/Article/details/gtszgskgei.html

Ruby: arr = [1, 2, 3]
来源：http://dali.svipenyu.cn/Article/details/gtphiqmarz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.9152youxi.cn/Article/details/gtorrycjdh.html

[D02] 追加元素到末尾
来源：http://dali.smart0.xyz/Article/details/gtcymxthli.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.pycfn.com/Article/details/gtpdwxmbpq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.bjfxy.top/Article/details/gtvdeipcdi.html

JS:   arr.push(4);
来源：http://dali.guannengcc.top/Article/details/gtopqqouib.html

TS:   arr.push(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmmhtaran.html

Java: list.add(4);
来源：http://dali.chenlongwang.top/Article/details/gttstbsmwc.html

Go:   arr = append(arr, 4)
来源：http://dali.jqgufenzy.top/Article/details/gtlxdjcnmg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.andypj.xyz/Article/details/gtwvjucugu.html

C#:   list.Add(4);
来源：http://dali.ybcxt.top/Article/details/gtwwrcdbkq.html

[D03] 在指定位置插入元素
来源：http://dali.wangdashe.top/Article/details/gtsacbsvmr.html

Py:   arr.insert(0, 0)
来源：http://dali.jinqigufen.top/Article/details/gteefqokyq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.daxiang520.top/Article/details/gtoxqjvdec.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.wangshuangyany.cn/Article/details/gtnooxggnv.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jqgfzy.top/Article/details/gtndnuvkpn.html

Java: list.add(0, 0);
来源：http://dali.hfpthk.cn/Article/details/gthguldjto.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.chenjidiqi.icu/Article/details/gtcjjtcsty.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yuanzhike.top/Article/details/gtsficpnlh.html

C#:   list.Insert(0, 0);
来源：http://dali.tian-w.cn/Article/details/gtyuxjiqhi.html

[D04] 删除元素
来源：http://dali.svipenyu.cn/Article/details/gtabpiotir.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.kuanghao11.cn/Article/details/gtznvlipvu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.chenzaomai.com/Article/details/gtktybwulw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ydzc1.top/Article/details/gtitttgxub.html

TS:   arr.splice(0, 1);
来源：http://dali.quarkkingdee.top/Article/details/gtybzvzzzs.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdgwymcyq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.havefunace.top/Article/details/gtrluayocs.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtolfrdcsj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jqgufenzy.top/Article/details/gtfnlkgmnq.html

[D05] 访问与修改元素
来源：http://dali.aibaodan.cn/Article/details/gtthrqkzyz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sxryk.cn/Article/details/gtdtvhyoex.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gtljuacocf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.mhx1999.top/Article/details/gtaebzqdvq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cucudq.cn/Article/details/gtuoxxqsto.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ivvv.top/Article/details/gtqvitmflv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shuidangran.top/Article/details/gtwqymhmks.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnqzz.top/Article/details/gtuhtmjoov.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.meibo888.top/Article/details/gtdriajszm.html

[D06] 数组长度
来源：http://dali.316326.xyz/Article/details/gtpbaxcbpn.html

Py:   len(arr)
来源：http://dali.cdnleiting.top/Article/details/gtndkcxuzw.html

PHP:  count($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtzvanfcvq.html

JS:   arr.length
来源：http://dali.hnqzz.top/Article/details/gtlzukbqsa.html

TS:   arr.length
来源：http://dali.zhixingplan.top/Article/details/gtevogdtqd.html

Java: list.size();
来源：http://dali.yanxiufei.cn/Article/details/gtggfhbahn.html

Go:   len(arr)
来源：http://dali.iojbl.cn/Article/details/gttrfyibfl.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gtjbvgqefq.html

C#:   list.Count;
来源：http://dali.shuidangran.top/Article/details/gthbququwy.html

[D07] 切片 / 取子数组
来源：http://dali.316326.xyz/Article/details/gtqrtrflam.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzhcdncxj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.tanke756.top/Article/details/gtivsestqq.html

JS:   arr.slice(1, 4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtlfuhttvn.html

TS:   arr.slice(1, 4);
来源：http://dali.ybcxt.top/Article/details/gtvujvqbfu.html

Java: list.subList(1, 4);
来源：http://dali.cashguo.top/Article/details/gtttwhbvad.html

Go:   arr[1:4]
来源：http://dali.fengsongda.top/Article/details/gtidimwlsy.html

Ruby: arr[1, 3]
来源：http://dali.xinyue.icu/Article/details/gtsqwosruz.html

C#:   list.GetRange(1, 3);
来源：http://dali.xuanzx.com/Article/details/gtpuvojiuv.html

[D08] 合并两个数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtdtjzekll.html

Py:   a + b;  a.extend(b)
来源：http://dali.tanke756.top/Article/details/gtqrhypblv.html

PHP:  array_merge($a, $b);
来源：http://dali.wangdashe.top/Article/details/gteqbtomww.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xylfe.cn/Article/details/gtleuuvkav.html

TS:   [...a, ...b];
来源：http://dali.ybcxt.top/Article/details/gtanovmtsh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.bjfxy.top/Article/details/gtkatrwqvw.html

Go:   append(a, b...)
来源：http://dali.yangfankeji.com/Article/details/gtesdeyijy.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhiwuduotai.top/Article/details/gtmocotcsu.html

C#:   a.Concat(b).ToList()
来源：http://dali.316326.xyz/Article/details/gtcnaoaxtn.html

[D09] 排序（升序）
来源：http://dali.bjfxy.top/Article/details/gtvblwowfy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.feifeiyinyue.top/Article/details/gtzojqmmdc.html

PHP:  sort($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwuezfxdg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jianghu66.top/Article/details/gtsdpavqbq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhongyouzk.top/Article/details/gtjnvietlt.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.kuanghao11.cn/Article/details/gthdhapymp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.tian-w.cn/Article/details/gtvxsjmkeu.html

Ruby: arr.sort
来源：http://dali.shangyingyoupin.top/Article/details/gtirdfjrgp.html

C#:   list.Sort();
来源：http://dali.yongpay.top/Article/details/gtusrqwjrx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.daria6918.cn/Article/details/gtsmetwkvh.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.mhx1999.top/Article/details/gtsoempsll.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinqigfzy.top/Article/details/gtkjdkxetq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhengqikj.top/Article/details/gttotqmoxl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.mhx1999.top/Article/details/gtmkbgnzhs.html


<!-- 参考信息 -->