代发 wailian999

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yuxming.cn/Article/details/gtfvfwsirn.html

[B06] 遍历字典 / 对象
来源：http://dali.yuxming.cn/Article/details/gtrstabhqh.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.pengpengdd.cyou/Article/details/gtnjrvypya.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hywenlv.cn/Article/details/gthjxzzwuw.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.snrcjt.cn/Article/details/gtydjbafln.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfirlzulu.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.gotoacloud.top/Article/details/gtdsnkzzxs.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hammf.cn/Article/details/gtcmqenlis.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.xziqi.cn/Article/details/gtoawteriu.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.chenjidiqi.icu/Article/details/gtsfmelpht.html

[B07] while 循环
来源：http://dali.hywenlv.cn/Article/details/gtogqblpbm.html

Py:   while i < 10: i += 1
来源：http://dali.jlsjyb.cn/Article/details/gtyqqwiemt.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.sxryk.cn/Article/details/gtxzmfcggk.html

JS:   while (i < 10) { i++; }
来源：http://dali.andypj.xyz/Article/details/gtugfgdaio.html

TS:   while (i < 10) { i++; }
来源：http://dali.daxiang520.top/Article/details/gtsmkcksmm.html

Java: while (i < 10) { i++; }
来源：http://dali.nanxinkj.top/Article/details/gtksimbiju.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgjexokkj.html

Ruby: while i < 10; i += 1; end
来源：http://dali.guowangkeji.top/Article/details/gtkcscghxw.html

C#:   while (i < 10) { i++; }
来源：http://dali.nwbrower.top/Article/details/gteizbctln.html

[B08] do-while（至少执行一次）
来源：http://dali.yj20258.top/Article/details/gtmydyuuaz.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hysaishi.cn/Article/details/gtevolddgs.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yanxiufei.cn/Article/details/gthshtvziu.html

JS:   do { i++; } while (i < 10);
来源：http://dali.pycfn.com/Article/details/gtcncxhwet.html

TS:   do { i++; } while (i < 10);
来源：http://dali.dashuyun.cn/Article/details/gtxulbmsea.html

Java: do { i++; } while (i < 10);
来源：http://dali.0kj1m.cn/Article/details/gtkizfzoky.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.tian-w.cn/Article/details/gtzmnwkmwy.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.gotoacloud.top/Article/details/gtvkfxovfm.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jinqigfzy.top/Article/details/gtxwkpbwld.html

[B09] break 与 continue
来源：http://dali.birdmap.top/Article/details/gtwnrudgub.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhoulong.xyz/Article/details/gtnhjdqoea.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.aizwys.cn/Article/details/gtbatgigto.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fzhhl.top/Article/details/gtkxybiysl.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fengsongda.top/Article/details/gtcknhbdrq.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sxryk.cn/Article/details/gtkxneqsoy.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.quarkkingdee.top/Article/details/gtmveeqjzb.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.xinyue.icu/Article/details/gtixmgnqvc.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangshuangyany.cn/Article/details/gtykczjtli.html

[B10] 遍历同时拿索引
来源：http://dali.andypj.xyz/Article/details/gtzoavazhy.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.cucudq.cn/Article/details/gtyuwslbbm.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yongpay.top/Article/details/gtpytjlhlo.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jlsjyb.cn/Article/details/gtmxtbfdbx.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhongyouzk.top/Article/details/gtnnixdxmz.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hnqzz.top/Article/details/gtnxugvgey.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.cqqwz.cn/Article/details/gtjaxkdvtf.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.daxiang520.top/Article/details/gtuwzdhift.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hysaishi.cn/Article/details/gtgvmjfjgl.html

[B11] 生成数字序列 / 区间
来源：http://dali.yongpay.top/Article/details/gtefvmrqvj.html

Py:   list(range(0, 10, 2))
来源：http://dali.iojbl.cn/Article/details/gtrztyshco.html

PHP:  range(0, 10, 2);
来源：http://dali.9152youxi.cn/Article/details/gtpoizlsds.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nanxuanxn.top/Article/details/gtosqawejz.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.0kj1m.cn/Article/details/gtyphyeqic.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yuanzhike.top/Article/details/gtwikliqjh.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.daria6918.cn/Article/details/gthxsnwmck.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yuxming.cn/Article/details/gtksmmqchi.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.bjfxy.top/Article/details/gtufelkerj.html

[B12] 跳出多层循环
来源：http://dali.shangyingyoupin.top/Article/details/gtbgektnwk.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.dashuyun.cn/Article/details/gtumeybrbc.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.tianlin.xyz/Article/details/gtawoipaxj.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdjizmqed.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ehwqpu.com/Article/details/gtmcttlkah.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhoulong.xyz/Article/details/gtvasseaeh.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.kuanghao11.cn/Article/details/gtfforbwdh.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hysaishi.cn/Article/details/gtqdjattvt.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.chenjidiqi.icu/Article/details/gtrjfyrwnz.html

[B13] 判断是否为数字
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdcmctxzk.html

Py:   isinstance(x, (int, float))
来源：http://dali.yuxming.cn/Article/details/gtnlfretew.html

PHP:  is_numeric($x)
来源：http://dali.nanxinkj.top/Article/details/gttpqcxqyo.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj20258.top/Article/details/gtscqgtrib.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ehwqpu.com/Article/details/gteidzhepp.html

Java: x instanceof Number
来源：http://dali.daria6918.cn/Article/details/gtkovyhjur.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.aibaodan.cn/Article/details/gtwydoibda.html

Ruby: x.is_a?(Numeric)
来源：http://dali.wangdashe.top/Article/details/gthvmjiuzs.html

C#:   x is int or double or decimal
来源：http://dali.wangshuangyany.cn/Article/details/gtexulnnhs.html

[B14] 判断值是否在集合内
来源：http://dali.cqqwz.cn/Article/details/gtzdxwzsmb.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.bjfxy.top/Article/details/gtgsnznvvi.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.meibo888.top/Article/details/gtwezqguhg.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gtaybhmrds.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jiagoushi.top/Article/details/gtjshjmnso.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.aizwys.cn/Article/details/gtxywhwysk.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsbntnwhl.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hfpthk.cn/Article/details/gtfcegsgqm.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ydzc1.top/Article/details/gtkbsiphvr.html

[B15] 布尔运算与取反
来源：http://dali.zhixingplan.top/Article/details/gtlnygqypj.html

Py:   a and b or not c
来源：http://dali.meibo888.top/Article/details/gthqfoldwe.html

PHP:  $a && $b || !$c
来源：http://dali.gaohongyu789.top/Article/details/gtowtoyiqn.html

JS:   a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gttjcmaywa.html

TS:   a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gtuuoypnwh.html

Java: a && b || !c
来源：http://dali.andypj.xyz/Article/details/gtuvmvpcda.html

Go:   a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gtesovzqhh.html

Ruby: a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gtivtazufo.html

C#:   a && b || !c
来源：http://dali.havefunace.top/Article/details/gtnrwmugol.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hysaishi.cn/Article/details/gtuhgatfkd.html

Py:   if not data: return
来源：http://dali.quarkkingdee.top/Article/details/gtugxdphum.html

PHP:  if (!$data) { return; }
来源：http://dali.sxryk.cn/Article/details/gtpdqcwhds.html

JS:   if (!data) return;
来源：http://dali.jianghu66.top/Article/details/gtlybqggyu.html

TS:   if (!data) return;
来源：http://dali.shzxlz.cn/Article/details/gtngrrrqng.html

Java: if (data == null) return;
来源：http://dali.daria6918.cn/Article/details/gtqohxthoh.html

Go:   if data == nil { return }
来源：http://dali.ppjwa.cn/Article/details/gtudelfzuf.html

Ruby: return if data.nil?
来源：http://dali.hnqzz.top/Article/details/gtpshvcubk.html

C#:   if (data == null) return;
来源：http://dali.yuanzhike.top/Article/details/gtcazjkkfh.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gttfpklbwx.html

C. 函数与作用域
来源：http://dali.birdmap.top/Article/details/gtgpowfxxo.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtawweuxli.html

[C01] 定义函数
来源：http://dali.tanke756.top/Article/details/gtnkaarbse.html

Py:   def add(a, b): return a + b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtexuucyxm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtygzfnzau.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gthuhfwpex.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tanke756.top/Article/details/gtzhuuyole.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gttofmfbrq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jinqigufen.top/Article/details/gtiyyovgwe.html

Ruby: def add(a, b); a + b; end
来源：http://dali.nwbrower.top/Article/details/gtucqpfskg.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtnkuqgdtm.html

[C02] 默认参数
来源：http://dali.jinqigfzy.top/Article/details/gtvpjxyygf.html

Py:   def greet(name="World"): return name
来源：http://dali.iojbl.cn/Article/details/gtrgroptba.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shzxlz.cn/Article/details/gtfbipuvxp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkslrrluo.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.birdmap.top/Article/details/gtzsxikqac.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.redwolf501.top/Article/details/gtgrwffwao.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.svipenyu.cn/Article/details/gtjwijgpyu.html

Ruby: def greet(name = "World") = name
来源：http://dali.hammf.cn/Article/details/gtrwqaexxz.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.quarkkingdee.top/Article/details/gtlpkdkzkq.html

[C03] 可变参数
来源：http://dali.yonumen.top/Article/details/gtnuavvvvk.html

Py:   def total(*args): return sum(args)
来源：http://dali.quarkkingdee.top/Article/details/gtbjzqnsdv.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.chenjidiqi.icu/Article/details/gtxflrraih.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.wangshuangyany.cn/Article/details/gthhqdkbur.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.birdmap.top/Article/details/gtanegrndl.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.guowangkeji.top/Article/details/gtiyryhcsd.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hammf.cn/Article/details/gtdffuzvei.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yanxiufei.cn/Article/details/gtjpvpmpxu.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cashguo.top/Article/details/gtnxjdxquw.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gaohongyu789.top/Article/details/gtzmwdcnsk.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sysykeji.top/Article/details/gtgyuuqisb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hongshengwenyu.top/Article/details/gtkeixbdfb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yanxiufei.cn/Article/details/gtuotgljjf.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.aizwys.cn/Article/details/gtrtqmdiyv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hysaishi.cn/Article/details/gtyekzloua.html

Go:   // 无：用配置结构体参数
来源：http://dali.jinqigufen.top/Article/details/gtkhprtjwe.html

Ruby: f(a: 1, b: 2)
来源：http://dali.aizwys.cn/Article/details/gtbomgbdfw.html

C#:   f(a: 1, b: 2)
来源：http://dali.shzxlz.cn/Article/details/gtacfcenuu.html

[C05] 返回多个值
来源：http://dali.bjfxy.top/Article/details/gtokwpcekb.html

Py:   return a, b
来源：http://dali.gzhubu.top/Article/details/gtwjecvlzr.html

PHP:  return [$a, $b];
来源：http://dali.aizwys.cn/Article/details/gtufqdobdu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shuidangran.top/Article/details/gtdsvdnlhj.html

TS:   return { a, b };
来源：http://dali.xuanzx.com/Article/details/gtudbhcckh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hnqzz.top/Article/details/gtnkjivtci.html

Go:   return a, b
来源：http://dali.hfpthk.cn/Article/details/gtzynsorbt.html

Ruby: return a, b
来源：http://dali.hnqzz.top/Article/details/gtwalbtupt.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xinyue.icu/Article/details/gtvqkifyko.html

[C06] 匿名函数 / lambda
来源：http://dali.ydzc1.top/Article/details/gtnzoqxafr.html

Py:   square = lambda x: x * x
来源：http://dali.jqgfzy.top/Article/details/gtegqviccb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.quarkkingdee.top/Article/details/gtbwbhbgui.html

JS:   const square = x => x * x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwbrlnqzx.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cdnleiting.top/Article/details/gthdsftwlm.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.shzxlz.cn/Article/details/gtkgnjucnq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.dashuyun.cn/Article/details/gtldariajt.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jianghu66.top/Article/details/gttmserimn.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shzxlz.cn/Article/details/gtndbnbvgl.html

[C07] 把函数作为参数传入
来源：http://dali.jinghuilouyu.cn/Article/details/gtwbvklkco.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xinyue.icu/Article/details/gtdwiakwmf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.9152youxi.cn/Article/details/gtwkjfbffl.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.tanke756.top/Article/details/gtocosbhyk.html

TS:   arr.map(String)
来源：http://dali.guowangkeji.top/Article/details/gtfixsnish.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.fzhhl.top/Article/details/gtvdrofsva.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ywan-chungtsiang.top/Article/details/gtizeozgqm.html

Ruby: arr.map(&:upcase)
来源：http://dali.hfpthk.cn/Article/details/gtxyftvhjj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.birdmap.top/Article/details/gtjohjgjld.html

[C08] 闭包
来源：http://dali.yj20258.top/Article/details/gtfinxvqgw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.daria6918.cn/Article/details/gtlxkkwsto.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.fengsongda.top/Article/details/gtwytbqseg.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdlsbcvfy.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.chenlongwang.top/Article/details/gtashqyxnk.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gzhubu.top/Article/details/gtbudfmoqv.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jlsjyb.cn/Article/details/gtmdklyizn.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shzxlz.cn/Article/details/gtodzbrrnt.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.havefunace.top/Article/details/gtvlfkyvpz.html

[C09] 递归
来源：http://dali.cucudq.cn/Article/details/gtfbbclstw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.gogol.net.cn/Article/details/gtvlhdohrq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cdnleiting.top/Article/details/gtkeyrludx.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkhmsudmf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.guannengcc.top/Article/details/gteuknycsp.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdvygdcte.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yanxiufei.cn/Article/details/gtkujnpxkb.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ppjwa.cn/Article/details/gtsaofrekr.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jiagoushi.top/Article/details/gtpkmutbon.html

[C10] 变量作用域
来源：http://dali.nwbrower.top/Article/details/gtyegdxzbf.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hysaishi.cn/Article/details/gttdcsuxwn.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xuanzx.com/Article/details/gtpaliaggl.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.shuidangran.top/Article/details/gtxdjemjsg.html

TS:   同 JS
来源：http://dali.chenlongwang.top/Article/details/gtpvuolxxp.html

Java: 方法内为块级作用域
来源：http://dali.shzxlz.cn/Article/details/gtqxqxkxfa.html

Go:   花括号块级作用域
来源：http://dali.cqqwz.cn/Article/details/gtpxpwvsqh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.sufxvd.cn/Article/details/gtksqbglts.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gtiogatjqb.html

[C11] 模块导入与导出
来源：http://dali.yuanzhike.top/Article/details/gtymafxiuf.html

Py:   from module import func
来源：http://dali.cheryme.top/Article/details/gtxdvunhuu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yuxming.cn/Article/details/gtuycfzwlr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinqigfzy.top/Article/details/gtgdochvvo.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yongpay.top/Article/details/gtzavmfvir.html

Java: import java.util.List;
来源：http://dali.c1oappe.top/Article/details/gtwsjwpyxy.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hnxiangtu.top/Article/details/gtxzsnynxr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hammf.cn/Article/details/gteudlagrp.html

C#:   using System.Text;
来源：http://dali.ppjwa.cn/Article/details/gtnhwowcys.html

[C12] 立即执行函数 IIFE
来源：http://dali.xuanzx.com/Article/details/gtpirqfnll.html

Py:   (lambda: print("run"))()
来源：http://dali.316326.xyz/Article/details/gthkupbfwo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.andypj.xyz/Article/details/gtwmhtjfgk.html

JS:   (() => { console.log("run"); })();
来源：http://dali.nanxuanxn.top/Article/details/gtswvblpsx.html

TS:   (() => { console.log("run"); })();
来源：http://dali.tianlin.xyz/Article/details/gtyukmczaa.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sweek.top/Article/details/gtylfagbff.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yonumen.top/Article/details/gtzvhxchvc.html

Ruby: -> { puts "run" }.call
来源：http://dali.guowangkeji.top/Article/details/gtjvwowyys.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cucudq.cn/Article/details/gteyycgivx.html

[C13] 类型声明 / 类型注解
来源：http://dali.yvedp.cn/Article/details/gtasywmuhf.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.bjfxy.top/Article/details/gtvjvnzbtt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzwkzyjbl.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.svipenyu.cn/Article/details/gtjdnknpiy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gtkcraecos.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gtvmjushhf.html

Go:   func add(a, b int) int
来源：http://dali.hnxiangtu.top/Article/details/gtmqfpsxdt.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ydzc1.top/Article/details/gtryrmpldv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.pycfn.com/Article/details/gtpvoqnfbm.html

[C14] 泛型函数
来源：http://dali.havefunace.top/Article/details/gttzujomtg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.gzhubu.top/Article/details/gtwsjusczh.html

PHP:  // 无泛型
来源：http://dali.sxryk.cn/Article/details/gtgvygetdu.html

JS:   // 无泛型
来源：http://dali.vqdsnc.cn/Article/details/gtesnkkzlc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.guannengcc.top/Article/details/gtrevpylos.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.havefunace.top/Article/details/gtnatzxtjr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jiagoushi.top/Article/details/gtbzfxtiod.html

Ruby: # 无泛型
来源：http://dali.yj20258.top/Article/details/gtheodkzcx.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cdnleiting.top/Article/details/gtddtggsmg.html

[C15] 解构 / 展开参数
来源：http://dali.yj20258.top/Article/details/gttpjntzqq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.fzhhl.top/Article/details/gtogahgrnv.html

PHP:  [$a, $b] = $pair;
来源：http://dali.havefunace.top/Article/details/gtrmpavtnp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtfutxyiif.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.pycfn.com/Article/details/gtufomvtfy.html

Java: // 无解构
来源：http://dali.yueranfly.top/Article/details/gtzrroomcz.html

Go:   // 无解构
来源：http://dali.gaohongyu789.top/Article/details/gtlqdurngh.html

Ruby: a, b = pair
来源：http://dali.ivvv.top/Article/details/gtajbkuppw.html

C#:   var (a, b) = pair;
来源：http://dali.zdqjudy.top/Article/details/gtkqrqfute.html

[C16] 函数 / 方法重载
来源：http://dali.yanxiufei.cn/Article/details/gtcfgljhcz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.bjfxy.top/Article/details/gtlchsckdh.html

PHP:  // 无重载
来源：http://dali.xziqi.cn/Article/details/gtjnqjryaz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jiagoushi.top/Article/details/gtuegnodcl.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.redwolf501.top/Article/details/gtzelcpdhc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xuetiantiany.cn/Article/details/gthrekprzj.html

Go:   // 无重载：用不同函数名
来源：http://dali.aizwys.cn/Article/details/gtrxikeqvd.html

Ruby: # 无重载：靠动态参数
来源：http://dali.nanxinkj.top/Article/details/gtknonbozm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.9152youxi.cn/Article/details/gtkwpayddb.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtoevmxqel.html

D. 数组 / 列表 / 集合
来源：http://dali.yj20258888.top/Article/details/gtzrusvgji.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtdyrmfpnt.html

[D01] 创建数组 / 列表
来源：http://dali.yuanzhike.top/Article/details/gtunonyuds.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yongpay.top/Article/details/gtohrczoct.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.kuanghao11.cn/Article/details/gtnicifaay.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gaohongyu789.top/Article/details/gtrmyddszq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.mhx1999.top/Article/details/gtskibonqb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yuxming.cn/Article/details/gtbdhbovss.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yvedp.cn/Article/details/gtpmhpezhf.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xuanzx.com/Article/details/gtvaymfyis.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.kuanghao11.cn/Article/details/gtdyqawcgz.html

[D02] 追加元素到末尾
来源：http://dali.zhixingplan.top/Article/details/gtlkavwscw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhongyouzk.top/Article/details/gtczwyxeid.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cheryme.top/Article/details/gthydcrqju.html

JS:   arr.push(4);
来源：http://dali.meibo888.top/Article/details/gtrizliinr.html

TS:   arr.push(4);
来源：http://dali.hammf.cn/Article/details/gtprjqszcm.html

Java: list.add(4);
来源：http://dali.9152youxi.cn/Article/details/gtqaacaaft.html

Go:   arr = append(arr, 4)
来源：http://dali.guowangkeji.top/Article/details/gtihjfcnks.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xylfe.cn/Article/details/gttoxirjjh.html

C#:   list.Add(4);
来源：http://dali.birdmap.top/Article/details/gtwxmxwmhd.html

[D03] 在指定位置插入元素
来源：http://dali.sxryk.cn/Article/details/gtfswszkzo.html

Py:   arr.insert(0, 0)
来源：http://dali.hnqzz.top/Article/details/gtwkbvselt.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hnqzz.top/Article/details/gtczevguav.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shuidangran.top/Article/details/gtthhawyuw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yongpay.top/Article/details/gtiukupuyx.html

Java: list.add(0, 0);
来源：http://dali.xziqi.cn/Article/details/gtntrgkeig.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinqigfzy.top/Article/details/gtrwxeirau.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shangyingyoupin.top/Article/details/gthfjbpnfl.html

C#:   list.Insert(0, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtvbriukxt.html

[D04] 删除元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtknzqyxsz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.nanxinkj.top/Article/details/gtouacgijn.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtklnesxem.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.chenlongwang.top/Article/details/gthjquqhqu.html

TS:   arr.splice(0, 1);
来源：http://dali.ehwqpu.com/Article/details/gtsxftjgzp.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ehwqpu.com/Article/details/gtjkwkumxz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jianghu66.top/Article/details/gtgxlsfbnc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hysaishi.cn/Article/details/gtkshprtup.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.guowangkeji.top/Article/details/gtixrixgqe.html

[D05] 访问与修改元素
来源：http://dali.ybcxt.top/Article/details/gtrqgakpxu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangshuangyany.cn/Article/details/gtfdbbicob.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenzaomai.com/Article/details/gtbnzfhmvi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.nwbrower.top/Article/details/gtzfbywgqq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ybcxt.top/Article/details/gtqcaegstt.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hnxiangtu.top/Article/details/gtzoklaoom.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hfpthk.cn/Article/details/gthezpawuv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cucudq.cn/Article/details/gtyapumllc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zycfv.cn/Article/details/gtnddzmthi.html

[D06] 数组长度
来源：http://dali.dianchejie.cn/Article/details/gtemhhsodp.html

Py:   len(arr)
来源：http://dali.daxiang520.top/Article/details/gtfsgwvfqn.html

PHP:  count($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtjxubvbio.html

JS:   arr.length
来源：http://dali.ivvv.top/Article/details/gtrxqlrzrh.html

TS:   arr.length
来源：http://dali.fzhhl.top/Article/details/gttmvyysex.html


<!-- 参考信息 -->