代发 wailian999

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigfzy.top/Article/details/gtcmtzrdxz.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cucudq.cn/Article/details/gtkwpkywfr.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jinqigufen.top/Article/details/gtpheenued.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jinqigufen.top/Article/details/gthsqavgtx.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tianlin.xyz/Article/details/gtnhpudgir.html

[B10] 遍历同时拿索引
来源：http://dali.quarkkingdee.top/Article/details/gtylkrdqao.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hammf.cn/Article/details/gtmcyoiotg.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.tanke756.top/Article/details/gtyhtoajyc.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jianghu66.top/Article/details/gtqqhctdew.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.vqdsnc.cn/Article/details/gtidqyuvpz.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.9152youxi.cn/Article/details/gttpsmsavs.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hfpthk.cn/Article/details/gtdhumvoym.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.9152youxi.cn/Article/details/gtpnnzhawc.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.gotoacloud.top/Article/details/gtiiergmmp.html

[B11] 生成数字序列 / 区间
来源：http://dali.birdmap.top/Article/details/gtgyjedhmx.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjlcjurdq.html

PHP:  range(0, 10, 2);
来源：http://dali.tianlin.xyz/Article/details/gtyxdfwhbm.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nanxinkj.top/Article/details/gtpxmhwjvj.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tanke756.top/Article/details/gtgxybfjal.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yuxming.cn/Article/details/gtahrqbpdl.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.nanxuanxn.top/Article/details/gthsmvemxa.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zdqjudy.top/Article/details/gtdimvwtcd.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hnqzz.top/Article/details/gtcarcfykx.html

[B12] 跳出多层循环
来源：http://dali.tianlin.xyz/Article/details/gtibcxbdcc.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.quarkkingdee.top/Article/details/gtonjwofvh.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jqgfzy.top/Article/details/gtknuyqbag.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sxryk.cn/Article/details/gtasnpzfen.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yvedp.cn/Article/details/gtegmnkiep.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.shzxlz.cn/Article/details/gtmfkxojio.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jinqigfzy.top/Article/details/gttmelgwev.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfwzdedvo.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.cqqwz.cn/Article/details/gtnirwowje.html

[B13] 判断是否为数字
来源：http://dali.xuanzx.com/Article/details/gtvlwtjexa.html

Py:   isinstance(x, (int, float))
来源：http://dali.yuanzhike.top/Article/details/gtlhtiibch.html

PHP:  is_numeric($x)
来源：http://dali.jqgfzy.top/Article/details/gtdlolfaau.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.smart0.xyz/Article/details/gtbiqkvybc.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zdqjudy.top/Article/details/gtdtbixsmc.html

Java: x instanceof Number
来源：http://dali.hfpthk.cn/Article/details/gtpgpkhhks.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gtmokwacah.html

Ruby: x.is_a?(Numeric)
来源：http://dali.tian-w.cn/Article/details/gtrymotniz.html

C#:   x is int or double or decimal
来源：http://dali.tian-w.cn/Article/details/gtbpwswhll.html

[B14] 判断值是否在集合内
来源：http://dali.hywenlv.cn/Article/details/gtkmhlxnue.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.9152youxi.cn/Article/details/gtchlkdbvf.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.nanxuanxn.top/Article/details/gtunczjhdz.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cucudq.cn/Article/details/gtocdcxfej.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jinqigufen.top/Article/details/gtbniuvqxd.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jqgfzy.top/Article/details/gtthwtpmpg.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhoulong.xyz/Article/details/gtcrkmqips.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.0kj1m.cn/Article/details/gtearqdmnc.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hfpthk.cn/Article/details/gtbhjxyrwt.html

[B15] 布尔运算与取反
来源：http://dali.chenlongwang.top/Article/details/gtritjgaft.html

Py:   a and b or not c
来源：http://dali.yj202588.top/Article/details/gtybdkpvfw.html

PHP:  $a && $b || !$c
来源：http://dali.yj20258.top/Article/details/gtdluqddes.html

JS:   a && b || !c
来源：http://dali.ivvv.top/Article/details/gtzkqfgrkz.html

TS:   a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtddodrfqk.html

Java: a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gtshanqjgh.html

Go:   a && b || !c
来源：http://dali.sxryk.cn/Article/details/gtleogifbv.html

Ruby: a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gtmaesnlei.html

C#:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gtdfkawolv.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ybcxt.top/Article/details/gtlhryelqt.html

Py:   if not data: return
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiffybwiy.html

PHP:  if (!$data) { return; }
来源：http://dali.shangyingyoupin.top/Article/details/gtltrgxlox.html

JS:   if (!data) return;
来源：http://dali.316326.xyz/Article/details/gtszgtgewr.html

TS:   if (!data) return;
来源：http://dali.ppjwa.cn/Article/details/gtowldtdiq.html

Java: if (data == null) return;
来源：http://dali.zhiwuduotai.top/Article/details/gttkebfscs.html

Go:   if data == nil { return }
来源：http://dali.jianghu66.top/Article/details/gtpwwmazig.html

Ruby: return if data.nil?
来源：http://dali.redwolf501.top/Article/details/gthcqzbapn.html

C#:   if (data == null) return;
来源：http://dali.quarkkingdee.top/Article/details/gtwbhkwizq.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtmammjplq.html

C. 函数与作用域
来源：http://dali.ydzc1.top/Article/details/gtydihtntu.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtcdqkccoz.html

[C01] 定义函数
来源：http://dali.nwbrower.top/Article/details/gtdwkoealu.html

Py:   def add(a, b): return a + b
来源：http://dali.gzhubu.top/Article/details/gtmlcsukkz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuanzx.com/Article/details/gtdwumtxqh.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gthhqeethy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gtaltbfxqv.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gtwsiahlwk.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.pycfn.com/Article/details/gtsykppzws.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xziqi.cn/Article/details/gtkaywijgq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtvzfjengl.html

[C02] 默认参数
来源：http://dali.sufxvd.cn/Article/details/gtzqoxpugy.html

Py:   def greet(name="World"): return name
来源：http://dali.hammf.cn/Article/details/gtxrdrkfcx.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yonumen.top/Article/details/gttfppkped.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.aizwys.cn/Article/details/gttpzugmql.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtdyakypck.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.mhx1999.top/Article/details/gtwrfrphvw.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsfosthrz.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhiwuduotai.top/Article/details/gtyuhasizu.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jyoumei.cn/Article/details/gtvezmgspy.html

[C03] 可变参数
来源：http://dali.cheryme.top/Article/details/gtiewoigve.html

Py:   def total(*args): return sum(args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiqkbnpzo.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.pengpengdd.cyou/Article/details/gtgdreorbe.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.wangshuangyany.cn/Article/details/gttlxiawzj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ehwqpu.com/Article/details/gtiwjiuaas.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jianghu66.top/Article/details/gtowbdcanz.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.316326.xyz/Article/details/gtnsydgpzr.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hnxiangtu.top/Article/details/gtgrltvkxn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yvedp.cn/Article/details/gtxgdmwyzm.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhoulong.xyz/Article/details/gtweagfqpj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrsfkxgta.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtwzurgtlh.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zycfv.cn/Article/details/gthlqqwghj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.gogol.net.cn/Article/details/gtrpmkvihm.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.316326.xyz/Article/details/gtlnpkjnqb.html

Go:   // 无：用配置结构体参数
来源：http://dali.0kj1m.cn/Article/details/gtohputcfl.html

Ruby: f(a: 1, b: 2)
来源：http://dali.chenzaomai.com/Article/details/gtcwmiofra.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhoulong.xyz/Article/details/gtpjqqwhqz.html

[C05] 返回多个值
来源：http://dali.shzxlz.cn/Article/details/gtypnzkase.html

Py:   return a, b
来源：http://dali.hongshengwenyu.top/Article/details/gtfbmcyoxq.html

PHP:  return [$a, $b];
来源：http://dali.jinqigufen.top/Article/details/gtzmjevctj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yj20258.top/Article/details/gtfqjdslzn.html

TS:   return { a, b };
来源：http://dali.pengpengdd.cyou/Article/details/gtlnnvraud.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ppjwa.cn/Article/details/gtviafsxwd.html

Go:   return a, b
来源：http://dali.havefunace.top/Article/details/gtxqqroyxl.html

Ruby: return a, b
来源：http://dali.nwbrower.top/Article/details/gtewrakvue.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yj20258.top/Article/details/gtqfatmkij.html

[C06] 匿名函数 / lambda
来源：http://dali.cqqwz.cn/Article/details/gtenxpeiat.html

Py:   square = lambda x: x * x
来源：http://dali.yongpay.top/Article/details/gtsxfzepsl.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.aizwys.cn/Article/details/gtrmxouyaj.html

JS:   const square = x => x * x;
来源：http://dali.dianchejie.cn/Article/details/gttzduholn.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yanxiufei.cn/Article/details/gtvxuvkrec.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zdqjudy.top/Article/details/gtwvjtuzbg.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yj20258.top/Article/details/gtizcfauvj.html

Ruby: square = ->(x) { x * x }
来源：http://dali.gogol.net.cn/Article/details/gtjusslmwy.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.aizwys.cn/Article/details/gtdrahlxhd.html

[C07] 把函数作为参数传入
来源：http://dali.chenjidiqi.icu/Article/details/gtcfzneeov.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmmxnfkdk.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.316326.xyz/Article/details/gtzboxmvxu.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.wangdashe.top/Article/details/gtdbksspum.html

TS:   arr.map(String)
来源：http://dali.cqqwz.cn/Article/details/gtnbfdxnbr.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yuanzhike.top/Article/details/gtzbmsjkkx.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.chenzaomai.com/Article/details/gttishvdgq.html

Ruby: arr.map(&:upcase)
来源：http://dali.tianlin.xyz/Article/details/gtmhefmcdk.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xinyue.icu/Article/details/gtszrhmrky.html

[C08] 闭包
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqsxlazbu.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cheryme.top/Article/details/gtpcfefzvo.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xziqi.cn/Article/details/gthtfcazwt.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.smart0.xyz/Article/details/gtbliaeckv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yuanzhike.top/Article/details/gtlodbllpw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhongyouzk.top/Article/details/gtmcmkvcur.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqhchfasv.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhoulong.xyz/Article/details/gtwukhexuj.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yj20258888.top/Article/details/gtrhspncov.html

[C09] 递归
来源：http://dali.hywenlv.cn/Article/details/gtrteimass.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.smart0.xyz/Article/details/gtkvolgyql.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jlsjyb.cn/Article/details/gtnygbhjic.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhixingplan.top/Article/details/gtyddgurqk.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258888.top/Article/details/gtsmhlcpvn.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.guowangkeji.top/Article/details/gtvwiefuca.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ivvv.top/Article/details/gtjsuovfbf.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yuanzhike.top/Article/details/gtsaqpiwll.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.meibo888.top/Article/details/gtsgpmwxyx.html

[C10] 变量作用域
来源：http://dali.nanxinkj.top/Article/details/gtytqphcis.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.mhx1999.top/Article/details/gtmhpnuquy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.nanxuanxn.top/Article/details/gtfsveiugh.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.andypj.xyz/Article/details/gtynaonbqa.html

TS:   同 JS
来源：http://dali.316326.xyz/Article/details/gtiesfhuuv.html

Java: 方法内为块级作用域
来源：http://dali.quarkkingdee.top/Article/details/gtqlkjwuzm.html

Go:   花括号块级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqadqmky.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jianghu66.top/Article/details/gthnafihmp.html

C#:   块级作用域
来源：http://dali.snrcjt.cn/Article/details/gtinuikujn.html

[C11] 模块导入与导出
来源：http://dali.jinqigfzy.top/Article/details/gtfpygynzk.html

Py:   from module import func
来源：http://dali.daxiang520.top/Article/details/gtmmxumyoj.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.bjfxy.top/Article/details/gtarcpnvbn.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hnqzz.top/Article/details/gtvzjxwksg.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.316326.xyz/Article/details/gtfhskshpy.html

Java: import java.util.List;
来源：http://dali.cucudq.cn/Article/details/gtocmfgjvg.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cucudq.cn/Article/details/gthpzjimyr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cdnleiting.top/Article/details/gtszffzfor.html

C#:   using System.Text;
来源：http://dali.fzhhl.top/Article/details/gtdwnntuzy.html

[C12] 立即执行函数 IIFE
来源：http://dali.cashguo.top/Article/details/gtkjsidbzo.html

Py:   (lambda: print("run"))()
来源：http://dali.cashguo.top/Article/details/gtryrseoxv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hongshengwenyu.top/Article/details/gtqbdcqikz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yueranfly.top/Article/details/gtgfiitmjr.html

TS:   (() => { console.log("run"); })();
来源：http://dali.bjfxy.top/Article/details/gtkqqnwklv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xuanzx.com/Article/details/gtihyhmxuz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.mhx1999.top/Article/details/gttrppgjbl.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhiwuduotai.top/Article/details/gtiuzophwn.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.havefunace.top/Article/details/gtwroptdpi.html

[C13] 类型声明 / 类型注解
来源：http://dali.xylfe.cn/Article/details/gtvphbluez.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhiwuduotai.top/Article/details/gtuvzlvfox.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gtdaewmmby.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.vqdsnc.cn/Article/details/gtcstqoxod.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gtzwguogkg.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtunxirfgc.html

Go:   func add(a, b int) int
来源：http://dali.gotoacloud.top/Article/details/gtkopmjqkw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.bjfxy.top/Article/details/gtdwkqcwld.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.quarkkingdee.top/Article/details/gtgfjmpxlk.html

[C14] 泛型函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjkwfsiuj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jqgufenzy.top/Article/details/gtlesjhtnd.html

PHP:  // 无泛型
来源：http://dali.shuidangran.top/Article/details/gttrueiinn.html

JS:   // 无泛型
来源：http://dali.nanxinkj.top/Article/details/gtfaasnuwz.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ppjwa.cn/Article/details/gtvrofndqa.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gaohongyu789.top/Article/details/gtjfnuxsbc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhongyouzk.top/Article/details/gtrdxmqpbq.html

Ruby: # 无泛型
来源：http://dali.xziqi.cn/Article/details/gttdleuoih.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yuanzhike.top/Article/details/gtgoavcugl.html

[C15] 解构 / 展开参数
来源：http://dali.dashuyun.cn/Article/details/gtqayubpfj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gogol.net.cn/Article/details/gtbnlbvtxg.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hywenlv.cn/Article/details/gtkjpcjavd.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yonumen.top/Article/details/gtgfvcnqoj.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.daxiang520.top/Article/details/gtaxdlcqec.html

Java: // 无解构
来源：http://dali.0kj1m.cn/Article/details/gtpvznfcoa.html

Go:   // 无解构
来源：http://dali.zdqjudy.top/Article/details/gthtedzcht.html

Ruby: a, b = pair
来源：http://dali.gotoacloud.top/Article/details/gtortudkvl.html

C#:   var (a, b) = pair;
来源：http://dali.xylfe.cn/Article/details/gtmcnndfwd.html

[C16] 函数 / 方法重载
来源：http://dali.bjfxy.top/Article/details/gtwnqagqdb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xuetiantiany.cn/Article/details/gtudaboxhr.html

PHP:  // 无重载
来源：http://dali.shuidangran.top/Article/details/gtjldaxonf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.wangshuangyany.cn/Article/details/gtpnkvaxpc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hnxiangtu.top/Article/details/gtcyyrrotb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jqgfzy.top/Article/details/gtonkvsscb.html

Go:   // 无重载：用不同函数名
来源：http://dali.cashguo.top/Article/details/gtlosnftpa.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sweek.top/Article/details/gtvnejiwyv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.smart0.xyz/Article/details/gtloxnwuwe.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtvlusnqid.html

D. 数组 / 列表 / 集合
来源：http://dali.daria6918.cn/Article/details/gtmlnntejl.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtzhqdriqg.html

[D01] 创建数组 / 列表
来源：http://dali.sweek.top/Article/details/gtzjsqpbcq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj20258.top/Article/details/gttnmwemdy.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.daria6918.cn/Article/details/gtbmrtfbjp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cheryme.top/Article/details/gtimnfawko.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsewunuvy.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.sxryk.cn/Article/details/gtlnqkfqms.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.vqdsnc.cn/Article/details/gtgkatdrmf.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhiwuduotai.top/Article/details/gtujaonurc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.316326.xyz/Article/details/gtuyodoobx.html

[D02] 追加元素到末尾
来源：http://dali.redwolf501.top/Article/details/gtxjkrgxes.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.wangshuangyany.cn/Article/details/gttcufnmes.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yongpay.top/Article/details/gtovcoftom.html

JS:   arr.push(4);
来源：http://dali.cucudq.cn/Article/details/gtwtksjkwp.html

TS:   arr.push(4);
来源：http://dali.gzhubu.top/Article/details/gtveqrzhee.html

Java: list.add(4);
来源：http://dali.tian-w.cn/Article/details/gtfmadcawp.html

Go:   arr = append(arr, 4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtitxmpwkv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yanxiufei.cn/Article/details/gtpbrlrwpl.html

C#:   list.Add(4);
来源：http://dali.shangyingyoupin.top/Article/details/gtnpacgyhx.html

[D03] 在指定位置插入元素
来源：http://dali.chenlongwang.top/Article/details/gtagxkqjgl.html

Py:   arr.insert(0, 0)
来源：http://dali.gogol.net.cn/Article/details/gthtakzynt.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ivvv.top/Article/details/gtrtydcfrs.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.aizwys.cn/Article/details/gtprrtzhry.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.nwbrower.top/Article/details/gtnvcnqddi.html

Java: list.add(0, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtowtjbhun.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.tanke756.top/Article/details/gtyfgerrfq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cucudq.cn/Article/details/gtfwcetxcw.html

C#:   list.Insert(0, 0);
来源：http://dali.c1oappe.top/Article/details/gtrdfxdknh.html

[D04] 删除元素
来源：http://dali.bjfxy.top/Article/details/gtfakjbdfu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinqigfzy.top/Article/details/gtidzdqrai.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqtdvqkto.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hywenlv.cn/Article/details/gtkpgnraay.html

TS:   arr.splice(0, 1);
来源：http://dali.chenjidiqi.icu/Article/details/gtzpgjfiqn.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtjarebasx.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.guowangkeji.top/Article/details/gtreedfndd.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xziqi.cn/Article/details/gtmwouiruh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jlsjyb.cn/Article/details/gtkcafvkbm.html

[D05] 访问与修改元素
来源：http://dali.zhongyouzk.top/Article/details/gtwdbsprfd.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xziqi.cn/Article/details/gtotzjsota.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hnqzz.top/Article/details/gthdpzhfib.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.pycfn.com/Article/details/gtztvwqcww.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttxrfertw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jlsjyb.cn/Article/details/gtvminerwj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yonumen.top/Article/details/gtcoxsfzro.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.birdmap.top/Article/details/gtellwhegy.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cucudq.cn/Article/details/gtpgznypkv.html

[D06] 数组长度
来源：http://dali.cdnleiting.top/Article/details/gtlsywyrde.html

Py:   len(arr)
来源：http://dali.chenzaomai.com/Article/details/gtwfornvcp.html

PHP:  count($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtihgdhvhv.html

JS:   arr.length
来源：http://dali.jqgufenzy.top/Article/details/gtcvuteflt.html

TS:   arr.length
来源：http://dali.aizwys.cn/Article/details/gtwscxxyqq.html

Java: list.size();
来源：http://dali.redwolf501.top/Article/details/gtsofoyyrt.html

Go:   len(arr)
来源：http://dali.daria6918.cn/Article/details/gtuwvnvrtz.html

Ruby: arr.length; arr.size
来源：http://dali.chenzaomai.com/Article/details/gtbxcqrhgr.html

C#:   list.Count;
来源：http://dali.gotoacloud.top/Article/details/gtxfwxtorx.html

[D07] 切片 / 取子数组
来源：http://dali.c1oappe.top/Article/details/gtzbdefjli.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.fzhhl.top/Article/details/gtocdflgnw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdxelgngk.html

JS:   arr.slice(1, 4);
来源：http://dali.yongpay.top/Article/details/gtkxhkphkh.html

TS:   arr.slice(1, 4);
来源：http://dali.daria6918.cn/Article/details/gtrluvahem.html

Java: list.subList(1, 4);
来源：http://dali.yj20258888.top/Article/details/gtoewowxyo.html

Go:   arr[1:4]
来源：http://dali.wangdashe.top/Article/details/gtpmptduyp.html

Ruby: arr[1, 3]
来源：http://dali.shzxlz.cn/Article/details/gtxbvgjyha.html

C#:   list.GetRange(1, 3);
来源：http://dali.gaohongyu789.top/Article/details/gtzdgvnkig.html

[D08] 合并两个数组
来源：http://dali.gaohongyu789.top/Article/details/gtjknkdjlg.html

Py:   a + b;  a.extend(b)
来源：http://dali.andypj.xyz/Article/details/gtozzjelro.html

PHP:  array_merge($a, $b);
来源：http://dali.kuanghao11.cn/Article/details/gttsmgyxrr.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.gzhubu.top/Article/details/gtazzclcfr.html

TS:   [...a, ...b];
来源：http://dali.guowangkeji.top/Article/details/gtffworxhf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yanxiufei.cn/Article/details/gtccvelcqa.html

Go:   append(a, b...)
来源：http://dali.nwbrower.top/Article/details/gtfgwdtxrk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jqgufenzy.top/Article/details/gtwaoeexwe.html

C#:   a.Concat(b).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtduggiwhz.html

[D09] 排序（升序）
来源：http://dali.chenjidiqi.icu/Article/details/gttefrkpao.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ehwqpu.com/Article/details/gtfwgdowiu.html

PHP:  sort($arr);
来源：http://dali.gogol.net.cn/Article/details/gtnkoqfyaw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ydzc1.top/Article/details/gtjwphajpw.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.birdmap.top/Article/details/gtvzykoutc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zdqjudy.top/Article/details/gtiuthjago.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yj20258888.top/Article/details/gtkbwhrtji.html

Ruby: arr.sort
来源：http://dali.aizwys.cn/Article/details/gtdhveudkk.html

C#:   list.Sort();
来源：http://dali.tianlin.xyz/Article/details/gtligeammk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yuanzhike.top/Article/details/gtfahspvmv.html


<!-- 参考信息 -->