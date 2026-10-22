代发 wailian999

PHP:  while ($i < 10) { $i++; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2txzdbwmj.html

JS:   while (i < 10) { i++; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2wfzgrugb.html

TS:   while (i < 10) { i++; }
来源：http://dali.guannengcc.top/Article/details/gt2ooxezofd.html

Java: while (i < 10) { i++; }
来源：http://dali.haohaochexian.top/Article/details/gt2wfrhswch.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hammf.cn/Article/details/gt2swbfeuyc.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yanxiufei.cn/Article/details/gt2kjccitnk.html

C#:   while (i < 10) { i++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qhplxlbz.html

[B08] do-while（至少执行一次）
来源：http://dali.dashuyun.cn/Article/details/gt2fibuuaez.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.gotoacloud.top/Article/details/gt2qrbcfmiy.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.316326.xyz/Article/details/gt2aijrkhzp.html

JS:   do { i++; } while (i < 10);
来源：http://dali.sysykeji.top/Article/details/gt2tquoussy.html

TS:   do { i++; } while (i < 10);
来源：http://dali.xuanzx.com/Article/details/gt2vllsared.html

Java: do { i++; } while (i < 10);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iljuyiod.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.gzhubu.top/Article/details/gt2bxvvbauk.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yueranfly.top/Article/details/gt2gernokhw.html

C#:   do { i++; } while (i < 10);
来源：http://dali.pengpengdd.cyou/Article/details/gt2tnqfbnnh.html

[B09] break 与 continue
来源：http://dali.sufxvd.cn/Article/details/gt2bjgqjjaz.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ppjwa.cn/Article/details/gt2epobequg.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.smart0.xyz/Article/details/gt2vvetigdb.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigfzy.top/Article/details/gt2mkefynsn.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ppjwa.cn/Article/details/gt2zharmbqd.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangdashe.top/Article/details/gt2wxrfowuk.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.sweek.top/Article/details/gt2zmzchfxz.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.chenzaomai.com/Article/details/gt2sjfqbpko.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.snrcjt.cn/Article/details/gt2dpcwchro.html

[B10] 遍历同时拿索引
来源：http://dali.zhongyouzk.top/Article/details/gt2ungofkww.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ybcxt.top/Article/details/gt2uyelmvqi.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2cjjasfcw.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.xuanzx.com/Article/details/gt2pttxntnm.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.c1oappe.top/Article/details/gt2lokawoma.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.havefunace.top/Article/details/gt2hgijpenp.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhoulong.xyz/Article/details/gt2uxppvoac.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.wangshuangyany.cn/Article/details/gt2beatmgkk.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yueranfly.top/Article/details/gt2curqtliw.html

[B11] 生成数字序列 / 区间
来源：http://dali.yuanzhike.top/Article/details/gt2yonzrcoa.html

Py:   list(range(0, 10, 2))
来源：http://dali.yvedp.cn/Article/details/gt2icdzcbjl.html

PHP:  range(0, 10, 2);
来源：http://dali.hysaishi.cn/Article/details/gt2gnjvyhhl.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gaohongyu789.top/Article/details/gt2ntlvqxdq.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cheryme.top/Article/details/gt2gzueizpa.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.meibo888.top/Article/details/gt2cofczxwo.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.dianchejie.cn/Article/details/gt2zgfghilo.html

Ruby: (0...10).step(2).to_a
来源：http://dali.cdnleiting.top/Article/details/gt2mnocxxup.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yanxiufei.cn/Article/details/gt2yzelftrn.html

[B12] 跳出多层循环
来源：http://dali.zdqjudy.top/Article/details/gt2lvhaetze.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.bjfxy.top/Article/details/gt2tfnakirr.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yuanzhike.top/Article/details/gt2zcuiidrn.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bgpqupgh.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ybcxt.top/Article/details/gt2komlhqtm.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yueranfly.top/Article/details/gt2vcocoefm.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hnqzz.top/Article/details/gt2arysphry.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.quarkkingdee.top/Article/details/gt2wmogiyhk.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhongyouzk.top/Article/details/gt2mxsjnknv.html

[B13] 判断是否为数字
来源：http://dali.xuanzx.com/Article/details/gt2iyegcfnu.html

Py:   isinstance(x, (int, float))
来源：http://dali.fzhhl.top/Article/details/gt2abaxoecm.html

PHP:  is_numeric($x)
来源：http://dali.xziqi.cn/Article/details/gt2ejszvuhd.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gzhubu.top/Article/details/gt2cqakeyfy.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zycfv.cn/Article/details/gt2qswjhkka.html

Java: x instanceof Number
来源：http://dali.chenlongwang.top/Article/details/gt2tfrfqdfg.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.svipenyu.cn/Article/details/gt2laziinef.html

Ruby: x.is_a?(Numeric)
来源：http://dali.9152youxi.cn/Article/details/gt2ybbglptc.html

C#:   x is int or double or decimal
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zfuvjicb.html

[B14] 判断值是否在集合内
来源：http://dali.xuanzx.com/Article/details/gt2lckupfif.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shuidangran.top/Article/details/gt2olycovyk.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.gotoacloud.top/Article/details/gt2plducuhs.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.wangdashe.top/Article/details/gt2rfondcuo.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.andypj.xyz/Article/details/gt2wbkoskgg.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ppjwa.cn/Article/details/gt2lokuptya.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aprilxrl.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.haohaochexian.top/Article/details/gt2fpqdgjpx.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ybcxt.top/Article/details/gt2qdbyytdf.html

[B15] 布尔运算与取反
来源：http://dali.snrcjt.cn/Article/details/gt2dwqyloyi.html

Py:   a and b or not c
来源：http://dali.gzhubu.top/Article/details/gt2mltohfju.html

PHP:  $a && $b || !$c
来源：http://dali.zhoulong.xyz/Article/details/gt2eiyzxvsj.html

JS:   a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gt2ksbwyyog.html

TS:   a && b || !c
来源：http://dali.birdmap.top/Article/details/gt2zrkyowpl.html

Java: a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gt2tmmhlzul.html

Go:   a && b || !c
来源：http://dali.smart0.xyz/Article/details/gt2optawhot.html

Ruby: a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gt2cipndzbg.html

C#:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gt2fwwgmseo.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zdqjudy.top/Article/details/gt2vifftusb.html

Py:   if not data: return
来源：http://dali.pycfn.com/Article/details/gt2mihvavyu.html

PHP:  if (!$data) { return; }
来源：http://dali.ppjwa.cn/Article/details/gt2zeycbguz.html

JS:   if (!data) return;
来源：http://dali.fengsongda.top/Article/details/gt2uiilzzso.html

TS:   if (!data) return;
来源：http://dali.nanxinkj.top/Article/details/gt2qjqgtmxx.html

Java: if (data == null) return;
来源：http://dali.ydzc1.top/Article/details/gt2byunfhrp.html

Go:   if data == nil { return }
来源：http://dali.0kj1m.cn/Article/details/gt2gdugmoub.html

Ruby: return if data.nil?
来源：http://dali.nanxuanxn.top/Article/details/gt2bydlssiw.html

C#:   if (data == null) return;
来源：http://dali.jlsjyb.cn/Article/details/gt2twhtfbuw.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2cqatgakp.html

C. 函数与作用域
来源：http://dali.zhixingplan.top/Article/details/gt2ozqbqzaz.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2hwicrwdg.html

[C01] 定义函数
来源：http://dali.yuxming.cn/Article/details/gt2fhrmteqh.html

Py:   def add(a, b): return a + b
来源：http://dali.xinyue.icu/Article/details/gt2cziomxim.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxuanxn.top/Article/details/gt2vhpebxxu.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gt2mrkmxlaf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gt2prxrnozb.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gt2ijwmjndf.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yueranfly.top/Article/details/gt2hdoxcqmj.html

Ruby: def add(a, b); a + b; end
来源：http://dali.svipenyu.cn/Article/details/gt2krxfcrdf.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gt2bjugvfko.html

[C02] 默认参数
来源：http://dali.meibo888.top/Article/details/gt2yijarsiy.html

Py:   def greet(name="World"): return name
来源：http://dali.yangfankeji.com/Article/details/gt2pqvnrfwi.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.fengsongda.top/Article/details/gt2hferjepb.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.9152youxi.cn/Article/details/gt2nkmfyzty.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yueranfly.top/Article/details/gt2ctrkqdpi.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ybcxt.top/Article/details/gt2rmfvqkrp.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zycfv.cn/Article/details/gt2biqucfhw.html

Ruby: def greet(name = "World") = name
来源：http://dali.xuanzx.com/Article/details/gt2jdpxtstv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.bjfxy.top/Article/details/gt2oplxgowt.html

[C03] 可变参数
来源：http://dali.xinyue.icu/Article/details/gt2bxpzizpq.html

Py:   def total(*args): return sum(args)
来源：http://dali.svipenyu.cn/Article/details/gt2nafoeuwe.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wotmrhnv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jlsjyb.cn/Article/details/gt2nvqntmtr.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhengqikj.top/Article/details/gt2aqgdopgi.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sweek.top/Article/details/gt2jixcqrth.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ybcxt.top/Article/details/gt2vpjuzyct.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rnovalko.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.chenjidiqi.icu/Article/details/gt2tqupebhk.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aieligvc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.gotoacloud.top/Article/details/gt2dxvmutuj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ohwwxfqu.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yuanzhike.top/Article/details/gt2xdxcmhun.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.bjfxy.top/Article/details/gt2cqtkxteo.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xinyue.icu/Article/details/gt2rlgemnht.html

Go:   // 无：用配置结构体参数
来源：http://dali.yangfankeji.com/Article/details/gt2jqnekcfw.html

Ruby: f(a: 1, b: 2)
来源：http://dali.tian-w.cn/Article/details/gt2pwtdfrqz.html

C#:   f(a: 1, b: 2)
来源：http://dali.ivvv.top/Article/details/gt2vktkrwqi.html

[C05] 返回多个值
来源：http://dali.jiagoushi.top/Article/details/gt2sojvfvjy.html

Py:   return a, b
来源：http://dali.yuxming.cn/Article/details/gt2gcafvsun.html

PHP:  return [$a, $b];
来源：http://dali.yueranfly.top/Article/details/gt2djgmoqub.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.9152youxi.cn/Article/details/gt2zjvwwney.html

TS:   return { a, b };
来源：http://dali.wangshuangyany.cn/Article/details/gt2vwyzairt.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.fzhhl.top/Article/details/gt2pfadvncp.html

Go:   return a, b
来源：http://dali.snrcjt.cn/Article/details/gt2imzosrwn.html

Ruby: return a, b
来源：http://dali.tian-w.cn/Article/details/gt2hmwxqcxc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xylfe.cn/Article/details/gt2gtrbawde.html

[C06] 匿名函数 / lambda
来源：http://dali.jqgfzy.top/Article/details/gt2ixfokkcp.html

Py:   square = lambda x: x * x
来源：http://dali.zhongyouzk.top/Article/details/gt2ubmtmegj.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.aizwys.cn/Article/details/gt2mdawcytu.html

JS:   const square = x => x * x;
来源：http://dali.zhoulong.xyz/Article/details/gt2gmgweecp.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.quarkkingdee.top/Article/details/gt2vwprlkmj.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gt2pmljcyja.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.kuanghao11.cn/Article/details/gt2wkbrfrdb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.sweek.top/Article/details/gt2faovvzmz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.sxryk.cn/Article/details/gt2swqelndi.html

[C07] 把函数作为参数传入
来源：http://dali.hnqzz.top/Article/details/gt2dlhnjvty.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yongpay.top/Article/details/gt2gwhozzoq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jqgfzy.top/Article/details/gt2almraftb.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hnxiangtu.top/Article/details/gt2ygamaeiz.html

TS:   arr.map(String)
来源：http://dali.shzxlz.cn/Article/details/gt2jetykzls.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jqgfzy.top/Article/details/gt2sextoycs.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xylfe.cn/Article/details/gt2xisxcfwb.html

Ruby: arr.map(&:upcase)
来源：http://dali.svipenyu.cn/Article/details/gt2rxfgmukh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.birdmap.top/Article/details/gt2agvpvnsj.html

[C08] 闭包
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aiyulahd.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.fzhhl.top/Article/details/gt2pjcskuji.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.aizwys.cn/Article/details/gt2wdthqieg.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wdzrvyta.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ipflbbau.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ohrccxrk.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2biahndhy.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.snrcjt.cn/Article/details/gt2jptfcfvm.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhongyouzk.top/Article/details/gt2kowomrkg.html

[C09] 递归
来源：http://dali.gaohongyu789.top/Article/details/gt2kvdognfl.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hysaishi.cn/Article/details/gt2bmuuoeks.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.smart0.xyz/Article/details/gt2qhvzklbv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cqqwz.cn/Article/details/gt2ngxdnuvw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.svipenyu.cn/Article/details/gt2mscexpse.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xinyue.icu/Article/details/gt2ufkyojwi.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hammf.cn/Article/details/gt2ddujzktm.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lnyyxase.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ydzc1.top/Article/details/gt2oatmllqp.html

[C10] 变量作用域
来源：http://dali.cashguo.top/Article/details/gt2lobopgrc.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.shuidangran.top/Article/details/gt2gvdoldic.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yvedp.cn/Article/details/gt2lbnwzbcw.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.daria6918.cn/Article/details/gt2hdrrlkhj.html

TS:   同 JS
来源：http://dali.jiagoushi.top/Article/details/gt2twilxsfs.html

Java: 方法内为块级作用域
来源：http://dali.daxiang520.top/Article/details/gt2gluinlvc.html

Go:   花括号块级作用域
来源：http://dali.zhengqikj.top/Article/details/gt2wvqctxag.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.smart0.xyz/Article/details/gt2crixkkbn.html

C#:   块级作用域
来源：http://dali.yvedp.cn/Article/details/gt2viajrbct.html

[C11] 模块导入与导出
来源：http://dali.hnqzz.top/Article/details/gt2niuetvjj.html

Py:   from module import func
来源：http://dali.zycfv.cn/Article/details/gt2ffdpdeaa.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jianghu66.top/Article/details/gt2gmffrkmv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.tanke756.top/Article/details/gt2jhlmwmmr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cdnleiting.top/Article/details/gt2wmtzqlqq.html

Java: import java.util.List;
来源：http://dali.dashuyun.cn/Article/details/gt2ldwrcsiz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xziqi.cn/Article/details/gt2bbflvlgd.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jiagoushi.top/Article/details/gt2qngjuaje.html

C#:   using System.Text;
来源：http://dali.ehwqpu.com/Article/details/gt2ohexuplt.html

[C12] 立即执行函数 IIFE
来源：http://dali.cdnleiting.top/Article/details/gt2bdzgusgy.html

Py:   (lambda: print("run"))()
来源：http://dali.0kj1m.cn/Article/details/gt2adwlfsnl.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jyoumei.cn/Article/details/gt2lbxhrvib.html

JS:   (() => { console.log("run"); })();
来源：http://dali.bjfxy.top/Article/details/gt2wzsnijyv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.wangdashe.top/Article/details/gt2zhrcufaf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.guannengcc.top/Article/details/gt2atolajed.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gzhubu.top/Article/details/gt2ovtafgxx.html

Ruby: -> { puts "run" }.call
来源：http://dali.jqgufenzy.top/Article/details/gt2niiurtlt.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.chenlongwang.top/Article/details/gt2rjlkoest.html

[C13] 类型声明 / 类型注解
来源：http://dali.fzhhl.top/Article/details/gt2xckubogt.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jqgfzy.top/Article/details/gt2ezdwgyhf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yongpay.top/Article/details/gt2vryznumj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.feifeiyinyue.top/Article/details/gt2qgsrvtnb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gt2yerjcson.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gt2cxcqsxak.html

Go:   func add(a, b int) int
来源：http://dali.yueranfly.top/Article/details/gt2cavkpicj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sxryk.cn/Article/details/gt2rimgiswv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jyoumei.cn/Article/details/gt2fhnheivm.html

[C14] 泛型函数
来源：http://dali.sysykeji.top/Article/details/gt2bomqihck.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zycfv.cn/Article/details/gt2kdwebaer.html

PHP:  // 无泛型
来源：http://dali.yuxming.cn/Article/details/gt2eizberzr.html

JS:   // 无泛型
来源：http://dali.pengpengdd.cyou/Article/details/gt2pwkdjglx.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.316326.xyz/Article/details/gt2nosrwefv.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cashguo.top/Article/details/gt2rhtgfvmm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.fzhhl.top/Article/details/gt2fkgsbhnn.html

Ruby: # 无泛型
来源：http://dali.hnxiangtu.top/Article/details/gt2otmoafrt.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jqgufenzy.top/Article/details/gt2zdlwzagc.html

[C15] 解构 / 展开参数
来源：http://dali.kuanghao11.cn/Article/details/gt2bmomukun.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.chenlongwang.top/Article/details/gt2erlmrdjf.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jyoumei.cn/Article/details/gt2gaapoejj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.fzhhl.top/Article/details/gt2qgmpjnxb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.tianlin.xyz/Article/details/gt2yelpudlw.html

Java: // 无解构
来源：http://dali.yangfankeji.com/Article/details/gt2hlolhuiw.html

Go:   // 无解构
来源：http://dali.smart0.xyz/Article/details/gt2shacadia.html

Ruby: a, b = pair
来源：http://dali.nanxuanxn.top/Article/details/gt2jzycoxyl.html

C#:   var (a, b) = pair;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lmibnayj.html

[C16] 函数 / 方法重载
来源：http://dali.andypj.xyz/Article/details/gt2mgunlwby.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.dianchejie.cn/Article/details/gt2vmgsekgw.html

PHP:  // 无重载
来源：http://dali.ybcxt.top/Article/details/gt2seyumgml.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xziqi.cn/Article/details/gt2cuqvlnks.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gzhubu.top/Article/details/gt2esfvkvvf.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2xyqqucxp.html

Go:   // 无重载：用不同函数名
来源：http://dali.sxryk.cn/Article/details/gt2pghftmpn.html

Ruby: # 无重载：靠动态参数
来源：http://dali.tianlin.xyz/Article/details/gt2vvzfvzhq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jiagoushi.top/Article/details/gt2ltckbggu.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2ttydcynb.html

D. 数组 / 列表 / 集合
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kksssbmv.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2zsdseiqx.html

[D01] 创建数组 / 列表
来源：http://dali.andypj.xyz/Article/details/gt2juozoxgw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.bjfxy.top/Article/details/gt2ixegvobm.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhoulong.xyz/Article/details/gt2ghnlilaa.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jbmwguus.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yj20258.top/Article/details/gt2vgtouand.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hongshengwenyu.top/Article/details/gt2sviavwfg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.wangshuangyany.cn/Article/details/gt2ixukxjue.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jyoumei.cn/Article/details/gt2wranwcdh.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.dashuyun.cn/Article/details/gt2kblilfmk.html

[D02] 追加元素到末尾
来源：http://dali.shuidangran.top/Article/details/gt2zebfhicf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xuetiantiany.cn/Article/details/gt2lxphwmpo.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xziqi.cn/Article/details/gt2lsnnjmgk.html

JS:   arr.push(4);
来源：http://dali.jianghu66.top/Article/details/gt2nbvlhlfk.html

TS:   arr.push(4);
来源：http://dali.ppjwa.cn/Article/details/gt2xtbxbpmu.html

Java: list.add(4);
来源：http://dali.sweek.top/Article/details/gt2rqijlyap.html

Go:   arr = append(arr, 4)
来源：http://dali.sxryk.cn/Article/details/gt2iqcywbvz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shuidangran.top/Article/details/gt2lesphbyw.html

C#:   list.Add(4);
来源：http://dali.meibo888.top/Article/details/gt2yibhvzhy.html

[D03] 在指定位置插入元素
来源：http://dali.jyoumei.cn/Article/details/gt2nxqisfxh.html

Py:   arr.insert(0, 0)
来源：http://dali.hnxiangtu.top/Article/details/gt2xuvhogay.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhengqikj.top/Article/details/gt2wenisfbg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.bjfxy.top/Article/details/gt2kbiqwbrx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xylfe.cn/Article/details/gt2nhpbxpin.html

Java: list.add(0, 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2pnfrmqrq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gaohongyu789.top/Article/details/gt2kegigysg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ivvv.top/Article/details/gt2widpfwpq.html

C#:   list.Insert(0, 0);
来源：http://dali.smart0.xyz/Article/details/gt2qvitbucl.html

[D04] 删除元素
来源：http://dali.redwolf501.top/Article/details/gt2cyowxqrr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinqigfzy.top/Article/details/gt2cyccjslk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.dianchejie.cn/Article/details/gt2tvwzkagi.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.fzhhl.top/Article/details/gt2ijyvmrsr.html

TS:   arr.splice(0, 1);
来源：http://dali.yuanzhike.top/Article/details/gt2bqgipuwj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.havefunace.top/Article/details/gt2zssmqane.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jyoumei.cn/Article/details/gt2yyvhwpuw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.chenzaomai.com/Article/details/gt2jhsugepa.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xinyue.icu/Article/details/gt2ovydfufb.html

[D05] 访问与修改元素
来源：http://dali.yongpay.top/Article/details/gt2izsvcvcu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yangfankeji.com/Article/details/gt2vxmxraxu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yvedp.cn/Article/details/gt2wfvbacbo.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.kuanghao11.cn/Article/details/gt2rzyqbidv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ivvv.top/Article/details/gt2pidgkqcq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.haohaochexian.top/Article/details/gt2iyvrcpve.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.fengsongda.top/Article/details/gt2emqzixgf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.feifeiyinyue.top/Article/details/gt2gsbibxvm.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pklfexiw.html

[D06] 数组长度
来源：http://dali.yangfankeji.com/Article/details/gt2aqvqyreg.html

Py:   len(arr)
来源：http://dali.hnqzz.top/Article/details/gt2lghhgmjf.html

PHP:  count($arr);
来源：http://dali.snrcjt.cn/Article/details/gt2zxbqlejs.html

JS:   arr.length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kvxomrdp.html

TS:   arr.length
来源：http://dali.vqdsnc.cn/Article/details/gt2lwsnbdnf.html

Java: list.size();
来源：http://dali.jianghu66.top/Article/details/gt2rldyraen.html

Go:   len(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2rdhohujf.html

Ruby: arr.length; arr.size
来源：http://dali.jqgufenzy.top/Article/details/gt2xulgtpft.html

C#:   list.Count;
来源：http://dali.andypj.xyz/Article/details/gt2nhlkkmks.html

[D07] 切片 / 取子数组
来源：http://dali.hongshengwenyu.top/Article/details/gt2tvegtmfg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.chenzaomai.com/Article/details/gt2yleaqdru.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.svipenyu.cn/Article/details/gt2yopkkldz.html

JS:   arr.slice(1, 4);
来源：http://dali.hywenlv.cn/Article/details/gt2wdwdnwob.html

TS:   arr.slice(1, 4);
来源：http://dali.xinyue.icu/Article/details/gt2ulhgvjxv.html

Java: list.subList(1, 4);
来源：http://dali.shangyingyoupin.top/Article/details/gt2ktrcwpqi.html

Go:   arr[1:4]
来源：http://dali.jqgfzy.top/Article/details/gt2emauwccl.html

Ruby: arr[1, 3]
来源：http://dali.zhiwuduotai.top/Article/details/gt2dpbxkabo.html


<!-- 参考信息 -->