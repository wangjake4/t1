代发 wailian999

[B09] break 与 continue
来源：http://dali.nwbrower.top/Article/details/gtvewbdarf.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.guowangkeji.top/Article/details/gtlmuitfgi.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jqgfzy.top/Article/details/gtkdmfyulr.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cqqwz.cn/Article/details/gtigjtpbhh.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbsghljox.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigfzy.top/Article/details/gtjixyibol.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.hnxiangtu.top/Article/details/gtwisfkseq.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhengqikj.top/Article/details/gtewwxeldy.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ppjwa.cn/Article/details/gtdgrjkpcy.html

[B10] 遍历同时拿索引
来源：http://dali.c1oappe.top/Article/details/gtrqaqjhyo.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yuxming.cn/Article/details/gterbjxjeb.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsmhdduve.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.meibo888.top/Article/details/gtxihxdtsc.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmuilcxaz.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yueranfly.top/Article/details/gtrkwmbdfe.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhongyouzk.top/Article/details/gtrgfrlpbm.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.nwbrower.top/Article/details/gtewggjnpn.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.pycfn.com/Article/details/gtsdrobrrh.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhengqikj.top/Article/details/gtnonrsakw.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhixingplan.top/Article/details/gtgrmznptm.html

PHP:  range(0, 10, 2);
来源：http://dali.nanxinkj.top/Article/details/gtlmdjbkzs.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yongpay.top/Article/details/gtyikcpmhh.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yangfankeji.com/Article/details/gtcxeoaocl.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.c1oappe.top/Article/details/gtzwoxrvra.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jlsjyb.cn/Article/details/gtzmvbszpu.html

Ruby: (0...10).step(2).to_a
来源：http://dali.gotoacloud.top/Article/details/gtoorpaweu.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.svipenyu.cn/Article/details/gtyqesexdg.html

[B12] 跳出多层循环
来源：http://dali.hammf.cn/Article/details/gtbxqzwpbv.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.nwbrower.top/Article/details/gtddtojolq.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ppjwa.cn/Article/details/gtkzivusjk.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258888.top/Article/details/gtiuhxycvy.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yvedp.cn/Article/details/gtbuzjfjcg.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.tanke756.top/Article/details/gttheuomoy.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.meibo888.top/Article/details/gteozkcpnx.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhengqikj.top/Article/details/gttcuveyuk.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.nanxinkj.top/Article/details/gtkrununiz.html

[B13] 判断是否为数字
来源：http://dali.aibaodan.cn/Article/details/gtdnrvbqzo.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gtfdqtepbj.html

PHP:  is_numeric($x)
来源：http://dali.zhoulong.xyz/Article/details/gtxydljigh.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.redwolf501.top/Article/details/gtinyozqyi.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinqigfzy.top/Article/details/gtncznirrm.html

Java: x instanceof Number
来源：http://dali.0kj1m.cn/Article/details/gtfuowdhts.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.quarkkingdee.top/Article/details/gtulgaatjv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jianghu66.top/Article/details/gtodbntmnn.html

C#:   x is int or double or decimal
来源：http://dali.gaohongyu789.top/Article/details/gtrcodwrbs.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gtgjjgzxfc.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.tian-w.cn/Article/details/gtqyozvkiw.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jianghu66.top/Article/details/gtlrwngtdm.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhixingplan.top/Article/details/gtftzibxtt.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.xinyue.icu/Article/details/gtpetziqqu.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtafbyewas.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.cucudq.cn/Article/details/gtrrnalxki.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.meibo888.top/Article/details/gtqotqtthi.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ivvv.top/Article/details/gtzyxrcnji.html

[B15] 布尔运算与取反
来源：http://dali.kuanghao11.cn/Article/details/gtlxqhsdqc.html

Py:   a and b or not c
来源：http://dali.aibaodan.cn/Article/details/gtqcldksdx.html

PHP:  $a && $b || !$c
来源：http://dali.meibo888.top/Article/details/gtfdumglum.html

JS:   a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gtgikiymtf.html

TS:   a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gtwlskynwi.html

Java: a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gtbesqsfgk.html

Go:   a && b || !c
来源：http://dali.yvedp.cn/Article/details/gtighekzzk.html

Ruby: a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gtpowhwsmr.html

C#:   a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gtijlvyjzh.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.gzhubu.top/Article/details/gtbcibfiev.html

Py:   if not data: return
来源：http://dali.pengpengdd.cyou/Article/details/gtmrmbovtu.html

PHP:  if (!$data) { return; }
来源：http://dali.shuidangran.top/Article/details/gtqxaruvki.html

JS:   if (!data) return;
来源：http://dali.wangdashe.top/Article/details/gtbccfuqny.html

TS:   if (!data) return;
来源：http://dali.ybcxt.top/Article/details/gtfqixdewj.html

Java: if (data == null) return;
来源：http://dali.chenzaomai.com/Article/details/gticyicgob.html

Go:   if data == nil { return }
来源：http://dali.andypj.xyz/Article/details/gtvynspufv.html

Ruby: return if data.nil?
来源：http://dali.hongshengwenyu.top/Article/details/gtpwizbzmo.html

C#:   if (data == null) return;
来源：http://dali.zhiwuduotai.top/Article/details/gtcnpltfun.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtydbnctvj.html

C. 函数与作用域
来源：http://dali.redwolf501.top/Article/details/gtgpyoranb.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtcndqhkrx.html

[C01] 定义函数
来源：http://dali.hnxiangtu.top/Article/details/gtheslzfrn.html

Py:   def add(a, b): return a + b
来源：http://dali.cdnleiting.top/Article/details/gtqgiultud.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtkxmtmznq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gtgvbipcma.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtvocwcpzz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gtlizkhgep.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.pycfn.com/Article/details/gtdjdocxuj.html

Ruby: def add(a, b); a + b; end
来源：http://dali.nanxuanxn.top/Article/details/gtdxozdgue.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtxpqqekkq.html

[C02] 默认参数
来源：http://dali.zhoulong.xyz/Article/details/gtplcngdnh.html

Py:   def greet(name="World"): return name
来源：http://dali.haohaochexian.top/Article/details/gtjyehcxrh.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwbbqcvyh.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cucudq.cn/Article/details/gtadrfvmrq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ydzc1.top/Article/details/gthrssdpsh.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.nanxinkj.top/Article/details/gtjfquwzyh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.guannengcc.top/Article/details/gtdfkkiptw.html

Ruby: def greet(name = "World") = name
来源：http://dali.hfpthk.cn/Article/details/gtzrhbmsvn.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xuetiantiany.cn/Article/details/gtjyuvmlsd.html

[C03] 可变参数
来源：http://dali.hammf.cn/Article/details/gttltdcczo.html

Py:   def total(*args): return sum(args)
来源：http://dali.chenlongwang.top/Article/details/gtqoyvcebo.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xuetiantiany.cn/Article/details/gttplefotf.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenlongwang.top/Article/details/gttgtaeghb.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoaxpqaug.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yuanzhike.top/Article/details/gttzddjcut.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xziqi.cn/Article/details/gtlcwnwkek.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jqgfzy.top/Article/details/gtenrubtvq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yvedp.cn/Article/details/gtyvqbubun.html

[C04] 命名参数 / 关键字参数
来源：http://dali.wangdashe.top/Article/details/gtgwnokaxm.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.nwbrower.top/Article/details/gtrfxtqeoq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xziqi.cn/Article/details/gtldfzapxe.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yanxiufei.cn/Article/details/gtivxlwxix.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hongshengwenyu.top/Article/details/gtfnpdjlpk.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.andypj.xyz/Article/details/gtgvazmkjo.html

Go:   // 无：用配置结构体参数
来源：http://dali.nwbrower.top/Article/details/gtdtlqcfyk.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zycfv.cn/Article/details/gtyinsvhzx.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhoulong.xyz/Article/details/gtdnrhninp.html

[C05] 返回多个值
来源：http://dali.zycfv.cn/Article/details/gtwaeldmjc.html

Py:   return a, b
来源：http://dali.sxryk.cn/Article/details/gtruoptcxy.html

PHP:  return [$a, $b];
来源：http://dali.zycfv.cn/Article/details/gtykatioch.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.feifeiyinyue.top/Article/details/gtwpehaxio.html

TS:   return { a, b };
来源：http://dali.cqqwz.cn/Article/details/gtunjwqtud.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ydzc1.top/Article/details/gtowkiztmi.html

Go:   return a, b
来源：http://dali.jinyuanbaomall.cn/Article/details/gthhrmzzps.html

Ruby: return a, b
来源：http://dali.ehwqpu.com/Article/details/gtxbrlcjda.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.tianlin.xyz/Article/details/gtnfwnfgkl.html

[C06] 匿名函数 / lambda
来源：http://dali.gogol.net.cn/Article/details/gtuvdgsqza.html

Py:   square = lambda x: x * x
来源：http://dali.yongpay.top/Article/details/gtxdkxaaqf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gaohongyu789.top/Article/details/gtgmokcwma.html

JS:   const square = x => x * x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyxiswwzt.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xylfe.cn/Article/details/gtplgpgeyw.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ydzc1.top/Article/details/gtjopjoeil.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.daxiang520.top/Article/details/gtdtikrqva.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yj20258.top/Article/details/gttgqevyxv.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhiwuduotai.top/Article/details/gtjpshzpjy.html

[C07] 把函数作为参数传入
来源：http://dali.nanxuanxn.top/Article/details/gtuwxobdvv.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.quarkkingdee.top/Article/details/gtstpnixyc.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.tian-w.cn/Article/details/gtvhxyirxj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cdnleiting.top/Article/details/gtnznlnfin.html

TS:   arr.map(String)
来源：http://dali.andypj.xyz/Article/details/gtzvuxvhrf.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtknkohhue.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jiagoushi.top/Article/details/gtzkxbjvbz.html

Ruby: arr.map(&:upcase)
来源：http://dali.sufxvd.cn/Article/details/gtmlsveeox.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.nwbrower.top/Article/details/gtiqxqmgrh.html

[C08] 闭包
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxkluqxau.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.quarkkingdee.top/Article/details/gtizlqvtip.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zycfv.cn/Article/details/gtfetuiaup.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.havefunace.top/Article/details/gtaefzuama.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cashguo.top/Article/details/gtgxovppzb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.sweek.top/Article/details/gtxaflpilt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.guowangkeji.top/Article/details/gtgfaibrgh.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtloxiozzh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.mhx1999.top/Article/details/gtgiirnvoe.html

[C09] 递归
来源：http://dali.nwbrower.top/Article/details/gtfwwiacop.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.andypj.xyz/Article/details/gtqggryuqi.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gaohongyu789.top/Article/details/gthuvlvdti.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.andypj.xyz/Article/details/gterhqlapf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.dashuyun.cn/Article/details/gtdphausor.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.chenzaomai.com/Article/details/gtoiefiujo.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.aizwys.cn/Article/details/gtmksnddty.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.chenzaomai.com/Article/details/gtdqhyhtlk.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.fengsongda.top/Article/details/gtooabnipu.html

[C10] 变量作用域
来源：http://dali.xuanzx.com/Article/details/gtsuvkruic.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.chenlongwang.top/Article/details/gttkhshtkq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yueranfly.top/Article/details/gtgxqnsgay.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yangfankeji.com/Article/details/gtrhehombt.html

TS:   同 JS
来源：http://dali.hammf.cn/Article/details/gtuzeprtxw.html

Java: 方法内为块级作用域
来源：http://dali.shangyingyoupin.top/Article/details/gtqlbzxsae.html

Go:   花括号块级作用域
来源：http://dali.gogol.net.cn/Article/details/gtzkasfsae.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xinyue.icu/Article/details/gtoiapdgmm.html

C#:   块级作用域
来源：http://dali.daria6918.cn/Article/details/gtezncisfr.html

[C11] 模块导入与导出
来源：http://dali.0kj1m.cn/Article/details/gtobgjhztj.html

Py:   from module import func
来源：http://dali.guowangkeji.top/Article/details/gtsdkbrkzk.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.sysykeji.top/Article/details/gtfvdjbwsb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.daria6918.cn/Article/details/gtswkftkpn.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jinqigufen.top/Article/details/gtwzbsxqpg.html

Java: import java.util.List;
来源：http://dali.xuanzx.com/Article/details/gtyvsxetxg.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yuanzhike.top/Article/details/gtsyeqtxdr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.c1oappe.top/Article/details/gtujdrdvrj.html

C#:   using System.Text;
来源：http://dali.shanyushiyangtech.top/Article/details/gtvwfkiluq.html

[C12] 立即执行函数 IIFE
来源：http://dali.yanxiufei.cn/Article/details/gtzhcyficl.html

Py:   (lambda: print("run"))()
来源：http://dali.xuetiantiany.cn/Article/details/gtqevjshep.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xuanzx.com/Article/details/gtaumertvj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ppjwa.cn/Article/details/gtcjwetzku.html

TS:   (() => { console.log("run"); })();
来源：http://dali.nanxinkj.top/Article/details/gtsgvtuuic.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxfnoentv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.chenlongwang.top/Article/details/gtyxmsifbi.html

Ruby: -> { puts "run" }.call
来源：http://dali.xinyue.icu/Article/details/gtgzhwoaws.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.mhx1999.top/Article/details/gturlvxxsy.html

[C13] 类型声明 / 类型注解
来源：http://dali.cdnleiting.top/Article/details/gtlmdpjcpk.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.tian-w.cn/Article/details/gtcdsqzrqy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.c1oappe.top/Article/details/gtazmdptpz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhiwuduotai.top/Article/details/gtfmqsmcwa.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtftkdaqdj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gtfuguzbub.html

Go:   func add(a, b int) int
来源：http://dali.chenzaomai.com/Article/details/gtjmpfbgrb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.c1oappe.top/Article/details/gtbkzcrfic.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yangfankeji.com/Article/details/gtklijfrux.html

[C14] 泛型函数
来源：http://dali.hammf.cn/Article/details/gtlyeofjyp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.wangshuangyany.cn/Article/details/gtianpgduq.html

PHP:  // 无泛型
来源：http://dali.snrcjt.cn/Article/details/gtwueushxw.html

JS:   // 无泛型
来源：http://dali.9152youxi.cn/Article/details/gtgdmpvjxr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xylfe.cn/Article/details/gtmgnnbjfg.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.pycfn.com/Article/details/gtqyyjpyql.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zdqjudy.top/Article/details/gtpjqjqmeh.html

Ruby: # 无泛型
来源：http://dali.yonumen.top/Article/details/gtnvedxcvz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jinghuilouyu.cn/Article/details/gtmpffvmhn.html

[C15] 解构 / 展开参数
来源：http://dali.zhoulong.xyz/Article/details/gtpacxshcm.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhixingplan.top/Article/details/gtabgmptuv.html

PHP:  [$a, $b] = $pair;
来源：http://dali.daxiang520.top/Article/details/gtoaekiifs.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.0kj1m.cn/Article/details/gttrhsqvnh.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cdnleiting.top/Article/details/gtuxeqmjqs.html

Java: // 无解构
来源：http://dali.ehwqpu.com/Article/details/gttlccuonw.html

Go:   // 无解构
来源：http://dali.jinqigufen.top/Article/details/gtsxawonra.html

Ruby: a, b = pair
来源：http://dali.xuetiantiany.cn/Article/details/gtiavybbzq.html

C#:   var (a, b) = pair;
来源：http://dali.ivvv.top/Article/details/gtgmokthkd.html

[C16] 函数 / 方法重载
来源：http://dali.hywenlv.cn/Article/details/gtuqsfqpym.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.feifeiyinyue.top/Article/details/gtbnogutzh.html

PHP:  // 无重载
来源：http://dali.cqqwz.cn/Article/details/gtuufhrhoi.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xuanzx.com/Article/details/gtzhvlllyo.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xuetiantiany.cn/Article/details/gtvzrlhkgx.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jqgufenzy.top/Article/details/gthaocesmm.html

Go:   // 无重载：用不同函数名
来源：http://dali.meibo888.top/Article/details/gtnfobctgc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.bjfxy.top/Article/details/gtnbbaiorb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gotoacloud.top/Article/details/gtgrjndmjc.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtkdvtpzxa.html

D. 数组 / 列表 / 集合
来源：http://dali.pycfn.com/Article/details/gtlqpakxhr.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtjcnauepv.html

[D01] 创建数组 / 列表
来源：http://dali.yonumen.top/Article/details/gteosifdwq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yvedp.cn/Article/details/gtkefweyjj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.chenzaomai.com/Article/details/gtlnjqgmjp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yvedp.cn/Article/details/gtkpmeterw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.wangdashe.top/Article/details/gthsjmonpo.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.dianchejie.cn/Article/details/gtbrurumfz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.feifeiyinyue.top/Article/details/gtcwcxroze.html

Ruby: arr = [1, 2, 3]
来源：http://dali.gaohongyu789.top/Article/details/gtrrtivrjk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yvedp.cn/Article/details/gtmesdclim.html

[D02] 追加元素到末尾
来源：http://dali.cqqwz.cn/Article/details/gtnikhrevp.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhoulong.xyz/Article/details/gtwsemyail.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhengqikj.top/Article/details/gtewhfougk.html

JS:   arr.push(4);
来源：http://dali.ybcxt.top/Article/details/gtliginumk.html

TS:   arr.push(4);
来源：http://dali.feifeiyinyue.top/Article/details/gtdsoynwqe.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gtnbwhbrju.html

Go:   arr = append(arr, 4)
来源：http://dali.hywenlv.cn/Article/details/gtjtluovnt.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.kuanghao11.cn/Article/details/gtewrjrtdt.html

C#:   list.Add(4);
来源：http://dali.kuanghao11.cn/Article/details/gtbvhnzjvj.html

[D03] 在指定位置插入元素
来源：http://dali.zhongyouzk.top/Article/details/gthdljzltf.html

Py:   arr.insert(0, 0)
来源：http://dali.yueranfly.top/Article/details/gtpfxswwza.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpqwdmwbu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hnqzz.top/Article/details/gtouyajszc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cqqwz.cn/Article/details/gtzncecxra.html

Java: list.add(0, 0);
来源：http://dali.ehwqpu.com/Article/details/gtjtnevnpq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.chenlongwang.top/Article/details/gtpzzrwbwe.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yvedp.cn/Article/details/gtwbldkgma.html

C#:   list.Insert(0, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtduqjpjbs.html

[D04] 删除元素
来源：http://dali.vqdsnc.cn/Article/details/gtykefzhvy.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.mhx1999.top/Article/details/gtlhgphowr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtagcftpnb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhiwuduotai.top/Article/details/gtduzoggym.html

TS:   arr.splice(0, 1);
来源：http://dali.zdqjudy.top/Article/details/gtiksvlymm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yanxiufei.cn/Article/details/gttwnumdya.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.iojbl.cn/Article/details/gtqcpiunxq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.svipenyu.cn/Article/details/gtoshsvbvy.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cqqwz.cn/Article/details/gtybgtutzs.html

[D05] 访问与修改元素
来源：http://dali.redwolf501.top/Article/details/gtstgamysb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.redwolf501.top/Article/details/gtqgwfwnor.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shuidangran.top/Article/details/gtrraeipje.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yj20258.top/Article/details/gtdbvumnyv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hfpthk.cn/Article/details/gtbkiimzmz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.meibo888.top/Article/details/gtrvebohox.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiemxpfuc.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.dashuyun.cn/Article/details/gtlabxjdly.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ybcxt.top/Article/details/gtdhkzfadf.html

[D06] 数组长度
来源：http://dali.snrcjt.cn/Article/details/gtzyxymrlr.html

Py:   len(arr)
来源：http://dali.tian-w.cn/Article/details/gtbeghqjux.html

PHP:  count($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtuwrwtehq.html

JS:   arr.length
来源：http://dali.gogol.net.cn/Article/details/gtclmjsfbd.html

TS:   arr.length
来源：http://dali.ehwqpu.com/Article/details/gtsjhwdqqj.html

Java: list.size();
来源：http://dali.xinyue.icu/Article/details/gtbrjedfzb.html

Go:   len(arr)
来源：http://dali.cqqwz.cn/Article/details/gtinnjpqut.html

Ruby: arr.length; arr.size
来源：http://dali.jqgfzy.top/Article/details/gtmdugddxk.html

C#:   list.Count;
来源：http://dali.ppjwa.cn/Article/details/gtgfgblnmj.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gtejuathxl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhiwuduotai.top/Article/details/gtloyofrtm.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hammf.cn/Article/details/gtltojqhmj.html

JS:   arr.slice(1, 4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtofvpfyqu.html

TS:   arr.slice(1, 4);
来源：http://dali.cqqwz.cn/Article/details/gtzgfjzcda.html

Java: list.subList(1, 4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtqfjmwfcw.html

Go:   arr[1:4]
来源：http://dali.jinqigfzy.top/Article/details/gtlffigvft.html

Ruby: arr[1, 3]
来源：http://dali.sufxvd.cn/Article/details/gtoakexlha.html

C#:   list.GetRange(1, 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdtncgjxq.html

[D08] 合并两个数组
来源：http://dali.zhixingplan.top/Article/details/gtjobckafu.html

Py:   a + b;  a.extend(b)
来源：http://dali.jlsjyb.cn/Article/details/gtronlmuno.html

PHP:  array_merge($a, $b);
来源：http://dali.quarkkingdee.top/Article/details/gtoosgsnzr.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ybcxt.top/Article/details/gtbjunaupt.html

TS:   [...a, ...b];
来源：http://dali.nanxuanxn.top/Article/details/gtzlcelukd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hnxiangtu.top/Article/details/gtszokgeqv.html

Go:   append(a, b...)
来源：http://dali.ydzc1.top/Article/details/gtacmbpqls.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yj20258.top/Article/details/gtowahrwml.html

C#:   a.Concat(b).ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtavwbxubc.html

[D09] 排序（升序）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgsqfivha.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.svipenyu.cn/Article/details/gtmiruukmz.html

PHP:  sort($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtlarhpuwu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.smart0.xyz/Article/details/gtfdqanvgo.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.haohaochexian.top/Article/details/gthzmpsdkt.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinghuilouyu.cn/Article/details/gtfekedicd.html


<!-- 参考信息 -->