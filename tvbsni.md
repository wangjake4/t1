代发 wailian999

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hysaishi.cn/Article/details/gtpzcpatrf.html

[B10] 遍历同时拿索引
来源：http://dali.guannengcc.top/Article/details/gtyiznulvd.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvbqeumzy.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hnxiangtu.top/Article/details/gtqngprreo.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.sxryk.cn/Article/details/gtqizznpme.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yueranfly.top/Article/details/gtdnefhvbh.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.pycfn.com/Article/details/gtvkhqgngs.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.gaohongyu789.top/Article/details/gtadnlwwzj.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhiwuduotai.top/Article/details/gtkeagtyre.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yueranfly.top/Article/details/gttecovqpv.html

[B11] 生成数字序列 / 区间
来源：http://dali.daxiang520.top/Article/details/gtsmlidwef.html

Py:   list(range(0, 10, 2))
来源：http://dali.birdmap.top/Article/details/gteofrqzbj.html

PHP:  range(0, 10, 2);
来源：http://dali.iojbl.cn/Article/details/gtkaujtcgm.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hfpthk.cn/Article/details/gtidyccwoo.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yonumen.top/Article/details/gtdkoknxpx.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.svipenyu.cn/Article/details/gtqpyzfapo.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.9152youxi.cn/Article/details/gtowyirdfc.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hongshengwenyu.top/Article/details/gtpyrhmvrg.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.gotoacloud.top/Article/details/gtufiqgyiv.html

[B12] 跳出多层循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gthrzbpsax.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.haohaochexian.top/Article/details/gtcpypaiwt.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yuanzhike.top/Article/details/gtabfkbfbs.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangdashe.top/Article/details/gtwjbpyhou.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gzhubu.top/Article/details/gtutnimkwq.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gthvnfqnky.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zdqjudy.top/Article/details/gtmbfifxtu.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.havefunace.top/Article/details/gtpmzrtqxj.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.nanxinkj.top/Article/details/gtikxpahgg.html

[B13] 判断是否为数字
来源：http://dali.zdqjudy.top/Article/details/gtdtlxtysv.html

Py:   isinstance(x, (int, float))
来源：http://dali.jyoumei.cn/Article/details/gtqsqjjbix.html

PHP:  is_numeric($x)
来源：http://dali.wangdashe.top/Article/details/gtoaeivwcn.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hammf.cn/Article/details/gtjquiyscr.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jiagoushi.top/Article/details/gtvcpmgfjy.html

Java: x instanceof Number
来源：http://dali.yongpay.top/Article/details/gtmgbtoonh.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.9152youxi.cn/Article/details/gtvylrzpdx.html

Ruby: x.is_a?(Numeric)
来源：http://dali.nanxuanxn.top/Article/details/gtinywxioq.html

C#:   x is int or double or decimal
来源：http://dali.yj202588.top/Article/details/gtbhifgrbn.html

[B14] 判断值是否在集合内
来源：http://dali.yonumen.top/Article/details/gtkkyiktip.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yvedp.cn/Article/details/gtakvvvkxd.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hongshengwenyu.top/Article/details/gtkbymxsaz.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yanxiufei.cn/Article/details/gtjxputmkt.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.andypj.xyz/Article/details/gtcomilezm.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.meibo888.top/Article/details/gtjsypdfkp.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.meibo888.top/Article/details/gtmymgchpv.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xylfe.cn/Article/details/gtvaoshvqg.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtwmvtvmdh.html

[B15] 布尔运算与取反
来源：http://dali.zycfv.cn/Article/details/gtyyaovoph.html

Py:   a and b or not c
来源：http://dali.aizwys.cn/Article/details/gtrscukxca.html

PHP:  $a && $b || !$c
来源：http://dali.wangdashe.top/Article/details/gtiaukssrf.html

JS:   a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gtdbpymzya.html

TS:   a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gtjzvjuehp.html

Java: a && b || !c
来源：http://dali.pycfn.com/Article/details/gtmiedgual.html

Go:   a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gtdgpnjjfj.html

Ruby: a && b || !c
来源：http://dali.316326.xyz/Article/details/gtsyhdubrx.html

C#:   a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gteuqxeecm.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ehwqpu.com/Article/details/gttkhjxidd.html

Py:   if not data: return
来源：http://dali.wangshuangyany.cn/Article/details/gtyzwzuwqb.html

PHP:  if (!$data) { return; }
来源：http://dali.cheryme.top/Article/details/gtywauwcxg.html

JS:   if (!data) return;
来源：http://dali.pycfn.com/Article/details/gtttzkxter.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gtemankril.html

Java: if (data == null) return;
来源：http://dali.chenjidiqi.icu/Article/details/gtuymmfhdc.html

Go:   if data == nil { return }
来源：http://dali.gaohongyu789.top/Article/details/gthqpujtkz.html

Ruby: return if data.nil?
来源：http://dali.ehwqpu.com/Article/details/gtcdgtejqi.html

C#:   if (data == null) return;
来源：http://dali.cashguo.top/Article/details/gtlguvediw.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtshavpbib.html

C. 函数与作用域
来源：http://dali.xziqi.cn/Article/details/gtrfwueebk.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtmbyuthvv.html

[C01] 定义函数
来源：http://dali.aibaodan.cn/Article/details/gtuevfhrgh.html

Py:   def add(a, b): return a + b
来源：http://dali.chenzaomai.com/Article/details/gtusizdrof.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtdddakkej.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gtcdmxywuz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gtzvjpvdxr.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gteqjlsyaw.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiwfxbtsc.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jinqigufen.top/Article/details/gtqprxcnee.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yj20258.top/Article/details/gtavfejfyc.html

[C02] 默认参数
来源：http://dali.wangdashe.top/Article/details/gtjuctkkad.html

Py:   def greet(name="World"): return name
来源：http://dali.dianchejie.cn/Article/details/gtaxkorqbq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtqlcnpane.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yonumen.top/Article/details/gtgzziailm.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hammf.cn/Article/details/gtfdrpcyjc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xuetiantiany.cn/Article/details/gtrqnrgwrr.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.gaohongyu789.top/Article/details/gtqcfglivc.html

Ruby: def greet(name = "World") = name
来源：http://dali.jinghuilouyu.cn/Article/details/gtpumyvpfk.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gaohongyu789.top/Article/details/gttbezniym.html

[C03] 可变参数
来源：http://dali.zdqjudy.top/Article/details/gtvgaaiamp.html

Py:   def total(*args): return sum(args)
来源：http://dali.haohaochexian.top/Article/details/gtqajxpzms.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.sysykeji.top/Article/details/gtqtwiomkg.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinqigfzy.top/Article/details/gtzpnfigjj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.redwolf501.top/Article/details/gtkvutptfo.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.vqdsnc.cn/Article/details/gtqrtjsqwa.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.shzxlz.cn/Article/details/gtynugbtde.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sweek.top/Article/details/gtgtgueozh.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hammf.cn/Article/details/gtwbnadher.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ehwqpu.com/Article/details/gtbirjmnqx.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.bjfxy.top/Article/details/gthzedlrul.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xylfe.cn/Article/details/gtmnddinng.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.havefunace.top/Article/details/gtlhpxhhnh.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.fengsongda.top/Article/details/gtkmtdokgj.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.dianchejie.cn/Article/details/gtwqmsebqi.html

Go:   // 无：用配置结构体参数
来源：http://dali.tianlin.xyz/Article/details/gtovdjetho.html

Ruby: f(a: 1, b: 2)
来源：http://dali.guannengcc.top/Article/details/gtlwnfswjy.html

C#:   f(a: 1, b: 2)
来源：http://dali.daxiang520.top/Article/details/gtzovaehlh.html

[C05] 返回多个值
来源：http://dali.mhx1999.top/Article/details/gtwnuwcgvl.html

Py:   return a, b
来源：http://dali.sxryk.cn/Article/details/gtbbuiogeq.html

PHP:  return [$a, $b];
来源：http://dali.chenzaomai.com/Article/details/gtyvmamqxw.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jinqigufen.top/Article/details/gtwzaeeahg.html

TS:   return { a, b };
来源：http://dali.dashuyun.cn/Article/details/gtylxdstyq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sysykeji.top/Article/details/gtaxaljjbp.html

Go:   return a, b
来源：http://dali.guannengcc.top/Article/details/gtqeqiyooe.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gtjdcrizmj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cashguo.top/Article/details/gthtdwvsxd.html

[C06] 匿名函数 / lambda
来源：http://dali.meibo888.top/Article/details/gtqerjdbcr.html

Py:   square = lambda x: x * x
来源：http://dali.svipenyu.cn/Article/details/gtgzmbihrw.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.tianlin.xyz/Article/details/gtsvpzfcjy.html

JS:   const square = x => x * x;
来源：http://dali.yj20258888.top/Article/details/gtrpstnsuo.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.bjfxy.top/Article/details/gtwrofzjtd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zycfv.cn/Article/details/gtzskkiocw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ppjwa.cn/Article/details/gtmlapplet.html

Ruby: square = ->(x) { x * x }
来源：http://dali.pengpengdd.cyou/Article/details/gtiubmwgss.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gteudogjqm.html

[C07] 把函数作为参数传入
来源：http://dali.zycfv.cn/Article/details/gtmhyszowk.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.fengsongda.top/Article/details/gtjcnkshyk.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtxbvaecux.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cqqwz.cn/Article/details/gtphmtswcr.html

TS:   arr.map(String)
来源：http://dali.hfpthk.cn/Article/details/gtyrezecto.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdbvivjix.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.0kj1m.cn/Article/details/gtmjiicizo.html

Ruby: arr.map(&:upcase)
来源：http://dali.xuanzx.com/Article/details/gtafmmvier.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cucudq.cn/Article/details/gtgbhzggui.html

[C08] 闭包
来源：http://dali.fengsongda.top/Article/details/gtiufpdxkq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yueranfly.top/Article/details/gtbimmsupb.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.daxiang520.top/Article/details/gtmifcremw.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yangfankeji.com/Article/details/gtuwqodzrv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhengqikj.top/Article/details/gthskzkpse.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.sysykeji.top/Article/details/gtjmjdkuml.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cheryme.top/Article/details/gtzaaqmwsh.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.svipenyu.cn/Article/details/gtuxetrshx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zycfv.cn/Article/details/gtybddwvov.html

[C09] 递归
来源：http://dali.smart0.xyz/Article/details/gtrkbjisxh.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.wangdashe.top/Article/details/gtnfydvims.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.dianchejie.cn/Article/details/gtetyfdbok.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.pycfn.com/Article/details/gtjqynpwsy.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.feifeiyinyue.top/Article/details/gtqfpjmyqv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.vqdsnc.cn/Article/details/gttheevbsb.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yj202588.top/Article/details/gtvggttosl.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.nanxinkj.top/Article/details/gtebpfkpyt.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.aibaodan.cn/Article/details/gtzlsoxabr.html

[C10] 变量作用域
来源：http://dali.wangshuangyany.cn/Article/details/gtzjvoopik.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hfpthk.cn/Article/details/gtbmrlccra.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnlinfwbs.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.chenjidiqi.icu/Article/details/gtbdywltxr.html

TS:   同 JS
来源：http://dali.mhx1999.top/Article/details/gtcqcxnwfn.html

Java: 方法内为块级作用域
来源：http://dali.hywenlv.cn/Article/details/gtvjbfxyjq.html

Go:   花括号块级作用域
来源：http://dali.ybcxt.top/Article/details/gtzqzazcib.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.sysykeji.top/Article/details/gthcypqnyf.html

C#:   块级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfmvvpwlh.html

[C11] 模块导入与导出
来源：http://dali.cheryme.top/Article/details/gtahxliiny.html

Py:   from module import func
来源：http://dali.wangshuangyany.cn/Article/details/gtrbtwhhyr.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hfpthk.cn/Article/details/gtpsrzlnff.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yuxming.cn/Article/details/gtjhpdoick.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hywenlv.cn/Article/details/gtgttkderf.html

Java: import java.util.List;
来源：http://dali.ivvv.top/Article/details/gtejgbunex.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jqgufenzy.top/Article/details/gtihnzoogg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.svipenyu.cn/Article/details/gthcjhogzq.html

C#:   using System.Text;
来源：http://dali.jqgufenzy.top/Article/details/gtiwkyogwj.html

[C12] 立即执行函数 IIFE
来源：http://dali.ybcxt.top/Article/details/gtkrefmatq.html

Py:   (lambda: print("run"))()
来源：http://dali.yanxiufei.cn/Article/details/gtfyzrzfma.html

PHP:  (function () { echo "run"; })();
来源：http://dali.tianlin.xyz/Article/details/gtgndfixwg.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xinyue.icu/Article/details/gtybxumhvc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zdqjudy.top/Article/details/gtavgovdug.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.kuanghao11.cn/Article/details/gthbvhkjqg.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yj20258.top/Article/details/gtmjevmppf.html

Ruby: -> { puts "run" }.call
来源：http://dali.chenlongwang.top/Article/details/gtrwbbdlmg.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.iojbl.cn/Article/details/gtpnzqavif.html

[C13] 类型声明 / 类型注解
来源：http://dali.birdmap.top/Article/details/gthysulane.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.quarkkingdee.top/Article/details/gtbfpfecmh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zycfv.cn/Article/details/gtvwqartot.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gotoacloud.top/Article/details/gticcivbln.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gtnmhjknru.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gtovjdbbtc.html

Go:   func add(a, b int) int
来源：http://dali.tian-w.cn/Article/details/gtmeyglanc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.kuanghao11.cn/Article/details/gtbeyawsgk.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cucudq.cn/Article/details/gtwrumolmz.html

[C14] 泛型函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtobvdabjk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hysaishi.cn/Article/details/gtwqrqoziz.html

PHP:  // 无泛型
来源：http://dali.dianchejie.cn/Article/details/gtyuhewezh.html

JS:   // 无泛型
来源：http://dali.nanxinkj.top/Article/details/gtkhwhhohx.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.fengsongda.top/Article/details/gthczbpuvi.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.tian-w.cn/Article/details/gtqctsvciv.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yuxming.cn/Article/details/gthacveqvo.html

Ruby: # 无泛型
来源：http://dali.zhongyouzk.top/Article/details/gtjcrmalnk.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ivvv.top/Article/details/gtslwsxlgs.html

[C15] 解构 / 展开参数
来源：http://dali.jinqigfzy.top/Article/details/gtqvmjllta.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.guowangkeji.top/Article/details/gtxuounesg.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cheryme.top/Article/details/gtlfqswymq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.9152youxi.cn/Article/details/gtqrmpowmh.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sysykeji.top/Article/details/gtbuqxycfl.html

Java: // 无解构
来源：http://dali.havefunace.top/Article/details/gtmljmjxhb.html

Go:   // 无解构
来源：http://dali.wangdashe.top/Article/details/gtccfmqxqo.html

Ruby: a, b = pair
来源：http://dali.mhx1999.top/Article/details/gtsdxfndhc.html

C#:   var (a, b) = pair;
来源：http://dali.jiagoushi.top/Article/details/gtoadrquet.html

[C16] 函数 / 方法重载
来源：http://dali.xuetiantiany.cn/Article/details/gtduwgrbxh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.tanke756.top/Article/details/gtmdqkgeok.html

PHP:  // 无重载
来源：http://dali.shzxlz.cn/Article/details/gtzuuyeyfj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jianghu66.top/Article/details/gtrflnxjvy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.c1oappe.top/Article/details/gttfwdknpp.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xylfe.cn/Article/details/gtrxlomncq.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhoulong.xyz/Article/details/gtqjuxjxnp.html

Ruby: # 无重载：靠动态参数
来源：http://dali.0kj1m.cn/Article/details/gtwyluljfi.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.tanke756.top/Article/details/gttzfeuate.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtrlhspdfa.html

D. 数组 / 列表 / 集合
来源：http://dali.zdqjudy.top/Article/details/gtovamfsoj.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtazaztsye.html

[D01] 创建数组 / 列表
来源：http://dali.9152youxi.cn/Article/details/gtsabodedy.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhixingplan.top/Article/details/gtsxeoqtaw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.quarkkingdee.top/Article/details/gthkdrzamd.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.svipenyu.cn/Article/details/gtbulybfyn.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.tianlin.xyz/Article/details/gtpooemlbf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shanyushiyangkeji.top/Article/details/gttmaqrohs.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.guannengcc.top/Article/details/gtieizgqcn.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtncsewptu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.aizwys.cn/Article/details/gthhvhtaot.html

[D02] 追加元素到末尾
来源：http://dali.jiagoushi.top/Article/details/gteqmkgmny.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sxryk.cn/Article/details/gtgclgsubt.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.smart0.xyz/Article/details/gtbhxwbjem.html

JS:   arr.push(4);
来源：http://dali.nwbrower.top/Article/details/gtbmxijoky.html

TS:   arr.push(4);
来源：http://dali.guannengcc.top/Article/details/gtxteguklk.html

Java: list.add(4);
来源：http://dali.kuanghao11.cn/Article/details/gttoricjfj.html

Go:   arr = append(arr, 4)
来源：http://dali.hnqzz.top/Article/details/gtprtsbxce.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jqgufenzy.top/Article/details/gtkbgatbhs.html

C#:   list.Add(4);
来源：http://dali.tanke756.top/Article/details/gtkhefgqdf.html

[D03] 在指定位置插入元素
来源：http://dali.zhixingplan.top/Article/details/gtjukjbtia.html

Py:   arr.insert(0, 0)
来源：http://dali.pycfn.com/Article/details/gtmlogjtmh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zdqjudy.top/Article/details/gtxepybxqj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xuetiantiany.cn/Article/details/gtpbwxrwsr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.sweek.top/Article/details/gtqxibheuf.html

Java: list.add(0, 0);
来源：http://dali.pycfn.com/Article/details/gtqzkxjtzm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sweek.top/Article/details/gtttdrgzug.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shangyingyoupin.top/Article/details/gtinrxvmqm.html

C#:   list.Insert(0, 0);
来源：http://dali.wangdashe.top/Article/details/gtdflhmcrj.html

[D04] 删除元素
来源：http://dali.bjfxy.top/Article/details/gttnkfyilt.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtobaiezei.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtykaqomim.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.chenjidiqi.icu/Article/details/gttgvchpkh.html

TS:   arr.splice(0, 1);
来源：http://dali.xylfe.cn/Article/details/gtpornpuyx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.nwbrower.top/Article/details/gtpvlqdbdr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jianghu66.top/Article/details/gticnihslz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.aizwys.cn/Article/details/gtvzuvvlht.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.birdmap.top/Article/details/gtnsipfwtd.html

[D05] 访问与修改元素
来源：http://dali.shanyushiyangtech.top/Article/details/gtsdvfgwhh.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinghuilouyu.cn/Article/details/gtnkvkimel.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ivvv.top/Article/details/gttzuwuqhf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hnqzz.top/Article/details/gtldxwabrp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jianghu66.top/Article/details/gtewyfiygh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhixingplan.top/Article/details/gthofhrmwi.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.0kj1m.cn/Article/details/gtabalkkae.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gogol.net.cn/Article/details/gtfzbkedhs.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.svipenyu.cn/Article/details/gtrdumngil.html

[D06] 数组长度
来源：http://dali.sweek.top/Article/details/gtkmwbtxee.html

Py:   len(arr)
来源：http://dali.sysykeji.top/Article/details/gtqqceulcw.html

PHP:  count($arr);
来源：http://dali.9152youxi.cn/Article/details/gtggembmvw.html

JS:   arr.length
来源：http://dali.gzhubu.top/Article/details/gtjcsvfjyn.html

TS:   arr.length
来源：http://dali.andypj.xyz/Article/details/gttxzkhpae.html

Java: list.size();
来源：http://dali.guowangkeji.top/Article/details/gtorsjooaf.html

Go:   len(arr)
来源：http://dali.iojbl.cn/Article/details/gtwzomossf.html

Ruby: arr.length; arr.size
来源：http://dali.guowangkeji.top/Article/details/gtytqvjnng.html

C#:   list.Count;
来源：http://dali.hammf.cn/Article/details/gtzwubvdph.html

[D07] 切片 / 取子数组
来源：http://dali.hnqzz.top/Article/details/gtkzuvqfdi.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jiagoushi.top/Article/details/gtjaojxbew.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sysykeji.top/Article/details/gtpzmtaeia.html

JS:   arr.slice(1, 4);
来源：http://dali.jiagoushi.top/Article/details/gtdjyidycp.html

TS:   arr.slice(1, 4);
来源：http://dali.yuxming.cn/Article/details/gtsenyfeop.html

Java: list.subList(1, 4);
来源：http://dali.cucudq.cn/Article/details/gtszgimrov.html

Go:   arr[1:4]
来源：http://dali.hfpthk.cn/Article/details/gtzcxgicdu.html

Ruby: arr[1, 3]
来源：http://dali.yonumen.top/Article/details/gtvgeqjixx.html

C#:   list.GetRange(1, 3);
来源：http://dali.yj202588.top/Article/details/gtnltikpoe.html

[D08] 合并两个数组
来源：http://dali.tian-w.cn/Article/details/gtdtggykbq.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhiwuduotai.top/Article/details/gtbsomtbzl.html

PHP:  array_merge($a, $b);
来源：http://dali.yj20258.top/Article/details/gtfryezldn.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.smart0.xyz/Article/details/gtuyhjmoit.html

TS:   [...a, ...b];
来源：http://dali.aibaodan.cn/Article/details/gtbtixdadt.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.0kj1m.cn/Article/details/gthzxphrnc.html

Go:   append(a, b...)
来源：http://dali.0kj1m.cn/Article/details/gtxslwrdwe.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xylfe.cn/Article/details/gtexruhlpr.html

C#:   a.Concat(b).ToList()
来源：http://dali.sxryk.cn/Article/details/gtbrlombqi.html

[D09] 排序（升序）
来源：http://dali.gogol.net.cn/Article/details/gtasoobzga.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.c1oappe.top/Article/details/gtahyaitce.html

PHP:  sort($arr);
来源：http://dali.xziqi.cn/Article/details/gtfaqvaava.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xylfe.cn/Article/details/gttwxipill.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtszkhdcim.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yonumen.top/Article/details/gtomojztwh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yj20258.top/Article/details/gtqkqpstqv.html

Ruby: arr.sort
来源：http://dali.tanke756.top/Article/details/gtlxbgejhd.html

C#:   list.Sort();
来源：http://dali.xylfe.cn/Article/details/gtuqwrmgtv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.pycfn.com/Article/details/gtvdeoqivd.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yj20258888.top/Article/details/gtxwmyixoa.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zycfv.cn/Article/details/gtyjxqdyqy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aizwys.cn/Article/details/gtfkhekspe.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ppjwa.cn/Article/details/gteeukkbmj.html


<!-- 参考信息 -->