代发 wailian999

[B09] break 与 continue
来源：http://dali.hammf.cn/Article/details/gtoztlyapn.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.feifeiyinyue.top/Article/details/gtoabrfafo.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.fengsongda.top/Article/details/gtmczdctke.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpiqsllnp.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtalztyumb.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jlsjyb.cn/Article/details/gtdlworcbt.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.tian-w.cn/Article/details/gtqcbxfosl.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.daxiang520.top/Article/details/gtfmbwtkgk.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gtthuvacpd.html

[B10] 遍历同时拿索引
来源：http://dali.zdqjudy.top/Article/details/gtobitezjm.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.nwbrower.top/Article/details/gtlzpgxzbo.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jiagoushi.top/Article/details/gttvmpffpw.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.quarkkingdee.top/Article/details/gtyvdzlucd.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.haohaochexian.top/Article/details/gtuiscxlgw.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jqgufenzy.top/Article/details/gtemzfvuzr.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmzwsvocl.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhiwuduotai.top/Article/details/gtcavebirx.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.xylfe.cn/Article/details/gtxmtzssxy.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhixingplan.top/Article/details/gtcmeiznpg.html

Py:   list(range(0, 10, 2))
来源：http://dali.cucudq.cn/Article/details/gtcizenhzd.html

PHP:  range(0, 10, 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqrdlydvl.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.iojbl.cn/Article/details/gtanrwfdib.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xziqi.cn/Article/details/gtjljpafwt.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.wangdashe.top/Article/details/gtwhyhtkpg.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.cdnleiting.top/Article/details/gtrbbeaioh.html

Ruby: (0...10).step(2).to_a
来源：http://dali.0kj1m.cn/Article/details/gtmwftevtn.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhongyouzk.top/Article/details/gtufvzhmhu.html

[B12] 跳出多层循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtleueokqh.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.shangyingyoupin.top/Article/details/gtmapiqwvu.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jyoumei.cn/Article/details/gtplvpslvd.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuxming.cn/Article/details/gtnlzsazxo.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.snrcjt.cn/Article/details/gtrczmdvmy.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yongpay.top/Article/details/gtlbbvdhmz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jqgufenzy.top/Article/details/gthlipbgea.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xziqi.cn/Article/details/gtkojdmwcb.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.quarkkingdee.top/Article/details/gtfjtkkzhb.html

[B13] 判断是否为数字
来源：http://dali.feifeiyinyue.top/Article/details/gtofvxneue.html

Py:   isinstance(x, (int, float))
来源：http://dali.yonumen.top/Article/details/gtiipvutkm.html

PHP:  is_numeric($x)
来源：http://dali.zhiwuduotai.top/Article/details/gtxwftgjzc.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenlongwang.top/Article/details/gtrlpsjqns.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tanke756.top/Article/details/gtwqbsvxyq.html

Java: x instanceof Number
来源：http://dali.zycfv.cn/Article/details/gtpdlbbpzv.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrdyzlmvj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hfpthk.cn/Article/details/gtkipqtmfz.html

C#:   x is int or double or decimal
来源：http://dali.feifeiyinyue.top/Article/details/gtxeswntog.html

[B14] 判断值是否在集合内
来源：http://dali.hywenlv.cn/Article/details/gtbjxuopvf.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.andypj.xyz/Article/details/gtcyeglpoi.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.kuanghao11.cn/Article/details/gtvlzmnfpo.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.meibo888.top/Article/details/gtdhqzwdxz.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yonumen.top/Article/details/gtcpyeypjf.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yj20258.top/Article/details/gtxkjmoese.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.9152youxi.cn/Article/details/gtlwkdqazr.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ppjwa.cn/Article/details/gthxuxhqzs.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hammf.cn/Article/details/gtfxpfcpvv.html

[B15] 布尔运算与取反
来源：http://dali.guannengcc.top/Article/details/gtttmuixgb.html

Py:   a and b or not c
来源：http://dali.sysykeji.top/Article/details/gtmrkaciwn.html

PHP:  $a && $b || !$c
来源：http://dali.yj202588.top/Article/details/gtjokkbqft.html

JS:   a && b || !c
来源：http://dali.wangdashe.top/Article/details/gtetcryhzk.html

TS:   a && b || !c
来源：http://dali.guannengcc.top/Article/details/gtgxutsksr.html

Java: a && b || !c
来源：http://dali.jqgufenzy.top/Article/details/gtxradjjrj.html

Go:   a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gtpekjgnet.html

Ruby: a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gtonwlsueo.html

C#:   a && b || !c
来源：http://dali.ybcxt.top/Article/details/gtwajhaohy.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.gaohongyu789.top/Article/details/gtyuebwnpl.html

Py:   if not data: return
来源：http://dali.ybcxt.top/Article/details/gtgxprmefm.html

PHP:  if (!$data) { return; }
来源：http://dali.tanke756.top/Article/details/gtvdvskyrn.html

JS:   if (!data) return;
来源：http://dali.gaohongyu789.top/Article/details/gtqxmxufgg.html

TS:   if (!data) return;
来源：http://dali.zhiwuduotai.top/Article/details/gtibtzbjpq.html

Java: if (data == null) return;
来源：http://dali.pengpengdd.cyou/Article/details/gtjhuhyewc.html

Go:   if data == nil { return }
来源：http://dali.guannengcc.top/Article/details/gtolhefmrs.html

Ruby: return if data.nil?
来源：http://dali.quarkkingdee.top/Article/details/gtxtahrozy.html

C#:   if (data == null) return;
来源：http://dali.svipenyu.cn/Article/details/gtytscendx.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtwdttvqeo.html

C. 函数与作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gtgrhyidae.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtuakxmlsa.html

[C01] 定义函数
来源：http://dali.ppjwa.cn/Article/details/gtsnrjloes.html

Py:   def add(a, b): return a + b
来源：http://dali.chenjidiqi.icu/Article/details/gtrwmypljb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sufxvd.cn/Article/details/gtjekeqtck.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gtddsbqjgk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gtiqxpvgsb.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gtgbgeqjuv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhoulong.xyz/Article/details/gtyigjxwpg.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shuidangran.top/Article/details/gtjowfpndv.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.tanke756.top/Article/details/gtiqjxpebe.html

[C02] 默认参数
来源：http://dali.svipenyu.cn/Article/details/gtbkxindrp.html

Py:   def greet(name="World"): return name
来源：http://dali.sxryk.cn/Article/details/gtewoduwpu.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.aibaodan.cn/Article/details/gtcxfskrra.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.wangdashe.top/Article/details/gtxnbqylyd.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hammf.cn/Article/details/gtvmdgsxau.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.gogol.net.cn/Article/details/gthpqmgude.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.pengpengdd.cyou/Article/details/gtgcnsssty.html

Ruby: def greet(name = "World") = name
来源：http://dali.jyoumei.cn/Article/details/gtljywleto.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.sxryk.cn/Article/details/gtjtxacral.html

[C03] 可变参数
来源：http://dali.xuanzx.com/Article/details/gttffaiini.html

Py:   def total(*args): return sum(args)
来源：http://dali.tanke756.top/Article/details/gtghymibrp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gogol.net.cn/Article/details/gtlcrqjiws.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jqgfzy.top/Article/details/gtjwayevdd.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cashguo.top/Article/details/gtkibehqrl.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xinyue.icu/Article/details/gtidbruhpb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xinyue.icu/Article/details/gtoaqtopws.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xuetiantiany.cn/Article/details/gtbrsoedfm.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.meibo888.top/Article/details/gtokhwniah.html

[C04] 命名参数 / 关键字参数
来源：http://dali.pengpengdd.cyou/Article/details/gtcpckbswx.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.gogol.net.cn/Article/details/gtmceonvdx.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ydzc1.top/Article/details/gtwmerpjib.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.tian-w.cn/Article/details/gtugdcveok.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.guowangkeji.top/Article/details/gtgaeouzne.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yvedp.cn/Article/details/gtxqxcirmu.html

Go:   // 无：用配置结构体参数
来源：http://dali.cdnleiting.top/Article/details/gtdkhhwtjm.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtztrouxrn.html

C#:   f(a: 1, b: 2)
来源：http://dali.jinqigfzy.top/Article/details/gtavzgorrf.html

[C05] 返回多个值
来源：http://dali.iojbl.cn/Article/details/gtpuvcpbix.html

Py:   return a, b
来源：http://dali.nanxinkj.top/Article/details/gtqwydniei.html

PHP:  return [$a, $b];
来源：http://dali.xuanzx.com/Article/details/gtwhgcpedv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sxryk.cn/Article/details/gtgqqskjkl.html

TS:   return { a, b };
来源：http://dali.gzhubu.top/Article/details/gtqrfystle.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.fengsongda.top/Article/details/gtlhfhozll.html

Go:   return a, b
来源：http://dali.jiagoushi.top/Article/details/gtonfdyomx.html

Ruby: return a, b
来源：http://dali.shanyushiyangtech.top/Article/details/gtkgdlilbt.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yongpay.top/Article/details/gthpdbrfln.html

[C06] 匿名函数 / lambda
来源：http://dali.havefunace.top/Article/details/gthsdapgsr.html

Py:   square = lambda x: x * x
来源：http://dali.shzxlz.cn/Article/details/gtszuaheuc.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrznejnvr.html

JS:   const square = x => x * x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvhcahgcj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcxqgxiyt.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.gogol.net.cn/Article/details/gtoevvrxbl.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jlsjyb.cn/Article/details/gtxfyfdwwb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hnqzz.top/Article/details/gtbutwffqr.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.birdmap.top/Article/details/gtarzddjua.html

[C07] 把函数作为参数传入
来源：http://dali.shangyingyoupin.top/Article/details/gtxihjlibp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzofxwzdt.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.aibaodan.cn/Article/details/gtciokedvl.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.316326.xyz/Article/details/gtjyfemwac.html

TS:   arr.map(String)
来源：http://dali.zhixingplan.top/Article/details/gtmwvgtfnq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtrzfuxtqj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ehwqpu.com/Article/details/gtfuqdagac.html

Ruby: arr.map(&:upcase)
来源：http://dali.jqgfzy.top/Article/details/gtdomjkjpw.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hnqzz.top/Article/details/gtrinclsjp.html

[C08] 闭包
来源：http://dali.zhixingplan.top/Article/details/gtmnjjwvkl.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.andypj.xyz/Article/details/gtohxuvaox.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cucudq.cn/Article/details/gtrlofmytd.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shuidangran.top/Article/details/gtsbkjurtd.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.shangyingyoupin.top/Article/details/gtbpjnxalm.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrilpzkpc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.vqdsnc.cn/Article/details/gtepdzbqgt.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.sweek.top/Article/details/gtgonzxlhr.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.wangdashe.top/Article/details/gtifozmugp.html

[C09] 递归
来源：http://dali.yj20258.top/Article/details/gtyhiorsae.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jqgfzy.top/Article/details/gtcwkictaf.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.aibaodan.cn/Article/details/gtgrflmvld.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hammf.cn/Article/details/gtkeobfvuz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.0kj1m.cn/Article/details/gtmrifclcp.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.tian-w.cn/Article/details/gtpqkoekjo.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.gotoacloud.top/Article/details/gtocwqkjxj.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xylfe.cn/Article/details/gtugmywzwm.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yvedp.cn/Article/details/gtfkwbaufm.html

[C10] 变量作用域
来源：http://dali.nanxinkj.top/Article/details/gtcpmjduzs.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gttaqwysai.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hammf.cn/Article/details/gtdkdtobnc.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.quarkkingdee.top/Article/details/gtmcvwvygx.html

TS:   同 JS
来源：http://dali.smart0.xyz/Article/details/gtrmkuoeiq.html

Java: 方法内为块级作用域
来源：http://dali.dianchejie.cn/Article/details/gttaoqgdyh.html

Go:   花括号块级作用域
来源：http://dali.316326.xyz/Article/details/gtzgpwfqkb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.daxiang520.top/Article/details/gtagsjeztq.html

C#:   块级作用域
来源：http://dali.meibo888.top/Article/details/gtpngpgsbf.html

[C11] 模块导入与导出
来源：http://dali.sweek.top/Article/details/gtyrjvfojr.html

Py:   from module import func
来源：http://dali.chenjidiqi.icu/Article/details/gtqyalsjqm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.havefunace.top/Article/details/gteeaauxvw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.tanke756.top/Article/details/gtqhhuhgyo.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yj20258.top/Article/details/gtdradjbyk.html

Java: import java.util.List;
来源：http://dali.ppjwa.cn/Article/details/gthyixhssu.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jqgfzy.top/Article/details/gtgvcnwcmj.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.pengpengdd.cyou/Article/details/gtfjccvhrl.html

C#:   using System.Text;
来源：http://dali.havefunace.top/Article/details/gtshhxplaq.html

[C12] 立即执行函数 IIFE
来源：http://dali.chenlongwang.top/Article/details/gtvmrsawfy.html

Py:   (lambda: print("run"))()
来源：http://dali.wangdashe.top/Article/details/gtlsovumlh.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yonumen.top/Article/details/gtkcwuhnjo.html

JS:   (() => { console.log("run"); })();
来源：http://dali.redwolf501.top/Article/details/gtxhrndscs.html

TS:   (() => { console.log("run"); })();
来源：http://dali.tanke756.top/Article/details/gteznpxjkm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ivvv.top/Article/details/gtcftfhtwl.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinqigfzy.top/Article/details/gtfwenpfri.html

Ruby: -> { puts "run" }.call
来源：http://dali.cucudq.cn/Article/details/gtgqqohwqo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hammf.cn/Article/details/gtzsgbbwts.html

[C13] 类型声明 / 类型注解
来源：http://dali.nwbrower.top/Article/details/gtnctwhtaq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jqgufenzy.top/Article/details/gthrsomqvg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pycfn.com/Article/details/gtgyngscyw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shzxlz.cn/Article/details/gtlvxalfdg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gtdrbkhfen.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gtplmotczt.html

Go:   func add(a, b int) int
来源：http://dali.iojbl.cn/Article/details/gtoqtxbwnf.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.wangdashe.top/Article/details/gtvpheozxv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.andypj.xyz/Article/details/gtodmrqida.html

[C14] 泛型函数
来源：http://dali.hongshengwenyu.top/Article/details/gtfvyevhiq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xuanzx.com/Article/details/gtwhxiouxy.html

PHP:  // 无泛型
来源：http://dali.sufxvd.cn/Article/details/gtxodsttsk.html

JS:   // 无泛型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcfdgjtfj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hfpthk.cn/Article/details/gtzqpqkwgu.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sysykeji.top/Article/details/gtbvzghpki.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.smart0.xyz/Article/details/gtbpumpmhz.html

Ruby: # 无泛型
来源：http://dali.daria6918.cn/Article/details/gtxurazviw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cheryme.top/Article/details/gteznjmmhu.html

[C15] 解构 / 展开参数
来源：http://dali.shuidangran.top/Article/details/gtmwlfiyde.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ydzc1.top/Article/details/gthfgubrlt.html

PHP:  [$a, $b] = $pair;
来源：http://dali.c1oappe.top/Article/details/gtzyvkcqqo.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.havefunace.top/Article/details/gteksvpkwo.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtartxnxyw.html

Java: // 无解构
来源：http://dali.ehwqpu.com/Article/details/gtfzlvspwz.html

Go:   // 无解构
来源：http://dali.andypj.xyz/Article/details/gttblcjhad.html

Ruby: a, b = pair
来源：http://dali.shangyingyoupin.top/Article/details/gtulipyxab.html

C#:   var (a, b) = pair;
来源：http://dali.shzxlz.cn/Article/details/gtnoknrgqn.html

[C16] 函数 / 方法重载
来源：http://dali.yj202588.top/Article/details/gtmqvlgaxq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.0kj1m.cn/Article/details/gtjkvtvsws.html

PHP:  // 无重载
来源：http://dali.hnqzz.top/Article/details/gtjsnysusz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.redwolf501.top/Article/details/gtgbyyfyxv.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yonumen.top/Article/details/gtybcgpypj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtmgskafzi.html

Go:   // 无重载：用不同函数名
来源：http://dali.wangshuangyany.cn/Article/details/gttdgqzbqa.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cucudq.cn/Article/details/gtivjxhpux.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.c1oappe.top/Article/details/gtcpazhufg.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtvpytqazk.html

D. 数组 / 列表 / 集合
来源：http://dali.redwolf501.top/Article/details/gtcnxxsupl.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtvmizwahw.html

[D01] 创建数组 / 列表
来源：http://dali.haohaochexian.top/Article/details/gtpamwwdee.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shuidangran.top/Article/details/gtsljvuosb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shanyushiyangtech.top/Article/details/gtvjbzzkft.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yuxming.cn/Article/details/gtdqdtikyp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.mhx1999.top/Article/details/gtqwgjroyy.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yangfankeji.com/Article/details/gtzqlduxmg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.smart0.xyz/Article/details/gtqhxikded.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hnqzz.top/Article/details/gtxeekzlub.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.guannengcc.top/Article/details/gtkhkrigod.html

[D02] 追加元素到末尾
来源：http://dali.cucudq.cn/Article/details/gtfjjwdiad.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.daxiang520.top/Article/details/gtrpifkaio.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jiagoushi.top/Article/details/gtkcymshag.html

JS:   arr.push(4);
来源：http://dali.316326.xyz/Article/details/gtjmkxulhc.html

TS:   arr.push(4);
来源：http://dali.iojbl.cn/Article/details/gtkjxgipoz.html

Java: list.add(4);
来源：http://dali.meibo888.top/Article/details/gtgavztrts.html

Go:   arr = append(arr, 4)
来源：http://dali.zhengqikj.top/Article/details/gtyqmfqhdl.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sufxvd.cn/Article/details/gtvvnjokar.html

C#:   list.Add(4);
来源：http://dali.jinqigufen.top/Article/details/gtjttzcrno.html

[D03] 在指定位置插入元素
来源：http://dali.bjfxy.top/Article/details/gthojaryke.html

Py:   arr.insert(0, 0)
来源：http://dali.chenlongwang.top/Article/details/gtuskkohhu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.0kj1m.cn/Article/details/gtisctndvx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.sweek.top/Article/details/gtwqsfxymw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.316326.xyz/Article/details/gtnirswzyl.html

Java: list.add(0, 0);
来源：http://dali.zycfv.cn/Article/details/gtprauhajy.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hnqzz.top/Article/details/gtcjtmghsl.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.feifeiyinyue.top/Article/details/gtobhenvlm.html

C#:   list.Insert(0, 0);
来源：http://dali.guannengcc.top/Article/details/gtgohwuqhp.html

[D04] 删除元素
来源：http://dali.hongshengwenyu.top/Article/details/gtirqejamv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.dianchejie.cn/Article/details/gtgwdlwdac.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sweek.top/Article/details/gtlvwktpry.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hongshengwenyu.top/Article/details/gtbzypgwtj.html

TS:   arr.splice(0, 1);
来源：http://dali.redwolf501.top/Article/details/gttzcndhxk.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwxkenmo.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xylfe.cn/Article/details/gtiiflfpjj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cucudq.cn/Article/details/gtqluhgnco.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttopdashu.html

[D05] 访问与修改元素
来源：http://dali.chenzaomai.com/Article/details/gtegddtdio.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmnouwxuh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xziqi.cn/Article/details/gthyrolayv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shuidangran.top/Article/details/gtaxrepilq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.nanxuanxn.top/Article/details/gtkdjwgogv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jlsjyb.cn/Article/details/gtlwdgofzk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ywan-chungtsiang.top/Article/details/gthwqugnoa.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jianghu66.top/Article/details/gtujhtqofd.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jlsjyb.cn/Article/details/gtppbhlxlf.html

[D06] 数组长度
来源：http://dali.pycfn.com/Article/details/gtyujbocga.html

Py:   len(arr)
来源：http://dali.yuxming.cn/Article/details/gtmhxwkelc.html

PHP:  count($arr);
来源：http://dali.hammf.cn/Article/details/gtuaohhfxm.html

JS:   arr.length
来源：http://dali.cashguo.top/Article/details/gtxukuuqku.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gtpkonlkvf.html

Java: list.size();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpecwxrcq.html

Go:   len(arr)
来源：http://dali.hfpthk.cn/Article/details/gtfbzrcewv.html

Ruby: arr.length; arr.size
来源：http://dali.dashuyun.cn/Article/details/gtinqcivit.html

C#:   list.Count;
来源：http://dali.zhongyouzk.top/Article/details/gtwrgeyumk.html

[D07] 切片 / 取子数组
来源：http://dali.sxryk.cn/Article/details/gtzvpjyfgr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.nanxuanxn.top/Article/details/gtfpkemywf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.gotoacloud.top/Article/details/gtmehrjvlb.html

JS:   arr.slice(1, 4);
来源：http://dali.yvedp.cn/Article/details/gtvpxsbfgu.html

TS:   arr.slice(1, 4);
来源：http://dali.yanxiufei.cn/Article/details/gtfqamlcni.html

Java: list.subList(1, 4);
来源：http://dali.zycfv.cn/Article/details/gtrdzdcpjj.html

Go:   arr[1:4]
来源：http://dali.ybcxt.top/Article/details/gteypxhiqm.html

Ruby: arr[1, 3]
来源：http://dali.daxiang520.top/Article/details/gttlmkconl.html

C#:   list.GetRange(1, 3);
来源：http://dali.guowangkeji.top/Article/details/gtmdpizyxm.html

[D08] 合并两个数组
来源：http://dali.hfpthk.cn/Article/details/gterymnkql.html

Py:   a + b;  a.extend(b)
来源：http://dali.dianchejie.cn/Article/details/gtcxkjylis.html

PHP:  array_merge($a, $b);
来源：http://dali.shuidangran.top/Article/details/gtoxqzrpiz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.tanke756.top/Article/details/gtfpmcmqur.html

TS:   [...a, ...b];
来源：http://dali.zhiwuduotai.top/Article/details/gtozhzmrbi.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.gaohongyu789.top/Article/details/gtnctxtftw.html

Go:   append(a, b...)
来源：http://dali.yj20258888.top/Article/details/gtatrvesyc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.c1oappe.top/Article/details/gtjyjvymwa.html

C#:   a.Concat(b).ToList()
来源：http://dali.pycfn.com/Article/details/gtmsmksxyv.html

[D09] 排序（升序）
来源：http://dali.zycfv.cn/Article/details/gtwkorfprm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aibaodan.cn/Article/details/gtmwwuyhxb.html

PHP:  sort($arr);
来源：http://dali.cheryme.top/Article/details/gtfghzzcqi.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgfvumrqm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.mhx1999.top/Article/details/gtzotlxjlj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jlsjyb.cn/Article/details/gtrnyehxdv.html


<!-- 参考信息 -->