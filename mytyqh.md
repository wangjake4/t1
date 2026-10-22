代发 wailian999

[B05] 遍历数组 / 列表
来源：http://dali.xziqi.cn/Article/details/gt2mnlkphih.html

Py:   for item in arr: print(item)
来源：http://dali.chenlongwang.top/Article/details/gt2jdtvslda.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhoulong.xyz/Article/details/gt2xzkvhann.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jianghu66.top/Article/details/gt2hnzzerky.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.jlsjyb.cn/Article/details/gt2fgscxvgv.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.meibo888.top/Article/details/gt2cjtofyez.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zycfv.cn/Article/details/gt2ydiwylds.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2seoisqix.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2zwvecnou.html

[B06] 遍历字典 / 对象
来源：http://dali.ydzc1.top/Article/details/gt2yulvezcu.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jiagoushi.top/Article/details/gt2wpcowufi.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2jcpceial.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hammf.cn/Article/details/gt2ldihvcro.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cashguo.top/Article/details/gt2jobbjipz.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aegthgsd.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.9152youxi.cn/Article/details/gt2sgfzzjyp.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.haohaochexian.top/Article/details/gt2jwuhiata.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.vqdsnc.cn/Article/details/gt2geueqodm.html

[B07] while 循环
来源：http://dali.gogol.net.cn/Article/details/gt2mbybcgpt.html

Py:   while i < 10: i += 1
来源：http://dali.meibo888.top/Article/details/gt2afgxnpma.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2lizhnxsc.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ztekrzkg.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ssowmsyr.html

Java: while (i < 10) { i++; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2zqdbremx.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.aizwys.cn/Article/details/gt2ebehelgp.html

Ruby: while i < 10; i += 1; end
来源：http://dali.aibaodan.cn/Article/details/gt2iwlkiype.html

C#:   while (i < 10) { i++; }
来源：http://dali.smart0.xyz/Article/details/gt2kahbihuy.html

[B08] do-while（至少执行一次）
来源：http://dali.pengpengdd.cyou/Article/details/gt2nhvceiqy.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yuxming.cn/Article/details/gt2bxakadmf.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.redwolf501.top/Article/details/gt2ptmiherv.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yj20258888.top/Article/details/gt2jnpjcujm.html

TS:   do { i++; } while (i < 10);
来源：http://dali.daxiang520.top/Article/details/gt2fpboexpu.html

Java: do { i++; } while (i < 10);
来源：http://dali.vqdsnc.cn/Article/details/gt2mfeiootr.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xinyue.icu/Article/details/gt2hcntsmgx.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yanxiufei.cn/Article/details/gt2arbujcwk.html

C#:   do { i++; } while (i < 10);
来源：http://dali.chenlongwang.top/Article/details/gt2odgjqqpb.html

[B09] break 与 continue
来源：http://dali.zhongyouzk.top/Article/details/gt2uflihvys.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.gaohongyu789.top/Article/details/gt2arqpxudt.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.316326.xyz/Article/details/gt2cypjwbhm.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.havefunace.top/Article/details/gt2kgusazvt.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.9152youxi.cn/Article/details/gt2ieyvdxfc.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jianghu66.top/Article/details/gt2czcaiuyt.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhixingplan.top/Article/details/gt2ccavbfzz.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sdwikqqu.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sysykeji.top/Article/details/gt2znsgtacq.html

[B10] 遍历同时拿索引
来源：http://dali.pycfn.com/Article/details/gt2flwltgjl.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yuanzhike.top/Article/details/gt2kiehslgz.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.gogol.net.cn/Article/details/gt2lqvpiulr.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jinqigfzy.top/Article/details/gt2ycocxxdi.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shuidangran.top/Article/details/gt2wjebyoge.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jinqigfzy.top/Article/details/gt2dgpklnzm.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.nanxinkj.top/Article/details/gt2kotglkkb.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.cashguo.top/Article/details/gt2szgpdvlt.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2vvngyabk.html

[B11] 生成数字序列 / 区间
来源：http://dali.quarkkingdee.top/Article/details/gt2kmgegroi.html

Py:   list(range(0, 10, 2))
来源：http://dali.sxryk.cn/Article/details/gt2jpylhnel.html

PHP:  range(0, 10, 2);
来源：http://dali.yj202588.top/Article/details/gt2ushwqkzn.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jyoumei.cn/Article/details/gt2wyqcqobg.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.iojbl.cn/Article/details/gt2oukgvdkp.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.ppjwa.cn/Article/details/gt2bpfnhqyl.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.ydzc1.top/Article/details/gt2rhxqmwdl.html

Ruby: (0...10).step(2).to_a
来源：http://dali.quarkkingdee.top/Article/details/gt2aoaecjus.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.chenzaomai.com/Article/details/gt2nzpfgyuo.html

[B12] 跳出多层循环
来源：http://dali.sufxvd.cn/Article/details/gt2shymfcvx.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jiagoushi.top/Article/details/gt2xfplsups.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.mhx1999.top/Article/details/gt2ikaitdre.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.smart0.xyz/Article/details/gt2ioovqtqz.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhongyouzk.top/Article/details/gt2hmldonvt.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.sufxvd.cn/Article/details/gt2xsluqtrv.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.cashguo.top/Article/details/gt2glepyavj.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hysaishi.cn/Article/details/gt2bzwkfyei.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jinghuilouyu.cn/Article/details/gt2schhkhsp.html

[B13] 判断是否为数字
来源：http://dali.mhx1999.top/Article/details/gt2qdetpmfj.html

Py:   isinstance(x, (int, float))
来源：http://dali.xuanzx.com/Article/details/gt2wtrzexyu.html

PHP:  is_numeric($x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2raystcqm.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yueranfly.top/Article/details/gt2tldmztbb.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cucudq.cn/Article/details/gt2syvdiqla.html

Java: x instanceof Number
来源：http://dali.sysykeji.top/Article/details/gt2yycvfegj.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qbwrvqlg.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hammf.cn/Article/details/gt2caebduzt.html

C#:   x is int or double or decimal
来源：http://dali.fengsongda.top/Article/details/gt2qgbcuefq.html

[B14] 判断值是否在集合内
来源：http://dali.zhiwuduotai.top/Article/details/gt2nhabgduv.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hfpthk.cn/Article/details/gt2yuimytpr.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.tanke756.top/Article/details/gt2eutuyrxu.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.daxiang520.top/Article/details/gt2hsypvhbm.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.daxiang520.top/Article/details/gt2ytjzbdhl.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ivvv.top/Article/details/gt2cpfanlbw.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yongpay.top/Article/details/gt2blbjrlcw.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.dashuyun.cn/Article/details/gt2fmsyfroj.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lbilonjk.html

[B15] 布尔运算与取反
来源：http://dali.ydzc1.top/Article/details/gt2jqheicez.html

Py:   a and b or not c
来源：http://dali.haohaochexian.top/Article/details/gt2snryotvg.html

PHP:  $a && $b || !$c
来源：http://dali.jyoumei.cn/Article/details/gt2qoerppyh.html

JS:   a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gt2cjwdvifm.html

TS:   a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gt2mwgybqvd.html

Java: a && b || !c
来源：http://dali.redwolf501.top/Article/details/gt2hjqfgcfb.html

Go:   a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gt2zpyykbqz.html

Ruby: a && b || !c
来源：http://dali.mhx1999.top/Article/details/gt2qbjiebfv.html

C#:   a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gt2owjpmsre.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.havefunace.top/Article/details/gt2qbuefann.html

Py:   if not data: return
来源：http://dali.sysykeji.top/Article/details/gt2jljfhyut.html

PHP:  if (!$data) { return; }
来源：http://dali.zhixingplan.top/Article/details/gt2dpvsruzs.html

JS:   if (!data) return;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2blzhdwqb.html

TS:   if (!data) return;
来源：http://dali.yanxiufei.cn/Article/details/gt2zaxmfhfq.html

Java: if (data == null) return;
来源：http://dali.sufxvd.cn/Article/details/gt2wwerthil.html

Go:   if data == nil { return }
来源：http://dali.quarkkingdee.top/Article/details/gt2rgdomsxz.html

Ruby: return if data.nil?
来源：http://dali.gotoacloud.top/Article/details/gt2ekirredk.html

C#:   if (data == null) return;
来源：http://dali.yueranfly.top/Article/details/gt2czbpefaw.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2ivbihfdf.html

C. 函数与作用域
来源：http://dali.yj20258888.top/Article/details/gt2mpqauzvq.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2ksrfnlob.html

[C01] 定义函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zarlpfjw.html

Py:   def add(a, b): return a + b
来源：http://dali.sufxvd.cn/Article/details/gt2mtmbziim.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.redwolf501.top/Article/details/gt2xfbjtzsr.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gt2jvkxqibn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gt2cclfcsgo.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gt2lcenepni.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.wangdashe.top/Article/details/gt2cxxrkwlq.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yvedp.cn/Article/details/gt2sdrqqikh.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gt2yjdafggt.html

[C02] 默认参数
来源：http://dali.hnxiangtu.top/Article/details/gt2rcudfxbf.html

Py:   def greet(name="World"): return name
来源：http://dali.ybcxt.top/Article/details/gt2qjqcytse.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.nanxinkj.top/Article/details/gt2nowxadvp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jqgfzy.top/Article/details/gt2cctcbvcc.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.dashuyun.cn/Article/details/gt2jigrgodz.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.tanke756.top/Article/details/gt2nrvrtgow.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.c1oappe.top/Article/details/gt2peokfsop.html

Ruby: def greet(name = "World") = name
来源：http://dali.dashuyun.cn/Article/details/gt2lrxwwdzl.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhoulong.xyz/Article/details/gt2lzvkugut.html

[C03] 可变参数
来源：http://dali.wangshuangyany.cn/Article/details/gt2grbnlylc.html

Py:   def total(*args): return sum(args)
来源：http://dali.yangfankeji.com/Article/details/gt2daoeirsy.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.kuanghao11.cn/Article/details/gt2swkjrvsl.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hywenlv.cn/Article/details/gt2tircjkhq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.iojbl.cn/Article/details/gt2qktcbolr.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.fengsongda.top/Article/details/gt2ajbsewej.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.birdmap.top/Article/details/gt2ftdlmmll.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xinyue.icu/Article/details/gt2elgkznqq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.haohaochexian.top/Article/details/gt2mvitoree.html

[C04] 命名参数 / 关键字参数
来源：http://dali.chenjidiqi.icu/Article/details/gt2tedrxkqu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hysaishi.cn/Article/details/gt2nnoyimbx.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cdnleiting.top/Article/details/gt2tfwxgmps.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.bjfxy.top/Article/details/gt2ffvuvymf.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ivvv.top/Article/details/gt2xhlqeoml.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hammf.cn/Article/details/gt2eaoplipn.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtvtmdj.html

Ruby: f(a: 1, b: 2)
来源：http://dali.chenzaomai.com/Article/details/gt2pecncbim.html

C#:   f(a: 1, b: 2)
来源：http://dali.guowangkeji.top/Article/details/gt2ferpolnv.html

[C05] 返回多个值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oqfrfafj.html

Py:   return a, b
来源：http://dali.dianchejie.cn/Article/details/gt2tugzohsn.html

PHP:  return [$a, $b];
来源：http://dali.gaohongyu789.top/Article/details/gt2edbgjtme.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cdnleiting.top/Article/details/gt2ccoyqzfj.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2zmxqkeyi.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.gogol.net.cn/Article/details/gt2mrpsjsji.html

Go:   return a, b
来源：http://dali.wangdashe.top/Article/details/gt2hhtrnntb.html

Ruby: return a, b
来源：http://dali.yvedp.cn/Article/details/gt2mxnbtswy.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ybcxt.top/Article/details/gt2flpicfbf.html

[C06] 匿名函数 / lambda
来源：http://dali.zhengqikj.top/Article/details/gt2ehzfcdyg.html

Py:   square = lambda x: x * x
来源：http://dali.jyoumei.cn/Article/details/gt2duohbkzt.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cucudq.cn/Article/details/gt2ysshtrgh.html

JS:   const square = x => x * x;
来源：http://dali.hnqzz.top/Article/details/gt2xemudxqi.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.chenzaomai.com/Article/details/gt2jfuhhnrm.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tnmzzkjl.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yj20258.top/Article/details/gt2tosezjhk.html

Ruby: square = ->(x) { x * x }
来源：http://dali.pycfn.com/Article/details/gt2yeabfbzo.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.bjfxy.top/Article/details/gt2nuhsdgnj.html

[C07] 把函数作为参数传入
来源：http://dali.gzhubu.top/Article/details/gt2uyvqbdhs.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2nndlimem.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cheryme.top/Article/details/gt2nwcadynb.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hnqzz.top/Article/details/gt2pmnenbgm.html

TS:   arr.map(String)
来源：http://dali.ehwqpu.com/Article/details/gt2jebbqbhn.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gotoacloud.top/Article/details/gt2irdouemz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xylfe.cn/Article/details/gt2ntsiwkzh.html

Ruby: arr.map(&:upcase)
来源：http://dali.quarkkingdee.top/Article/details/gt2jykbpwkb.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jqgufenzy.top/Article/details/gt2hwullcck.html

[C08] 闭包
来源：http://dali.yanxiufei.cn/Article/details/gt2fryuapzi.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jqgufenzy.top/Article/details/gt2rnocupdc.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.kuanghao11.cn/Article/details/gt2fvxmhlwz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2dhtfobdz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.svipenyu.cn/Article/details/gt2piqmunoj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.sxryk.cn/Article/details/gt2ygiofmjk.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.gotoacloud.top/Article/details/gt2ukoyqazv.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.guannengcc.top/Article/details/gt2letllfds.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.mhx1999.top/Article/details/gt2qnrsitjt.html

[C09] 递归
来源：http://dali.sxryk.cn/Article/details/gt2hhorvopa.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.snrcjt.cn/Article/details/gt2qwrifstg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gogol.net.cn/Article/details/gt2rrtvvdio.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yanxiufei.cn/Article/details/gt2zvyutttp.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zycfv.cn/Article/details/gt2jxaajqmo.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jinqigfzy.top/Article/details/gt2dlglvzzm.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shangyingyoupin.top/Article/details/gt2wzjqecqt.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhixingplan.top/Article/details/gt2qjeqhvwr.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ppjwa.cn/Article/details/gt2lhqsuxdi.html

[C10] 变量作用域
来源：http://dali.jinqigufen.top/Article/details/gt2tnialifs.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xuetiantiany.cn/Article/details/gt2cgplaozc.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.quarkkingdee.top/Article/details/gt2psoardvo.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jiagoushi.top/Article/details/gt2pgkcnnuk.html

TS:   同 JS
来源：http://dali.9152youxi.cn/Article/details/gt2rtylqamk.html

Java: 方法内为块级作用域
来源：http://dali.zhixingplan.top/Article/details/gt2dlsdeerr.html

Go:   花括号块级作用域
来源：http://dali.feifeiyinyue.top/Article/details/gt2fvnxgkin.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zycfv.cn/Article/details/gt2ruzmhkxm.html

C#:   块级作用域
来源：http://dali.dianchejie.cn/Article/details/gt2ipwijffk.html

[C11] 模块导入与导出
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uqpglpyi.html

Py:   from module import func
来源：http://dali.ppjwa.cn/Article/details/gt2dlvnanki.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hysaishi.cn/Article/details/gt2ovqznpab.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinqigfzy.top/Article/details/gt2opdaoryn.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ehwqpu.com/Article/details/gt2olzfxfsv.html

Java: import java.util.List;
来源：http://dali.fengsongda.top/Article/details/gt2ftqhvmtn.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cucudq.cn/Article/details/gt2jboufusx.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yueranfly.top/Article/details/gt2dkrvorah.html

C#:   using System.Text;
来源：http://dali.shangyingyoupin.top/Article/details/gt2exhsfeir.html

[C12] 立即执行函数 IIFE
来源：http://dali.0kj1m.cn/Article/details/gt2cbwfcxiu.html

Py:   (lambda: print("run"))()
来源：http://dali.fzhhl.top/Article/details/gt2iggewsuj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xuetiantiany.cn/Article/details/gt2ognkbxup.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xinyue.icu/Article/details/gt2lqykwnjt.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shzxlz.cn/Article/details/gt2fjeixcwl.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yanxiufei.cn/Article/details/gt2nnzidadi.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shangyingyoupin.top/Article/details/gt2hwkhaxsb.html

Ruby: -> { puts "run" }.call
来源：http://dali.haohaochexian.top/Article/details/gt2mitzvsge.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2osxoqibf.html

[C13] 类型声明 / 类型注解
来源：http://dali.ppjwa.cn/Article/details/gt2tqvjwjdv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.havefunace.top/Article/details/gt2tpswntyc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuanzhike.top/Article/details/gt2nnpdhbod.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bfxkjxxk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gt2iwlelnxi.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gt2wycjkxke.html

Go:   func add(a, b int) int
来源：http://dali.yueranfly.top/Article/details/gt2yoszjptn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.svipenyu.cn/Article/details/gt2devvtqnf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gzhubu.top/Article/details/gt2rpiukqqt.html

[C14] 泛型函数
来源：http://dali.tanke756.top/Article/details/gt2mnpjzafl.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hnxiangtu.top/Article/details/gt2wnnvnzbv.html

PHP:  // 无泛型
来源：http://dali.yj20258.top/Article/details/gt2nlfcsfgh.html

JS:   // 无泛型
来源：http://dali.yj20258.top/Article/details/gt2ucfrxkxs.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sweek.top/Article/details/gt2bkfaihtl.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.fzhhl.top/Article/details/gt2vincuuhq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xylfe.cn/Article/details/gt2niodronp.html

Ruby: # 无泛型
来源：http://dali.yj202588.top/Article/details/gt2rejsynlk.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.tian-w.cn/Article/details/gt2ygzcvnkp.html

[C15] 解构 / 展开参数
来源：http://dali.dashuyun.cn/Article/details/gt2kkirpjbl.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.pengpengdd.cyou/Article/details/gt2hkgoidxc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zdqjudy.top/Article/details/gt2ahpafvop.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhengqikj.top/Article/details/gt2fmailmsf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.aizwys.cn/Article/details/gt2qtxvecdt.html

Java: // 无解构
来源：http://dali.hfpthk.cn/Article/details/gt2wofcwbkr.html

Go:   // 无解构
来源：http://dali.jyoumei.cn/Article/details/gt2zwcvejvq.html

Ruby: a, b = pair
来源：http://dali.sxryk.cn/Article/details/gt2ipkeymnf.html

C#:   var (a, b) = pair;
来源：http://dali.daria6918.cn/Article/details/gt2mgbfqcoz.html

[C16] 函数 / 方法重载
来源：http://dali.wangshuangyany.cn/Article/details/gt2gpaeizri.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.smart0.xyz/Article/details/gt2nagiixka.html

PHP:  // 无重载
来源：http://dali.mhx1999.top/Article/details/gt2niazmgcb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.bjfxy.top/Article/details/gt2fiqwrwdi.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yanxiufei.cn/Article/details/gt2orixeedb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ydzc1.top/Article/details/gt2mcffhiav.html

Go:   // 无重载：用不同函数名
来源：http://dali.cheryme.top/Article/details/gt2qcaecryq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.chenjidiqi.icu/Article/details/gt2mzjqfucp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.sxryk.cn/Article/details/gt2srdikcql.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2ztbrgamo.html

D. 数组 / 列表 / 集合
来源：http://dali.yuanzhike.top/Article/details/gt2ltgxecby.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2fphlngrb.html

[D01] 创建数组 / 列表
来源：http://dali.havefunace.top/Article/details/gt2jhpyocar.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.meibo888.top/Article/details/gt2bloswger.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.tanke756.top/Article/details/gt2ghivkytb.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cucudq.cn/Article/details/gt2xkzpxloa.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hongshengwenyu.top/Article/details/gt2oxugowpd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.iojbl.cn/Article/details/gt2sjudmjdh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.wangshuangyany.cn/Article/details/gt2gqbqislb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.pycfn.com/Article/details/gt2pxuxnxri.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sysykeji.top/Article/details/gt2wqrvtfqt.html

[D02] 追加元素到末尾
来源：http://dali.xziqi.cn/Article/details/gt2osqfxvry.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xinyue.icu/Article/details/gt2weofsume.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.pengpengdd.cyou/Article/details/gt2enpsmnug.html

JS:   arr.push(4);
来源：http://dali.svipenyu.cn/Article/details/gt2xrgyklqb.html

TS:   arr.push(4);
来源：http://dali.nwbrower.top/Article/details/gt2zrzjdnml.html

Java: list.add(4);
来源：http://dali.cheryme.top/Article/details/gt2vnzqlhhq.html

Go:   arr = append(arr, 4)
来源：http://dali.shuidangran.top/Article/details/gt2vjqptgxt.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jlsjyb.cn/Article/details/gt2semykjtp.html

C#:   list.Add(4);
来源：http://dali.hywenlv.cn/Article/details/gt2bkciswtt.html

[D03] 在指定位置插入元素
来源：http://dali.yuanzhike.top/Article/details/gt2fwmhckcf.html

Py:   arr.insert(0, 0)
来源：http://dali.daria6918.cn/Article/details/gt2cszaywnw.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hnqzz.top/Article/details/gt2wccdtpow.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yangfankeji.com/Article/details/gt2cxyyyelb.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.pycfn.com/Article/details/gt2umqrqwnf.html

Java: list.add(0, 0);
来源：http://dali.andypj.xyz/Article/details/gt2osxjxxze.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.redwolf501.top/Article/details/gt2eukeneyo.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zycfv.cn/Article/details/gt2yiwgyxtw.html

C#:   list.Insert(0, 0);
来源：http://dali.xziqi.cn/Article/details/gt2mxqjjnvf.html

[D04] 删除元素
来源：http://dali.wangshuangyany.cn/Article/details/gt2wnwlzvwd.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cucudq.cn/Article/details/gt2xpvayuqu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.daria6918.cn/Article/details/gt2jawzfmcn.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.meibo888.top/Article/details/gt2cedfswtn.html

TS:   arr.splice(0, 1);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yalorcgw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.pengpengdd.cyou/Article/details/gt2mjgtqgsn.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shzxlz.cn/Article/details/gt2rpaqfwam.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinqigfzy.top/Article/details/gt2alalkikl.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ehwqpu.com/Article/details/gt2cnnhqbhu.html

[D05] 访问与修改元素
来源：http://dali.tianlin.xyz/Article/details/gt2qtxdjeel.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yuxming.cn/Article/details/gt2gemqezgg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.guannengcc.top/Article/details/gt2yrhrttks.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.meibo888.top/Article/details/gt2yuaegmfc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hfpthk.cn/Article/details/gt2njfygqco.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yj20258.top/Article/details/gt2wdewektv.html


<!-- 参考信息 -->