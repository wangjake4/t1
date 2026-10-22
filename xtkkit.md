代发 wailian999

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.guowangkeji.top/Article/details/gt2lydldpyp.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yj20258888.top/Article/details/gt2cokentpp.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.0kj1m.cn/Article/details/gt2cwwrarpk.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ixzhrhnl.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.wangshuangyany.cn/Article/details/gt2lhrldbab.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.sufxvd.cn/Article/details/gt2uxmbwjzy.html

[B07] while 循环
来源：http://dali.pengpengdd.cyou/Article/details/gt2gmdjtizu.html

Py:   while i < 10: i += 1
来源：http://dali.yvedp.cn/Article/details/gt2rtzeawpg.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.ydzc1.top/Article/details/gt2kaxgyrqx.html

JS:   while (i < 10) { i++; }
来源：http://dali.kuanghao11.cn/Article/details/gt2tgzwmcof.html

TS:   while (i < 10) { i++; }
来源：http://dali.316326.xyz/Article/details/gt2pztzfwcd.html

Java: while (i < 10) { i++; }
来源：http://dali.tian-w.cn/Article/details/gt2xbhctwug.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.aibaodan.cn/Article/details/gt2jpixpzxt.html

Ruby: while i < 10; i += 1; end
来源：http://dali.tanke756.top/Article/details/gt2swzbjjxy.html

C#:   while (i < 10) { i++; }
来源：http://dali.gzhubu.top/Article/details/gt2hbphxrpc.html

[B08] do-while（至少执行一次）
来源：http://dali.guannengcc.top/Article/details/gt2rlrazbzz.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.andypj.xyz/Article/details/gt2vutamiyq.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yj202588.top/Article/details/gt2vbhpzzqz.html

JS:   do { i++; } while (i < 10);
来源：http://dali.haohaochexian.top/Article/details/gt2qoawxgsx.html

TS:   do { i++; } while (i < 10);
来源：http://dali.gogol.net.cn/Article/details/gt2kmhhjjpo.html

Java: do { i++; } while (i < 10);
来源：http://dali.vqdsnc.cn/Article/details/gt2kfyfhwdd.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jyoumei.cn/Article/details/gt2jnmqgxhg.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yonumen.top/Article/details/gt2holprpnl.html

C#:   do { i++; } while (i < 10);
来源：http://dali.nanxinkj.top/Article/details/gt2qsjakkxs.html

[B09] break 与 continue
来源：http://dali.aizwys.cn/Article/details/gt2rcmmzigf.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.meibo888.top/Article/details/gt2nkajeddk.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.birdmap.top/Article/details/gt2rzixavyi.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2qnprnpmc.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yonumen.top/Article/details/gt2wymajfpz.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ydzc1.top/Article/details/gt2gwrvrqus.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhoulong.xyz/Article/details/gt2dhhtggcl.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhiwuduotai.top/Article/details/gt2hxwerwiq.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sweek.top/Article/details/gt2ogunajqi.html

[B10] 遍历同时拿索引
来源：http://dali.daxiang520.top/Article/details/gt2iesusqxa.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.gotoacloud.top/Article/details/gt2azfaujwx.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yuxming.cn/Article/details/gt2aujaekeu.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.chenzaomai.com/Article/details/gt2uljgbsat.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.dashuyun.cn/Article/details/gt2ptmxpzdu.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yvedp.cn/Article/details/gt2jjlcbegk.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhiwuduotai.top/Article/details/gt2vgqdljvk.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhiwuduotai.top/Article/details/gt2awajkwls.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.cdnleiting.top/Article/details/gt2dzbvvwsd.html

[B11] 生成数字序列 / 区间
来源：http://dali.fengsongda.top/Article/details/gt2exjuslsd.html

Py:   list(range(0, 10, 2))
来源：http://dali.sxryk.cn/Article/details/gt2ehtpagvo.html

PHP:  range(0, 10, 2);
来源：http://dali.jianghu66.top/Article/details/gt2yswtptoo.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tianlin.xyz/Article/details/gt2vifxnfvg.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.andypj.xyz/Article/details/gt2oxunoron.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.aibaodan.cn/Article/details/gt2jjwcuchw.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.pycfn.com/Article/details/gt2fexlwjse.html

Ruby: (0...10).step(2).to_a
来源：http://dali.mhx1999.top/Article/details/gt2itdtnwaz.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhixingplan.top/Article/details/gt2gdsuecij.html

[B12] 跳出多层循环
来源：http://dali.chenjidiqi.icu/Article/details/gt2kapexxag.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.316326.xyz/Article/details/gt2yvvzqmwo.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zozsvqyk.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.daria6918.cn/Article/details/gt2inomxcla.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.quarkkingdee.top/Article/details/gt2qugfyson.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.feifeiyinyue.top/Article/details/gt2rhezuhts.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.wangdashe.top/Article/details/gt2djcnjlmp.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.aibaodan.cn/Article/details/gt2qbmxhfns.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yuanzhike.top/Article/details/gt2abasqukq.html

[B13] 判断是否为数字
来源：http://dali.ybcxt.top/Article/details/gt2clretqig.html

Py:   isinstance(x, (int, float))
来源：http://dali.zdqjudy.top/Article/details/gt2disypnzx.html

PHP:  is_numeric($x)
来源：http://dali.cashguo.top/Article/details/gt2oxzybnck.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gotoacloud.top/Article/details/gt2qpslnfdi.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lqcbdzgv.html

Java: x instanceof Number
来源：http://dali.xinyue.icu/Article/details/gt2syibhzyj.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.gzhubu.top/Article/details/gt2owwkkefb.html

Ruby: x.is_a?(Numeric)
来源：http://dali.svipenyu.cn/Article/details/gt2wfjafndf.html

C#:   x is int or double or decimal
来源：http://dali.pycfn.com/Article/details/gt2jndequym.html

[B14] 判断值是否在集合内
来源：http://dali.smart0.xyz/Article/details/gt2hufaygel.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hysaishi.cn/Article/details/gt2oezwodfl.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nzxmtthr.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.gotoacloud.top/Article/details/gt2xevjktyr.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hysaishi.cn/Article/details/gt2eqnycjda.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.iojbl.cn/Article/details/gt2ouaotszq.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hnqzz.top/Article/details/gt2qvkbqtkh.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yuanzhike.top/Article/details/gt2xgoywgmx.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yongpay.top/Article/details/gt2fmlmuqbs.html

[B15] 布尔运算与取反
来源：http://dali.hywenlv.cn/Article/details/gt2ibpaidsw.html

Py:   a and b or not c
来源：http://dali.ppjwa.cn/Article/details/gt2zxcvnmhb.html

PHP:  $a && $b || !$c
来源：http://dali.sxryk.cn/Article/details/gt2hojhgkro.html

JS:   a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gt2ftcwqwwv.html

TS:   a && b || !c
来源：http://dali.gzhubu.top/Article/details/gt2zaskisbh.html

Java: a && b || !c
来源：http://dali.sysykeji.top/Article/details/gt2allachzc.html

Go:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gt2eymankpz.html

Ruby: a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gt2ccxeuedn.html

C#:   a && b || !c
来源：http://dali.shuidangran.top/Article/details/gt2skctxise.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hnqzz.top/Article/details/gt2lfnuestz.html

Py:   if not data: return
来源：http://dali.redwolf501.top/Article/details/gt2yfkyxwev.html

PHP:  if (!$data) { return; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kudsutty.html

JS:   if (!data) return;
来源：http://dali.tianlin.xyz/Article/details/gt2yaohkkmy.html

TS:   if (!data) return;
来源：http://dali.dashuyun.cn/Article/details/gt2gwttyxgo.html

Java: if (data == null) return;
来源：http://dali.snrcjt.cn/Article/details/gt2vyyypnmh.html

Go:   if data == nil { return }
来源：http://dali.guowangkeji.top/Article/details/gt2dushuksr.html

Ruby: return if data.nil?
来源：http://dali.shzxlz.cn/Article/details/gt2hvlphdpg.html

C#:   if (data == null) return;
来源：http://dali.zhiwuduotai.top/Article/details/gt2crqbvefv.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2wttpadgy.html

C. 函数与作用域
来源：http://dali.hnxiangtu.top/Article/details/gt2dllqmkkv.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2dabupyve.html

[C01] 定义函数
来源：http://dali.bjfxy.top/Article/details/gt2kulpqlts.html

Py:   def add(a, b): return a + b
来源：http://dali.tianlin.xyz/Article/details/gt2zbmqhoyd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shzxlz.cn/Article/details/gt2enzgnmdi.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gt2syufaepb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gt2emvulerp.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gt2wwiolepg.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ybcxt.top/Article/details/gt2eldymhtv.html

Ruby: def add(a, b); a + b; end
来源：http://dali.9152youxi.cn/Article/details/gt2vcademgg.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gt2nauwuqpa.html

[C02] 默认参数
来源：http://dali.tanke756.top/Article/details/gt2mlwxffzw.html

Py:   def greet(name="World"): return name
来源：http://dali.zhiwuduotai.top/Article/details/gt2wmqzqnyp.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jianghu66.top/Article/details/gt2gytnjxyv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hnqzz.top/Article/details/gt2zynedtac.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2hacfpbzf.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hysaishi.cn/Article/details/gt2angflmtq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cucudq.cn/Article/details/gt2jsbdwhah.html

Ruby: def greet(name = "World") = name
来源：http://dali.yj20258.top/Article/details/gt2dvcfxfnn.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.sxryk.cn/Article/details/gt2rppoqwkt.html

[C03] 可变参数
来源：http://dali.chenlongwang.top/Article/details/gt2ypomupzz.html

Py:   def total(*args): return sum(args)
来源：http://dali.sysykeji.top/Article/details/gt2cxjixdwx.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rtkdshtm.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.c1oappe.top/Article/details/gt2praeiafz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhoulong.xyz/Article/details/gt2rbdbpaxf.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yj202588.top/Article/details/gt2pmtfztoq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.gotoacloud.top/Article/details/gt2pqrlvgsm.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinqigfzy.top/Article/details/gt2qmpsbumf.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.sysykeji.top/Article/details/gt2xscwkibk.html

[C04] 命名参数 / 关键字参数
来源：http://dali.chenzaomai.com/Article/details/gt2mdmrygyr.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.smart0.xyz/Article/details/gt2evqxainj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sjodjfvv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cucudq.cn/Article/details/gt2foyjtsql.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fijotign.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.quarkkingdee.top/Article/details/gt2dzpjwggl.html

Go:   // 无：用配置结构体参数
来源：http://dali.daxiang520.top/Article/details/gt2olqaaucj.html

Ruby: f(a: 1, b: 2)
来源：http://dali.tian-w.cn/Article/details/gt2xwcxcjex.html

C#:   f(a: 1, b: 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hxnrafxj.html

[C05] 返回多个值
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mlqmxblx.html

Py:   return a, b
来源：http://dali.chenjidiqi.icu/Article/details/gt2rxwfbwli.html

PHP:  return [$a, $b];
来源：http://dali.yvedp.cn/Article/details/gt2bylmwzkp.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shzxlz.cn/Article/details/gt2jejvqeli.html

TS:   return { a, b };
来源：http://dali.jiagoushi.top/Article/details/gt2klpvhcoq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cucudq.cn/Article/details/gt2mvbnfzyr.html

Go:   return a, b
来源：http://dali.sweek.top/Article/details/gt2qmdgpves.html

Ruby: return a, b
来源：http://dali.xuanzx.com/Article/details/gt2saarviof.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jianghu66.top/Article/details/gt2bgorbwqk.html

[C06] 匿名函数 / lambda
来源：http://dali.nwbrower.top/Article/details/gt2jmfjqmwo.html

Py:   square = lambda x: x * x
来源：http://dali.316326.xyz/Article/details/gt2ktrozhvt.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.nanxinkj.top/Article/details/gt2zquscmjc.html

JS:   const square = x => x * x;
来源：http://dali.gogol.net.cn/Article/details/gt2zzkrilbk.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yj20258888.top/Article/details/gt2rtugfgtn.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.smart0.xyz/Article/details/gt2zrczeueo.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.9152youxi.cn/Article/details/gt2xwmwdzrt.html

Ruby: square = ->(x) { x * x }
来源：http://dali.wangdashe.top/Article/details/gt2ifchycvb.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ndvglqzq.html

[C07] 把函数作为参数传入
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eosunhfn.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.guowangkeji.top/Article/details/gt2fznumrry.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2ggdckcbp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yj20258888.top/Article/details/gt2pkhrjfin.html

TS:   arr.map(String)
来源：http://dali.redwolf501.top/Article/details/gt2atklisyi.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.kuanghao11.cn/Article/details/gt2laarobrn.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.sxryk.cn/Article/details/gt2nigckkuk.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2ektnceyy.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shzxlz.cn/Article/details/gt2hbyccjxk.html

[C08] 闭包
来源：http://dali.fzhhl.top/Article/details/gt2jwurzdby.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yongpay.top/Article/details/gt2kedoesrz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xinyue.icu/Article/details/gt2reagpbgr.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.dashuyun.cn/Article/details/gt2eesjjooh.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ybcxt.top/Article/details/gt2ayrnyfcu.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cucudq.cn/Article/details/gt2tovdeylc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2whmotxdh.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hnqzz.top/Article/details/gt2ahqthavs.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2tjbzwzno.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2myjbpbrl.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.smart0.xyz/Article/details/gt2pkucpavw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jqgufenzy.top/Article/details/gt2epaoexic.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jianghu66.top/Article/details/gt2rkvayuak.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sysykeji.top/Article/details/gt2hbmzpcvv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.316326.xyz/Article/details/gt2onqoacmm.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xuanzx.com/Article/details/gt2qjwzsbuu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shuidangran.top/Article/details/gt2exbcdqqo.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.chenzaomai.com/Article/details/gt2cbcejycf.html

[C10] 变量作用域
来源：http://dali.chenlongwang.top/Article/details/gt2jxhvvdnj.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cheryme.top/Article/details/gt2fjtxzrps.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yuanzhike.top/Article/details/gt2tymaojci.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hongshengwenyu.top/Article/details/gt2yauanryh.html

TS:   同 JS
来源：http://dali.jinqigufen.top/Article/details/gt2sapjojvm.html

Java: 方法内为块级作用域
来源：http://dali.ivvv.top/Article/details/gt2fphiqjnr.html

Go:   花括号块级作用域
来源：http://dali.gaohongyu789.top/Article/details/gt2bsdpdxkq.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pxcuylms.html

C#:   块级作用域
来源：http://dali.nanxuanxn.top/Article/details/gt2yrkxwetn.html

[C11] 模块导入与导出
来源：http://dali.cqqwz.cn/Article/details/gt2nlrxxkrk.html

Py:   from module import func
来源：http://dali.pycfn.com/Article/details/gt2xktuvbee.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.gzhubu.top/Article/details/gt2jbbbyaee.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.tian-w.cn/Article/details/gt2wvfhuxcj.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.mhx1999.top/Article/details/gt2mpvaxpwf.html

Java: import java.util.List;
来源：http://dali.gaohongyu789.top/Article/details/gt2hoqesbjt.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.gotoacloud.top/Article/details/gt2wcfvbcnb.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pkygxbuz.html

C#:   using System.Text;
来源：http://dali.yueranfly.top/Article/details/gt2odwudsxk.html

[C12] 立即执行函数 IIFE
来源：http://dali.nwbrower.top/Article/details/gt2qgmbsiyb.html

Py:   (lambda: print("run"))()
来源：http://dali.zycfv.cn/Article/details/gt2foltlxui.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shuidangran.top/Article/details/gt2hpmanzov.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hnqzz.top/Article/details/gt2qjssmvgz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.wangshuangyany.cn/Article/details/gt2yrgiekux.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.wangshuangyany.cn/Article/details/gt2wjrkmqzc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.feifeiyinyue.top/Article/details/gt2juynduds.html

Ruby: -> { puts "run" }.call
来源：http://dali.cucudq.cn/Article/details/gt2aaxkfrcb.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.guowangkeji.top/Article/details/gt2lsqofbjq.html

[C13] 类型声明 / 类型注解
来源：http://dali.ivvv.top/Article/details/gt2toqozauk.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.svipenyu.cn/Article/details/gt2endgnldp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gt2crrewdmf.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shzxlz.cn/Article/details/gt2fjenzkem.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yoljpvpr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gt2bidypwkt.html

Go:   func add(a, b int) int
来源：http://dali.zhongyouzk.top/Article/details/gt2wkztsenl.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gogol.net.cn/Article/details/gt2pktivnhj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yongpay.top/Article/details/gt2hydauvwl.html

[C14] 泛型函数
来源：http://dali.0kj1m.cn/Article/details/gt2nxkcmbro.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.wangdashe.top/Article/details/gt2wipbykts.html

PHP:  // 无泛型
来源：http://dali.jqgfzy.top/Article/details/gt2ghdncvpo.html

JS:   // 无泛型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rsdxzidl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shuidangran.top/Article/details/gt2pgndbycj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.316326.xyz/Article/details/gt2xkdapvlo.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.guannengcc.top/Article/details/gt2nrozsldz.html

Ruby: # 无泛型
来源：http://dali.redwolf501.top/Article/details/gt2oclvzrsv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yj20258.top/Article/details/gt2fzhxmffj.html

[C15] 解构 / 展开参数
来源：http://dali.xinyue.icu/Article/details/gt2zwmhhran.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yuanzhike.top/Article/details/gt2tmafymug.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ydzc1.top/Article/details/gt2hhhhbpsy.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lhhceeqz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.aibaodan.cn/Article/details/gt2ssyzfqld.html

Java: // 无解构
来源：http://dali.zhengqikj.top/Article/details/gt2pghjoxmz.html

Go:   // 无解构
来源：http://dali.yj202588.top/Article/details/gt2wwmdlcjc.html

Ruby: a, b = pair
来源：http://dali.yanxiufei.cn/Article/details/gt2uldrzkkc.html

C#:   var (a, b) = pair;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vvttwiej.html

[C16] 函数 / 方法重载
来源：http://dali.haohaochexian.top/Article/details/gt2ajlzpckx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.gaohongyu789.top/Article/details/gt2wkjpiqkz.html

PHP:  // 无重载
来源：http://dali.guowangkeji.top/Article/details/gt2dwpqruqh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.kuanghao11.cn/Article/details/gt2pwjnfldu.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shanyushiyangtech.top/Article/details/gt2easichkc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sweek.top/Article/details/gt2uuzhjweq.html

Go:   // 无重载：用不同函数名
来源：http://dali.cheryme.top/Article/details/gt2zooczkuc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2rsgfnzbz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ppjwa.cn/Article/details/gt2tobvkosm.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2huikylii.html

D. 数组 / 列表 / 集合
来源：http://dali.yj20258888.top/Article/details/gt2uxywbwlb.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2dfgbtymp.html

[D01] 创建数组 / 列表
来源：http://dali.aizwys.cn/Article/details/gt2gosvdlei.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jejakyin.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hfpthk.cn/Article/details/gt2dyubganb.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jyoumei.cn/Article/details/gt2mmfptquu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.havefunace.top/Article/details/gt2anyrrnbp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cdnleiting.top/Article/details/gt2bpziezig.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.guannengcc.top/Article/details/gt2bmpxrtvj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.pengpengdd.cyou/Article/details/gt2dqaqawkr.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eqakgqny.html

[D02] 追加元素到末尾
来源：http://dali.yonumen.top/Article/details/gt2ovbxrzje.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jqgufenzy.top/Article/details/gt2udeynazw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.chenlongwang.top/Article/details/gt2oacuylhx.html

JS:   arr.push(4);
来源：http://dali.shzxlz.cn/Article/details/gt2unzzuhco.html

TS:   arr.push(4);
来源：http://dali.aizwys.cn/Article/details/gt2fyfiedtv.html

Java: list.add(4);
来源：http://dali.9152youxi.cn/Article/details/gt2uvoxoaos.html

Go:   arr = append(arr, 4)
来源：http://dali.shzxlz.cn/Article/details/gt2fnokhfld.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jlsjyb.cn/Article/details/gt2ebhuotwl.html

C#:   list.Add(4);
来源：http://dali.zhixingplan.top/Article/details/gt2ffdzwwrr.html

[D03] 在指定位置插入元素
来源：http://dali.redwolf501.top/Article/details/gt2zliepoyk.html

Py:   arr.insert(0, 0)
来源：http://dali.jqgfzy.top/Article/details/gt2hwchcyxo.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.9152youxi.cn/Article/details/gt2ibkyqwcn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yuxming.cn/Article/details/gt2bfwrldxd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yuxming.cn/Article/details/gt2jihzejyj.html

Java: list.add(0, 0);
来源：http://dali.snrcjt.cn/Article/details/gt2ajpbhnzo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.nanxuanxn.top/Article/details/gt2gaozajvx.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hfpthk.cn/Article/details/gt2ungeorqx.html

C#:   list.Insert(0, 0);
来源：http://dali.xinyue.icu/Article/details/gt2hixczhee.html

[D04] 删除元素
来源：http://dali.chenlongwang.top/Article/details/gt2zmwxjyxb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.guannengcc.top/Article/details/gt2ybfivxih.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xuanzx.com/Article/details/gt2tvpowqzn.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jyoumei.cn/Article/details/gt2uxjtzywj.html

TS:   arr.splice(0, 1);
来源：http://dali.jlsjyb.cn/Article/details/gt2bgybpgkz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jlsjyb.cn/Article/details/gt2cpwtoxwn.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gogol.net.cn/Article/details/gt2nnuvfpvp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.nanxuanxn.top/Article/details/gt2efwzyxzw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hnqzz.top/Article/details/gt2seahnafd.html

[D05] 访问与修改元素
来源：http://dali.9152youxi.cn/Article/details/gt2xxjqiaoh.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxinkj.top/Article/details/gt2ijdjbavn.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.guannengcc.top/Article/details/gt2vjrscuwd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cucudq.cn/Article/details/gt2ptefttmy.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cashguo.top/Article/details/gt2fnwtcjgq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hfpthk.cn/Article/details/gt2uqiccyrq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gzhubu.top/Article/details/gt2cnlfkooq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.316326.xyz/Article/details/gt2orsaykid.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.havefunace.top/Article/details/gt2brcuohsm.html

[D06] 数组长度
来源：http://dali.yongpay.top/Article/details/gt2dufdgavh.html

Py:   len(arr)
来源：http://dali.daria6918.cn/Article/details/gt2bxazatkh.html

PHP:  count($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vxwssbeo.html

JS:   arr.length
来源：http://dali.hysaishi.cn/Article/details/gt2fmovcihl.html

TS:   arr.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ysoxzgcm.html

Java: list.size();
来源：http://dali.gzhubu.top/Article/details/gt2whpcfohk.html

Go:   len(arr)
来源：http://dali.yongpay.top/Article/details/gt2bdsbhoev.html

Ruby: arr.length; arr.size
来源：http://dali.zhengqikj.top/Article/details/gt2wfdpuwyh.html

C#:   list.Count;
来源：http://dali.hnxiangtu.top/Article/details/gt2azqeecer.html


<!-- 参考信息 -->