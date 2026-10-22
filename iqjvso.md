代发 wailian999

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2vzmsoush.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigufen.top/Article/details/gt2zljfeuiv.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.kuanghao11.cn/Article/details/gt2qvzjlrmo.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yongpay.top/Article/details/gt2vkgjjahk.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhongyouzk.top/Article/details/gt2pbakoweq.html

[B10] 遍历同时拿索引
来源：http://dali.gaohongyu789.top/Article/details/gt2ambzegfz.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.daxiang520.top/Article/details/gt2wqjbvyzl.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yuanzhike.top/Article/details/gt2flerljdo.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.sufxvd.cn/Article/details/gt2xymcsxsq.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.cdnleiting.top/Article/details/gt2ljaymrmb.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.fengsongda.top/Article/details/gt2gzaxtnja.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.daxiang520.top/Article/details/gt2tychgpms.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.gaohongyu789.top/Article/details/gt2aeubcojq.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.birdmap.top/Article/details/gt2xiwahiuh.html

[B11] 生成数字序列 / 区间
来源：http://dali.cashguo.top/Article/details/gt2tyrbnqft.html

Py:   list(range(0, 10, 2))
来源：http://dali.0kj1m.cn/Article/details/gt2ablfcugt.html

PHP:  range(0, 10, 2);
来源：http://dali.tanke756.top/Article/details/gt2faieahrw.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.bjfxy.top/Article/details/gt2jvmwahpc.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.chenlongwang.top/Article/details/gt2ccnnword.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yj202588.top/Article/details/gt2cgjbpbbu.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jinqigfzy.top/Article/details/gt2fcrvvpky.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jianghu66.top/Article/details/gt2iwgplucy.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.guannengcc.top/Article/details/gt2fkdgfgog.html

[B12] 跳出多层循环
来源：http://dali.sysykeji.top/Article/details/gt2hohezwie.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.nanxuanxn.top/Article/details/gt2alquujvf.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.havefunace.top/Article/details/gt2hhjudeba.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.andypj.xyz/Article/details/gt2fdbhjwrh.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangdashe.top/Article/details/gt2frrgwnrq.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.fzhhl.top/Article/details/gt2cqdtzduv.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yueranfly.top/Article/details/gt2hgevdwmr.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.cqqwz.cn/Article/details/gt2wmzylhcm.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.wangdashe.top/Article/details/gt2jnvlamnf.html

[B13] 判断是否为数字
来源：http://dali.andypj.xyz/Article/details/gt2mmkdxjyn.html

Py:   isinstance(x, (int, float))
来源：http://dali.yonumen.top/Article/details/gt2rjjuhdwm.html

PHP:  is_numeric($x)
来源：http://dali.zhoulong.xyz/Article/details/gt2izqozrkp.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sufxvd.cn/Article/details/gt2fbaqskcx.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ydzc1.top/Article/details/gt2owgeytto.html

Java: x instanceof Number
来源：http://dali.ppjwa.cn/Article/details/gt2vkhlwwzt.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.meibo888.top/Article/details/gt2mvdvuqnw.html

Ruby: x.is_a?(Numeric)
来源：http://dali.c1oappe.top/Article/details/gt2ifzefzhe.html

C#:   x is int or double or decimal
来源：http://dali.birdmap.top/Article/details/gt2pjksmfqq.html

[B14] 判断值是否在集合内
来源：http://dali.yonumen.top/Article/details/gt2ulwgxipo.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.316326.xyz/Article/details/gt2oxfdwnbz.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.smart0.xyz/Article/details/gt2wexmwnxj.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ehwqpu.com/Article/details/gt2scndhtjq.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zycfv.cn/Article/details/gt2edtsgdgh.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.daxiang520.top/Article/details/gt2mllmcqtb.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hnxiangtu.top/Article/details/gt2ppddxgmx.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.sweek.top/Article/details/gt2gjhhbixy.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wzjtwsjz.html

[B15] 布尔运算与取反
来源：http://dali.jinqigufen.top/Article/details/gt2cxefuxwd.html

Py:   a and b or not c
来源：http://dali.sufxvd.cn/Article/details/gt2ldeqhxfa.html

PHP:  $a && $b || !$c
来源：http://dali.ppjwa.cn/Article/details/gt2vluuwqtu.html

JS:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gt2lnbkutkr.html

TS:   a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gt2zmshyksg.html

Java: a && b || !c
来源：http://dali.pycfn.com/Article/details/gt2efnuvcow.html

Go:   a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gt2smukdemo.html

Ruby: a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gt2jqyfaent.html

C#:   a && b || !c
来源：http://dali.redwolf501.top/Article/details/gt2qetrswzb.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ehwqpu.com/Article/details/gt2mjnuwdso.html

Py:   if not data: return
来源：http://dali.chenlongwang.top/Article/details/gt2pvltimbg.html

PHP:  if (!$data) { return; }
来源：http://dali.yueranfly.top/Article/details/gt2tnijwlmp.html

JS:   if (!data) return;
来源：http://dali.sweek.top/Article/details/gt2zohpixeh.html

TS:   if (!data) return;
来源：http://dali.chenjidiqi.icu/Article/details/gt2qynegqix.html

Java: if (data == null) return;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2afcaczsw.html

Go:   if data == nil { return }
来源：http://dali.aizwys.cn/Article/details/gt2fmfvfcfd.html

Ruby: return if data.nil?
来源：http://dali.zdqjudy.top/Article/details/gt2fnazbydt.html

C#:   if (data == null) return;
来源：http://dali.yonumen.top/Article/details/gt2flhwftvj.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2prkhpsyj.html

C. 函数与作用域
来源：http://dali.yangfankeji.com/Article/details/gt2karuyovl.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2jamwcgtw.html

[C01] 定义函数
来源：http://dali.jyoumei.cn/Article/details/gt2rciiadgu.html

Py:   def add(a, b): return a + b
来源：http://dali.ehwqpu.com/Article/details/gt2zqjciqdp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daxiang520.top/Article/details/gt2vbezwgkn.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gt2pdgpsmsz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gt2ldyejtna.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gt2ucieitgm.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ybcxt.top/Article/details/gt2ricjihno.html

Ruby: def add(a, b); a + b; end
来源：http://dali.chenlongwang.top/Article/details/gt2vtfgjkjt.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gt2viozgdsk.html

[C02] 默认参数
来源：http://dali.aibaodan.cn/Article/details/gt2vmtlwmkb.html

Py:   def greet(name="World"): return name
来源：http://dali.dianchejie.cn/Article/details/gt2aqybdfij.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2msrvsgcn.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hammf.cn/Article/details/gt2fexzgisn.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2jrpqhppd.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.gotoacloud.top/Article/details/gt2unfgvpnq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yj202588.top/Article/details/gt2wdmshjtt.html

Ruby: def greet(name = "World") = name
来源：http://dali.xinyue.icu/Article/details/gt2kosfejze.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cqqwz.cn/Article/details/gt2usjsqsvx.html

[C03] 可变参数
来源：http://dali.xinyue.icu/Article/details/gt2jpqkxqns.html

Py:   def total(*args): return sum(args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ftalpqsq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.cashguo.top/Article/details/gt2budyjdsh.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.316326.xyz/Article/details/gt2fhvtcxzv.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.pycfn.com/Article/details/gt2pvgcqcdg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yangfankeji.com/Article/details/gt2djthjapa.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhongyouzk.top/Article/details/gt2cveqkvhu.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yuxming.cn/Article/details/gt2rcakvcju.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.sysykeji.top/Article/details/gt2jlkuaits.html

[C04] 命名参数 / 关键字参数
来源：http://dali.haohaochexian.top/Article/details/gt2zyzxnnbd.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhongyouzk.top/Article/details/gt2folawdwt.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jinqigufen.top/Article/details/gt2buibejzr.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.bjfxy.top/Article/details/gt2rhtfqlls.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.iojbl.cn/Article/details/gt2uylkomlg.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xylfe.cn/Article/details/gt2vzbnebds.html

Go:   // 无：用配置结构体参数
来源：http://dali.jlsjyb.cn/Article/details/gt2csabfotk.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zdqjudy.top/Article/details/gt2aefalyhj.html

C#:   f(a: 1, b: 2)
来源：http://dali.jyoumei.cn/Article/details/gt2nhrmwegb.html

[C05] 返回多个值
来源：http://dali.gogol.net.cn/Article/details/gt2qihwwthp.html

Py:   return a, b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fyouqinh.html

PHP:  return [$a, $b];
来源：http://dali.pengpengdd.cyou/Article/details/gt2vpltffxo.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.chenlongwang.top/Article/details/gt2zlyrcijy.html

TS:   return { a, b };
来源：http://dali.kuanghao11.cn/Article/details/gt2hpiaxijl.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cqqwz.cn/Article/details/gt2fsumzqne.html

Go:   return a, b
来源：http://dali.ehwqpu.com/Article/details/gt2npzcyrav.html

Ruby: return a, b
来源：http://dali.xuetiantiany.cn/Article/details/gt2uzuugrqy.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.gogol.net.cn/Article/details/gt2eowjulqv.html

[C06] 匿名函数 / lambda
来源：http://dali.hfpthk.cn/Article/details/gt2nihuwvxi.html

Py:   square = lambda x: x * x
来源：http://dali.pycfn.com/Article/details/gt2bisydvvw.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.chenjidiqi.icu/Article/details/gt2ckrssrgs.html

JS:   const square = x => x * x;
来源：http://dali.nwbrower.top/Article/details/gt2ybuibngf.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ecnseyep.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.fzhhl.top/Article/details/gt2sqpoiqpn.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ktixxslv.html

Ruby: square = ->(x) { x * x }
来源：http://dali.svipenyu.cn/Article/details/gt2grqolizs.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.gogol.net.cn/Article/details/gt2ccumnezj.html

[C07] 把函数作为参数传入
来源：http://dali.hysaishi.cn/Article/details/gt2bhcynejp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.quarkkingdee.top/Article/details/gt2djvorwfu.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yueranfly.top/Article/details/gt2layoatcu.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yj20258888.top/Article/details/gt2chcqiyti.html

TS:   arr.map(String)
来源：http://dali.quarkkingdee.top/Article/details/gt2jvmdqoqt.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2nnjocmch.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.nanxinkj.top/Article/details/gt2kvumerdg.html

Ruby: arr.map(&:upcase)
来源：http://dali.svipenyu.cn/Article/details/gt2vdmrvzdy.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhixingplan.top/Article/details/gt2njmzcyck.html

[C08] 闭包
来源：http://dali.xinyue.icu/Article/details/gt2bkugnlan.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.chenzaomai.com/Article/details/gt2iedhvmji.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.sysykeji.top/Article/details/gt2zcpuyspa.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.chenzaomai.com/Article/details/gt2srsgelnk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hfpthk.cn/Article/details/gt2ndkltoof.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.tianlin.xyz/Article/details/gt2ajqzyghg.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhengqikj.top/Article/details/gt2xslczkwn.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.kuanghao11.cn/Article/details/gt2hxpoxtgu.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.daria6918.cn/Article/details/gt2fcslzjyy.html

[C09] 递归
来源：http://dali.yj20258888.top/Article/details/gt2pwoucicy.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cqqwz.cn/Article/details/gt2mfubchuy.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yonumen.top/Article/details/gt2ixyraxvt.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cucudq.cn/Article/details/gt2jhfofpsa.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhixingplan.top/Article/details/gt2drpupdwf.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shzxlz.cn/Article/details/gt2uygstoef.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hammf.cn/Article/details/gt2yolyepkh.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hammf.cn/Article/details/gt2cfpmeuyt.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.dashuyun.cn/Article/details/gt2gygwoxpc.html

[C10] 变量作用域
来源：http://dali.hywenlv.cn/Article/details/gt2zqxqtdye.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.redwolf501.top/Article/details/gt2ldsvvvge.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.guowangkeji.top/Article/details/gt2xakqpddf.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.iojbl.cn/Article/details/gt2cqfcvhyt.html

TS:   同 JS
来源：http://dali.zhiwuduotai.top/Article/details/gt2yagbigyd.html

Java: 方法内为块级作用域
来源：http://dali.zhixingplan.top/Article/details/gt2lrqepeus.html

Go:   花括号块级作用域
来源：http://dali.sweek.top/Article/details/gt2zldbliof.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.smart0.xyz/Article/details/gt2hhjqdkwa.html

C#:   块级作用域
来源：http://dali.chenlongwang.top/Article/details/gt2dzhzdhdb.html

[C11] 模块导入与导出
来源：http://dali.yj20258.top/Article/details/gt2gxtrqjnb.html

Py:   from module import func
来源：http://dali.nwbrower.top/Article/details/gt2xgsnrsuy.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinqigfzy.top/Article/details/gt2kxcswdfu.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sysykeji.top/Article/details/gt2ysveiryq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hongshengwenyu.top/Article/details/gt2oaxhcviq.html

Java: import java.util.List;
来源：http://dali.hfpthk.cn/Article/details/gt2kfcsbxjn.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jhajgysa.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.nanxuanxn.top/Article/details/gt2suxrvgwc.html

C#:   using System.Text;
来源：http://dali.shuidangran.top/Article/details/gt2uifdcpqr.html

[C12] 立即执行函数 IIFE
来源：http://dali.hysaishi.cn/Article/details/gt2exhcjmph.html

Py:   (lambda: print("run"))()
来源：http://dali.zhiwuduotai.top/Article/details/gt2shumevhb.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhiwuduotai.top/Article/details/gt2wglpgxje.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jianghu66.top/Article/details/gt2vmwjlrrc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xinyue.icu/Article/details/gt2phjxtqhg.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yongpay.top/Article/details/gt2ehmtggwc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yongpay.top/Article/details/gt2gsbbjmtl.html

Ruby: -> { puts "run" }.call
来源：http://dali.havefunace.top/Article/details/gt2snygneld.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ivvv.top/Article/details/gt2jxsmofsd.html

[C13] 类型声明 / 类型注解
来源：http://dali.havefunace.top/Article/details/gt2lveupxwp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.tanke756.top/Article/details/gt2giqddfqc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gt2rlormgvh.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.dianchejie.cn/Article/details/gt2ugpiglql.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sweek.top/Article/details/gt2bonrgvmv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cheryme.top/Article/details/gt2uejxfbnf.html

Go:   func add(a, b int) int
来源：http://dali.yongpay.top/Article/details/gt2xluayunm.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhiwuduotai.top/Article/details/gt2ynwfgsbd.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.iojbl.cn/Article/details/gt2djjpaafk.html

[C14] 泛型函数
来源：http://dali.guowangkeji.top/Article/details/gt2jsecxgmf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cqqwz.cn/Article/details/gt2zjcvgzwn.html

PHP:  // 无泛型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yvcdmhxr.html

JS:   // 无泛型
来源：http://dali.xylfe.cn/Article/details/gt2apwfvizd.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.mhx1999.top/Article/details/gt2uerwmkly.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yongpay.top/Article/details/gt2jymflxxe.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hnxiangtu.top/Article/details/gt2ymrwwgoi.html

Ruby: # 无泛型
来源：http://dali.tanke756.top/Article/details/gt2ctstcqae.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hnxiangtu.top/Article/details/gt2ygmacutv.html

[C15] 解构 / 展开参数
来源：http://dali.wangshuangyany.cn/Article/details/gt2xhdvklsg.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.9152youxi.cn/Article/details/gt2zqtfzbgy.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhengqikj.top/Article/details/gt2cpkendln.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.tian-w.cn/Article/details/gt2gsadndam.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cheryme.top/Article/details/gt2vpwglusn.html

Java: // 无解构
来源：http://dali.jqgufenzy.top/Article/details/gt2iropmdov.html

Go:   // 无解构
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2igsuwimr.html

Ruby: a, b = pair
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2enlsbtgx.html

C#:   var (a, b) = pair;
来源：http://dali.jyoumei.cn/Article/details/gt2rdkaxttg.html

[C16] 函数 / 方法重载
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cmyjlazq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.c1oappe.top/Article/details/gt2rbuguswg.html

PHP:  // 无重载
来源：http://dali.gogol.net.cn/Article/details/gt2iffrceci.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.snrcjt.cn/Article/details/gt2zjflgypg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hongshengwenyu.top/Article/details/gt2enfwyari.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2vpyisrum.html

Go:   // 无重载：用不同函数名
来源：http://dali.xziqi.cn/Article/details/gt2xdsbevvz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jlsjyb.cn/Article/details/gt2gzzxcgaf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.chenlongwang.top/Article/details/gt2pzxfzcxu.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iihcplgp.html

D. 数组 / 列表 / 集合
来源：http://dali.ydzc1.top/Article/details/gt2mpgrofcm.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2kymbmxgp.html

[D01] 创建数组 / 列表
来源：http://dali.yuanzhike.top/Article/details/gt2gxlkqpwr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.chenjidiqi.icu/Article/details/gt2wmecdmfp.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.haohaochexian.top/Article/details/gt2bkerutyc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bhuqfkic.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.guannengcc.top/Article/details/gt2vyybibuz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.aibaodan.cn/Article/details/gt2atfymsue.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cheryme.top/Article/details/gt2iftnazub.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hammf.cn/Article/details/gt2oclcxgvh.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.316326.xyz/Article/details/gt2hdekfiul.html

[D02] 追加元素到末尾
来源：http://dali.cashguo.top/Article/details/gt2oxyigmdr.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cdnleiting.top/Article/details/gt2ntdpxfcd.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cdnleiting.top/Article/details/gt2jtmuonhl.html

JS:   arr.push(4);
来源：http://dali.yuanzhike.top/Article/details/gt2bytfvytl.html

TS:   arr.push(4);
来源：http://dali.bjfxy.top/Article/details/gt2nqmfbjvp.html

Java: list.add(4);
来源：http://dali.jlsjyb.cn/Article/details/gt2fhwgmamq.html

Go:   arr = append(arr, 4)
来源：http://dali.ivvv.top/Article/details/gt2dcmmsbgp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shzxlz.cn/Article/details/gt2aaeauegr.html

C#:   list.Add(4);
来源：http://dali.sufxvd.cn/Article/details/gt2wycelquo.html

[D03] 在指定位置插入元素
来源：http://dali.cdnleiting.top/Article/details/gt2yhkbfxbh.html

Py:   arr.insert(0, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2xszjpugy.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.havefunace.top/Article/details/gt2vtiqzdwq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.kuanghao11.cn/Article/details/gt2dpraqbif.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cheryme.top/Article/details/gt2stmgrsrs.html

Java: list.add(0, 0);
来源：http://dali.hnqzz.top/Article/details/gt2dvhgwret.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sysykeji.top/Article/details/gt2tilmigun.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.iojbl.cn/Article/details/gt2zpqigweh.html

C#:   list.Insert(0, 0);
来源：http://dali.jiagoushi.top/Article/details/gt2xufnqvdq.html

[D04] 删除元素
来源：http://dali.hammf.cn/Article/details/gt2bulwiofb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ehwqpu.com/Article/details/gt2bpeoiyzu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jiagoushi.top/Article/details/gt2dcbxxdto.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xziqi.cn/Article/details/gt2escxmndv.html

TS:   arr.splice(0, 1);
来源：http://dali.guowangkeji.top/Article/details/gt2xzmowmab.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jyoumei.cn/Article/details/gt2eikfaxdm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tpiqcyjj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vyxdpaqu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.tianlin.xyz/Article/details/gt2zdascmcr.html

[D05] 访问与修改元素
来源：http://dali.sysykeji.top/Article/details/gt2jedelzxm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.0kj1m.cn/Article/details/gt2oehzwfaz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sxryk.cn/Article/details/gt2ezlkgmso.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oxotqxht.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gogol.net.cn/Article/details/gt2wupihrun.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shzxlz.cn/Article/details/gt2omhlhdvo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jianghu66.top/Article/details/gt2bhedsmen.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gt2eqtamupt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ivvv.top/Article/details/gt2xpmzzevk.html

[D06] 数组长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2utrhbfif.html

Py:   len(arr)
来源：http://dali.cashguo.top/Article/details/gt2wztodvrp.html

PHP:  count($arr);
来源：http://dali.zhixingplan.top/Article/details/gt2tgccemso.html

JS:   arr.length
来源：http://dali.ehwqpu.com/Article/details/gt2uievevhg.html

TS:   arr.length
来源：http://dali.hywenlv.cn/Article/details/gt2wefnfjjn.html

Java: list.size();
来源：http://dali.yuxming.cn/Article/details/gt2hvbphobw.html

Go:   len(arr)
来源：http://dali.sysykeji.top/Article/details/gt2qtwlspdp.html

Ruby: arr.length; arr.size
来源：http://dali.yj20258888.top/Article/details/gt2nhydirhu.html

C#:   list.Count;
来源：http://dali.dianchejie.cn/Article/details/gt2gvfdchjg.html

[D07] 切片 / 取子数组
来源：http://dali.xuanzx.com/Article/details/gt2sxvjcfwo.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ybcxt.top/Article/details/gt2rloxinfu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zycfv.cn/Article/details/gt2efrhbbns.html

JS:   arr.slice(1, 4);
来源：http://dali.hywenlv.cn/Article/details/gt2jdkyzzqt.html

TS:   arr.slice(1, 4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rxmujuqx.html

Java: list.subList(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gt2bkcyrfha.html

Go:   arr[1:4]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cxhbkixh.html

Ruby: arr[1, 3]
来源：http://dali.hnxiangtu.top/Article/details/gt2xrhptlqy.html

C#:   list.GetRange(1, 3);
来源：http://dali.meibo888.top/Article/details/gt2trocprrt.html

[D08] 合并两个数组
来源：http://dali.guowangkeji.top/Article/details/gt2aywlvaqe.html

Py:   a + b;  a.extend(b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2rwhvbxhu.html

PHP:  array_merge($a, $b);
来源：http://dali.gzhubu.top/Article/details/gt2gybvcvfv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.iojbl.cn/Article/details/gt2cvncxkov.html

TS:   [...a, ...b];
来源：http://dali.xylfe.cn/Article/details/gt2hxpliurg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nsbitnhs.html

Go:   append(a, b...)
来源：http://dali.yuxming.cn/Article/details/gt2gxoifhoc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.316326.xyz/Article/details/gt2rmkybtun.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhixingplan.top/Article/details/gt2pwllhzmm.html

[D09] 排序（升序）
来源：http://dali.ivvv.top/Article/details/gt2fbqyffnx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vodyrewj.html

PHP:  sort($arr);
来源：http://dali.smart0.xyz/Article/details/gt2iltelbho.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.aibaodan.cn/Article/details/gt2ygldxvoq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.316326.xyz/Article/details/gt2tggmzewm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhongyouzk.top/Article/details/gt2uyfkdofg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.havefunace.top/Article/details/gt2qpvjwbrv.html

Ruby: arr.sort
来源：http://dali.cqqwz.cn/Article/details/gt2zxlhjqfn.html

C#:   list.Sort();
来源：http://dali.hammf.cn/Article/details/gt2nvhvjxfz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.fengsongda.top/Article/details/gt2fvunwvrd.html


<!-- 参考信息 -->