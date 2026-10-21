代发 wailian999

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuetiantiany.cn/Article/details/gtgjgbrwfl.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ivvv.top/Article/details/gtnbicggya.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yvedp.cn/Article/details/gthfsjoatw.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.wangdashe.top/Article/details/gtkjaejbxt.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.andypj.xyz/Article/details/gtcxixyacd.html

[B10] 遍历同时拿索引
来源：http://dali.zhoulong.xyz/Article/details/gtojtkuvmx.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.vqdsnc.cn/Article/details/gthoxfzhun.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.nanxuanxn.top/Article/details/gtfyicnfcr.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.cashguo.top/Article/details/gtjoaokefq.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yj202588.top/Article/details/gtqgkerwov.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.tian-w.cn/Article/details/gthhbhxxup.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.0kj1m.cn/Article/details/gtxzuxwslg.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.birdmap.top/Article/details/gtgkiubzuv.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhiwuduotai.top/Article/details/gtnafukhwa.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhixingplan.top/Article/details/gtdcjzsagf.html

Py:   list(range(0, 10, 2))
来源：http://dali.yj202588.top/Article/details/gtkscgpudp.html

PHP:  range(0, 10, 2);
来源：http://dali.shzxlz.cn/Article/details/gtiaaxprai.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tianlin.xyz/Article/details/gtpucpgofz.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.aizwys.cn/Article/details/gtmsyuklns.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.fzhhl.top/Article/details/gtfvkaxmfd.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.fengsongda.top/Article/details/gtgjkqeyio.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinghuilouyu.cn/Article/details/gtiyivrbaw.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.fengsongda.top/Article/details/gtgygpqyhm.html

[B12] 跳出多层循环
来源：http://dali.quarkkingdee.top/Article/details/gtbgjkxksx.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.havefunace.top/Article/details/gtddxwswqq.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.chenzaomai.com/Article/details/gtjvutahxs.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shangyingyoupin.top/Article/details/gtyaykoqjl.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgufenzy.top/Article/details/gtnhqvreab.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.daria6918.cn/Article/details/gthhnnmldl.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.pengpengdd.cyou/Article/details/gtnizlcivn.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.wangdashe.top/Article/details/gtlqwmmnwm.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.nwbrower.top/Article/details/gtmkdzsxhq.html

[B13] 判断是否为数字
来源：http://dali.gogol.net.cn/Article/details/gtxamujkxj.html

Py:   isinstance(x, (int, float))
来源：http://dali.yuanzhike.top/Article/details/gtlxtcqowd.html

PHP:  is_numeric($x)
来源：http://dali.fengsongda.top/Article/details/gteemmispk.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtszcprhvg.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.svipenyu.cn/Article/details/gtvcusbrkp.html

Java: x instanceof Number
来源：http://dali.yj20258.top/Article/details/gtqtshgbnc.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.sweek.top/Article/details/gtsykpdqjv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.snrcjt.cn/Article/details/gtfzieooro.html

C#:   x is int or double or decimal
来源：http://dali.chenjidiqi.icu/Article/details/gtvviukykk.html

[B14] 判断值是否在集合内
来源：http://dali.aibaodan.cn/Article/details/gtulvtxawx.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jqgufenzy.top/Article/details/gtnvcflllh.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hfpthk.cn/Article/details/gtnuyzhsvo.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ybcxt.top/Article/details/gtipdtutfe.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.tianlin.xyz/Article/details/gtqnfjioyw.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yonumen.top/Article/details/gtsvgtpkdz.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.aizwys.cn/Article/details/gtxdghmwpk.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.kuanghao11.cn/Article/details/gtcywonfga.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gtmaronejt.html

[B15] 布尔运算与取反
来源：http://dali.aizwys.cn/Article/details/gtlbkwefux.html

Py:   a and b or not c
来源：http://dali.zhiwuduotai.top/Article/details/gtztigbkvc.html

PHP:  $a && $b || !$c
来源：http://dali.xylfe.cn/Article/details/gttwjkpbof.html

JS:   a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gtdhgptxou.html

TS:   a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gthwtqjihb.html

Java: a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gtfnlvwusz.html

Go:   a && b || !c
来源：http://dali.ybcxt.top/Article/details/gtiljfpdhh.html

Ruby: a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gtlcwqfdfd.html

C#:   a && b || !c
来源：http://dali.cheryme.top/Article/details/gtntipvxur.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hongshengwenyu.top/Article/details/gtbiljrlxp.html

Py:   if not data: return
来源：http://dali.tian-w.cn/Article/details/gtjctgjgkw.html

PHP:  if (!$data) { return; }
来源：http://dali.aizwys.cn/Article/details/gtzwnyzvsh.html

JS:   if (!data) return;
来源：http://dali.zdqjudy.top/Article/details/gtiqkkhmbq.html

TS:   if (!data) return;
来源：http://dali.cheryme.top/Article/details/gtdhkoirvr.html

Java: if (data == null) return;
来源：http://dali.meibo888.top/Article/details/gtsipzbfua.html

Go:   if data == nil { return }
来源：http://dali.jianghu66.top/Article/details/gtjnroojch.html

Ruby: return if data.nil?
来源：http://dali.yuanzhike.top/Article/details/gtbxzefpry.html

C#:   if (data == null) return;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmdwewyul.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtdtwtbiot.html

C. 函数与作用域
来源：http://dali.yonumen.top/Article/details/gtwpbbghjw.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtipcdambq.html

[C01] 定义函数
来源：http://dali.shangyingyoupin.top/Article/details/gtqxneqwvv.html

Py:   def add(a, b): return a + b
来源：http://dali.jqgfzy.top/Article/details/gtscewxixi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtfxiampmb.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtekzagohj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtwtxnhwlq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gteiwhpfua.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hammf.cn/Article/details/gtsibxggpj.html

Ruby: def add(a, b); a + b; end
来源：http://dali.nanxuanxn.top/Article/details/gtyaezdusp.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gtsopvrmgw.html

[C02] 默认参数
来源：http://dali.shuidangran.top/Article/details/gtysoygnta.html

Py:   def greet(name="World"): return name
来源：http://dali.ppjwa.cn/Article/details/gtwdcwfqkw.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtflmkiyiw.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ppjwa.cn/Article/details/gtarhyidzr.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hysaishi.cn/Article/details/gtozhyxoed.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hongshengwenyu.top/Article/details/gtthtkxcnn.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zycfv.cn/Article/details/gtmmhctjwt.html

Ruby: def greet(name = "World") = name
来源：http://dali.yuxming.cn/Article/details/gtxjntpqfh.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.kuanghao11.cn/Article/details/gtiifgbmvg.html

[C03] 可变参数
来源：http://dali.bjfxy.top/Article/details/gtkdvyrudg.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhiwuduotai.top/Article/details/gtbwwlnhky.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.daxiang520.top/Article/details/gtzqpcalhj.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gogol.net.cn/Article/details/gtqpziqbvd.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhiwuduotai.top/Article/details/gtlanvsrqi.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.mhx1999.top/Article/details/gtccqgypok.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hysaishi.cn/Article/details/gtiyumzjem.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yuanzhike.top/Article/details/gtrukwjkhh.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jiagoushi.top/Article/details/gtlsphyhzx.html

[C04] 命名参数 / 关键字参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxyhtyhqy.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhongyouzk.top/Article/details/gtfdjanlot.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.aibaodan.cn/Article/details/gtpkbtdqmm.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cheryme.top/Article/details/gtujdinwgm.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jianghu66.top/Article/details/gtbhpoupmo.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hnxiangtu.top/Article/details/gthtuqnqhx.html

Go:   // 无：用配置结构体参数
来源：http://dali.yanxiufei.cn/Article/details/gtwoexrnih.html

Ruby: f(a: 1, b: 2)
来源：http://dali.vqdsnc.cn/Article/details/gtwgvywkrs.html

C#:   f(a: 1, b: 2)
来源：http://dali.iojbl.cn/Article/details/gttbeqiniu.html

[C05] 返回多个值
来源：http://dali.hammf.cn/Article/details/gtgaykxyxk.html

Py:   return a, b
来源：http://dali.yvedp.cn/Article/details/gtxtkmftbj.html

PHP:  return [$a, $b];
来源：http://dali.nwbrower.top/Article/details/gtkkwvjpdx.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.haohaochexian.top/Article/details/gtampzhpzn.html

TS:   return { a, b };
来源：http://dali.fengsongda.top/Article/details/gtpjnutvsi.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.chenlongwang.top/Article/details/gtlpgtcwmu.html

Go:   return a, b
来源：http://dali.ppjwa.cn/Article/details/gtylkgywlg.html

Ruby: return a, b
来源：http://dali.yongpay.top/Article/details/gtncbshmdw.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yvedp.cn/Article/details/gttkgubgsh.html

[C06] 匿名函数 / lambda
来源：http://dali.andypj.xyz/Article/details/gtoxsuukmk.html

Py:   square = lambda x: x * x
来源：http://dali.pengpengdd.cyou/Article/details/gtthnemeoe.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.fzhhl.top/Article/details/gtoeowhnzb.html

JS:   const square = x => x * x;
来源：http://dali.jiagoushi.top/Article/details/gtrswnuaxd.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhiwuduotai.top/Article/details/gtvswypjfa.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.quarkkingdee.top/Article/details/gtwepnfesl.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jyoumei.cn/Article/details/gtiquuumbs.html

Ruby: square = ->(x) { x * x }
来源：http://dali.sweek.top/Article/details/gtiweescgv.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.daxiang520.top/Article/details/gtgnsxjfvs.html

[C07] 把函数作为参数传入
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsyytcyvf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shangyingyoupin.top/Article/details/gtpeovmjaq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.havefunace.top/Article/details/gthopeleoh.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zycfv.cn/Article/details/gtsxfjchhj.html

TS:   arr.map(String)
来源：http://dali.jqgufenzy.top/Article/details/gtidjyidod.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.dashuyun.cn/Article/details/gtmoxvacos.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfxwomqzs.html

Ruby: arr.map(&:upcase)
来源：http://dali.gzhubu.top/Article/details/gtwwtmnjbh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.nanxuanxn.top/Article/details/gtoikovtvm.html

[C08] 闭包
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmvwxpmpd.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.sxryk.cn/Article/details/gtstlfsfuw.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yuxming.cn/Article/details/gtjoybtbvq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.daria6918.cn/Article/details/gtqfzwqqhl.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.iojbl.cn/Article/details/gtxegajkja.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yuanzhike.top/Article/details/gtdixwnpdj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.nwbrower.top/Article/details/gtxiqedgfn.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hfpthk.cn/Article/details/gtppxzbrss.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gzhubu.top/Article/details/gtqukfnroh.html

[C09] 递归
来源：http://dali.hnqzz.top/Article/details/gttfoxhgzg.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtqqflqvqf.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.sweek.top/Article/details/gtevuyxywg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jyoumei.cn/Article/details/gtvbshdscv.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zycfv.cn/Article/details/gtebuwvcdt.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.chenlongwang.top/Article/details/gtlicaifff.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ybcxt.top/Article/details/gtwnfiggll.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.nanxinkj.top/Article/details/gtfdgutlag.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.birdmap.top/Article/details/gtcpghvjie.html

[C10] 变量作用域
来源：http://dali.ydzc1.top/Article/details/gtsbzkphcu.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gzhubu.top/Article/details/gtyrrjheul.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhengqikj.top/Article/details/gtqhunlnyb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.nwbrower.top/Article/details/gtkfpuifoa.html

TS:   同 JS
来源：http://dali.gogol.net.cn/Article/details/gtkslqqsqb.html

Java: 方法内为块级作用域
来源：http://dali.chenlongwang.top/Article/details/gtojblrylh.html

Go:   花括号块级作用域
来源：http://dali.birdmap.top/Article/details/gtticbmjjc.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shuidangran.top/Article/details/gtiebkqhsi.html

C#:   块级作用域
来源：http://dali.vqdsnc.cn/Article/details/gtfrvhpneu.html

[C11] 模块导入与导出
来源：http://dali.jinyuanbaomall.cn/Article/details/gtceqtghbf.html

Py:   from module import func
来源：http://dali.iojbl.cn/Article/details/gtiowjwbpx.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhengqikj.top/Article/details/gtkdsixlfx.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.iojbl.cn/Article/details/gtiwnnhedl.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cashguo.top/Article/details/gtxrzyuobv.html

Java: import java.util.List;
来源：http://dali.fzhhl.top/Article/details/gtstuxfcge.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.gogol.net.cn/Article/details/gtpeaqdwiv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhiwuduotai.top/Article/details/gtnepwrdgq.html

C#:   using System.Text;
来源：http://dali.zhoulong.xyz/Article/details/gtwpfxaoly.html

[C12] 立即执行函数 IIFE
来源：http://dali.316326.xyz/Article/details/gtyolzbcka.html

Py:   (lambda: print("run"))()
来源：http://dali.xylfe.cn/Article/details/gthjnukhjh.html

PHP:  (function () { echo "run"; })();
来源：http://dali.aizwys.cn/Article/details/gtkcdlfrip.html

JS:   (() => { console.log("run"); })();
来源：http://dali.meibo888.top/Article/details/gteldbzkjm.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hywenlv.cn/Article/details/gtdwrmcwss.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ydzc1.top/Article/details/gtrrjnqqwp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhengqikj.top/Article/details/gtnbahdgxo.html

Ruby: -> { puts "run" }.call
来源：http://dali.yangfankeji.com/Article/details/gtxlcxrpsi.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cdnleiting.top/Article/details/gtcrvfwmid.html

[C13] 类型声明 / 类型注解
来源：http://dali.meibo888.top/Article/details/gtrlegqsph.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ehwqpu.com/Article/details/gttcyygoyj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yvedp.cn/Article/details/gtkubhxmur.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtveshsnew.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gtnadtezxo.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gtsprslfao.html

Go:   func add(a, b int) int
来源：http://dali.zhaomingkeji.xyz/Article/details/gthpbkjohl.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gogol.net.cn/Article/details/gtmiqedvxv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.smart0.xyz/Article/details/gtcufcmiis.html

[C14] 泛型函数
来源：http://dali.jiagoushi.top/Article/details/gtakfucvbn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.svipenyu.cn/Article/details/gtopmszurq.html

PHP:  // 无泛型
来源：http://dali.ehwqpu.com/Article/details/gtpsxrnzhi.html

JS:   // 无泛型
来源：http://dali.xinyue.icu/Article/details/gtqnrgrgzp.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yueranfly.top/Article/details/gtrenekcmr.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hammf.cn/Article/details/gttuqvbpge.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xuanzx.com/Article/details/gtciatewhf.html

Ruby: # 无泛型
来源：http://dali.sxryk.cn/Article/details/gtbxjldzsm.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zycfv.cn/Article/details/gtxybguzny.html

[C15] 解构 / 展开参数
来源：http://dali.jinqigfzy.top/Article/details/gtwchkjqqr.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhongyouzk.top/Article/details/gtnbvltejp.html

PHP:  [$a, $b] = $pair;
来源：http://dali.nanxinkj.top/Article/details/gtpjrxhsov.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jinqigufen.top/Article/details/gtddwwwvgn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yonumen.top/Article/details/gtpifkycen.html

Java: // 无解构
来源：http://dali.fengsongda.top/Article/details/gtjlobegzx.html

Go:   // 无解构
来源：http://dali.sufxvd.cn/Article/details/gtgfyfgznt.html

Ruby: a, b = pair
来源：http://dali.sysykeji.top/Article/details/gtaxgpbumz.html

C#:   var (a, b) = pair;
来源：http://dali.cqqwz.cn/Article/details/gtpjqdiwyo.html

[C16] 函数 / 方法重载
来源：http://dali.jinghuilouyu.cn/Article/details/gtwopmnhoq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.dianchejie.cn/Article/details/gtmktzhkvp.html

PHP:  // 无重载
来源：http://dali.0kj1m.cn/Article/details/gtrotpbhty.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.meibo888.top/Article/details/gtgqwkruys.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.svipenyu.cn/Article/details/gtwynbsvnf.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hnxiangtu.top/Article/details/gtnbwwdwtf.html

Go:   // 无重载：用不同函数名
来源：http://dali.guowangkeji.top/Article/details/gtzujnadgp.html

Ruby: # 无重载：靠动态参数
来源：http://dali.316326.xyz/Article/details/gtwgnzvikw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yj20258888.top/Article/details/gtguezbqyw.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtpveuwacz.html

D. 数组 / 列表 / 集合
来源：http://dali.pycfn.com/Article/details/gtqccuizjm.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtyuwelfcc.html

[D01] 创建数组 / 列表
来源：http://dali.nanxinkj.top/Article/details/gteyrgjrov.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jqgfzy.top/Article/details/gtalzhruij.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.nanxinkj.top/Article/details/gtvvqkauqg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.316326.xyz/Article/details/gtogsngpsy.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.chenzaomai.com/Article/details/gtdcnyuuym.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.pengpengdd.cyou/Article/details/gtftjazawk.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yj202588.top/Article/details/gtsjgsjsna.html

Ruby: arr = [1, 2, 3]
来源：http://dali.haohaochexian.top/Article/details/gtvpovdggf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yuxming.cn/Article/details/gtkdktvejm.html

[D02] 追加元素到末尾
来源：http://dali.yj202588.top/Article/details/gtughjrynf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hysaishi.cn/Article/details/gtuklckxbf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.pycfn.com/Article/details/gtfvhqssni.html

JS:   arr.push(4);
来源：http://dali.chenlongwang.top/Article/details/gtlnzwzbfu.html

TS:   arr.push(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtaagmllwy.html

Java: list.add(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbsnnkakt.html

Go:   arr = append(arr, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfrqepkvc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gtzbmtzuya.html

C#:   list.Add(4);
来源：http://dali.sysykeji.top/Article/details/gtpybehvcv.html

[D03] 在指定位置插入元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnetegnhl.html

Py:   arr.insert(0, 0)
来源：http://dali.jiagoushi.top/Article/details/gtxcjawjia.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.wangdashe.top/Article/details/gtohgwuoeh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.wangshuangyany.cn/Article/details/gtxsqvcpqh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yueranfly.top/Article/details/gtlwimvgqd.html

Java: list.add(0, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmlokxvxc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sysykeji.top/Article/details/gtvxjwenxe.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ydzc1.top/Article/details/gtzlvighcj.html

C#:   list.Insert(0, 0);
来源：http://dali.chenzaomai.com/Article/details/gtrigxmyto.html

[D04] 删除元素
来源：http://dali.c1oappe.top/Article/details/gttfpmzejg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhixingplan.top/Article/details/gtbsconklg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.snrcjt.cn/Article/details/gtcvnkapzw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yuanzhike.top/Article/details/gtvafxyzba.html

TS:   arr.splice(0, 1);
来源：http://dali.vqdsnc.cn/Article/details/gtmihumbdc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yj20258.top/Article/details/gtspvfnpht.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.sufxvd.cn/Article/details/gtgwppltwf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cashguo.top/Article/details/gtpgdxkvou.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.dashuyun.cn/Article/details/gtsfzorycp.html

[D05] 访问与修改元素
来源：http://dali.haohaochexian.top/Article/details/gtejpmilhj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yangfankeji.com/Article/details/gtpzemkmim.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yanxiufei.cn/Article/details/gtihuvjtzg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.redwolf501.top/Article/details/gtwbavnkup.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.pycfn.com/Article/details/gttnpxrexp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sweek.top/Article/details/gtovqohpka.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yuxming.cn/Article/details/gtzhohlumq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yangfankeji.com/Article/details/gtkfkcvnks.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zdqjudy.top/Article/details/gtnwyhrudc.html

[D06] 数组长度
来源：http://dali.shangyingyoupin.top/Article/details/gtszzpaarw.html

Py:   len(arr)
来源：http://dali.guowangkeji.top/Article/details/gtrpjrugmo.html

PHP:  count($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtxsqniqxv.html

JS:   arr.length
来源：http://dali.jiagoushi.top/Article/details/gtqcbwpvzo.html

TS:   arr.length
来源：http://dali.tian-w.cn/Article/details/gtjctyqpks.html

Java: list.size();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgjrggkao.html

Go:   len(arr)
来源：http://dali.wangdashe.top/Article/details/gtlztopunh.html

Ruby: arr.length; arr.size
来源：http://dali.xinyue.icu/Article/details/gtbfoywkve.html

C#:   list.Count;
来源：http://dali.svipenyu.cn/Article/details/gtxmtnvear.html

[D07] 切片 / 取子数组
来源：http://dali.tianlin.xyz/Article/details/gtxktqeqlk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.tanke756.top/Article/details/gthzffsiqg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cucudq.cn/Article/details/gtvmgiyqsk.html

JS:   arr.slice(1, 4);
来源：http://dali.ppjwa.cn/Article/details/gtobjlehel.html

TS:   arr.slice(1, 4);
来源：http://dali.hnxiangtu.top/Article/details/gtozxxspzo.html

Java: list.subList(1, 4);
来源：http://dali.redwolf501.top/Article/details/gtkifiyrvi.html

Go:   arr[1:4]
来源：http://dali.yuanzhike.top/Article/details/gtsloahtha.html

Ruby: arr[1, 3]
来源：http://dali.xuanzx.com/Article/details/gtatkiffor.html

C#:   list.GetRange(1, 3);
来源：http://dali.yj20258.top/Article/details/gtkqudheqq.html

[D08] 合并两个数组
来源：http://dali.sxryk.cn/Article/details/gttvxgjqmx.html

Py:   a + b;  a.extend(b)
来源：http://dali.smart0.xyz/Article/details/gtbshcefrj.html

PHP:  array_merge($a, $b);
来源：http://dali.jiagoushi.top/Article/details/gtkmyeggna.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.aizwys.cn/Article/details/gtkbesonpj.html

TS:   [...a, ...b];
来源：http://dali.zhiwuduotai.top/Article/details/gtereooazj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhengqikj.top/Article/details/gtkrxvgxba.html

Go:   append(a, b...)
来源：http://dali.guannengcc.top/Article/details/gtcnjzqwfh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.chenlongwang.top/Article/details/gtochmxyoi.html

C#:   a.Concat(b).ToList()
来源：http://dali.tianlin.xyz/Article/details/gtkqdgxwgc.html

[D09] 排序（升序）
来源：http://dali.gaohongyu789.top/Article/details/gtwszzetks.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhongyouzk.top/Article/details/gtlfadasym.html

PHP:  sort($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtbxahholg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.nwbrower.top/Article/details/gtkqkzvejx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jianghu66.top/Article/details/gtqwarlwng.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cdnleiting.top/Article/details/gtqpimvtno.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhixingplan.top/Article/details/gtuuoplckv.html

Ruby: arr.sort
来源：http://dali.316326.xyz/Article/details/gteepcsfsc.html

C#:   list.Sort();
来源：http://dali.hywenlv.cn/Article/details/gtsudjmnap.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhongyouzk.top/Article/details/gtlksdwzcr.html


<!-- 参考信息 -->