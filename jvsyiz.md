代发 wailian999

[B09] break 与 continue
来源：http://dali.iojbl.cn/Article/details/gtvphvoorb.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.haohaochexian.top/Article/details/gtwytudahu.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.guannengcc.top/Article/details/gtqxdfahdb.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xylfe.cn/Article/details/gtbgqmbhwa.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nwbrower.top/Article/details/gthvjghntt.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yonumen.top/Article/details/gtfdwhnmwt.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.bjfxy.top/Article/details/gtopufovfd.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyaqolfan.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tanke756.top/Article/details/gtlibmrspt.html

[B10] 遍历同时拿索引
来源：http://dali.nanxinkj.top/Article/details/gtpwzmgmfj.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jinqigfzy.top/Article/details/gtmvbjnkwd.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.iojbl.cn/Article/details/gtrupxhcsv.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.haohaochexian.top/Article/details/gtzkwoetef.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.iojbl.cn/Article/details/gtxewkkxnh.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.vqdsnc.cn/Article/details/gtqgzkzurv.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ppjwa.cn/Article/details/gtwxpoxowf.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.iojbl.cn/Article/details/gtcmowxgkd.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.chenlongwang.top/Article/details/gtvplmyhqg.html

[B11] 生成数字序列 / 区间
来源：http://dali.sufxvd.cn/Article/details/gtsaolroir.html

Py:   list(range(0, 10, 2))
来源：http://dali.guowangkeji.top/Article/details/gtqlcdohrx.html

PHP:  range(0, 10, 2);
来源：http://dali.snrcjt.cn/Article/details/gtoxymlleq.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yangfankeji.com/Article/details/gtlfmlhhwa.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaxgeqndf.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.nanxinkj.top/Article/details/gtusklwofp.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhoulong.xyz/Article/details/gtwzhyvbef.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hongshengwenyu.top/Article/details/gtxylwowyv.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jqgfzy.top/Article/details/gtqegctzuv.html

[B12] 跳出多层循环
来源：http://dali.pycfn.com/Article/details/gtanzysssk.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.feifeiyinyue.top/Article/details/gtgvzluqtj.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.redwolf501.top/Article/details/gtutoulcug.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jyoumei.cn/Article/details/gtiomdpwak.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.dianchejie.cn/Article/details/gtvqytuqpu.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zycfv.cn/Article/details/gtijzpbemr.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yj20258.top/Article/details/gtryhsgoqa.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.havefunace.top/Article/details/gtdqfzecwp.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.cheryme.top/Article/details/gthzfagydy.html

[B13] 判断是否为数字
来源：http://dali.shanyushiyangkeji.top/Article/details/gtybmtmpqz.html

Py:   isinstance(x, (int, float))
来源：http://dali.316326.xyz/Article/details/gtqwjzjujx.html

PHP:  is_numeric($x)
来源：http://dali.ybcxt.top/Article/details/gtwsztqwlw.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jiagoushi.top/Article/details/gtiofmurwl.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xinyue.icu/Article/details/gtrpyswkdj.html

Java: x instanceof Number
来源：http://dali.zhoulong.xyz/Article/details/gttgjkzezm.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.wangshuangyany.cn/Article/details/gtgcaockeo.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hywenlv.cn/Article/details/gtlergizmr.html

C#:   x is int or double or decimal
来源：http://dali.daria6918.cn/Article/details/gtfvysmqkt.html

[B14] 判断值是否在集合内
来源：http://dali.jqgufenzy.top/Article/details/gtelnxuxwc.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.gogol.net.cn/Article/details/gtcctcyzgu.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.9152youxi.cn/Article/details/gtwtdzclqy.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrituzjgd.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yvedp.cn/Article/details/gtccksemak.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ivvv.top/Article/details/gtyuzpyhvy.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtvvpjmcyv.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhongyouzk.top/Article/details/gtjainuahh.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.tanke756.top/Article/details/gteoahovby.html

[B15] 布尔运算与取反
来源：http://dali.hnqzz.top/Article/details/gtqaqrkell.html

Py:   a and b or not c
来源：http://dali.meibo888.top/Article/details/gthuutrhtf.html

PHP:  $a && $b || !$c
来源：http://dali.fengsongda.top/Article/details/gtncgxiuyc.html

JS:   a && b || !c
来源：http://dali.daria6918.cn/Article/details/gtbaetsvxs.html

TS:   a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gtwzqulzpo.html

Java: a && b || !c
来源：http://dali.shuidangran.top/Article/details/gtonaxlddi.html

Go:   a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gtrywzriel.html

Ruby: a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gtxfqfgfwb.html

C#:   a && b || !c
来源：http://dali.guannengcc.top/Article/details/gtpobucvld.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jyoumei.cn/Article/details/gtjczvmrmm.html

Py:   if not data: return
来源：http://dali.cashguo.top/Article/details/gtzchlszfb.html

PHP:  if (!$data) { return; }
来源：http://dali.birdmap.top/Article/details/gtywppiepn.html

JS:   if (!data) return;
来源：http://dali.zhoulong.xyz/Article/details/gtnejalyni.html

TS:   if (!data) return;
来源：http://dali.yanxiufei.cn/Article/details/gtvjjpddzd.html

Java: if (data == null) return;
来源：http://dali.sxryk.cn/Article/details/gttjhmhwuc.html

Go:   if data == nil { return }
来源：http://dali.zhoulong.xyz/Article/details/gtjsmfeibo.html

Ruby: return if data.nil?
来源：http://dali.nanxuanxn.top/Article/details/gtubfxnrwk.html

C#:   if (data == null) return;
来源：http://dali.hfpthk.cn/Article/details/gtddvmohen.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtjfcbgkej.html

C. 函数与作用域
来源：http://dali.wangdashe.top/Article/details/gtkhsjgaah.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtbomkxqgn.html

[C01] 定义函数
来源：http://dali.fzhhl.top/Article/details/gtoabmqrhs.html

Py:   def add(a, b): return a + b
来源：http://dali.vqdsnc.cn/Article/details/gtpfjureyk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daxiang520.top/Article/details/gtzmqrfuhw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gtdkqjciup.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gtogazlwld.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtyeioumcf.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ydzc1.top/Article/details/gtpaqpfuuk.html

Ruby: def add(a, b); a + b; end
来源：http://dali.dianchejie.cn/Article/details/gtmwaqfitq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gtexczgvwt.html

[C02] 默认参数
来源：http://dali.wangshuangyany.cn/Article/details/gteaywhwsh.html

Py:   def greet(name="World"): return name
来源：http://dali.nanxinkj.top/Article/details/gtssiluoso.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsbvskjkr.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtuejkduax.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxjsaqkak.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jiagoushi.top/Article/details/gteruuuqvd.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zycfv.cn/Article/details/gtmrxjphth.html

Ruby: def greet(name = "World") = name
来源：http://dali.316326.xyz/Article/details/gtepifcwsq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xziqi.cn/Article/details/gtdfhqppzm.html

[C03] 可变参数
来源：http://dali.smart0.xyz/Article/details/gtrfejqhxo.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhongyouzk.top/Article/details/gtgmceccfe.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.iojbl.cn/Article/details/gtjfrxjzfx.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.pengpengdd.cyou/Article/details/gtjalrevik.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.kuanghao11.cn/Article/details/gtwdeblkin.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ehwqpu.com/Article/details/gtmxosfcej.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfuoykfw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.havefunace.top/Article/details/gtdrinawux.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.mhx1999.top/Article/details/gtizhupufi.html

[C04] 命名参数 / 关键字参数
来源：http://dali.andypj.xyz/Article/details/gtxhxhksns.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.guowangkeji.top/Article/details/gtjftozmhy.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gtgrejlyod.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtqpuypcwm.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhixingplan.top/Article/details/gtdvijhwje.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.mhx1999.top/Article/details/gtfzuiwqfy.html

Go:   // 无：用配置结构体参数
来源：http://dali.yanxiufei.cn/Article/details/gtcqlrsobs.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hysaishi.cn/Article/details/gtkibcnksv.html

C#:   f(a: 1, b: 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtvvbqykjo.html

[C05] 返回多个值
来源：http://dali.feifeiyinyue.top/Article/details/gtsagnffpw.html

Py:   return a, b
来源：http://dali.jiagoushi.top/Article/details/gtcmlpoucs.html

PHP:  return [$a, $b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpnrtisxu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yj20258.top/Article/details/gttpfyzvqe.html

TS:   return { a, b };
来源：http://dali.yongpay.top/Article/details/gtmvcouzrl.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xziqi.cn/Article/details/gtuxvedluk.html

Go:   return a, b
来源：http://dali.zhixingplan.top/Article/details/gtxnlbuojf.html

Ruby: return a, b
来源：http://dali.jlsjyb.cn/Article/details/gtavjlfpty.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shuidangran.top/Article/details/gtrdjqrnlf.html

[C06] 匿名函数 / lambda
来源：http://dali.tanke756.top/Article/details/gtwhiukqqp.html

Py:   square = lambda x: x * x
来源：http://dali.andypj.xyz/Article/details/gtwmhebwax.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.iojbl.cn/Article/details/gtnqwlzolq.html

JS:   const square = x => x * x;
来源：http://dali.tianlin.xyz/Article/details/gtvcdbfean.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.bjfxy.top/Article/details/gtaccvnknw.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.shanyushiyangtech.top/Article/details/gttwtgsshc.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ehwqpu.com/Article/details/gtvjmgbgvc.html

Ruby: square = ->(x) { x * x }
来源：http://dali.316326.xyz/Article/details/gtprgtjsdv.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.aizwys.cn/Article/details/gtchqpxngt.html

[C07] 把函数作为参数传入
来源：http://dali.gaohongyu789.top/Article/details/gtlilolrbx.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxidfzpoh.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yanxiufei.cn/Article/details/gtpyxgvgwk.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xylfe.cn/Article/details/gtfgojcfcu.html

TS:   arr.map(String)
来源：http://dali.daxiang520.top/Article/details/gtpgsucrsg.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.kuanghao11.cn/Article/details/gtmaydmylh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.guowangkeji.top/Article/details/gtavbdhznj.html

Ruby: arr.map(&:upcase)
来源：http://dali.yanxiufei.cn/Article/details/gtedzdckvp.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.nanxinkj.top/Article/details/gtppzfaiwc.html

[C08] 闭包
来源：http://dali.dashuyun.cn/Article/details/gtxgnljfyq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.nwbrower.top/Article/details/gtikkdiznn.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgqlzxnxc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.quarkkingdee.top/Article/details/gtiilistkn.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xuanzx.com/Article/details/gtdhdxjjuj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.daria6918.cn/Article/details/gtlbosxdun.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.ivvv.top/Article/details/gtpswlwleq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.meibo888.top/Article/details/gtljthzpkw.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cdnleiting.top/Article/details/gthenrhyiy.html

[C09] 递归
来源：http://dali.xuetiantiany.cn/Article/details/gtoouhwqyt.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtfidfmllt.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.9152youxi.cn/Article/details/gthomqjpun.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yueranfly.top/Article/details/gtslnhzqsc.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.svipenyu.cn/Article/details/gtsemxvjrq.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.tianlin.xyz/Article/details/gtjkazctyx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hywenlv.cn/Article/details/gtjkntlner.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtumxlyehu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xylfe.cn/Article/details/gthkfankel.html

[C10] 变量作用域
来源：http://dali.gogol.net.cn/Article/details/gtcewrtskm.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.nwbrower.top/Article/details/gtgzdczgfx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yuanzhike.top/Article/details/gtliowzhbl.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yuxming.cn/Article/details/gtrgbawiwq.html

TS:   同 JS
来源：http://dali.zhoulong.xyz/Article/details/gtwicclnex.html

Java: 方法内为块级作用域
来源：http://dali.hongshengwenyu.top/Article/details/gtwgpoupaf.html

Go:   花括号块级作用域
来源：http://dali.zycfv.cn/Article/details/gtamboerov.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcpwhxban.html

C#:   块级作用域
来源：http://dali.zhongyouzk.top/Article/details/gtkgrcqroo.html

[C11] 模块导入与导出
来源：http://dali.hammf.cn/Article/details/gtoavznndb.html

Py:   from module import func
来源：http://dali.cdnleiting.top/Article/details/gtanzzpyfu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yueranfly.top/Article/details/gtoxhhgzwx.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.guowangkeji.top/Article/details/gtbqhkctnk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gtiscnmdrx.html

Java: import java.util.List;
来源：http://dali.yvedp.cn/Article/details/gtfavcaqjv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.chenjidiqi.icu/Article/details/gtagkjuevp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.andypj.xyz/Article/details/gtsiwibkac.html

C#:   using System.Text;
来源：http://dali.chenlongwang.top/Article/details/gtldzqrkja.html

[C12] 立即执行函数 IIFE
来源：http://dali.feifeiyinyue.top/Article/details/gtqdukamod.html

Py:   (lambda: print("run"))()
来源：http://dali.daria6918.cn/Article/details/gtntljucfq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yongpay.top/Article/details/gtgqiuwjuu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xinyue.icu/Article/details/gttotzkukk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtliyeyqpr.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yvedp.cn/Article/details/gtgqfimevx.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.sxryk.cn/Article/details/gtepgodvpn.html

Ruby: -> { puts "run" }.call
来源：http://dali.iojbl.cn/Article/details/gtnnzjyjfa.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yj202588.top/Article/details/gtbuvcrhpx.html

[C13] 类型声明 / 类型注解
来源：http://dali.meibo888.top/Article/details/gtmmclkwfi.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shzxlz.cn/Article/details/gtedqsmzmm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tianlin.xyz/Article/details/gtywiplajs.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jinqigufen.top/Article/details/gtksepkolt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gtpfrbybad.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtocyskpya.html

Go:   func add(a, b int) int
来源：http://dali.yuxming.cn/Article/details/gtkrthoren.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zycfv.cn/Article/details/gtizuqqmnb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gogol.net.cn/Article/details/gtifiwuhft.html

[C14] 泛型函数
来源：http://dali.jlsjyb.cn/Article/details/gtbcdbcsxw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yuxming.cn/Article/details/gtrbvbcfdx.html

PHP:  // 无泛型
来源：http://dali.iojbl.cn/Article/details/gtwebzasts.html

JS:   // 无泛型
来源：http://dali.birdmap.top/Article/details/gtmtrcctjt.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.chenzaomai.com/Article/details/gtalyvftan.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jianghu66.top/Article/details/gtewquwchq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ybcxt.top/Article/details/gtvrfdykct.html

Ruby: # 无泛型
来源：http://dali.xuetiantiany.cn/Article/details/gtbsuvpske.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhixingplan.top/Article/details/gtcjvemdgs.html

[C15] 解构 / 展开参数
来源：http://dali.andypj.xyz/Article/details/gteirgvzbr.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ppjwa.cn/Article/details/gtzjvqalqt.html

PHP:  [$a, $b] = $pair;
来源：http://dali.andypj.xyz/Article/details/gthiguucql.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlfqfjsxw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cashguo.top/Article/details/gtbqzttyrt.html

Java: // 无解构
来源：http://dali.hammf.cn/Article/details/gtryxrirwo.html

Go:   // 无解构
来源：http://dali.guowangkeji.top/Article/details/gtuszwdbqm.html

Ruby: a, b = pair
来源：http://dali.cashguo.top/Article/details/gtxmbjxqlf.html

C#:   var (a, b) = pair;
来源：http://dali.zhengqikj.top/Article/details/gtkbyzkaal.html

[C16] 函数 / 方法重载
来源：http://dali.ehwqpu.com/Article/details/gtxmacczsa.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ywan-chungtsiang.top/Article/details/gturtprjzz.html

PHP:  // 无重载
来源：http://dali.quarkkingdee.top/Article/details/gtgongrqvl.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hfpthk.cn/Article/details/gtnergerzz.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yj20258.top/Article/details/gtjskjrjhe.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jyoumei.cn/Article/details/gtymepfnrm.html

Go:   // 无重载：用不同函数名
来源：http://dali.ehwqpu.com/Article/details/gtsjygtrep.html

Ruby: # 无重载：靠动态参数
来源：http://dali.smart0.xyz/Article/details/gtimqlrzbb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.tian-w.cn/Article/details/gtnpksilky.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtztjmiczn.html

D. 数组 / 列表 / 集合
来源：http://dali.yangfankeji.com/Article/details/gttjxdjdms.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtbfsdphlk.html

[D01] 创建数组 / 列表
来源：http://dali.cheryme.top/Article/details/gtoqgjnhzm.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yuxming.cn/Article/details/gtrrpgykya.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ehwqpu.com/Article/details/gthenpxpwe.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sysykeji.top/Article/details/gtgylfwqld.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ybcxt.top/Article/details/gtiueanjbz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhengqikj.top/Article/details/gtsdeotbia.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhiwuduotai.top/Article/details/gtmcgqrhfs.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yj202588.top/Article/details/gtvnhbcvja.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.guannengcc.top/Article/details/gtrqtxvkis.html

[D02] 追加元素到末尾
来源：http://dali.sysykeji.top/Article/details/gtusvdlxye.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.mhx1999.top/Article/details/gtpythiyov.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.aizwys.cn/Article/details/gtriikpbmx.html

JS:   arr.push(4);
来源：http://dali.daria6918.cn/Article/details/gtrnemjtsl.html

TS:   arr.push(4);
来源：http://dali.yueranfly.top/Article/details/gtmzganwqy.html

Java: list.add(4);
来源：http://dali.chenjidiqi.icu/Article/details/gtknladshb.html

Go:   arr = append(arr, 4)
来源：http://dali.pycfn.com/Article/details/gttleokjbs.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.chenjidiqi.icu/Article/details/gtroqmqhvc.html

C#:   list.Add(4);
来源：http://dali.tian-w.cn/Article/details/gtinopczfp.html

[D03] 在指定位置插入元素
来源：http://dali.hammf.cn/Article/details/gtaabhdtyj.html

Py:   arr.insert(0, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtwmggxeay.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.quarkkingdee.top/Article/details/gtfengdiyh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shanyushiyangkeji.top/Article/details/gtshmzayxc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jiagoushi.top/Article/details/gtnhmewmzy.html

Java: list.add(0, 0);
来源：http://dali.sxryk.cn/Article/details/gtelxshury.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hnxiangtu.top/Article/details/gtfqpdmxxs.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hongshengwenyu.top/Article/details/gtuxpdecox.html

C#:   list.Insert(0, 0);
来源：http://dali.redwolf501.top/Article/details/gthfrvfusb.html

[D04] 删除元素
来源：http://dali.cashguo.top/Article/details/gtqouuulbf.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinqigufen.top/Article/details/gtxclmkqtf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtiwwrcrwx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.dashuyun.cn/Article/details/gtiaxxqrwy.html

TS:   arr.splice(0, 1);
来源：http://dali.zdqjudy.top/Article/details/gtckvuobeh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jinqigufen.top/Article/details/gtgndmwmjy.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zycfv.cn/Article/details/gtdtnkxirm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.tanke756.top/Article/details/gtypqjfekl.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.kuanghao11.cn/Article/details/gteffcvsqk.html

[D05] 访问与修改元素
来源：http://dali.bjfxy.top/Article/details/gtyalvrxfm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nwbrower.top/Article/details/gtnzrpvsdq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.aibaodan.cn/Article/details/gtevbocpyd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ehwqpu.com/Article/details/gtzbybpdes.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hfpthk.cn/Article/details/gtraicpnsl.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sxryk.cn/Article/details/gtzryhyqmf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.quarkkingdee.top/Article/details/gtymtnxzal.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenjidiqi.icu/Article/details/gtqvqnlnmh.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenjidiqi.icu/Article/details/gtpxonpjce.html

[D06] 数组长度
来源：http://dali.ehwqpu.com/Article/details/gtmqcvjbyk.html

Py:   len(arr)
来源：http://dali.hywenlv.cn/Article/details/gtpydqvulc.html

PHP:  count($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtgjuzjyek.html

JS:   arr.length
来源：http://dali.jqgufenzy.top/Article/details/gtonvnrbam.html

TS:   arr.length
来源：http://dali.ybcxt.top/Article/details/gtupinzufj.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gtwkuiuexk.html

Go:   len(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gthxbamepp.html

Ruby: arr.length; arr.size
来源：http://dali.xziqi.cn/Article/details/gtaysiybdi.html

C#:   list.Count;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtujnzypzv.html

[D07] 切片 / 取子数组
来源：http://dali.yangfankeji.com/Article/details/gtpxalmywf.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hammf.cn/Article/details/gtmvsnxfns.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtwvinnxgd.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gtosqefgvj.html

TS:   arr.slice(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gtrenjgnbx.html

Java: list.subList(1, 4);
来源：http://dali.cucudq.cn/Article/details/gtmufnejmp.html

Go:   arr[1:4]
来源：http://dali.kuanghao11.cn/Article/details/gtqlddulvt.html

Ruby: arr[1, 3]
来源：http://dali.yj202588.top/Article/details/gtuapiflgk.html

C#:   list.GetRange(1, 3);
来源：http://dali.ivvv.top/Article/details/gtkuaqrvae.html

[D08] 合并两个数组
来源：http://dali.ivvv.top/Article/details/gtmixxoldo.html

Py:   a + b;  a.extend(b)
来源：http://dali.tanke756.top/Article/details/gtrfnuiyap.html

PHP:  array_merge($a, $b);
来源：http://dali.hnxiangtu.top/Article/details/gtwmcwktpt.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.tanke756.top/Article/details/gthfvjdeay.html

TS:   [...a, ...b];
来源：http://dali.sufxvd.cn/Article/details/gtquxwpabe.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shuidangran.top/Article/details/gtwyhzkmmx.html

Go:   append(a, b...)
来源：http://dali.hysaishi.cn/Article/details/gtdrjzyooe.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yanxiufei.cn/Article/details/gtofisyrzc.html

C#:   a.Concat(b).ToList()
来源：http://dali.sysykeji.top/Article/details/gtrlmrdskf.html

[D09] 排序（升序）
来源：http://dali.zycfv.cn/Article/details/gtsermcyxd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hysaishi.cn/Article/details/gtjthflvvr.html

PHP:  sort($arr);
来源：http://dali.bjfxy.top/Article/details/gtofhbgvjl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yvedp.cn/Article/details/gtghcqtkvz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.aibaodan.cn/Article/details/gtzdrhewed.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cashguo.top/Article/details/gtdixkvurl.html


<!-- 参考信息 -->