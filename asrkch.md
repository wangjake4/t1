代发 wailian999

[B09] break 与 continue
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvylxntpx.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.316326.xyz/Article/details/gtmhptaudw.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtikcabvnw.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.redwolf501.top/Article/details/gtfzqlqzcn.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigfzy.top/Article/details/gtvuwenvdv.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hammf.cn/Article/details/gtnrruwfpp.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jinqigfzy.top/Article/details/gtfkihadne.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtscbtcqyj.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gtmkqatzke.html

[B10] 遍历同时拿索引
来源：http://dali.nanxinkj.top/Article/details/gtqczijeoy.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.havefunace.top/Article/details/gtqldlzuel.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.xinyue.icu/Article/details/gtmyexstsl.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.fengsongda.top/Article/details/gtnuogkjzy.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ydzc1.top/Article/details/gtzuurdzgt.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkqrddafo.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shzxlz.cn/Article/details/gtfakftrxn.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.aizwys.cn/Article/details/gtphvohcwp.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.andypj.xyz/Article/details/gtekwbpsyn.html

[B11] 生成数字序列 / 区间
来源：http://dali.9152youxi.cn/Article/details/gtnikptkfh.html

Py:   list(range(0, 10, 2))
来源：http://dali.chenjidiqi.icu/Article/details/gtzelxinbi.html

PHP:  range(0, 10, 2);
来源：http://dali.zhixingplan.top/Article/details/gtrtayijsp.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.chenzaomai.com/Article/details/gthlfyueex.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sxryk.cn/Article/details/gtrsufpkyz.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cqqwz.cn/Article/details/gtfqeufzne.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.gzhubu.top/Article/details/gtkuvxospe.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinqigufen.top/Article/details/gtsqqbcgpn.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.xylfe.cn/Article/details/gtbcuzeytf.html

[B12] 跳出多层循环
来源：http://dali.pengpengdd.cyou/Article/details/gtlibulbvp.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jqgfzy.top/Article/details/gtgpshrxsn.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.316326.xyz/Article/details/gtffzzdhuo.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.svipenyu.cn/Article/details/gtgofjacmt.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zdqjudy.top/Article/details/gtkwngwxlm.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigfzy.top/Article/details/gthwtwsjqf.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.sufxvd.cn/Article/details/gtojpmcvzx.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yvedp.cn/Article/details/gtrcyukuyv.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yanxiufei.cn/Article/details/gtowzmzqnp.html

[B13] 判断是否为数字
来源：http://dali.cdnleiting.top/Article/details/gtvshrqzxs.html

Py:   isinstance(x, (int, float))
来源：http://dali.cashguo.top/Article/details/gteqztdupe.html

PHP:  is_numeric($x)
来源：http://dali.hongshengwenyu.top/Article/details/gtgdllkbzq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhongyouzk.top/Article/details/gtlshajocq.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtbbfbrhxp.html

Java: x instanceof Number
来源：http://dali.svipenyu.cn/Article/details/gtylyktiap.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.gotoacloud.top/Article/details/gtojimzxbp.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jqgfzy.top/Article/details/gtwadhlqdk.html

C#:   x is int or double or decimal
来源：http://dali.xylfe.cn/Article/details/gtwbemtgwz.html

[B14] 判断值是否在集合内
来源：http://dali.zycfv.cn/Article/details/gtscvnyodj.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.sweek.top/Article/details/gtwkxeikom.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yangfankeji.com/Article/details/gthbmjjmme.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cheryme.top/Article/details/gthjdumvrz.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.haohaochexian.top/Article/details/gtslcseiko.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yonumen.top/Article/details/gtjjpsotku.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.iojbl.cn/Article/details/gtixaugiqq.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jianghu66.top/Article/details/gthlssniwb.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.dianchejie.cn/Article/details/gtnygkzveq.html

[B15] 布尔运算与取反
来源：http://dali.cdnleiting.top/Article/details/gtatlifkdx.html

Py:   a and b or not c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcbmqjqev.html

PHP:  $a && $b || !$c
来源：http://dali.yueranfly.top/Article/details/gtvhburlpb.html

JS:   a && b || !c
来源：http://dali.jianghu66.top/Article/details/gtbcogdjna.html

TS:   a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gtahpxzbse.html

Java: a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gttqygqzds.html

Go:   a && b || !c
来源：http://dali.gzhubu.top/Article/details/gtunnovztr.html

Ruby: a && b || !c
来源：http://dali.xziqi.cn/Article/details/gtfocrngwy.html

C#:   a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gtsijwjpvy.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.pengpengdd.cyou/Article/details/gthhubozrz.html

Py:   if not data: return
来源：http://dali.gaohongyu789.top/Article/details/gtzeejzrma.html

PHP:  if (!$data) { return; }
来源：http://dali.jyoumei.cn/Article/details/gttorcvhqg.html

JS:   if (!data) return;
来源：http://dali.tianlin.xyz/Article/details/gtdvnajjlo.html

TS:   if (!data) return;
来源：http://dali.xylfe.cn/Article/details/gtuqggobyq.html

Java: if (data == null) return;
来源：http://dali.andypj.xyz/Article/details/gtcpksogjd.html

Go:   if data == nil { return }
来源：http://dali.jinghuilouyu.cn/Article/details/gtejwoejbn.html

Ruby: return if data.nil?
来源：http://dali.gaohongyu789.top/Article/details/gtbgbnntzj.html

C#:   if (data == null) return;
来源：http://dali.smart0.xyz/Article/details/gtyybwsnsu.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtmreqmugh.html

C. 函数与作用域
来源：http://dali.hongshengwenyu.top/Article/details/gtoncekcey.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtpkuawhby.html

[C01] 定义函数
来源：http://dali.zhongyouzk.top/Article/details/gtwgvwhxef.html

Py:   def add(a, b): return a + b
来源：http://dali.gaohongyu789.top/Article/details/gtwxumeblc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.kuanghao11.cn/Article/details/gtdnptpzoh.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtklruitpm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hammf.cn/Article/details/gtexezuhzf.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtvnptvqrs.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yuxming.cn/Article/details/gtwuihofmr.html

Ruby: def add(a, b); a + b; end
来源：http://dali.chenlongwang.top/Article/details/gtwfrykyto.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtyjojxteb.html

[C02] 默认参数
来源：http://dali.zycfv.cn/Article/details/gtnnuutngs.html

Py:   def greet(name="World"): return name
来源：http://dali.xziqi.cn/Article/details/gtnguyyqgb.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.0kj1m.cn/Article/details/gtlfgaxrxi.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.guannengcc.top/Article/details/gtfboupdgp.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gtiehblfbs.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jinqigfzy.top/Article/details/gtmokjxhcj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.vqdsnc.cn/Article/details/gtnbnntpxb.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtykkavoda.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yangfankeji.com/Article/details/gtifailsdh.html

[C03] 可变参数
来源：http://dali.shuidangran.top/Article/details/gtrysvzmrt.html

Py:   def total(*args): return sum(args)
来源：http://dali.yuxming.cn/Article/details/gtyshwahod.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jyoumei.cn/Article/details/gtshsfvzrm.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xinyue.icu/Article/details/gtimdbwdxt.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbpuymiof.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jqgufenzy.top/Article/details/gtbmltmhei.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.wangshuangyany.cn/Article/details/gtfujpctib.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ydzc1.top/Article/details/gtrjogujpo.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.havefunace.top/Article/details/gtbzjjqrgo.html

[C04] 命名参数 / 关键字参数
来源：http://dali.sxryk.cn/Article/details/gtsszebztt.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cucudq.cn/Article/details/gtnrrizlgn.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jinqigfzy.top/Article/details/gtzgkpyjwk.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinqigfzy.top/Article/details/gtxmostvoq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.wangshuangyany.cn/Article/details/gtgxtimsqm.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.fengsongda.top/Article/details/gtbvigljst.html

Go:   // 无：用配置结构体参数
来源：http://dali.mhx1999.top/Article/details/gtjeqyxhak.html

Ruby: f(a: 1, b: 2)
来源：http://dali.havefunace.top/Article/details/gtvqzakfbw.html

C#:   f(a: 1, b: 2)
来源：http://dali.fzhhl.top/Article/details/gtgxzbcywd.html

[C05] 返回多个值
来源：http://dali.fengsongda.top/Article/details/gtgkyggiyw.html

Py:   return a, b
来源：http://dali.hnqzz.top/Article/details/gtyeknbxgq.html

PHP:  return [$a, $b];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvdpebaxh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.daxiang520.top/Article/details/gtrbkrlizk.html

TS:   return { a, b };
来源：http://dali.jianghu66.top/Article/details/gtujkdrhxn.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cqqwz.cn/Article/details/gtzbmomhib.html

Go:   return a, b
来源：http://dali.wangdashe.top/Article/details/gtlnebcoro.html

Ruby: return a, b
来源：http://dali.andypj.xyz/Article/details/gtznpimbul.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shzxlz.cn/Article/details/gtnswkktmu.html

[C06] 匿名函数 / lambda
来源：http://dali.yvedp.cn/Article/details/gtfftfnbzx.html

Py:   square = lambda x: x * x
来源：http://dali.jiagoushi.top/Article/details/gtlpqximov.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.smart0.xyz/Article/details/gtrigaetsz.html

JS:   const square = x => x * x;
来源：http://dali.c1oappe.top/Article/details/gtpxeakqbl.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.sufxvd.cn/Article/details/gtcwcxslre.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.cdnleiting.top/Article/details/gtmznwzxyj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.0kj1m.cn/Article/details/gtmlbylwib.html

Ruby: square = ->(x) { x * x }
来源：http://dali.tanke756.top/Article/details/gtukilmbaj.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinqigufen.top/Article/details/gtrhfaedqu.html

[C07] 把函数作为参数传入
来源：http://dali.ehwqpu.com/Article/details/gtcgoaujbd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ehwqpu.com/Article/details/gturtrehli.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sysykeji.top/Article/details/gtmvdzrpms.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zycfv.cn/Article/details/gtuoxsboau.html

TS:   arr.map(String)
来源：http://dali.kuanghao11.cn/Article/details/gtugcwuduy.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtrggijkbp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.wangshuangyany.cn/Article/details/gtatojjmpl.html

Ruby: arr.map(&:upcase)
来源：http://dali.chenzaomai.com/Article/details/gtptvsuqdt.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yonumen.top/Article/details/gtcgixdwoz.html

[C08] 闭包
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtimofmlfj.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ydzc1.top/Article/details/gtddpgcnip.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ydzc1.top/Article/details/gtmyvlknww.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.mhx1999.top/Article/details/gtrnhwsgrx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hnqzz.top/Article/details/gthhquaprm.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ybcxt.top/Article/details/gtkligikdt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.svipenyu.cn/Article/details/gtckaukfar.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhoulong.xyz/Article/details/gtxpvyklgj.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhongyouzk.top/Article/details/gtkgiavynk.html

[C09] 递归
来源：http://dali.ehwqpu.com/Article/details/gtbntdwswl.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ybcxt.top/Article/details/gtwofrdccg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gthafndkta.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.redwolf501.top/Article/details/gttmfixsqe.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zycfv.cn/Article/details/gtvkxaryfb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoayrddrx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ehwqpu.com/Article/details/gtyfolelsa.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtxgxwagum.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhongyouzk.top/Article/details/gtxtocfagq.html

[C10] 变量作用域
来源：http://dali.0kj1m.cn/Article/details/gtzomdxjor.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.fzhhl.top/Article/details/gtumhjgsql.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xziqi.cn/Article/details/gtsnnsgynp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ivvv.top/Article/details/gttrligjpi.html

TS:   同 JS
来源：http://dali.chenjidiqi.icu/Article/details/gtormitfxi.html

Java: 方法内为块级作用域
来源：http://dali.hywenlv.cn/Article/details/gtcwduolmc.html

Go:   花括号块级作用域
来源：http://dali.bjfxy.top/Article/details/gtlxykjqhb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zycfv.cn/Article/details/gtesslxulx.html

C#:   块级作用域
来源：http://dali.cheryme.top/Article/details/gtiyvywinn.html

[C11] 模块导入与导出
来源：http://dali.havefunace.top/Article/details/gtzmdrwpaw.html

Py:   from module import func
来源：http://dali.yj20258.top/Article/details/gtfywghpfe.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsbkajhwv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhixingplan.top/Article/details/gtxpdvinbs.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sweek.top/Article/details/gthmlgjfsg.html

Java: import java.util.List;
来源：http://dali.fengsongda.top/Article/details/gtikirmvco.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yuxming.cn/Article/details/gtzallhdvo.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.dashuyun.cn/Article/details/gtvwyjtexi.html

C#:   using System.Text;
来源：http://dali.yongpay.top/Article/details/gtvmidvtaj.html

[C12] 立即执行函数 IIFE
来源：http://dali.sweek.top/Article/details/gtoxqhkdkg.html

Py:   (lambda: print("run"))()
来源：http://dali.cdnleiting.top/Article/details/gtlegravym.html

PHP:  (function () { echo "run"; })();
来源：http://dali.gogol.net.cn/Article/details/gtxwvhrnew.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jianghu66.top/Article/details/gtmuhxgczx.html

TS:   (() => { console.log("run"); })();
来源：http://dali.pycfn.com/Article/details/gtegdtexjg.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sxryk.cn/Article/details/gthnvzvoqe.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.tian-w.cn/Article/details/gtejzkuaia.html

Ruby: -> { puts "run" }.call
来源：http://dali.daxiang520.top/Article/details/gtekropnnc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jqgfzy.top/Article/details/gtpnatlphc.html

[C13] 类型声明 / 类型注解
来源：http://dali.cdnleiting.top/Article/details/gtktgfmkph.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shanyushiyangtech.top/Article/details/gtufyxagzu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenzaomai.com/Article/details/gtatvjmemr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shangyingyoupin.top/Article/details/gtvowocwsm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gteoejavah.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gtgaqjeomr.html

Go:   func add(a, b int) int
来源：http://dali.yueranfly.top/Article/details/gtkxsckepw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gaohongyu789.top/Article/details/gtllqutmbm.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.sweek.top/Article/details/gtfrpghcph.html

[C14] 泛型函数
来源：http://dali.meibo888.top/Article/details/gtzybsidgf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jiagoushi.top/Article/details/gtinxzqrjf.html

PHP:  // 无泛型
来源：http://dali.sxryk.cn/Article/details/gtcnmpzupo.html

JS:   // 无泛型
来源：http://dali.jqgfzy.top/Article/details/gtmpqwbgct.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.fzhhl.top/Article/details/gttplhfhip.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jyoumei.cn/Article/details/gtikdywzni.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxjzxkqhx.html

Ruby: # 无泛型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkdqjigzf.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jqgufenzy.top/Article/details/gtzvcklckj.html

[C15] 解构 / 展开参数
来源：http://dali.haohaochexian.top/Article/details/gtbrbxdegv.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gaohongyu789.top/Article/details/gtsyesucqf.html

PHP:  [$a, $b] = $pair;
来源：http://dali.daxiang520.top/Article/details/gtrwbbtxzx.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xylfe.cn/Article/details/gtcqqgiheq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gogol.net.cn/Article/details/gtgusegnet.html

Java: // 无解构
来源：http://dali.nwbrower.top/Article/details/gtirconzwy.html

Go:   // 无解构
来源：http://dali.haohaochexian.top/Article/details/gtigpxappt.html

Ruby: a, b = pair
来源：http://dali.vqdsnc.cn/Article/details/gtjhhudeig.html

C#:   var (a, b) = pair;
来源：http://dali.pengpengdd.cyou/Article/details/gtystegtyt.html

[C16] 函数 / 方法重载
来源：http://dali.hongshengwenyu.top/Article/details/gtpukenywp.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yonumen.top/Article/details/gtcuddgwzo.html

PHP:  // 无重载
来源：http://dali.yuxming.cn/Article/details/gtjpucirbv.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.chenzaomai.com/Article/details/gtywotbedg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.tianlin.xyz/Article/details/gtqprgffdp.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xuanzx.com/Article/details/gtzubvurgq.html

Go:   // 无重载：用不同函数名
来源：http://dali.shanyushiyangtech.top/Article/details/gtzagztrvr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cashguo.top/Article/details/gtnrmrxyby.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ydzc1.top/Article/details/gteqqoikpc.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtqztpowba.html

D. 数组 / 列表 / 集合
来源：http://dali.meibo888.top/Article/details/gtzplzjlce.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtsjmspssk.html

[D01] 创建数组 / 列表
来源：http://dali.sweek.top/Article/details/gtkqltyhot.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.aibaodan.cn/Article/details/gtgbtywwrg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.chenjidiqi.icu/Article/details/gtxwbwposn.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.feifeiyinyue.top/Article/details/gtzhfzlbcw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shuidangran.top/Article/details/gtdwmiipwl.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.svipenyu.cn/Article/details/gtfropwjax.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.daxiang520.top/Article/details/gtbmgfeacv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hammf.cn/Article/details/gtsqnujadd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.chenzaomai.com/Article/details/gtybqyofrh.html

[D02] 追加元素到末尾
来源：http://dali.tian-w.cn/Article/details/gtnkcqflie.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.guowangkeji.top/Article/details/gtnzbvmlbw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cashguo.top/Article/details/gtoghpouia.html

JS:   arr.push(4);
来源：http://dali.xuanzx.com/Article/details/gttvhjqadc.html

TS:   arr.push(4);
来源：http://dali.birdmap.top/Article/details/gtghjadqbd.html

Java: list.add(4);
来源：http://dali.guowangkeji.top/Article/details/gtqiywodyv.html

Go:   arr = append(arr, 4)
来源：http://dali.0kj1m.cn/Article/details/gtgysnntna.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xziqi.cn/Article/details/gtnqhdnegs.html

C#:   list.Add(4);
来源：http://dali.c1oappe.top/Article/details/gtpgjcyovw.html

[D03] 在指定位置插入元素
来源：http://dali.ehwqpu.com/Article/details/gtakdhaudn.html

Py:   arr.insert(0, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtfwcsykhr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.meibo888.top/Article/details/gtzrdpavqh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.sxryk.cn/Article/details/gtpauglbmb.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhoulong.xyz/Article/details/gtisnrqvfo.html

Java: list.add(0, 0);
来源：http://dali.bjfxy.top/Article/details/gteqzqqyjl.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sweek.top/Article/details/gtnhxicsjz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jianghu66.top/Article/details/gtseyccstf.html

C#:   list.Insert(0, 0);
来源：http://dali.hnqzz.top/Article/details/gtszozydbl.html

[D04] 删除元素
来源：http://dali.hywenlv.cn/Article/details/gtmrerzcze.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.birdmap.top/Article/details/gtukkpzxnx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtzktsdipd.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gtgscbxilf.html

TS:   arr.splice(0, 1);
来源：http://dali.feifeiyinyue.top/Article/details/gtpcrewosu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.snrcjt.cn/Article/details/gtrnzvnbvd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.316326.xyz/Article/details/gtucrcxpmr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cucudq.cn/Article/details/gtbjiwvfnd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yueranfly.top/Article/details/gtajzgvmou.html

[D05] 访问与修改元素
来源：http://dali.tanke756.top/Article/details/gtdrwptqux.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.vqdsnc.cn/Article/details/gtouvodmgo.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.kuanghao11.cn/Article/details/gtrvbibvcc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.nanxuanxn.top/Article/details/gtlxxivbrj.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gaohongyu789.top/Article/details/gttmldlqxu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpehmyzyq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gtujsnjvkb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gzhubu.top/Article/details/gtydrhlcap.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.0kj1m.cn/Article/details/gttzszkhcj.html

[D06] 数组长度
来源：http://dali.yonumen.top/Article/details/gtbtklnaub.html

Py:   len(arr)
来源：http://dali.yangfankeji.com/Article/details/gtgmlcdgol.html

PHP:  count($arr);
来源：http://dali.yj20258.top/Article/details/gtdglfnxqm.html

JS:   arr.length
来源：http://dali.hfpthk.cn/Article/details/gtvfbccteu.html

TS:   arr.length
来源：http://dali.svipenyu.cn/Article/details/gtxpxabwtb.html

Java: list.size();
来源：http://dali.fzhhl.top/Article/details/gtkviudzxa.html

Go:   len(arr)
来源：http://dali.dianchejie.cn/Article/details/gtodyzvdea.html

Ruby: arr.length; arr.size
来源：http://dali.xylfe.cn/Article/details/gtgijnhejk.html

C#:   list.Count;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmabhsnez.html

[D07] 切片 / 取子数组
来源：http://dali.wangshuangyany.cn/Article/details/gtrezmhxyc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cqqwz.cn/Article/details/gtcxqvdmoj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zdqjudy.top/Article/details/gtduelckko.html

JS:   arr.slice(1, 4);
来源：http://dali.zhiwuduotai.top/Article/details/gtzonvbqiu.html

TS:   arr.slice(1, 4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtureqremg.html

Java: list.subList(1, 4);
来源：http://dali.zhongyouzk.top/Article/details/gtugdhcmyo.html

Go:   arr[1:4]
来源：http://dali.daria6918.cn/Article/details/gthrpimjav.html

Ruby: arr[1, 3]
来源：http://dali.xziqi.cn/Article/details/gtxmsynmfc.html

C#:   list.GetRange(1, 3);
来源：http://dali.yj20258888.top/Article/details/gtscnalqmu.html

[D08] 合并两个数组
来源：http://dali.gotoacloud.top/Article/details/gtcgyvigbg.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinqigfzy.top/Article/details/gtcupypxco.html

PHP:  array_merge($a, $b);
来源：http://dali.ppjwa.cn/Article/details/gtaxzztkmj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cucudq.cn/Article/details/gtsaftrccp.html

TS:   [...a, ...b];
来源：http://dali.cheryme.top/Article/details/gtxpykdpwg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yuanzhike.top/Article/details/gtorseewqa.html

Go:   append(a, b...)
来源：http://dali.zhixingplan.top/Article/details/gtdixnwctx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhoulong.xyz/Article/details/gtjdgfzjgn.html

C#:   a.Concat(b).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtsztxqmcw.html

[D09] 排序（升序）
来源：http://dali.cheryme.top/Article/details/gtigjrskhl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.kuanghao11.cn/Article/details/gtbxnegsrm.html

PHP:  sort($arr);
来源：http://dali.jqgufenzy.top/Article/details/gttgofnuqe.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.haohaochexian.top/Article/details/gtfpxeqywh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gtutjdzpaq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yj20258888.top/Article/details/gtymkdfnvx.html


<!-- 参考信息 -->