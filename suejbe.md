代发 wailian999

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.iojbl.cn/Article/details/gtjihdwruo.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtuqiugrua.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.redwolf501.top/Article/details/gtjrwfcjue.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtouukjutv.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdjyibvbb.html

[B10] 遍历同时拿索引
来源：http://dali.chenjidiqi.icu/Article/details/gtztuiokqx.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.xuetiantiany.cn/Article/details/gtvztfebtp.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.fzhhl.top/Article/details/gtiwbfqbvp.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhengqikj.top/Article/details/gtnwlgmgav.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jiagoushi.top/Article/details/gtwdaadxgw.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.gotoacloud.top/Article/details/gtzcqmliki.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yj202588.top/Article/details/gtqxrguhsr.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhengqikj.top/Article/details/gtcnerntid.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhixingplan.top/Article/details/gtogdaywyg.html

[B11] 生成数字序列 / 区间
来源：http://dali.hnxiangtu.top/Article/details/gtrdbegvuu.html

Py:   list(range(0, 10, 2))
来源：http://dali.yj20258.top/Article/details/gtjdcknjca.html

PHP:  range(0, 10, 2);
来源：http://dali.gotoacloud.top/Article/details/gtqriycocd.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtvbquxedp.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhoulong.xyz/Article/details/gtwzpxflqm.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yueranfly.top/Article/details/gtpcpwjyae.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhongyouzk.top/Article/details/gtlddfolli.html

Ruby: (0...10).step(2).to_a
来源：http://dali.shzxlz.cn/Article/details/gtfqyvpjdg.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.c1oappe.top/Article/details/gtyuudznwi.html

[B12] 跳出多层循环
来源：http://dali.yuanzhike.top/Article/details/gtrqgkopaq.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hfpthk.cn/Article/details/gtwczaixos.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.gotoacloud.top/Article/details/gtdrrrvdcd.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenjidiqi.icu/Article/details/gtuibufbet.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nwbrower.top/Article/details/gtihrfgqsg.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.havefunace.top/Article/details/gtfmtzyumo.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hnqzz.top/Article/details/gtxepbcqmf.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.cdnleiting.top/Article/details/gtydnotujg.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yvedp.cn/Article/details/gtrprtwqaa.html

[B13] 判断是否为数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gtymxydbhx.html

Py:   isinstance(x, (int, float))
来源：http://dali.jqgufenzy.top/Article/details/gtgaoyiygk.html

PHP:  is_numeric($x)
来源：http://dali.ydzc1.top/Article/details/gtksyqhhig.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.mhx1999.top/Article/details/gtgnrjooxp.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinqigufen.top/Article/details/gtddeefqqv.html

Java: x instanceof Number
来源：http://dali.sysykeji.top/Article/details/gtecluxkih.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.vqdsnc.cn/Article/details/gtvygvnjij.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yuxming.cn/Article/details/gttvntqouy.html

C#:   x is int or double or decimal
来源：http://dali.pengpengdd.cyou/Article/details/gtbeyxlygz.html

[B14] 判断值是否在集合内
来源：http://dali.chenjidiqi.icu/Article/details/gtnnmfiian.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcqxoimmq.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnvurbthl.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyxgxdjux.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.dashuyun.cn/Article/details/gtiwnsssyo.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.mhx1999.top/Article/details/gtwqbeowmf.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtybcvvyph.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtemmcscpc.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jiagoushi.top/Article/details/gtjostacas.html

[B15] 布尔运算与取反
来源：http://dali.iojbl.cn/Article/details/gtyvyahgpb.html

Py:   a and b or not c
来源：http://dali.yonumen.top/Article/details/gtucniidxw.html

PHP:  $a && $b || !$c
来源：http://dali.daxiang520.top/Article/details/gtfoejsfnu.html

JS:   a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gtutdmqfua.html

TS:   a && b || !c
来源：http://dali.yueranfly.top/Article/details/gtopncalin.html

Java: a && b || !c
来源：http://dali.pycfn.com/Article/details/gtaewbtzjd.html

Go:   a && b || !c
来源：http://dali.hongshengwenyu.top/Article/details/gtizchbqdp.html

Ruby: a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gtfsltdzcs.html

C#:   a && b || !c
来源：http://dali.ivvv.top/Article/details/gtfijsexws.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.gogol.net.cn/Article/details/gtanvhlfoi.html

Py:   if not data: return
来源：http://dali.gotoacloud.top/Article/details/gtqiietkgx.html

PHP:  if (!$data) { return; }
来源：http://dali.sxryk.cn/Article/details/gtbaaqpnve.html

JS:   if (!data) return;
来源：http://dali.jianghu66.top/Article/details/gtjdwtkvvb.html

TS:   if (!data) return;
来源：http://dali.hysaishi.cn/Article/details/gtznjrqdky.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gtvxakpbuu.html

Go:   if data == nil { return }
来源：http://dali.ybcxt.top/Article/details/gtzqhynpfp.html

Ruby: return if data.nil?
来源：http://dali.yj20258888.top/Article/details/gtpgyicdgt.html

C#:   if (data == null) return;
来源：http://dali.jqgufenzy.top/Article/details/gttedycjqq.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtqnzxquyw.html

C. 函数与作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gtaptbieqm.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtxlqhafgz.html

[C01] 定义函数
来源：http://dali.birdmap.top/Article/details/gtikqpbpgh.html

Py:   def add(a, b): return a + b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxmoncbnb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.fzhhl.top/Article/details/gthzgcegrs.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ivvv.top/Article/details/gthfrfqeig.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gtcegddnxm.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtyleijxot.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.gogol.net.cn/Article/details/gtwdhlnjin.html

Ruby: def add(a, b); a + b; end
来源：http://dali.snrcjt.cn/Article/details/gttsdsddhp.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gtmvizqqut.html

[C02] 默认参数
来源：http://dali.wangshuangyany.cn/Article/details/gtgwgwqkrc.html

Py:   def greet(name="World"): return name
来源：http://dali.jqgfzy.top/Article/details/gtovswwrgr.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jinqigufen.top/Article/details/gthxoctdqc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.iojbl.cn/Article/details/gtucudvdnd.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xinyue.icu/Article/details/gthfnqrwdg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shangyingyoupin.top/Article/details/gtfewftatl.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jiagoushi.top/Article/details/gtrsowjtsj.html

Ruby: def greet(name = "World") = name
来源：http://dali.jlsjyb.cn/Article/details/gtcgjonjum.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yonumen.top/Article/details/gtdnbhaizk.html

[C03] 可变参数
来源：http://dali.jqgfzy.top/Article/details/gtcnwskmxz.html

Py:   def total(*args): return sum(args)
来源：http://dali.nwbrower.top/Article/details/gttmogudxf.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gtcwiaguaj.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hammf.cn/Article/details/gtrfkpppzw.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.meibo888.top/Article/details/gtyuvazsxn.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtrczfbwmh.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yuanzhike.top/Article/details/gtzvijscqe.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.haohaochexian.top/Article/details/gtqjobolfl.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.aibaodan.cn/Article/details/gtdfyvqfyi.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gogol.net.cn/Article/details/gtpcubwgzi.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shangyingyoupin.top/Article/details/gtptkuvzme.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zycfv.cn/Article/details/gtjjjtdbli.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yuanzhike.top/Article/details/gtbwwpqhyn.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zdqjudy.top/Article/details/gtwqbnzlja.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.iojbl.cn/Article/details/gtyglzrssi.html

Go:   // 无：用配置结构体参数
来源：http://dali.yongpay.top/Article/details/gtqseojvfm.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jlsjyb.cn/Article/details/gtnzvsvtsj.html

C#:   f(a: 1, b: 2)
来源：http://dali.jlsjyb.cn/Article/details/gtcfwvcyjz.html

[C05] 返回多个值
来源：http://dali.havefunace.top/Article/details/gtsgwgmllz.html

Py:   return a, b
来源：http://dali.xziqi.cn/Article/details/gtvbugizbz.html

PHP:  return [$a, $b];
来源：http://dali.gaohongyu789.top/Article/details/gtfwahlipq.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sxryk.cn/Article/details/gtjwldcvpk.html

TS:   return { a, b };
来源：http://dali.chenlongwang.top/Article/details/gtqmkbnuhb.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuoloigny.html

Go:   return a, b
来源：http://dali.pengpengdd.cyou/Article/details/gtilwvzlhn.html

Ruby: return a, b
来源：http://dali.yueranfly.top/Article/details/gtftfwzvrf.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hywenlv.cn/Article/details/gtshoehxzk.html

[C06] 匿名函数 / lambda
来源：http://dali.feifeiyinyue.top/Article/details/gtbvwxgujv.html

Py:   square = lambda x: x * x
来源：http://dali.yangfankeji.com/Article/details/gtqtsvkhqs.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.guowangkeji.top/Article/details/gtlwpwwwyi.html

JS:   const square = x => x * x;
来源：http://dali.pycfn.com/Article/details/gtpchxjdli.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jinqigufen.top/Article/details/gtwcnysqxt.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hywenlv.cn/Article/details/gtuxhgaawg.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xziqi.cn/Article/details/gtkrzuunpn.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jqgufenzy.top/Article/details/gtphexddtj.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.dashuyun.cn/Article/details/gtbnikffvw.html

[C07] 把函数作为参数传入
来源：http://dali.nwbrower.top/Article/details/gtbyxyikws.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yuxming.cn/Article/details/gtdaumzuvx.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.dashuyun.cn/Article/details/gtazvstywg.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cucudq.cn/Article/details/gtlnimcxkv.html

TS:   arr.map(String)
来源：http://dali.andypj.xyz/Article/details/gtfxyuxvgq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hnxiangtu.top/Article/details/gtfjwucfap.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xziqi.cn/Article/details/gtzfkjztty.html

Ruby: arr.map(&:upcase)
来源：http://dali.ybcxt.top/Article/details/gtstrffyvo.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xuetiantiany.cn/Article/details/gtbusmaucl.html

[C08] 闭包
来源：http://dali.gotoacloud.top/Article/details/gtsqwjdlej.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdowbilnh.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.tanke756.top/Article/details/gtppcflpsf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.guowangkeji.top/Article/details/gtyljpgxzg.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.aizwys.cn/Article/details/gtivopipnn.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gogol.net.cn/Article/details/gtkgtnfduq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shzxlz.cn/Article/details/gtsattnprh.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hammf.cn/Article/details/gtrgaymmks.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.dashuyun.cn/Article/details/gtvbrpcbjy.html

[C09] 递归
来源：http://dali.zhiwuduotai.top/Article/details/gtpunoapqd.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yj202588.top/Article/details/gtcxcbssfb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.chenlongwang.top/Article/details/gtidfftdma.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cdnleiting.top/Article/details/gtjtajfwvb.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shanyushiyangtech.top/Article/details/gthjcermhp.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jqgufenzy.top/Article/details/gtjjmvcujg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.iojbl.cn/Article/details/gtpozrndqq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shzxlz.cn/Article/details/gthulpwfhx.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.sweek.top/Article/details/gtrftlbizp.html

[C10] 变量作用域
来源：http://dali.gotoacloud.top/Article/details/gtjhwxmmwu.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gaohongyu789.top/Article/details/gtmpccqwpx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqgpaogdz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ybcxt.top/Article/details/gtimrrwggq.html

TS:   同 JS
来源：http://dali.snrcjt.cn/Article/details/gtaifkvhzu.html

Java: 方法内为块级作用域
来源：http://dali.guowangkeji.top/Article/details/gtumjnglhy.html

Go:   花括号块级作用域
来源：http://dali.tanke756.top/Article/details/gtauxxlbxx.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhongyouzk.top/Article/details/gtfrcvqfmv.html

C#:   块级作用域
来源：http://dali.yangfankeji.com/Article/details/gthnbgvrzu.html

[C11] 模块导入与导出
来源：http://dali.kuanghao11.cn/Article/details/gtkiwskzka.html

Py:   from module import func
来源：http://dali.yj20258888.top/Article/details/gtxzmtppdq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.sysykeji.top/Article/details/gtyuhxbwia.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.andypj.xyz/Article/details/gtvukthqus.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.shangyingyoupin.top/Article/details/gtfcctobqf.html

Java: import java.util.List;
来源：http://dali.meibo888.top/Article/details/gttrawhxwh.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sweek.top/Article/details/gtwopmoqyn.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.daria6918.cn/Article/details/gtfhrulxyq.html

C#:   using System.Text;
来源：http://dali.jinqigfzy.top/Article/details/gtsnsdqvqb.html

[C12] 立即执行函数 IIFE
来源：http://dali.hammf.cn/Article/details/gtaarazhxi.html

Py:   (lambda: print("run"))()
来源：http://dali.tianlin.xyz/Article/details/gtktnrfnik.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhixingplan.top/Article/details/gtuewvbfam.html

JS:   (() => { console.log("run"); })();
来源：http://dali.tian-w.cn/Article/details/gtkiietsri.html

TS:   (() => { console.log("run"); })();
来源：http://dali.smart0.xyz/Article/details/gtgmjuxocw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbmokhvvl.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuykzscyj.html

Ruby: -> { puts "run" }.call
来源：http://dali.tanke756.top/Article/details/gtlxrwnjad.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yongpay.top/Article/details/gtlsszgter.html

[C13] 类型声明 / 类型注解
来源：http://dali.quarkkingdee.top/Article/details/gtdejmaggq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jqgufenzy.top/Article/details/gtafuvllqc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258.top/Article/details/gtdhntlztd.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yuxming.cn/Article/details/gtdokmgdxs.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gtqfuvppwm.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gtptjypjax.html

Go:   func add(a, b int) int
来源：http://dali.smart0.xyz/Article/details/gtvmjymmqc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sxryk.cn/Article/details/gtrjnimntj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cucudq.cn/Article/details/gtlfkeepjz.html

[C14] 泛型函数
来源：http://dali.jinqigfzy.top/Article/details/gthkgqubci.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.mhx1999.top/Article/details/gtfkdczfgp.html

PHP:  // 无泛型
来源：http://dali.yueranfly.top/Article/details/gtkqjjqeqa.html

JS:   // 无泛型
来源：http://dali.smart0.xyz/Article/details/gtqiswlyjp.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gtrfdfdvbb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.fengsongda.top/Article/details/gtogzctnoe.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.guowangkeji.top/Article/details/gtftyalsxn.html

Ruby: # 无泛型
来源：http://dali.shanyushiyangtech.top/Article/details/gtzxikiprr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.mhx1999.top/Article/details/gtaecxlzui.html

[C15] 解构 / 展开参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvlylfgdb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.feifeiyinyue.top/Article/details/gtbhyytrtj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cucudq.cn/Article/details/gtjnfcudtr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.0kj1m.cn/Article/details/gthltqbigd.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zycfv.cn/Article/details/gtbjhwgpml.html

Java: // 无解构
来源：http://dali.jqgfzy.top/Article/details/gtarhvpyci.html

Go:   // 无解构
来源：http://dali.sxryk.cn/Article/details/gtygqwpsvm.html

Ruby: a, b = pair
来源：http://dali.cdnleiting.top/Article/details/gtcqcqfces.html

C#:   var (a, b) = pair;
来源：http://dali.yvedp.cn/Article/details/gtvmhiwnlz.html

[C16] 函数 / 方法重载
来源：http://dali.hysaishi.cn/Article/details/gtzpqptksd.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xziqi.cn/Article/details/gtpjwyxiox.html

PHP:  // 无重载
来源：http://dali.sxryk.cn/Article/details/gtqnnrvynf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.9152youxi.cn/Article/details/gtnxpcmbeu.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.nwbrower.top/Article/details/gtkebijbvm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jlsjyb.cn/Article/details/gtddfdrvlt.html

Go:   // 无重载：用不同函数名
来源：http://dali.hfpthk.cn/Article/details/gtxzbbppoe.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sweek.top/Article/details/gtawyvszvs.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaqqnuaci.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtljrssixk.html

D. 数组 / 列表 / 集合
来源：http://dali.shanyushiyangtech.top/Article/details/gtxhpqbjps.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtgyqednox.html

[D01] 创建数组 / 列表
来源：http://dali.316326.xyz/Article/details/gtxfrvyxfy.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ybcxt.top/Article/details/gtnlqzgarb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhixingplan.top/Article/details/gttmejbtss.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yongpay.top/Article/details/gtjhjwaylm.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yuxming.cn/Article/details/gtnvfivdoe.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yj20258888.top/Article/details/gtwekrnimr.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.sweek.top/Article/details/gtaqbjofas.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xziqi.cn/Article/details/gtuypshsxs.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hysaishi.cn/Article/details/gtqiukayvg.html

[D02] 追加元素到末尾
来源：http://dali.cqqwz.cn/Article/details/gtjeusrhnf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gzhubu.top/Article/details/gtqxuthuvd.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.fzhhl.top/Article/details/gtdosuelff.html

JS:   arr.push(4);
来源：http://dali.gogol.net.cn/Article/details/gtvaknhefu.html

TS:   arr.push(4);
来源：http://dali.316326.xyz/Article/details/gtszlktdpr.html

Java: list.add(4);
来源：http://dali.316326.xyz/Article/details/gtllltmkjx.html

Go:   arr = append(arr, 4)
来源：http://dali.snrcjt.cn/Article/details/gtzasxibxf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jqgfzy.top/Article/details/gtqlsypsta.html

C#:   list.Add(4);
来源：http://dali.yueranfly.top/Article/details/gtgmhzlzfk.html

[D03] 在指定位置插入元素
来源：http://dali.jiagoushi.top/Article/details/gttguzuddn.html

Py:   arr.insert(0, 0)
来源：http://dali.gzhubu.top/Article/details/gtknrnnbbe.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.tian-w.cn/Article/details/gtsnpsaicj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cqqwz.cn/Article/details/gtxlyhwbjv.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttlezdaju.html

Java: list.add(0, 0);
来源：http://dali.aizwys.cn/Article/details/gtiujmkqfw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.aibaodan.cn/Article/details/gtutitdpzv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hnxiangtu.top/Article/details/gtqewuksam.html

C#:   list.Insert(0, 0);
来源：http://dali.vqdsnc.cn/Article/details/gtpcfhoxuc.html

[D04] 删除元素
来源：http://dali.yongpay.top/Article/details/gtmelhnvoz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.mhx1999.top/Article/details/gtrpfrfkjf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sufxvd.cn/Article/details/gtipnujksk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yongpay.top/Article/details/gtbzoqunpe.html

TS:   arr.splice(0, 1);
来源：http://dali.daxiang520.top/Article/details/gtyvfhusql.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.c1oappe.top/Article/details/gtuinvuvbc.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ivvv.top/Article/details/gtktcgpluu.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.snrcjt.cn/Article/details/gtihhwkgid.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xuanzx.com/Article/details/gtezncjlyi.html

[D05] 访问与修改元素
来源：http://dali.yanxiufei.cn/Article/details/gthiviimen.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxuanxn.top/Article/details/gtpvwjsnae.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yueranfly.top/Article/details/gtqehluefi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtujydpafy.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.fzhhl.top/Article/details/gtcysooxlx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xylfe.cn/Article/details/gtdywfqgbz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cheryme.top/Article/details/gtpejdrlcr.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigufen.top/Article/details/gtbylgevav.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.snrcjt.cn/Article/details/gtujjupxmc.html

[D06] 数组长度
来源：http://dali.fzhhl.top/Article/details/gtgcqsylxt.html

Py:   len(arr)
来源：http://dali.chenzaomai.com/Article/details/gtiesdspkb.html

PHP:  count($arr);
来源：http://dali.0kj1m.cn/Article/details/gttheemaey.html

JS:   arr.length
来源：http://dali.quarkkingdee.top/Article/details/gteqwoghhx.html

TS:   arr.length
来源：http://dali.xylfe.cn/Article/details/gtktdkcqhw.html

Java: list.size();
来源：http://dali.jyoumei.cn/Article/details/gtbeorswcb.html

Go:   len(arr)
来源：http://dali.ybcxt.top/Article/details/gtnbfiqbpz.html

Ruby: arr.length; arr.size
来源：http://dali.haohaochexian.top/Article/details/gtratrvqvj.html

C#:   list.Count;
来源：http://dali.yj202588.top/Article/details/gtljiwsjpk.html

[D07] 切片 / 取子数组
来源：http://dali.nanxinkj.top/Article/details/gtnnaosegz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shangyingyoupin.top/Article/details/gtdjvsston.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cdnleiting.top/Article/details/gtzfmwljmm.html

JS:   arr.slice(1, 4);
来源：http://dali.yangfankeji.com/Article/details/gtbxngqhso.html

TS:   arr.slice(1, 4);
来源：http://dali.havefunace.top/Article/details/gtcnlqdmsu.html

Java: list.subList(1, 4);
来源：http://dali.cheryme.top/Article/details/gtrwbhuvpn.html

Go:   arr[1:4]
来源：http://dali.nanxinkj.top/Article/details/gtomnittte.html

Ruby: arr[1, 3]
来源：http://dali.yj20258888.top/Article/details/gtxhuqtblz.html

C#:   list.GetRange(1, 3);
来源：http://dali.snrcjt.cn/Article/details/gtjwpemspw.html

[D08] 合并两个数组
来源：http://dali.ybcxt.top/Article/details/gtnllzfdrv.html

Py:   a + b;  a.extend(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdpeyhcyw.html

PHP:  array_merge($a, $b);
来源：http://dali.snrcjt.cn/Article/details/gtiptvhyax.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xylfe.cn/Article/details/gtsfcoetms.html

TS:   [...a, ...b];
来源：http://dali.daria6918.cn/Article/details/gtptrpfqbv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hysaishi.cn/Article/details/gthawtxsrq.html

Go:   append(a, b...)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzgxtoukz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gtlcvafrer.html

C#:   a.Concat(b).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gttmebeagj.html

[D09] 排序（升序）
来源：http://dali.cdnleiting.top/Article/details/gtpmyuuffo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenlongwang.top/Article/details/gtvukmsvzt.html

PHP:  sort($arr);
来源：http://dali.fzhhl.top/Article/details/gtiadsiinz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jyoumei.cn/Article/details/gttmpapjsu.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.tanke756.top/Article/details/gtrbyshtec.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenjidiqi.icu/Article/details/gtrqdckfov.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.fengsongda.top/Article/details/gtvbcxeymi.html

Ruby: arr.sort
来源：http://dali.xylfe.cn/Article/details/gtwywkhono.html

C#:   list.Sort();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpohsxtvj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xinyue.icu/Article/details/gtdsuiuzpr.html


<!-- 参考信息 -->