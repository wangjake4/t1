代发 wailian999

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.tianlin.xyz/Article/details/gt2kgdabggj.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.iojbl.cn/Article/details/gt2axxwvxid.html

[B07] while 循环
来源：http://dali.0kj1m.cn/Article/details/gt2diobwcgl.html

Py:   while i < 10: i += 1
来源：http://dali.aizwys.cn/Article/details/gt2scsjgtwb.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2izbashrt.html

JS:   while (i < 10) { i++; }
来源：http://dali.jiagoushi.top/Article/details/gt2nchtaigz.html

TS:   while (i < 10) { i++; }
来源：http://dali.xylfe.cn/Article/details/gt2lrdtbcai.html

Java: while (i < 10) { i++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yblihkpk.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhengqikj.top/Article/details/gt2gwwgjcay.html

Ruby: while i < 10; i += 1; end
来源：http://dali.ehwqpu.com/Article/details/gt2xkzfmsbt.html

C#:   while (i < 10) { i++; }
来源：http://dali.shzxlz.cn/Article/details/gt2dowbmypf.html

[B08] do-while（至少执行一次）
来源：http://dali.yj20258.top/Article/details/gt2kezpisvu.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hongshengwenyu.top/Article/details/gt2cxtavxlk.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yanxiufei.cn/Article/details/gt2hnnorofc.html

JS:   do { i++; } while (i < 10);
来源：http://dali.dianchejie.cn/Article/details/gt2wavsgmld.html

TS:   do { i++; } while (i < 10);
来源：http://dali.daria6918.cn/Article/details/gt2myhskceq.html

Java: do { i++; } while (i < 10);
来源：http://dali.gaohongyu789.top/Article/details/gt2fllgwrit.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.c1oappe.top/Article/details/gt2gvrfcuah.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2adtvcmgf.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhongyouzk.top/Article/details/gt2chpyxrwr.html

[B09] break 与 continue
来源：http://dali.meibo888.top/Article/details/gt2hejtngdo.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.fzhhl.top/Article/details/gt2vecvwmfa.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gt2flkyribq.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangdashe.top/Article/details/gt2dlylluqt.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuanzhike.top/Article/details/gt2blgldllx.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hysaishi.cn/Article/details/gt2qidykbpl.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.hfpthk.cn/Article/details/gt2zszrgdfv.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.cheryme.top/Article/details/gt2tuefdusa.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuanzx.com/Article/details/gt2saxawfwi.html

[B10] 遍历同时拿索引
来源：http://dali.jqgufenzy.top/Article/details/gt2bfyhoyae.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhoulong.xyz/Article/details/gt2xntycvrj.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ppjwa.cn/Article/details/gt2kmgkztch.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.snrcjt.cn/Article/details/gt2oyzsllvp.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.gogol.net.cn/Article/details/gt2wfulpxkj.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bnkrpcum.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shzxlz.cn/Article/details/gt2xyoftsvo.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.gotoacloud.top/Article/details/gt2qqcfrjqf.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yangfankeji.com/Article/details/gt2rgvjbsfx.html

[B11] 生成数字序列 / 区间
来源：http://dali.hfpthk.cn/Article/details/gt2igzhbpzk.html

Py:   list(range(0, 10, 2))
来源：http://dali.jiagoushi.top/Article/details/gt2wsshkuba.html

PHP:  range(0, 10, 2);
来源：http://dali.chenzaomai.com/Article/details/gt2ehlbnklu.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nanxuanxn.top/Article/details/gt2lssuhxjz.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yonumen.top/Article/details/gt2egprstit.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jyoumei.cn/Article/details/gt2wxgvzapa.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.c1oappe.top/Article/details/gt2fzslqtwt.html

Ruby: (0...10).step(2).to_a
来源：http://dali.haohaochexian.top/Article/details/gt2gqjikanv.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shzxlz.cn/Article/details/gt2dtkhmqmv.html

[B12] 跳出多层循环
来源：http://dali.xuanzx.com/Article/details/gt2pucchhzh.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hammf.cn/Article/details/gt2njofsqsy.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cheryme.top/Article/details/gt2zwnlgfwv.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cdnleiting.top/Article/details/gt2xpudoydf.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.birdmap.top/Article/details/gt2kyedtoju.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj202588.top/Article/details/gt2nejtquti.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xylfe.cn/Article/details/gt2nyakluqe.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhongyouzk.top/Article/details/gt2pyualgwz.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.sweek.top/Article/details/gt2jijwzjfl.html

[B13] 判断是否为数字
来源：http://dali.cqqwz.cn/Article/details/gt2kbqkitpj.html

Py:   isinstance(x, (int, float))
来源：http://dali.guowangkeji.top/Article/details/gt2xjiijtxy.html

PHP:  is_numeric($x)
来源：http://dali.chenzaomai.com/Article/details/gt2ojvjbrcj.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gaohongyu789.top/Article/details/gt2ripyizox.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.fzhhl.top/Article/details/gt2jeuzcofa.html

Java: x instanceof Number
来源：http://dali.zhoulong.xyz/Article/details/gt2xaefaemz.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xylfe.cn/Article/details/gt2lwgqenbn.html

Ruby: x.is_a?(Numeric)
来源：http://dali.gogol.net.cn/Article/details/gt2fpfksmrv.html

C#:   x is int or double or decimal
来源：http://dali.ybcxt.top/Article/details/gt2zdbsebqe.html

[B14] 判断值是否在集合内
来源：http://dali.zhongyouzk.top/Article/details/gt2anqgkxqt.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.mhx1999.top/Article/details/gt2ezvhdzpf.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.tian-w.cn/Article/details/gt2vnhkizkb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yangfankeji.com/Article/details/gt2lgsfskoy.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.fengsongda.top/Article/details/gt2vxxllxlr.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jiagoushi.top/Article/details/gt2ionrqqiq.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xziqi.cn/Article/details/gt2avvjypyb.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.aizwys.cn/Article/details/gt2jofvfrmo.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.gotoacloud.top/Article/details/gt2whrkrgkd.html

[B15] 布尔运算与取反
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zhtjbgkh.html

Py:   a and b or not c
来源：http://dali.316326.xyz/Article/details/gt2wiedeoyq.html

PHP:  $a && $b || !$c
来源：http://dali.zhixingplan.top/Article/details/gt2ovlgcqzr.html

JS:   a && b || !c
来源：http://dali.sweek.top/Article/details/gt2rqewfjnd.html

TS:   a && b || !c
来源：http://dali.smart0.xyz/Article/details/gt2egxcsfxe.html

Java: a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gt2bioumkcu.html

Go:   a && b || !c
来源：http://dali.tanke756.top/Article/details/gt2yvcjzazc.html

Ruby: a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gt2oyxjrivz.html

C#:   a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gt2nxkpfdrm.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.guowangkeji.top/Article/details/gt2jwafewth.html

Py:   if not data: return
来源：http://dali.ydzc1.top/Article/details/gt2kezbaxar.html

PHP:  if (!$data) { return; }
来源：http://dali.ydzc1.top/Article/details/gt2ywkrropz.html

JS:   if (!data) return;
来源：http://dali.gaohongyu789.top/Article/details/gt2qujhoqkv.html

TS:   if (!data) return;
来源：http://dali.yj20258.top/Article/details/gt2qkajrnnr.html

Java: if (data == null) return;
来源：http://dali.hnqzz.top/Article/details/gt2onnpfoco.html

Go:   if data == nil { return }
来源：http://dali.zhiwuduotai.top/Article/details/gt2twmtopbg.html

Ruby: return if data.nil?
来源：http://dali.316326.xyz/Article/details/gt2hycpkrja.html

C#:   if (data == null) return;
来源：http://dali.jianghu66.top/Article/details/gt2moqlmjcu.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mtgevsrm.html

C. 函数与作用域
来源：http://dali.sxryk.cn/Article/details/gt2pmrfpkaq.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2zrqkzqrg.html

[C01] 定义函数
来源：http://dali.gaohongyu789.top/Article/details/gt2bdbdcyik.html

Py:   def add(a, b): return a + b
来源：http://dali.svipenyu.cn/Article/details/gt2tlaehuyf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenlongwang.top/Article/details/gt2kcqaykqt.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gt2zglbzozo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wowoyleu.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gt2kirpwsel.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.wangdashe.top/Article/details/gt2lcwplmdt.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cbtkqrln.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gt2bdgkcvzp.html

[C02] 默认参数
来源：http://dali.xuanzx.com/Article/details/gt2pecvqgtt.html

Py:   def greet(name="World"): return name
来源：http://dali.aizwys.cn/Article/details/gt2jpnbizhe.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gogol.net.cn/Article/details/gt2oxbjjcgf.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2mcohppvi.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.shzxlz.cn/Article/details/gt2zcftzggy.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.mhx1999.top/Article/details/gt2jkhqfeuw.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.guowangkeji.top/Article/details/gt2lwafqdir.html

Ruby: def greet(name = "World") = name
来源：http://dali.kuanghao11.cn/Article/details/gt2ghjabfer.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ybcxt.top/Article/details/gt2pprenibx.html

[C03] 可变参数
来源：http://dali.gzhubu.top/Article/details/gt2dnriorya.html

Py:   def total(*args): return sum(args)
来源：http://dali.gogol.net.cn/Article/details/gt2vvmfsngb.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.fzhhl.top/Article/details/gt2iicvypun.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258888.top/Article/details/gt2ysbovlds.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.316326.xyz/Article/details/gt2yiuzqixv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xinyue.icu/Article/details/gt2cqbfcsws.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jiagoushi.top/Article/details/gt2xfvemyyx.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hammf.cn/Article/details/gt2obkzcdys.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xziqi.cn/Article/details/gt2smjfzxpj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.chenlongwang.top/Article/details/gt2kdjqzudz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hnqzz.top/Article/details/gt2gvyvxyrl.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yj20258.top/Article/details/gt2lpabpkud.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wzepfvla.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhongyouzk.top/Article/details/gt2azfyguzl.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.gogol.net.cn/Article/details/gt2qqexbale.html

Go:   // 无：用配置结构体参数
来源：http://dali.nanxuanxn.top/Article/details/gt2qdhbmhec.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yvedp.cn/Article/details/gt2pxposbpk.html

C#:   f(a: 1, b: 2)
来源：http://dali.andypj.xyz/Article/details/gt2kurerieq.html

[C05] 返回多个值
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bjmnrbwg.html

Py:   return a, b
来源：http://dali.nwbrower.top/Article/details/gt2qigfncai.html

PHP:  return [$a, $b];
来源：http://dali.daxiang520.top/Article/details/gt2dyuaoszf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.guannengcc.top/Article/details/gt2xwaavdcc.html

TS:   return { a, b };
来源：http://dali.kuanghao11.cn/Article/details/gt2jgiejibp.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.iojbl.cn/Article/details/gt2yoczwizg.html

Go:   return a, b
来源：http://dali.yangfankeji.com/Article/details/gt2jvktaehx.html

Ruby: return a, b
来源：http://dali.tianlin.xyz/Article/details/gt2kzcdtgge.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.bjfxy.top/Article/details/gt2vvjchbzi.html

[C06] 匿名函数 / lambda
来源：http://dali.andypj.xyz/Article/details/gt2fxcsofgy.html

Py:   square = lambda x: x * x
来源：http://dali.yongpay.top/Article/details/gt2swwwtkze.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.pengpengdd.cyou/Article/details/gt2qikydtde.html

JS:   const square = x => x * x;
来源：http://dali.yangfankeji.com/Article/details/gt2laiyfvci.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.mhx1999.top/Article/details/gt2gfwzzxzd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yonumen.top/Article/details/gt2hjgkegkk.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.cqqwz.cn/Article/details/gt2mhdsxygp.html

Ruby: square = ->(x) { x * x }
来源：http://dali.wangshuangyany.cn/Article/details/gt2tzdplnsf.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.aibaodan.cn/Article/details/gt2anpwedgp.html

[C07] 把函数作为参数传入
来源：http://dali.nanxuanxn.top/Article/details/gt2zgyojqcw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vobgqmws.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2yztwbsav.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jqgufenzy.top/Article/details/gt2umvmrnrf.html

TS:   arr.map(String)
来源：http://dali.wangdashe.top/Article/details/gt2cisvhoih.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2opagykcs.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhongyouzk.top/Article/details/gt2cvscvmnr.html

Ruby: arr.map(&:upcase)
来源：http://dali.yonumen.top/Article/details/gt2swimlioq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hongshengwenyu.top/Article/details/gt2ffnkylho.html

[C08] 闭包
来源：http://dali.jqgufenzy.top/Article/details/gt2irbzzzkx.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jinqigfzy.top/Article/details/gt2xpxjtlof.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jqgufenzy.top/Article/details/gt2sgakutxd.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yj202588.top/Article/details/gt2vzbeprpq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.gzhubu.top/Article/details/gt2rtccenik.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.guowangkeji.top/Article/details/gt2inqsbtcb.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yj20258.top/Article/details/gt2zoltygdt.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jlsjyb.cn/Article/details/gt2xgmyssuc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.chenzaomai.com/Article/details/gt2zwtyjzvd.html

[C09] 递归
来源：http://dali.pengpengdd.cyou/Article/details/gt2swlitfqw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xwclbkma.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shuidangran.top/Article/details/gt2wazuzsgi.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.haohaochexian.top/Article/details/gt2olrecmww.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.dashuyun.cn/Article/details/gt2gnqsrgtc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cdnleiting.top/Article/details/gt2luqbiwuq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xuetiantiany.cn/Article/details/gt2tdafuimf.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2prwckzbq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yvedp.cn/Article/details/gt2kpypmwsu.html

[C10] 变量作用域
来源：http://dali.zycfv.cn/Article/details/gt2ivhzuozf.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hongshengwenyu.top/Article/details/gt2sdzspgwh.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xylfe.cn/Article/details/gt2knzsmoul.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hysaishi.cn/Article/details/gt2kngnohtk.html

TS:   同 JS
来源：http://dali.cqqwz.cn/Article/details/gt2tqypztjs.html

Java: 方法内为块级作用域
来源：http://dali.chenjidiqi.icu/Article/details/gt2suxnzgqu.html

Go:   花括号块级作用域
来源：http://dali.yongpay.top/Article/details/gt2ozkbcejs.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zycfv.cn/Article/details/gt2mmxlczug.html

C#:   块级作用域
来源：http://dali.mhx1999.top/Article/details/gt2rtvsrqpo.html

[C11] 模块导入与导出
来源：http://dali.yuanzhike.top/Article/details/gt2xbjecrjg.html

Py:   from module import func
来源：http://dali.vqdsnc.cn/Article/details/gt2oevqtsnh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.smart0.xyz/Article/details/gt2gziahxnb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.tanke756.top/Article/details/gt2vqvovryc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hongshengwenyu.top/Article/details/gt2snmiawgu.html

Java: import java.util.List;
来源：http://dali.ppjwa.cn/Article/details/gt2mhtghjua.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.guowangkeji.top/Article/details/gt2jokjnqui.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xuanzx.com/Article/details/gt2nggvyeka.html

C#:   using System.Text;
来源：http://dali.kuanghao11.cn/Article/details/gt2eoizkngv.html

[C12] 立即执行函数 IIFE
来源：http://dali.smart0.xyz/Article/details/gt2myrzvhci.html

Py:   (lambda: print("run"))()
来源：http://dali.haohaochexian.top/Article/details/gt2foesedjn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hysaishi.cn/Article/details/gt2bjggfvyk.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yonumen.top/Article/details/gt2gjfidyeo.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fpyjbesw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.chenlongwang.top/Article/details/gt2ievautpx.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.tianlin.xyz/Article/details/gt2hicainqi.html

Ruby: -> { puts "run" }.call
来源：http://dali.quarkkingdee.top/Article/details/gt2uryixkpd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shuidangran.top/Article/details/gt2wwunnbcp.html

[C13] 类型声明 / 类型注解
来源：http://dali.cqqwz.cn/Article/details/gt2psysafkj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shzxlz.cn/Article/details/gt2owzscodi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.snrcjt.cn/Article/details/gt2iftlwxny.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ppjwa.cn/Article/details/gt2xrkilppp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gt2nqqnsvjn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gt2vynzwvqo.html

Go:   func add(a, b int) int
来源：http://dali.ehwqpu.com/Article/details/gt2hvqyyjjm.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yueranfly.top/Article/details/gt2nahslacm.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.0kj1m.cn/Article/details/gt2ozhtswns.html

[C14] 泛型函数
来源：http://dali.316326.xyz/Article/details/gt2pedkvguj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.andypj.xyz/Article/details/gt2vmhzjdta.html

PHP:  // 无泛型
来源：http://dali.ehwqpu.com/Article/details/gt2sddnbcyw.html

JS:   // 无泛型
来源：http://dali.redwolf501.top/Article/details/gt2njcstdzn.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.quarkkingdee.top/Article/details/gt2ezvbcbtm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.0kj1m.cn/Article/details/gt2jhygiqvo.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cashguo.top/Article/details/gt2dvrceflf.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2rnetdbin.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.kuanghao11.cn/Article/details/gt2okqeasgb.html

[C15] 解构 / 展开参数
来源：http://dali.ppjwa.cn/Article/details/gt2cbdgnpkc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shangyingyoupin.top/Article/details/gt2utgsokgn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.0kj1m.cn/Article/details/gt2jlhiitlr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shuidangran.top/Article/details/gt2bctcmxiw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2nlowjawq.html

Java: // 无解构
来源：http://dali.tianlin.xyz/Article/details/gt2lkcsvzro.html

Go:   // 无解构
来源：http://dali.nanxinkj.top/Article/details/gt2aamcdgrd.html

Ruby: a, b = pair
来源：http://dali.andypj.xyz/Article/details/gt2syvkjkuk.html

C#:   var (a, b) = pair;
来源：http://dali.tianlin.xyz/Article/details/gt2fqfmunsm.html

[C16] 函数 / 方法重载
来源：http://dali.sxryk.cn/Article/details/gt2zfssrrfx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.sufxvd.cn/Article/details/gt2wxcikiug.html

PHP:  // 无重载
来源：http://dali.hywenlv.cn/Article/details/gt2qkajdzgc.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.tianlin.xyz/Article/details/gt2uvplnrfn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sweek.top/Article/details/gt2metcfpen.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2yqbvgrtm.html

Go:   // 无重载：用不同函数名
来源：http://dali.aibaodan.cn/Article/details/gt2gtcqvyaj.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yanxiufei.cn/Article/details/gt2jyqwwsvw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hnqzz.top/Article/details/gt2dkbhabsp.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2usjymhll.html

D. 数组 / 列表 / 集合
来源：http://dali.yueranfly.top/Article/details/gt2pvbfymer.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2kfoepfxk.html

[D01] 创建数组 / 列表
来源：http://dali.zhixingplan.top/Article/details/gt2pulzleez.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.birdmap.top/Article/details/gt2mpydbzec.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.iojbl.cn/Article/details/gt2bbjkxofb.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xylfe.cn/Article/details/gt2qqlftmhm.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cdnleiting.top/Article/details/gt2puuwnyzz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cqqwz.cn/Article/details/gt2rndlnnya.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ydzc1.top/Article/details/gt2zgdiucks.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvznrnk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.9152youxi.cn/Article/details/gt2djhafdcd.html

[D02] 追加元素到末尾
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wmriaggn.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinqigufen.top/Article/details/gt2urggvxus.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.nwbrower.top/Article/details/gt2idqfxkzc.html

JS:   arr.push(4);
来源：http://dali.zhoulong.xyz/Article/details/gt2cvpqiuql.html

TS:   arr.push(4);
来源：http://dali.ydzc1.top/Article/details/gt2jbsgjnwz.html

Java: list.add(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wczbklvl.html

Go:   arr = append(arr, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gt2twofltxw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sweek.top/Article/details/gt2flhzywez.html

C#:   list.Add(4);
来源：http://dali.cdnleiting.top/Article/details/gt2uyhjjvso.html

[D03] 在指定位置插入元素
来源：http://dali.cucudq.cn/Article/details/gt2ljhrrvad.html

Py:   arr.insert(0, 0)
来源：http://dali.yj20258.top/Article/details/gt2edsxxayf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hnqzz.top/Article/details/gt2kmspqqho.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.iojbl.cn/Article/details/gt2qxzxutqi.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.gzhubu.top/Article/details/gt2twuyvwhz.html

Java: list.add(0, 0);
来源：http://dali.9152youxi.cn/Article/details/gt2tbbenwef.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cucudq.cn/Article/details/gt2sugawhnv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.birdmap.top/Article/details/gt2yhokipke.html

C#:   list.Insert(0, 0);
来源：http://dali.jqgfzy.top/Article/details/gt2hiwvqnxn.html

[D04] 删除元素
来源：http://dali.daria6918.cn/Article/details/gt2nmiacrof.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yangfankeji.com/Article/details/gt2kpahhggi.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kdtekhzr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fwqhvfqh.html

TS:   arr.splice(0, 1);
来源：http://dali.yvedp.cn/Article/details/gt2pvdslvwc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.daria6918.cn/Article/details/gt2aquvhiyw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xinyue.icu/Article/details/gt2gijzkess.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.daria6918.cn/Article/details/gt2namryqpe.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hnxiangtu.top/Article/details/gt2wldvfjbs.html

[D05] 访问与修改元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2amenvqwk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xinyue.icu/Article/details/gt2zamvvtmj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xuanzx.com/Article/details/gt2hgipvscw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.chenjidiqi.icu/Article/details/gt2cxjedbra.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jqgfzy.top/Article/details/gt2duxiklsa.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yj20258.top/Article/details/gt2hyofjqnr.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.nanxinkj.top/Article/details/gt2ndjdllzu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.mhx1999.top/Article/details/gt2axdhdhwa.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.daxiang520.top/Article/details/gt2nsvyellc.html

[D06] 数组长度
来源：http://dali.ybcxt.top/Article/details/gt2enjjbdjc.html

Py:   len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jwnkqgmm.html

PHP:  count($arr);
来源：http://dali.jinqigufen.top/Article/details/gt2cfeumdax.html

JS:   arr.length
来源：http://dali.aizwys.cn/Article/details/gt2mcookruv.html

TS:   arr.length
来源：http://dali.pengpengdd.cyou/Article/details/gt2llpgicik.html

Java: list.size();
来源：http://dali.9152youxi.cn/Article/details/gt2kjekefrm.html

Go:   len(arr)
来源：http://dali.jinqigufen.top/Article/details/gt2iqzwpaxd.html

Ruby: arr.length; arr.size
来源：http://dali.chenlongwang.top/Article/details/gt2abwjuamk.html

C#:   list.Count;
来源：http://dali.gogol.net.cn/Article/details/gt2mqabistc.html

[D07] 切片 / 取子数组
来源：http://dali.jinqigfzy.top/Article/details/gt2bhojlbtx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.haohaochexian.top/Article/details/gt2welvzvai.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wleckqhb.html

JS:   arr.slice(1, 4);
来源：http://dali.sysykeji.top/Article/details/gt2aznqqljp.html


<!-- 参考信息 -->