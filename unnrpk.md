代发 wailian999

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnqzz.top/Article/details/gtfnedajpn.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuanzhike.top/Article/details/gtnnjqmrse.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.aizwys.cn/Article/details/gtxupwzcpq.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.guannengcc.top/Article/details/gtxprmggct.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gtnnpqlepc.html

[B10] 遍历同时拿索引
来源：http://dali.tian-w.cn/Article/details/gteaaecisl.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.bjfxy.top/Article/details/gtwpjtqjmm.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.gaohongyu789.top/Article/details/gtuonqqvom.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyvcmdpsd.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.sufxvd.cn/Article/details/gtzxjyhybb.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yangfankeji.com/Article/details/gtthdodrkq.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.pycfn.com/Article/details/gtgjfozppi.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ppjwa.cn/Article/details/gtvsspgbpf.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ppjwa.cn/Article/details/gteamtszwr.html

[B11] 生成数字序列 / 区间
来源：http://dali.hammf.cn/Article/details/gtrmfrnxpt.html

Py:   list(range(0, 10, 2))
来源：http://dali.pengpengdd.cyou/Article/details/gtcbitagfa.html

PHP:  range(0, 10, 2);
来源：http://dali.kuanghao11.cn/Article/details/gtzxzctnbz.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yanxiufei.cn/Article/details/gtonpscbzn.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gogol.net.cn/Article/details/gtokevynew.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.iojbl.cn/Article/details/gtsjgkuijp.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jqgfzy.top/Article/details/gtsorbxpzg.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xuetiantiany.cn/Article/details/gtiibyznky.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.xinyue.icu/Article/details/gtigthxudp.html

[B12] 跳出多层循环
来源：http://dali.jianghu66.top/Article/details/gtjsytxmcq.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.shangyingyoupin.top/Article/details/gtwdnptzki.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cucudq.cn/Article/details/gtseyaxjkp.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.vqdsnc.cn/Article/details/gtpmcjhtjd.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtowczsysb.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jianghu66.top/Article/details/gtolbeqeso.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.aizwys.cn/Article/details/gtrwqevlmb.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jqgufenzy.top/Article/details/gtdsmldlpm.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gtzqpemibn.html

[B13] 判断是否为数字
来源：http://dali.chenzaomai.com/Article/details/gtvymwqfka.html

Py:   isinstance(x, (int, float))
来源：http://dali.gogol.net.cn/Article/details/gtltkypmle.html

PHP:  is_numeric($x)
来源：http://dali.cheryme.top/Article/details/gtqhtqewkp.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhixingplan.top/Article/details/gtcliqyitb.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj20258888.top/Article/details/gtogrlcnkf.html

Java: x instanceof Number
来源：http://dali.yuxming.cn/Article/details/gtqfiactdq.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmudylmdk.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yvedp.cn/Article/details/gtzuvrmtrm.html

C#:   x is int or double or decimal
来源：http://dali.xuanzx.com/Article/details/gtjbsrbsos.html

[B14] 判断值是否在集合内
来源：http://dali.shuidangran.top/Article/details/gtqbhucfkt.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hysaishi.cn/Article/details/gtvvbynkzv.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xinyue.icu/Article/details/gttpuruyyy.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.tianlin.xyz/Article/details/gtjcgdwzwh.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.c1oappe.top/Article/details/gtikiqhgcz.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.dianchejie.cn/Article/details/gtazfuaznf.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtsubzzute.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.kuanghao11.cn/Article/details/gtnbmnydzs.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ehwqpu.com/Article/details/gtzqvjjkoc.html

[B15] 布尔运算与取反
来源：http://dali.hnxiangtu.top/Article/details/gtkosaqdde.html

Py:   a and b or not c
来源：http://dali.xziqi.cn/Article/details/gtujtytksg.html

PHP:  $a && $b || !$c
来源：http://dali.cucudq.cn/Article/details/gtfrajkctn.html

JS:   a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gtrfscwgpg.html

TS:   a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gtslnzsnbh.html

Java: a && b || !c
来源：http://dali.cashguo.top/Article/details/gtbtuldioy.html

Go:   a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gthstlobhf.html

Ruby: a && b || !c
来源：http://dali.daria6918.cn/Article/details/gtlbaacqib.html

C#:   a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gtevjuqwfl.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jinqigfzy.top/Article/details/gtdlxykoay.html

Py:   if not data: return
来源：http://dali.cucudq.cn/Article/details/gtiyyawlhf.html

PHP:  if (!$data) { return; }
来源：http://dali.svipenyu.cn/Article/details/gttyasbhcy.html

JS:   if (!data) return;
来源：http://dali.gzhubu.top/Article/details/gtacaepnnr.html

TS:   if (!data) return;
来源：http://dali.wangshuangyany.cn/Article/details/gtuyucqklr.html

Java: if (data == null) return;
来源：http://dali.daria6918.cn/Article/details/gtpnppemmc.html

Go:   if data == nil { return }
来源：http://dali.xinyue.icu/Article/details/gtjuqxteng.html

Ruby: return if data.nil?
来源：http://dali.zhiwuduotai.top/Article/details/gtgzobveau.html

C#:   if (data == null) return;
来源：http://dali.zhiwuduotai.top/Article/details/gtvtgutplw.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtjrsnzvct.html

C. 函数与作用域
来源：http://dali.fzhhl.top/Article/details/gtczcfpqyc.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtdlrtpftt.html

[C01] 定义函数
来源：http://dali.jlsjyb.cn/Article/details/gtllewwlxv.html

Py:   def add(a, b): return a + b
来源：http://dali.quarkkingdee.top/Article/details/gtgxngerrh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sufxvd.cn/Article/details/gtdcffjgif.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cashguo.top/Article/details/gtdckcwfpe.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gtmbngsfqd.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gtkhacgyvg.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.cucudq.cn/Article/details/gtyoqswhsu.html

Ruby: def add(a, b); a + b; end
来源：http://dali.nanxinkj.top/Article/details/gtdtacyufc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gtrsjffpyz.html

[C02] 默认参数
来源：http://dali.zhengqikj.top/Article/details/gtuythjdld.html

Py:   def greet(name="World"): return name
来源：http://dali.xinyue.icu/Article/details/gttlqhhgkk.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.aizwys.cn/Article/details/gtgplzqkhb.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtelkbssnt.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yuxming.cn/Article/details/gtykzdxtix.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hammf.cn/Article/details/gtxpzsxzsa.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.sweek.top/Article/details/gtvesgdpng.html

Ruby: def greet(name = "World") = name
来源：http://dali.jianghu66.top/Article/details/gteislvkcu.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yangfankeji.com/Article/details/gtchcsmhzg.html

[C03] 可变参数
来源：http://dali.jyoumei.cn/Article/details/gtipolxdnk.html

Py:   def total(*args): return sum(args)
来源：http://dali.gotoacloud.top/Article/details/gtaqgsdkls.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.sxryk.cn/Article/details/gthdhiscxc.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtemdcoijs.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzruidypu.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yongpay.top/Article/details/gtzldijhfd.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yj202588.top/Article/details/gthatgeras.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jyoumei.cn/Article/details/gtuhmxhwkz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ydzc1.top/Article/details/gtojwqfrwa.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hnqzz.top/Article/details/gtcrndyufh.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xuanzx.com/Article/details/gtfbpouyht.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yonumen.top/Article/details/gtpmfwtbho.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtihzglzlz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqwhgwzoi.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ppjwa.cn/Article/details/gtxplkzdpj.html

Go:   // 无：用配置结构体参数
来源：http://dali.yanxiufei.cn/Article/details/gteeibpqkg.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jlsjyb.cn/Article/details/gtwofkfwmy.html

C#:   f(a: 1, b: 2)
来源：http://dali.xuetiantiany.cn/Article/details/gttksnusfk.html

[C05] 返回多个值
来源：http://dali.jqgfzy.top/Article/details/gtyvhaixka.html

Py:   return a, b
来源：http://dali.sweek.top/Article/details/gtxrpgmsuc.html

PHP:  return [$a, $b];
来源：http://dali.yvedp.cn/Article/details/gtoeucaued.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.c1oappe.top/Article/details/gtjjrcxzvp.html

TS:   return { a, b };
来源：http://dali.jyoumei.cn/Article/details/gtiwtudjlc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hammf.cn/Article/details/gtdxhhazlz.html

Go:   return a, b
来源：http://dali.yj202588.top/Article/details/gtnukiqlmb.html

Ruby: return a, b
来源：http://dali.feifeiyinyue.top/Article/details/gtovvlzxzl.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yj202588.top/Article/details/gtrsojyrin.html

[C06] 匿名函数 / lambda
来源：http://dali.daxiang520.top/Article/details/gtwfrkxswp.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gttixcpija.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.316326.xyz/Article/details/gtzwunglsk.html

JS:   const square = x => x * x;
来源：http://dali.sysykeji.top/Article/details/gtbjnjqxom.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnwceiskp.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.dashuyun.cn/Article/details/gtkldlszew.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.snrcjt.cn/Article/details/gtqccmacxr.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hywenlv.cn/Article/details/gtnzubaxhb.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shangyingyoupin.top/Article/details/gttvsjcnsg.html

[C07] 把函数作为参数传入
来源：http://dali.shzxlz.cn/Article/details/gtqjitxofe.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.aizwys.cn/Article/details/gtvpxstbsy.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.gzhubu.top/Article/details/gtrpoecuep.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.daxiang520.top/Article/details/gtsucpicix.html

TS:   arr.map(String)
来源：http://dali.dianchejie.cn/Article/details/gtnvwqybrs.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgarefevz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.nanxinkj.top/Article/details/gtvhpypbpb.html

Ruby: arr.map(&:upcase)
来源：http://dali.gotoacloud.top/Article/details/gtbmzmfpsu.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ehwqpu.com/Article/details/gtapddiold.html

[C08] 闭包
来源：http://dali.chenlongwang.top/Article/details/gtdxqjhkeu.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.gzhubu.top/Article/details/gtkdgihavv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yj20258.top/Article/details/gttzhvoeny.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.c1oappe.top/Article/details/gttnmlnugt.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yj20258888.top/Article/details/gtwebobeee.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.fzhhl.top/Article/details/gtgzvollee.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.haohaochexian.top/Article/details/gtxwexjctj.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtgmxnjoyx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jinqigufen.top/Article/details/gtekeklfjg.html

[C09] 递归
来源：http://dali.yvedp.cn/Article/details/gtrjznmbrs.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ybcxt.top/Article/details/gtfepkaqnb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.havefunace.top/Article/details/gtlrndilby.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.feifeiyinyue.top/Article/details/gtitxgxxuq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hnqzz.top/Article/details/gtlbolwfgm.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yj202588.top/Article/details/gtrwlylvei.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jinqigufen.top/Article/details/gtnivcgqmn.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yueranfly.top/Article/details/gtebyzhzue.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xuanzx.com/Article/details/gtvfcxspfw.html

[C10] 变量作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkgsovjhq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cucudq.cn/Article/details/gtdgefzbmz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sysykeji.top/Article/details/gtivjcpydj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gthwdltmhz.html

TS:   同 JS
来源：http://dali.tanke756.top/Article/details/gtbzohnork.html

Java: 方法内为块级作用域
来源：http://dali.sufxvd.cn/Article/details/gtoeqcdyfv.html

Go:   花括号块级作用域
来源：http://dali.guannengcc.top/Article/details/gtuuzlpqvy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzpkfzhlh.html

C#:   块级作用域
来源：http://dali.vqdsnc.cn/Article/details/gtczrbrzkb.html

[C11] 模块导入与导出
来源：http://dali.haohaochexian.top/Article/details/gtfilhcmgg.html

Py:   from module import func
来源：http://dali.andypj.xyz/Article/details/gtkxmmxgbh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.tianlin.xyz/Article/details/gtraznhgdc.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.chenlongwang.top/Article/details/gtyvhcvffv.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sysykeji.top/Article/details/gtuxbniqgs.html

Java: import java.util.List;
来源：http://dali.jqgufenzy.top/Article/details/gtsxiamsqg.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.feifeiyinyue.top/Article/details/gtmcnculqa.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xuanzx.com/Article/details/gtkyhkrdjo.html

C#:   using System.Text;
来源：http://dali.zdqjudy.top/Article/details/gtdcckwveb.html

[C12] 立即执行函数 IIFE
来源：http://dali.mhx1999.top/Article/details/gtuossohti.html

Py:   (lambda: print("run"))()
来源：http://dali.9152youxi.cn/Article/details/gtvcswreky.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hnxiangtu.top/Article/details/gttitrqyeb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hnqzz.top/Article/details/gtyosjzvgy.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jiagoushi.top/Article/details/gtoupqjjjb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.wangdashe.top/Article/details/gtqawwvifp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinghuilouyu.cn/Article/details/gthbaixvei.html

Ruby: -> { puts "run" }.call
来源：http://dali.andypj.xyz/Article/details/gttlvvqyeq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.chenjidiqi.icu/Article/details/gtqkmvdlos.html

[C13] 类型声明 / 类型注解
来源：http://dali.jyoumei.cn/Article/details/gtvprqxbdk.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yongpay.top/Article/details/gtjqepznek.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gtxkkmcfnc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jinqigfzy.top/Article/details/gtqpddtxgu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gtiseszgox.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtowcvbhrs.html

Go:   func add(a, b int) int
来源：http://dali.gaohongyu789.top/Article/details/gtbsmoncdq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xinyue.icu/Article/details/gtsesjhcas.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gzhubu.top/Article/details/gttlmatzkq.html

[C14] 泛型函数
来源：http://dali.andypj.xyz/Article/details/gtgyhtifsc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.wangdashe.top/Article/details/gtcamyzusl.html

PHP:  // 无泛型
来源：http://dali.yj20258888.top/Article/details/gtszuhurbz.html

JS:   // 无泛型
来源：http://dali.tanke756.top/Article/details/gtncorqomo.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shangyingyoupin.top/Article/details/gtquxbvzoh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gaohongyu789.top/Article/details/gtlgqsmgxd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.chenjidiqi.icu/Article/details/gthxpyhsdm.html

Ruby: # 无泛型
来源：http://dali.shzxlz.cn/Article/details/gtnzxjyhqg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yanxiufei.cn/Article/details/gthvrpmukw.html

[C15] 解构 / 展开参数
来源：http://dali.hfpthk.cn/Article/details/gthztxnrtl.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.fzhhl.top/Article/details/gtlyxpjued.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinqigfzy.top/Article/details/gtvmergwqh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hnxiangtu.top/Article/details/gtcrxoxyke.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.316326.xyz/Article/details/gtcdygsxbg.html

Java: // 无解构
来源：http://dali.shzxlz.cn/Article/details/gtvzwpvqhf.html

Go:   // 无解构
来源：http://dali.hfpthk.cn/Article/details/gtjzoixgzy.html

Ruby: a, b = pair
来源：http://dali.shangyingyoupin.top/Article/details/gtdjvprugv.html

C#:   var (a, b) = pair;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoijoeafo.html

[C16] 函数 / 方法重载
来源：http://dali.ivvv.top/Article/details/gtlykbrahk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gtmovwhloa.html

PHP:  // 无重载
来源：http://dali.sxryk.cn/Article/details/gtgdxyrxkt.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shanyushiyangtech.top/Article/details/gtzmcnxviw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hnqzz.top/Article/details/gthyhyiimc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.smart0.xyz/Article/details/gtlhmxkdyj.html

Go:   // 无重载：用不同函数名
来源：http://dali.svipenyu.cn/Article/details/gtqremgirq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.fengsongda.top/Article/details/gtlfdvhoyj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cashguo.top/Article/details/gtqttwykun.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtgycekzpm.html

D. 数组 / 列表 / 集合
来源：http://dali.zhoulong.xyz/Article/details/gtgbisvhjw.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtddokvglx.html

[D01] 创建数组 / 列表
来源：http://dali.yj20258.top/Article/details/gtgqpzcotz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sxryk.cn/Article/details/gtnyyicdow.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.mhx1999.top/Article/details/gtrbvjiwoo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yj20258.top/Article/details/gtzqknelbr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yueranfly.top/Article/details/gtosebyqaq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.fengsongda.top/Article/details/gtodrtjgef.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.nanxinkj.top/Article/details/gtmcuwvzwj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.guannengcc.top/Article/details/gthujaotul.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.chenjidiqi.icu/Article/details/gtzhclbuwx.html

[D02] 追加元素到末尾
来源：http://dali.feifeiyinyue.top/Article/details/gthfuusiak.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cqqwz.cn/Article/details/gtdotdidcu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.dashuyun.cn/Article/details/gtfwjebtuf.html

JS:   arr.push(4);
来源：http://dali.yj20258.top/Article/details/gtmtnhxlxm.html

TS:   arr.push(4);
来源：http://dali.dianchejie.cn/Article/details/gtkpdpztwu.html

Java: list.add(4);
来源：http://dali.zhixingplan.top/Article/details/gtgrwqbsgg.html

Go:   arr = append(arr, 4)
来源：http://dali.cqqwz.cn/Article/details/gtkoyrrcol.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yongpay.top/Article/details/gtemahzonv.html

C#:   list.Add(4);
来源：http://dali.yonumen.top/Article/details/gtmzgmnyew.html

[D03] 在指定位置插入元素
来源：http://dali.hywenlv.cn/Article/details/gtevniqhex.html

Py:   arr.insert(0, 0)
来源：http://dali.zhengqikj.top/Article/details/gtkudbbiry.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.guannengcc.top/Article/details/gthmdkfofh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yj202588.top/Article/details/gtuwlahech.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ydzc1.top/Article/details/gtkxhhswvz.html

Java: list.add(0, 0);
来源：http://dali.chenlongwang.top/Article/details/gtvmjscgns.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.316326.xyz/Article/details/gtihjrxbai.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cdnleiting.top/Article/details/gtgkoibxfa.html

C#:   list.Insert(0, 0);
来源：http://dali.haohaochexian.top/Article/details/gtinnflazj.html

[D04] 删除元素
来源：http://dali.yangfankeji.com/Article/details/gtyxwqwcss.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.tianlin.xyz/Article/details/gtbmmvkgto.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jinqigufen.top/Article/details/gtwrooziab.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.haohaochexian.top/Article/details/gtiwysescm.html

TS:   arr.splice(0, 1);
来源：http://dali.pycfn.com/Article/details/gtfkqnvdxo.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.nanxinkj.top/Article/details/gtzfbbvxxh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hysaishi.cn/Article/details/gtqbjksmej.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yvedp.cn/Article/details/gtycttyiuk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yonumen.top/Article/details/gtuocfiyld.html

[D05] 访问与修改元素
来源：http://dali.cqqwz.cn/Article/details/gtrtaqyapm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.fengsongda.top/Article/details/gtbyqkkmim.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zdqjudy.top/Article/details/gtendjklpd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.sweek.top/Article/details/gtbxhlxwst.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhongyouzk.top/Article/details/gtzdtnobsc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hywenlv.cn/Article/details/gtojbzpjmf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sxryk.cn/Article/details/gtdamjszes.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.fengsongda.top/Article/details/gtzrmmbhsz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgdjrgsod.html

[D06] 数组长度
来源：http://dali.zycfv.cn/Article/details/gtfuxyaprp.html

Py:   len(arr)
来源：http://dali.zhixingplan.top/Article/details/gtdnzlgqww.html

PHP:  count($arr);
来源：http://dali.xinyue.icu/Article/details/gtdlixozch.html

JS:   arr.length
来源：http://dali.meibo888.top/Article/details/gtdkgjrhso.html

TS:   arr.length
来源：http://dali.yueranfly.top/Article/details/gtuqroqknk.html

Java: list.size();
来源：http://dali.shangyingyoupin.top/Article/details/gtfuzlwfbj.html

Go:   len(arr)
来源：http://dali.xinyue.icu/Article/details/gtdosawtyy.html

Ruby: arr.length; arr.size
来源：http://dali.sufxvd.cn/Article/details/gtvexyufoz.html

C#:   list.Count;
来源：http://dali.ehwqpu.com/Article/details/gtmtlpeoow.html

[D07] 切片 / 取子数组
来源：http://dali.zhengqikj.top/Article/details/gtdlhfxhcn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhongyouzk.top/Article/details/gtnocdwidl.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.wangdashe.top/Article/details/gtmxwvzbte.html

JS:   arr.slice(1, 4);
来源：http://dali.yanxiufei.cn/Article/details/gtinfxliet.html

TS:   arr.slice(1, 4);
来源：http://dali.andypj.xyz/Article/details/gttyfvvsir.html

Java: list.subList(1, 4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgchrmkau.html

Go:   arr[1:4]
来源：http://dali.zhengqikj.top/Article/details/gtsccbopdo.html

Ruby: arr[1, 3]
来源：http://dali.bjfxy.top/Article/details/gtliljmiyj.html

C#:   list.GetRange(1, 3);
来源：http://dali.hfpthk.cn/Article/details/gtcnihgsww.html

[D08] 合并两个数组
来源：http://dali.316326.xyz/Article/details/gtrldqbxzn.html

Py:   a + b;  a.extend(b)
来源：http://dali.cqqwz.cn/Article/details/gtitftgbds.html

PHP:  array_merge($a, $b);
来源：http://dali.zhengqikj.top/Article/details/gtwvbxiids.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.svipenyu.cn/Article/details/gtjvewuofz.html

TS:   [...a, ...b];
来源：http://dali.feifeiyinyue.top/Article/details/gtfkkfvwun.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttuhvepwk.html

Go:   append(a, b...)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsymnbgut.html

Ruby: a + b;  a.concat(b)
来源：http://dali.guowangkeji.top/Article/details/gtyqljlvom.html

C#:   a.Concat(b).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtminwbvan.html

[D09] 排序（升序）
来源：http://dali.jinghuilouyu.cn/Article/details/gtoyiskntv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jiagoushi.top/Article/details/gtnaezjsjl.html

PHP:  sort($arr);
来源：http://dali.ehwqpu.com/Article/details/gtgdxjyhwi.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhoulong.xyz/Article/details/gtzplvuntv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.meibo888.top/Article/details/gtnvmbjdxt.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.dianchejie.cn/Article/details/gtpcaiywfu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cqqwz.cn/Article/details/gtlbxwvoxi.html

Ruby: arr.sort
来源：http://dali.shangyingyoupin.top/Article/details/gtozljucnb.html

C#:   list.Sort();
来源：http://dali.gogol.net.cn/Article/details/gtaswucpsv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ydzc1.top/Article/details/gtssymvftx.html


<!-- 参考信息 -->