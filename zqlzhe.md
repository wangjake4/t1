代发 wailian999

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmejhtlfa.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jyoumei.cn/Article/details/gtpkwegltx.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.dianchejie.cn/Article/details/gthsgtfjzp.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.havefunace.top/Article/details/gtvitorggl.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.cqqwz.cn/Article/details/gtalyzeise.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdbjauwyb.html

[B11] 生成数字序列 / 区间
来源：http://dali.birdmap.top/Article/details/gtgucifxxo.html

Py:   list(range(0, 10, 2))
来源：http://dali.hammf.cn/Article/details/gthxxvqojm.html

PHP:  range(0, 10, 2);
来源：http://dali.hywenlv.cn/Article/details/gtqjqwdmrh.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.daria6918.cn/Article/details/gtxxqoxegy.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtzaropccy.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.gogol.net.cn/Article/details/gtsttmlqtb.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.gaohongyu789.top/Article/details/gtyiqkmjtx.html

Ruby: (0...10).step(2).to_a
来源：http://dali.kuanghao11.cn/Article/details/gtjijzhhya.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.kuanghao11.cn/Article/details/gtxocijiyg.html

[B12] 跳出多层循环
来源：http://dali.hysaishi.cn/Article/details/gtnrbnqnnz.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jqgfzy.top/Article/details/gttnlzvhcr.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hfpthk.cn/Article/details/gtzshgawpl.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.0kj1m.cn/Article/details/gtchbnvwtv.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sweek.top/Article/details/gtlzovrdpd.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yongpay.top/Article/details/gtxhntqdlm.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ydzc1.top/Article/details/gtkjdwmhxg.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnwxpgubp.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.mhx1999.top/Article/details/gtpewxtutp.html

[B13] 判断是否为数字
来源：http://dali.jqgufenzy.top/Article/details/gtsyhrfpqu.html

Py:   isinstance(x, (int, float))
来源：http://dali.hongshengwenyu.top/Article/details/gtrtherqta.html

PHP:  is_numeric($x)
来源：http://dali.316326.xyz/Article/details/gtwwvmqjxn.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtwzewxvhy.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.dashuyun.cn/Article/details/gthmpjqbby.html

Java: x instanceof Number
来源：http://dali.hongshengwenyu.top/Article/details/gtsgqffcct.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jyoumei.cn/Article/details/gtdrdlorbv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jyoumei.cn/Article/details/gtcrgaoitx.html

C#:   x is int or double or decimal
来源：http://dali.c1oappe.top/Article/details/gtfpbnuxgg.html

[B14] 判断值是否在集合内
来源：http://dali.zycfv.cn/Article/details/gtpwuexcaf.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.aizwys.cn/Article/details/gtrrqydjef.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.redwolf501.top/Article/details/gtwtfvewqa.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gthlidtgqi.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ivvv.top/Article/details/gtuapeepxg.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yanxiufei.cn/Article/details/gtannsekny.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.cashguo.top/Article/details/gtbyzfizhz.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.chenlongwang.top/Article/details/gtfeytqawy.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jiagoushi.top/Article/details/gtivnwwcjy.html

[B15] 布尔运算与取反
来源：http://dali.xuanzx.com/Article/details/gtdbeyaire.html

Py:   a and b or not c
来源：http://dali.cucudq.cn/Article/details/gtoqsqxhzc.html

PHP:  $a && $b || !$c
来源：http://dali.c1oappe.top/Article/details/gtbbaliwcn.html

JS:   a && b || !c
来源：http://dali.yj202588.top/Article/details/gtijpdyqyf.html

TS:   a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gtfcghvhfd.html

Java: a && b || !c
来源：http://dali.fengsongda.top/Article/details/gtfcupthug.html

Go:   a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gtewsxmyyf.html

Ruby: a && b || !c
来源：http://dali.havefunace.top/Article/details/gttxrpichi.html

C#:   a && b || !c
来源：http://dali.daxiang520.top/Article/details/gtfbggrndu.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yj20258888.top/Article/details/gtuuqnuvbn.html

Py:   if not data: return
来源：http://dali.0kj1m.cn/Article/details/gtufaftiau.html

PHP:  if (!$data) { return; }
来源：http://dali.nwbrower.top/Article/details/gtunlfncrn.html

JS:   if (!data) return;
来源：http://dali.cucudq.cn/Article/details/gtiswgkyoj.html

TS:   if (!data) return;
来源：http://dali.chenjidiqi.icu/Article/details/gtasmuohks.html

Java: if (data == null) return;
来源：http://dali.kuanghao11.cn/Article/details/gtqszycccy.html

Go:   if data == nil { return }
来源：http://dali.svipenyu.cn/Article/details/gtlwfeynai.html

Ruby: return if data.nil?
来源：http://dali.hywenlv.cn/Article/details/gtvlqpjzwm.html

C#:   if (data == null) return;
来源：http://dali.feifeiyinyue.top/Article/details/gtrqnodtfg.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtnnwlsbcg.html

C. 函数与作用域
来源：http://dali.nanxuanxn.top/Article/details/gtmyeqirgq.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gticrmnkel.html

[C01] 定义函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmjgycvbz.html

Py:   def add(a, b): return a + b
来源：http://dali.yangfankeji.com/Article/details/gtnxesxfyj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hysaishi.cn/Article/details/gtktlcsgir.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gtzkzukzag.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gtfzanfchy.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gtvaoofcci.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.shangyingyoupin.top/Article/details/gttzdhrxjk.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yangfankeji.com/Article/details/gtfxiytwcy.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gtxxamsqrp.html

[C02] 默认参数
来源：http://dali.hammf.cn/Article/details/gtpuzptmue.html

Py:   def greet(name="World"): return name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtftiwaobz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtqnioclqc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ybcxt.top/Article/details/gttstvjmop.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jianghu66.top/Article/details/gtmtchmjeh.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.chenlongwang.top/Article/details/gtoxdtqyzn.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jyoumei.cn/Article/details/gtmfywkzkv.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzdtrnkfv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.chenzaomai.com/Article/details/gtyarmpoaz.html

[C03] 可变参数
来源：http://dali.ehwqpu.com/Article/details/gtlgrinagl.html

Py:   def total(*args): return sum(args)
来源：http://dali.xinyue.icu/Article/details/gthxsbisfo.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.c1oappe.top/Article/details/gtesfrchww.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.bjfxy.top/Article/details/gtcjtwzdzy.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tanke756.top/Article/details/gtebvvcjrt.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.fzhhl.top/Article/details/gtudrholbt.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jianghu66.top/Article/details/gtffqwqlpw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.redwolf501.top/Article/details/gtbputavkw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.aibaodan.cn/Article/details/gtygjdmzif.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jiagoushi.top/Article/details/gtsaxzavtq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.0kj1m.cn/Article/details/gtslldjbtz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shzxlz.cn/Article/details/gtbtfxgpin.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.sufxvd.cn/Article/details/gtqhkrjnyz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xinyue.icu/Article/details/gthyxwmrid.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.svipenyu.cn/Article/details/gtsgxpppqv.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhoulong.xyz/Article/details/gtolkbhmxc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdjeuxawx.html

C#:   f(a: 1, b: 2)
来源：http://dali.mhx1999.top/Article/details/gtqrovcysa.html

[C05] 返回多个值
来源：http://dali.ivvv.top/Article/details/gtlkwjmkej.html

Py:   return a, b
来源：http://dali.sysykeji.top/Article/details/gtjvrlukke.html

PHP:  return [$a, $b];
来源：http://dali.zhengqikj.top/Article/details/gtpwgfbqyj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xinyue.icu/Article/details/gtxwulhigr.html

TS:   return { a, b };
来源：http://dali.mhx1999.top/Article/details/gtpmywrtcv.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xylfe.cn/Article/details/gtzpvaezsp.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gtlupbpfce.html

Ruby: return a, b
来源：http://dali.andypj.xyz/Article/details/gtlduekiky.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cdnleiting.top/Article/details/gtihsqgkbu.html

[C06] 匿名函数 / lambda
来源：http://dali.nwbrower.top/Article/details/gtnhyghybl.html

Py:   square = lambda x: x * x
来源：http://dali.sufxvd.cn/Article/details/gthtkynmqa.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.shanyushiyangtech.top/Article/details/gtouvwmltu.html

JS:   const square = x => x * x;
来源：http://dali.zhiwuduotai.top/Article/details/gthbxtyaow.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yj202588.top/Article/details/gtazzggpom.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yvedp.cn/Article/details/gteldvssyt.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.quarkkingdee.top/Article/details/gtdxxduskf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.redwolf501.top/Article/details/gtavnjgncu.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.guowangkeji.top/Article/details/gtyqimzhio.html

[C07] 把函数作为参数传入
来源：http://dali.ehwqpu.com/Article/details/gtfebumjil.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cdnleiting.top/Article/details/gtseytpfnu.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yuxming.cn/Article/details/gtuecwfcqi.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxvcxjbiv.html

TS:   arr.map(String)
来源：http://dali.hfpthk.cn/Article/details/gtqxbharoz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ehwqpu.com/Article/details/gthhvdqanu.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.chenlongwang.top/Article/details/gtirfmjisg.html

Ruby: arr.map(&:upcase)
来源：http://dali.yueranfly.top/Article/details/gtrtfzqgcm.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.316326.xyz/Article/details/gtzerfdbis.html

[C08] 闭包
来源：http://dali.ydzc1.top/Article/details/gtegiapxju.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yonumen.top/Article/details/gtpssamimi.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.haohaochexian.top/Article/details/gtimeqwpzw.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.svipenyu.cn/Article/details/gtxgnupfkg.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.chenzaomai.com/Article/details/gtwoadfrgx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.redwolf501.top/Article/details/gtiexqttcz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.tian-w.cn/Article/details/gtsbgqpwmt.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yonumen.top/Article/details/gtmlpvxctl.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhixingplan.top/Article/details/gtxphdkqtq.html

[C09] 递归
来源：http://dali.hnqzz.top/Article/details/gtuymndpfm.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtliohaygk.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hongshengwenyu.top/Article/details/gtojqnvjvu.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xylfe.cn/Article/details/gtfbzjzyjv.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nanxinkj.top/Article/details/gtaymrkxgk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfrgavyof.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sxryk.cn/Article/details/gtyuiohtln.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yuanzhike.top/Article/details/gtekywkfeu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xuanzx.com/Article/details/gtcgacetkh.html

[C10] 变量作用域
来源：http://dali.havefunace.top/Article/details/gtckputing.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhengqikj.top/Article/details/gtfylfhymy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xuetiantiany.cn/Article/details/gtwlmtmjqh.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtegsujmpm.html

TS:   同 JS
来源：http://dali.ivvv.top/Article/details/gtgxznamcd.html

Java: 方法内为块级作用域
来源：http://dali.ydzc1.top/Article/details/gtotojlazg.html

Go:   花括号块级作用域
来源：http://dali.aibaodan.cn/Article/details/gthvqijwnu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhoulong.xyz/Article/details/gtavbpjzxw.html

C#:   块级作用域
来源：http://dali.zhengqikj.top/Article/details/gtkcawzeyf.html

[C11] 模块导入与导出
来源：http://dali.hfpthk.cn/Article/details/gtnuyvcaiu.html

Py:   from module import func
来源：http://dali.wangshuangyany.cn/Article/details/gtxvwbmlyq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.sufxvd.cn/Article/details/gtdzlyylgk.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yj202588.top/Article/details/gtjrxopmzc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtljrtdgao.html

Java: import java.util.List;
来源：http://dali.shuidangran.top/Article/details/gtmoulshho.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.fzhhl.top/Article/details/gtjfplgrjk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.birdmap.top/Article/details/gteiosavto.html

C#:   using System.Text;
来源：http://dali.cqqwz.cn/Article/details/gttqfgdtfm.html

[C12] 立即执行函数 IIFE
来源：http://dali.fzhhl.top/Article/details/gtyckosrhf.html

Py:   (lambda: print("run"))()
来源：http://dali.zycfv.cn/Article/details/gtyxwfnxsb.html

PHP:  (function () { echo "run"; })();
来源：http://dali.fengsongda.top/Article/details/gtfivtvggq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yongpay.top/Article/details/gtkdalpwyj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gtlfjltueq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yanxiufei.cn/Article/details/gtbfqpwfhw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhixingplan.top/Article/details/gtnvzrfzmw.html

Ruby: -> { puts "run" }.call
来源：http://dali.jinghuilouyu.cn/Article/details/gtdkrwvbok.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jianghu66.top/Article/details/gtupgtlrxr.html

[C13] 类型声明 / 类型注解
来源：http://dali.hfpthk.cn/Article/details/gtfuutptpl.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hammf.cn/Article/details/gthvybijle.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gogol.net.cn/Article/details/gtxpnnhpug.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xinyue.icu/Article/details/gtjhftrhyj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gtsupcpzgn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gtjgwyzlcp.html

Go:   func add(a, b int) int
来源：http://dali.meibo888.top/Article/details/gtvcmoazxc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xylfe.cn/Article/details/gtioosbexp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.daria6918.cn/Article/details/gtfemrslse.html

[C14] 泛型函数
来源：http://dali.zhixingplan.top/Article/details/gtgclcmzrr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinghuilouyu.cn/Article/details/gtkzjrimig.html

PHP:  // 无泛型
来源：http://dali.xuanzx.com/Article/details/gtlxolbspb.html

JS:   // 无泛型
来源：http://dali.zhixingplan.top/Article/details/gtggppgykx.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.pycfn.com/Article/details/gtuvgzpgiw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzabovucs.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.chenjidiqi.icu/Article/details/gtzwjybeln.html

Ruby: # 无泛型
来源：http://dali.sufxvd.cn/Article/details/gtycjsvocb.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jianghu66.top/Article/details/gtlnghwgrt.html

[C15] 解构 / 展开参数
来源：http://dali.hysaishi.cn/Article/details/gtolpgarlz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xuetiantiany.cn/Article/details/gtwcdkscwm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yj202588.top/Article/details/gtxkuoxrhl.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.chenlongwang.top/Article/details/gtiwkqpith.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.svipenyu.cn/Article/details/gtyphkoook.html

Java: // 无解构
来源：http://dali.jinqigufen.top/Article/details/gtxslluwml.html

Go:   // 无解构
来源：http://dali.hywenlv.cn/Article/details/gtfovpyiod.html

Ruby: a, b = pair
来源：http://dali.xuanzx.com/Article/details/gtrzoxjree.html

C#:   var (a, b) = pair;
来源：http://dali.jqgfzy.top/Article/details/gtymlayrul.html

[C16] 函数 / 方法重载
来源：http://dali.nanxinkj.top/Article/details/gtebeevmni.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xziqi.cn/Article/details/gtyxihalku.html

PHP:  // 无重载
来源：http://dali.hywenlv.cn/Article/details/gtevvmkbtt.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.nwbrower.top/Article/details/gtfqfwxfgn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoiztgspm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtcyofyyju.html

Go:   // 无重载：用不同函数名
来源：http://dali.guannengcc.top/Article/details/gtfnynyqyp.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sweek.top/Article/details/gtfkcaewte.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.fengsongda.top/Article/details/gttkruxzfk.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtfjiyyhqq.html

D. 数组 / 列表 / 集合
来源：http://dali.shangyingyoupin.top/Article/details/gtaecwhcmb.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtvbjntdze.html

[D01] 创建数组 / 列表
来源：http://dali.wangdashe.top/Article/details/gtarpmlnjh.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtltrqjxfc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.kuanghao11.cn/Article/details/gtaklokaox.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ppjwa.cn/Article/details/gtjpmxgmwb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.snrcjt.cn/Article/details/gtrynpnybl.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yvedp.cn/Article/details/gtbldxwwqq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.wangshuangyany.cn/Article/details/gthueoffyx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.nanxuanxn.top/Article/details/gtvkaeavak.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zycfv.cn/Article/details/gtqwoocsti.html

[D02] 追加元素到末尾
来源：http://dali.svipenyu.cn/Article/details/gtxluhvifp.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.aibaodan.cn/Article/details/gtaweyjghe.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hammf.cn/Article/details/gtjzilapan.html

JS:   arr.push(4);
来源：http://dali.fengsongda.top/Article/details/gtlbwxmjyq.html

TS:   arr.push(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtpdtijzre.html

Java: list.add(4);
来源：http://dali.redwolf501.top/Article/details/gtpukxyybp.html

Go:   arr = append(arr, 4)
来源：http://dali.svipenyu.cn/Article/details/gttcgjryiq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yj202588.top/Article/details/gtzbzxgkme.html

C#:   list.Add(4);
来源：http://dali.hfpthk.cn/Article/details/gtthzgrdey.html

[D03] 在指定位置插入元素
来源：http://dali.wangshuangyany.cn/Article/details/gtlwxuwmzt.html

Py:   arr.insert(0, 0)
来源：http://dali.sweek.top/Article/details/gtbnmibtsi.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.chenzaomai.com/Article/details/gtvsajpslw.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jiagoushi.top/Article/details/gtikodixjb.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.chenzaomai.com/Article/details/gtnpuxmyrt.html

Java: list.add(0, 0);
来源：http://dali.jqgfzy.top/Article/details/gtktgncqhu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.bjfxy.top/Article/details/gtuntzrgoy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jiagoushi.top/Article/details/gtfvfuxuni.html

C#:   list.Insert(0, 0);
来源：http://dali.sweek.top/Article/details/gtutfytnpj.html

[D04] 删除元素
来源：http://dali.jianghu66.top/Article/details/gtqbkdtrly.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.svipenyu.cn/Article/details/gtwiiqhxsf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtxxonauqb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.redwolf501.top/Article/details/gtwxjgfgsz.html

TS:   arr.splice(0, 1);
来源：http://dali.meibo888.top/Article/details/gtlwnrnttz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yanxiufei.cn/Article/details/gtdpraruiy.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.aibaodan.cn/Article/details/gtpgsfhukx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yanxiufei.cn/Article/details/gtbifdiatr.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xylfe.cn/Article/details/gtsvwajgbe.html

[D05] 访问与修改元素
来源：http://dali.feifeiyinyue.top/Article/details/gtnxohaosg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.redwolf501.top/Article/details/gtxwkbqbvg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.aizwys.cn/Article/details/gtqkrbryyp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zycfv.cn/Article/details/gtoxwgefiu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sxryk.cn/Article/details/gtzlqdpzde.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.haohaochexian.top/Article/details/gtrbhtrewf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jqgufenzy.top/Article/details/gtjaixawtt.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sxryk.cn/Article/details/gtsztejhdt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdhecoczy.html

[D06] 数组长度
来源：http://dali.yongpay.top/Article/details/gtlniyeeqv.html

Py:   len(arr)
来源：http://dali.tanke756.top/Article/details/gtgwqvrril.html

PHP:  count($arr);
来源：http://dali.yuxming.cn/Article/details/gtjriqcgot.html

JS:   arr.length
来源：http://dali.daria6918.cn/Article/details/gtjterrzvk.html

TS:   arr.length
来源：http://dali.hfpthk.cn/Article/details/gtffqegrco.html

Java: list.size();
来源：http://dali.cheryme.top/Article/details/gtqqwfnqml.html

Go:   len(arr)
来源：http://dali.hysaishi.cn/Article/details/gtndunfvpm.html

Ruby: arr.length; arr.size
来源：http://dali.0kj1m.cn/Article/details/gtbjkgyzey.html

C#:   list.Count;
来源：http://dali.daxiang520.top/Article/details/gtqowrbdlp.html

[D07] 切片 / 取子数组
来源：http://dali.gotoacloud.top/Article/details/gtxydnalbz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.gogol.net.cn/Article/details/gttilcoqqs.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.gaohongyu789.top/Article/details/gtxzdqgqez.html

JS:   arr.slice(1, 4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlhhugpwa.html

TS:   arr.slice(1, 4);
来源：http://dali.xuanzx.com/Article/details/gtmzwnbwtv.html

Java: list.subList(1, 4);
来源：http://dali.xuanzx.com/Article/details/gtoygzjids.html

Go:   arr[1:4]
来源：http://dali.jiagoushi.top/Article/details/gtlxdginyh.html

Ruby: arr[1, 3]
来源：http://dali.hongshengwenyu.top/Article/details/gtumnotcsq.html

C#:   list.GetRange(1, 3);
来源：http://dali.yangfankeji.com/Article/details/gtphmvjzyw.html

[D08] 合并两个数组
来源：http://dali.ybcxt.top/Article/details/gthskpyzcl.html

Py:   a + b;  a.extend(b)
来源：http://dali.yuxming.cn/Article/details/gticezvupq.html

PHP:  array_merge($a, $b);
来源：http://dali.hammf.cn/Article/details/gtnduxdjjm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cashguo.top/Article/details/gtwydylpmp.html

TS:   [...a, ...b];
来源：http://dali.zdqjudy.top/Article/details/gtihnwkbbt.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmpbziycx.html

Go:   append(a, b...)
来源：http://dali.zhengqikj.top/Article/details/gtucdywfdw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shangyingyoupin.top/Article/details/gtozykqihv.html

C#:   a.Concat(b).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtchiqmuxu.html

[D09] 排序（升序）
来源：http://dali.yj20258.top/Article/details/gtzmdntgcy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigufen.top/Article/details/gtaagrwtub.html

PHP:  sort($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtmwieiusy.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hysaishi.cn/Article/details/gtfseaalui.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.nanxuanxn.top/Article/details/gtumvhmndv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sweek.top/Article/details/gttqljfdjw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtroypigst.html

Ruby: arr.sort
来源：http://dali.gaohongyu789.top/Article/details/gtbiifljgs.html

C#:   list.Sort();
来源：http://dali.ehwqpu.com/Article/details/gtxylvopuq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shanyushiyangtech.top/Article/details/gtjczpsvmu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yj20258888.top/Article/details/gtieiqpwws.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sysykeji.top/Article/details/gtcgvhjvox.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shuidangran.top/Article/details/gtgycquyhh.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cqqwz.cn/Article/details/gthogstvza.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.meibo888.top/Article/details/gtoretnfig.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhixingplan.top/Article/details/gtwgabkzzo.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhiwuduotai.top/Article/details/gtcxkdkkzi.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.chenjidiqi.icu/Article/details/gtblejskgv.html


<!-- 参考信息 -->