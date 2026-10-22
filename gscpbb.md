代发 wailian999

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.chenlongwang.top/Article/details/gt2mpwkqwfh.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2dcjqglkh.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jinqigufen.top/Article/details/gt2ghjuttbq.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.0kj1m.cn/Article/details/gt2whocpecq.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.cucudq.cn/Article/details/gt2whitbvch.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2fyqrvcdp.html

[B07] while 循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jlibwksx.html

Py:   while i < 10: i += 1
来源：http://dali.shzxlz.cn/Article/details/gt2qkrmtbjn.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2gmdzprwx.html

JS:   while (i < 10) { i++; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ubgyqtcr.html

TS:   while (i < 10) { i++; }
来源：http://dali.hammf.cn/Article/details/gt2yekhpwln.html

Java: while (i < 10) { i++; }
来源：http://dali.316326.xyz/Article/details/gt2pbywhagc.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.fzhhl.top/Article/details/gt2osmgknvi.html

Ruby: while i < 10; i += 1; end
来源：http://dali.cheryme.top/Article/details/gt2hjmhgyie.html

C#:   while (i < 10) { i++; }
来源：http://dali.sysykeji.top/Article/details/gt2mewrteup.html

[B08] do-while（至少执行一次）
来源：http://dali.meibo888.top/Article/details/gt2yovzhtpd.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.daria6918.cn/Article/details/gt2ieofadaq.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yswrjdux.html

JS:   do { i++; } while (i < 10);
来源：http://dali.shuidangran.top/Article/details/gt2fcbkitgs.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yongpay.top/Article/details/gt2ufbedwfx.html

Java: do { i++; } while (i < 10);
来源：http://dali.chenlongwang.top/Article/details/gt2aszgvdpf.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yongpay.top/Article/details/gt2icjleidb.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhongyouzk.top/Article/details/gt2xotgivmz.html

C#:   do { i++; } while (i < 10);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qdmxuaaf.html

[B09] break 与 continue
来源：http://dali.sxryk.cn/Article/details/gt2ugrqglrl.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhongyouzk.top/Article/details/gt2ptdldkhv.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.pycfn.com/Article/details/gt2sxtvsuox.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gogol.net.cn/Article/details/gt2tezhqmmc.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sysykeji.top/Article/details/gt2ajqjnnyy.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.vqdsnc.cn/Article/details/gt2ebhwpnte.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.tian-w.cn/Article/details/gt2eslhypco.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ppjwa.cn/Article/details/gt2lqekmykk.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.smart0.xyz/Article/details/gt2wpjmkmxa.html

[B10] 遍历同时拿索引
来源：http://dali.tanke756.top/Article/details/gt2jqgqndou.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.fengsongda.top/Article/details/gt2egnesefd.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2mkilwzua.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhengqikj.top/Article/details/gt2tsmdpicp.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.aizwys.cn/Article/details/gt2vacswijp.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.gaohongyu789.top/Article/details/gt2wnofjvbi.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.bjfxy.top/Article/details/gt2ufwcoxht.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhoulong.xyz/Article/details/gt2nifvlkwc.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yj20258888.top/Article/details/gt2crnumwjk.html

[B11] 生成数字序列 / 区间
来源：http://dali.gotoacloud.top/Article/details/gt2sodifqvz.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2thmhlzah.html

PHP:  range(0, 10, 2);
来源：http://dali.jiagoushi.top/Article/details/gt2yejtszew.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.wangdashe.top/Article/details/gt2oankjhim.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ppjwa.cn/Article/details/gt2fadpqmdt.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yongpay.top/Article/details/gt2bdzbfcuz.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yvedp.cn/Article/details/gt2mdmsvddd.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xuanzx.com/Article/details/gt2nxlaouxn.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.cheryme.top/Article/details/gt2jlwejkuq.html

[B12] 跳出多层循环
来源：http://dali.ivvv.top/Article/details/gt2yrsiwcda.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yongpay.top/Article/details/gt2aynegjyb.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.sysykeji.top/Article/details/gt2hdrrfgbc.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.pycfn.com/Article/details/gt2xycjkvkr.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.0kj1m.cn/Article/details/gt2vtokttyx.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhongyouzk.top/Article/details/gt2wxiwdzjh.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jqgfzy.top/Article/details/gt2zypvpjba.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hongshengwenyu.top/Article/details/gt2pfvaogju.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hammf.cn/Article/details/gt2pnzxvequ.html

[B13] 判断是否为数字
来源：http://dali.yuanzhike.top/Article/details/gt2khpvvmql.html

Py:   isinstance(x, (int, float))
来源：http://dali.cheryme.top/Article/details/gt2kwtozdjd.html

PHP:  is_numeric($x)
来源：http://dali.haohaochexian.top/Article/details/gt2qvttrnuc.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lnokzrom.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hysaishi.cn/Article/details/gt2yfxirizd.html

Java: x instanceof Number
来源：http://dali.9152youxi.cn/Article/details/gt2suhsaibg.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.wangshuangyany.cn/Article/details/gt2khjphhyw.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jqgufenzy.top/Article/details/gt2qyoitkgu.html

C#:   x is int or double or decimal
来源：http://dali.316326.xyz/Article/details/gt2jsjmeyng.html

[B14] 判断值是否在集合内
来源：http://dali.jqgfzy.top/Article/details/gt2olmvkecv.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.c1oappe.top/Article/details/gt2huqdlsfd.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.gaohongyu789.top/Article/details/gt2pevsosth.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.0kj1m.cn/Article/details/gt2rrtmhynh.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ppjwa.cn/Article/details/gt2ngnxqqoq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mjsvplgq.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhixingplan.top/Article/details/gt2dngalmpg.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.cdnleiting.top/Article/details/gt2pjyfprcn.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gsktpzsx.html

[B15] 布尔运算与取反
来源：http://dali.nwbrower.top/Article/details/gt2poxyzlsp.html

Py:   a and b or not c
来源：http://dali.svipenyu.cn/Article/details/gt2osuykmny.html

PHP:  $a && $b || !$c
来源：http://dali.yuxming.cn/Article/details/gt2aiqehvlg.html

JS:   a && b || !c
来源：http://dali.ydzc1.top/Article/details/gt2npqqaiax.html

TS:   a && b || !c
来源：http://dali.daxiang520.top/Article/details/gt2asowiojk.html

Java: a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gt2oxtxwgzx.html

Go:   a && b || !c
来源：http://dali.daxiang520.top/Article/details/gt2cenwzqno.html

Ruby: a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gt2hgzgbtzd.html

C#:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gt2vqvkirbc.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gssrxyxy.html

Py:   if not data: return
来源：http://dali.xinyue.icu/Article/details/gt2rdbyblzo.html

PHP:  if (!$data) { return; }
来源：http://dali.gogol.net.cn/Article/details/gt2dggnuqtk.html

JS:   if (!data) return;
来源：http://dali.jqgufenzy.top/Article/details/gt2qpvkdjok.html

TS:   if (!data) return;
来源：http://dali.xylfe.cn/Article/details/gt2ojdwhmsi.html

Java: if (data == null) return;
来源：http://dali.quarkkingdee.top/Article/details/gt2rjwrvvfa.html

Go:   if data == nil { return }
来源：http://dali.yueranfly.top/Article/details/gt2djxwnsee.html

Ruby: return if data.nil?
来源：http://dali.ybcxt.top/Article/details/gt2fwwkictq.html

C#:   if (data == null) return;
来源：http://dali.yj202588.top/Article/details/gt2uaxbauwm.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2ehufazhe.html

C. 函数与作用域
来源：http://dali.fengsongda.top/Article/details/gt2cglaqkmr.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2pfhjrwcy.html

[C01] 定义函数
来源：http://dali.nanxuanxn.top/Article/details/gt2pmrjixwc.html

Py:   def add(a, b): return a + b
来源：http://dali.yonumen.top/Article/details/gt2feqmwebv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dianchejie.cn/Article/details/gt2esmgisue.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gt2vcbulenr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gt2uklilpdw.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gt2imzrtvfi.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zpzqkomc.html

Ruby: def add(a, b); a + b; end
来源：http://dali.vqdsnc.cn/Article/details/gt2igwcsqul.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.birdmap.top/Article/details/gt2plobtihk.html

[C02] 默认参数
来源：http://dali.jiagoushi.top/Article/details/gt2akatuknl.html

Py:   def greet(name="World"): return name
来源：http://dali.xinyue.icu/Article/details/gt2qtvlfdov.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2jbrkemgh.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hnqzz.top/Article/details/gt2hknhqpkv.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2rgbxzhsq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.pengpengdd.cyou/Article/details/gt2mnotdspx.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ivvv.top/Article/details/gt2uwnazpgm.html

Ruby: def greet(name = "World") = name
来源：http://dali.smart0.xyz/Article/details/gt2nnrpdyqh.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.dashuyun.cn/Article/details/gt2mkfuoxld.html

[C03] 可变参数
来源：http://dali.jianghu66.top/Article/details/gt2vasrzhfy.html

Py:   def total(*args): return sum(args)
来源：http://dali.hnxiangtu.top/Article/details/gt2wthgbeao.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.cashguo.top/Article/details/gt2momgqtyn.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258.top/Article/details/gt2msopvvlu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yvedp.cn/Article/details/gt2rvjzprfe.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sysykeji.top/Article/details/gt2vopdkgcj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.fengsongda.top/Article/details/gt2zgialloz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hfpthk.cn/Article/details/gt2veogjyvv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.snrcjt.cn/Article/details/gt2rkpjlobm.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rvbqlbla.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.guannengcc.top/Article/details/gt2ovrieetu.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.chenlongwang.top/Article/details/gt2zqowlgws.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.havefunace.top/Article/details/gt2vtcilmyn.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jinqigufen.top/Article/details/gt2jjzfyttb.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.c1oappe.top/Article/details/gt2joflbgia.html

Go:   // 无：用配置结构体参数
来源：http://dali.fzhhl.top/Article/details/gt2kujmclsz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.andypj.xyz/Article/details/gt2hedkqowi.html

C#:   f(a: 1, b: 2)
来源：http://dali.yj202588.top/Article/details/gt2vqhjkhib.html

[C05] 返回多个值
来源：http://dali.sufxvd.cn/Article/details/gt2qhewvapx.html

Py:   return a, b
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cpbplyzq.html

PHP:  return [$a, $b];
来源：http://dali.yueranfly.top/Article/details/gt2deadmcio.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ppjwa.cn/Article/details/gt2cfedylte.html

TS:   return { a, b };
来源：http://dali.svipenyu.cn/Article/details/gt2oybvasnl.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.quarkkingdee.top/Article/details/gt2pkcopmoi.html

Go:   return a, b
来源：http://dali.hywenlv.cn/Article/details/gt2wuamvtdk.html

Ruby: return a, b
来源：http://dali.hammf.cn/Article/details/gt2nybvzyqq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.guannengcc.top/Article/details/gt2hunfwgvr.html

[C06] 匿名函数 / lambda
来源：http://dali.c1oappe.top/Article/details/gt2hzdykien.html

Py:   square = lambda x: x * x
来源：http://dali.pycfn.com/Article/details/gt2ovumljdp.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hnxiangtu.top/Article/details/gt2plmydest.html

JS:   const square = x => x * x;
来源：http://dali.sxryk.cn/Article/details/gt2eolyhgeb.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.smart0.xyz/Article/details/gt2rxmtxjpx.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xylfe.cn/Article/details/gt2pdttjeyb.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.kuanghao11.cn/Article/details/gt2jvavqfci.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2undtkpkh.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.chenjidiqi.icu/Article/details/gt2gvdmpgpl.html

[C07] 把函数作为参数传入
来源：http://dali.jlsjyb.cn/Article/details/gt2zkjxquvl.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yangfankeji.com/Article/details/gt2fzdwycoy.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xziqi.cn/Article/details/gt2pcjjubst.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinqigufen.top/Article/details/gt2nqoyuljc.html

TS:   arr.map(String)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zrhtvuto.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jyoumei.cn/Article/details/gt2iwxvrhgh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.dianchejie.cn/Article/details/gt2oeipcdxv.html

Ruby: arr.map(&:upcase)
来源：http://dali.ydzc1.top/Article/details/gt2bkbhxybr.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhongyouzk.top/Article/details/gt2orronzxx.html

[C08] 闭包
来源：http://dali.xziqi.cn/Article/details/gt2qxrrskzc.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.pengpengdd.cyou/Article/details/gt2gwkkpxth.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2antktrvp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.redwolf501.top/Article/details/gt2yqlycwpa.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2boafauph.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yj202588.top/Article/details/gt2mezdfsjd.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhiwuduotai.top/Article/details/gt2nqukpdbk.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.meibo888.top/Article/details/gt2whlkjeuq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dxinbpvb.html

[C09] 递归
来源：http://dali.chenlongwang.top/Article/details/gt2ozivpakf.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yuanzhike.top/Article/details/gt2fgkyriaf.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.bjfxy.top/Article/details/gt2cdcgiorg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cqqwz.cn/Article/details/gt2fepofxxl.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cheryme.top/Article/details/gt2lvphnfzh.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2comjbypn.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.birdmap.top/Article/details/gt2dnuoiriz.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.tian-w.cn/Article/details/gt2gfemdcvu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.aibaodan.cn/Article/details/gt2ofqcmxgc.html

[C10] 变量作用域
来源：http://dali.tianlin.xyz/Article/details/gt2bvngjcuj.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.9152youxi.cn/Article/details/gt2ghtcxurk.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhixingplan.top/Article/details/gt2lgndfpfc.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ehwqpu.com/Article/details/gt2nnjisfvc.html

TS:   同 JS
来源：http://dali.andypj.xyz/Article/details/gt2qwyribng.html

Java: 方法内为块级作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sibrkmoe.html

Go:   花括号块级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ypoiufpo.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.316326.xyz/Article/details/gt2magkgtqg.html

C#:   块级作用域
来源：http://dali.gotoacloud.top/Article/details/gt2wnremefq.html

[C11] 模块导入与导出
来源：http://dali.kuanghao11.cn/Article/details/gt2qlvjrbyo.html

Py:   from module import func
来源：http://dali.dashuyun.cn/Article/details/gt2apbfltin.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cdnleiting.top/Article/details/gt2fueumqdv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.c1oappe.top/Article/details/gt2rntrrjsn.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.tanke756.top/Article/details/gt2obiimrvg.html

Java: import java.util.List;
来源：http://dali.gogol.net.cn/Article/details/gt2stdvgwfe.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.haohaochexian.top/Article/details/gt2kzzubhyq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ydzc1.top/Article/details/gt2kprdqekg.html

C#:   using System.Text;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vdqdznlt.html

[C12] 立即执行函数 IIFE
来源：http://dali.yuxming.cn/Article/details/gt2txcwvwkl.html

Py:   (lambda: print("run"))()
来源：http://dali.zhixingplan.top/Article/details/gt2yzganweo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.vqdsnc.cn/Article/details/gt2arwavnhx.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zycfv.cn/Article/details/gt2lajbjtpd.html

TS:   (() => { console.log("run"); })();
来源：http://dali.gzhubu.top/Article/details/gt2lsfxtdgn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xziqi.cn/Article/details/gt2krrqvbvc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hnqzz.top/Article/details/gt2dqbhhkne.html

Ruby: -> { puts "run" }.call
来源：http://dali.xylfe.cn/Article/details/gt2gcpelvyu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.haohaochexian.top/Article/details/gt2ditjwriq.html

[C13] 类型声明 / 类型注解
来源：http://dali.316326.xyz/Article/details/gt2jlbsnbvk.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.daxiang520.top/Article/details/gt2mgogoarc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2onvbgvdw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rqwmxqdg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gt2jkdhsckt.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gt2dflojkan.html

Go:   func add(a, b int) int
来源：http://dali.snrcjt.cn/Article/details/gt2vkbyvach.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lfzsayag.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shangyingyoupin.top/Article/details/gt2zsllwkns.html

[C14] 泛型函数
来源：http://dali.jlsjyb.cn/Article/details/gt2ihnilzqx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.chenzaomai.com/Article/details/gt2mvkknbay.html

PHP:  // 无泛型
来源：http://dali.yanxiufei.cn/Article/details/gt2trhwhytq.html

JS:   // 无泛型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wuefjdtk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.svipenyu.cn/Article/details/gt2mzutdqgy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2oaonmjsy.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xuanzx.com/Article/details/gt2mfifeqnf.html

Ruby: # 无泛型
来源：http://dali.ydzc1.top/Article/details/gt2jxdjpfqq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.316326.xyz/Article/details/gt2djjkejkc.html

[C15] 解构 / 展开参数
来源：http://dali.tanke756.top/Article/details/gt2qsykebgw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sweek.top/Article/details/gt2vytwjzjq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.sufxvd.cn/Article/details/gt2kldriyvx.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yuanzhike.top/Article/details/gt2mpugberl.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shzxlz.cn/Article/details/gt2nabrrpah.html

Java: // 无解构
来源：http://dali.tianlin.xyz/Article/details/gt2gnmiezki.html

Go:   // 无解构
来源：http://dali.zhongyouzk.top/Article/details/gt2tyvlmxyi.html

Ruby: a, b = pair
来源：http://dali.snrcjt.cn/Article/details/gt2zkcldioq.html

C#:   var (a, b) = pair;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uvubrpuq.html

[C16] 函数 / 方法重载
来源：http://dali.hnxiangtu.top/Article/details/gt2kkptvemk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.gogol.net.cn/Article/details/gt2fsdhalpo.html

PHP:  // 无重载
来源：http://dali.cashguo.top/Article/details/gt2gclhkxvq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.smart0.xyz/Article/details/gt2ngsacbpn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ohvjqscw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zycfv.cn/Article/details/gt2iyookfpt.html

Go:   // 无重载：用不同函数名
来源：http://dali.bjfxy.top/Article/details/gt2ojuwgmlu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.tanke756.top/Article/details/gt2foylulnc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shzxlz.cn/Article/details/gt2fbggdmim.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2torfolzc.html

D. 数组 / 列表 / 集合
来源：http://dali.jianghu66.top/Article/details/gt2txfhrjxr.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2xfyardwy.html

[D01] 创建数组 / 列表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mywgivfq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zdqjudy.top/Article/details/gt2muugreub.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhoulong.xyz/Article/details/gt2cfdbiyvd.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zycfv.cn/Article/details/gt2ewmaaaiw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.svipenyu.cn/Article/details/gt2qolvfcox.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yvedp.cn/Article/details/gt2uwwrzsgb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.daxiang520.top/Article/details/gt2qhhzizui.html

Ruby: arr = [1, 2, 3]
来源：http://dali.havefunace.top/Article/details/gt2mczfijvv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.redwolf501.top/Article/details/gt2xyjeriwn.html

[D02] 追加元素到末尾
来源：http://dali.0kj1m.cn/Article/details/gt2dtizaxxy.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.havefunace.top/Article/details/gt2qgkkjosp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shangyingyoupin.top/Article/details/gt2bmtzgcql.html

JS:   arr.push(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wicatiir.html

TS:   arr.push(4);
来源：http://dali.gaohongyu789.top/Article/details/gt2qntbxnkd.html

Java: list.add(4);
来源：http://dali.yonumen.top/Article/details/gt2bdhswrzg.html

Go:   arr = append(arr, 4)
来源：http://dali.hnxiangtu.top/Article/details/gt2hdrfdkuk.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hammf.cn/Article/details/gt2dzuryksa.html

C#:   list.Add(4);
来源：http://dali.hammf.cn/Article/details/gt2ygfzmyka.html

[D03] 在指定位置插入元素
来源：http://dali.guannengcc.top/Article/details/gt2lmcckwjs.html

Py:   arr.insert(0, 0)
来源：http://dali.yonumen.top/Article/details/gt2dtusuytd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jianghu66.top/Article/details/gt2mtndaitx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yuxming.cn/Article/details/gt2kamqyeif.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2vavrdmui.html

Java: list.add(0, 0);
来源：http://dali.hysaishi.cn/Article/details/gt2soquvwtq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.birdmap.top/Article/details/gt2qpbkhdrg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhixingplan.top/Article/details/gt2wvygcfft.html

C#:   list.Insert(0, 0);
来源：http://dali.nwbrower.top/Article/details/gt2paqlscay.html

[D04] 删除元素
来源：http://dali.feifeiyinyue.top/Article/details/gt2gpplstgb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ufntbnnz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yangfankeji.com/Article/details/gt2uugrczsz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sysykeji.top/Article/details/gt2owvflvth.html

TS:   arr.splice(0, 1);
来源：http://dali.hammf.cn/Article/details/gt2vayktzyx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.tanke756.top/Article/details/gt2ncjnkhyb.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2adgwwmyf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hywenlv.cn/Article/details/gt2htevxogi.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hyxcqipt.html

[D05] 访问与修改元素
来源：http://dali.xuetiantiany.cn/Article/details/gt2fwqovpwh.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sweek.top/Article/details/gt2qhkmjykg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yonumen.top/Article/details/gt2wrjpyyil.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.dashuyun.cn/Article/details/gt2tghxdtbl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.redwolf501.top/Article/details/gt2nfgwceyc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gogol.net.cn/Article/details/gt2oqkbwdor.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cucudq.cn/Article/details/gt2nxnfbndd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xylfe.cn/Article/details/gt2byrcrsks.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cashguo.top/Article/details/gt2mugtczrl.html

[D06] 数组长度
来源：http://dali.shzxlz.cn/Article/details/gt2ucxujoqi.html

Py:   len(arr)
来源：http://dali.gzhubu.top/Article/details/gt2fhyeving.html

PHP:  count($arr);
来源：http://dali.daria6918.cn/Article/details/gt2vkpsmjri.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxkkyjc.html

TS:   arr.length
来源：http://dali.jqgufenzy.top/Article/details/gt2rqaizcvl.html

Java: list.size();
来源：http://dali.hnxiangtu.top/Article/details/gt2vpxtmhsf.html

Go:   len(arr)
来源：http://dali.pycfn.com/Article/details/gt2jsvebqft.html

Ruby: arr.length; arr.size
来源：http://dali.pycfn.com/Article/details/gt2bohzcxng.html

C#:   list.Count;
来源：http://dali.gogol.net.cn/Article/details/gt2hhrbqrpz.html


<!-- 参考信息 -->