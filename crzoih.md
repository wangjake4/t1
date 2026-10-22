代发 wailian999

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.birdmap.top/Article/details/gtlkaexpad.html

[B10] 遍历同时拿索引
来源：http://dali.zycfv.cn/Article/details/gtpizwbtnu.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.chenlongwang.top/Article/details/gthkklidjf.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.gogol.net.cn/Article/details/gttuhxdzhy.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.shangyingyoupin.top/Article/details/gtloyeektu.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.gaohongyu789.top/Article/details/gttuhiyiaa.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.feifeiyinyue.top/Article/details/gtatoyderv.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.cqqwz.cn/Article/details/gtijlmibra.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyxyyfhix.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yj202588.top/Article/details/gtmmktqfdf.html

[B11] 生成数字序列 / 区间
来源：http://dali.chenlongwang.top/Article/details/gtqkhyklrh.html

Py:   list(range(0, 10, 2))
来源：http://dali.fengsongda.top/Article/details/gtyoyagyqx.html

PHP:  range(0, 10, 2);
来源：http://dali.hnqzz.top/Article/details/gtnxcqinur.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtzeekedqf.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shzxlz.cn/Article/details/gteenquxqv.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yuanzhike.top/Article/details/gtaqlwcmon.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.fzhhl.top/Article/details/gtabwhnxkx.html

Ruby: (0...10).step(2).to_a
来源：http://dali.snrcjt.cn/Article/details/gtncyhwprd.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhengqikj.top/Article/details/gtntrkxfhh.html

[B12] 跳出多层循环
来源：http://dali.tanke756.top/Article/details/gtqinvhmxy.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.nanxinkj.top/Article/details/gtrsqcdojq.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xuanzx.com/Article/details/gtktcixvtx.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nwbrower.top/Article/details/gtxpgjucuo.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.guowangkeji.top/Article/details/gtuaieiltq.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cheryme.top/Article/details/gtcvliatgn.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yanxiufei.cn/Article/details/gtkqjfywsf.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.shzxlz.cn/Article/details/gtrtzdugok.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.andypj.xyz/Article/details/gtdikeohng.html

[B13] 判断是否为数字
来源：http://dali.ivvv.top/Article/details/gtnojwbidm.html

Py:   isinstance(x, (int, float))
来源：http://dali.hammf.cn/Article/details/gtqrugreyb.html

PHP:  is_numeric($x)
来源：http://dali.zhoulong.xyz/Article/details/gtpcohlegk.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.smart0.xyz/Article/details/gtdbtxakvc.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj202588.top/Article/details/gtlavoxadi.html

Java: x instanceof Number
来源：http://dali.0kj1m.cn/Article/details/gtigazunfe.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yonumen.top/Article/details/gtmpnqbmnu.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ivvv.top/Article/details/gtucwabgxt.html

C#:   x is int or double or decimal
来源：http://dali.redwolf501.top/Article/details/gtcwrzgnhx.html

[B14] 判断值是否在集合内
来源：http://dali.ivvv.top/Article/details/gtgykkftns.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ivvv.top/Article/details/gtmrscjkgo.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hysaishi.cn/Article/details/gtotopbidi.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hnxiangtu.top/Article/details/gtycpxwfpr.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.gotoacloud.top/Article/details/gtrwpruvhu.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.iojbl.cn/Article/details/gtpaduspbp.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.sxryk.cn/Article/details/gtmkgpuyou.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.pycfn.com/Article/details/gtxegushok.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtsawfpuhc.html

[B15] 布尔运算与取反
来源：http://dali.zhengqikj.top/Article/details/gtczhpsutf.html

Py:   a and b or not c
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbniliwuz.html

PHP:  $a && $b || !$c
来源：http://dali.feifeiyinyue.top/Article/details/gtciugjula.html

JS:   a && b || !c
来源：http://dali.shuidangran.top/Article/details/gtubruxgwf.html

TS:   a && b || !c
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaiangnvl.html

Java: a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gtqvjrbyib.html

Go:   a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gtfptzwbqa.html

Ruby: a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtzhebdgaj.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gttpgvijhz.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.smart0.xyz/Article/details/gtnpprsvmk.html

Py:   if not data: return
来源：http://dali.ydzc1.top/Article/details/gtkppfmnpl.html

PHP:  if (!$data) { return; }
来源：http://dali.wangdashe.top/Article/details/gteqlokdpf.html

JS:   if (!data) return;
来源：http://dali.yuxming.cn/Article/details/gtykbncqey.html

TS:   if (!data) return;
来源：http://dali.vqdsnc.cn/Article/details/gtmvaanaxq.html

Java: if (data == null) return;
来源：http://dali.yuxming.cn/Article/details/gtjiuggqiv.html

Go:   if data == nil { return }
来源：http://dali.iojbl.cn/Article/details/gtmxcblmqt.html

Ruby: return if data.nil?
来源：http://dali.iojbl.cn/Article/details/gtvtadggld.html

C#:   if (data == null) return;
来源：http://dali.dashuyun.cn/Article/details/gtpnjdmawo.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtiqvqymyo.html

C. 函数与作用域
来源：http://dali.guowangkeji.top/Article/details/gtamnevhrq.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtcrkoxnco.html

[C01] 定义函数
来源：http://dali.mhx1999.top/Article/details/gtyhvrfqvg.html

Py:   def add(a, b): return a + b
来源：http://dali.yanxiufei.cn/Article/details/gtikowqeqw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cqqwz.cn/Article/details/gtyusbcsiq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gteujzdcra.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gtxtlacmuh.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtqmxoaylg.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yj20258.top/Article/details/gtpfrjdvxf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.gogol.net.cn/Article/details/gtoyugssms.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gtdtbklioa.html

[C02] 默认参数
来源：http://dali.sxryk.cn/Article/details/gtppfhulwc.html

Py:   def greet(name="World"): return name
来源：http://dali.zhengqikj.top/Article/details/gtihcyrysu.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.guannengcc.top/Article/details/gtqefstnki.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.snrcjt.cn/Article/details/gtfzttfdyg.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gtwitgcjiw.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shanyushiyangtech.top/Article/details/gtqekanufb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.nanxuanxn.top/Article/details/gtswqvfsof.html

Ruby: def greet(name = "World") = name
来源：http://dali.hammf.cn/Article/details/gttfgsmskt.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.wangshuangyany.cn/Article/details/gtxpbcuigk.html

[C03] 可变参数
来源：http://dali.hnqzz.top/Article/details/gtcmbojghj.html

Py:   def total(*args): return sum(args)
来源：http://dali.cucudq.cn/Article/details/gtdkihnyur.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zdqjudy.top/Article/details/gtenzriqui.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gtyzwedqgu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj202588.top/Article/details/gtneervihs.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.tian-w.cn/Article/details/gtrmxavhzm.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.chenzaomai.com/Article/details/gtghhstmtg.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sufxvd.cn/Article/details/gtvquxqxta.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zdqjudy.top/Article/details/gtthnuacsp.html

[C04] 命名参数 / 关键字参数
来源：http://dali.nanxuanxn.top/Article/details/gtyajxerwj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gtgeenzycb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jlsjyb.cn/Article/details/gtoixcvogs.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hywenlv.cn/Article/details/gtuysjhktu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.feifeiyinyue.top/Article/details/gtptiwnbgi.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.chenjidiqi.icu/Article/details/gtxumoztiw.html

Go:   // 无：用配置结构体参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxvrpvcie.html

Ruby: f(a: 1, b: 2)
来源：http://dali.snrcjt.cn/Article/details/gtiilsrrnf.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtaczwgtxv.html

[C05] 返回多个值
来源：http://dali.nwbrower.top/Article/details/gtwyftiavp.html

Py:   return a, b
来源：http://dali.ydzc1.top/Article/details/gtogqoveab.html

PHP:  return [$a, $b];
来源：http://dali.shangyingyoupin.top/Article/details/gtfsdyluyu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.quarkkingdee.top/Article/details/gtvnhknaho.html

TS:   return { a, b };
来源：http://dali.yvedp.cn/Article/details/gthkycdpkv.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.tanke756.top/Article/details/gtwpgnwnix.html

Go:   return a, b
来源：http://dali.zhongyouzk.top/Article/details/gtszuchudr.html

Ruby: return a, b
来源：http://dali.yangfankeji.com/Article/details/gtmeolhmfr.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hnxiangtu.top/Article/details/gtybtaikiz.html

[C06] 匿名函数 / lambda
来源：http://dali.hnqzz.top/Article/details/gtwyasgoos.html

Py:   square = lambda x: x * x
来源：http://dali.guowangkeji.top/Article/details/gtmnycubxh.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cashguo.top/Article/details/gtmfoljoyo.html

JS:   const square = x => x * x;
来源：http://dali.ydzc1.top/Article/details/gtuxovngjm.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.gaohongyu789.top/Article/details/gtksuwgkww.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.pengpengdd.cyou/Article/details/gtkceejkii.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jlsjyb.cn/Article/details/gtrlcypwmr.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yanxiufei.cn/Article/details/gtccsqdiko.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ivvv.top/Article/details/gtesqhcxqe.html

[C07] 把函数作为参数传入
来源：http://dali.shzxlz.cn/Article/details/gtpaxawfjv.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jqgufenzy.top/Article/details/gtsgaqkajx.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hnxiangtu.top/Article/details/gtrrmzeyqo.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ivvv.top/Article/details/gtupwzntkw.html

TS:   arr.map(String)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfknwqzgx.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ydzc1.top/Article/details/gtgmbtunrj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.redwolf501.top/Article/details/gtzgzepxrf.html

Ruby: arr.map(&:upcase)
来源：http://dali.xziqi.cn/Article/details/gtvzliutoo.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.chenlongwang.top/Article/details/gtuowjnmey.html

[C08] 闭包
来源：http://dali.redwolf501.top/Article/details/gtbsmfgehm.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.aibaodan.cn/Article/details/gtiyibaihb.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.nanxinkj.top/Article/details/gtclkuwnjr.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jinqigfzy.top/Article/details/gtaeykceus.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cheryme.top/Article/details/gtskjoiksw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cqqwz.cn/Article/details/gtgkqugrpj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.0kj1m.cn/Article/details/gtxntubgqw.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.birdmap.top/Article/details/gtmaqfzche.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.aizwys.cn/Article/details/gtybfnfejb.html

[C09] 递归
来源：http://dali.redwolf501.top/Article/details/gthcyoajqy.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zdqjudy.top/Article/details/gtppvanrhv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gzhubu.top/Article/details/gtbklutzvh.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yongpay.top/Article/details/gtmortmnoz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdyyrbfdl.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shuidangran.top/Article/details/gtchnyihnc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.chenzaomai.com/Article/details/gtgzubqsli.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hnxiangtu.top/Article/details/gtoiqhyvns.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yonumen.top/Article/details/gtxveubyfa.html

[C10] 变量作用域
来源：http://dali.mhx1999.top/Article/details/gtykirgzhq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.dianchejie.cn/Article/details/gtucuteoel.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.haohaochexian.top/Article/details/gthlunifol.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ehwqpu.com/Article/details/gtwosvuyzs.html

TS:   同 JS
来源：http://dali.birdmap.top/Article/details/gtcbwbpdse.html

Java: 方法内为块级作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwiuhvabz.html

Go:   花括号块级作用域
来源：http://dali.aibaodan.cn/Article/details/gtvlzovzdr.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jinghuilouyu.cn/Article/details/gtxntajhtl.html

C#:   块级作用域
来源：http://dali.yangfankeji.com/Article/details/gtkastkilq.html

[C11] 模块导入与导出
来源：http://dali.jqgufenzy.top/Article/details/gtcuhkmzix.html

Py:   from module import func
来源：http://dali.fengsongda.top/Article/details/gtffcvxgoo.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.bjfxy.top/Article/details/gtphclvosw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.c1oappe.top/Article/details/gtrrmfmjre.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.nwbrower.top/Article/details/gtsoadwbab.html

Java: import java.util.List;
来源：http://dali.yvedp.cn/Article/details/gtkhxkekkr.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zycfv.cn/Article/details/gttlbmqlhy.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.aizwys.cn/Article/details/gtjtktdcif.html

C#:   using System.Text;
来源：http://dali.chenzaomai.com/Article/details/gtxxqihgax.html

[C12] 立即执行函数 IIFE
来源：http://dali.c1oappe.top/Article/details/gtzodrfxyw.html

Py:   (lambda: print("run"))()
来源：http://dali.c1oappe.top/Article/details/gtrllfftin.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yongpay.top/Article/details/gtyfoaeugo.html

JS:   (() => { console.log("run"); })();
来源：http://dali.aizwys.cn/Article/details/gtrbnnxuev.html

TS:   (() => { console.log("run"); })();
来源：http://dali.kuanghao11.cn/Article/details/gtzocxywof.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shangyingyoupin.top/Article/details/gttjkbnzow.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yuxming.cn/Article/details/gtbggentyt.html

Ruby: -> { puts "run" }.call
来源：http://dali.xylfe.cn/Article/details/gtmbvfbmbc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.nanxinkj.top/Article/details/gtzmsmdzbh.html

[C13] 类型声明 / 类型注解
来源：http://dali.ehwqpu.com/Article/details/gtqwmmngfi.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.chenzaomai.com/Article/details/gtqlsjqjah.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenzaomai.com/Article/details/gtuzpepihp.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yueranfly.top/Article/details/gtodmpoiuc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gtxqafaxrk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gtmzgauhqq.html

Go:   func add(a, b int) int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtirslhvpd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yueranfly.top/Article/details/gtotlreohg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ppjwa.cn/Article/details/gtdninsqyi.html

[C14] 泛型函数
来源：http://dali.316326.xyz/Article/details/gtrvnksluo.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.gzhubu.top/Article/details/gtrsqjvhui.html

PHP:  // 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsworwyps.html

JS:   // 无泛型
来源：http://dali.fengsongda.top/Article/details/gthcljvahd.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ybcxt.top/Article/details/gtzoifxoea.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hywenlv.cn/Article/details/gtggawqjmd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ppjwa.cn/Article/details/gtrnxdfkfh.html

Ruby: # 无泛型
来源：http://dali.gogol.net.cn/Article/details/gthferwicw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.nanxinkj.top/Article/details/gttkgskqgl.html

[C15] 解构 / 展开参数
来源：http://dali.daxiang520.top/Article/details/gtogshzvkp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.feifeiyinyue.top/Article/details/gtbrreongc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shangyingyoupin.top/Article/details/gtnxhhgiev.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.chenzaomai.com/Article/details/gtmsycufex.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.fzhhl.top/Article/details/gtnzbghsmx.html

Java: // 无解构
来源：http://dali.sxryk.cn/Article/details/gttvianlof.html

Go:   // 无解构
来源：http://dali.havefunace.top/Article/details/gtkjjdwxqr.html

Ruby: a, b = pair
来源：http://dali.andypj.xyz/Article/details/gtssxnbujy.html

C#:   var (a, b) = pair;
来源：http://dali.sxryk.cn/Article/details/gtwxjuywyv.html

[C16] 函数 / 方法重载
来源：http://dali.iojbl.cn/Article/details/gtyulrrfya.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.nanxuanxn.top/Article/details/gtndkmslmo.html

PHP:  // 无重载
来源：http://dali.yongpay.top/Article/details/gtyjazjqvo.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ybcxt.top/Article/details/gtwpsfgeba.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xuetiantiany.cn/Article/details/gtfzxrxaru.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cucudq.cn/Article/details/gtunmodrta.html

Go:   // 无重载：用不同函数名
来源：http://dali.hongshengwenyu.top/Article/details/gtbqpkapxv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuxcrbtfb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ydzc1.top/Article/details/gtdpprfzqn.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gthiztzlgd.html

D. 数组 / 列表 / 集合
来源：http://dali.jiagoushi.top/Article/details/gtbzvlncsj.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtqvjddjlf.html

[D01] 创建数组 / 列表
来源：http://dali.zhoulong.xyz/Article/details/gtzbnyqpns.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yuanzhike.top/Article/details/gttrfgntis.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.sysykeji.top/Article/details/gtzwnffksa.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xziqi.cn/Article/details/gtjvuicvur.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.chenjidiqi.icu/Article/details/gtggtigqfx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhoulong.xyz/Article/details/gthlqkewht.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xylfe.cn/Article/details/gtfykdrnzh.html

Ruby: arr = [1, 2, 3]
来源：http://dali.fzhhl.top/Article/details/gtbvmoqxyg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hnqzz.top/Article/details/gtqcyleths.html

[D02] 追加元素到末尾
来源：http://dali.feifeiyinyue.top/Article/details/gtwmzmiohh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hammf.cn/Article/details/gtdiqlrhfw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.wangshuangyany.cn/Article/details/gtzsttvrra.html

JS:   arr.push(4);
来源：http://dali.jqgufenzy.top/Article/details/gtvyewagyk.html

TS:   arr.push(4);
来源：http://dali.yuxming.cn/Article/details/gtbrvsjljv.html

Java: list.add(4);
来源：http://dali.hnqzz.top/Article/details/gtbttfccto.html

Go:   arr = append(arr, 4)
来源：http://dali.xylfe.cn/Article/details/gtvuphhthp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yj20258888.top/Article/details/gthrnoebzw.html

C#:   list.Add(4);
来源：http://dali.cdnleiting.top/Article/details/gtmafxzock.html

[D03] 在指定位置插入元素
来源：http://dali.ydzc1.top/Article/details/gtpcrpakzp.html

Py:   arr.insert(0, 0)
来源：http://dali.snrcjt.cn/Article/details/gtpuurpcnj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jyoumei.cn/Article/details/gttraysdne.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.meibo888.top/Article/details/gtjynvvpyg.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.snrcjt.cn/Article/details/gtdskxfomo.html

Java: list.add(0, 0);
来源：http://dali.ydzc1.top/Article/details/gtkbatnohz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hnxiangtu.top/Article/details/gtydhsxofy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ehwqpu.com/Article/details/gtaapzsywx.html

C#:   list.Insert(0, 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtavotqcks.html

[D04] 删除元素
来源：http://dali.iojbl.cn/Article/details/gtanotvljx.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.gzhubu.top/Article/details/gtzhsqkxpv.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.tian-w.cn/Article/details/gtlncdezlf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yj20258.top/Article/details/gtaflljvdf.html

TS:   arr.splice(0, 1);
来源：http://dali.316326.xyz/Article/details/gtkkmjzume.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.dianchejie.cn/Article/details/gtsibbdhfv.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xziqi.cn/Article/details/gtdtlbyfok.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.tian-w.cn/Article/details/gtdclkhbxm.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cqqwz.cn/Article/details/gtmuumbgqv.html

[D05] 访问与修改元素
来源：http://dali.yj20258888.top/Article/details/gtktnprfag.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sweek.top/Article/details/gtzzbzrqcv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.wangshuangyany.cn/Article/details/gthhlzwpyr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.daxiang520.top/Article/details/gtxbggosmf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ivvv.top/Article/details/gtnmcuefnc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.dashuyun.cn/Article/details/gtzlrkljxz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.daria6918.cn/Article/details/gtkrnugxti.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pengpengdd.cyou/Article/details/gtzqczoivy.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.svipenyu.cn/Article/details/gtrrpjucgn.html

[D06] 数组长度
来源：http://dali.nanxinkj.top/Article/details/gtehpzibot.html

Py:   len(arr)
来源：http://dali.ehwqpu.com/Article/details/gtxtizfspn.html

PHP:  count($arr);
来源：http://dali.shzxlz.cn/Article/details/gtoaigeyiw.html

JS:   arr.length
来源：http://dali.yuanzhike.top/Article/details/gtozqydqrj.html

TS:   arr.length
来源：http://dali.xuanzx.com/Article/details/gtzbvcygyr.html

Java: list.size();
来源：http://dali.iojbl.cn/Article/details/gtckideqmq.html

Go:   len(arr)
来源：http://dali.havefunace.top/Article/details/gtteoctwga.html

Ruby: arr.length; arr.size
来源：http://dali.quarkkingdee.top/Article/details/gtbputniyd.html

C#:   list.Count;
来源：http://dali.cdnleiting.top/Article/details/gtummhhtia.html

[D07] 切片 / 取子数组
来源：http://dali.dianchejie.cn/Article/details/gtpacndrog.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.aizwys.cn/Article/details/gtudoweafi.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.birdmap.top/Article/details/gtcwvxywjr.html

JS:   arr.slice(1, 4);
来源：http://dali.dianchejie.cn/Article/details/gtlzrdyuav.html

TS:   arr.slice(1, 4);
来源：http://dali.guannengcc.top/Article/details/gtwrotwvna.html

Java: list.subList(1, 4);
来源：http://dali.nanxinkj.top/Article/details/gtppotzfgh.html

Go:   arr[1:4]
来源：http://dali.jyoumei.cn/Article/details/gtdktwyrvj.html

Ruby: arr[1, 3]
来源：http://dali.gotoacloud.top/Article/details/gtergbdadn.html

C#:   list.GetRange(1, 3);
来源：http://dali.aibaodan.cn/Article/details/gtqftrdkwc.html

[D08] 合并两个数组
来源：http://dali.zhoulong.xyz/Article/details/gtsxzupblu.html

Py:   a + b;  a.extend(b)
来源：http://dali.wangshuangyany.cn/Article/details/gtjqpyzttt.html

PHP:  array_merge($a, $b);
来源：http://dali.xylfe.cn/Article/details/gtzbxagzlu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shanyushiyangtech.top/Article/details/gtljmmblfa.html

TS:   [...a, ...b];
来源：http://dali.aibaodan.cn/Article/details/gtxzvpgfpa.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.nanxinkj.top/Article/details/gtaywyrmmf.html

Go:   append(a, b...)
来源：http://dali.meibo888.top/Article/details/gthupxhbjz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.fzhhl.top/Article/details/gtlrhsrclg.html

C#:   a.Concat(b).ToList()
来源：http://dali.svipenyu.cn/Article/details/gtpmhyjvcf.html

[D09] 排序（升序）
来源：http://dali.smart0.xyz/Article/details/gtuemlqexq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yangfankeji.com/Article/details/gtsgobhasu.html

PHP:  sort($arr);
来源：http://dali.havefunace.top/Article/details/gthpbwxowm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ivvv.top/Article/details/gtzabdplmb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jiagoushi.top/Article/details/gtzaqwauuv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yj20258.top/Article/details/gtzgpdvfei.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hysaishi.cn/Article/details/gtkdjvwitv.html

Ruby: arr.sort
来源：http://dali.aizwys.cn/Article/details/gtvgslgnqo.html

C#:   list.Sort();
来源：http://dali.zhongyouzk.top/Article/details/gtnwfgswti.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.meibo888.top/Article/details/gttccfpopv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.dianchejie.cn/Article/details/gtvgwohvme.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xuetiantiany.cn/Article/details/gtlpbyhyno.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pycfn.com/Article/details/gttbuufcdc.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.mhx1999.top/Article/details/gtfiawrbsu.html


<!-- 参考信息 -->