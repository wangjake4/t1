代发 wailian999

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.xinyue.icu/Article/details/gtkggjlcej.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.havefunace.top/Article/details/gtfwopahyy.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.gogol.net.cn/Article/details/gtlzbawlts.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shuidangran.top/Article/details/gtsuqbsjue.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yj20258888.top/Article/details/gtitifcmej.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.gotoacloud.top/Article/details/gtqemcgnhm.html

[B11] 生成数字序列 / 区间
来源：http://dali.nanxinkj.top/Article/details/gtxosiayfk.html

Py:   list(range(0, 10, 2))
来源：http://dali.yongpay.top/Article/details/gtijpzgitw.html

PHP:  range(0, 10, 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyahbtjll.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sysykeji.top/Article/details/gtbytghzic.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.haohaochexian.top/Article/details/gtxlqyrvnw.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yangfankeji.com/Article/details/gtburbvqjo.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hammf.cn/Article/details/gtryyrjlyf.html

Ruby: (0...10).step(2).to_a
来源：http://dali.wangshuangyany.cn/Article/details/gttwkktzda.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.cashguo.top/Article/details/gtllwmxsdq.html

[B12] 跳出多层循环
来源：http://dali.sweek.top/Article/details/gtshqolftr.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.smart0.xyz/Article/details/gtijvyipda.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hammf.cn/Article/details/gtnaflundy.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ehwqpu.com/Article/details/gthojizshe.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcoiqievy.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cucudq.cn/Article/details/gttbqzeyvh.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.cqqwz.cn/Article/details/gtisqhjcap.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.c1oappe.top/Article/details/gtbucwctxm.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.9152youxi.cn/Article/details/gtzrhpvlqk.html

[B13] 判断是否为数字
来源：http://dali.chenjidiqi.icu/Article/details/gtfcgltzpa.html

Py:   isinstance(x, (int, float))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcapdlmqg.html

PHP:  is_numeric($x)
来源：http://dali.dashuyun.cn/Article/details/gtvsictynj.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.mhx1999.top/Article/details/gtxpqgfrwo.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinqigfzy.top/Article/details/gtocsqinhz.html

Java: x instanceof Number
来源：http://dali.chenjidiqi.icu/Article/details/gtfccwtspy.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.guowangkeji.top/Article/details/gtjplsceua.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ppjwa.cn/Article/details/gtyolzrmkw.html

C#:   x is int or double or decimal
来源：http://dali.shzxlz.cn/Article/details/gtmuhrrubt.html

[B14] 判断值是否在集合内
来源：http://dali.sufxvd.cn/Article/details/gtodnogisd.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.mhx1999.top/Article/details/gtocflkjuz.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xuanzx.com/Article/details/gtvpntvuvx.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.daria6918.cn/Article/details/gthvcjvhku.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ivvv.top/Article/details/gtgcxmjomt.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jinqigfzy.top/Article/details/gtswmlkghw.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jqgfzy.top/Article/details/gtgmtniwpm.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shuidangran.top/Article/details/gtxaokhohq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hammf.cn/Article/details/gtnnkajjgp.html

[B15] 布尔运算与取反
来源：http://dali.tianlin.xyz/Article/details/gtevmzocfm.html

Py:   a and b or not c
来源：http://dali.ehwqpu.com/Article/details/gtlishauhs.html

PHP:  $a && $b || !$c
来源：http://dali.daxiang520.top/Article/details/gtbcmafoid.html

JS:   a && b || !c
来源：http://dali.jqgufenzy.top/Article/details/gtotpysoyw.html

TS:   a && b || !c
来源：http://dali.yonumen.top/Article/details/gtlxwqhxfs.html

Java: a && b || !c
来源：http://dali.yj202588.top/Article/details/gtvutariza.html

Go:   a && b || !c
来源：http://dali.pycfn.com/Article/details/gtayhmhctv.html

Ruby: a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gtzbvncwmw.html

C#:   a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gtdvgciwvk.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yvedp.cn/Article/details/gtsrymuqyb.html

Py:   if not data: return
来源：http://dali.gogol.net.cn/Article/details/gtgviopdmk.html

PHP:  if (!$data) { return; }
来源：http://dali.sxryk.cn/Article/details/gtadpkyeuh.html

JS:   if (!data) return;
来源：http://dali.yueranfly.top/Article/details/gtgeiasalj.html

TS:   if (!data) return;
来源：http://dali.fengsongda.top/Article/details/gtpeyukjfo.html

Java: if (data == null) return;
来源：http://dali.pycfn.com/Article/details/gtlhvivmkq.html

Go:   if data == nil { return }
来源：http://dali.redwolf501.top/Article/details/gtjbhdfhdw.html

Ruby: return if data.nil?
来源：http://dali.xziqi.cn/Article/details/gtvrvfitej.html

C#:   if (data == null) return;
来源：http://dali.ydzc1.top/Article/details/gtlqfztgor.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtbqhmxrxr.html

C. 函数与作用域
来源：http://dali.shuidangran.top/Article/details/gtmqaslnor.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgksyduvt.html

[C01] 定义函数
来源：http://dali.meibo888.top/Article/details/gtbhduouux.html

Py:   def add(a, b): return a + b
来源：http://dali.ydzc1.top/Article/details/gtrupesjml.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.9152youxi.cn/Article/details/gtliykmtnd.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gtmfivlhpg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtysakjhxw.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.cheryme.top/Article/details/gtyvsjxvcw.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jinqigfzy.top/Article/details/gtllgbsxxw.html

Ruby: def add(a, b); a + b; end
来源：http://dali.feifeiyinyue.top/Article/details/gtodaqpcxe.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gtvkgdilxu.html

[C02] 默认参数
来源：http://dali.cucudq.cn/Article/details/gtrpfgmusr.html

Py:   def greet(name="World"): return name
来源：http://dali.gaohongyu789.top/Article/details/gtvwasfcfv.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shzxlz.cn/Article/details/gtnqzeltfb.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttepzgeog.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtuphaqlwb.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.meibo888.top/Article/details/gtxdkgmxeg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shangyingyoupin.top/Article/details/gtcgczwnzz.html

Ruby: def greet(name = "World") = name
来源：http://dali.ivvv.top/Article/details/gtutxhukhy.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yueranfly.top/Article/details/gthohljzck.html

[C03] 可变参数
来源：http://dali.yuxming.cn/Article/details/gtxxnzttdj.html

Py:   def total(*args): return sum(args)
来源：http://dali.haohaochexian.top/Article/details/gtifypdeqo.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xinyue.icu/Article/details/gttnvhgwsr.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.birdmap.top/Article/details/gtwquxmlaj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.svipenyu.cn/Article/details/gtcqojkwec.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinqigfzy.top/Article/details/gtglaqojbi.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.andypj.xyz/Article/details/gthjnhdilr.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhengqikj.top/Article/details/gtmfnsecya.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.9152youxi.cn/Article/details/gtidogaqtv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.tian-w.cn/Article/details/gtkevuuzst.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhixingplan.top/Article/details/gttvobfldk.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jinqigfzy.top/Article/details/gtilfbzqtd.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.andypj.xyz/Article/details/gttfmuzbuj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.dashuyun.cn/Article/details/gtadyyastm.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.nanxuanxn.top/Article/details/gtjomtsbfm.html

Go:   // 无：用配置结构体参数
来源：http://dali.snrcjt.cn/Article/details/gtmobbtmwo.html

Ruby: f(a: 1, b: 2)
来源：http://dali.dianchejie.cn/Article/details/gtadvchpna.html

C#:   f(a: 1, b: 2)
来源：http://dali.jqgufenzy.top/Article/details/gtjaujlaxz.html

[C05] 返回多个值
来源：http://dali.ybcxt.top/Article/details/gthbbflmzl.html

Py:   return a, b
来源：http://dali.hywenlv.cn/Article/details/gtdeceysnf.html

PHP:  return [$a, $b];
来源：http://dali.quarkkingdee.top/Article/details/gtpgnrllcd.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sufxvd.cn/Article/details/gtfjoyyunb.html

TS:   return { a, b };
来源：http://dali.hywenlv.cn/Article/details/gtdvoeqtah.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.aizwys.cn/Article/details/gtoqwpnzjs.html

Go:   return a, b
来源：http://dali.zycfv.cn/Article/details/gtdsqtpncf.html

Ruby: return a, b
来源：http://dali.sysykeji.top/Article/details/gtfbpimnnl.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.quarkkingdee.top/Article/details/gtpyfvoirc.html

[C06] 匿名函数 / lambda
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjcmnvmnc.html

Py:   square = lambda x: x * x
来源：http://dali.zhengqikj.top/Article/details/gtgwsbsyst.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.daria6918.cn/Article/details/gtsqufooza.html

JS:   const square = x => x * x;
来源：http://dali.ydzc1.top/Article/details/gtlsvczwvt.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.sufxvd.cn/Article/details/gtanalivwf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yongpay.top/Article/details/gtwjmknfng.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhoulong.xyz/Article/details/gtcehkzpwc.html

Ruby: square = ->(x) { x * x }
来源：http://dali.wangdashe.top/Article/details/gtigksgsnm.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hywenlv.cn/Article/details/gtlcmcslgh.html

[C07] 把函数作为参数传入
来源：http://dali.yj202588.top/Article/details/gtdepedpdq.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpzneythq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yj20258888.top/Article/details/gtspsbwmfv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.havefunace.top/Article/details/gtfspfxtxw.html

TS:   arr.map(String)
来源：http://dali.yonumen.top/Article/details/gtrgijdnyc.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtszcpctqs.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.guowangkeji.top/Article/details/gtvtobfpiw.html

Ruby: arr.map(&:upcase)
来源：http://dali.tanke756.top/Article/details/gtfgxctgjj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.birdmap.top/Article/details/gtkqavwapb.html

[C08] 闭包
来源：http://dali.yvedp.cn/Article/details/gtedszdfdj.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.gotoacloud.top/Article/details/gtyvpjafim.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ybcxt.top/Article/details/gtwsxqojos.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jinqigufen.top/Article/details/gtjggobrko.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.aibaodan.cn/Article/details/gtviffoysf.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.9152youxi.cn/Article/details/gtoeoofgwb.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cashguo.top/Article/details/gtvsgoszgb.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hnxiangtu.top/Article/details/gtpzikikpp.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfutjebxh.html

[C09] 递归
来源：http://dali.cqqwz.cn/Article/details/gtdsmlrwrf.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zycfv.cn/Article/details/gticfgomii.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.nanxuanxn.top/Article/details/gttwmgjlgm.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.kuanghao11.cn/Article/details/gtqwuoszuo.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.kuanghao11.cn/Article/details/gtxqohdxlg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.dashuyun.cn/Article/details/gttekvvqbp.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ehwqpu.com/Article/details/gtvzpgvvib.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.kuanghao11.cn/Article/details/gtalgajwpx.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.dashuyun.cn/Article/details/gtyzgdcacm.html

[C10] 变量作用域
来源：http://dali.ppjwa.cn/Article/details/gtuslqefjt.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.mhx1999.top/Article/details/gtwqjgpiun.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jiagoushi.top/Article/details/gthhuhaseh.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cdnleiting.top/Article/details/gtolppxnrw.html

TS:   同 JS
来源：http://dali.mhx1999.top/Article/details/gtsznofjgc.html

Java: 方法内为块级作用域
来源：http://dali.0kj1m.cn/Article/details/gtuxejxiyc.html

Go:   花括号块级作用域
来源：http://dali.guowangkeji.top/Article/details/gtfqaslcis.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yangfankeji.com/Article/details/gtmepthdxq.html

C#:   块级作用域
来源：http://dali.ybcxt.top/Article/details/gtcirnykir.html

[C11] 模块导入与导出
来源：http://dali.smart0.xyz/Article/details/gtmfmimzkn.html

Py:   from module import func
来源：http://dali.daria6918.cn/Article/details/gttowuohqo.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhoulong.xyz/Article/details/gteinpiggb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.gaohongyu789.top/Article/details/gtujbbskru.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.pengpengdd.cyou/Article/details/gtpkfkccdd.html

Java: import java.util.List;
来源：http://dali.dashuyun.cn/Article/details/gtmrmmvkfc.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.feifeiyinyue.top/Article/details/gtvpivfzcw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.fzhhl.top/Article/details/gtozijshft.html

C#:   using System.Text;
来源：http://dali.ehwqpu.com/Article/details/gtetzxlfar.html

[C12] 立即执行函数 IIFE
来源：http://dali.hfpthk.cn/Article/details/gtukcmuuey.html

Py:   (lambda: print("run"))()
来源：http://dali.kuanghao11.cn/Article/details/gtfmsbxxay.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yonumen.top/Article/details/gtzsqafwsh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.havefunace.top/Article/details/gtqngwruuc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.gogol.net.cn/Article/details/gtidlgbpjg.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.havefunace.top/Article/details/gtskcwqhkf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.smart0.xyz/Article/details/gtwjpnpzqu.html

Ruby: -> { puts "run" }.call
来源：http://dali.ydzc1.top/Article/details/gtfkjdgiai.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhengqikj.top/Article/details/gtbffzxgca.html

[C13] 类型声明 / 类型注解
来源：http://dali.hnqzz.top/Article/details/gtmmuwsbda.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.iojbl.cn/Article/details/gtmippsxfx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cashguo.top/Article/details/gtiqmjhxev.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.mhx1999.top/Article/details/gtbmsihafd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj20258.top/Article/details/gtirfrztvz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gtenwfgxjr.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gtujpxrqru.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.daria6918.cn/Article/details/gtsswvbwzq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.sxryk.cn/Article/details/gtkuczfvvf.html

[C14] 泛型函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtwhfdejnu.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinqigfzy.top/Article/details/gtrzgvriob.html

PHP:  // 无泛型
来源：http://dali.gaohongyu789.top/Article/details/gtqhjwwmul.html

JS:   // 无泛型
来源：http://dali.hnqzz.top/Article/details/gtjkngvqjt.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.nwbrower.top/Article/details/gtmnbtjovp.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yueranfly.top/Article/details/gtlyhylpen.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.daxiang520.top/Article/details/gtijgmuiyy.html

Ruby: # 无泛型
来源：http://dali.bjfxy.top/Article/details/gtologahhx.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cucudq.cn/Article/details/gtswmynrtk.html

[C15] 解构 / 展开参数
来源：http://dali.yj20258.top/Article/details/gtydibeuja.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhongyouzk.top/Article/details/gttovmmfsq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgxbadyfv.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.guannengcc.top/Article/details/gtkqtweqfc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhixingplan.top/Article/details/gtvlrikowc.html

Java: // 无解构
来源：http://dali.zhiwuduotai.top/Article/details/gtiqzdhtjg.html

Go:   // 无解构
来源：http://dali.ehwqpu.com/Article/details/gthwtimeiq.html

Ruby: a, b = pair
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsnufywum.html

C#:   var (a, b) = pair;
来源：http://dali.cucudq.cn/Article/details/gtbpxuhubt.html

[C16] 函数 / 方法重载
来源：http://dali.zhiwuduotai.top/Article/details/gtaekmgeqm.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jqgfzy.top/Article/details/gtqlvopanp.html

PHP:  // 无重载
来源：http://dali.havefunace.top/Article/details/gtzdblirvv.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yuxming.cn/Article/details/gtmbrfddqz.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yuxming.cn/Article/details/gtpdmrgtnc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtceflhhdl.html

Go:   // 无重载：用不同函数名
来源：http://dali.316326.xyz/Article/details/gtapfjfypb.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinqigufen.top/Article/details/gturihaeta.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.sweek.top/Article/details/gtxpepqesy.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtuhvycepz.html

D. 数组 / 列表 / 集合
来源：http://dali.mhx1999.top/Article/details/gtrhudbmni.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtyjkswiet.html

[D01] 创建数组 / 列表
来源：http://dali.hnxiangtu.top/Article/details/gtovgdufdp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.pycfn.com/Article/details/gthglbvqxf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.iojbl.cn/Article/details/gtxihvtpjy.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.fzhhl.top/Article/details/gtdxlfgfds.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cqqwz.cn/Article/details/gtvbeohtce.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yangfankeji.com/Article/details/gtwiawkkke.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shanyushiyangtech.top/Article/details/gtyubiegsk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jqgfzy.top/Article/details/gtpbbamxoz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinqigufen.top/Article/details/gtyqarmtsq.html

[D02] 追加元素到末尾
来源：http://dali.fzhhl.top/Article/details/gtdhdznnvt.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.bjfxy.top/Article/details/gthdwinoxr.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.daxiang520.top/Article/details/gtpyrldpcs.html

JS:   arr.push(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtgejbwdbb.html

TS:   arr.push(4);
来源：http://dali.svipenyu.cn/Article/details/gtxzyhylze.html

Java: list.add(4);
来源：http://dali.gzhubu.top/Article/details/gtsdcspnrw.html

Go:   arr = append(arr, 4)
来源：http://dali.c1oappe.top/Article/details/gtgqeqtquh.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.aizwys.cn/Article/details/gtwnyeqmix.html

C#:   list.Add(4);
来源：http://dali.ivvv.top/Article/details/gtpvbdwrdi.html

[D03] 在指定位置插入元素
来源：http://dali.nanxinkj.top/Article/details/gtcggwkvci.html

Py:   arr.insert(0, 0)
来源：http://dali.tanke756.top/Article/details/gtopxfcgdp.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.daxiang520.top/Article/details/gtfkimxmes.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.iojbl.cn/Article/details/gtxpurtacl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.sufxvd.cn/Article/details/gttgvlzqos.html

Java: list.add(0, 0);
来源：http://dali.c1oappe.top/Article/details/gtzznqtzwe.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xziqi.cn/Article/details/gtrggijppw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yj20258.top/Article/details/gtmtpufevk.html

C#:   list.Insert(0, 0);
来源：http://dali.jqgufenzy.top/Article/details/gtsfmvblue.html

[D04] 删除元素
来源：http://dali.shzxlz.cn/Article/details/gtfxorwuhv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.dashuyun.cn/Article/details/gtuhpblrzg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ehwqpu.com/Article/details/gthacgcywr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.vqdsnc.cn/Article/details/gtrcjdlwrf.html

TS:   arr.splice(0, 1);
来源：http://dali.andypj.xyz/Article/details/gtliyxncap.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ivvv.top/Article/details/gtdtxbdjbo.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xuanzx.com/Article/details/gtqcpxczjm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuwnvcoov.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xylfe.cn/Article/details/gtpbnmmabq.html

[D05] 访问与修改元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvohivquo.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hysaishi.cn/Article/details/gtjvpatjct.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sufxvd.cn/Article/details/gtzzqnadsx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.dashuyun.cn/Article/details/gttmvflrsw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj20258888.top/Article/details/gtxkrpakup.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ywan-chungtsiang.top/Article/details/gthosjdjfn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.wangdashe.top/Article/details/gtdadesvde.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hfpthk.cn/Article/details/gtwczqpzgt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gtztpmhosy.html

[D06] 数组长度
来源：http://dali.cdnleiting.top/Article/details/gtdxegujsr.html

Py:   len(arr)
来源：http://dali.gogol.net.cn/Article/details/gtjoopmhfn.html

PHP:  count($arr);
来源：http://dali.shzxlz.cn/Article/details/gtemugxyyy.html

JS:   arr.length
来源：http://dali.xuanzx.com/Article/details/gtqlaxukbq.html

TS:   arr.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuqttnsps.html

Java: list.size();
来源：http://dali.vqdsnc.cn/Article/details/gtxvlfoaxb.html

Go:   len(arr)
来源：http://dali.xylfe.cn/Article/details/gtdisvosge.html

Ruby: arr.length; arr.size
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmjbxofvu.html

C#:   list.Count;
来源：http://dali.fengsongda.top/Article/details/gtmkbpxqxv.html

[D07] 切片 / 取子数组
来源：http://dali.zycfv.cn/Article/details/gtjumoocuu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.nwbrower.top/Article/details/gtidcxkbor.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.kuanghao11.cn/Article/details/gtzhiinhfl.html

JS:   arr.slice(1, 4);
来源：http://dali.aibaodan.cn/Article/details/gtivyrouuh.html

TS:   arr.slice(1, 4);
来源：http://dali.quarkkingdee.top/Article/details/gttctjbizj.html

Java: list.subList(1, 4);
来源：http://dali.9152youxi.cn/Article/details/gtlrpswjqi.html

Go:   arr[1:4]
来源：http://dali.ydzc1.top/Article/details/gtsewucezl.html

Ruby: arr[1, 3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsostejrr.html

C#:   list.GetRange(1, 3);
来源：http://dali.gzhubu.top/Article/details/gtddpmkxol.html

[D08] 合并两个数组
来源：http://dali.pengpengdd.cyou/Article/details/gtkakzrpfm.html

Py:   a + b;  a.extend(b)
来源：http://dali.guannengcc.top/Article/details/gtuftzvywz.html

PHP:  array_merge($a, $b);
来源：http://dali.c1oappe.top/Article/details/gtqrltnwdt.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.guannengcc.top/Article/details/gtwrepgcyv.html

TS:   [...a, ...b];
来源：http://dali.cdnleiting.top/Article/details/gtnwjytdlx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhoulong.xyz/Article/details/gtyymqdxoi.html

Go:   append(a, b...)
来源：http://dali.zhiwuduotai.top/Article/details/gttjmkyoqr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.chenlongwang.top/Article/details/gtghybhhnx.html

C#:   a.Concat(b).ToList()
来源：http://dali.zycfv.cn/Article/details/gtaovpyygo.html

[D09] 排序（升序）
来源：http://dali.birdmap.top/Article/details/gtzzxdmjej.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shangyingyoupin.top/Article/details/gtknukatrt.html

PHP:  sort($arr);
来源：http://dali.fengsongda.top/Article/details/gtjmovjsdj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.wangdashe.top/Article/details/gtltrycdzn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zdqjudy.top/Article/details/gtzcymnqhf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.fengsongda.top/Article/details/gtlklsuqmr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtbgcmzpds.html

Ruby: arr.sort
来源：http://dali.feifeiyinyue.top/Article/details/gtrwtuvgkh.html

C#:   list.Sort();
来源：http://dali.daxiang520.top/Article/details/gtbztfpovt.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinqigufen.top/Article/details/gtbujdbeba.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.birdmap.top/Article/details/gtkyngbumh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jqgufenzy.top/Article/details/gtkqrrjbie.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yvedp.cn/Article/details/gtyivrhjpw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwhvqfgoq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xylfe.cn/Article/details/gtuanckoic.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.daria6918.cn/Article/details/gtdxvauynb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jianghu66.top/Article/details/gtbjmldlhu.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yvedp.cn/Article/details/gthvtiwlun.html


<!-- 参考信息 -->