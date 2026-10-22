代发 wailian999

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.fengsongda.top/Article/details/gtmogzacig.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.cucudq.cn/Article/details/gttijiovib.html

[B07] while 循环
来源：http://dali.sufxvd.cn/Article/details/gtmzpkoeal.html

Py:   while i < 10: i += 1
来源：http://dali.c1oappe.top/Article/details/gtqikbpczp.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.aibaodan.cn/Article/details/gtdkedjoab.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhengqikj.top/Article/details/gthcwoqqyc.html

TS:   while (i < 10) { i++; }
来源：http://dali.yj20258888.top/Article/details/gtahonpcvg.html

Java: while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gtqwmpahaa.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.cdnleiting.top/Article/details/gtauivhnwl.html

Ruby: while i < 10; i += 1; end
来源：http://dali.ehwqpu.com/Article/details/gtiuvdepzj.html

C#:   while (i < 10) { i++; }
来源：http://dali.cheryme.top/Article/details/gtzsrmphhw.html

[B08] do-while（至少执行一次）
来源：http://dali.shanyushiyangtech.top/Article/details/gtguseajjl.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.tanke756.top/Article/details/gtfctrvwit.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.aizwys.cn/Article/details/gtugzrkfuk.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yuanzhike.top/Article/details/gtxdhdzdjo.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zycfv.cn/Article/details/gtckcmvuwl.html

Java: do { i++; } while (i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gtotwnobfa.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hongshengwenyu.top/Article/details/gtpjumipal.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.shangyingyoupin.top/Article/details/gtsbxphpbh.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jinqigfzy.top/Article/details/gtrlfrkzad.html

[B09] break 与 continue
来源：http://dali.cqqwz.cn/Article/details/gtsalkqoyj.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.nanxinkj.top/Article/details/gtixhckxor.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxacmflrg.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gaohongyu789.top/Article/details/gtiqrmciul.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfkuurhsr.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tian-w.cn/Article/details/gtwmmjcgws.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.xuanzx.com/Article/details/gteicffudr.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.fzhhl.top/Article/details/gtqevsmoia.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxuanxn.top/Article/details/gtvmnyyauv.html

[B10] 遍历同时拿索引
来源：http://dali.nwbrower.top/Article/details/gtdnuicgnv.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jiagoushi.top/Article/details/gtetvbubfh.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.gogol.net.cn/Article/details/gthdhfzrwm.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.havefunace.top/Article/details/gtwsnunrmh.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ppjwa.cn/Article/details/gtrosjrehf.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hnxiangtu.top/Article/details/gtpdschaav.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.havefunace.top/Article/details/gtlvipnnki.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jianghu66.top/Article/details/gtiumbpvel.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthnrnavva.html

[B11] 生成数字序列 / 区间
来源：http://dali.jianghu66.top/Article/details/gthqeobhbl.html

Py:   list(range(0, 10, 2))
来源：http://dali.ppjwa.cn/Article/details/gtrqtyovrj.html

PHP:  range(0, 10, 2);
来源：http://dali.zhongyouzk.top/Article/details/gtzzdbfowj.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jqgufenzy.top/Article/details/gtbrvofiez.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.pycfn.com/Article/details/gtraqtutpw.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.haohaochexian.top/Article/details/gtaoeqpsyx.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jqgufenzy.top/Article/details/gtdzwflwrn.html

Ruby: (0...10).step(2).to_a
来源：http://dali.0kj1m.cn/Article/details/gtlzmkpocb.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yongpay.top/Article/details/gtlgchlcxr.html

[B12] 跳出多层循环
来源：http://dali.hnqzz.top/Article/details/gthkcrwkac.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jyoumei.cn/Article/details/gticauplai.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlonqpijc.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmouqibny.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tianlin.xyz/Article/details/gtdtifagiu.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenjidiqi.icu/Article/details/gthmfptsjo.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.fzhhl.top/Article/details/gtabspntxb.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvosenwwp.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.tanke756.top/Article/details/gtdxbwlvwe.html

[B13] 判断是否为数字
来源：http://dali.316326.xyz/Article/details/gtclkyndyn.html

Py:   isinstance(x, (int, float))
来源：http://dali.hongshengwenyu.top/Article/details/gtnhbuulzg.html

PHP:  is_numeric($x)
来源：http://dali.daxiang520.top/Article/details/gtebrqawbo.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xinyue.icu/Article/details/gtrbcqzvrq.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttjftiksw.html

Java: x instanceof Number
来源：http://dali.ppjwa.cn/Article/details/gtsnldyelt.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.chenjidiqi.icu/Article/details/gterxaxeao.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zdqjudy.top/Article/details/gtwjizmgih.html

C#:   x is int or double or decimal
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbdwxpmdz.html

[B14] 判断值是否在集合内
来源：http://dali.shanyushiyangtech.top/Article/details/gtkukicdxl.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhongyouzk.top/Article/details/gthwuazcvj.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.gotoacloud.top/Article/details/gtysuexmvh.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cashguo.top/Article/details/gtahmpvcpy.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.gogol.net.cn/Article/details/gtzkulynqb.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.tanke756.top/Article/details/gtznsbazlu.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.andypj.xyz/Article/details/gtckwvgqbe.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.daria6918.cn/Article/details/gtwzwwpynw.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnrtydobl.html

[B15] 布尔运算与取反
来源：http://dali.shangyingyoupin.top/Article/details/gtrgrzbwzm.html

Py:   a and b or not c
来源：http://dali.cashguo.top/Article/details/gtrskrtkap.html

PHP:  $a && $b || !$c
来源：http://dali.shzxlz.cn/Article/details/gtfuelirpv.html

JS:   a && b || !c
来源：http://dali.hongshengwenyu.top/Article/details/gtabugchqr.html

TS:   a && b || !c
来源：http://dali.yueranfly.top/Article/details/gtktczkjdb.html

Java: a && b || !c
来源：http://dali.yj20258888.top/Article/details/gtaoqxipnk.html

Go:   a && b || !c
来源：http://dali.iojbl.cn/Article/details/gtfiqsvwgn.html

Ruby: a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gtdsleyqaq.html

C#:   a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtlekjhwjg.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hongshengwenyu.top/Article/details/gtxbzfajvl.html

Py:   if not data: return
来源：http://dali.andypj.xyz/Article/details/gtwbpnntsj.html

PHP:  if (!$data) { return; }
来源：http://dali.xuetiantiany.cn/Article/details/gtyemrcibq.html

JS:   if (!data) return;
来源：http://dali.fzhhl.top/Article/details/gtpmyijwme.html

TS:   if (!data) return;
来源：http://dali.svipenyu.cn/Article/details/gtmvyupwio.html

Java: if (data == null) return;
来源：http://dali.hywenlv.cn/Article/details/gtnuwyqgol.html

Go:   if data == nil { return }
来源：http://dali.xylfe.cn/Article/details/gtyhjjzsgk.html

Ruby: return if data.nil?
来源：http://dali.sweek.top/Article/details/gtvokjsyam.html

C#:   if (data == null) return;
来源：http://dali.0kj1m.cn/Article/details/gtmctnulps.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtutyyepol.html

C. 函数与作用域
来源：http://dali.yj20258.top/Article/details/gtzvoiulyl.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gthnpajzlb.html

[C01] 定义函数
来源：http://dali.gzhubu.top/Article/details/gtsfmjsisi.html

Py:   def add(a, b): return a + b
来源：http://dali.yj20258.top/Article/details/gtxeffjgsl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.c1oappe.top/Article/details/gttckkhuwi.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gtlmcchhto.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtteekmsen.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtfgaydwfy.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.dashuyun.cn/Article/details/gtygfedgzx.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbecrobpr.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gtiytjakrb.html

[C02] 默认参数
来源：http://dali.nanxuanxn.top/Article/details/gtzqeozubs.html

Py:   def greet(name="World"): return name
来源：http://dali.hywenlv.cn/Article/details/gtwoishzql.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.svipenyu.cn/Article/details/gtbirifewr.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ivvv.top/Article/details/gtfjodzmka.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtvlcdzwqn.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hnxiangtu.top/Article/details/gtofpawllq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jyoumei.cn/Article/details/gtieknbsng.html

Ruby: def greet(name = "World") = name
来源：http://dali.zycfv.cn/Article/details/gtbhehpimf.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gthcafloip.html

[C03] 可变参数
来源：http://dali.hnxiangtu.top/Article/details/gtaqpezspm.html

Py:   def total(*args): return sum(args)
来源：http://dali.cheryme.top/Article/details/gtkyivvhcs.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtyexxrpcr.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.nanxinkj.top/Article/details/gtpomtnnrx.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyvdsevjq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrxlxzjxm.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yj20258888.top/Article/details/gthbuugkra.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jlsjyb.cn/Article/details/gtvaftcytb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.tanke756.top/Article/details/gtsbjhrlxe.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhoulong.xyz/Article/details/gtkbvjspoy.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.gotoacloud.top/Article/details/gtorlifqrk.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shzxlz.cn/Article/details/gtfqohfkbf.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.redwolf501.top/Article/details/gtogorbzqn.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shuidangran.top/Article/details/gtoquoguya.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwdubvvku.html

Go:   // 无：用配置结构体参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnyqsisqa.html

Ruby: f(a: 1, b: 2)
来源：http://dali.fzhhl.top/Article/details/gtkzbbzidb.html

C#:   f(a: 1, b: 2)
来源：http://dali.cheryme.top/Article/details/gtmerwanxw.html

[C05] 返回多个值
来源：http://dali.vqdsnc.cn/Article/details/gtvmuckpks.html

Py:   return a, b
来源：http://dali.yueranfly.top/Article/details/gtvyhbxvon.html

PHP:  return [$a, $b];
来源：http://dali.cdnleiting.top/Article/details/gtyivlgopy.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhiwuduotai.top/Article/details/gtzyyarcpr.html

TS:   return { a, b };
来源：http://dali.shanyushiyangtech.top/Article/details/gtwdtgcqma.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ybcxt.top/Article/details/gtezcomqcz.html

Go:   return a, b
来源：http://dali.hnqzz.top/Article/details/gtltsotgxy.html

Ruby: return a, b
来源：http://dali.hammf.cn/Article/details/gtnmioxyyu.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yj20258888.top/Article/details/gtwqcppbgi.html

[C06] 匿名函数 / lambda
来源：http://dali.yanxiufei.cn/Article/details/gtryajzbtj.html

Py:   square = lambda x: x * x
来源：http://dali.316326.xyz/Article/details/gtiinqcagi.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gthubovptg.html

JS:   const square = x => x * x;
来源：http://dali.aizwys.cn/Article/details/gtujeklult.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.havefunace.top/Article/details/gtmvoppgah.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.aibaodan.cn/Article/details/gtqjzopkln.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jianghu66.top/Article/details/gtigfojkrq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.birdmap.top/Article/details/gtinmeckqn.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.chenzaomai.com/Article/details/gtdirtcjhu.html

[C07] 把函数作为参数传入
来源：http://dali.yj202588.top/Article/details/gtxuqwbmuq.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.smart0.xyz/Article/details/gtkkgrjrpl.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yonumen.top/Article/details/gtphgprshj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.tian-w.cn/Article/details/gtnohneojo.html

TS:   arr.map(String)
来源：http://dali.yangfankeji.com/Article/details/gtmumbkrgk.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.meibo888.top/Article/details/gtsocmwuiu.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.birdmap.top/Article/details/gtuvtxscxh.html

Ruby: arr.map(&:upcase)
来源：http://dali.guowangkeji.top/Article/details/gtboqxteur.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfkpzkdmn.html

[C08] 闭包
来源：http://dali.yangfankeji.com/Article/details/gtngnldosf.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yangfankeji.com/Article/details/gtvjdnzypc.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinqigfzy.top/Article/details/gtifppnect.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.smart0.xyz/Article/details/gtlttoniny.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hfpthk.cn/Article/details/gtidpvaore.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzltytlod.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jiagoushi.top/Article/details/gtrabfhfpx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.9152youxi.cn/Article/details/gtpxoiryeo.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.andypj.xyz/Article/details/gtsltckelw.html

[C09] 递归
来源：http://dali.jinqigfzy.top/Article/details/gtuudlbmol.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xuanzx.com/Article/details/gtldxewzcx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqswrfpna.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.andypj.xyz/Article/details/gtjtxyersi.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwgoltang.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhixingplan.top/Article/details/gtrizbjtgq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhongyouzk.top/Article/details/gtcjbivgxm.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yj20258888.top/Article/details/gtluzlcmsx.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.andypj.xyz/Article/details/gtaoglmxyh.html

[C10] 变量作用域
来源：http://dali.birdmap.top/Article/details/gtkpptqmkd.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.sweek.top/Article/details/gtujjrthdg.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.gzhubu.top/Article/details/gtzoglshzn.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.kuanghao11.cn/Article/details/gthmicladv.html

TS:   同 JS
来源：http://dali.feifeiyinyue.top/Article/details/gtvusdyhhd.html

Java: 方法内为块级作用域
来源：http://dali.jinqigfzy.top/Article/details/gtpufijxlx.html

Go:   花括号块级作用域
来源：http://dali.jinqigufen.top/Article/details/gtnvdbmznw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.chenzaomai.com/Article/details/gthwnlxinf.html

C#:   块级作用域
来源：http://dali.yvedp.cn/Article/details/gtcfcviuoa.html

[C11] 模块导入与导出
来源：http://dali.xuetiantiany.cn/Article/details/gtynjwwsac.html

Py:   from module import func
来源：http://dali.hfpthk.cn/Article/details/gtygfcpaqt.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.quarkkingdee.top/Article/details/gtjhbpeyqy.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.nwbrower.top/Article/details/gtuziwcjby.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gtbnrqiojd.html

Java: import java.util.List;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtplqozxub.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hammf.cn/Article/details/gtmialsvzl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwmkjqlaf.html

C#:   using System.Text;
来源：http://dali.zdqjudy.top/Article/details/gtazstbcuu.html

[C12] 立即执行函数 IIFE
来源：http://dali.ybcxt.top/Article/details/gtldatcgsv.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gtwoblakxz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.feifeiyinyue.top/Article/details/gtgclygarj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shangyingyoupin.top/Article/details/gtvwlumsle.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvorekblq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.pengpengdd.cyou/Article/details/gtqroeqpbw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.pengpengdd.cyou/Article/details/gtvnqfagtp.html

Ruby: -> { puts "run" }.call
来源：http://dali.cashguo.top/Article/details/gtvwycmlxc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.vqdsnc.cn/Article/details/gteggqovvb.html

[C13] 类型声明 / 类型注解
来源：http://dali.gogol.net.cn/Article/details/gtaoobugdf.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.gotoacloud.top/Article/details/gtqxywurue.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgufenzy.top/Article/details/gtpleszztk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hysaishi.cn/Article/details/gtieuixkos.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtevrpblai.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gtvkvdjgzw.html

Go:   func add(a, b int) int
来源：http://dali.bjfxy.top/Article/details/gtpslbfpxq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.smart0.xyz/Article/details/gtdkbnqlkw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gtformljrv.html

[C14] 泛型函数
来源：http://dali.feifeiyinyue.top/Article/details/gtnfvarfex.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zycfv.cn/Article/details/gtkqskzgjp.html

PHP:  // 无泛型
来源：http://dali.haohaochexian.top/Article/details/gtpcjkuulv.html

JS:   // 无泛型
来源：http://dali.iojbl.cn/Article/details/gtnayunqrg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.quarkkingdee.top/Article/details/gtlobyeokq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yongpay.top/Article/details/gttlzekwym.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.havefunace.top/Article/details/gtqceoutsp.html

Ruby: # 无泛型
来源：http://dali.iojbl.cn/Article/details/gtmuuxicrl.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yj202588.top/Article/details/gtxskomefo.html

[C15] 解构 / 展开参数
来源：http://dali.dashuyun.cn/Article/details/gtdistdhxr.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.meibo888.top/Article/details/gthhxqqeoh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.aizwys.cn/Article/details/gtsxhccfyx.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sufxvd.cn/Article/details/gtdhfnnbbg.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yuanzhike.top/Article/details/gtjzdthhxf.html

Java: // 无解构
来源：http://dali.shuidangran.top/Article/details/gtcrabuinr.html

Go:   // 无解构
来源：http://dali.birdmap.top/Article/details/gtfbddtiaz.html

Ruby: a, b = pair
来源：http://dali.dashuyun.cn/Article/details/gtphpoaill.html

C#:   var (a, b) = pair;
来源：http://dali.hongshengwenyu.top/Article/details/gtexslovex.html

[C16] 函数 / 方法重载
来源：http://dali.chenjidiqi.icu/Article/details/gtuprlamxz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.mhx1999.top/Article/details/gtcdyfijaz.html

PHP:  // 无重载
来源：http://dali.jqgfzy.top/Article/details/gtwtamimvq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhengqikj.top/Article/details/gtqgtkxcxy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.chenlongwang.top/Article/details/gtoebrkvho.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ppjwa.cn/Article/details/gtzwxskpnu.html

Go:   // 无重载：用不同函数名
来源：http://dali.nanxuanxn.top/Article/details/gtmxzyjcpf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.aizwys.cn/Article/details/gtfeyjolfw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.redwolf501.top/Article/details/gtefdntnhf.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtgiuugdvf.html

D. 数组 / 列表 / 集合
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxeawikbj.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtscfcrnmp.html

[D01] 创建数组 / 列表
来源：http://dali.wangshuangyany.cn/Article/details/gtrkkooafd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cashguo.top/Article/details/gtiunnvgfe.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yj20258.top/Article/details/gtzvyihmji.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.tanke756.top/Article/details/gtktajypil.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yonumen.top/Article/details/gtijimbnxk.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cashguo.top/Article/details/gtuhfjnvpg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.birdmap.top/Article/details/gtqjwlxtlj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cdnleiting.top/Article/details/gtlphxwkzu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yongpay.top/Article/details/gtoqikctkb.html

[D02] 追加元素到末尾
来源：http://dali.snrcjt.cn/Article/details/gtcygytcie.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yangfankeji.com/Article/details/gthetiqubz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.daxiang520.top/Article/details/gtixvhavtq.html

JS:   arr.push(4);
来源：http://dali.fzhhl.top/Article/details/gtwbzaklks.html

TS:   arr.push(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtauktglrz.html

Java: list.add(4);
来源：http://dali.jlsjyb.cn/Article/details/gttleagehd.html

Go:   arr = append(arr, 4)
来源：http://dali.fzhhl.top/Article/details/gtafjmzqzh.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yonumen.top/Article/details/gtijoofkfb.html

C#:   list.Add(4);
来源：http://dali.mhx1999.top/Article/details/gtrgchasxe.html

[D03] 在指定位置插入元素
来源：http://dali.yanxiufei.cn/Article/details/gttbdqgfiu.html

Py:   arr.insert(0, 0)
来源：http://dali.jyoumei.cn/Article/details/gtosgubulv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.guannengcc.top/Article/details/gttjfqckfx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jqgfzy.top/Article/details/gteguwchsi.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jyoumei.cn/Article/details/gtimjscszt.html

Java: list.add(0, 0);
来源：http://dali.tanke756.top/Article/details/gtegcwsaqq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jyoumei.cn/Article/details/gtkdrokumv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtknzrbyrq.html

C#:   list.Insert(0, 0);
来源：http://dali.cucudq.cn/Article/details/gtrwgwjmuo.html

[D04] 删除元素
来源：http://dali.jlsjyb.cn/Article/details/gteqizbzue.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.tianlin.xyz/Article/details/gtxgqokbyj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shzxlz.cn/Article/details/gtxryucoec.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hnqzz.top/Article/details/gtlaqktbsf.html

TS:   arr.splice(0, 1);
来源：http://dali.mhx1999.top/Article/details/gtjliggkdw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yangfankeji.com/Article/details/gtglklyvil.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.tian-w.cn/Article/details/gtxddlpsca.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hywenlv.cn/Article/details/gtgyornrwb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthvehoomj.html

[D05] 访问与修改元素
来源：http://dali.xinyue.icu/Article/details/gtbkmbuvez.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tianlin.xyz/Article/details/gtxlcmgwdi.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gtzhqzllrd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.gotoacloud.top/Article/details/gthrxudjbx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.aibaodan.cn/Article/details/gtwfldzfyd.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhoulong.xyz/Article/details/gtcdwuspsf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gtscoyljgz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.snrcjt.cn/Article/details/gtfokuhdbz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ehwqpu.com/Article/details/gtdhdkeura.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gtakobseor.html

Py:   len(arr)
来源：http://dali.zhengqikj.top/Article/details/gtepvottwd.html

PHP:  count($arr);
来源：http://dali.pycfn.com/Article/details/gtfcsxhmdx.html

JS:   arr.length
来源：http://dali.shuidangran.top/Article/details/gtzavuycgf.html

TS:   arr.length
来源：http://dali.yuxming.cn/Article/details/gtpuqpjrat.html

Java: list.size();
来源：http://dali.andypj.xyz/Article/details/gtlhpvkqqa.html

Go:   len(arr)
来源：http://dali.pycfn.com/Article/details/gtdxsbwifk.html

Ruby: arr.length; arr.size
来源：http://dali.dianchejie.cn/Article/details/gtxkhxwfrh.html

C#:   list.Count;
来源：http://dali.havefunace.top/Article/details/gtwtiblcls.html

[D07] 切片 / 取子数组
来源：http://dali.shanyushiyangtech.top/Article/details/gtzdkotnhf.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zdqjudy.top/Article/details/gtkzrlrzzg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfbguvbms.html

JS:   arr.slice(1, 4);
来源：http://dali.zhongyouzk.top/Article/details/gtscavgygj.html


<!-- 参考信息 -->